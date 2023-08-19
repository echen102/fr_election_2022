# fr_election_2022

The repository contains an ongoing collection of tweets IDs associated with the 2022 French election. This dataset spans 04/03/2022 - 05/15/2022, which covers the weeks leading up to and after the election held on 04/10/22 and 04/24/22. We leveraged Twitter’s streaming API to follow specified accounts and also collect in real-time tweets that mention specific keywords. To comply with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), we are only publicly releasing the Tweet IDs of the collected Tweets. The data is released for non-commercial research use. 

The associated paper to this repository can be found here: [How Does Twitter Account Moderation Work? Dynamics of Account Creation and Suspension During Major Geopolitical Events](https://arxiv.org/abs/2209.07614)

## Data Organization
The Tweet-IDs are organized as follows:
* Tweet-ID files are stored in folders that indicate the year and month of the collection (YEAR-MONTH). 
* Individual Tweet-ID files contain a collection of Tweet IDs, and the file names all follow the same structure, with a prefix “french-election-2022-” followed by the YEAR-MONTH-DATE-HOUR. 
* Note that Twitter returns Tweets in UTC, and thus all Tweet ID folders and file names are all in UTC as well. 


# Data Usage Agreement / How to Cite

8/18/23 Note: Arxiv Author list has not been updated to reflect the most up to date list. 

This dataset is licensed under the Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International Public License ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)). By using this dataset, you agree to abide by the stipulations in the license, remain in compliance with Twitter’s [Terms of Service](https://developer.twitter.com/en/developer-terms/agreement-and-policy), and cite the following manuscript: 

Francesco Pierri, Luca Luceri, Emily Chen and  Emilio Ferrara. 2022. How Does Twitter Account Moderation Work? Dynamics of Account Creation and Suspension During Major Geopolitical Events. arXiv:cs.SI/2209.07614

BibTeX:
```bibtex
@misc{pierri2022twitter,
      title={How Does Twitter Account Moderation Work? Dynamics of Account Creation and Suspension During Major Geopolitical Events}, 
      author={Francesco Pierri, Luca Luceri, Emily Chen and Emilio Ferrara},
      year={2022},
      eprint={2209.07614},
      archivePrefix={arXiv},
      primaryClass={cs.SI}
}
```
