
# FIFA 22 Ultimate Team Recommender

## Overview

This is project using Python to scrap FIFA player data from an open
source website [SoFIFA](https://sofifa.com/) and apply automated
non-interacitve scripts to process crawled data, then fit models to
player statistics to setup a recommender (With UI) of players in FIFA22
given user inputs as constraints eg. budget, potential, attribute and
etc.

## Authors:

**Chloe Zhang**:

-   [GitHub](https://github.com/ZiyueChloeZhang)

**Tony Liang**:

-   <chunqingliang@gmail.com>

-   [GitHub](https://github.com/tonyliang19)

## Usage of the project (Instructions)

#### 1. Without using Docker

To replicate this project, clone this GitHub repository, install the
[dependencies](#dependencies) listed below, and run the following
command at the command line/terminal from the root directory of this
project:

    make all

To reset the repo to a clean state, with no intermediate or results
files, run the following command at the command line/terminal from the
root directory of this project:

    make clean

## Dependencies

-   Python 3.10.4 and Python packages:
    -   beautifulsoup4=4.11.1
    -   bs4=0.0.1
    -   certifi=2021.10.8
    -   chardet=4.0.0
    -   charset-normalizer=2.0.12
    -   idna==3.3
    -   numpy=1.22.3
    -   pandas=1.4.2
    -   pathlib=1.0.1
    -   python-dateutil=2.8.2
    -   pytz=2022.1
    -   requests=2.27.1
    -   six=1.16.0
    -   soupsieve=2.3.2.post1
    -   urllib3=1.26.9
-   R version 4.1.3 and R packages:
    -   docopt=0.7.1
    -   knitr=1.38
    -   rlang=1.0.2
    -   rmarkdown=2.13
    -   tidyverse=1.3.1
-   GNU make 4.3

## License

The underlying source code used to format and display the content of
this project is licensed under the [MIT License](LICENSE)
