# TROUBLESHOOTING

## I can't find my folder

Go back to GitHub Desktop and look at the project you cloned. The **Local Path** is the location of your Realtor Brain folder on your computer.

## Claude Code can't see the folder

Make sure you are in the Claude desktop app's **Code** tab (the part of the app that works with folders on your computer), then **Local**, then **Select folder**. Choose the same Realtor Brain folder you opened in Obsidian and GitHub Desktop.

Official help: https://code.claude.com/docs/en/desktop-quickstart

## I don't see new notes in Obsidian

Make sure Claude actually finished the update, then return to Obsidian and look in the file list on the left side of the Obsidian window for new or changed notes. If you still are not sure, check GitHub Desktop's **Changes** tab (the list of files that changed) to see whether files changed.

## GitHub Desktop shows changes. What does that mean?

It means files in your Realtor Brain folder were changed but you have not saved a version of those changes in GitHub Desktop yet.

Use:

1. **Summary** (the box where you briefly describe this save)
2. **Commit to [branch name]** (**commit** means save this version on your computer; **branch** means the current line of work for this project)
3. **Push origin** (**origin** means the GitHub copy connected to this project)

## "Push origin" isn't available or is grayed out

Usually that means one of these:

- you have not committed yet
- there are no new committed changes to send
- GitHub Desktop is still waiting for an earlier step to finish

First check whether you already clicked **Commit to [branch name]**.

## Claude asks something I don't understand

Answer in plain English as best you can, or say:

- "Can you ask that in a simpler way?"
- "Can you give me an example?"
- "I don't know yet — what would be helpful here?"

This brain is supposed to adapt to you.

## I accidentally changed a file

Do not panic. First, look at the file in Obsidian or GitHub Desktop and confirm what changed. If needed, ask Claude to help fix it in plain English.

Example:

> I accidentally changed something in my brain. Please help me put it back in a cleaner way.

## I want Claude to change the brain structure

Just ask in normal language.

Examples:

- "Please reorganize this around investor work."
- "I want fewer folders and simpler note groups."
- "Please make this better for listing clients."

## I don't know if something was saved

Check GitHub Desktop:

- If the file is still listed in **Changes**, it has not been committed yet
- If you committed but did not push, it is saved locally but not yet on GitHub
- If you committed and pushed, it is saved locally and sent to GitHub

Previous: **[06-SAVE-AND-BACKUP.md](06-SAVE-AND-BACKUP.md)** | Next: **[PRIVACY.md](PRIVACY.md)**
