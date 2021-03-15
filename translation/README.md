# Code to help with translations
#The automate_translation.sh file is a Bash script (so you’d open Terminal and run it), and it looks like it chains together several steps, like:
  * Pulling from the Google sheet (wget loads a URL’s page) yielding a CSV
  * Convert the CSV to a JSON
  * Cleans the resulting data (looks like modifyJSON.py reads the JSON as a dataframe, removes rows with empty first column and takes out the \r newline character)
