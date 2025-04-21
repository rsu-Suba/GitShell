## Simple Git-like Shell Tool

#### 🛠 Purpose
This shell script helps track and back up edits to the `src` directory.

#### 🚀 How to Use
1. Run the script at the start **and** end of your editing session.
2. If you made any changes, you'll be asked to enter a commit message when ending.
3. The script automatically backs up edited files.

#### 🧰 Options
- `-l` : Show who is currently logged in.
- `-s` : Check if you are currently working.

#### 📁 Directory Structure
- Make sure following directory structure be like:<br>
MainDir/<br>
├── gitsh<br>
└── src/<br>
- `./MainDir/backups` : Stores backups of edited files automatically.
- `./MainDir/logs` : Stores logs of login/logout events, commit messages, and full paths of edited files.
