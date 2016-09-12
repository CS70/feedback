# Feedback
A set of CS70-specific feedback forms. This repository contains (1) the 
generator for the website and (2) the static deployment. To configure
the static, simply input a list of Google Forms with basic information.
The deployment then displays all forms inline.

created by [Alvin Wan](http://alvinwan.com), Fall 2016

# Usage

To make edits to the website, first run the preview.

    make preview

Then, make edits as necessary. Note that *the preview automatically
re-generates* as anytime you save a file. Once you feel comfortable
with the changes made, deploy to production. 

    make deploy m="<message describing change>"

Your edits go live instantaneously.
