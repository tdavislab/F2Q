# F2Q: Flowchart to Questionnaire

One of the main applications of F2Q is to increase access to justice via visualiization. One of the main barriers to access to justice is the lack of awareness of legal rights, procedures, and available resources. We develop F2Q (Flowchart to Questionnaire), an open-source toolbox for legal experts or staff members at legal clinics or help centers (oftentimes with no programming expertise) to easily design and automatically generate web-based interactive questionnaires. Such questionnaires help guide the clients of these help centers, oftentimes minorities and underserved populations without legal representation, through a series of questions that could help them correctly categorize their legal problems and identify appropriate  remedies or solutions. Using F2Q, they can be easily modified in case of changes to the law and regulations. 
These questionnaires serve as a virtual assistant to provide initial guidance to possible solutions and to direct the clients to a legal expert at the help center for further assistance. Most importantly, this efficient process prevents potential clients from giving up their quest for justice due to the lack of awareness: when people do not know what questions to ask and where to seek answers, they give up and live with the injustice. F2Q aims to break down, or at least weaken, such barriers.

This repository provides the source code for the designer tool that enables users to design a questionnaire via a flowchart, as well as the web-based  interactive questionnaire. 


## Installation 
Download or clone this repository:

```bash
git clone https://github.com/tdavislab/F2Q.git
cd F2Q
```

#### To run the user interface:
```bash
cd user-interface
python3 -m http.server 8080
#Hit Ctrl+c to quit
```
You can view the page at http://[::]:8080/ (If possible, please use Chrome).

#### To run the designer tool:
```bash
cd designer-tool
python3 -m http.server 8000
#Hit Ctrl+c to quit
```

You can view the page at http://[::]:8000/  (If possible, please use Chrome).
