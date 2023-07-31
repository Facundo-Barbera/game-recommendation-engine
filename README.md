# Game Recommendation Engine: Analyzing a Video game Database

_Fancy name, huh?_
_Don't let it fool you, it's just a simple school project._

A project that I made for a teacher during a summer period. 
This project contains a series of data-driven analysis to determine which game is most suitable for my teacher to play next.

Note: This project was an extra credit assignment that I enjoyed doing. 
I decided to upload it to GitHub to show my work.

## Before running the code!

This project has a `reports` directory which contains an already generated report!
The report is made from exporting the Jupyter Notebook to HTML, so it's basically the same thing.

In case you want to play around with the code, you *will* need to install some dependencies
(a lot of thanks to jupyter).
If you have anaconda installed, then you _should_ be good to go.

In case you run this from a python environment, then do the following:

```bash
pip install -r requirements.txt
```
(Tip: type `pip install -r` and drag the `requirements.txt` file to the terminal to automatically write the path)

That should install all the dependencies you need to run the code.

## Running the code

You need to start a jupyter notebook server.
If you have anaconda installed or did the previous step, then you should be able to run the following command:

```bash
jupyter notebook
```

This should open a tab in your browser with the jupyter notebook server.
From there, you can navigate to the `notebooks` directory and open the `main.ipynb` file.

I recommend that you `cd` to the main directory of the project before running the command.
If you don't then you will have to search the `notebooks` directory manually (from where you run the command).

If you use PyCharm, then you can open the project and run the `main.ipynb` file from there.
Run *ALL* the cells in the notebook to generate the report.
If you don't, then the report will be incomplete.
If you run cells out of order, then you will get errors from missing dataframes or such.

## Introduction

This is a project for an analytics-driven course called "Análisis de Biología Computacional."
My teacher, Drao. Ella Raquel Acuña Gonzáles gave us a file called `videojuegos.xlsx`.
This file contains a database of video games, with the following columns:

| Column name   | Description                                                 |
|---------------|-------------------------------------------------------------|
| Game          | Name of the game                                            |
| First Release | The date of its first release                               |
| Platform      | The platform that my teacher has to play the game           |
| Re-release    | The date of the last update of the game                     |
| Developer     | The company that developed the game                         |
| Publisher     | The company that published the game                         |
| Genre         | The genre of the game                                       |
| Subgenre      | The subgenre of the game                                    |
| Main story    | The time it takes to complete the main story                |
| Main + extras | The time it takes to complete the main story and the extras |
| Completionist | The time it takes to complete the game 100%                 |
| Hours Played  | The time my teacher has played the game                     |
| % Completion  | The percentage of the game my teacher has completed         |
| Metascore     | The score that critics gave to the game                     |
| User Score    | The score that users gave to the game                       |
