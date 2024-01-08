## what is this, you might ask
Well its a bible study tool, assists you to quickly select bible books to go through with pastor Paul Leboutilier.
Find out more info at:<br>**["thru-the-bible website"](https://www.ccontario.com/thru-the-bible)**<br/>
I chose this way rather than the 'easier' way because to me its easier this way because I am geekier you might say, but also because its distraction free.
Think about going to search for a topic and you see something else that draws your attention, then you will set aside the thing that brought you to the platform(say youtube).
Okay enough introduction, let's see how you can start using this very simple way of studying the bible and growing by it

## getting started
Depending on the device you are using, grab the necessary files in the root folder after going through the whole manual and completing the requirements.

For the script to work you need a couple of things installed. 
In a different repository, \`[cyt-dl](https://github.com/Snavens/cyt-dl)\` set it up as this is a requirement for this to work.
All instructions setting up the script `cyt-dl` mentioned in its repo

### GNU LINUX 
Clone this repo and find the folder representing your device, copy file named `bteaching` to path (default local path: `/usr/local/bin`).
From there you are good to go, start by typing:
`bteaching` followed by your options.
Know more by typing:
```
bteaching --help
```

### ANDROID
Install termux if you don't have it,
Here is the link: <https://f-droid.org/repo/com.termux_118.apk>.
Once you have it install and open it up, since its first time use you have to install a couple of commands:
```
apt-get update ; apt-get upgrade < <(yes)
```

Install git and clone this repo:

```
apt install git && git clone https://github.com/Snavens/bteaching
```
Final step is to copy the script to your local path, If you don't have a local path set it up by adding line below to `~/.bashrc`:

export PATH="~/bin:$PATH"

Create local path folder if ! exists

```
mkdir ~/bin
```


copy script to path folder:

```
cp bteaching/Android/bteaching ~/bin
```

### WINDOWS
Adding support soon!

## comments
I presume that incase you encounter an error just submit an issue if you can't find any other help online. The main goal is go with that which suites your style, if this doesn't then try going for the easy way: ["thru-the-bible website"](https://www.ccontario.com/thru-the-bible).

You can choose audio or video depending with your liking.
