# Hello and welcome to my tutorial!

Today's tutorial is about **How to use the [GitHub CLI](https://cli.github.com) in repl.it!**

Make sure you have:
- a repl
- a terminal (or a bash repl)
that's it.
Stick with me onto this!


## First step, get the .tar.gz file from the GitHub repository
So first we should get the .tar.gz file from the GitHub repo, because we are on a Linux repl!

Type in the terminal:
```sh
wget https://github.com/cli/cli/releases/download/v1.5.0/gh_1.5.0_linux_386.deb
```

Look at your file tree, you'll see the .tar.gz file

## Second step, tar (or unzip whatever you call it) the .tar.gz file

You should extract the tar gz file, because we need to use the executable. Type in the terminal:

```sh
tar -xvf gh_1.5.0_linux_386.tar.gz
```

Now, you'll have a new folder, and in it, you have the `bin` folder, in the next step, you'll know how to use it in the terminal!

## Final and third step, use the executable

Open your new extracted folder, and then open the bin folder, you'll see the `gh` executable file! without any file extensions because we're on Linux!

And now the fun step, type in the terminal:
```sh
./gh_1.5.0_linux_386/bin/gh
```

Then BOOM! The GitHub CLI is running on Repl.it!
Thanks for your time, and have a great day!