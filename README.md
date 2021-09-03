# FIS_reports

This repository hosts html outputs from R Bookdown reports of the FIS team at INBO

The url for this repository is https://inbo.github.io/fis-reports/


To add a new Bookdown report to this page, follow these steps:

1. Create a separate branch online on https://github.com/inbo/fis-reports

2. Switch to your new branch in the desktop version

3. Under the FIS_reports/Reports folder, create a new folder. Use the short title of your report as the name for this folder.
This name will appear as the project title on the homepage.

4. Paste the Bookdown output of your report under this folder (html files + supporting folders).

> make sure a file named index.html is present

5. Under the FIS_reports/Homepage folder open fisreports.Rproj file. Run the index.Rmd file trhough the 'Knit to gitbook' command.
This will generate a new index.html file in the FIS_reports root folder.

6. Commit your changes to your new branch in the GitHub desktop application

7. Create a pull request for your new branch and assign a reviewer

8. After your pull requested has been reviewed and approved, the branch can be merged into the master.

9. Delete the branch you created under step 1.

10. You report is now available online, congrats!
