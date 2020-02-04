# costing-sheets-com
## To Edit Source Code and Work with GIT
1. Use Git Bash
2. `cd ../../Development`
3. `git clone git@github.com:northriverboats/costing-sheets-com.git`
4. `cd costing-sheets-com`

5. Use windows shell
6. `cd \Development\costing-sheets-com`
7. `\Python37\python -m venv .venv`
8. `.venv\Scripts\activate`
9. `python -m pip install pip --upgrade`
10. `pip install -r requirements.txt`
11. Remember to Create New Branch Before Doing Any Work

## Build Executable
`.venv\Scripts\pyinstaller.exe --onefile --windowed --icon options.ico  --name "Costing Sheets for Commercial" "costing-sheet-com.spec" main.py`