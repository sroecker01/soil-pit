---
output:
  html_document: default
---
# Pedon report

```r
# Set soil series
series <- "Miami"

# Set percentiles
p <- c(0, 0.25, 0.5, 0.75, 1)
```






```
## NOTICE: multiple datums present
## NOTICE: duplicate horizons in query results, matching pedons:
## 1954IL111001
## converting Munsell to RGB ...
## mixing dry colors ... [3 of 41 horizons]
## mixing moist colors ... [74 of 878 horizons]
## replacing missing lower horizon depths with top depth + 1cm ... [1 horizons]
## finding horizonation errors ...
## horizon errors detected, use `get('bad.pedon.ids', envir=soilDB.env)` for a list of pedon IDs
```


## Brief summary of pedon data

![plot of chunk Map of pedons and locations](figure/Map of pedons and locations-1.png) 



|pedon_id       |taxonname |tax_subgroup        |part_size_class |pedon_type                         |describer                                         |
|:--------------|:---------|:-------------------|:---------------|:----------------------------------|:-------------------------------------------------|
|S1953IN177002  |MIAMI     |missing             |missing         |missing                            |missing                                           |
|S1982IL029040  |MIAMI     |typic hapludalfs    |fine-loamy      |missing                            |missing                                           |
|S1981IN011002  |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |missing                                           |
|S1981IN011006  |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |missing                                           |
|S1981IN011012  |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |missing                                           |
|S1981IN011016  |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |missing                                           |
|S1982IN107001  |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |Bill Hosteter                                     |
|S1982IN107002  |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |Bill Hosteter                                     |
|S1982IN107005  |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |Bill Hosteter and Doug Wolf                       |
|S1982IN107006  |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |Bill Hosteter and Doug Wolf                       |
|78IN177007     |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Williams and Blank                                |
|78IN177008     |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Williams and Blank                                |
|84IN157023     |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Mark McClain                                      |
|84IN157024     |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Tom Ziegler                                       |
|83IL039008     |Miami     |typic hapludalfs    |fine-loamy      |missing                            |missing                                           |
|84IN015011     |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Bill Hosteter and Earnie Jensen                   |
|87IN107001     |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |WD Hosteter, Douglas Wolfe                        |
|87IN107008     |Miami     |typic hapludalfs    |fine-loamy      |missing                            |B. Hostetler, J. Shively                          |
|88MI059003     |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |missing                                           |
|90IL045001     |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |R. Leeper and J. Brewbaker.                       |
|1968IN011001   |Miami     |missing             |missing         |missing                            |Sanders and Franzmeier                            |
|1968IN011007   |Miami     |missing             |missing         |missing                            |Sanders and Langlois                              |
|1968IN113001   |Miami     |missing             |missing         |missing                            |Franzmeier                                        |
|1968IN139001   |Miami     |missing             |missing         |missing                            |Zachary                                           |
|1969IN157001   |Miami     |missing             |missing         |missing                            |Meyers and Harlan                                 |
|1969IN157002   |Miami     |missing             |missing         |missing                            |Meyers and Harlan                                 |
|1977IN031004   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Shively                                           |
|1976IN151004   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Farmer                                            |
|1977IN177004   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Blank                                             |
|1977IN177008   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Blank and Meland                                  |
|1977IN177007   |Miami     |typic hapludalfs    |fine            |missing                            |Blank and Meland                                  |
|1975IN023002   |Miami     |missing             |missing         |missing                            |Hosteter and Fink                                 |
|1976IN033003   |Miami     |missing             |missing         |missing                            |Sanders and Jensen                                |
|1974IN151002   |Miami     |missing             |missing         |missing                            |Farmer and Hillis                                 |
|1975IN169004   |Miami     |missing             |missing         |missing                            |Landrum and Langer                                |
|1975IN169009   |Miami     |missing             |missing         |missing                            |Ruesch and Landrum                                |
|1978IN065004   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Hillis and Le masters                             |
|1978IN031001   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Shively                                           |
|1979IN135033   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Neely and Houghtby                                |
|1979IN135034   |Miami     |typic hapludalfs    |fine            |missing                            |Neely and Latowski                                |
|1978IN139008   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Brock and Rohleder                                |
|1977IN169017   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Langer and Schumacher                             |
|1978IN177007   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Williams and Blank                                |
|1978IN177008   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Williams and Blank                                |
|1980IN135063   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Neely and Latowski                                |
|1980IN139009   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Brock and Dalton                                  |
|1981IN085010   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Staley                                            |
|1983IN157001   |Miami     |typic hapludalfs    |missing         |missing                            |Ziegler and Franzmeier                            |
|1984IN171025   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Shively                                           |
|1981IN007027   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Barnes and Plank                                  |
|1981IN047014   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Shively                                           |
|1984IN157023   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Mcclain and Ziegler                               |
|1984IN157024   |Miami     |typic hapludalfs    |fine-loamy      |missing                            |Ziegler and Hosteter                              |
|1986IL113004   |Miami     |oxyaquic hapludalfs |fine-loamy      |map unit inclusion                 |CLL                                               |
|1986IL113001   |Miami     |oxyaquic hapludalfs |fine-loamy      |map unit inclusion                 |CLL                                               |
|1984IL029003   |Miami     |oxyaquic hapludalfs |fine-loamy      |representative pedon for component |RGD, SCM                                          |
|1984IL029109   |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |AP, GH                                            |
|1984IL147022   |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |missing                                           |
|1955-OH141-010 |Miami     |missing             |missing         |missing                            |Petro & Finney                                    |
|1954-OH141-005 |Miami     |missing             |missing         |missing                            |Petro, Garner, Baldridge                          |
|1955-OH141-012 |Miami     |missing             |missing         |missing                            |Petro & Finney                                    |
|1954-OH027-013 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |bone                                              |
|1953-OH049-S21 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |n. holowaychuk                                    |
|1955-OH027-036 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |wiseman, bone                                     |
|1955-OH027-037 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |bone, siemond, schafer                            |
|1954-OH097-002 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |meeker, reese                                     |
|1955-OH097-003 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |schafer, reese                                    |
|1955-OH027-043 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |bone, wiseman                                     |
|1954-OH071-S16 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |dotson                                            |
|1954-OH057-001 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |evans, roseler                                    |
|1954-OH057-002 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |evans, roseler                                    |
|1954-OH023-S01 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |dotson, horse, holowaychuk                        |
|1954-OH021-S01 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |holowaychuk, dotson, morse                        |
|1955-OH141-013 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |petro, finney                                     |
|1959-OH017-S11 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |roseler, carner, reeder                           |
|1957-OH049-S32 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |n. holowaychuk, n. reeder                         |
|1960-OH165-041 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |garner, ernst                                     |
|1960-OH047-007 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |evans, reeder, donaoldson, petro                  |
|1959-OH135-016 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |schafer, lerch, hayhurst, Tornes, mcloda          |
|1958-OH021-005 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |ritchie                                           |
|1958-OH021-007 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |ritchie, evans                                    |
|1957-OH021-001 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |ritchie                                           |
|1958-OH021-004 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |ritchie                                           |
|1960-OH021-037 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |ritchie, dubford                                  |
|1960-OH135-056 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |mcloda, tornes, davis,                            |
|1959-OH021-015 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |ritchie, evans, powell, donaldson                 |
|1959-OH021-026 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |ritchie, powell                                   |
|1957-OH037-015 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |heffner, siegenthaler                             |
|1959-OH135-014 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lerch, mcloda, tornes                             |
|1956-OH135-003 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lerch, schafer                                    |
|1956-OH135-004 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lerch, schafer                                    |
|1956-OH135-005 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lerch, schafer                                    |
|1956-OH135-006 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lerch, shcafer                                    |
|1956-OH141-018 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |evans, petro                                      |
|1956-OH141-027 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |r. h. jones                                       |
|1959-OH149-006 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |heffner, siegenthaler                             |
|1961-OH165-057 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |garner, ernst                                     |
|1963-OH113-010 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lerch, davis, smeck                               |
|1961-OH021-047 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |ritchie, powell, siegenthaler                     |
|1961-OH091-011 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |heffner, siegenthaler, urban                      |
|1963-OH113-007 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lerch, smeck, steiger, davis                      |
|1962-OH113-003 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |davis, lerch, calhoun                             |
|1971-OH017-002 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lerch, & hale                                     |
|1967-OH049-007 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |r. l. blevens                                     |
|1969-OH047-003 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |petro                                             |
|1968-OH109-018 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lehman, bottrell                                  |
|1968-OH109-021 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |lehman, bottrell                                  |
|1971-OH129-023 |Miami     |oxyaquic hapludalfs |fine-loamy      |missing                            |hall, williams, kerr, jones, mc kinney, le master |


![plot of chunk unnamed-chunk-1](figure/unnamed-chunk-1-1.png) 


## Range in characteristics

### Summary of the soil surface


|  variable  |        range         |
|:----------:|:--------------------:|
| total_srf  | (0, 0, 0, 0, 0)(108) |
|  fgravel   | (0, 0, 0, 0, 0)(108) |
|   gravel   | (0, 0, 0, 0, 0)(108) |
|  cobbles   | (0, 0, 0, 0, 0)(108) |
|   stones   | (0, 0, 0, 0, 0)(108) |
|  boulders  | (0, 0, 0, 0, 0)(108) |
|  channers  | (0, 0, 0, 0, 0)(108) |
| flagstones | (0, 0, 0, 0, 0)(108) |


### Summary of diagnostic horizons and soil characteristics


|           diag_kind           |        featdept         |        featdepb         |        thickness        |
|:-----------------------------:|:-----------------------:|:-----------------------:|:-----------------------:|
|       argillic horizon        | (15, 15, 16, 18, 41)(6) | (51, 60, 68, 71, 76)(6) | (35, 38, 47, 52, 53)(6) |
|        ochric epipedon        |   (0, 0, 0, 0, 0)(6)    | (15, 15, 16, 18, 30)(6) | (15, 15, 16, 18, 30)(6) |
| particle size control section | (15, 15, 18, 28, 48)(8) | (51, 65, 68, 74, 98)(8) | (35, 46, 50, 50, 51)(8) |

![plot of chunk diagnostics](figure/diagnostics-1.png) 


### Summary of soil horizons


|         | 1A| 1A p| 1Ap| 1Ap1| 1Ap2| 1B 1t| 1B 2t| 1B 3| 1B t| 1B1| 1B21t| 1B22t| 1B31| 1B32| 1BC| 1BCt| 1Bt1| 1Bt2| 1Bt3| 1Bt4| 1C| 1C 1| 1C 2| 1C 3| 1C1| 1C2| 1C3| 1E| 2B t1| 2B t2| 2B t3| 2B1| 2B2| 2B22T| 2B23T| 2B24T| 2B3| 2BC| 2BC t| 2BE2| 2Bt2| 2Bt3| 2C| 2C 1| 2C 2| 2C1| 2C2| 2C3| 2C4| 2CBt| 2R|  A| A&B| A1| A2| A21| A22| A3| A3-B1| AB| Ap| AP| Ap1| AP1| Ap2| AP2|  B| B&A| B&C| B1| B1T| B2| B21| B21t| B21T| B21T1| B21T2| B22| B22t| B22T| B23| B23T| B24T| B2T| B2T1| B2T2| B2T3| B3| B3-C1| B31| B32| B3T| B4| BA| BC| BC3| BCt| BCT| BE| BE1| BEt| Bt| Bt1| BT1| Bt2| BT2| Bt3| BT3| Bt4| Btk| BW|  C| C1| C11| C12| C2| C21| C22| C23| C3| C4| C5| C6| CB| CBT|  E| E1| E2| EB| missing| Oi|  R| Sum|
|:--------|--:|----:|---:|----:|----:|-----:|-----:|----:|----:|---:|-----:|-----:|----:|----:|---:|----:|----:|----:|----:|----:|--:|----:|----:|----:|---:|---:|---:|--:|-----:|-----:|-----:|---:|---:|-----:|-----:|-----:|---:|---:|-----:|----:|----:|----:|--:|----:|----:|---:|---:|---:|---:|----:|--:|--:|---:|--:|--:|---:|---:|--:|-----:|--:|--:|--:|---:|---:|---:|---:|--:|---:|---:|--:|---:|--:|---:|----:|----:|-----:|-----:|---:|----:|----:|---:|----:|----:|---:|----:|----:|----:|--:|-----:|---:|---:|---:|--:|--:|--:|---:|---:|---:|--:|---:|---:|--:|---:|---:|---:|---:|---:|---:|---:|---:|--:|--:|--:|---:|---:|--:|---:|---:|---:|--:|--:|--:|--:|--:|---:|--:|--:|--:|--:|-------:|--:|--:|---:|
|Ap       |  0|    2|   4|    1|    1|     0|     0|    0|    0|   0|     0|     0|    0|    0|   0|    0|    0|    0|    0|    0|  0|    0|    0|    0|   0|   0|   0|  0|     0|     0|     0|   0|   0|     0|     0|     0|   0|   0|     0|    0|    0|    0|  0|    0|    0|   0|   0|   0|   0|    0|  0|  0|   0|  0|  0|   0|   0|  0|     0|  0| 41| 29|   2|   1|   2|   1|  0|   0|   0|  0|   0|  0|   0|    0|    0|     0|     0|   0|    0|    0|   0|    0|    0|   0|    0|    0|    0|  0|     0|   0|   0|   0|  0|  0|  0|   0|   0|   0|  0|   0|   0|  0|   0|   0|   0|   0|   0|   0|   0|   0|  0|  0|  0|   0|   0|  0|   0|   0|   0|  0|  0|  0|  0|  0|   0|  0|  0|  0|  0|       0|  0|  0|  84|
|A        |  0|    0|   0|    0|    0|     0|     0|    0|    0|   0|     0|     0|    0|    0|   0|    0|    0|    0|    0|    0|  0|    0|    0|    0|   0|   0|   0|  0|     0|     0|     0|   0|   0|     0|     0|     0|   0|   0|     0|    0|    0|    0|  0|    0|    0|   0|   0|   0|   0|    0|  0|  0|   0|  0| 14|   1|   1|  2|     1|  0|  0|  0|   0|   0|   0|   0|  0|   0|   0|  0|   0|  0|   0|    0|    0|     0|     0|   0|    0|    0|   0|    0|    0|   0|    0|    0|    0|  0|     0|   0|   0|   0|  0|  0|  0|   0|   0|   0|  0|   0|   0|  0|   0|   0|   0|   0|   0|   0|   0|   0|  0|  0|  0|   0|   0|  0|   0|   0|   0|  0|  0|  0|  0|  0|   0|  0|  0|  0|  0|       0|  0|  0|  19|
|E        |  0|    0|   0|    0|    0|     0|     0|    0|    0|   0|     0|     0|    0|    0|   0|    0|    0|    0|    0|    0|  0|    0|    0|    0|   0|   0|   0|  0|     0|     0|     0|   0|   0|     0|     0|     0|   0|   0|     0|    0|    0|    0|  0|    0|    0|   0|   0|   0|   0|    0|  0|  0|   0|  0|  0|   0|   0|  0|     0|  0|  0|  0|   0|   0|   0|   0|  0|   0|   0|  0|   0|  0|   0|    0|    0|     0|     0|   0|    0|    0|   0|    0|    0|   0|    0|    0|    0|  0|     0|   0|   0|   0|  0|  0|  0|   0|   0|   0|  0|   0|   0|  0|   0|   0|   0|   0|   0|   0|   0|   0|  0|  0|  0|   0|   0|  0|   0|   0|   0|  0|  0|  0|  0|  0|   0| 12|  1|  1|  4|       0|  0|  0|  18|
|Bt       |  0|    0|   0|    0|    0|     0|     0|    0|    0|   0|     0|     0|    0|    0|   0|    0|    5|    4|    4|    0|  0|    0|    0|    0|   0|   0|   0|  0|     0|     0|     0|   0|   0|     0|     0|     0|   0|   0|     0|    0|    0|    0|  0|    0|    0|   0|   0|   0|   0|    0|  0|  0|   0|  0|  0|   0|   0|  0|     0|  0|  0|  0|   0|   0|   0|   0|  0|   0|   0|  0|   0|  0|   0|    0|    0|     0|     0|   0|    0|    0|   0|    0|    0|   0|    0|    0|    0|  0|     0|   0|   0|   0|  0|  0|  0|   0|   0|   0|  0|   0|   0|  0|  19|   6|  19|   6|   7|   7|   0|   0|  0|  0|  0|   0|   0|  0|   0|   0|   0|  0|  0|  0|  0|  0|   0|  0|  0|  0|  0|       0|  0|  0|  77|
|2Bt      |  0|    0|   0|    0|    0|     0|     0|    0|    0|   0|     0|     0|    0|    0|   0|    0|    0|    0|    0|    0|  0|    0|    0|    0|   0|   0|   0|  0|     1|     0|     0|   1|   1|     1|     1|     1|   1|   0|     0|    0|    2|    2|  0|    0|    0|   0|   0|   0|   0|    0|  0|  0|   0|  0|  0|   0|   0|  0|     0|  0|  0|  0|   0|   0|   0|   0|  0|   0|   0|  0|   0|  0|   0|    0|    0|     0|     0|   0|    0|    0|   0|    0|    0|   0|    0|    0|    0|  0|     0|   0|   0|   0|  0|  0|  0|   0|   0|   0|  0|   0|   0|  0|   0|   0|   0|   0|   0|   0|   0|   0|  0|  0|  0|   0|   0|  0|   0|   0|   0|  0|  0|  0|  0|  0|   0|  0|  0|  0|  0|       0|  0|  0|  11|
|not-used |  1|    0|   0|    0|    0|     1|     1|    1|    1|   1|     1|     1|    1|    1|   0|    0|    0|    0|    0|    1|  5|    1|    1|    1|   1|   1|   1|  1|     0|     1|     1|   0|   0|     0|     0|     0|   0|   0|     0|    1|    0|    0|  0|    0|    0|   0|   0|   0|   0|    0|  1| 12|   1| 16|  0|   0|   0|  0|     0|  1|  0|  0|   0|   0|   0|   0|  1|   1|   1| 47|   3| 23|  10|    1|   27|     1|     1|  11|    2|   26|   3|   14|    1|   2|    1|    1|    1| 26|     1|   2|   2|   6|  1|  5|  0|   0|   0|   0| 21|   1|   2|  4|   0|   0|   0|   0|   0|   0|   1|   1|  1| 40| 53|   1|   1| 51|   1|   1|   1| 19|  8|  4|  1|  0|   0|  0|  0|  0|  0|       5|  1|  1| 497|
|2BCt     |  0|    0|   0|    0|    0|     0|     0|    0|    0|   0|     0|     0|    0|    0|   1|    1|    0|    0|    0|    0|  0|    0|    0|    0|   0|   0|   0|  0|     0|     0|     0|   0|   0|     0|     0|     0|   0|   2|     1|    0|    0|    0|  0|    0|    0|   0|   0|   0|   0|    0|  0|  0|   0|  0|  0|   0|   0|  0|     0|  0|  0|  0|   0|   0|   0|   0|  0|   0|   0|  0|   0|  0|   0|    0|    0|     0|     0|   0|    0|    0|   0|    0|    0|   0|    0|    0|    0|  0|     0|   0|   0|   0|  0|  0| 28|   1|   3|   1|  0|   0|   0|  0|   0|   0|   0|   0|   0|   0|   0|   0|  0|  0|  0|   0|   0|  0|   0|   0|   0|  0|  0|  0|  0|  3|   1|  0|  0|  0|  0|       0|  0|  0|  42|
|2Cd      |  0|    0|   0|    0|    0|     0|     0|    0|    0|   0|     0|     0|    0|    0|   0|    0|    0|    0|    0|    0|  0|    0|    0|    0|   0|   0|   0|  0|     0|     0|     0|   0|   0|     0|     0|     0|   0|   0|     0|    0|    0|    0|  3|    1|    1|   1|   1|   1|   1|    1|  0|  0|   0|  0|  0|   0|   0|  0|     0|  0|  0|  0|   0|   0|   0|   0|  0|   0|   0|  0|   0|  0|   0|    0|    0|     0|     0|   0|    0|    0|   0|    0|    0|   0|    0|    0|    0|  0|     0|   0|   0|   0|  0|  0|  0|   0|   0|   0|  0|   0|   0|  0|   0|   0|   0|   0|   0|   0|   0|   0|  0|  0|  0|   0|   0|  0|   0|   0|   0|  0|  0|  0|  0|  0|   0|  0|  0|  0|  0|       0|  0|  0|  10|
|Sum      |  1|    2|   4|    1|    1|     1|     1|    1|    1|   1|     1|     1|    1|    1|   1|    1|    5|    4|    4|    1|  5|    1|    1|    1|   1|   1|   1|  1|     1|     1|     1|   1|   1|     1|     1|     1|   1|   2|     1|    1|    2|    2|  3|    1|    1|   1|   1|   1|   1|    1|  1| 12|   1| 16| 14|   1|   1|  2|     1|  1| 41| 29|   2|   1|   2|   1|  1|   1|   1| 47|   3| 23|  10|    1|   27|     1|     1|  11|    2|   26|   3|   14|    1|   2|    1|    1|    1| 26|     1|   2|   2|   6|  1|  5| 28|   1|   3|   1| 21|   1|   2|  4|  19|   6|  19|   6|   7|   7|   1|   1|  1| 40| 53|   1|   1| 51|   1|   1|   1| 19|  8|  4|  1|  3|   1| 12|  1|  1|  4|       5|  1|  1| 758|



|  genhz   |           hzdept            |            hzdepb            |          thickness          |
|:--------:|:---------------------------:|:----------------------------:|:---------------------------:|
|    Ap    |    (0, 0, 0, 0, 20)(84)     |   (8, 15, 18, 20, 30)(84)    |   (8, 15, 18, 20, 25)(84)   |
|    A     |   (5, 8, 13, 18, 28)(19)    |   (15, 20, 23, 30, 38)(19)   |   (7, 9, 10, 12, 20)(19)    |
|    E     |   (5, 10, 15, 18, 23)(18)   |   (15, 20, 23, 27, 29)(18)   |    (5, 7, 8, 10, 15)(18)    |
|    Bt    |   (5, 23, 33, 46, 76)(77)   |   (23, 41, 51, 66, 99)(77)   |   (7, 13, 17, 22, 33)(77)   |
|   2Bt    |  (23, 40, 46, 61, 81)(11)   |  (38, 56, 61, 76, 102)(11)   |  (10, 12, 15, 20, 23)(11)   |
| not-used |  (0, 28, 53, 84, 201)(497)  |  (0, 41, 71, 112, 244)(497)  | (-79, 10, 16, 25, 106)(497) |
|   2BCt   |  (28, 54, 64, 70, 97)(42)   |  (36, 64, 78, 91, 130)(42)   |   (5, 10, 13, 21, 39)(42)   |
|   2Cd    | (69, 90, 100, 126, 155)(10) | (89, 130, 152, 154, 180)(10) |  (18, 21, 28, 47, 71)(10)   |

![plot of chunk hzname vs genhz](figure/hzname vs genhz-1.png) 


|  genhz   |          clay           |          sand           |     fine_gravel      |        gravel         |
|:--------:|:-----------------------:|:-----------------------:|:--------------------:|:---------------------:|
|    Ap    | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (0, 0, 0, 0, 0)(84)  |  (0, 0, 0, 0, 2)(84)  |
|    A     | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (0, 0, 0, 0, 0)(19)  |  (0, 0, 0, 0, 0)(19)  |
|    E     | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (0, 0, 0, 0, 0)(18)  |  (0, 0, 0, 0, 0)(18)  |
|    Bt    | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (0, 0, 0, 0, 0)(77)  | (0, 0, 0, 2, 15)(77)  |
|   2Bt    | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (0, 0, 0, 0, 0)(11)  |  (0, 0, 0, 0, 0)(11)  |
| not-used | (31, 31, 31, 31, 31)(1) | (NA, NA, NA, NA, NA)(0) | (0, 0, 0, 0, 0)(497) | (0, 0, 0, 0, 20)(497) |
|   2BCt   | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (0, 0, 0, 0, 0)(42)  |  (0, 0, 0, 0, 5)(42)  |
|   2Cd    | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (0, 0, 0, 0, 0)(10)  |  (0, 0, 0, 0, 0)(10)  |



|  genhz   |       cobbles        |        stones        |      fragvoltot       |            phfield             |
|:--------:|:--------------------:|:--------------------:|:---------------------:|:------------------------------:|
|    Ap    | (0, 0, 0, 0, 0)(84)  | (0, 0, 0, 0, 0)(84)  |  (0, 0, 0, 0, 5)(84)  |  (4.7, 5.8, 6.3, 7, 8.2)(67)   |
|    A     | (0, 0, 0, 0, 0)(19)  | (0, 0, 0, 0, 0)(19)  |  (0, 0, 0, 0, 0)(19)  | (4.9, 5.4, 5.9, 6.5, 7.5)(14)  |
|    E     | (0, 0, 0, 0, 0)(18)  | (0, 0, 0, 0, 0)(18)  |  (0, 0, 0, 0, 5)(18)  |  (4.8, 5.1, 5.4, 6, 7.2)(14)   |
|    Bt    | (0, 0, 0, 0, 0)(77)  | (0, 0, 0, 0, 0)(77)  | (0, 0, 0, 3, 15)(77)  |  (4.4, 5.8, 6.3, 7, 8.1)(72)   |
|   2Bt    | (0, 0, 0, 0, 0)(11)  | (0, 0, 0, 0, 0)(11)  |  (0, 0, 0, 0, 1)(11)  |  (5.3, 5.8, 6.4, 7, 7.6)(11)   |
| not-used | (0, 0, 0, 0, 0)(497) | (0, 0, 0, 0, 5)(497) | (0, 0, 0, 0, 30)(497) | (4.6, 5.8, 6.6, 7.8, 8.7)(306) |
|   2BCt   | (0, 0, 0, 0, 0)(42)  | (0, 0, 0, 0, 0)(42)  | (0, 0, 0, 0, 25)(42)  |  (5.8, 7, 7.4, 7.8, 8.7)(26)   |
|   2Cd    | (0, 0, 0, 0, 0)(10)  | (0, 0, 0, 0, 0)(10)  |  (0, 0, 0, 0, 0)(10)  |    (8, 8, 8.1, 8.2, 8.2)(5)    |



|  genhz   |         d_value         |        d_chroma         |       m_value        |       m_chroma       |
|:--------:|:-----------------------:|:-----------------------:|:--------------------:|:--------------------:|
|    Ap    |   (5, 6, 6, 6, 6)(17)   |   (2, 4, 4, 4, 5)(17)   | (3, 4, 4, 4, 5)(84)  | (2, 3, 4, 4, 5)(83)  |
|    A     |   (7, 7, 7, 7, 7)(1)    |   (4, 4, 4, 4, 4)(1)    | (4, 5, 5, 5, 6)(19)  | (3, 4, 4, 5, 6)(19)  |
|    E     |   (6, 7, 7, 7, 7)(5)    |   (3, 4, 4, 5, 5)(5)    | (4, 4, 5, 5, 6)(18)  | (3, 4, 4, 5, 5)(17)  |
|    Bt    |   (5, 5, 5, 5, 5)(2)    |   (5, 5, 5, 5, 5)(2)    | (4, 4, 4, 4, 5)(77)  | (3, 5, 5, 5, 6)(77)  |
|   2Bt    | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (4, 4, 4, 5, 5)(11)  | (5, 5, 5, 6, 6)(11)  |
| not-used |   (5, 5, 6, 6, 6)(12)   |   (2, 4, 5, 5, 6)(12)   | (1, 4, 5, 5, 6)(478) | (2, 4, 5, 5, 7)(477) |
|   2BCt   |   (6, 6, 6, 6, 6)(1)    |   (5, 5, 5, 5, 5)(1)    | (4, 4, 5, 5, 6)(42)  | (3, 5, 5, 5, 6)(42)  |
|   2Cd    | (NA, NA, NA, NA, NA)(0) | (NA, NA, NA, NA, NA)(0) | (4, 5, 5, 5, 6)(10)  | (4, 4, 5, 5, 5)(10)  |

![plot of chunk genhz numeric variables](figure/genhz numeric variables-1.png) 
</p>


|         |  c|  cl| cos| fsl|   l| ls| missing|  s| sc| scl| sic| sicl| sil| sl| Sum|
|:--------|--:|---:|---:|---:|---:|--:|-------:|--:|--:|---:|---:|----:|---:|--:|---:|
|Ap       |  0|   5|   0|   1|  10|  0|       0|  0|  0|   1|   0|    0|  67|  0|  84|
|A        |  0|   0|   0|   1|   1|  0|       0|  0|  0|   0|   0|    1|  16|  0|  19|
|E        |  0|   0|   0|   0|   2|  0|       0|  0|  0|   0|   0|    0|  16|  0|  18|
|Bt       |  4|  46|   0|   0|  10|  0|       0|  0|  0|   2|   3|    9|   3|  0|  77|
|2Bt      |  0|   8|   0|   0|   2|  0|       0|  0|  0|   0|   0|    1|   0|  0|  11|
|not-used | 41| 106|   1|  15| 194|  1|      10|  1|  1|   8|   4|   60|  51|  4| 497|
|2BCt     |  1|  18|   0|   0|  15|  0|       0|  0|  0|   0|   0|    7|   1|  0|  42|
|2Cd      |  0|   0|   0|   0|  10|  0|       0|  0|  0|   0|   0|    0|   0|  0|  10|
|Sum      | 46| 183|   1|  17| 244|  1|      10|  1|  1|  11|   7|   78| 154|  4| 758|



|         | and calcareous loam till| and fine silty clay loam|  C| calcareous loamy till| CL| CL                            | clay| clay loam| coarse silty clay loam| fine clay loam| fine clay loam or clay| fine loam| fine silty clay loam| FSL| GR-CL| GR-COS| GR-L| GR-SL                         | heavy clay loam| heavy loam| heavy loam or clay loam| heavy silt loam| heavy silty clay loam|   L| L                             | light clay| light clay loam| light loam| light silty clay loam| loam| loam glacial till| LS                            | medium silty clay loam| missing| S                             | SC| SCL| SICL| SICL                          | SIL| SIL                           | silt loam| silt loam or loam| silty clay| silty clay loam| silty clay loam to silty clay| SL| SL                            | Sum|
|:--------|------------------------:|------------------------:|--:|---------------------:|--:|------------------------------:|----:|---------:|----------------------:|--------------:|----------------------:|---------:|--------------------:|---:|-----:|------:|----:|------------------------------:|---------------:|----------:|-----------------------:|---------------:|---------------------:|---:|------------------------------:|----------:|---------------:|----------:|---------------------:|----:|-----------------:|------------------------------:|----------------------:|-------:|------------------------------:|--:|---:|----:|------------------------------:|---:|------------------------------:|---------:|-----------------:|----------:|---------------:|-----------------------------:|--:|------------------------------:|---:|
|Ap       |                        0|                        0|  0|                     0|  1|                              2|    0|         2|                      0|              0|                      0|         0|                    0|   1|     0|      0|    0|                              0|               0|          0|                       0|               1|                     0|   7|                              3|          0|               0|          0|                     0|    0|                 0|                              0|                      0|       0|                              0|  0|   1|    0|                              0|  24|                              8|        34|                 0|          0|               0|                             0|  0|                              0|  84|
|A        |                        0|                        0|  0|                     0|  0|                              0|    0|         0|                      0|              0|                      0|         0|                    0|   1|     0|      0|    0|                              0|               0|          0|                       0|               0|                     0|   1|                              0|          0|               0|          0|                     0|    0|                 0|                              0|                      0|       0|                              0|  0|   0|    0|                              0|   6|                              2|         8|                 0|          0|               1|                             0|  0|                              0|  19|
|E        |                        0|                        0|  0|                     0|  0|                              0|    0|         0|                      0|              0|                      0|         0|                    0|   0|     0|      0|    0|                              0|               0|          0|                       0|               1|                     0|   2|                              0|          0|               0|          0|                     0|    0|                 0|                              0|                      0|       0|                              0|  0|   0|    0|                              0|   1|                              0|        14|                 0|          0|               0|                             0|  0|                              0|  18|
|Bt       |                        0|                        0|  0|                     0| 25|                             16|    4|         3|                      0|              0|                      2|         0|                    1|   0|     0|      0|    0|                              0|               0|          0|                       0|               0|                     1|  10|                              0|          0|               0|          0|                     0|    0|                 0|                              0|                      0|       0|                              0|  0|   2|    2|                              1|   2|                              1|         0|                 0|          3|               4|                             0|  0|                              0|  77|
|2Bt      |                        0|                        0|  0|                     0|  0|                              5|    0|         2|                      0|              0|                      0|         0|                    0|   0|     0|      0|    0|                              0|               0|          0|                       0|               0|                     0|   1|                              1|          0|               1|          0|                     0|    0|                 0|                              0|                      0|       0|                              0|  0|   0|    1|                              0|   0|                              0|         0|                 0|          0|               0|                             0|  0|                              0|  11|
|not-used |                        1|                        1|  1|                     1| 52|                             17|   37|        31|                      1|              1|                      0|         2|                    1|  15|     1|      1|    3|                              1|               1|          1|                       1|               3|                     5|  73|                             28|          3|               2|          2|                     4|   83|                 1|                              1|                      1|       9|                              1|  1|   8|    7|                              2|  18|                              4|        25|                 1|          4|              37|                             1|  1|                              2| 497|
|2BCt     |                        0|                        0|  0|                     0|  4|                              1|    1|        11|                      0|              1|                      0|         1|                    0|   0|     0|      0|    0|                              0|               0|          1|                       0|               1|                     1|   6|                              3|          0|               1|          0|                     0|    4|                 0|                              0|                      0|       0|                              0|  0|   0|    0|                              0|   0|                              0|         0|                 0|          0|               6|                             0|  0|                              0|  42|
|2Cd      |                        0|                        0|  0|                     0|  0|                              0|    0|         0|                      0|              0|                      0|         0|                    0|   0|     0|      0|    0|                              0|               0|          0|                       0|               0|                     0|   1|                              5|          0|               0|          0|                     0|    4|                 0|                              0|                      0|       0|                              0|  0|   0|    0|                              0|   0|                              0|         0|                 0|          0|               0|                             0|  0|                              0|  10|
|Sum      |                        1|                        1|  1|                     1| 82|                             41|   42|        49|                      1|              2|                      2|         3|                    2|  17|     1|      1|    3|                              1|               1|          2|                       1|               6|                     7| 101|                             40|          3|               4|          2|                     4|   91|                 1|                              1|                      1|       9|                              1|  1|  11|   10|                              3|  51|                             15|        81|                 1|          7|              48|                             1|  1|                              2| 758|



|         | 10YR| 2.5Y| 5YR| missing| Sum|
|:--------|----:|----:|---:|-------:|---:|
|Ap       |   17|    0|   0|      67|  84|
|A        |    1|    0|   0|      18|  19|
|E        |    5|    0|   0|      13|  18|
|Bt       |    2|    0|   0|      75|  77|
|2Bt      |    0|    0|   0|      11|  11|
|not-used |    5|    6|   1|     485| 497|
|2BCt     |    0|    1|   0|      41|  42|
|2Cd      |    0|    0|   0|      10|  10|
|Sum      |   30|    7|   1|     720| 758|



|         | 10YR| 2.5Y| 2.5YR| 5Y| 5YR| 7.5Y| 7.5YR| missing| Sum|
|:--------|----:|----:|-----:|--:|---:|----:|-----:|-------:|---:|
|Ap       |   74|    0|     2|  3|   1|    0|     4|       0|  84|
|A        |   17|    0|     0|  0|   1|    0|     1|       0|  19|
|E        |   16|    0|     0|  1|   0|    0|     1|       0|  18|
|Bt       |   63|    0|     0|  2|   1|    0|    11|       0|  77|
|2Bt      |   10|    1|     0|  0|   0|    0|     0|       0|  11|
|not-used |  373|   25|     0|  8|  11|    1|    61|      18| 497|
|2BCt     |   39|    3|     0|  0|   0|    0|     0|       0|  42|
|2Cd      |    9|    1|     0|  0|   0|    0|     0|       0|  10|
|Sum      |  601|   30|     2| 14|  14|    1|    78|      18| 758|



|         | violent| strong| slight| very slight| none| missing| Sum|
|:--------|-------:|------:|------:|-----------:|----:|-------:|---:|
|Ap       |       0|      0|      1|           2|    0|      81|  84|
|A        |       0|      0|      0|           0|    0|      19|  19|
|E        |       0|      0|      0|           0|    0|      18|  18|
|Bt       |       0|      1|      0|           2|    0|      74|  77|
|2Bt      |       0|      0|      1|           0|    0|      10|  11|
|not-used |       6|    104|     51|           0|    0|     336| 497|
|2BCt     |       1|      4|     15|           0|    0|      22|  42|
|2Cd      |       1|      6|      1|           0|    0|       2|  10|
|Sum      |       8|    115|     69|           4|    0|     562| 758|


## Geographic setting


|variable     |range                                 |
|:------------|:-------------------------------------|
|elev_field   |(197.4, 243.8, 294.2, 330, 387.1)(44) |
|slope_field  |(0, 3, 4, 4, 40)(103)                 |
|aspect_field |(315, 214, 157, 90, 0)(18)            |

![plot of chunk unnamed-chunk-5](figure/unnamed-chunk-5-1.png) 

|                                                            | dead ice moraine| flat&#124;till plain| ground moraine| hill| knoll| missing| moraine| outwash plain| plain| rise&#124;moraine| rise&#124;till plain| stream terrace| till plain| upland slope| Sum|
|:-----------------------------------------------------------|----------------:|--------------------:|--------------:|----:|-----:|-------:|-------:|-------------:|-----:|-----------------:|--------------------:|--------------:|----------:|------------:|---:|
|limestone, unspecified residuum                             |                0|                    0|              2|    0|     0|       0|       0|             0|     0|                 0|                    0|              0|          0|            0|   2|
|missing drift                                               |                0|                    0|              0|    0|     0|       2|       1|             0|     0|                 0|                    0|              0|          0|            0|   3|
|missing loess                                               |                0|                    0|              0|    0|     0|       1|       0|             0|     0|                 0|                    0|              0|          0|            0|   1|
|missing loess&#124;outwash                                  |                0|                    0|              0|    0|     0|       0|       0|             0|     0|                 0|                    0|              1|          0|            0|   1|
|missing loess&#124;till, unspecified                        |                1|                    2|              0|    4|     0|       5|       1|             0|     0|                 0|                    3|              0|          0|            0|  16|
|missing loess&#124;till, unspecified&#124;till, unspecified |                0|                    0|              0|    0|     0|       0|       0|             0|     0|                 0|                    1|              0|          0|            0|   1|
|missing missing                                             |                0|                    0|              0|    0|     1|       5|       0|             0|     0|                 0|                    0|              0|          3|            0|   9|
|missing outwash&#124;till, unspecified                      |                0|                    0|              0|    0|     0|       0|       0|             1|     0|                 0|                    0|              0|          0|            0|   1|
|missing till, unspecified                                   |                0|                    0|             43|    2|     0|       6|       4|             0|     0|                 6|                    5|              0|          1|            0|  67|
|missing till, unspecified&#124;till, unspecified            |                0|                    0|              0|    0|     0|       0|       0|             0|     0|                 0|                    1|              0|          0|            0|   1|
|mixed-calcareous till, unspecified                          |                0|                    0|              0|    0|     0|       1|       0|             0|     0|                 0|                    0|              0|          0|            1|   2|
|mixed loess&#124;till, unspecified                          |                0|                    0|              0|    0|     0|       0|       0|             0|     1|                 0|                    0|              0|          0|            0|   1|
|mixed till, unspecified                                     |                0|                    0|              0|    0|     0|       0|       0|             0|     1|                 0|                    0|              0|          0|            0|   1|
|mixed&#124;mixed-calcareous loess&#124;till, unspecified    |                0|                    0|              0|    0|     0|       0|       0|             0|     0|                 0|                    0|              0|          0|            2|   2|
|Sum                                                         |                1|                    2|             45|    6|     1|      20|       6|             1|     2|                 6|                   10|              1|          4|            3| 108|



|        | Convex| Linear| Concave| missing| Sum|
|:-------|------:|------:|-------:|-------:|---:|
|Convex  |      0|      0|       0|       3|   3|
|Linear  |      0|      0|       0|       0|   0|
|Concave |      0|      0|       0|       0|   0|
|missing |      0|      0|       0|     105| 105|
|Sum     |      0|      0|       0|     108| 108|



|                                  | Summit| Shoulder| Backslope| Footslope| Toeslope| missing| Sum|
|:---------------------------------|------:|--------:|---------:|---------:|--------:|-------:|---:|
|Excessivelly drained              |      0|        0|         0|         0|        0|       0|   0|
|Well drained                      |      1|        1|         0|         1|        0|      93|  96|
|Somewhat excessively well drained |      0|        0|         0|         0|        0|       0|   0|
|Moderately well drained           |      0|        0|         0|         0|        0|       6|   6|
|Somewhat poorly drained           |      0|        0|         0|         0|        0|       0|   0|
|Poorly drained                    |      0|        0|         0|         0|        0|       0|   0|
|Very poorly drained               |      0|        0|         0|         0|        0|       0|   0|
|Subaqueous drainage               |      0|        0|         0|         0|        0|       0|   0|
|missing                           |      0|        0|         0|         0|        0|       6|   6|
|Sum                               |      1|        1|         0|         1|        0|     105| 108|