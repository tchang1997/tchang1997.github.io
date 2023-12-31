---
permalink: /nfl-big-data-bowl-2024-demos/
title: "NFL Big Data Bowl 2024 - Supplementary Material"
excerpt: ""
author_profile: true
---

This is an Appendix of demoes for the NFL 2024 Big Data Bowl entry [TAPER: An Intuitive Metric for Measuring Yards Prevented by Tackles.](https://www.kaggle.com/trentonchang/nfl-bdb-24-yards-prevented-by-tackles) Please reach out for specific requests.

Note that the demos are set to autoplay by default, which may lead to some lagging on the first playthrough.

Top 10 successful tackles, TAPER (defensive performance)
======

**TAPER** measures the difference in expected yards after first contact between a hypothetical successful tackle and a hypothetical failed tackle.

| Date | Initial tackler(s) (team) | Ball carrier (team) | $$f(x_i, 1)$$(yds. if tackle succeeds) | $$f(x_i, 0)$$ (yds. if tackle fails) | **TAPER** | 
|:-----|:------------------|:--------------------|:-----:|:-----:|:-----:|
| [10/30/2022](../../files/html/GAME2022103011_PLAY2484.html) | J. Love (NYG) | T. Homer (SEA) | 4.6 | 13.5 | **9.0** |
| [10/09/2022](../../files/html/GAME2022100906_PLAY2549.html)  | M. Davenport & K. Elliss (NO) | R. Penny (SEA) | 4.1 | 13.0 | **8.9** |
| [10/23/2022](../../files/html/GAME2022102300_PLAY2665.html) | D. Jones (CLE) | L. Jackson (BAL) | 4.1 | 12.7 | **8.6** |
| [10/16/2022](../../files/html/GAME2022101611_PLAY2655.html) | K. Wallace (PHI) | E. Elliott (DAL) |  4.2       |  12.7     |  **8.5**  | 
| [10/23/2022](../../files/html/GAME2022110603_PLAY486.html) | M. Hughes (DET) | A. Jones (GB) | 3.7 | 12.0 | **8.3** |
| [10/09/2022](../../files/html/GAME2022100908_PLAY2724.html) | J. Dean (TB) | M. Mariota (ATL) | 4.7 | 12.9 | **8.2** |
| [10/31/2022](../../files/html/GAME2022103100_PLAY2235.html) | J. Bates (CIN) | N. Chubb (CLE) | 4.0 | 12.1 | **8.1** |
| [10/30/2022](../../files/html/GAME2022103007_PLAY3143.html) | J. Jones (NE) | M. Carter (NYJ) | 4.1 | 12.2 | **8.1** |
| [10/30/2022](../../files/html/GAME2022103006_PLAY2474.html) | A. Averett (LV) | T. Hill (NO) | 4.6 | 12.6 | **7.9** |
| [10/09/2022](../../files/html/GAME2022100911_PLAY591.html) | T. Edwards (PHI) | E. Benjamin (ARI) | 3.4 | 11.2 | **7.8** |

Top 10 offensive plays, CAPER (offensive performance)
======

**CAPER** measures how much an offensive player exceeds the **TAPER** prediction ($f(x_i, 1)$ if tackle successful; $f(x_i, 0)$ if tackle missed).

| Date | Ball carrier (team) | Initial tackler (team) | $$f(x_i, 1)$$ | $$f(x_i, 0)$$ | Actual yds. after contact | **CAPER** |
|:----|:----|:----|:----:|:----:|:----:|:----:
| [10/02/2022](../../files/html/GAME2022100205_PLAY3163.html) | T. Hockenson (DET) | J. Jones (SEA) | 2.7 | 10.5 | 72.2 | **61.7** | 
| [09/11/2022](../../files/html/GAME2022091108_PLAY1948.html) | S. Barkley (NYG) | A. Hooker (TEN) | 2.9 | 7.9 | 57.9 | **49.9** |
| [09/18/2022](../../files/html/GAME2022091808_PLAY565.html) | D. Samuel (SF) | D. Taylor (SEA) | 2.1 | 7.0 | 55.6 | **48.5** |
| [10/13/2022](../../files/html/GAME2022101300_PLAY826.html) | K. Herbert (CHI) | E. Obada (WAS) | 4.2 | 13.8 | 62.2 | **48.4** |
| [09/15/2022](../../files/html/GAME2022091500_PLAY3626.html) | C. Edwards-Helaire (KC) | *D. James (DET)* | 2.4 | 6.8 | 50.7 | **44.0** |
| [09/11/2022](../../files/html/GAME2022091104_PLAY86.html) | D. Swift (PHI) | J. Bradberry (DET) | 2.1 | 6.1 | 48.3 | **42.3** |
| [10/16/2022](../../files/html/GAME2022101608_PLAY3227.html) | C. McCaffrey (CAR) | E. Jones (LA) | 2.2 | 6.7 | 48.7 | **42.1** |
| [09/18/2022](../../files/html/GAME2022091805_PLAY3127.html) | C. McCaffrey (CAR) | J. Ellis (NYG) | 1.8 | 4.8 | 45.5 | **40.7** |
| [10/02/2022](../../files/html/GAME2022100212_PLAY2366.html) | J. Jacobs (LV) | J. Griffith (DEN) | 1.7 | 4.4 | 43.3 | **38.9** |
| [09/25/2022](../../files/html/GAME2022092501_PLAY155.html) | J. Fields (CHI) | J. Hughes (HOU) | 2.2 | 7.7 | 41.8 | **34.1** |

