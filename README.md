# XML Parser
This XML parser GUI tool is developed as a project for CSE323-Data Structures and Algorithms course.
# How to Use:
This GUI requires PyQt5 to run. To run the GUI, you need to run the final.py file.
# List of Contributers
* AbdulRahman Mostafa fouad Ibrahim   1600758
* Neven Nabil Shokry                  1601626
* Mohamed AbdulRahem Mohamed Saber    1601227
* Ibrahim Gamal Ibrahim AbdulRady     1600007

# Idea
XML (Extensible Markup Language) is one of the most famous formats for storing and sharing
information among different devices. Some text editors such as Sublime Text are able to parse
such files and do some basic operations. In this project, you will work on developing a GUI
(Graphical User Interface) based program to parse and visualize an XML file

# Main requirements
● Building a GUI in which the user can specify the location of an input XML file.
● Checking the XML consistency: The input XML may have inconsistencies like missing
any of the closing and opening tags or not matching tags.The program should be able to
detect and visually show any errors in consistency. Optimally, the program will also be
able to automatically solve the errors.
● Formatting (Prettifying) the XML: the XML file should be well formatted by keeping the
indentation for each level.
● Converting XML to JSON: JSON (Javascript Object Notation) is another format that is
used to represent data. It’s helpful to convert the XML into JSON, especially when using
javascript as there’s tons of libraries and tools that use json notation.
This is the result of converting the XML
example input into JSON.
● Minifying the XML file: Since spaces and newlines (\n) are actually characters that can
increase the size of an XML document. This feature should aim at decreasing the size of
an XML file (compressing it) by deleting the whitespaces and indentations.
● Compressing the data in the XML/JSON file: You should come-up with a way to reduce
the size of the file using a data compression technique. You can invent your own ad-hoc
method for such compression. On the other hand, you can check how JSONH works and
try to distill ideas from it. Finally, you can use a data compression technique such as byte
pair encoding (https://en.wikipedia.org/wiki/Byte_pair_encoding).
The smaller the output file is, the more efficient your algorithm is.

# Why is the project worth doing
In this project, you will learn how to understand and parse XML and json files. Additionally, you
will work on designing a GUI (Graphical User Interface) to visualize XML and json files. You
should also work on designing the program such that it makes use of optimal data structures for
the implemented features.
