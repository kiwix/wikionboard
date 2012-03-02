---
layout: page
title: WikiOnBoard
---
{% include JB/setup %}

# News

<ul class="posts">
  {% for post in site.posts limit:4 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

# Overview

WikiOnBoard is a mobile phone app which allows reading the Wikipedia without internet connection.

## Screenshots 

### WikiOnBoard 2

|![Library](images/screenshot_2_library_w180.png)|![Index](images/screenshot_2_index_w180.png)|![Article](images/screenshot_2_article_w180.png)|

### WikiOnBoard 1

|![Index](images/screenshot_index.png)|![Article](images/screenshot_article.png)|

# Getting started

## Supported devices

Currently only Symbian based mobile phone are supported. Most touch and non-touch devices which are based
 on S60 3rd FP1, Symbian^1 and Symbian^3 are supported. This includes mobile phones like Nokia N8, C7, 5800, or N95.
 Note, that WikiOnBoard 2 is only available for Symbian^3 devices. Furthermore, the WikiOnBoard version S60 3rd FP1 
 has less features than even WikiOnBoard 1. 
 
## Install

### Symbian^1 and Symbian^3 mobile phones (For example Nokia N8, C7, 5800, N97)

WikiOnBoard is now availabe in Nokia store. Please download it using the Nokia Store App on your mobile or download it on your PC from [here](http://store.ovi.com/content/148305).

Note, that on Symbian^3 devices WikiOnBoard 2 is downloaded (Note: Not released yet), while on Symbian^1 devices WikiOnBoard 1 is downloaded.

Note, that the Nokia store version is much newer than the versions in the download section of this site. 


### S60 3rd edition, feature pack 1 or later (For example N82, E75)

To install download the latest [WikiOnBoard_installer_0.0.37.sisx](https://github.com/downloads/cip/WikiOnBoard/WikiOnBoard_installer_0.0.37.sisx)  from the download section, recommended is to download directly from your mobile phone's webbrowser. Open the downloaded file on your phone and follow the instructions.

Note, that the Qt installer requires an internet connections to download a significant amount of data (10-20 Mb). Thus either use wireless lan to connect your phone, or take care that you have a cheap data rate.  Alternatively, you can also download a version [without the Qt installer](https://github.com/downloads/cip/WikiOnBoard/wikionboard_0.0.37.sis). Qt has then to be installed separately.

## Download Wikipedia (or other zim-file)

See [Get-eBooks](Get-eBooks.html) where to download the Wikipedia or other eBooks in zim-format and how to it them on your mobile.


## Open and use WikiOnBoard

### WikiOnBoard 2

After installation you can find WikiOnBoard in you mobile phone's application menu. Use the "Find eBook on Phone" to add a file you have downloaded in the last step. If you stored it on the memory card, you can typicall find it on drive e or f.

When you have managed to do all this, it should be pretty self-explaining how to use it. Somethings to keep in mind:

* Search is case sensitive. In the wikipedia all articles start with a capital letter, so if you cannot find anything useful it may be because your search term does not. The search input per default  switches automatically to capital letter for the first letter

### WikiOnBoard 1 

After installation you can find WikiOnBoard in you mobile phone's application menu. 

After opening it you will see a pretty empty screen. Use "Options/Open Zimfile" to open the file you have downloaded in the last step. If you stored it on the memory card, you can typicall find it on drive e. In particular on non-touch devices this  step is pretty awkward, but fortunately you won't have to this frequently, as the last opened file is opened automatically next time you start WikiOnBoard.

When you have managed to do all this, it should be pretty self-explaining how to use it. Somethings to keep in mind:

* Search is case sensitive. In the wikipedia all articles start with a capital letter, so if you cannot find anything useful it may be because your search term does not. The search input per default  switches automatically to capital letter for the first letter
* Keys 8 and 2 can be used to scroll through an article. This is in particularly useful if there are lot of links in the current section of the article, for example in the table of content.
 
# Troubleshooting and Feedback

If you encounter problems, or have any suggestions I'd be happy if you let me know, either by using the [issue tracker](http://github.com/cip/WikiOnBoard/issues) or by sending a e-mail to cip@gmx.at.