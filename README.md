# DNA Data Storage

## Overview
This repository contains Python scripts to convert digital files into a DNA-based storage format. It includes functions to:
- Convert a file into binary format
- Encode binary data into a DNA sequence
- Decode DNA back into binary format (future implementation)

This project is inspired by the concept of **synthetic DNA storage**, which aims to provide a long-term, sustainable solution for digital data storage.

## Features
- **File to Binary:** Converts a file into an 8-bit binary format and saves it as a `.txt` file.
- **Binary to DNA:** Maps binary pairs to DNA bases (A, C, G, T) and stores the sequence in a file.

## File Structure
```
├── file_to_dna.py      # Main script for conversion
├── binary_output.txt   # Example binary output
├── dna_output.txt      # Example DNA sequence output
├── DNA Data Storage.pptx  # Presentation on the concept
└── README.md           # Project documentation
```

## Installation
Ensure you have Python installed on your system.

```bash
pip install -r requirements.txt  # (if any dependencies are added)
```

## Usage
Run the script with:
```bash
python file_to_dna.py input_file
```
Replace `input_file` with the actual file you want to convert.

## Future Scope
- Implement **DNA to Binary** conversion.
- Develop a full **restore mechanism** to retrieve original files.
- Improve efficiency and error correction in DNA encoding.

## References
This project is based on the concept of **DNA Data Storage**, as outlined in the attached PowerPoint presentation.

## License
This project is open-source and available for academic and research purposes.

## Acknowledgments
Special thanks to **BVERSITY** for inspiration and knowledge on **synthetic DNA storage**.

