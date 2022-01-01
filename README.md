# An Analysis On Spinrate and Pitcher Performance

Ever since StatCast was introduced into the baseball world, tracking of miscelleaneous statistics and data have never been more plentiful. A particular statistic I want to explore is the spin-rate on fastballs for pitchers since 2015 (when StatCast kept track of spin-rates). In short, spin-rate is the amount of complete revolutions a baseball makes once it is released from a pitcher's hand until it reaches the catcher's glove. Spin-rate is measured in RPM's or revolutions per minute.

It has also been speculated that many pitchers use foreign substances on the baseball to generate more spin on their pitches. Foreign substances such as pine-tar, sunscreen, or even a mixture of sticky stuff have been used as a source for competitive advantage. While this is not necessarily true of all pitchers, pitchers such as Trevor Bauer have even gone on record and admitted publicly that using sticky substances have proven to generate more spin on their pitches. Most other pitchers claim that having a tacky grip on a baseball is primarily for controlling their pitches and not for generating more spin.


<p align="center"> <img src="https://static01.nyt.com/images/2021/06/12/sports/12mlb-balldoctoring-toptest3/merlin_152020689_e3eae897-592c-4833-a1c4-f7b8e79ada6c-facebookJumbo.jpg"  width="400" length = "400" />


## The Goal

I wanted to take a closer look at the spin rates on fastballs for pitchers in MLB. In this notebook, my goal is to explore the wide range of visual analysis with the Pandas library and to comment on the spin-rate trends that may be apparent in MLB. Additionally, I want to specifically explore Gerrit Cole, a pitcher for the New York Yankees, and his performance metrics for the 2021 season. 

## The Dataset

The dataset was retrieved from [Baseball Savant](https://baseballsavant.mlb.com/) and can be filtered to provide the fastball and spin rate data relevant to purposes of this notebook. 

  
## Overall Observations & Conclusions 
  
  1. There is a slight correlation between average fastball speed and average fastball spinrate. However, there is no strong correlation between average pitch velocity and pitch spinrate. In general, throwing harder for breaking balls will result in a lower spinrate.  
<p align="center">
  <img src = "https://github.com/eric8395/pitching_analysis/blob/main/images/Screen%20Shot%202022-01-01%20at%205.47.22%20PM.png?raw=true" width="400" height="400">
</p>
<p align="center">
  <img src = "https://github.com/eric8395/pitching_analysis/blob/main/images/Screen%20Shot%202022-01-01%20at%205.47.49%20PM.png?raw=true" width="400" height="400">
</p>



2. MLB has seen an increase in pitchers allowing walks to batters between 2015 and 2021. In fact, 2021 saw a total of walks roughly equivalent to the 2017-2019 seasons. There is no strong indication that the crackdown on sticky substances has generated more or less walks. 

    * There is an indication that the game of baseball has seen a greater tendency for batters to walk. 

<p align="center">
  <img src = "https://github.com/eric8395/pitching_analysis/blob/main/images/Screen%20Shot%202022-01-01%20at%205.48.13%20PM.png?raw=true" width="700" height="300">
</p>    
    
3. There is a noticeable rise in hit by pitches each season since 2015. 2021 in particular, saw the greatest amount of hit by pitches (2016 hbp) since 2015. 

    * Pitchers are throwing harder than ever and may be relying on the grip of the baseball for control. The rise in hit by pitches can be partially attributed with the crackdown on sticky substances and rise of hard throwers in baseball. 

<p align="center">
  <img src = "https://github.com/eric8395/pitching_analysis/blob/main/images/Screen%20Shot%202022-01-01%20at%205.48.22%20PM.png?raw=true" width="700" height="300">
</p>    
    
4. There is evidence to suggest that the ban on foreign substances on baseballs in late June 2021 has impacted Gerrit Cole's performance. 

    * Since June 2021, Cole's average spinrate has decreased.
    * However, Cole's average fastball speed has increased; maybe compensating for his loss in spinrate. 
    
<p align="center">
  <img src = "https://github.com/eric8395/pitching_analysis/blob/main/images/Screen%20Shot%202022-01-01%20at%205.49.01%20PM.png?raw=true" width="550" height="400">
<p align="center">
  <img src = "https://github.com/eric8395/pitching_analysis/blob/main/images/Screen%20Shot%202022-01-01%20at%205.48.46%20PM.png?raw=true" width="550" height="400">
</p>    


    
