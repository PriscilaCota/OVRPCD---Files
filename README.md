# OVRPCD---Files

In this repository, you will find the codes, instances and results used in the article:

#### Integrating Vehicle Scheduling and Routing decisions in a Cross-Docking Center with Multiple Docks. Cota, P. M.; Nogueira, T.H. ; Juan, A.A.; Ravetti, M.G.  Submitted, 2021.

## Algorithms

The programming language used is C++ with the optimization software CPLEX 12.4. 

### Constructive Heuristics (VRCDH and CDVRH), and Prioritization Lagrangian Heuristic (PLH) - without uncertainty:

The Lagrangean heuristic(LH) uses the constructive heuristics PIFHA and CDHA. Thus, to obtain the result of all three proposed heuristics, it is only necessary to execute the MainHF.run, the other two files are called by the main file and must be in the same execution folder.

Download algorithm: [MainHF.run](https://drive.google.com/drive/folders/1Sx6HECJwkWzPvEHHu6Cs20dYMEFGjI7L?usp=sharing) 

Download algorithm CDHA: [MainCDTSPR.sa1](https://drive.google.com/drive/folders/1Sx6HECJwkWzPvEHHu6Cs20dYMEFGjI7L?usp=sharing) 

Download algorithm PIFHA: [MainCDTSP.sa1](https://drive.google.com/drive/folders/1Sx6HECJwkWzPvEHHu6Cs20dYMEFGjI7L?usp=sharing) 

### Instances - without uncertainty

Instances were generated in three scenario: Balanced; Scenario with a stressed vehicle routing problem; and Scenario with a stressed scheduling problem. For each scenario, we generate four subdivisions (Divided into small, medium and large scale) with 11 instances each, totalizing 132 instances. 

For a better understanding of the scenarios, see the article. For understanding and using the instances, first consult the example file. It contains the description of each item of the test instances.

Example:[Exemplo.dat](https://drive.google.com/drive/folders/1mv2PGR33RRFrgTU7gMtc4m1loXaHql_Q?usp=sharing)


|Scenario|subdivision|File |
|:-------------:|:-------------:|:-------------:|
| 1 | 1 | [1.1](https://drive.google.com/drive/folders/1jdTwFcXplby5nRVDtvOpjUz9N3dZY6GW?usp=sharing) |
| 1 | 2 | [1.2](https://drive.google.com/drive/folders/1M3zf-y9gZvsFvGPEifVe3EgwY8lTyqyx?usp=sharing) |
| 1 | 3 | [1.3](https://drive.google.com/drive/folders/1plOkefkUdJ7l-W9uqFvmRkCXer2GLZfv?usp=sharing) |
| 1 | 4 | [1.4](https://drive.google.com/drive/folders/14FGmVZS-_XZSXFida9mckyh_JaGa9X92?usp=sharing) |
| 2 | 1 | [2.1](https://drive.google.com/drive/folders/1gtE0s333syeNJKAy4AI2SXqlZZw7DNiF?usp=sharing) |
| 2 | 2 | [2.2](https://drive.google.com/drive/folders/1XnbigutcgKnr2XyGgn2muhW2uWL49GjU?usp=sharing) |
| 2 | 3 | [2.3](https://drive.google.com/drive/folders/187hMhGNBQuH4MBb0cZNJiTou45ofyQSy?usp=sharing) |
| 2 | 4 | [2.4](https://drive.google.com/drive/folders/1gfJOJ0RC3hk4jlOXrvm9EghP2-eufTXY?usp=sharing) |
| 3 | 1 | [3.1](https://drive.google.com/drive/folders/1513pSVU3Sd5UCDB9rfwWs7zGj2b5fTA5?usp=sharing) |
| 3 | 2 | [3.2](https://drive.google.com/drive/folders/12dJev8yhXiPzcEkRqX2vcLRTgR3Y670S?usp=sharing) |
| 3 | 3 | [3.3](https://drive.google.com/drive/folders/1MLbizk62NoLI6wDRwQHSvwP_gNliSBAW?usp=sharing) |
| 3 | 4 | [3.4](https://drive.google.com/drive/folders/176IkMXlrkYHBqaLShsN-6v7WhcLiO0Q-?usp=sharing) |


### Results for the heuristics

Following we report computational results of each instance in a table with Lower Bound, PIFHA, CDHA, and LH respectively.

Results: [TableResults.xlsx](https://drive.google.com/drive/folders/1IODqCf-8atw1c435AIblrGo4kaT7IJOx?usp=sharing) 

-------------------------------------------------------------------------------------------------------------------------------------------------------


### Robust Dynamic Prioritization Lagrangian Heuristic (RDPLH) - under uncertainty:

Incorporate uncertainties into this OVRPCD to use Lagrangian heuristics (LH) to achieve more applicable results to real cross-docking centers. Uncertainties are included in the trucks' arrival time at the CDC and in the travel time to go to the customer. It is only necessary to execute the MainHF-Dinamic.run, the other three files are called by the main file and must be in the same execution folder.


Download algorithm DLH: [MainHF-Dinamic.run](https://drive.google.com/file/d/1puIzlRnPogVetTnm0uPvwIKMjtjgG4QW/view?usp=sharing) 

Download algorithm LH: [MainLag-Dinamic.sa1](https://drive.google.com/file/d/1axM4mjDbYj9HIg-4X5T18gP1uu1rMJLu/view?usp=sharing) 

Download algorithm CDHA: [MainCDTSPR-Dinamic.sa1](https://drive.google.com/file/d/1n96UqxRndLefWzw-_SLMs_Nk0S-kp5sT/view?usp=sharing) 

Download algorithm PIFHA: [MainCDTSP-Dinamic.sa1](https://drive.google.com/file/d/1pniQvNPVg7eRo5hf0bNxnyht3q7Oxga_/view?usp=sharing) 


### Instances - under uncertainty

Instances were generated in three scenario: Balanced; Scenario with a stressed vehicle routing problem; and Scenario with a stressed scheduling problem. For each scenario, we generate four subdivisions (Divided into small, medium and large scale) with 11 instances each, totalizing 132 instances. 

For a better understanding of the scenarios, see the article. For understanding and using the instances, first consult the example file. It contains the description of each item of the test instances.

Example:[Exemplo-Dynamic.dat](https://drive.google.com/file/d/1cUjnJgVHK6ucev5I_he3j_CXe9Lkz5n0/view?usp=sharing)


|Group variation|subdivision|File |
|:-------------:|:-------------:|:-------------:|
| Small | 1 | [1.1](https://drive.google.com/drive/folders/1my6eTbQbIbyWwyYypIsNBOYn1eYnyQmX?usp=sharing) |
| Small  | 2 | [1.2](https://drive.google.com/drive/folders/1GA2xpoCDLCFEx6KmE-glUhl2My_HH5n0?usp=sharing) |
| Small  | 3 | [1.3](https://drive.google.com/drive/folders/16Hz8t40XCXVxUusAaVGfNxtUxKScVtuq?usp=sharing) |
| Small  | 4 | [1.4](https://drive.google.com/drive/folders/1YEPeDC9kbDH12uWEBhAWh4xaa64it94V?usp=sharing) |
| Medium | 1 | [1.1](https://drive.google.com/drive/folders/1_5gZpr_0Ba_pTRLDBQKipEiPyJktLFXq?usp=sharing) |
| Medium | 2 | [1.2](https://drive.google.com/drive/folders/1z-rJKzDQK1OGO1blRXZSx-eXU4gyrr5X?usp=sharing) |
| Medium | 3 | [1.3](https://drive.google.com/drive/folders/10Hyp-1PZ6jzMJZZXtFN5vu0pj80RJ50f?usp=sharing) |
| Medium | 4 | [1.4](https://drive.google.com/drive/folders/1Vyt3wMMTjgV-JUSQR8h3B9fDVTH4nHhu?usp=sharing) |
| Large | 1 | [1.1](https://drive.google.com/drive/folders/1cqJKP92dSTD72vzPXcj9vDdDtXGcSu4Z?usp=sharing) |
| Large | 2 | [1.2](https://drive.google.com/drive/folders/1VXWkr3OiyTV3V51u-Y2KWWh9fdST4Ycg?usp=sharing) |
| Large | 3 | [1.3](https://drive.google.com/drive/folders/1RWA41gPhyDk4LriYMwtzbhbd4lbFK7Li?usp=sharing) |
| Large | 4 | [1.4](https://drive.google.com/drive/folders/1D98dqN3yEtjVXAHEovmbN3GsRcRP5JFN?usp=sharing) |





Contact information

Priscila Mara Cota - priscila.maracota@gmail.com

Thiago Henrique Nogueira - thiagoh.nogueira@ufv.br

Angel A. Juan - ajuanp@gmail.com

Martin Gómez Ravetti - martin.ravetti@dep.ufmg.br





