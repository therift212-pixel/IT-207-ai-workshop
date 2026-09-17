# IT-207-ai-workshop
#ai work shop
#findFirst.js myhead.js, myrep.js
# project discritpon
This lightweight Node.js command-line utility replicates the core functionality of the classic Unix grep tool. Built using native modules like fs and path, the program processes command-line arguments to read specified text files, search for distinct text patterns, and print matching lines directly to the console. It includes input validation to display clear usage instructions when arguments are missing, along with support for an optional output limit to cap the number of returned lines. Designed for quick file filtering, the script provides a clean foundation for handling local file I/O, string manipulation, and process argument parsing.
#ai refelction
Overall, this is a solid, practical implementation of a custom grep utility in Node.js. It shows a clear understanding of basic file system I/O, process arguments, and string manipulation. While the logic bugs around argument handling and matching limits need addressing, the foundation is clean and readable. Fixing the line-limit counter, wrapping file reads in error handling, and adding flexible case-matching will take this from a functional prototype to a robust command-line tool.
