# worm-scrape
This program scrapes the story [Worm](https://parahumans.wordpress.com/) written by WildBow.

## Running the program
Simply download this [jar](worm-scrape/java-worm-scrape.jar) file. This program will do all the work.
The result is an output.txt file that is in the same directory as the .jar file when it is run. After the program is done running, the ouput.txt file will contain a line at the very bottom that says "The program ran for # minutes and # seconds."

If you are running Linux or Mac, you need to have Java installed to compile and build the jar file to run the code.

## Possible problems
1) No checking is performed in this program, it assumes that you have an internet connection and can connect to the website.
2) Run time depends on your internet connection and computer. It runs at an average of 3 minutes and 30 seconds in my computer and connection.
3) Assumes that you have Java installed and can run this jar. SDK version is 1.8 and jsoup 1.1.

## To do:
- [ ] Do proper exception and checking.
- [ ] Implement a simple GUI.
- [ ] Convert .txt file into EPUB.
