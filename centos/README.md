Azul Zulu CentOS
================

These Docker images of Azul Zulu Build of OpenJDK are based on CentOS.

Azul Zulu Builds of OpenJDK are available for free unlimited use and are commercially supported by [Azul][1] as a part of the Azul Platform Core bundle.
Check out [Azul Platform Core][2] for more information. The technical documentation can be found on [docs.azul.com/core][3].

Docker images of Azul Zulu are available in the following repositories, depending on the base system:

  * [Ubuntu: azul/zulu-openjdk][4]
  * [Alpine: azul/zulu-openjdk-alpine][5]
  * [CentOS: azul/zulu-openjdk-centos][6]
  * [Debian: azul/zulu-openjdk-debian][7]
  * [Distroless: azul/zulu-openjdk-distroless][8]

Tags and `Dockerfile` links
===========================

Most Recent
-----------


  * [`26.0.0-26.28`, `26-latest` (*26-latest/Dockerfile)*][40]
  * [`25.0.2-25.32`, `25-latest` (*25-latest/Dockerfile)*][44]
  * [`22.0.2-22.32`, `22-latest` (*22-latest/Dockerfile)*][74]
  * [`21.0.10-21.48`, `21-latest` (*21-latest/Dockerfile)*][84]
  * [`17.0.18-17.64`, `17-latest` (*17-latest/Dockerfile)*][152]
  * [`11.0.30-11.86`, `11-latest` (*11-latest/Dockerfile)*][277]
  * [`8u482-8.92`, `8-latest` (*8-latest/Dockerfile)*][358]

Previous
--------

Earlier CentOS Docker image tags(the most recent 4 tags) of Azul Zulu for previous update releases of OpenJDK are as follows:


  *[26-jre-headless-latest][11],
  [26.0.0-26.28-jre-headless][41],
  
  *[25-jre-headless-latest][12],
  [25.0.0-25.28-jre-headless][47],
  [25.0.1-25.30-jre-headless][49],
  [25.0.2-25.32-jre-headless][52],
  
  *[24-jre-headless-latest][13],
  [24.0.0-24.28-jre-headless][57],
  [24.0.1-24.30-jre-headless][59],
  [24.0.2-24.32-jre-headless][61],
  
  *[23-jre-headless-latest][14],
  [23.0.0-23.28-jre-headless][67],
  [23.0.1-23.30-jre-headless][69],
  [23.0.2-23.32-jre-headless][73],
  
  *[22-jre-headless-latest][15],
  [22.0.0-22.28-jre-headless][75],
  [22.0.1-22.30-jre-headless][79],
  [22.0.2-22.32-jre-headless][83],
  
  *[21-jre-headless-latest][16],
  [21.0.0-21.28.85-jre-headless][85],
  [21.0.1-21.30-jre-headless][89],
  [21.0.1-21.30.15-jre-headless][91],
  
  
  
  
  
  
  
  
  
  
  *[20-jre-headless-latest][17],
  [20.0.0-20.28.85-jre-headless][124],
  [20.0.1-20.30.11-jre-headless][126],
  [20.0.2-20.32.11-jre-headless][130],
  
  *[19-jre-headless-latest][18],
  [19.0.0-19.28.81-jre-headless][132],
  [19.0.1-19.30.11-jre-headless][136],
  [19.0.2-19.32.13-jre-headless][140],
  
  *[18-jre-headless-latest][19],
  [18.0.1-18.30.11-jre-headless][143],
  [18.0.2.1-18.32.13-jre-headless][147],
  [18.0.2-18.32.11-jre-headless][149],
  
  *[17-jre-headless-latest][20],
  [17.0.0-17.28.13-jre-headless][153],
  [17.0.1-17.30.15-jre-headless][158],
  [17.0.2-17.32.13-jre-headless][161],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[15-jre-headless-latest][21],
  [15.0.7-15.40.19-jre-headless][236],
  [15.0.8-15.42.15-jre-headless][240],
  [15.0.9-15.44.13-jre-headless][242],
  
  
  *[13-jre-headless-latest][22],
  [13.0.11-13.48.19-jre-headless][262],
  [13.0.12-13.50.15-jre-headless][266],
  [13.0.13-13.52.15-jre-headless][267],
  
  
  *[11-jre-headless-latest][23],
  [11.0.15-11.56.19-jre-headless][294],
  [11.0.16.1-11.58.23-jre-headless][296],
  [11.0.16-11.58.15-jre-headless][300],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[8-jre-headless-latest][24],
  [8u332-8.62.0.19-jre-headless][396],
  [8u342-8.64.0.15-jre-headless][400],
  [8u345-8.64.0.19-jre-headless][403],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[26-jre-latest][25],
  [26.0.0-26.28-jre][43],
  
  *[25-jre-latest][26],
  [25.0.0-25.28-jre][45],
  [25.0.1-25.30-jre][50],
  [25.0.2-25.32-jre][53],
  
  *[24-jre-latest][27],
  [24.0.0-24.28-jre][56],
  [24.0.1-24.30-jre][58],
  [24.0.2-24.32-jre][62],
  
  *[23-jre-latest][28],
  [23.0.0-23.28-jre][65],
  [23.0.1-23.30-jre][70],
  [23.0.2-23.32-jre][72],
  
  *[22-jre-latest][29],
  [22.0.0-22.28-jre][77],
  [22.0.1-22.30-jre][78],
  [22.0.2-22.32-jre][82],
  
  *[21-jre-latest][30],
  [21.0.0-21.28.85-jre][87],
  [21.0.1-21.30-jre][88],
  [21.0.1-21.30.15-jre][93],
  
  
  
  
  
  
  
  
  
  
  *[20-jre-latest][31],
  [20.0.0-20.28.85-jre][123],
  [20.0.1-20.30.11-jre][127],
  [20.0.2-20.32.11-jre][129],
  
  *[19-jre-latest][32],
  [19.0.0-19.28.81-jre][134],
  [19.0.1-19.30.11-jre][135],
  [19.0.2-19.32.13-jre][138],
  
  *[18-jre-latest][33],
  [18.0.1-18.30.11-jre][145],
  [18.0.2.1-18.32.13-jre][146],
  [18.0.2-18.32.11-jre][150],
  
  *[17-jre-latest][34],
  [17.0.0-17.28.13-jre][155],
  [17.0.1-17.30.15-jre][156],
  [17.0.2-17.32.13-jre][160],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[16-jre-latest][35],
  [16.0.0-16.28.11-jre][221],
  [16.0.1-16.30.15-jre][222],
  [16.0.2-16.32.15-jre][225],
  
  *[15-jre-latest][36],
  [15.0.7-15.40.19-jre][235],
  [15.0.8-15.42.15-jre][239],
  [15.0.9-15.44.13-jre][241],
  
  
  *[13-jre-latest][37],
  [13.0.11-13.48.19-jre][263],
  [13.0.12-13.50.15-jre][264],
  [13.0.13-13.52.15-jre][269],
  
  
  *[11-jre-latest][38],
  [11.0.15-11.56.19-jre][293],
  [11.0.16.1-11.58.23-jre][298],
  [11.0.16-11.58.15-jre][301],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[8-jre-latest][39],
  [8u332-8.62.0.19-jre][397],
  [8u342-8.64.0.15-jre][401],
  [8u345-8.64.0.19-jre][404],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[26-latest][40],
  [26.0.0-26.28][42],
  
  *[25-latest][44],
  [25.0.0-25.28][46],
  [25.0.1-25.30][48],
  [25.0.2-25.32][51],
  
  *[24-latest][54],
  [24.0.0-24.28][55],
  [24.0.1-24.30][60],
  [24.0.2-24.32][63],
  
  *[23-latest][64],
  [23.0.0-23.28][66],
  [23.0.1-23.30][68],
  [23.0.2-23.32][71],
  
  *[22-latest][74],
  [22.0.0-22.28][76],
  [22.0.1-22.30][80],
  [22.0.2-22.32][81],
  
  *[21-latest][84],
  [21.0.0-21.28.85][86],
  [21.0.1-21.30][90],
  [21.0.1-21.30.15][92],
  
  
  
  
  
  
  
  
  
  
  *[20-latest][121],
  [20.0.0-20.28.85][122],
  [20.0.1-20.30.11][125],
  [20.0.2-20.32.11][128],
  
  *[19-latest][131],
  [19.0.0-19.28.81][133],
  [19.0.1-19.30.11][137],
  [19.0.2-19.32.13][139],
  
  
  *[18-latest][142],
  [18.0.1-18.30.11][144],
  [18.0.2.1-18.32.13][148],
  [18.0.2-18.32.11][151],
  
  *[17-latest][152],
  [17.0.0-17.28.13][154],
  [17.0.1-17.30.15][157],
  [17.0.2-17.32.13][159],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[16-latest][219],
  [16.0.0-16.28.11][220],
  [16.0.1-16.30.15][223],
  [16.0.2-16.32.15][224],
  
  *[15-latest][226],
  [15.0.0-15.27.17][227],
  [15.0.1-15.28.13][228],
  [15.0.1-15.28.51][229],
  
  
  
  
  
  
  
  
  
  
  *[14-latest][247],
  [14.0.1-14.28.21][248],
  [14.0.2-14.29.23][249],
  
  *[13-latest][250],
  [13.0.1-13.28][251],
  [13.0.2-13.29][252],
  [13.0.3-13.31.11][253],
  
  
  
  
  
  
  
  
  
  
  
  
  *[12-latest][273],
  [12.0.1-12.2][274],
  [12.0.2-12.3][275],
  [12-12.1][276],
  
  *[11-latest][277],
  [11.0.1-11.2][278],
  [11.0.2-11.29][279],
  [11.0.3-11.31][280],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[10-latest][350],
  [10u01-10.2][351],
  [10u02-10.3][352],
  
  *[9-latest][353],
  [9-ea][354],
  [9u01-9.0.1.3][355],
  [9u04-9.0.4.1][356],
  
  
  *[8-latest][358],
  [8u11-8.2.0.1][359],
  [8u20-8.3.0.1][360],
  [8u25-8.4.0.1][361],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[7-latest][453],
  [7u65-7.6.0.1][454],
  [7u72-7.7.0.1][455],
  [7u76-7.8.0.3][456],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[6-latest][488],
  [6u53-6.5.0.2][489],
  [6u56-6.6.0.1][490],
  [6u59-6.7.0.2][491],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  License
=======

Azul Zulu incorporates third-party licensed software packages. Some of these have distribution restrictions, and some have only reporting requirements. Please see [docs.azul.com/core/tpl][9] for the links to the documents with licenses for third-party software included in the latest version of Azul Platform Core.

As with all Docker images, these likely also contain other software which may be under other licenses (such as Bash, etc., from the base distribution, along with any direct or indirect dependencies of the primary software being contained).

As for any pre-built image usage, it is the image user's responsibility to ensure that any use of this image complies with any relevant licenses for all software contained within.

[BSD 3-Clause Clear License][10]

  [1]: https://www.azul.com/
  [2]: https://www.azul.com/products/core/
  [3]: https://docs.azul.com/core/
  [4]: https://hub.docker.com/r/azul/zulu-openjdk
  [5]: https://hub.docker.com/r/azul/zulu-openjdk-alpine
  [6]: https://hub.docker.com/r/azul/zulu-openjdk-centos
  [7]: https://hub.docker.com/r/azul/zulu-openjdk-debian
  [8]: https://hub.docker.com/r/azul/zulu-openjdk-distroless
  [9]: https://docs.azul.com/core/tpl
  [10]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/LICENSE.txt


  [11]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/26-jre-headless-latest/Dockerfile
  [41]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/26.0.0-26.28-jre-headless/Dockerfile
  
  [12]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25-jre-headless-latest/Dockerfile
  [47]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.0-25.28-jre-headless/Dockerfile
  [49]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.1-25.30-jre-headless/Dockerfile
  [52]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.2-25.32-jre-headless/Dockerfile
  
  [13]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24-jre-headless-latest/Dockerfile
  [57]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.0-24.28-jre-headless/Dockerfile
  [59]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.1-24.30-jre-headless/Dockerfile
  [61]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.2-24.32-jre-headless/Dockerfile
  
  [14]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23-jre-headless-latest/Dockerfile
  [67]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.0-23.28-jre-headless/Dockerfile
  [69]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.1-23.30-jre-headless/Dockerfile
  [73]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.2-23.32-jre-headless/Dockerfile
  
  [15]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22-jre-headless-latest/Dockerfile
  [75]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.0-22.28-jre-headless/Dockerfile
  [79]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.1-22.30-jre-headless/Dockerfile
  [83]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.2-22.32-jre-headless/Dockerfile
  
  [16]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21-jre-headless-latest/Dockerfile
  [85]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.0-21.28.85-jre-headless/Dockerfile
  [89]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.1-21.30-jre-headless/Dockerfile
  [91]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.1-21.30.15-jre-headless/Dockerfile
  
  
  
  
  
  
  
  
  
  
  [17]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20-jre-headless-latest/Dockerfile
  [124]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.0-20.28.85-jre-headless/Dockerfile
  [126]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.1-20.30.11-jre-headless/Dockerfile
  [130]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.2-20.32.11-jre-headless/Dockerfile
  
  [18]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19-jre-headless-latest/Dockerfile
  [132]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.0-19.28.81-jre-headless/Dockerfile
  [136]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.1-19.30.11-jre-headless/Dockerfile
  [140]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.2-19.32.13-jre-headless/Dockerfile
  
  [19]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18-jre-headless-latest/Dockerfile
  [143]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.1-18.30.11-jre-headless/Dockerfile
  [147]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.2.1-18.32.13-jre-headless/Dockerfile
  [149]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.2-18.32.11-jre-headless/Dockerfile
  
  [20]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17-jre-headless-latest/Dockerfile
  [153]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.0-17.28.13-jre-headless/Dockerfile
  [158]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.1-17.30.15-jre-headless/Dockerfile
  [161]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.2-17.32.13-jre-headless/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [21]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15-jre-headless-latest/Dockerfile
  [236]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.7-15.40.19-jre-headless/Dockerfile
  [240]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.8-15.42.15-jre-headless/Dockerfile
  [242]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.9-15.44.13-jre-headless/Dockerfile
  
  
  [22]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13-jre-headless-latest/Dockerfile
  [262]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.11-13.48.19-jre-headless/Dockerfile
  [266]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.12-13.50.15-jre-headless/Dockerfile
  [267]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.13-13.52.15-jre-headless/Dockerfile
  
  
  [23]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11-jre-headless-latest/Dockerfile
  [294]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.15-11.56.19-jre-headless/Dockerfile
  [296]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.16.1-11.58.23-jre-headless/Dockerfile
  [300]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.16-11.58.15-jre-headless/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [24]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8-jre-headless-latest/Dockerfile
  [396]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u332-8.62.0.19-jre-headless/Dockerfile
  [400]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u342-8.64.0.15-jre-headless/Dockerfile
  [403]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u345-8.64.0.19-jre-headless/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [25]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/26-jre-latest/Dockerfile
  [43]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/26.0.0-26.28-jre/Dockerfile
  
  [26]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25-jre-latest/Dockerfile
  [45]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.0-25.28-jre/Dockerfile
  [50]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.1-25.30-jre/Dockerfile
  [53]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.2-25.32-jre/Dockerfile
  
  [27]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24-jre-latest/Dockerfile
  [56]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.0-24.28-jre/Dockerfile
  [58]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.1-24.30-jre/Dockerfile
  [62]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.2-24.32-jre/Dockerfile
  
  [28]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23-jre-latest/Dockerfile
  [65]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.0-23.28-jre/Dockerfile
  [70]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.1-23.30-jre/Dockerfile
  [72]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.2-23.32-jre/Dockerfile
  
  [29]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22-jre-latest/Dockerfile
  [77]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.0-22.28-jre/Dockerfile
  [78]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.1-22.30-jre/Dockerfile
  [82]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.2-22.32-jre/Dockerfile
  
  [30]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21-jre-latest/Dockerfile
  [87]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.0-21.28.85-jre/Dockerfile
  [88]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.1-21.30-jre/Dockerfile
  [93]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.1-21.30.15-jre/Dockerfile
  
  
  
  
  
  
  
  
  
  
  [31]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20-jre-latest/Dockerfile
  [123]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.0-20.28.85-jre/Dockerfile
  [127]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.1-20.30.11-jre/Dockerfile
  [129]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.2-20.32.11-jre/Dockerfile
  
  [32]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19-jre-latest/Dockerfile
  [134]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.0-19.28.81-jre/Dockerfile
  [135]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.1-19.30.11-jre/Dockerfile
  [138]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.2-19.32.13-jre/Dockerfile
  
  [33]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18-jre-latest/Dockerfile
  [145]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.1-18.30.11-jre/Dockerfile
  [146]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.2.1-18.32.13-jre/Dockerfile
  [150]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.2-18.32.11-jre/Dockerfile
  
  [34]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17-jre-latest/Dockerfile
  [155]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.0-17.28.13-jre/Dockerfile
  [156]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.1-17.30.15-jre/Dockerfile
  [160]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.2-17.32.13-jre/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [35]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16-jre-latest/Dockerfile
  [221]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.0-16.28.11-jre/Dockerfile
  [222]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.1-16.30.15-jre/Dockerfile
  [225]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.2-16.32.15-jre/Dockerfile
  
  [36]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15-jre-latest/Dockerfile
  [235]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.7-15.40.19-jre/Dockerfile
  [239]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.8-15.42.15-jre/Dockerfile
  [241]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.9-15.44.13-jre/Dockerfile
  
  
  [37]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13-jre-latest/Dockerfile
  [263]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.11-13.48.19-jre/Dockerfile
  [264]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.12-13.50.15-jre/Dockerfile
  [269]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.13-13.52.15-jre/Dockerfile
  
  
  [38]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11-jre-latest/Dockerfile
  [293]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.15-11.56.19-jre/Dockerfile
  [298]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.16.1-11.58.23-jre/Dockerfile
  [301]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.16-11.58.15-jre/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [39]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8-jre-latest/Dockerfile
  [397]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u332-8.62.0.19-jre/Dockerfile
  [401]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u342-8.64.0.15-jre/Dockerfile
  [404]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u345-8.64.0.19-jre/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [40]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/26-latest/Dockerfile
  [42]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/26.0.0-26.28/Dockerfile
  
  [44]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25-latest/Dockerfile
  [46]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.0-25.28/Dockerfile
  [48]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.1-25.30/Dockerfile
  [51]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/25.0.2-25.32/Dockerfile
  
  [54]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24-latest/Dockerfile
  [55]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.0-24.28/Dockerfile
  [60]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.1-24.30/Dockerfile
  [63]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/24.0.2-24.32/Dockerfile
  
  [64]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23-latest/Dockerfile
  [66]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.0-23.28/Dockerfile
  [68]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.1-23.30/Dockerfile
  [71]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/23.0.2-23.32/Dockerfile
  
  [74]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22-latest/Dockerfile
  [76]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.0-22.28/Dockerfile
  [80]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.1-22.30/Dockerfile
  [81]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/22.0.2-22.32/Dockerfile
  
  [84]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21-latest/Dockerfile
  [86]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.0-21.28.85/Dockerfile
  [90]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.1-21.30/Dockerfile
  [92]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/21.0.1-21.30.15/Dockerfile
  
  
  
  
  
  
  
  
  
  
  [121]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20-latest/Dockerfile
  [122]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.0-20.28.85/Dockerfile
  [125]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.1-20.30.11/Dockerfile
  [128]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/20.0.2-20.32.11/Dockerfile
  
  [131]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19-latest/Dockerfile
  [133]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.0-19.28.81/Dockerfile
  [137]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.1-19.30.11/Dockerfile
  [139]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/19.0.2-19.32.13/Dockerfile
  
  
  [142]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18-latest/Dockerfile
  [144]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.1-18.30.11/Dockerfile
  [148]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.2.1-18.32.13/Dockerfile
  [151]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.2-18.32.11/Dockerfile
  
  [152]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17-latest/Dockerfile
  [154]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.0-17.28.13/Dockerfile
  [157]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.1-17.30.15/Dockerfile
  [159]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.2-17.32.13/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [219]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16-latest/Dockerfile
  [220]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.0-16.28.11/Dockerfile
  [223]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.1-16.30.15/Dockerfile
  [224]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.2-16.32.15/Dockerfile
  
  [226]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15-latest/Dockerfile
  [227]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.0-15.27.17/Dockerfile
  [228]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.1-15.28.13/Dockerfile
  [229]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.1-15.28.51/Dockerfile
  
  
  
  
  
  
  
  
  
  
  [247]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/14-latest/Dockerfile
  [248]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/14.0.1-14.28.21/Dockerfile
  [249]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/14.0.2-14.29.23/Dockerfile
  
  [250]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13-latest/Dockerfile
  [251]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.1-13.28/Dockerfile
  [252]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.2-13.29/Dockerfile
  [253]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.3-13.31.11/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  [273]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/12-latest/Dockerfile
  [274]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/12.0.1-12.2/Dockerfile
  [275]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/12.0.2-12.3/Dockerfile
  [276]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/12-12.1/Dockerfile
  
  [277]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11-latest/Dockerfile
  [278]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.1-11.2/Dockerfile
  [279]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.2-11.29/Dockerfile
  [280]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.3-11.31/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [350]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/10-latest/Dockerfile
  [351]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/10u01-10.2/Dockerfile
  [352]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/10u02-10.3/Dockerfile
  
  [353]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9-latest/Dockerfile
  [354]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9-ea/Dockerfile
  [355]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9u01-9.0.1.3/Dockerfile
  [356]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9u04-9.0.4.1/Dockerfile
  
  
  [358]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8-latest/Dockerfile
  [359]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u11-8.2.0.1/Dockerfile
  [360]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u20-8.3.0.1/Dockerfile
  [361]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u25-8.4.0.1/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [453]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7-latest/Dockerfile
  [454]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u65-7.6.0.1/Dockerfile
  [455]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u72-7.7.0.1/Dockerfile
  [456]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u76-7.8.0.3/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [488]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6-latest/Dockerfile
  [489]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u53-6.5.0.2/Dockerfile
  [490]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u56-6.6.0.1/Dockerfile
  [491]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u59-6.7.0.2/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  