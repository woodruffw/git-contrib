git-contrib
==========

# MIGRATED

I will no longer be making changes to this repository. The current code has
been migrated to my [snippets](http://woodruffw.us/snippets.html) and the
[corresponding repo](https://github.com/woodruffw/snippets).

`git-contrib` is a neat little script for creating CONTRIBUTORS files for git repositories.

It can currently generate Markdown (GitHub-flavored), CSV, and plain text files using git's logging facilities.


## Installation and Usage:
First, clone the reposity or download the `git-contrib.rb` file otherwise.
```bash
$ git clone https://github.com/woodruffw/git-contrib.git
```

Place the `git-contrib.rb` file somewhere in your `$PATH`, removing the ".rb" if you don't want the suffix.

Then, just execute it in your git repository/repositories:

```bash
git contrib.rb # generate plain-text CONTRIBUTORS
git contrib.rb --markdown # generate CONTRIBUTORS.md
git contrib.rb --csv # generate CONTRIBUTORS.csv
```

## Examples
See [CONTRIBUTORS.md](CONTRIBUTORS.md), [CONTRIBUTORS.csv](CONTRIBUTORS.csv), and plain old [CONTRIBUTORS](CONTRIBUTORS)
