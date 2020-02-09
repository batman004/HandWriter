<p align="center">
	<img src="https://user-images.githubusercontent.com/30529572/72455010-fb38d400-37e7-11ea-9c1e-8cdeb5f5906e.png" />
	<h2 align="center"> Handwriting Parser </h2>
	<h4 align="center"> Convert typed documents into handwritten PDFs <h4>
</p>

---
[![DOCS](https://img.shields.io/badge/Documentation-see%20docs-green?style=flat-square&logo=appveyor)](INSERT_LINK_FOR_DOCS_HERE) 
  [![UI ](https://img.shields.io/badge/User%20Interface-Link%20to%20UI-orange?style=flat-square&logo=appveyor)](INSERT_UI_LINK_HERE)

This project is *work in progress*


<br>

## Functionalities
- [ ] Convert a text document (.docx file) into a PDF file with the text content handwritten
- [ ] Feed your own handwriting to the application to generate PDF outputs in your handwriting

## Instructions to run

* Pre-requisites:
	-  python >= 3.0
	-  dependencies from requirements.txt
<br>

### Directions to install
First, clone this repository onto your system. <br>
Then, create a virtual environment and install the packages from requirements.txt: <br>
If virtualenv isn't installed on your system, install virtualenv:
```bash
pip install virtualenv --user
```
Navigate to this repository, create a virtual environment and activate it:
```bash
cd path/to/folder
virtualenv env
source env/bin/activate
```
Install the python dependencies from requirements.txt:
```bash
pip install -r requirements.txt
```
Finally, download the data file from [ here ](https://drive.google.com/open?id=1yaS8zwzgr8BtzUcgWfP_PqG1JljnTsbe)<br> 
Copy **hashes.pickle** to install directory. <br>

### Directions to run
Presently, the application has a CLI that takes path to document and output PDF path as arguments. For instance,
```bash
python src/document_parser.py /path/to/docx /path/to/pdf
```
<br><br>
The original dataset can be downloaded from [ here ](https://drive.google.com/file/d/10pFgeiL4FOrIaqp-r2_d6kM62g4X8zYf/view?usp=sharing)- but it is password protected. Request access from [ SaurusXI ](https://github.com/SaurusXI/)
<br>


<br>

## Contributors

* [ Shantanu Verma ](https://github.com/SaurusXI/)


<br>
<br>

<p align="center">
	Made with :heart: by DSC VIT
</p>

