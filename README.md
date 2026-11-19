# A Novel Approach to Studying the Role Influence Plays in Team Collective Intelligence

by Lisa R. O'Bryan, T. Oxendahl, S. Garnier, Santiago Segarra, W. Wettergreen, A. Sabharwal, and M. E. Beier.

This code replicates the data processing steps and analyses presented in *Collective Intelligence*, 4(2) ([view article](https://journals.sagepub.com/doi/10.1177/26339137251343584)).

## Summary

In this paper, we present an objective measure of individual influence over team decision-making during a virtual engineering design challenge. In our study, participants used the platform [Line Rider](https://www.linerider.com/) to solve a virtual design challenge with measurable performance outcomes. Solutions take the form of 2D tracks through an obstacle course. Participants first created individual-level solutions independently. They then worked together to design a single group-level solution. We measure influence as the objective similarity between the team-level solution and each individual's initial individual-level design. Our results show that teams tended to converge on a single member’s idea rather than integrate all ideas equally. Individual influence over the team solution was driven by initial idea quality (expertise), hands-on work contributions (screen control time), and how closely an initial idea aligned with mean of all team members’ ideas. Speaking time and dominance did not directly correlate with individual influence, although both were positively correlated with hands-on work contributions. Teams achieved higher performance when their most influential member had greater expertise and contributed more hands-on work. The code presented here enables the processing of 2D tracks extracted from the Line Rider platform, the calculation of our objective influence measure, and analyses examine the association between individuals' characteristics and their influence measures and the association between the characteristics of a team's most influential member and the team's performance and collective intelligence.

## Software implementation

All R scripts for data processing and statistical analyses are located in the `R Code` folder, and the corresponding datasets are located in the `Data` folder.
