# SupervisedResearch
Project on Google trends data for the SR course at ETHZ

Topic:

Environment:
This repository contains an environment.yml file. It can be used by conda to create an identical environment like we used for the analysis. for this use the command:

conda env create -f environment.yml

The environment will be named SR

Scripts:
The data download was done using the script

GT_data_loader.ipynb (see troubleshooting section for difficulties)

The analysis can be found in the

GT_brexit.ipynb -General EDA, and plots found in the submission
                - Spearman correalation evaluation 

Troubleshooting:
Pytrends is not an official API form Google, thus google will frequently detect the data download as bots (error 429). Please refer to following sources which provide guidance on how to bypass this issue:
https://pypi.org/project/pytrends/
https://stackoverflow.com/questions/50571317/pytrends-the-request-failed-google-returned-a-response-with-code-429
https://github.com/GeneralMills/pytrends/issues/538 

For us, it worked to just try multiple times and use various VPN connections.

Note that downloading the data is not necessary as we provide it in the repository.