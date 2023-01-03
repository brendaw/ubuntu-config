# Ubuntu Config

**Ubuntu Config** is a basic checklist I follow to set up a new Ubuntu development environment. It gets me up to speed with Git, Java, Deno, Apps and more so I can more quickly get back to coding. Hugely inspired in the [@mdo's same structure](https://github.com/mdo/config).

## Checklist

### 1. Prep Ubuntu

- Update and upgrade the system with the good 'ol command mantra: `sudo apt update && apt upgrade -y`

**Accept any thing that is beyond -y arg auto allowance.**

### 2. Prep Terminal

- First of all, install build-essential, git, zsh, vim, curl and net-tools.
- Change `/etc/passwd` shell to use `/bin/zsh`.
- Clone and install the dotfiles project.
- Add custom padding into terminal.
- Add transparency into terminal profile.
- Generate news ssh keys and update it elsewhere (GitHub, GitLab, and so on).

### 3. Setup Deno

- Install deno via curl: `curl -fsSL https://deno.land/x/install/install.sh | sh`.
- Ensure DENO_INSTALL is set and loaded into PATH.

### 4. Setup VS Codium

- Install Visual Studio Codium.
- Install VS Code.

### 4. Install programs

- Install Firefox and Chromium browsers.
- Install draw.io and yEd diagram apps.
- Install Inkscape and Gimp graphic apps.

### 4. Additional dependencies

- Install node via apt: `sudo apt install node -y`.
- Install Ruby via apt: `sudo apt install ruby -y`.

### 7. Customize things
- 
- Add params `--enable-features=WebUIDarkMode --force-dark-mode` on every Exec instruction on its launcher and reload application.
- Install Ad Blocker in Firefox and Chromium. Please.

### Config iPad as a second monitor

- Run `gsettings set org.gnome.desktop.remote-desktop.rdp screen-share-mode extend` to enable screen extend when on RDP.
- Enable RDP on Sharing settings.
- Ensure iPad has the Microsoft RDP app to access the machine.
- Access the computer from iPAD using local IP.

## Use it yourself

Fork this repo, or just copy-paste things you need, and make it your own. **Please be sure to change your `.gitconfig` name and email address though!**

## Works on my machine

Yup, it does. Hopefully it does on yours as well, but please don't hate me if it doesn't.

<3
