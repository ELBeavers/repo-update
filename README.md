# repo-update

A simple tool to update all of the git repositories in a given directory.

## Usage

To run the script, `cd` into the directory and make it executable by typing `chmod +x lipsum.sh`.

Install the binary in your `$PATH`. Move into a directory with a collection of `git` repositories and run the command `repo-update`. It will check each local repository. After it finds the git information, it connects to the VCS and pulls the latest commits.

Personally, I store scripts like this one somewhere on my drive and symlink to a directory in my `$PATH`, usually `/usr/local/bin`, like so:

	ln -s /path/to/lipsum.sh /usr/local/bin/lipsum
