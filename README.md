# Bank
Bank Project in Python

The Bank will require the following:
1. Computer / Laptop
   Minimum Requirements:
   Operating System: Microsoft Windows 7 or above, Mac OS X 10.11 or higher, and Linux
   600 Mhz Processor, Intel Atom® processor or Intel® Core™ i3 processor
   1GB RAM
   Disk Space : About 2GB
2. Python 3.6 and above
3. MySQL

Note - For Windows operating system, to support coloured text uncomment the first 3 lines(as given in instructions).

Copy the code and save it in a suitable text editor in the py extension.The code uses some external libraries so please run the following commands on CMD/Terminal before executing the program:

pip3 install datetime
pip3 install tabulate

(For windows please see the “For Windows” section in the end before doing the following step)

Then cd to the file location and run

python3 <filename>.py

Please run through the terminal because it might not run directly from editors like idle/jupyter notebook due to different pythonpath locations.

For Windows: We are using ANSI color codes to colour code our input and output. ANSI is not supported by Windows by default so to enable them please uncomment these 3 lines in the top before running.
  
import ctypes
kernel32 = ctypes.windll.kernel32
kernel32.SetConsoleMode(kernel32.GetStdHandle(-11), 7)

