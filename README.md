# TEACHxperts Workshop Instructions

## Instructions for anyone who is new to GitHub or R Studio

These instructions require a web browser. No software installations are necessary.

- Create a free GitHub account: https://github.com/
- While logged in, visit: https://github.com/chrisdaaz/recipe-bookdown
- At the top-right of the page, click on the `Fork` button:

_This action will create a copy of the project files for you to edit. After the copying is complete, you should now be looking at your version of the project at `https://github.com/[YOUR_USERNAME]/recipe-bookdown`_

- Click on the `Create new file` button

- Edit the following lines in the `recipe-title.Rmd` file:

| Line Number | Text to Edit                                                     | Example                                                                                                                                | Description                                                                                                                                                                                                                       |
|-------------|------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1           | # Title of Recipe                                                | # Moroccan Stew                                                                                                                        | Keep the `#` at the beginning of the line and enter the title of your recipe                                                                                                                                                      |
| 3           | \begin{recipe}[title]{number of services}{preparation time}      | \begin{recipe}[MoroccanStew]{Moroccan Lamb (or Turkey) Stew}{4 Portions}{1 hour}                                                       | Begin the recipe by entering the title, portions, and estimated time it takes to make.                                                                                                                                            |
| 5-7+        | \ingredient{Numerical quantity}{Unit of measurement}{Ingredient} | \ingredient[2]{cups}{onion}<br>\ingredient[\fr12]{cup}{carrots}                                                                        | Add a line for an ingredient: start with the name of the ingredient, the numerical quanity, and unit of measurement (optional). For any step in the cooking process, you can add multiple ingredients following the same pattern. |
| 8+          | Instructions for what to do with the above ingredients.          | Add oil to pan. Chop onions vertically and carrots diagonally. Add to pan and saut\'{e} for 4-5 minutes on medium heat, or until soft. | Explain this step in the cooking process in relation the ingredients mentioned above.                                                                                                                                             |

- Add as many steps and ingredients as you need. Just make sure that the last line in the file is this: `\end{recipe}`
- When you are ready to save the file, scroll to the bottom of the page and fill out the form with the following information: the name of the edit (e.g. `Adds pizza recipe`) and add an optional description of the edit/
- Keep the setting on: `Commit directly to the master branch`
- Click on the `Commit changes` button
- Go back to the original repository: https://github.com/chrisdaaz/recipe-bookdown
- Click on `New Pull Request`
- Click on `compare across forks`
- In the head repository drop-down menu, select your fork: `[YOUR_USERNAME]/recipe-bookdown`
- Click on `Create pull request`
- Enter a name for the pull request (e.g. `Chris's Recipe`)
- Click on `Create pull request`

_By doing this, you are requesting to have your recipe added to the shared recipe book. We will approve your request and a new verion of the recipe book will be made._

**Finished!**

## Instructions for anyone who is familiar with GitHub and R Studio

These instructions assume you have a GitHub account and R Studio installed on your computer.



## Credits

This is a minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown). Please see the page "[Get Started](https://bookdown.org/yihui/bookdown/get-started.html)" at https://bookdown.org/yihui/bookdown/ for how to compile a **bookdown** project into HTML. You may generate a copy of the book in `bookdown::pdf_book` format by calling `bookdown::render_book('index.Rmd', 'bookdown::pdf_book')`. More detailed instructions are available here https://bookdown.org/yihui/bookdown/build-the-book.html.

You can find the preview of this example at https://bookdown.org/yihui/bookdown-demo/.
