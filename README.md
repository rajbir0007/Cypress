# Cypress
Renaming cypress reporter result files according to their corresponding spec.js file name.

The high-level idea of this process is to rename a set of XML files based on the values contained in each file. This is achieved by first iterating over the array of XML files located in a specified folder. For each XML file, the file is converted to a JSON object, allowing the script to extract the desired value, which in this case is the “spec file name”. Once the spec file name has been extracted from the XML file, the script renames the file using this value. By following this process for each XML file in the specified folder, all files will be renamed according to their respective spec file names.
