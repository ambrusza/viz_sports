## viz_sports_python

![](https://komarev.com/ghpvc/?username=ambrusza&style=for-the-badge&color=red)

<div id="badges">
  <a href="https://twitter.com/ambrusz_a">
    <img src="https://img.shields.io/badge/Twitter-blue?style=for-the-badge&logo=twitter&logoColor=white" alt="Twitter Badge"/>
  </a>
</div>


Visualization of data extracted from sports - mainly with python and matplotlib

1. theme - ([go to code](Clustering_Teams))

**Clustering teams** 

we want to group the teams basically according to their xG Points and their Points -
for this we use kMeans clustering, previously we determined the number of groups in 6 clusters

![nb219_cluster_GITHUB](https://user-images.githubusercontent.com/66861232/214641478-3e4fcca8-55c3-423b-9987-a512412b8455.png)



2. theme - ([go to code](PowerSpace_xG_Real_NB1))

**Power Space** - based on real performance and calc xG perfomance

The team with the most points is 100% - the value of the others is relative to them. We were looking for a gap between the total value of the teams and 200% (real 100% + xG 100%)

Questions:

- How big is the gap?
- In which direction is greater or balanced?             


![powerSpace NB2](https://user-images.githubusercontent.com/66861232/214352588-79b15a7a-316f-44db-aba6-8985cefcd2cb.png)


3. theme - 

the points scored by the teams in relation to the total points that can be scored in the 5-match grouping

plus: mood change according to loss aversion/prospect theory measured in util  -            **comparative**          ([go to code](points_VS_utils/))


![2020_21Season_percentageTeam](https://user-images.githubusercontent.com/66861232/211208975-f1b9a56e-c90c-4593-a2f7-3190456de510.png)


![2020_21Season_UTIL_Team](https://user-images.githubusercontent.com/66861232/211208982-22863576-b3a7-4a7e-9d3c-8bb672cd05bc.png)



4. theme - Random walk with the positions - **comparative**        ([go to code](random_walk_with_rankings/))

![randomWalkNb2_19forduló](https://user-images.githubusercontent.com/66861232/208676527-e23fed80-9b67-408b-829f-14eb29a8b108.png)


5. theme - Real table vs. xG table - **comparative**      ([go to code](realAndxGCalc_tab/))


![Képernyőfotó 2022-11-23 - 19 33 21](https://user-images.githubusercontent.com/66861232/203622468-52a76f98-8a0d-4411-8ad4-5d46f69bcdb0.png)


6. theme - xG Match flow          ([go to code](matchXg_flow/))

![Képernyőfotó 2022-11-24 - 15 16 36](https://user-images.githubusercontent.com/66861232/203805892-dfddb5c3-3422-4e8a-a69e-edfedb3f0ae9.png)


7. theme - position of teams per round - **comparative**      ([go to code](teamsPosition/))

![Képernyőfotó 2022-11-29 - 10 15 18](https://user-images.githubusercontent.com/66861232/204488679-d7c638aa-5ca4-4f74-9857-ee9232bc57c5.png)
