### [pi](https://pi.dev)

#### Install using Git

Clone the repository to keep the theme up to date with the latest changes:

```bash
git clone https://github.com/dracula/pi-coding-agent.git
```

#### Install manually

Download the [`.zip` archive](https://github.com/dracula/pi-coding-agent/archive/main.zip) from GitHub and extract it to a location of your choice.

#### Activating theme

1. Create the pi themes directory if it doesn't exist:

   ```bash
   mkdir -p ~/.pi/agent/themes
   ```

2. Symlink the theme file into the pi themes directory:

   ```bash
   ln -s /path/to/pi-dracula/dracula.json ~/.pi/agent/themes/dracula.json
   ```

   Replace `/path/to/pi-dracula` with the actual path where you cloned or extracted the theme.

3. Open pi and run `/settings`, then select `dracula` from the theme list.

   Alternatively, open `~/.pi/agent/settings.json` directly and add:

   ```json
   {
     "theme": "dracula"
   }
   ```

4. Restart pi for the changes to take effect.
