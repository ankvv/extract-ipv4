# extract_ipv4
This Python program extracts IPv4 addresses from a specified input file and saves them to an output file. The program can optionally filter out duplicate IP addresses, returning only unique addresses.

## Features
- Extracts IPv4 addresses from a text file.
- Option to return only unique IP addresses.
- Outputs the extracted IP addresses to a specified file.

## Prerequisites
- Python 3.x

## Usage
You can run this program from the command line with the following syntax:

```bash
python ip_extractor.py -i <input_file_path> -o <output_file_path> [-u <true|false>]
```
## Parameters
- -i: Specify the input file path from which to extract the IP addresses (required).
- -o: Specify the output file path where the extracted IP addresses will be stored (required).
- -u: Specify whether to return only unique IP addresses. Defaults to true. Set to false to include non-unique addresses.

## Example
To extract unique IP addresses:
```bash
python ip_extractor.py -i input.txt -o output.txt -u true
```
To extract all IP addresses (including duplicates):
```bash
python ip_extractor.py -i input.txt -o output.txt -u false
```

## Notes
If the output file already exists, it will be removed before writing the new data.
The input file should contain text data with potential IPv4 addresses scattered throughout.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contributions
Contributions are welcome! Please feel free to fork the repository and submit a pull request.

## ⭐ Like this project?
If you find it helpful, please give it a star! ⭐️ It helps others discover this project and motivates me to keep improving it.

### 🌟 Current Stars: ![GitHub stars](https://img.shields.io/github/stars/ankvv/extract_ipv4?style=social)
