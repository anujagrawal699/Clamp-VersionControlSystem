## Description

Clamp is a git alternative at a very small scale, implemented using file system and other npm packages of javascript. Is is a versatile command-line tool designed to streamline and enhance your version control workflow. Built with simplicity and efficiency in mind, Clamp offers a suite of commands that cater to various version control needs. Clamp is designed to be intuitive and easy to use, whether you're a seasoned developer or just starting out. Its straightforward syntax and powerful features make it an indispensable tool for managing your version control workflow efficiently.

## Features

- Add Files: Easily stage files for commit with the add command. This feature allows you to specify one or more files that you wish to include in your next commit, making it straightforward to manage your changes.

- Commit Changes: Securely save your changes to the repository with the commit command. This feature enables you to provide a descriptive message for the changes you're committing, ensuring a clear history of your project's evolution.

- View Commit Logs: Keep track of your project's history with the log command. This feature presents a chronological log of commits, allowing you to review the project's development over time.

- Show Commit Differences: Inspect the changes introduced in specific commits with the show command. By specifying a commit hash, you can view the differences introduced by that commit, aiding in code review and history exploration.

## Installation

To install GitCloneClamp, follow these steps:

1. Clone the repository: `git clone https://github.com/your-username/GitCloneClamp.git`
2. Navigate to the project directory: `cd GitCloneClamp`
3. Install the dependencies: `npm install`

After cloning the repository, please delete the `.clamp` folder to initialize a new version tracking.

## Usage

To use Clamp, run the following commands using Node.js:

- Initialize a new GitCloneClamp project: `node Clamp.mjs init`
- Add a file to the project: `node Clamp.mjs add <file>`

Replace `<file>` with the name of the file you want to add.

- Commit the changes: `node Clamp.mjs commit <message>`
- See the commit logs: `node Clamp.mjs log`
- View the changes done in specific commit: `node Clamp.mjs show <commitHash>`

Here is terminal screenshot of the commands:

![image](https://github.com/anujagrawal699/Clamp-VersionControlSystem/assets/121146661/0414ae1f-8c5b-4526-9e46-87fd130a5a1f)



## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please open an issue or submit a pull request.



