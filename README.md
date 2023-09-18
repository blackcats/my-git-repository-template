# My git repository template

This is my personal git repository template that I use when I create a new 
repository.

![Static Badge](https://img.shields.io/badge/markdown-black?logo=markdown)
[![CC BY-NC-SA 4.0][cc-by-nc-sa-shield]][cc-by-nc-sa]

## About the project
As mentioned above, this is my personal template for new repository. It contain
generic template that I use to create github (and gitlab) repository.

Template are:
- Issues template
- Pull or Merge Requests template
- Actions scripts
- ...

## Installation
You can use this project in 2 ways: by forking it, the better way, or by 
cloning it.

The simple and better way to use the project is by forking it. 
To do this, simply click on the **Fork** button :slightly_smiling_face:.

If you want to clone it, then run the following:
```
git clone git@github.com:blackcats/my-git-repository-template.git
git remote remove origin
```
Now add your remote repository by running :
```
git remote add origin path_to_my_remote_repository
```
Replace _path_to_my_remote_repository_ by the path of your remote repository 
and push it:
```
git push -u origin main
```

## Configuration
> [!NOTE]
> I only explain how to configure the repository as a template on GitHub.
> How to configure the repository has a template on GitLab will come later.

In your GitHub repository of the project, go to the **Setting** section 

![Settings](/../assets/images/readme/setting_button.png?raw=true)

and select: **Template repository**.

![template_checkbox](/../assets/images/readme/template_checkbox.png?raw=true)

## Usage
Once the configuration is done, you can use the repository template in 2 ways.
- From the repository itself: click on **Use this template** first then click
  on **Create a new repository**. 
  
  ![New repository from template](/../assets/images/readme/new_repo_from_template.png?raw=true)

- From your repositories page, click on **New** 
  
  ![New repository button](/../assets/images/readme/new_repo.png?raw=true)

  then under **Repository template** select your repository template.

  ![Template selection](/../assets/images/readme/template_selection.png?raw=true)

Once the new repository created on GitHub:
- clone it 
  ```
  git clone path_to_my_new_repository
  ```
- replace the current README file with the template
  ```
  git mv README_TEMPLATE.md README.md
  ```
- edit the README file
  ```
  $EDITOR README.md
  ```
- commit the changes and push them
  ```
  git commit -m "initial commit, add readme file"
  git push
  ```

## Support 
If you need help, or have ideas of what to add, please open an Issue.

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
This work is licensed under a
[Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License][cc-by-nc-sa].

[![CC BY-NC-SA 4.0][cc-by-nc-sa-image]][cc-by-nc-sa]

[cc-by-nc-sa]: http://creativecommons.org/licenses/by-nc-sa/4.0/
[cc-by-nc-sa-image]: https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png
[cc-by-nc-sa-shield]: https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg

## Links
- [github-issue-templates](https://github.com/timothystewart6/github-issue-templates)
<!----
The following Links explain how to create a good readme file:\
https://www.makeareadme.com/ \
https://coding-boot-camp.github.io/full-stack/github/professional-readme-guide \
https://dev.to/rohit19060/how-to-write-stunning-github-readme-md-template-provided-5b09 \
https://bulldogjob.com/readme/how-to-write-a-good-readme-for-your-github-projeck
-->
