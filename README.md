# SupervisedResearch
Project on Google trends data for the SR course at ETHZ

Topic:

Environment:


Scripts:


Troubleshooting:
Pytrends is not an official API form Google, thus google will frequently detect the data download as bots (error 429). Please refer to following sources which provide guidance on how to bypass this issue:
https://pypi.org/project/pytrends/
https://stackoverflow.com/questions/50571317/pytrends-the-request-failed-google-returned-a-response-with-code-429
https://github.com/GeneralMills/pytrends/issues/538 

For us, it worked to just try multiple times and use various VPN connections.

Note that downloading the data is not necessary as we provide it in the repository.