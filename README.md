# git-gone
Frequently when leaving the office in a rush, I forget to push any local changes to the remote. When I pick up my work from another computer, I realise too late that I didn't push my work. This tool provides the bash functions `leave` and `begone` to shutdown the computer after synchronising any visited git repositories. To avoid making unwanted commits, it pushes to a remote "git-gone" branch by default.

Ignore repositories with `.git-gone-ignore` in the root directory.
