# FIFA World Cup 2018
We're in the midst of the 2018 FIFA World Cup. I've wanted to play with some sort of sports-related data for a while, so I figured now is as good as a time as any to start. Take a look at [my blog post](https://www.johnwmillr.com/fifa-world-cup-data/) for more details.

## Collecting the data
After doing some Googling for World Cup APIs, I came across the [Sportradar API](https://developer.sportradar.com/io-docs). Sportradar provides 15 APIs for soccer data alone. Luckily, they [provide a free tier](https://developer.sportradar.com/member/register) for the APIs that allows for 1,000 queries each month. I wrote a simple class to interface with the soccer API and download the data I needed.

## Visualizations
I was interested in the relationships between height and weight and player positions after seeming this [great post](https://www.reddit.com/r/dataisbeautiful/comments/1oh47i/height_and_weight_of_all_active_nfl_players_by/) looking for similar patterns in the NFL.

[![Distributions of height for the different positions in soccer](./figures/height_by_position.png)](https://www.reddit.com/r/dataisbeautiful/comments/8sg3ok/distributions_of_height_for_the_different)