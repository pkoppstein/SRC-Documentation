One way to access the data and scripts in the repository is by downloading a "zip" file.  Simply follow the "Downloads" link to do so, or visit https://bitbucket.org/states50/nominate/downloads
You will need an "unzip" program or app to unzip the zipped file.

Individual files can also be viewed and downloaded by following the "Source" hyperlink.

An alternative is to "clone" the entire repository.  This has several advantages - for example, it is trivially easy to determine if your copy has been updated, and to obtain all the updates.  However, if you aren't already familiar with Mercurial or Git, the "startup" costs are relatively high.

In any case, there are two main ways to "clone" the SRC repository:

1. Use the command-line program, `hg`
2. Use a GUI program, such as TortoiseHg (Windows or Linux) or SourceTree (Windows or Mac).

Here are some links for further information about installing and using hg:

* Guided Tour - https://www.mercurial-scm.org/wiki/Tutorial
* Installation - https://www.mercurial-scm.org/wiki/Download
* Tutorial - http://hginit.com/
* Online Book - https://book.mercurial-scm.org/read

## TortoiseHg for Windows
    https://tortoisehg.bitbucket.io/
## TortoiseHg for Linux
    https://tortoisehg.bitbucket.io/download/linux.html
## SourceTree for Windows or Mac
    https://www.sourcetreeapp.com/

## Notes on using hg at the command prompt##
Here are some very brief notes rather than detailed recipes.

1. To clone into the pwd:
 
    hg clone https://pkoppstein@bitbucket.org/states50/nominate

2. To check whether there are any updates:

    hg incoming

3. To obtain updates:

    hg pull -u