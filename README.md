# Install Cursor AI on Ubuntu

This is a simple script that is going to install Cursor AI on Ubuntu and integrate it to the menu system.

- Download the install-cursor.sh file
- Add execute permissions: **chmod +x install-cursor.sh**
- Run it **./install-cursor.sh**

Everything is going to be set automatically.

Notes: you may have to install Fuse

If you get this error:

```markdown
dlopen(): error loading libfuse.so.2

AppImages require FUSE to run.

Just install the library:

```

```bash
sudo apt update
sudo apt install libfuse2
```
