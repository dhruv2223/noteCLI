# 📝 noteCLI

## Description

NoteCLI is a simple and efficient command-line interface (CLI) application for managing your notes. Designed for developers and power users who prefer the speed and flexibility of the terminal, NoteCLI allows you to quickly create, view, and organize your notes without leaving your command-line environment.

## Why

In the age of graphical note-taking applications, many developers find it tedious to switch contexts between their terminal and other tools. NoteCLI was created to streamline the note-taking process for those who live in their terminal. Whether you're jotting down a quick idea, documenting a command, or organizing your to-do list, NoteCLI offers a no-frills, terminal-native solution to help you stay productive.

## 🚀 Quick Start

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/dhruv2223/noteCLI.git
   cd noteCLI
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Link the project globally:
   ```bash
   npm link
   ```
4. Run NoteCLI using the `note` command:
   ```bash
   note <command>
   ```

## 📖 Usage

### Available Commands

- `new <note>`: Create a new note.

  ```bash
  note new "The content of the note" --tags tag1,tag2
  ```

  **Options:**

  - `--tags, -t`: Tags to add to the note, separated by commas.

- `all`: Get all notes.

  ```bash
  note all
  ```

- `find <filter>`: Get matching notes.

  ```bash
  note find "search term"
  ```

  **Positional Arguments:**

  - `filter`: The search term to filter notes by, applied to `note.content`.

- `remove <id>`: Remove a note by ID.

  ```bash
  note remove 1
  ```

  **Positional Arguments:**

  - `id`: The ID of the note to remove.

- `clean`: Remove all notes.

  ```bash
  note clean
  ```

- `--help`: Display help information for the `note` command.

  ```bash
  note --help
  ```

### Examples

Add a new note with tags:

```bash
note new "Meeting Notes" --tags work,project
```

View all notes:

```bash
note all
```

Find notes containing a specific term:

```bash
note find "Meeting"
```

Remove a note by ID:

```bash
note remove 2
```

Remove all notes:

```bash
note clean
```

Get help information:

```bash
note --help
```

## 🤝 Contributing

### Clone the repo

```bash
git clone https://github.com/dhruv2223/noteCLI.git
cd noteCLI
```

### Build the project

This project is written in Node.js. Ensure you have Node.js 14+ installed.

### Link the project globally

Run the following command to make the `note` command globally available:

```bash
npm link
```

### Run the project

```bash
note <command>
```

### Submit a pull request

If you'd like to contribute, please fork the repository and open a pull request to the `main` branch.

---

Feel free to suggest any features or report bugs by opening an issue on GitHub!
