# My git repository template

This is my personal git repository template that I use when I create a new 
repository.

![Static Badge](https://img.shields.io/badge/markdown-black?logo=markdown)
![Static Badge](https://img.shields.io/badge/creativecommons-v1.0-%23EF9421?logo=creativecommons)


## About the project
As mentioned above, this is my personal template for new repository. It's a
generic template that I use for github (and gitlab) repository.

It's contain templates for Issues, Pull / Merge Requests, Actions...

## Installation
You can use this project in 2 ways: by forking it, the better way, or by 
cloning it.

The simple and better way to use the project is by forking it. 
To do this, simply click on the **Fork** button :slightly_smiling_face:.

If you want to clone it, run the following:
```
git clone git@github.com:blackcats/my-git-repository-template.git
git remote remove origin
```
Now add your remote repository by running (replace _path_to_my_remote_repository_ 
by a valide path):
```
git remote add origin path_to_my_remote_repository
```
and push it:
```
git push -u origin main
```

## Configuration
> [!NOTE]
> For now, I only explain how to configure the repository as a template on GitHub.
> How to configure the repository has a template on GitLab will come later.

On your GitHub repository of the project, go to the **Setting** section 
![Settings](/../screenshots/readme/setting_button.png)
and select: **Template repository**.
![template_checkbox](/../screenshots/readme/template_checkbox.png)

## Usage
Once the configuration is done, you can use the repository template in 2 ways.
- From the repository itself: click on **Use this template** first then click
  on **Create a new repository**. 
  ![New repository from template](/../screenshots/readme/new_repo_from_template.png)
- From your repositories page: click on **New** 
  ![New repository button](/../screenshots/readme/new_repo.png)
  then under **Repository template** select your repository template.
  ![Template selection](/../screenshots/readme/template_selection.png)

Clone the new repository and:
- remove the screenshots directory, or at least its contents 
- replace the current README file with the template
- commit the changes and push them
with the following commands:
```
git clone path_to_my_remote_repository
git mv README_TEMPLATE.md README.md
git commit -m "replace readme file by the readme template"
git push
```

## Support 
If you need help, or have an idea of what to add, please open an Issue.

## Roadmap
The upcoming adds are:
- [ ] Issues template(s)
- [ ] Pull / Merge request template(s)
- [ ] Configuration for GitLab
- [ ] Actions template(s)

## Project status
Although there are no frequent commit, the project is always active.

<!--
## Acknowledgment
People or teams those actively participate to the project, or project or people
who inspirate you for creating the project.
-->


## Author
This project was created in 2023 by [Olivier LE GALL](lgo@black-cats.org).

## Licence
[![CC0](https://i.creativecommons.org/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

## Links
- [github-issue-templates](https://github.com/timothystewart6/github-issue-templates)
<!----
The following Links explain how to create a good readme file:\
https://www.makeareadme.com/ \
https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide \
https://dev.to/rohit19060/how-to-write-stunning-github-readme-md-template-provided-5b09 \
https://bulldogjob.com/readme/how-to-write-a-good-readme-for-your-github-projeck
-->
