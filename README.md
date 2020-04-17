By default, I use this alternative, and highly effective approach: https://www.sitepoint.com/organize-project-files/?utm_source=rss 
The content is copied and repeated below:

### The Mandatory Set
This is a reference list of files that nearly every software project should have:   
__README__: this is what GitHub renders for you right under the sourcetree, and it can go a long way to explaining what the project is about, how files are organized, and where to find further information.  
__CHANGELOG__: to list what’s new, modified or discontinued on every version or revision — normally in a reverse chronological order for convenience (last changes first).  
__COPYING LICENSE__: a file containing the full text of the license covering the software, including some additional copyright information, if necessary (such as third-party licenses).   
__.gitignore__: assuming you use Git (you most probably do), this will also be a must to tell what files not to sync with the repository. (See Jump Start Git’s primer on .gitignore and the documentation for more info, and have a look at a collection of useful .gitignore templates for some ideas.)  

### Supporting Actors
Some additional files you might also consider including, depending on the project:   
__AUTHORS__: credits to those participating in writing the code.  
__BUGS__: known issues and instructions on reporting newly found bugs.  
__CONTRIBUTING/HACKING__: guide for prospective contributors, especially useful for open-source projects.  
__FAQ__: you already know what that is. ;)   
__INSTALL__: instructions on how to compile or install the software on different systems.   
__NEWS__: similar to the CHANGELOG file, but intended for end users, not developers.   
__THANKS__: acknowledgments.  
__TODO/ROADMAP__: a listing for planned upcoming features.  
__VERSION/RELEASE__: a one-liner describing the current version number or release name.   

### Case 1: Web App
Let’s consider a web application — software that runs on a web server and that you can access through the browser, either on your desktop computer or mobile device. And let’s say this is a web app that offers a membership to access a premium service of sorts — maybe exclusive reports, or travel tips, or a library of videos.
```
File Structure
├── .elasticbeanstalk
├── .env
├── billing
├── changelog.txt
├── locale
│   ├── en
│   └── zh_Hans
├── members
├── readme.txt
├── static
│   ├── fonts
│   ├── images
│   ├── javascript
│   └── styles
├── templates
│   ├── admin
│   └── frontend
├── todo.txt
└── tools
```

### Case 2: Desktop App
Now let’s consider an application that you can download and install on your computer. And let’s say the app takes some input, such as CSV files, and presents a series of reports afterward.

```
File Structure
├── .gitignore
├── data
├── doc
├── legacy
│   ├── dashboard
│   ├── img
│   └── system
├── LICENSE
├── README
├── tests
├── thirdparty
├── tools
│   ├── data_integration
│   └── data_scraping
├── ui
│   ├── charts
│   ├── css
│   ├── csv
│   ├── dashboard
│   ├── img
│   │   └── icons
│   ├── js
│   ├── reports
│   └── summaries
├── VERSION
└── wiki
```


### References
del Alba, L. 2020. "How to Properly Organize Files in Your Codebase & Avoid Mayhem". Retrieved from https://www.sitepoint.com/organize-project-files/?utm_source=rss
