git init initializes a directory as a Git repository
To create a repository from an existing directory of files, you can simply run git init in that directory. For example, let's say we have a directory with a few files in it, like this:

$ cd konichiwa
$ ls
README   hello.rb
This is a project where we are writing examples of the "Hello World" program in every language. So far, we just have Ruby, but hey, it's a start. To start version controlling this with Git, we can simply run git init.

$ git init
Initialized empty Git repository in /opt/konichiwa/.git/
Now you can see that there is a .git subdirectory in your project. This is your Git repository where all the data of your project snapshots are stored.

$ ls -a
.        ..       .git     README   hello.rb
Congratulations, you now have a skeleton Git repository and can start snapshotting your project.

In a nutshell, you use git init to make an existing directory of content into a new Git repository. You can do this in any directory at any time, completely locally.
