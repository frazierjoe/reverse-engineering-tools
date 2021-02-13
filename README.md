# pe-tools

My toolkit for reverse engineering and malware analysis

## import-checker - searches a file of imports for malicious imports and prints those that regularly used in malicious programs along with a description
* List of possible malicious imports is from appendix A of Practical Malware Analysis by Michael Sikorski and Andrew Honig
* As with the list from the appendix, this does not include imports such as `ReadFile` that their purpose can be assumed

### Running the program
* Create a file with the name of the import placed on its own line
* Run the import checker `./import-checker/import-checker`
* Supply a path to your file when prompted
* Malicious imports will be printed to stdout
