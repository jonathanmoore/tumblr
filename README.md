# Tumblr Archive

This is a collection of my posts to Tumblr from April 2009 until the present.  The backup of my Tumblr posts was created using [tumblr-utils](https://github.com/bbolli/tumblr-utils/) by [Beat Bolli](https://github.com/bbolli/). 

Even after the Yahoo aquisition of Tumblr I personally believe the platform has a bright future ahead, and I will continue to actively post on Tumblr. I am going to keep this archive up to date in an effor to keep as much of my personal data open on Github as possible.

## Using `tumblr_backup.py`

Here are the quick steps that I used to backup my Tumblr blog on a Mac using the `tumblr_backup.py` script, but it might be helpful to reference the complete installation and usage documents at [tumblr_backup.md](blob/master/tumblr_backup.md). If you encounter any issues directly related to the script you will be better opening an issue at [bbolli/tumblr-utils](https://github.com/bbolli/tumblr-utils/issues)

1. Make sure you have Python installed on your Mac. Type in `python --version` in the terminal to see your version. Everything worked perfectly for me using Python 2.7.2.
2. Determine where your Python site-packages directory is located: 
`python -c "from distutils.sysconfig import get_python_lib; print(get_python_lib())"`
3. Download and unzip the [xmltramp.zip](https://github.com/bbolli/xmltramp/zipball/master) package.
4. Install or move `xmltramp.py` to your site-packages directory from step 2.
5. Copy `tumblr_backup.py` into the directory where you want to archive your blog.
6. Run `tumblr_backup.py` by typing the following into the terminal:  
`python tumblr_backup.py your-blog-name`
7. For a full list of options, arguments and environment variables see [tumblr_backup.md](blob/master/tumblr_backup.md).