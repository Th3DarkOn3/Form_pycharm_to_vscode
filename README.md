# VSCode Python Project Settings

This guide is useful for anyone switching from PyCharm to VSCode.

### Steps to set up:

1. Create a Python virtual environment in your project folder:
   ```bash
   python -m venv .venv
   ```

2. Create a `.vscode` folder in the root of your project:
   ```bash
   mkdir .vscode
   ```

3. Copy the `settings.json` file from this repository into the `.vscode` folder.

### NB: If you're using Linux or macOS, you need to modify line 2 of the settings.json file by replacing the existing path with:
```
./.venv/bin/python
```

### Essential extensions

- Python (Microsoft)
- Python Debugger (Microsoft)
- Pylance (Microsoft)
  
### Recommended Extensions

- Python Indent (Kevin rose)
- Prettier - Code formatter (Prettier)

That’s it! Your VSCode project is now configured.
