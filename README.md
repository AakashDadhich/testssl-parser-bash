# Testssl.sh-2-Text
Quick and dirty bash script to parse testssl.sh .log files into a .txt file, sorting affected hosts by which vulnerabilities/misconfigurations were identified. This script comes in particularly handy when you have many testssl.sh log files to parse through.

Currently rewriting in Python using the in-built CSV library to parse the CSV, which will improve the efficiency (and readability) of the code significantly. 
