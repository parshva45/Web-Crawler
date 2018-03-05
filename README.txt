- The two tasks of the IR HW1 are placed seperately in two directories:
Task 1 and Task 2

- Each directory consists of:

1) One python file (the one that needs to be run).

2) A directory named "Logs" having a text file containing
   information such as seed, keyword (in case of focused crawling),
   a list of URLs along with the depth at which they were crawled,
   number of results and maximum depth of crawling reached.

   Note - This directory and its content get created automatically by
          the program.

3) A directory named "Raw_HTML_Downloads" which contains files in
   plain text format of all the documents found while crawling.

   Note - This directory and its content get created automatically by
          the program. However, the code segment that creates this directory
          and its content has been commented. Downloading of the documents
          can easily be done by just uncommenting the code segment and running.
          Make sure to delete these directory before running the program to
          prevent mixing of previous and upcoming results.

Setup :

- You should have a Python programming environment set up on your machine.
- You should have the Requests and Beautiful Soup modules installed.

Before running the code:

- In case you wish to download the documents too, make sure to delete
  "Raw_HTML_Downloads" directory before running any of the programs
  from Task 1 and Task 2 to prevent mixing of previous and upcoming results.

Run the code:

- If you are using some text-editor like Sublime, just open the python file
  with the text editor and Build it.
- An alternate way is to run from your terminal or Comand Prompt. Got to the
  directory where the python file resides and use the command
  > python file-name.py
  to run. In our case, it would be:
  > python crawler.py (for Task 1) and
  > python focused-crawler.py (for Task 2)

Results:

The results are generated in "Logs" and "Raw_HTML_Downloads" directories
