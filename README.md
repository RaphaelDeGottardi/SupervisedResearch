# SupervisedResearch Project on Google Trends Data

## Topic:
Analysis of Google search trends for measures of magical thinking
in response to economic shocks.
### Environment
This repository contains an `environment.yml` file. It can be used by conda to create an identical environment as used for the analysis. Use the following command to create the environment:

```bash
conda env create -f environment.yml
```

The environment will be named `SR`.

### Scripts
- **Data Download**: 
  - The data download was done using the script: `GT_data_loader.ipynb` (see the Troubleshooting section for difficulties).

- **Analysis**:
  - The analysis can be found in: `GT_brexit.ipynb`
    - General EDA and plots are found in the submission.
    - Spearman correlation evaluation.

### Troubleshooting
Pytrends is not an official API from Google, thus Google will frequently detect the data download as bots (error 429). Please refer to the following sources which provide guidance on how to bypass this issue:
- [Pytrends on PyPI](https://pypi.org/project/pytrends/)
- [Stack Overflow: Pytrends error 429](https://stackoverflow.com/questions/50571317/pytrends-the-request-failed-google-returned-a-response-with-code-429)
- [GitHub Issue on Pytrends 429 Error](https://github.com/GeneralMills/pytrends/issues/538)

For us, it worked to just try multiple times and use various VPN connections.

**Note**: Downloading the data is not necessary as we provide it in the repository.

