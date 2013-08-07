Bitsoftly Web Page
===================
bitsoftly.github.io
-------------------
To visit our page simply got to [www.bitsoftly.com](http://www.bitsoftly.com).

## Technologies we used

* **Jekyll** - static web page generator
* **Porto Template** - template repository
* **Twitter Bootstrap** - CSS Framework
* **GitHub** - Git repository
* **GitHub Pages** - web server with automatic statitc web page generator

## GitHub Pages

GitHub Pages is the placeholder of our website.
Thanks to the Git, GitHub and GitHub Pages:

- we don't care if a bad rm command accidentally deletes production files:
 
  ![alt text](http://i.imgur.com/Gf03RPe.gif "we don't care if a bad rm command accidentally deletes production files")

- cooperation, bug fixing and updating is fast as F1 pitstop:
 
  ![alt text](http://i.imgur.com/BPKQ2hX.gif "cooperation, bug fixing and updating is fast as F1 pitstop")

- when we show to the others the diffrences of using Git, GitHub and GitHub Pages in comparison to the standard methods:
 
  ![alt text](http://i.imgur.com/wD7lRWR.gif "when we show to the others the diffrences of using Git, GitHub and GitHub Pages in comparison to the standard methods")


## Repository cloning to your local directory

* Go to your home directory `$ cd ~`
* Copy the string `https://github.com/bitsoftly/bitsoftly.github.io.git`
* Type in the console `$ git clone https://github.com/bitsoftly/bitsoftly.github.io.git`

## Updating and checking the changes in Real Time

Thanks to the [Jekyll](http://jekyllrb.com/) you can serve locally the files in repository. And what's more important, Jekyll automatically regenerates all the files whenever you make changes in them.
To do that, simply:
```bash
~ $ gem install jekyll
~ $ jekyll new myblog
~ $ cd myblog
~/myblog $ jekyll serve
# => Now browse to http://localhost:4000
```


### There is also few shortcuts to make things quickly:
```bash
~ $ git commit -a
```

* Remember Password, Git bash under Windows Git Bash and Linux

I've an automatic building service which download from a git private repository. The problem is that when it tries to clone repository it need to provide the password, because it is not remembered; so because there is no human interaction, it waits forever the password. How can I force it to remember from id_rsa.pub?

For Windows users, just a note that this is how I setup the Git Bash environment to log me in once when I start it up. I edit my ~/.bashrc:
```bash
eval `ssh-agent`
ssh-add
```
So when I start Git Bash, it looks like:

```bash
Welcome to Git (version 1.7.8-preview20111206)
(etc)
Agent pid 3376
Enter passphrase for /c/Users/starmonkey/.ssh/id_dsa:
Identity added: /c/Users/starmonkey/.ssh/id_dsa (/c/Users/starmonkey/.ssh/id_dsa)
```
And now I can ssh to other servers without logging in every time.


## Roadmap
* Write additional subpages
* Better footer and header in Jekyll
* Blog section
* Jekyll pagination
* Social media buttons

## Copyright

* Copyright (c) 2013 Piotr Kowalski [github.com/bitroniq](https://github.com/bitroniq)
* See LICENSE for details.
