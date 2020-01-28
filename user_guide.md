# Using this repository

## Introduction
The purpose of this repository is to provide all lab meeting materials and information.
All changes to the documents (including additions and subtractions) are actively tracked
and previous versions of documents can be accessed if needed.
The GitHub environment also provides an avenue for you to make changes to the repository
or post issues.
The purpose of this guide is to walk through various ways to access and use repository
and is geared towards users that are not familiar with the Git environment.

## What are these weird file extensions?
You may notice that some of the file extensions are unfamiliar.
Here are some of the more common ones, with descriptions of what they mean:
- **.md** : These are Markdown files. The are light-weight (see: small) files
designed to display simple text. The simplicity of the plain text allows for files to
be easily read, written, and tracked via version control. They are most similar to
.html files, but simpler. When opened in GitHub, these will display in their formatted
version. However, if you open these with a text editor
(e.g., TextEdit on Mac or Notepad on Windows) they will just show the raw code. To see
the formatted version you can view the files directly in GitHub or
use the software [Markdown](https://daringfireball.net/projects/markdown/).
There is also a 
[Google Chrome plugin](https://chrome.google.com/webstore/detail/markdown-preview/jmchmkecamhbiokiopfpnfgbidieafmd?hl=en)
for viewing formatted .md files. Various text editors also include a .md preview feature.
- **.html** : These are html files and are what webpages are written in.
You can use a text editor to view the raw code or a browser (e.g., Chrome, Firefox)
to view the formatted version.
- **.R** : These are files read by the software "R". R was originally developed as
software for doing data analysis, but can now do a variety of things from visualizations,
file formatting, presentation creations, and much more. To open and run these files, you
will need to download R from the [software homepage](https://www.r-project.org/).
You may also find it useful to download [R studio](https://www.rstudio.com/), which
provides additional tools as well as a more user-friendly environment.
- **.Rmd** : These are R markdown files and are used for making nicely formatted version of
R code that include results. The files created by R markdown are typically .html or .pdf.
You may see these in cases where R code is being presented. The files can be opened
using R studio (see above).
- **.pdf** : you got those right? These should be easily viewable with
software typically preloaded onto most computers, such as Adobe Acrobat or Preview (Mac).
- **.pptx** : Powerpoint files that can be opened using Microsoft Powerpoint.
You will not need to access these files as they will all be converted to .pdf
after they are created (or edited).
- **.tex** : These are latex files that can be opened with a text editor. They are
used to create formatted text documents (typically pdfs). Conceptually, they are somewhat
analogous to Microsoft Word documents. You will not need to read .tex files as these will
all be formatted and converted to .pdf after they are edited.

Note: if you have trouble opening any files on your machine, please let a PI know and
they can get you sorted out.

## How do I download individual files without using Git?
For .pdf and .pptx files:
1. From the GitHub page, click on the file you want to download.
2. Click the "Download" button near the top of the file.
3. The file should now be in your "Downloads" folder.

For .md, .R, .Rmd, .html, and .tex files:
1. From the GitHub page, click on the file you want to download.
2. Right click on the "Raw" button near the top of the file and choose "Save Link As..."
3. Choose the location where you'd like to save the file.
4. Open the file using the desired software.

## How do I download the entire repository without using Git (not recommended)?
1. Navigate the 
[main course directory](https://github.com/SmithEcophysLab/lab_meeting).
2. Click the green button that says `Clone or Download`.
3. Click `Download Zip`. A .zip file should begin downloading.
4. Double click on the file to unzip in your downloads folder (or wherever you want to 
house the file) to unzip.
5. Everything should be there.

**Note: the files you downloaded will not change if files are changed during the course
(and they will!). As such, downloading the entire repository in this manner is not 
recommended.**

## How do I download files using Git?
1. Before using Git, you will need to install it on your machine. Check out this website
for ways to install Git to your machine:
[https://git-scm.com/book/en/v2/Getting-Started-Installing-Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git).
	- If you have a Windows machine, it may also be useful to download and install
	Git Bash for your machine. This will provide you with a command line environment
	for running Git commands. The download can be found here:
	[https://gitforwindows.org/](https://gitforwindows.org/).
2. To download all the course files using git, you will need to clone the repository.
To do this, open a command line editor (e.g., Git Bash or 
Terminal). Then use the command `cd` to navigate to the folder where you want to
put the repository E.g.,
	
	> cd ~/Documents/Git

	Then, use the `git clone` command to clone the repository. E.g.,
	
	> git clone https://github.com/SmithEcophysLab/ptee_fall2019.git
	
	Now the full repository should be downloaded in a new folder.
	
3. To make sure you have the most up-to-date version of the files from the main repository,
you will can run the command `git status` from the command line within your cloned
repository. E.g.,

	> cd ~/Documents/Git/ptee_fall2019
	
	> git status

4. If you are not up to date, you can run the command `git pull` from the main repository
and this will pull
in all the new changes to the repository.

	> cd ~/Documents/Git/ptee_fall2019
	
	> git pull

## How do I provide feedback about folders or files?
You can provide feedback by opening an issue! To do this, navigate to the
[Issues](https://github.com/SmithEcophysLab/lab_meeting/issues)
tab. Your issue will be visible to Nick and the members of the course and responses
to the issue can be made directly.

## How do I make commits to the repository
[NEED TO ADD]

## an alternative resource
Check out the [schwilk lab](https://github.com/schwilklab) page for more detailed Git and
GitHub resources. The file to look at is 
[data-code/git-and-github.md](https://github.com/schwilklab/lab-resources/blob/master/data-code/git-and-github.md).


