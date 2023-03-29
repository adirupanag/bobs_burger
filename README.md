## Bob's Burgers Episode Analysis
This repository contains code to scrape IMDb website and analyze the episode ratings of the American animated sitcom, "Bob's Burgers".

The code was written in R programming language using several packages such as rvest, dplyr, xml2, stringr, robotstxt, ggplot2, and forcats. The scraped data is saved as a CSV file, bobs_burger_episode.csv.

## Scraping
The scraping.Rmd file contains the code to scrape the IMDb website and extract the episode data for all 12 seasons of Bob's Burgers. The code iterates over each season and extracts the episode title, rating, number of ratings, summary, and season number. The scraped data is then saved as a CSV file.

## Analysis
The analysis.Rmd file contains the code to analyze the episode data. The code cleans the summary column by removing newline characters and adds an episode number column. It then identifies the top 5 episodes of all 12 seasons.
<img width="999" alt="Screen Shot 2023-03-27 at 3 49 37 PM" src="https://user-images.githubusercontent.com/44686660/228051523-d1047ebb-0aec-430b-a6d4-b348641b3736.png">
We can observe that the most popular episodes of the television show are situated in Season 5 and Season 6. Interestingly, these seasons encompass exceptional episodes that revolve around both Louise and Bob, two of the show's central characters.

Let us go into the least favored episodes of the show.
<img width="970" alt="Screen Shot 2023-03-27 at 3 50 28 PM" src="https://user-images.githubusercontent.com/44686660/228052098-f5129f5f-c136-4f01-b5f3-febe57253b57.png">

It is noteworthy that the episodes that have been ranked as the least favored not only have the lowest number of ratings, but also come from a specific time period within the show's run, specifically spanning from Season 10 to Season 12. These episodes, which predominantly feature the characters of Gene and Linda in the spotlight, have failed to garner the same level of appreciation from viewers as their counterparts in other seasons.

Does the lower audience ratings for the episodes in Season 10 to Season 12 suggest a decrease in the show's overall quality? ![download](https://user-images.githubusercontent.com/44686660/228053611-40853902-9925-48d6-9dd4-79b4ea1c5d71.png)
We see that the quality is overall the same, but it does have a small dip in the later seasons as we expected.

Is there a discernible decrease in the number of ratings or votes for the show over time?

By examining the number of ratings for a show on IMDB, we can get an idea of how engaged the audience is with the show and how invested they are in its success. This can provide insight into the show's popularity among the specific population of IMDB users who vote, allowing us to make inferences about the show's overall appeal.
![download2](https://user-images.githubusercontent.com/44686660/228054637-7230394f-4994-4add-b752-b7a433fe9e1d.png)

Do certain characters of the show receive higher audience favorability or preference compared to others, and if so, which characters are most favored?
![download 3](https://user-images.githubusercontent.com/44686660/228055040-07da9c24-dbe4-4cac-9dee-4def66dc54c3.png)
It appears that, on the whole, the characters of the show enjoy similar levels of audience approval. However, there seems to be a slight preference for the character of Bob over others.

Let us explore the relative popularity of each character within the show's storylines, based on the frequency of their appearances or mentions. This analysis will provide insight into which characters the show's writers have chosen to feature more prominently, and may shed light on audience preferences for certain characters.
![download4](https://user-images.githubusercontent.com/44686660/228055862-24e9413d-cebb-4761-bad8-85636a259d9e.png)
An examination of the frequency with which characters are mentioned or featured in the show's storylines reveals some interesting trends. Notably, the character of Gene appears to be consistently the least mentioned throughout the show's run, while Tina experiences a significant spike in mentions during Season 6, a season that is widely regarded as one of the show's best. Unsurprisingly, given that the show is named after his character, Bob emerges as the most popular and prominent character overall.

While the frequency of mentions of each character varies significantly across seasons, it is also important to examine whether the audience's perception of these characters changes from season to season. By analyzing the average ratings of the mentions of each character, we can gain insights into how the audience's perceptions of the characters evolve over time.

Therefore, we can investigate whether the favorability or negativity towards each character shifts from one season to the next, and whether there are any discernible patterns or trends. By examining changes in audience perception over time, we can better understand how the characters in Bob's Burgers resonate with viewers and whether certain characters are more likely to generate positive or negative sentiment in specific seasons.
![download5](https://user-images.githubusercontent.com/44686660/228631897-e15b736b-7fd1-4518-9084-2fab532c2758.png)
The general perception of the characters remains relatively consistent across seasons, with no significant shifts in overall favorability. However, some patterns do emerge when examining the data. For instance, Gene consistently ranks as the least favorite character, while Tina and Bob are consistently among the most favored. Linda, on the other hand, falls somewhere in the middle.

Interestingly, the data reveals a somewhat volatile perception of Louise, with notable spikes in favorability in certain seasons. Overall, these trends suggest that while the characters in Bob's Burgers are generally well-liked, there are subtle variations in audience perception that can be observed over time. 


## Usage
To use the code, you need to have R and the required packages installed. You can run the scraping.Rmd file to scrape the IMDb website and create the bobs_burger_episode.csv file. Then run the analysis.R file to analyze the data and create the plots. The code in the analysis.R file assumes that the bobs_burger_episode.csv file is in the same directory.

## Credits
This code was written by Adirupa Nag. The data was scraped from the IMDb website. Bob's Burgers is created by Loren Bouchard and produced by Bento Box 
