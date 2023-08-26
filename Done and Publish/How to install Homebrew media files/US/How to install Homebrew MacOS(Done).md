# How to install Home

## What is Homebrew

According to the official site Homebrew is all you need that Apple does not install by default.

I think Apple should consider to include this by default as an optional setup step when you buy a new computer.

Let's begin...

## Step 0 - Download Homebrew

- Open the your default terminal, for this I will use the one that come by default which is [zsh](https://ohmyz.sh/) since the release of macOS Catalina on october 7 2019.

You can find it into the application folder as `Terminal.app`

![Terminal.app](https://macreports.com/wp-content/uploads/2019/05/terminal-app-icon.png)

This is the default icon of the app.

- Copy and paste the following text, hit enter and wait for the download to complete.

```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)
```

## Step 1 - Check you version

After that run the following to validate you the result

```bat
 brew -v
```

or

```bat
 brew --version
```

Then you should see something like this on the terminal

![brew version](https://github.com/RicardoBritoBrens/Blog/blob/main/How%20to%20install%20Homebrew%20media%20files/brew%20version%20command.png?raw=true)

## Step 2 - Downloading packages

To download new packages you can use the following structure command

brew install + `package name`

Example:

```bat
 brew install discord
```

Then you should see something like this on your terminal

![brew install command progress](https://github.com/RicardoBritoBrens/Blog/blob/main/How%20to%20install%20Homebrew%20media%20files/brew%20install%20command%20progress.png?raw=true)

![brew install command finish](https://github.com/RicardoBritoBrens/Blog/blob/main/How%20to%20install%20Homebrew%20media%20files/brew%20install%20command%20finish.png?raw=true)

That's it you are done!!!

## Extra

In case you need to remove package you use the following brew command

```bat
 brew remove discord
```

![brew remove command](https://github.com/RicardoBritoBrens/Blog/blob/main/How%20to%20install%20Homebrew%20media%20files/brew%20remove%20command.png?raw=true)

That is all for now I hope this can help you like it does for my.

For a complete reference take a look at the official documentation [Here](https://brew.sh/index_es)
