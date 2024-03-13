# OpenSTEF workshop

This OpenSTEF workshop repository contains two workshops: a beginner workshop where no coding is required and a more advanced workshop where you through exercises you get to know OpenSTEF. Both contain the same three notebooks: ``Workshop_1_train_model``, ``Workshop_2_make_forecast``, and ``Workshop_3_perform_backtest``. 

It is also recommended to look at the presentation of the workshop, to gain some basic understanding of OpenSTEF. You can find the presentation [here](https://github.com/OpenSTEF/openstef-workshop/blob/main/OpenSTEF_workshop_presentation.pdf). 

## Pre-knowledge

Participants of the beginner workshop do not need any pre-existing knowledge. 

Participants of the advanced workshop are expected to have basic knowledge on [Jupyter Notebook](https://jupyter.org/) and Python.

## Preparation

### Beginner

1. Download the repository (find an elaborate guide [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)). 
2. Open an online notebook interface such as google collab or jupyter lab.
3. Upload the data.
4. Have fun with the workshop!

### Advanced

Preparation for Windows

1. Download the repository (find an elaborate guide [here](https://docs.github.com/en/repositories/creating-and-managing-repositories/cloning-a-repository)). Remember the destination location. For example `C:\Users\YourUserName\Downloads\openstef-workshop`.
2. Install [Python 3.10](https://www.python.org/downloads/release/python-31013/).
3. Open a terminal (Windows-Key + R, type cmd, press OK) and use the cd (change dir) command to navigate to the folder where you downloaded the workshop. For example:

```shell
C:\Users\YourUserName> cd Downloads\openstef-workshop
C:\Users\YourUserName\Downloads\power-grid-model-workshop>
```

4. Optional: create and activate a virtual environment. This helps to keep your system clean.

```shell
> python -m venv venv
> venv\Scripts\activate
```

5. Install the requirements (openSTEF and Jupyter):

```shell
pip install -r requirements.txt
```

6. Run Jupyter notebook. This will either open a browser or the console output will tell you where to find the jupyter notebook server. Alternatively, if you are for example working in Visual Studio Code or PyCharm, you can open the openstef-workshop foler manually.

```shell
> jupyter notebook
```

7. Try the workshop files by opening any of the ```.ipynb``` files and pressing the ``>>`` (run all) button.
Note that in the files not ending with ``_answers``, there are exercises where you have to fill in some code. These notebooks will thus work without you doing these exercises.

## License

This project is licensed under the Mozilla Public License, version 2.0 - see LICENSE for details.

## Contributing

Please read [CODE_OF_CONDUCT.md](https://github.com/OpenSTEF/.github/blob/main/CODE_OF_CONDUCT.md), [CONTRIBUTING.md](https://github.com/OpenSTEF/.github/blob/main/CONTRIBUTING.md) and [PROJECT_GOVERNANCE.md](https://github.com/OpenSTEF/.github/blob/main/PROJECT_GOVERNANCE.md) for details on the process for submitting pull requests to us.

## Contact

Please read [SUPPORT.md](https://github.com/OpenSTEF/.github/blob/main/SUPPORT.md) for how to connect and get into contact with the OpenSTEF project.
