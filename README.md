Code for The Annotated Transformer blog post:

http://nlp.seas.harvard.edu/2018/04/03/attention.html


## Other downloads at start up

1. Create a conda environment using the `environment.yml` file
    ```
    conda env create -f environment.yml
    ```
2. Activate conda environment
    ```
    conda activate nlptorch
    ```

3. Download english, and german language things?
    ```
    python -m spacy download en
    python -m spacy download de
    ```

4. Check if can load both these languages in a ipython shell
    ```
    ipython
    > import spacy
    > en = spacy.load("en")
    > de = spacy.load("de")
    ```