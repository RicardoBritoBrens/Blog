# How to install MkDocs on mac OS

## Requirements

- Homebrew (If you don't have install check my post about it Go)
- Python version 3.5 or further.
- MkDocs

---

## Principles that matters

## The principle of least surprise suggests that each feature of our application **Should behave in a way that most users will expect it to behave**

Author: ¿?

---

## Remove username from mac os terminal

## Step 0 - Open your file manager

## Step 1 - Navigate to your user folder and hit

In your file manager press Ctrl + H to show hidden files.

Open the “.bashrc” file in a text editor.

file-manager-bashrc-file 3. Find the line that starts with PS1=. The complete line should be something like this: PS1='[\u@\h \W]\$ ' where \u represents the username, \h the hostname and \W your location in the file structure.

bashrc-ps1-line 4. To remove the username and hostname from the prompt, simply remove the \u@\h part so it looks like this: PS1='[\W]\$ '.

terminal-prompt-no-username-hostname 5. For pure minimalism, you can remove everything and just leave the prompt sign: PS1='\$ '.

terminal-prompt-removed-everything 6. Once you are done with the edit, save the file.

Now relaunch your terminal, and the changes will be reflected immediately. If you are not able to restart the terminal because of a running session, type source ~/.bashrc instead.

Within ~/.zshrc

Uncomment the following line to disable auto-setting terminal title.

DISABLE_AUTO_TITLE="true"

---
