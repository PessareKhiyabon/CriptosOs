# What The CriptosOs ?
It Is A Terminal Script That Is Used In The Field Of Hacking And Security. This Tool Is A Completely Separate And Relatively Professional Terminal That Has Many Features. You Can Use This Script To Perform All Kinds Of Scans, Detections, And Attacks. It Can Be Used In Both Online And Offline Modes, You Can Also See Other Features Of This Script In The Rest Of This Article, It's A Fun Time :)!

## Features
Script Features Are Always Being Updated, So New Features Are Added In Each Version !!

- [x] DnsLookUp
- [x] ScanPorts
- [x] CVE-Enum
- [x] SubDomain-Enum
- [x] CVE-Exploit
- [x] TeleGram Osint
- [x] Scan Site With Telegram Robot 
- [x] Reverse DNS
- [x] Reverse IP
- [x] Complete!
- [x] Complete!
- [x] Complete!








# Installing And Usage !

Markdown-Diff annotates word [diff][]s of [Markdown][] documents for easier review.
It reformats the output of [`wdiff`][] or `git --word-diff` in Markdown, so the changes to a Markdown document can be viewed inline.
It can also summarize commit history of Markdown documents in a Git repository as well as the changes made to them.

[Markdown]: https://en.wikipedia.org/wiki/Markdown
[diff]: https://en.wikipedia.org/wiki/Diff
[`wdiff`]: http://www.gnu.org/software/wdiff/ 


## Usage

### Download and Install the Scripts

* [markdown-format-wdiff](https://raw.github.com/netj/markdown-diff/master/markdown-format-wdiff)
* [markdown-git-changes](https://raw.github.com/netj/markdown-diff/master/markdown-git-changes)

Mark them as executable and put them in a directory that's on your `$PATH`, e.g., `~/bin/` or `/usr/local/bin/`, as shown in the following list of commands:

```bash
curl -RL \
     -O https://raw.github.com/netj/markdown-diff/master/markdown-format-wdiff \
     -O https://raw.github.com/netj/markdown-diff/master/markdown-git-changes
chmod +x markdown-format-wdiff markdown-git-changes
mkdir -p ~/bin
mv -f markdown-format-wdiff markdown-git-changes ~/bin/
export PATH=~/bin:"$PATH"
```

### Use with GNU wdiff

```bash
wdiff old.md new.md | markdown-format-wdiff >changes.md
```

### Use with Git

```bash
markdown-git-changes origin/master README.md >changes.md
```

### View the Output

```bash
# use a Markdown preview app, such as Marked
open changes.md

# or, compile it into HTML and view with your web browser
npm -g install marked
marked changes.md >changes.html
open changes.html
```



----



