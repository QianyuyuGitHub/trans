# Welcome to the English corner of Dr. Q and Dr. L :heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes::heart_eyes:
:two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts::two_hearts:

In this repository you will find a few useful and elegant English expressions.
And there is also some descent ways to use English.:heartbeat:

**Please take notes and update everyday, and keep reading and practicing as well!**:kissing_heart:

## Here are some vital notes you may keep in mind:

- Each time before you change your own file, please **pull the update from remote**.
- Each time before you push your own update to the remote, you should check **if your local version is the newest version**.

## In the following, I will teach you how to manage the GitHub and Git for version control purpose.

- **Download and install Git environment.**[Git] - Git is a version control system for tracking changes in computer files and coordinating work on those files among multiple people.

- **Download and install GitKraken software.**[GitKraken] - GitKraken is a cross platform Git GUI client.
> 1. log in your GitHub Account (if you don't have one, sign up one at first.)
> 2. Select **File** then **Clone Repo** (repo is short for repository), and then in **Clone** tab, click **GitHub.com**, and click on **Browse** button and choose a folder you want to store the whole repository.
> 3. Scroll down the **Repository to clone** to see whether there is a repository called **trans**, if so, click on that and then click on the **Green** button **Clone the repo!** on the right below; on the contract, if not, you should contact me on **WeChat**.
> 4. Then you can find the whole repository in the directory you choose before.

- **Download and install the Sublime Text 3 software if you haven's downloaded it yet.** [Sublime Text 3] - The proprietary cross-platform source code editor with a Python application programming interface.
> 1. Open **Sublime Text 3** and click on the **View** tab on the top, select **Show Console**.
> 2. After **step 1.** you will have a **white** command line like console **under the bottom**. Copy and paste the codes into it and press `Enter`:
```
	import urllib.request,os,hashlib; h = '6f4c264a24d933ce70df5dedcf1dcaee' + 'ebe013ee18cced0ef93d5f746d80ef60'; pf = 'Package Control.sublime-package'; ipp = sublime.installed_packages_path(); urllib.request.install_opener( urllib.request.build_opener( urllib.request.ProxyHandler()) ); by = urllib.request.urlopen( 'http://packagecontrol.io/' + pf.replace(' ', '%20')).read(); dh = hashlib.sha256(by).hexdigest(); print('Error validating download (got %s instead of %s), please try manual install' % (dh, h)) if dh != h else open(os.path.join( ipp, pf), 'wb' ).write(by)
```
> 3. After **Step 2.** you may open the **package control** by `Ctrl+Shift+P`, and enter `install` then click on the **Package Control: Install Package**, then enter `markdown`, select **Markdown Preview**, after s short time, it will install the package for you automatically.
> 4. You may want to open the file you already cloned from the remote in the previous steps. Now you can select the **EnglishStyles.txt** by the right click on mouse, and choose open with the Sublime Text 3. But for now, you can only see the raw file. Use `Ctrl+Shift+P` and type in `markdown` then click on the **Markdown Preview: Preview in Browser**, then **GitHub**. Now you can read the formated style file in your browser.
> 5. f you have done the **Step 4.1** you may wonder how to read it without repeating the method every time you open the file. Well, you can transform the file into a **.html** format file, and then you can open the **.html** file by double clicking. First, you should press `Ctrl+Shift+P` and type in `markdown`, but this time you should choose **Markdown Preview: Save to HTML** and then **GitHub**. After done this, you will find a new **EnglishStyles.html** in the root folder.




[Sublime Text 3]: <https://www.sublimetext.com/>
[Git]: <https://git-scm.com/downloads>
[GitKraken]: <https://www.gitkraken.com/>