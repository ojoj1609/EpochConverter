# EpochConverter

Desc: This is an executable jar to convert epoch time into human readable time ("MM/dd/yyyy HH:mm:ss"). Input and output utilising txt file.

Prerequisite: Install java 11 on system (https://phoenixnap.com/kb/install-java-windows)

Steps to execute jar:
1. Download the executable jar (epochConverter.jar)
2. Create a text file (name it input.txt)
3. Paste epoch value into input.txt, where one value is on one line only. Save the file.
4. Open a command prompt by searching for cmd in search bar
5. Validate java installed on system, run: java --version
6. Navigate to the directory where jar was downloaded, execute: cd <path_to_jar_folder>. e.g. "cd C:\Users\johnDoe\Downloads\epochConverter.jar"
7. Execute jar by passing location of input.txt file, execute: java -jar epochConverter.jar <path_to_input_file>. e.g. "java -jar epochConverter.jar C:\Users\johnDoe\Downloads\input.txt"
8. A file (output.txt) will be created in the same folder as input.txt, containing the converted value of epoch in human readable time.
9. To convert new values, repeat step 7 by replacing all values in input.txt with new values. output.txt file will be overriden with newly converted human readable time.
10. Enjoy!