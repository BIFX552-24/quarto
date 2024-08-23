# Practicing Quarto

We are going to start with the iris demo from [Rpubs.com](https://rpubs.com/moeransm/intro-iris), and then we'll go back and make some upgrades to the formatting.

## Helpful links

* [Quarto](https://quarto.org/) tour.
  * Quarto [documentation guide](https://quarto.org/docs/guide/).
  * [Markdown basics](https://quarto.org/docs/authoring/markdown-basics.html).
  * [Formatting code block output](https://quarto.org/docs/output-formats/html-code.html).
* The [iris dataset](https://rpubs.com/moeransm/intro-iris).

## Required work

These steps will need to be completed to receive full credit. If there is time, there are some additional edits we will make to give it some extra polish.

* Set up a repository using [this GitHub Classroom link]().

* Start by creating a quarto document and replicating the information and formatting found at <https://rpubs.com/moeransm/intro-iris> (export HTML code). Be sure to leave a note attributing the original authors.

  * Open RStudio and create a new Quarto document (use `File > New File > Quarto Document...`) and save it as `index.qmd`.
  * Header: Update the `title` field and enter the author's name and the original date published in the `author` and `date` fields.
  * Attribution: Add a note at the top of the document attributing the original author with a comment that we are copying this for educational purposes.
  * Text: Copy the text from the iris demo and paste it into your new Quarto document.
  * Code: Create a new code block for each chunk of code (use `Insert > Executable Cell > R`) and copy/paste the code chunk from the iris demo. Do *not* copy the code output from the demo - this will be generated automatically when you render the document.
  * Render: Click `Render` occasionally to see the progress of your document. It should open/update in your browser.

* Push your changes to GitHub.

  * Open your repo in the browser.
  * Click the `+` button right next to the green `<> Code` button and select `Upload files`.
  * Drag and drop your `index.qmd` file, `index.html` file, and `index_files` directory into the window.
  
* Configure your repository to publish your webpage using [GitHub Pages](https://docs.github.com/en/pages/quickstart).
  * On step 6 of the quickstart linked above, select "/(root)" to publish your html code from the root directory.
  * After a few minutes your webpage should be live at https://bifx552-24.github.io/quarto-username/, where `username` is your GitHub username.
  
*  Export your document in [Word format](https://quarto.org/docs/output-formats/ms-word.html) and submit it on Blackboard.

## Additional (optional) edits

If you have time, consider making the following edits to your document:

* Make it so that the user can opt for [dark mode](https://quarto.org/docs/output-formats/html-themes.html#dark-mode).
* Turn the paragraph starting "The `summary()` function gives summary statistics for any dataset." into at tip using a [callout block](https://quarto.org/docs/authoring/callouts.html).
* [Fold the code](https://quarto.org/docs/output-formats/html-code.html#folding-code) in the visualization section, such that only the figures are shown by default.
