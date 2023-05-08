#!/bin/bash
# Step 1: Navigate to the directory where the files are located
cd ~/project/that.md/
echo that.md
# step 2: Loop through each file with .txt extention
for file in *.txt; do
# step 3: Get the filename without extention
filename="${file%.*}"
# step 4: Rename the file with .md extention
mv "$file" "{file%.txt}.md
done
