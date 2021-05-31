Review the code of all PRs before triggering the bot on them.
Be gentle; try not to run mass rebuilds or massive builds (like Chromium) on it.
Automatic Building
All users will have their PRs automatically trigger builds if their commits follow the well-defined format of Nixpkgs. Specifically: prefixing the commit title with the package attribute. This includes package bumps as well as other changes.

Example commit titles and the builds they will start:

Message	Automatic Build
vim: 1.0.0 -> 2.0.0	vim
vagrant: Fix dependencies for version 2.0.2	vagrant
python36Packages.requests,python27Packages.requests: 1.0.0 -> 2.0.0	python36Packages.requests, python27Packages.requests
python{2,3}Packages.requests: 1.0.0 -> 2.0.0	nothing
When opening a PR with multiple commits, ofborg creates a single build job for all detected packages. If multiple commits get pushed to a PR one-by-one, each detected package will get a separate build job.

If the title of a PR begins with WIP:, contains [WIP] anywhere, or has the 2.status: work-in-progress label, its packages are not built automatically. Note: Marking a PR as a draft does not prevent automatic builds.

Commands
The comment parser is line-based, so commentary can be interwoven with instructions for ofborg.

To trigger the bot, the line must start with @ofborg (case insensitive).
Note: GitHub will not suggest @ofborg to you, but it will work all the same. When in doubt, preview your comment and verify that @ofborg links to https://github.com/ofborg/.
To use multiple commands, separate them with whitespace. For examples, see the "Multiple Commands" section.
