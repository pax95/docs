---
title: Windows version of the IronWorker CLI
layout: default
section: worker
breadcrumbs:
  - ['CLI Tool', 'cli', 'Windows']
---

The Iron.io command line tool will help you interact with the IronWorker API to make creating workers easier.
<section id="toc">
  <h3>Table of Contents</h3>
  <ul>
    <li><a href="#installing">Install</a></li>
    <li><a href="#configuration">Configure</a></li>
    <li><a href="#Confirm">Confirm</a></li>
  </ul>
</section>

<h2 id="installing">Install</h2>

Head over to [https://github.com/iron-io/ironcli/releases](https://github.com/iron-io/ironcli/releases) and download the newest version of the cli. 


<h2 id="configuration">Configure</h2>
Open a new Command Line and CD into the directory you’ve downloaded the executable to. From that directory, confirm the installation was successful by checking the version

```sh
ironcli.exe --version
```

Now that it’s working, let's move everything to C:\ directly (Replacing $username with your username)

```sh
copy c:\Users\$username\Downloads\ironcli.exe c:\IronCli\iron.exe
```

Once that has been completed, add the C:\IronCli to the PATH Environment Variable. If you need help with this step, please see [this article](http://www.howtogeek.com/118594/how-to-edit-your-system-path-for-easy-command-line-access/) as a guide.

<h2 id="confirm">Confirm</h2>
Finally, to confirm everything has been setup properly, open a new Command Line and run

```sh
iron --version
```

Now you can follow along with all of the examples in the docs. 



