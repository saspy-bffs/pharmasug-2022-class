[![Python 3.7](https://img.shields.io/badge/python-3.7-brightgreen.svg)](#prerequisites)  [![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)  [![Gitter](https://img.shields.io/gitter/room/saspy-bffs/community.svg?color=777777)](https://gitter.im/saspy-bffs/community)


# Everything is Better with Friends: Using SAS in Python Applications with SASPy and Open-Source Tooling (Beyond the Basics)


### Materials from a Half-Day Class at [PharmaSUG](https://www.pharmasug.org/us/) in Austin, Texas, on May 21, 2022.

Materials provided:
  - Examples and Exercises as interactive Google Colab Notebooks:
    - [Part 1](https://colab.research.google.com/drive/1ophFN64mLAXTGivlf4y6HeWP6n4-bPFp#offline=true&sandboxMode=true)
    - [Part 2](https://colab.research.google.com/drive/1K8Jzy8ksiw9JkHK2OmMWP7N1xb-zoWGN#offline=true&sandboxMode=true)
    - [Part 3](https://colab.research.google.com/drive/1x375TZViS2h2Q5JaS-Pqan_lu3fGlb3v#offline=true&sandboxMode=true)
    - [Part 4](https://colab.research.google.com/drive/1WksihEIR3NB8ktRqzrTpDKWH-Rodgcj_#offline=true&sandboxMode=true)
    
  - Solutions to all Exercises as interactive Google Colab Notebooks:
    - [Part 1](https://colab.research.google.com/drive/19lKR6M5v9uidRRh4p92rfqPyH2ILtDkc#offline=true&sandboxMode=true)
    - [Part 2](https://colab.research.google.com/drive/1sBRblgoHAxjh8qsan_Twj2IVCZpsumQF#offline=true&sandboxMode=true)
    - [Part 3](https://colab.research.google.com/drive/1udKM6OxJqNIUGOwpfjzZ-qrEXHlUrP4I#offline=true&sandboxMode=true)
    - [Part 4](https://colab.research.google.com/drive/1Dhj6zlYHu1qxIwdB1qm0a-JJm60q-kEN#offline=true&sandboxMode=true)

  - Solutions to all Exercises as PDF files:
    - [Part 1](solutions/Part1-Solutions-Everything_is_Better_with_Friends-Beyond_the_Basics.pdf)
    - [Part 2](solutions/Part2-Solutions-Everything_is_Better_with_Friends-Beyond_the_Basics.pdf)
    - [Part 3](solutions/Part3-Solutions-Everything_is_Better_with_Friends-Beyond_the_Basics.pdf)
    - [Part 4](solutions/Part4-Solutions-Everything_is_Better_with_Friends-Beyond_the_Basics.pdf)

  - [Slides](slides/Slides-Everything_Is_Better_With_Friends-PharmaSUG2022_Seminar.pdf) as a PDF file


## Setup Instructions & Prerequisites

### Accounts Needed

In order to interact with code examples, accounts for the following two online services will be needed:

- Google
  - We'll be using Google accounts to run code examples in [https://colab.research.google.com/](https://colab.research.google.com/)
  - If you don't already have a Google Account, you can create one for free at [https://accounts.google.com/signup](https://accounts.google.com/signup) 

- SAS OnDemand for Academics (ODA)
  - We'll be accessing ODA accounts from Google Colab, which will require you to know the Region associated with your ODA account. (The Region for an ODA account is typically displayed in the upper-right corner after logging in.)
  - If you don't already have an ODA account, you can create one for free at [https://welcome.oda.sas.com/](https://welcome.oda.sas.com/)
  - Note: To create an ODA account, you will also need a SAS Profile account. If you don't already have a SAS Profile account, you can create one for free using the "Don't have a SAS Profile?" link on the ODA login page.

To test your setup, please follow the instructions in our [Setup Test Colab Notebook](https://colab.research.google.com/drive/12KqxwnRm7IoFpShnD2UnhrJEP31KiGHD#offline=true&sandboxMode=true). If desired, you can use the __File__ -> __Save a Copy in Drive__ command to save a copy of the results.

All in-class examples assume the use of Google Colab and ODA, and we will not be able to provide support for any other setup. However, if you're interested in using a local SASPy environment, with Python talking to a commercial SAS installation, you're welcome to follow the setup instructions for the demo application [https://github.com/saspy-bffs/dataset-explorer](https://github.com/saspy-bffs/dataset-explorer)


### Attendee Prerequisites

This class is designed for intermediate to advanced SAS programmers, but assumes only basic familiarity with Python syntax and `pandas` DataFrames. No knowledge of JupyterLab is assumed. (For a refresher on Python, you're welcome to look through the materials from our [Getting Started](https://colab.research.google.com/drive/1OfdSTm5T_xEUQU2cAHWi7ORH4YWf7s3p#offline=true&sandboxMode=true) class.)

We also recommend a relatively new computer with a broadband internet connection and a modern web browser.


## Learning Outcomes

After successfully completing this class, we will be equipped for the following:

-	Using Google Colab for Python script development, including linking to SAS OnDemand for Academics to access the SAS analytical engine
-	Using SAS and Python together with SASPy, include understanding the trade-offs of completing common data-science tasks in SAS and Python.
-	Rectangularizing complex JSON-formatted data returned by web APIs.
-	Building simple Python web applications utilizing SAS analytics.


## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


## Authors
* [ilankham](https://github.com/ilankham)
* [mtslaugh](https://github.com/mtslaugh)


## Disclaimer

This project is in no way affiliated with SAS Institute Inc.
