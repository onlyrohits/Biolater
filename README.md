# OMOP2OBO

This repository provides code to map different sources of clinical data to the [Open Biomedical Repositories](http://www.obofoundry.org/).

Please see the [Project Wiki](https://github.com/callahantiff/BioLater/wiki) for more information!

**UPDATE:** Mapping is complete and a manuscript is in progress. All mappings will be publicly available once the manuscript is submitted.


<br>

#### This is a Reproducible Research Repository
This repository contains more than just code, it provides a detailed and transparent narrative of our research process. For detailed information on how we use GitHub as a reproducible research platform, click [here](https://github.com/callahantiff/PheKnowVec/wiki/Using-GitHub-as-a-Reproducible-Research-Platform).

<img src="https://img.shields.io/badge/ReproducibleResearch-AbraCollaboratory-magenta.svg?style=flat-square" alt="git-AbraCollaboratory">

### Project Stats

![GitHub contributors](https://img.shields.io/github/contributors/callahantiff/Biolater.svg?color=yellow&style=flat-square) ![Github all releases](https://img.shields.io/github/downloads/callahantiff/Biolater/total.svg?color=dodgerblue&style=flat-square)

<br>

______
### Getting Started

**Dependencies**  
This repository is built using Python 3.6.2. To install the libraries used in this repository, run the line of code
shown below from the within the project directory.
```
pip install -r requirements.txt
```
This software also relies on owltools

**Data**  
This repository assumes that input data files contain code which relies on Google's [DriveAPI](https://developers.google.com/drive/) and [SheetsAPI](https://developers.google.com/sheets/api/).

There are several important
-  that multiple codes are separated by a "|"
- umls_api key file
-google sheets API



<!--### Installation

<!--To install and execute the program designate the cloned project folder as the current working directory. Place any outside <!--files within the working directory prior to executing the program.-->


## Contributing
Please read [CONTRIBUTING.md](https://github.com/callahantiff/biolater/blob/master/CONTRIBUTING.md) for details on our code of conduct, and the process for submitting pull requests to us.


## License

This project is licensed under MIT License - see the [LICENSE.md](https://github.com/callahantiff/Biolater/blob/master/LICENSE) file for details.  

<!--
**Citing this Work:**  
```
@misc{callahan_tj_2019_3401437,
  author       = {Callahan, TJ},
  title        = {Biolater},
  month        = mar,
  year         = 2019,
  doi          = {10.5281/zenodo.3401437},
  url          = {https://doi.org/10.5281/zenodo.3401437}
}
```   


## add note on running `resources/programming/google_api/quickstart.py` to authenticate google sheet  

-->   
