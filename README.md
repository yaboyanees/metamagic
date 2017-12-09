# metamagic
This workflow automatically tags files as they are uploaded and moved around in sharepoint based on their file path. This makes it easier for users to take advantage of custom views and metadata without the painful process of filling out forms one file at a time. 

## To get started
1. Attach this workflow to any document library
2. Add the following columns:
+Folder: Single line of text
+Sub Folder 1: Single line of text
+Sub Folder 2: Single line of text
+Sub Folder 3: Single line of text
+Sub Folder 4: Single line of text
+CurrentPath: Single line of text
3. Use Your Saved time on making custom views

## How it works
1. The workflow splits the file path to extract folder names
2. Iterates over each and assigns values 5 levels down
3. Waits for changes to update the columns when necessary
