### Preview Changes (Optional)

Run `quarto preview` to see your site locally. Quarto will bring up the website in a browser tab pointed to a localhost URL, such as `http://localhost:3456`. 

   - You can leave the preview running as you make changes to the source files; saving changes to the source files will generally (with a few exceptions, such as .ejs files) will be reflected live in your browser.

   - You can also run `quarto render` to create the HTML (in the `_site` directory) without automatically displaying it. Or `quarto render file.qmd` to just render a single file. 
      - Note that you shouldn't commit the files in `_site` to your repository as they will be frequently regenerated and having them in the repository can complicate matters.
      
### Publish Your Changes

1. Run `quarto publish gh-pages` from the command line to push updates to the course website.
   - Hit `Y` when prompted to "Update site at `https://stat555.stat.berkeley.edu/fall-2024/? "`
   - Wait a minute for the content to be rendered on your computer. You should then see a message that files are being updated in the `gh-pages` branch.
   - Wait a minute for the content to be copied to the GitHub Pages site.

2. You can observe the build process at GitHub by clicking on the Actions button at the top of your repository, e.g. https://github.com/berkeley-stat555/fall-2024/actions. It usually takes a couple of minutes for this to complete. 

### README Content for Actual Class Repositories

This is the repository for the course website and course material for Statistics 555 for Fall 2024. 
The website for which this content is the source materials is available at <https://stat555.berkeley.edu/fall-2024>.

For instructors: please see [these instructions](https://github.com/berkeley-scf/stat999-quarto#instructions-for-course-staff) on how to use this repository.


### Some extra resources

Poll Everywhere:
https://rtl.berkeley.edu/services-programs/student-response-systems/instructors-getting-started-poll-everywhere