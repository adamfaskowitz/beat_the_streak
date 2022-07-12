# My Attempt to Beat the Streak!

The longest hit streak in Major League Baseball history belongs to Joe Dimaggio in 1941, with Joe recording a hit in 56 straight games. Probabilistically, what he accomplished was quite the feat (the next longest streak in MLB history is a "paltry" 45, accomplished in 1896)!

To understand how unlikely his magical run was, let's dive into the numbers:

For a hitter with an average** of 0.25, given they receive 4 plate appearances a game, the probability of them getting at least one hit in 56 staight games is:

***
    P(at least one hit in a 56 straight games) = P(at least one hit in one game) ** 56 
    P(at least one hit in one game) = 1 - P(no hits in one game)
                                    = 1 - ((3/4) * (3/4) * (3/4) * (3/4))
                                    = 1 - 0.3
    P(at least one hit in one game) ≈ 0.7
    P(at least one hit in a 56 straight games) = 0.7 ** 56 
    ≈ 0.00000000021159, aka basically impossible
  
***

Additionally, this calculation is even too simplistic because it does not take into account non-hit outcomes that would lower this probability even more.

*average*** *= percent of the time they get a hit = (# of hits) / (# of at-bats)*

Because it is essentially unattainable, the MLB puts out a challenge every year awarding $5.6 million to anyone who can beat Joe's streak. The challenge allows you to choose a player every day who you think will get a hit. Pick 57 straight correctly and you can win $5.6 million. Spoiler alert: no one has ever won.

In this project, I create a model that assists me in choosing players who are most likely to record a hit, in hopes of shifting the probability in my favor. 

### Putting my model to the test, I was able to achieve a streak of 29, ranking me 3rd in the world at that time!

<img src="https://user-images.githubusercontent.com/31783686/178377864-400150a3-86ff-4a6e-84cb-16c796f914cb.jpg" width="300">
