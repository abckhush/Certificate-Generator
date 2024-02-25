# Certificate Generator
As a volunteer for the workshop, "Intellectual Property Rights" organized by Rajiv Gandhi Institute of Petroleum Technology (RGIPT), sponsored by the Council of Science & Technology, Uttar Pradesh, I have been appointed the task of generation of certificates. This repository contains a Python script to generate certificates for the same.

## Usage
1. Ensure you have Python installed on your system.
2. Clone this repository to your local machine.
   ```bash
   git clone https://github.com/yabckhush/certificate-generator.git
3. Prepare a CSV file (names.csv) with a list of participant names.
4. Edit the generate_certificates.ipynb script to customize the certificate template and output folder.
5. Run the script to generate certificates.
6. The generated certificates will be saved in the specified output folder.

## Certificate Template
The certificate template (template.png) should be a PNG image file with placeholders for participant names. The script will automatically insert participant names into the template.

## Requirements
- Python 3.x
- OpenCV (cv2) library

## Limitations
The program currently supports only one template and one font style and size. The program does not support batch printing of certificates.
