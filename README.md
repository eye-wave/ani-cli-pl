<div align="center">

![Static Badge](https://img.shields.io/badge/linux-gray?style=for-the-badge&logo=linux&logoColor=fff&label=os&color=darklime)
![Static Badge](https://img.shields.io/badge/android-gray?style=for-the-badge&logo=android&logoColor=fff&label=os&color=darklime)

![Static Badge](https://img.shields.io/badge/bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=fff)
![Static Badge](https://img.shields.io/github/license/eye-wave/ani-cli-pl?style=for-the-badge)
![Static Badge](https://img.shields.io/github/languages/code-size/eye-wave/ani-cli-pl?style=for-the-badge)

# ani-cli-pl
</div>


Cli tool to watch anime with polish subtitles mainly from [shinden.pl](https://shinden.pl).

Written in Bourne shell for wider compatability with various operating systems.

### Getting Started

Install required dependencies:
```
curl fzf grep gunzip gzip md5sum sed
```

Download the script
```bash
curl https://raw.githubusercontent.com/eye-wave/ani-cli-pl/main/ani-cli-pl -o ~/.local/bin/ani-cli-pl
chmod +x ~/.local/bin/ani-cli-pl
```

and run it
```
ani-cli-pl
```

To uninstall simply run the following
```
rm ~/.local/bin/ani-cli-pl
```

### Todo
- [x] Better closing with <kbd>Ctrl</kbd>+<kbd>C</kbd>
- [ ] Better caching
- [ ] Cli flags
- [ ] Help menu
- [ ] Test compatibility on Windows with Git Bash
