# Constellate Workshop Series Template

This repository is an example for teaching workshops and/or classes using [Constellate](https://constellate.org/). Constellate is the text analytics service from the not-for-profit [ITHAKA](https://www.ithaka.org/) - the same people who brought you [JSTOR](https://www.jstor.org/) and [Portico](https://www.portico.org/). It is a platform for teaching, learning, and performing text analysis using the world’s leading archival repositories of scholarly and primary source content.

Constellate enables schools of all sizes to teach data and text analytics with a learning platform that empowers faculty, librarians, and other instructors to educate a new generation of learners in text and data analysis. Our solution, centered on student and researcher success, provides text and data analysis capabilities and access to content from some of the world’s most respected databases in an open environment with a variety of teaching materials that can be used, modified, and shared. We envision a future where text and data analytics skills are being taught on Constellate in classes in all disciplines.

Most of the content in this repository was created with basic Markdown, a superset of HTML that allows you to easily stylize text, create links, images, and more. See this [basic markdown cheatsheet](https://www.markdownguide.org/cheat-sheet/) for more details.

## The Constellate Lab 

Institutions that subscribe to Constellate can use the Constellate Lab for teaching, learning, and research. The Constellate Lab will load Jupyter Notebooks from a GitHub repository. The repository must contain one or more Jupyter Notebook (.ipynb) files. These Notebook files could be developed in the Constellate Lab or on a local machine using an IDE such as [Pycharm](https://www.jetbrains.com/pycharm/), [Visual Studio Code](https://code.visualstudio.com/), [Spyder](https://www.spyder-ide.org/), etc.  

## Opening a Repository with Constellate

Once a GitHub repository is created that contains at least one Jupyter Notebook (.ipynb) file, it can be opened with the Constellate Lab. 

1. Log into Constellate on an institutional network. Your institution should be identified in the upper-righthand corner. 

![Choosing login on the Constellate homepage](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/login-and-institution-identifier.png)

Register for a personal JSTOR account in order to use Constellate. This is not the same thing as your institution's JSTOR account. This account will keep track of your personal files on Constellate, allowing you to do things like create, save, and delete your personal files, including datasets and notebooks.

![The login prompt on Constellate](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/constellate-login.png)

2. Open your dashboard. Under Constellate Lab, choose "Import GitHub Repository." If you do not see Constellate Lab options, either your institution does not subscribe to Constellate or it is not being recognized. 

![The button for "Import GitHub Repository"](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/dashboard-import-notebook.png)

3. Enter the URL for the repository you would like to load. You may optionally add a particular Jupyter notebook (.ipynb) file and/or repository branch. A URL is generated that can be opened by anyone with a Constellate subscription. For example, the link could be shared with an entire class during an instruction session. Each student clicks on the link and the Constellate Lab will make a personal copy of the repository and open the Jupyter Notebook for them.

For more information on this process, see our documentation for [sharing a lesson](https://constellate.org/docs/sharing-a-lesson/).

## Using this Template for your Workshop

1. [Create a GitHub account](https://github.com/signup) and log into it. Navigate your browser to [the repository for this template](https://github.com/ithaka/constellate-python-basics/). 
2. Click the "Use this Template" button.
![The template button](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/use-this-template.png)
3. Give your repository a name and a description. Make sure it is public. It is not necessary to "Include all branches." When finished, choose "Create repository from template."
![create repository button](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/create-repository-from-template.png)
4. Choose "Settings" and then select "Pages."
![the settings menu](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/github-settings-menu.png)
![the pages menu](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/pages-menu.png)
5. Under "Build and Deployment," for "Source" choose "Deploy from a Branch." Under "Branch," choose "Main" and "(root)". Be sure to click "Save". 
![save button for build and deployment](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/build-and-deployment.png)
6. To preview your website, make a small change to the "index.md" file. You can see it under the "Code" tab. Select the file you wish to change, then choose the pencil icon to make a change. After the change is made, scroll to the bottom. Optionally, write a comment describing your changes, then choose "Commit changes."
![the pencil icon in GitHub](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/pencil-icon.png)
![the commit changes button](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/commit+changes.png)
7. Return to "Settings" > "Pages" and you should see the URL where your site is live. This URL can be shared with your workshop participants. Any changes to your site will take 1-2 minutes to be visible on the live site. The address will look like:

`https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME`

![view website url](https://ithaka-labs.s3.amazonaws.com/static-files/images/tdm/tdmdocs/preview-github-pages.png)

## Files in this Repository

### `LICENSE`
Contains the MIT license for this template allowing you to "use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software" so long as it is redistributed with the MIT License.

### `README.md`
The document you are currently reading. It contains the information for using the files in the repository.

### `_config.yml`
Specifies several aspects of the template including:

* `theme` The default theme is `jekyll-theme-minimal`. There are more themes [available here](https://pages.github.com/themes/). The themes are based o Jekyll. See the [GitHub documention on themes](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/adding-a-theme-to-your-github-pages-site-using-jekyll).
* `title` Change the default title for your webpage. The default is `University Library Data Literacy Workshop Series`.
* `description` A brief description of the webpage that could describe the content of the material.
* `show_downloads` Takes a boolean true/false value for showing download links for the repository. Default is `false`.
* `logo` The logo on the front page of the website. Be default, this specifies `logo.png` in the root of the repository. You could delete this file and replace it with another file named logo.png that has your institutional affiliation. In general, it is usually better not to store images for a GitHub Pages website in the repository. We recommend storing images in another hosting location such as AWS, Google Drive, Dropbox, etc.

### `XXXX.ipynb` 
Any file that ends in `.ipynb` is a Jupyter notebook file that will be loaded into Constellate. GitHub will preview these files nicely, but it cannot make them execute code in the same way as Constellate. We recommend editing on your local machine and uploading to the repository OR editing in Constellate then downloading the file to your local machine then uploading it to the GitHub repository.
