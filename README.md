# OVRPCD---Files

In this repository, you will find the codes, instances and results used in the article:

#### Optimizing Vehicle Scheduling and Routing in a Cross-Docking Center with Multiple Docks. Cota, P. M.; Nogueira, T.H. ; Juan, A.A.; Ravetti, M.G.  Submitted, 2020.

## Algorithms

The programming language used is C++ with the optimization software CPLEX 12.4. 

### Constructive Heuristics (PIFHA and CDHA), and Lagrangian Heuristic (LH):

The Lagrangean heuristic(LH) uses the constructive heuristics PIFHA and CDHA. Thus, to obtain the result of all three proposed heuristics, it is only necessary to execute the MainHF.run, the other two files are called by the main file and must be in the same execution folder.

Download algorithm: [MainHF.run](https://drive.google.com/drive/folders/1Sx6HECJwkWzPvEHHu6Cs20dYMEFGjI7L?usp=sharing) 

Download algorithm CDHA: [MainCDTSPR.sa1](https://drive.google.com/drive/folders/1Sx6HECJwkWzPvEHHu6Cs20dYMEFGjI7L?usp=sharing) 

Download algorithm PIFHA: [MainCDTSP.sa1](https://drive.google.com/drive/folders/1Sx6HECJwkWzPvEHHu6Cs20dYMEFGjI7L?usp=sharing) 

### Instances

Instances were generated in three scenario: Balanced; Scenario with a stressed vehicle routing problem; and Scenario with a stressed scheduling problem. For each scenario, we generate four subdivisions (Divided into small, medium and large scale) with 11 instances each, totalizing 132 instances. 

For a better understanding of the scenarios, see the article. For understanding and using the instances, first consult the example file. It contains the description of each item of the test instances.

Example:[Exemplo.dat](https://drive.google.com/drive/folders/1mv2PGR33RRFrgTU7gMtc4m1loXaHql_Q?usp=sharing)


|Scenario|subdivision|File |
|:-------------:|:-------------:|:-------------:|
| 1 | | 1 | [1.1](https://drive.google.com/drive/folders/1jdTwFcXplby5nRVDtvOpjUz9N3dZY6GW?usp=sharing) |
| 1 | | 2 | [1.2](https://drive.google.com/drive/folders/1M3zf-y9gZvsFvGPEifVe3EgwY8lTyqyx?usp=sharing) |
| 1 | | 3 | [1.3](https://drive.google.com/drive/folders/1plOkefkUdJ7l-W9uqFvmRkCXer2GLZfv?usp=sharing) |
| 1 | | 4 | [1.4](https://drive.google.com/drive/folders/14FGmVZS-_XZSXFida9mckyh_JaGa9X92?usp=sharing) |
| 2 | | 1 | [2.1](https://drive.google.com/drive/folders/1gtE0s333syeNJKAy4AI2SXqlZZw7DNiF?usp=sharing) |
| 2 | | 2 | [2.2](https://drive.google.com/drive/folders/1XnbigutcgKnr2XyGgn2muhW2uWL49GjU?usp=sharing) |
| 2 | | 3 | [2.3](https://drive.google.com/drive/folders/187hMhGNBQuH4MBb0cZNJiTou45ofyQSy?usp=sharing) |
| 2 | | 4 | [2.4](https://drive.google.com/drive/folders/1gfJOJ0RC3hk4jlOXrvm9EghP2-eufTXY?usp=sharing) |
| 3 | | 1 | [3.1](https://drive.google.com/drive/folders/1513pSVU3Sd5UCDB9rfwWs7zGj2b5fTA5?usp=sharing) |
| 3 | | 2 | [3.2](https://drive.google.com/drive/folders/12dJev8yhXiPzcEkRqX2vcLRTgR3Y670S?usp=sharing) |
| 3 | | 3 | [3.3](https://drive.google.com/drive/folders/1MLbizk62NoLI6wDRwQHSvwP_gNliSBAW?usp=sharing) |
| 3 | | 4 | [3.4](https://drive.google.com/drive/folders/176IkMXlrkYHBqaLShsN-6v7WhcLiO0Q-?usp=sharing) |


### Results for the heuristics

Following we report computational results of each instance in a table with Lower Bound, PIFHA, CDHA, and LH respectively.

Results: [TableResults.xlsx](https://drive.google.com/drive/folders/1IODqCf-8atw1c435AIblrGo4kaT7IJOx?usp=sharing) 




