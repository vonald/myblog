---
author : Stephen James
date : 2021-11-05T05:13:12
slug: "file_saving_blues" 
title : ""
tags : [ ]
type : post
---
I'm trying out iA Writer on my Android phone. I had it on iOS way back, not long after it came out, if I recall correctly. The only reason I didn't use it more was because the file handling didn't work for me. And once I got in to using Drafts, where I could set up a workflow just how I liked it, there was no going back.

It's perfectly fine to write with, however, it is doing something weird when I save. In order to run my Python script that saves a post with all the correct formatting, I start with a basic template file. I overwrite any text within that file, normally the previous post. But when I open the file there are a few lines from the previous version still there, at the bottom. Go figure.

I think I will try tweaking the Python script to clear all text from the template file once it has been copied to the formatted .md file. [^1]See if that does the trick. 

[^1] : Just three lines of code needed using .truncate(0) to remove all text from the file.




