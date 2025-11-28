# Terminal-Styled Personal Website

An interactive, retro-styled web terminal personal website built with **Vanilla JavaScript** and **Tailwind CSS**.

This project simulates a fully functional Linux terminal in the browser. It is designed to be a unique personal website or portfolio for developers who want to showcase their skills in a geeky way.

## ✨ Features

* **File System Simulation**: Navigate directories (`cd`), list files (`ls`), and read content (`cat`) just like a real OS.
* **Auto-completion**: Press `Tab` to autocomplete commands and filenames.
* **Command History**: Use `Up`/`Down` arrows to cycle through previous commands.
* **Visual Effects**:
    * *Matrix Mode*: A falling code rain effect inspired by *The Matrix*.
    * *Root Mode*: A cyberpunk-themed "superuser" mode with particle explosions, screen glitches, and glowing aesthetics.
    * *CRT Vibes*: Retro fonts (IBM Plex Mono) and terminal styling.
* **Easter Eggs**: Try `sudo su`, `cowsay`, or `neofetch`.
* **Responsive Design**: Includes a mobile detection warning to ensure the best typing experience on desktops.

## 🚀 Live Demo

[Click here to view the Demo](https://lazitech.github.io/Terminal-Styled-Personal-Website)

## 🛠️ Usage

**Available Commands**

| Command | Description |
| :--- | :--- |
| `help` | Show list of available commands |
| `ls` / `cd` / `pwd` | Navigation commands |
| `cat [file]` | Read file contents |
| `contact` | Display contact card |
| `resume` | Display resume summary and PDF link |
| `matrix` | Toggle Matrix visual effect |
| `neofetch` | Show system information |
| `sudo su` | Enter Root/Admin mode (Password: `admin`) |
| `cowsay [msg]` | Make a cow say something |
| `reboot` / `poweroff` | Simulate system power actions |

## ⚙️ Customization

You can easily customize this terminal with your own information without diving deep into the code.

1.  Open `index.html`.
2.  Locate the **Configuration Area** at the top of the script section:

```javascript
// --- CONFIGURATION AREA ---
const CONFIG = {
    username: 'guest',
    hostname: 'portfolio',
    adminPassword: 'admin', // Password for 'sudo su'
    name: 'Alex Developer',
    email: 'alex@example.com',
    github: '[https://github.com/your-username](https://github.com/your-username)',
    linkedin: '[https://linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)',
    resumeUrl: '#' // Link to your PDF resume
};
```

## 🤗Acknowledgements

Gemini 3 Pro wrote 100% of the code, I wrote 100% of the prompt.