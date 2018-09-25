# The Avenue Concept Database

This repository captures the current state of the Avenue Concept's artwork database. The database is built on top of Zoho Creator. The file in this repository captures the structure of the Zoho application, including field definitions and business logic.

## Exporting

Whenever the database is edited significantly, make sure to export a copy of the application, replace the **Artworks_Database.ds** file in this repository, and commit the changes. Keep in mind:

- Only known good states of the database should be committed to the `master` branch of this repository. Experiments, tests, and other developments should be committed to their own branch, called `feature-{{ x }}` where `x` is the name of the feature you're testing. **Do not commit a database definition that doesn't run.**

To export a database file, the zoho creator needs to be in the "old version" interface. At the left hand panel in the old interface, click `Settings` and then `General`. At the top right, outside of the actual settings form, you'll see a button called `Export Application`. Click that, and add the resulting `Artworks_Database.ds` file to the repository.

## Importing

To import a database file, you need [to create a new application, and import the `.ds` file into it](https://www.zoho.com/creator/help/script/import-deluge-script.html). Following that, [you'll need to import your data into the application](https://www.zoho.com/creator/help/views/import-and-export-data.html).
