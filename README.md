# zettel

A script to create zettel for the zettelkasten note-taking system

This is my personal script to get a little automation going, please read the script before you execute it!
It will be work in progress from now on, if you don't understand what it does, ask me or try to look it up online, it's pretty straight forward.

## The script

### My thoughts of doing the zettelkasten note-taking system
Since I am not going to use any images within my zettel notes, I am skipping to have a folder for each note and therefor also won't hit the GitHub file limits in any way. There's a possible 365 daily folders that you could create and within that whatever amount of zettel notes you might like.

You can change that behaviour for yourself at any time within the script.

### GitHub usage
I prefer to have a commit and push after each saved zettel note so I don't have to take care of that myself.

### VIM usage
After a zettel note is created it will open the respective zettel within VIM so I can go ahead and edit it right away.

## Usage

You can symlink or copy it to your /usr/local/bin folder or whatever you prefer (e.g. running it from a more specific folder)
I personally like to have it globally available.

```bash
# zettel "<headline for your zettel>"
zettel "This is my recognizable headline"
```

This will currently create a folder with the date of the day executing it, then it will go ahead an create a an Markdown file with your title and the filename as a quote.
The filename itself gets put together from the current date and time so you basically have a unique filename.

It will look somewhat like this.

```bash
➜ tree
.
├── 20220515
│   ├── 20220515102051.md
│   ├── 20220515102554.md
│   ├── 20220515104541.md
│   ├── 20220515105145.md
│   ├── 20220515112508.md
│   ├── 20220515120139.md
│   ├── 20220515121249.md
│   ├── 20220515122152.md
│   └── 20220515132402.md
└── README.md

1 directory, 10 files
```

## Credits / Recognition

The main idea came from the 2022 SKILSTACK Beginner boost by [@rwxrob](https://github.com/rwxrob).
All credits to him. Thank you for your inspirational personality.

You can check out his channels here:
https://www.youtube.com/watch?v=T2D3uO3oEM8 (2022 SKILSTACK Beginner boost - Week 1)

https://www.twitch.tv/rwxrob
https://www.youtube.com/c/rwxrob

