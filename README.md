# An Analysis On Spinrate and Pitcher Performance

Ever since StatCast was introduced into the baseball world, tracking of miscelleaneous statistics and data have never been more plentiful. A particular statistic I want to explore is the spin-rate on fastballs for pitchers since 2015 (when StatCast kept track of spin-rates). In short, spin-rate is the amount of complete revolutions a baseball makes once it is released from a pitcher's hand until it reaches the catcher's glove. Spin-rate is measured in RPM's or revolutions per minute.

It has also been speculated that many pitchers use foreign substances on the baseball to generate more spin on their pitches. Foreign substances such as pine-tar, sunscreen, or even a mixture of sticky stuff have been used as a source for competitive advantage. While this is not necessarily true of all pitchers, pitchers such as Trevor Bauer have even gone on record and admitted publicly that using sticky substances have proven to generate more spin on their pitches. Most other pitchers claim that having a tacky grip on a baseball is primarily for controlling their pitches and not for generating more spin.


<p align="center"> <img src="https://static01.nyt.com/images/2021/06/12/sports/12mlb-balldoctoring-toptest3/merlin_152020689_e3eae897-592c-4833-a1c4-f7b8e79ada6c-facebookJumbo.jpg"  width="400" length = "400" />


## The Goal

I wanted to take a closer look at the spin rates on fastballs for pitchers in MLB. In this notebook, my goal is to explore the wide range of visual analysis with the Pandas library and to comment on the spin-rate trends that may be apparent in MLB. Additionally, I want to specifically explore Gerrit Cole, a pitcher for the New York Yankees, and his performance metrics for the 2021 season. 

## The Dataset

The dataset was retrieved from [Baseball Savant](https://baseballsavant.mlb.com/) and can be filtered to provide the fastball and spin rate data relevant to purposes of this notebook. 
