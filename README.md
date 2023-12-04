# JCSS.DATA

## Introduction
JCSS.DATA is a repository for data relevant to structural safety, which can be accessed by researchers, students and practitioners. Data sets can be uploaded by individual contributors. It is an initiative of the Joint Committee on Structural Safety (JCSS). 


The data sets are grouped into 5 categories, which can be found in 5 separate folders:
- Data on loads
- Data on material properties
- Data on structure failure 
- Inspection data
- Other data
 
 ## Download a data set
There are multiple ways to download a data set：
- Above the lists of all files, click the green icon `Code`, and then choose `Download Zip` in the dropdown list. In this way, the whole database will be downloaded to your local computer.       
- To download a single file, first go to the file you want to download, then click it to view the contents within the GitHub UI. On the top right, click the `Raw` button. Finally, right click and save the file.
- Git users can clone the repository to their local computer with HTTPS or SSH.

## Upload a data set
#### Documentation for submission
When uploading a data set, make sure that it is properly documented. An examplary data set named **Data-concrete-Tongji** is given in the folder **Data on material properties**. \
Any submission should include the following:
- Data (mandatory): Any **documented text-based format** is acceptable.
- README.md (mandatory): To make the data set easier to use, contributors should provide the following information in the README.md file:
    - **Data format**：It is best to use formats that can be easily read in with Matlab, Python, etc. 
    - **Description**: A specific description of the data set should be included in the README.md file.
    - **Data source**
    - **Contact information**
    - **Citation (if there is any)**
    - **License (if there is one)**
    - **additional documentation**
- License (strongly recommended): It is highly recommended that contributors include a license in their documentation. Otherwise, the uploaded data set is by default under a [CC BY-NC-SA 4.0 license](https://creativecommons.org/licenses/by/4.0/). The [License Selector](https://ufal.github.io/public-license-selector/)  can be useful in identifying a proper license.
- Additional documents, such as background reports and papers, can be included.
  
All documentation for submission should be included in one **single folder**.

#### How to upload a data set
There are two ways of uploading a dataset:
1. First, copy the JCSS.DATA repository to your github account by clicking the `Fork` button on the top right of the official JCSS_Database repo. Then upload the data set folder to the JCSS.DATA in your account (See how [here](https://github.community/t/add-a-folder/2304)). After this is done, change to the `Pull request` module and click the green button `New pull request` to issue a pull request for us to review the changes and to merge your changes in the copied repo. into the original JCSS.DATA repository.
3. In the official JCSS.DATA repository, change to the `Issues` module and click the green button `New issue` to create an issue, which will notify us. We will then add your data set (a single folder) to the repo.

## License
Unless otherwise stated by the contributors, all data sets from the JCSS_Database is under a CC BY-NC-SA 4.0 license. A brief summary of the license can be found [here](https://creativecommons.org/licenses/by/4.0/). 

## Links to external databases
The following are other databases, which provide data relevant to structural safety:
- [International Society of Soil Mechanics and Geotechnical Engineering (ISSMGE) TC304 Database](http://140.112.12.21/issmge/tc304.htm) is a publically available database for investigating inherent spatial variability and mechanic properties of soil and rocks.  
- [Transportation Networks for Research](https://github.com/bstabler/TransportationNetworks) is a repository of real-world transportation networks primarily meant for static traffic assignment.
- [Extreme Winds and Wind Effects on Structures](https://www.itl.nist.gov/div898/winds/homepage.htm) is a website that provides datasets and software for analysis of extreme wind speeds and other extreme phenomena in wind engineering.
