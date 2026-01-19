Secure Credential Storage System

Technical Stack:

Python with MySQL backend

AES encryption via PyCryptodome

Master password authentication

Rich CLI interface

Security Features:

Encrypted password storage in MySQL database

Master password protection with confirmation

Hidden password display in listings

Clipboard integration for secure password copying

Duplicate entry prevention

Key Commands:
bashpython config.py make          # Initial setup with master password

python pm.py add -s <site> -u <url> -e <email> -l <username>

python pm.py e                 # List all entries (passwords hidden)

python pm.py e -s <entry>      # View specific entry

python pm.py e -s <entry> --copy  # Copy password to clipboard

Use Case: Centralized credential management for individuals and organizations requiring secure password storage
