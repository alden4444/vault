# vault
Lightweight encryption software for Google Drive folders shared between different people


# Instructions:

**Step 1: Share the Vault Folder with Linux**
  - Open the Chromebook Files app.
  - Go to Google Drive -> My Drive.
  - Right-click the shared Vault folder and select 'Share with Linux'.
  
**Step 2: Terminal Installer**
  - Copy setup.txt (in repository)
  - Paste and run in ChromeOS terminal

# Guidelines:
- No Concurrent Live Editing: This framework does not support Google Docs-style real-time collaborative editing. If two users unlock the vault and write changes to the exact same file simultaneously, Google Drive will split the updates into a conflicted version block. Treat it like an archive library—one person edits documents at a time.
- Commit Your Workspace Quickly: Do not leave the vault open in the background indefinitely. Once your updates are finalized, input the password to close it immediately. This ensures the rest of your family always downloads the absolute newest iteration of the data block.
- Accidental Deletion Recovery: If a file is accidentally dropped or modified incorrectly, navigate to Google Drive via your web browser, right-click confidential.zip, select File information -> Manage versions, and restore a clean past version state.
