# README
## Citation
Chatanaka MK, Soosaipillai A, Morato X, Diamandis A. Human Kallikrein 6 in the cerebrospinal fluid of patients with progressive and 
non-progressive Alzheimer’s disease. 2025. _in preparation._

## Scripts
The script, raw data and clinical information used to generate figures and results 
in the manuscript is provided in this repository. 
- [Statistical analysis and visualization file](./KLK6_ELISA_data_analysis.ipynb)

## Technology requirements
Users should have access to a computer with admin privileges. For a smooth experience running Python scripts and handling data throughout an entire session, 
consider the following minimum specifications:

**RAM**: 8GB. This ensures smooth operation when running multiple applications and handling data-intensive tasks.

**Storage**: A minimum of 50GB of available storage space. While an HDD is sufficient, an SSD is highly recommended for improved performance, 
especially when working with large datasets and multiple development environments.

**CPU**: A modern dual-core processor, such as an Intel Core i3 or AMD Ryzen 3. This will efficiently handle development workloads and tasks involving Python packages and software tools.

**Operating System**: Any modern operating system that supports Python is required. This includes Windows 10 or newer, macOS (High Sierra 10.13 or newer), or a stable Linux distribution. 
Avoid using ChromeOS, Android OS, and iPadOS, as they are not suitable for out-of-the-box usage and require extensive setup that is not 
practical for most Users.

**Note**: The set-up described here was done in a Windows 10 operating system. For macOS, please consult the equivalent links

## Installation Guide
All analyses were run in Visual Code Studio (VS Code) v1.104.0, Python v3.9.15, using the packages detailed in the "Python Session Info" section below.

Instructions on how to install VS Code, Jupyter Notebook and Python extensions can be found here: 
- [Download Visual Code Studio](https://code.visualstudio.com/download)
- Install VS Code extensions: [Download Jupyter Notebook](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter), [Download Python extension](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
The extensions will appear under the Extensions tab (four-square icon).

To install packages used in the analysis, follow this guide: [Python packages installation]()

## Instructions for Use
The python script is provided as a Jupyter Notebook (ipynb) file and is intended to be run in order chunk by chunk to ensure all variables have been appropriately defined for downstream analyses. In sections where data are loaded from local directories (own computer), Users will have to specify  the file location (marked in the script file). Following these steps, the figures and statistical results can be reproduced.

## System requirements
Python v3.9.15

Platform:

Running under: Windows 10 x64 (build )

## Package Information

| Package  | Version |
| ------------- | ------------- |
| numpy  | 1.26.4  |
| matplotlib  | 3.9.1  |
| pandas  | 2.2.3  |
| scipy  | 1.13.1  |
| seaborn  | 0.13.2  |
| statsmodels  | 0.14.4  |
| dateutil  | 2.9.0.post0  |


