### [pi](https://github.com/badlogic/pi-mono)

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
git clone https://github.com/dracula/pi.git
```

#### Install manually

Download using the [GitHub `.zip` download](https://github.com/dracula/pi/archive/main.zip) option and unzip them.

#### Activating theme

1. Create the pi themes directory if it doesn't exist:

   ```bash
   mkdir -p ~/.pi/agent/themes
   ```

2. Symlink the theme file to the pi themes directory:

   ```bash
   ln -s /path/to/pi-dracula/dracula.json ~/.pi/agent/themes/dracula.json
   ```

   Replace `/path/to/pi-dracula` with the actual path where you cloned/downloaded the theme.

3. Open pi in your terminal and type `/settings`, then select the `dracula` theme from the theme list.

   Alternatively, edit your pi settings file (`~/.pi/agent/settings.json`) and set the theme:

   ```json
   {
     "theme": "dracula"
   }
   ```

4. Restart pi
