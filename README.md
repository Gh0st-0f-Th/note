note

A minimalist terminal-based note-taking tool written in Bash.
Lightweight, dependency-free, and designed for fast CLI-based logging.

---

Features

- Save timestamped notes quickly
- View all notes or with line numbers
- Search notes by keyword
- Delete specific notes by line number
- Delete all notes
- Fully uninstall the tool (cleans files and aliases)

---

Installation

1. Clone the repository:

   git clone https://github.com/Gh0st-0f-Th/note.git
   cd note

2. Run the installer:

   bash install

3. Reload your terminal config:

   source ~/.bashrc  # or source ~/.zshrc

---

Getting Started

Once installed, run:

   note -h

to see the help menu with all available commands.

---

Example Usage

note "Remember to read man pages"

note -v

note -s 'man'

note -3d

---

License

MIT License

---

Author

Gh0st-0f-Th (https://github.com/Gh0st-0f-Th)
