# DUET

TP on the DUET algorithm for undetermined Sound Source Separation

## Python Initialization

Setup the virtual environment and install dependencies (tested on linux)

1. Open the console / terminal and go in you favorite folder
    ```bash
    $ cd path/to/dir`
    ```
2. git clone the repository and enter the folder
    ```bash
    $ git clone https://github.com/Chutlhu/VAI2020_TP_DUET`
    $ cd VAI2020_TP_DUET
    ```
3. instantiate the virtual environment:
    ```bash
    $ virtualenv venv -p python3`
    ```
4. activate it:
    ```bash
    $ source venv/bin/activate
    (venv) $
    ```
    The `(venv)` before the prompt simbol `$` denotes that you are inside the virtual environment
5. install dependencies and packages:
    ```bash
    (venv) $ pip install -r requirements.txt
    ```
6. launch the notebook:
    ```bash
    (venv) $ jupyter notebook
    ```

## The DUET Algorithm
The Degenerate Unmixing Estimation Technique (DUET) is a Sound Source Separation methods.
'Degenerate' refers to the underdetermined case of more sound sources than microphones, that is, mixtures.
We will assume here only 2 microphones


## References
[1] [The DUET Blind Source Separation Algorithm, Scott Rickard](https://link.springer.com/chapter/10.1007%2F978-1-4020-6479-1_8#page-1)

[2] [The DUET tutorial](https://users.cs.northwestern.edu/~pardo/courses/casa/papers/DuetSourceSeparationTutorial)

[3] [Blind Separation of Speech Mixtures viaTime-Frequency Masking, Özgür Yılmaz and Scott Rickard](https://users.cs.northwestern.edu/~pardo/courses/casa/papers/DUET.pdf)