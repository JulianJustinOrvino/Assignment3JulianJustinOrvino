# PBP Django Project Template

Platform-Based Programming (CSGE602022) - Organized by the Faculty of Computer Science Universitas Indonesia, Odd Semester 2022/2023

*Read this in other languages: [Indonesian](README.md), [English](README.en.md)*

## Introduction

This repository is a template that is designed to help students who take the Platform-Based Development/Programming Course (CSGE602022) to know the structure of a Django Web application project, including the files and configurations that are important in running the application. You can freely copy the contents of this repository or utilise this repository as a learning material and also as a starting code to build a Django Web application project.

## How to Use

If you want to use the code template in this repository as a starter code for
developing a Django Web application:

1. Open the GitHub page of the code template repository and click "**Use this template**"
   button to make a copy of the repository into your own GitHub account.
2. Clone the new Django template repository from your GitHub account to a
   location in the filesystem of your local development environment by using
   Git:

   ```shell
   git clone <URL to your repository on GitHub> <path in local development environment>
   ```
3. Go to the location where the cloned repository is located in the local
   development environment:

   ```shell
   cd <path to the cloned repository>
   ```
4. Create a Python virtual environment named `env` inside the cloned repository
   by using Python's `venv` module:

   ```shell
   python -m venv env
   ```
5. Activate the virtual environment:

   ```shell
   # Windows
   .\env\Scripts\activate
   # Linux/Unix, e.g. Ubuntu, MacOS
   source env/bin/activate
   ```
6. Verify the virtual environment has been activated by looking at the prompt
   of your shell. Make sure there is a `env` prefix in your shell. For example:

   ```shell
   # Windows using `pwsh` shell
   (env) PS C:\Users\RickeyAstley\my-django-app
   # Linux/Unix, e.g. Ubuntu using `bash` shell
   (env) rickeyastley@ubuntu:~/my-django-app
   ```

   > Note: You can use [Visual Studio Code][] (with Python extension) or [PyCharm][]
   > to open the source code directory that has a virtual environment directory.
   > Both will detect the virtual environment and use the correct Python virtual
   > environment. Furthermore, you can also run your shell directly in both text
   > editor/IDE.
7. Install the dependencies needed to build, test, and run the application:

   ```shell
   pip install -r requirements.txt
   ```
8. Run the Django Web application using local development server:

   ```shell
   python manage.py runserver
   ```
9. Open http://localhost:8000 in your favourite Web browser to see if the Web
   application is running.

## Deployment Example

The code template provided a GitHub workflow to deploy the sample Django Web
application to [Heroku][], which is a Platform-as-a-Service (PaaS) provider
that lets you to build and run a Web application on their infrastructure. You
can read the instructions at [Tutorial 0][] to figure out how to configure the
GitHub Actions to run the provided workflow in your repository.

For reference, the deployed Django Web application example from the original
code template repository can be found at: https://django-pbp-template.herokuapp.com.

## Next Actions

If you have successfully created your own repository and set up the Django Web
application project, you can start working on the weekly tutorials and assignments
related to Django Web application development. 

If you found any issues or have ideas to improve the code template, feel free
to discuss your proposal via the [issue tracker](https://github.com/pbp-fasilkom-ui/django-pbp-template/issues)
and create a Pull Request (PR) containing your changes to the code template.

## Credits

This template was based on [PBP Odd Term 2021/2022](https://gitlab.com/PBP-2021/pbp-lab) written by 2021 Platform Based Programming Teaching Team ([@prakashdivyy](https://gitlab.com/prakashdivyy)) and [django-template-heroku](https://github.com/laymonage/django-template-heroku) written by [@laymonage, et al.](https://github.com/laymonage). This template is designed in such a way so that students can use this template as a starter and reference in doing assignments and their work.

[Heroku]: https://www.heroku.com/
[Tutorial 0]: https://pbp-fasilkom-ui.github.io/ganjil-2023/en/assignments/tutorial/tutorial-0
[Visual Studio Code]: https://code.visualstudio.com/
[PyCharm]: https://www.jetbrains.com/pycharm/

# Assignment5

## What is the difference between Inline, Internal, and External CSS? What are the advantages and disadvantages of each style?

1. Inline CSS: An inline CSS is used to apply a unique style to a single HTML element. An inline CSS uses the style attribute of an HTML element.
2. Internal CSS: Internal CSS is a form of CSS using which you can add CSS to HTML documents. It helps to design the layout of a single HTML web page       and change the styles of a web page within HTML code.
3. External CSS:An external style sheet is a separate CSS file that can be accessed by creating a link within the head section of the webpage.        Multiple webpages can use the same link to access the stylesheet. The link to an external style sheet is placed within the head section of the page.

## Describe the HTML5 tags that you know.

div, a tag to make blok for html elements a, a tag for hyperlink meta, containing the metadata for html website span, to change the style of certain text. form, to make a form table,to make a table title, to contain a title of a website img, insert a an image style, make an internal css script, to make a website more instersting p, make a paragraph h1, h2, h3, h4, h5, h6, make a heading

## Describe the types of CSS selectors you know.

element, select certain elements .class-name, choose an element that has class name #id, choose an element that have id, pick all element .class1, .class2, Pick an element for a selector element .class-name, pick a certain element with class-name :hover, style when the cursor hover :active, style when the link is clicked

##  Explain how you would implement the checklist above.

 work with HTML and CSS without bootstrap, first I make the login-user, register, todolist and create-task using CSS. I used the online template, google preferences to make the website more attractive, after that I add commit then push to github.