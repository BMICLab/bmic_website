# [BMIC Lab Website](https://bmic-lab.netlify.app/)
This repository holds the code to the BMIC lab website. It is based on the Wowchemy [Reasearch Group template](https://github.com/wowchemy/starter-hugo-research-group) and is hosted on [Netlify](https://www.netlify.com/).

## Usage
There are several ways to update lab's website:
1. **Directly on GitHub**. You can edit the content of the website directly on GitHub. check out the dev branch and make any change you wish. All changes can be seen [here](https://dev--bmic-lab.netlify.app/). Once satisfied with your changes, open a PR to merge the changes into the main branch. Once merged, the changes will be automatically deployed to the main website.


2. **Using Netlify CMS**  Netlify offers a content management system (like a poor man's Wordpress), which can be accessed from the [dev branch website](https://dev--bmic-lab.netlify.app/). Make any changes you wish, then create a PR to merge the changes into the main branch. Once merged, the changes will be automatically deployed to the main website. 


## Site Structure
The site is built using [Hugo](https://gohugo.io/), a static site generator. The site's content is written in [Markdown](https://www.markdownguide.org/). The site's structure is defined in the `config/_default/menus.toml` file. The content of each page is defined in the `content/` folder. The site's theme is defined in the `themes/` folder.

### Adding your profile
Create a new directory under `content/authors/` with your username. Add a `index.md` file with the required format (use any existing profile as a template). Add a profile picture to the `content/authors/<your_username>/` directory. The picture should be named `avatar.jpg` and should be square (ideally 512x512 pixels).

### Adding a publication
There are 2 ways to add a publication:
1. **Import Bibtex file** Using [Hugo academic CLI](https://github.com/wowchemy/hugo-academic-cli) you can automatically turn a .bibtext file into a publication entry in the website. This can serve as a good starting point for additional manual editing or as a simple entry to just publish to the website.
2. **Manual Entry** Create a new directory under `content/publication` with the name of the publication. Add a `index.md` file with the required format (use any existing publication as a template). Add a publication picture to the `content/publication/<publication_name>/` directory. The picture should be named `featured.jpg` and should be square (ideally 512x512 pixels).

### Adding other types of content
The logic is similar to the above methods. Type of content is defined by the directory name under `content/`. Each type of content has a different `index.md` file format. Use any existing content as a template.

# Run Locally
In case you want to run host the website locally to see changes before pushing them to GitHub, follow these steps:
1. Clone this repo.
2. run the following command to build and host the website locally on port `PORT_NUMBER`:
```docker run  --privileged --rm -it   -v $(pwd):/src   -p <PORT_NUMBER>:1313   klakegg/hugo:ext-ubuntu   server```
3. Open your browser to the following address: `http://<SERVER_IP>:<PORT_NUMBER>/`

The website will be automatically updated on every chagne you make (useful for major edits to the website).


