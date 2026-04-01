# 🧩 mcp-unify - One endpoint for all MCP servers

[![Download mcp-unify](https://img.shields.io/badge/Download%20mcp--unify-purple?style=for-the-badge&logo=github)](https://github.com/Zanegreyamylnitrate785/mcp-unify/releases)

## 🚀 What mcp-unify does

mcp-unify helps you connect to multiple MCP servers through one place. Instead of opening many tools and managing each one on its own, you can use one endpoint and keep things simple.

It is built for people who want:
- one clean way to reach several MCP servers
- less setup work
- better control over which tools show up
- automatic cleanup when a server is no longer needed
- Python `@tool` plugins for custom actions

## 📦 Download mcp-unify

Go to the release page and download the Windows version:

https://github.com/Zanegreyamylnitrate785/mcp-unify/releases

If you see a `.exe` file, download it and run this file. If you see a `.zip` file, download it, then unpack it before you start.

## 🖥️ Windows setup

Use a Windows 10 or Windows 11 PC. A newer system works best.

You also need:
- a stable internet connection
- at least 200 MB of free disk space
- permission to run downloaded apps
- access to your MCP server details, if you already use other MCP servers

## 🔧 How to install

1. Open the release page.
2. Download the Windows file.
3. If the file is zipped, right-click it and choose Extract All.
4. Open the extracted folder.
5. Double-click the app file or installer.
6. If Windows asks for permission, choose Run or Yes.
7. Follow the setup prompts on screen.

## 🧭 First run

When you start mcp-unify for the first time, it will create its local files and prepare the main endpoint.

If you already have MCP servers, you can add them right away. If not, you can still open the app and set things up later.

## ⚙️ How it works

mcp-unify sits between your app and your MCP servers. Your app connects to mcp-unify, and mcp-unify passes requests to the right server.

This gives you:
- one endpoint instead of many
- lazy loading, so servers start only when needed
- auto-cleanup, so unused servers do not stay open
- role-based filtering, so users only see the tools they should use
- support for Python `@tool` plugins, so you can add custom tools

## 🧱 Typical use cases

Use mcp-unify if you want to:
- connect Claude or another AI tool to several MCP servers
- keep tool access in one place
- reduce clutter in your setup
- load tools only when they are needed
- separate tools by role or user type
- add your own Python tools without changing the main setup

## 🧰 Basic setup steps

1. Start mcp-unify.
2. Open the config screen or config file.
3. Add the MCP servers you want to use.
4. Give each server a clear name.
5. Save your settings.
6. Connect your AI app or client to the mcp-unify endpoint.
7. Test one tool from each server.

## 🔌 Adding MCP servers

You can point mcp-unify at several MCP servers at once. Use simple names that help you remember what each one does.

Example server types:
- file tools
- note tools
- search tools
- database tools
- custom internal tools

Keep the list short at first. Add more servers after you confirm the first ones work.

## 🧠 Lazy loading

Lazy loading means mcp-unify waits to start a server until you use it.

This helps you:
- save memory
- reduce startup time
- keep your system lighter
- avoid running tools you do not need yet

For an end user, this means less waiting and fewer apps running in the background.

## 🧹 Auto-cleanup

When a server stays unused, mcp-unify can shut it down on its own.

This helps keep your setup tidy and reduces clutter. It also makes it easier to run several servers without leaving them open all the time.

## 🛡️ Role-based filtering

Role-based filtering lets you show different tools to different users or app roles.

This is useful when:
- one person should see only safe tools
- a team needs different access levels
- you want to hide admin tools from normal use
- you want a clean tool list in your AI app

## 🧩 Python `@tool` plugins

mcp-unify can load Python plugins that use `@tool`.

Use this when you want to add custom actions such as:
- quick file helpers
- simple text tools
- internal office tasks
- project-specific actions

If you are not using Python plugins, you can skip this part and still use the core app.

## 🗂️ Recommended folder layout

A simple setup can look like this:

- `mcp-unify`
- `servers`
- `plugins`
- `config`

Keep your files in one place so you can find them later. This helps if you add more MCP servers or change your settings.

## 🧪 Quick test

After setup, test the connection with one tool first.

1. Open your AI app or client.
2. Connect it to the mcp-unify endpoint.
3. Ask it to use one tool.
4. Check that the right server starts.
5. Confirm the result looks correct.

If that works, add the rest of your servers one by one.

## 🧩 Common tasks

### Add a new server
- Open your config
- Add the server address or command
- Save
- Restart mcp-unify if needed

### Remove a server
- Open your config
- Delete the server entry
- Save
- Refresh or restart

### Add a Python plugin
- Put the plugin file in the plugin folder
- Use `@tool` in your Python file
- Restart mcp-unify
- Check that the new tool appears

### Limit what users see
- Open role settings
- Match tools to a role
- Save the rules
- Test with the target role

## 🪟 Windows tips

If Windows blocks the file:
- right-click the file
- choose Properties
- look for an Unblock box if it appears
- apply the change
- run the file again

If SmartScreen appears:
- choose More info
- then choose Run anyway if you trust the source

## 🧾 Topics

This project relates to:
- AI tools
- Claude
- gateway
- LLM
- MCP
- MCP server
- model context protocol
- plugin
- Python

## 📋 What to expect after setup

Once mcp-unify is running, you should have:
- one main endpoint for several servers
- a cleaner tool list
- less manual switching
- control over when tools start
- a simple way to add custom Python tools

## 🛠️ Simple troubleshooting

If the app does not start:
- download the file again
- make sure the download finished
- try running it as an administrator
- check that your antivirus did not block it

If a server does not show up:
- check the server name
- check the address or command
- save the config again
- restart the app

If your AI app cannot connect:
- confirm the endpoint is correct
- make sure mcp-unify is running
- check your firewall settings
- test with one server before adding more

## 📥 Download and install

Visit the release page and download the Windows file:

https://github.com/Zanegreyamylnitrate785/mcp-unify/releases

If the download is a setup file, open it and follow the steps on screen. If it is a zip file, extract it first, then open the app inside the folder

## 🔍 Before you begin

Make sure you know:
- which MCP servers you want to use
- whether you need all tools or only some
- if you want role-based access
- whether you want to use Python plugins now or later

## 🧭 Best first setup

If you are new to MCP tools, start small:
1. Install mcp-unify
2. Add one server
3. Connect one AI app
4. Test one tool
5. Add the next server after that

This keeps setup clear and makes it easier to spot problems

## 🧰 File types you may see

You may see one of these:
- `.exe` — run this file
- `.zip` — extract it first
- `.msi` — open it to start setup

Use the file type that matches the release you download