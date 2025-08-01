Take Home Assessment

🔧 Steps Completed

1)Data Inspection & Cleaning

  -Created a Jupyter Notebook to explore and validate the datasets.
  -Identified inconsistencies (e.g. unit mismatches) and updated the data accordingly based on project type (generation, storage, grid, etc.).

2)Dataset Preparation

  -Saved the cleaned and updated datasets as .csv files.
  -Uploaded the datasets into Retool for further visualization.

3) CSV-to-Retool SQL Pipeline (New Step)

-Developed a Python pipeline to automate CSV uploads into the Retool-hosted PostgreSQL database.
-Used SQLAlchemy and pandas to:

  Read local .csv files
  Connect securely to the Retool PostgreSQL instance using the provided connection string

-Upload the data into SQL tables (projects, publications, etc.)

-Enabled future integration with automated or recurring data updates.

4)Retool App Development

  -Built two Retool pages:
    -Projects Page: Displays a searchable and filterable table of energy projects.
    -Publications Page: Displays a searchable and filterable table of publications.

5)Interactive Drawer for Details

  -Implemented row click events for both tables.
    -When a row is clicked, a Drawer component expands to show additional details of the selected project or publication.

✨ Features
✅ Search and filter functionality on both tables.
✅ Dynamic drawer showing full row details.
✅ Easy CSV data integration into Retool.
✅ Clean separation of views for projects and publications.
✅ Python pipeline for uploading cleaned CSV data into Retool Database
