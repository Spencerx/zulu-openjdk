Azul Zulu Ubuntu
================

These Docker images of Azul Zulu Build of OpenJDK are based on Ubuntu.

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


  * [`26.0.0-26.28`, `26-latest` (*26-latest/Dockerfile)*][54]
  * [`25.0.2-25.32`, `25-latest` (*25-latest/Dockerfile)*][60]
  * [`22.0.2-22.32`, `22-latest` (*22-latest/Dockerfile)*][108]
  * [`21.0.10-21.48`, `21-latest` (*21-latest/Dockerfile)*][122]
  * [`17.0.18-17.64`, `17-latest` (*17-latest/Dockerfile)*][209]
  * [`11.0.30-11.86`, `11-latest` (*11-latest/Dockerfile)*][352]
  * [`8u482-8.92`, `8-latest` (*8-latest/Dockerfile)*][433]

Previous
--------

Earlier Ubuntu Docker image tags(the most recent 3 tags) of Azul Zulu for previous update releases of OpenJDK are as follows:


  *[26-jre-headless-latest][11],
  [26.0.0-26.28-jre-headless][57],
  
  *[25-jre-headless-latest][12],
  [25.0.0-25.28-jre-headless][63],
  [25.0.1-25.30-jre-headless][67],
  
  
  *[24-jre-headless-latest][13],
  [24.0.0-24.28-jre-headless][80],
  [24.0.1-24.30-jre-headless][85],
  
  
  *[23-jre-headless-latest][14],
  [23.0.0-23.28-jre-headless][97],
  [23.0.1-23.30-jre-headless][99],
  
  
  *[22-jre-headless-latest][15],
  [22.0.0-22.28-jre-headless][109],
  [22.0.1-22.30-jre-headless][115],
  
  
  *[21-jre-headless-latest][16],
  [21.0.0-21.28.85-jre-headless][123],
  [21.0.1-21.30-jre-headless][129],
  
  
  
  
  
  
  
  
  
  
  
  *[20-jre-headless-latest][17],
  [20.0.0-20.28.85-jre-headless][181],
  [20.0.1-20.30.11-jre-headless][183],
  
  
  *[19-jre-headless-latest][18],
  [19.0.0-19.28.81-jre-headless][189],
  [19.0.1-19.30.11-jre-headless][193],
  
  
  *[18-jre-headless-latest][19],
  [18.0.1-18.30.11-jre-headless][200],
  [18.0.2.1-18.32.13-jre-headless][204],
  
  
  *[17-jre-headless-latest][20],
  [17.0.0-17.28.13-jre-headless][210],
  [17.0.1-17.30.15-jre-headless][215],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[15-jre-headless-latest][21],
  [15.0.7-15.40.19-jre-headless][311],
  [15.0.8-15.42.15-jre-headless][315],
  
  
  
  *[13-jre-headless-latest][22],
  [13.0.11-13.48.19-jre-headless][337],
  [13.0.12-13.50.15-jre-headless][341],
  
  
  
  *[11-jre-headless-latest][23],
  [11.0.15-11.56.19-jre-headless][369],
  [11.0.16.1-11.58.23-jre-headless][371],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[8-jre-headless-latest][24],
  [8u332-8.62.0.19-jre-headless][471],
  [8u342-8.64.0.15-jre-headless][475],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[26-jre-crac-latest][25],
  [26.0.0-26.28-jre-crac][55],
  
  *[26-jdk-crac-latest][26],
  [26.0.0-26.28-jdk-crac][56],
  
  *[25-jre-crac-latest][27],
  [25.0.0-25.28-jre-crac][64],
  [25.0.1-25.30-jre-crac][69],
  
  
  *[25-jdk-crac-latest][28],
  [25.0.0-25.28-jdk-crac][65],
  [25.0.1-25.30-jdk-crac][70],
  
  
  *[24-jre-crac-latest][29],
  [24.0.0-24.28-jre-crac][78],
  [24.0.1-24.30-jre-crac][83],
  
  
  *[24-jdk-crac-latest][30],
  [24.0.0-24.28-jdk-crac][81],
  [24.0.1-24.30-jdk-crac][84],
  
  
  *[23-jre-crac-latest][31],
  [23.0.0-23.28-jre-crac][94],
  [23.0.1-23.30-jre-crac][100],
  
  
  *[23-jdk-crac-latest][32],
  [23.0.0-23.28-jdk-crac][96],
  [23.0.1-23.30-jdk-crac][102],
  
  
  *[22-jre-crac-latest][33],
  [22.0.2-22.32-jre-crac][117],
  
  *[22-jdk-crac-latest][34],
  [22.0.0-22.28-jdk-crac][111],
  [22.0.1-22.30-jdk-crac][114],
  
  
  *[21-jre-crac-latest][35],
  [21.0.4-21.36-jre-crac][147],
  [21.0.5-21.38-jre-crac][149],
  
  
  
  
  
  
  *[21-jdk-crac-latest][36],
  [21.0.0-21.28.89-jdk-crac][126],
  [21.0.1-21.30-jdk-crac][128],
  
  
  
  
  
  
  
  
  
  
  
  *[17-jre-crac-latest][37],
  [17.0.12-17.52-jre-crac][263],
  [17.0.13-17.54-jre-crac][267],
  
  
  
  
  
  
  *[17-jdk-crac-latest][38],
  [17.0.8.1-17.44.55-jdk-crac][240],
  [17.0.8-17.44.17-jdk-crac][244],
  
  
  
  
  
  
  
  
  
  
  
  
  *[26-jre-latest][39],
  [26.0.0-26.28-jre][59],
  
  *[25-jre-latest][40],
  [25.0.0-25.28-jre][61],
  [25.0.1-25.30-jre][68],
  
  
  *[24-jre-latest][41],
  [24.0.0-24.28-jre][79],
  [24.0.1-24.30-jre][82],
  
  
  *[23-jre-latest][42],
  [23.0.0-23.28-jre][93],
  [23.0.1-23.30-jre][101],
  
  
  *[22-jre-latest][43],
  [22.0.0-22.28-jre][112],
  [22.0.1-22.30-jre][113],
  
  
  *[21-jre-latest][44],
  [21.0.0-21.28.85-jre][125],
  [21.0.1-21.30-jre][127],
  
  
  
  
  
  
  
  
  
  
  
  *[20-jre-latest][45],
  [20.0.0-20.28.85-jre][180],
  [20.0.1-20.30.11-jre][184],
  
  
  *[19-jre-latest][46],
  [19.0.0-19.28.81-jre][191],
  [19.0.1-19.30.11-jre][192],
  
  
  *[18-jre-latest][47],
  [18.0.1-18.30.11-jre][202],
  [18.0.2.1-18.32.13-jre][203],
  
  
  *[17-jre-latest][48],
  [17.0.0-17.28.13-jre][212],
  [17.0.1-17.30.15-jre][213],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[16-jre-latest][49],
  [16.0.0-16.28.11-jre][298],
  [16.0.1-16.30.15-jre][299],
  
  
  *[15-jre-latest][50],
  [15.0.7-15.40.19-jre][310],
  [15.0.8-15.42.15-jre][314],
  
  
  
  *[13-jre-latest][51],
  [13.0.11-13.48.19-jre][338],
  [13.0.12-13.50.15-jre][339],
  
  
  
  *[11-jre-latest][52],
  [11.0.15-11.56.19-jre][368],
  [11.0.16.1-11.58.23-jre][373],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[8-jre-latest][53],
  [8u332-8.62.0.19-jre][472],
  [8u342-8.64.0.15-jre][476],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[26-latest][54],
  [26.0.0-26.28][58],
  
  *[25-latest][60],
  [25.0.0-25.28][62],
  [25.0.1-25.30][66],
  
  
  *[24-latest][76],
  [24.0.0-24.28][77],
  [24.0.1-24.30][86],
  
  
  *[23-latest][92],
  [23.0.0-23.28][95],
  [23.0.1-23.30][98],
  
  
  *[22-latest][108],
  [22.0.0-22.28][110],
  [22.0.1-22.30][116],
  
  
  *[21-latest][122],
  [21.0.0-21.28.85][124],
  [21.0.1-21.30][130],
  
  
  
  
  
  
  
  
  
  
  
  *[20-latest][178],
  [20.0.0-20.28.85][179],
  [20.0.1-20.30.11][182],
  
  
  *[19-latest][188],
  [19.0.0-19.28.81][190],
  [19.0.1-19.30.11][194],
  
  
  
  *[18-latest][199],
  [18.0.1-18.30.11][201],
  [18.0.2.1-18.32.13][205],
  
  
  *[17-latest][209],
  [17.0.0-17.28.13][211],
  [17.0.1-17.30.15][214],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[16-latest][296],
  [16.0.0-16.28.11][297],
  [16.0.2-16.32.15][300],
  
  *[15-latest][302],
  [15.0.1-15.28.13][303],
  [15.0.1-15.28.51][304],
  
  
  
  
  
  
  
  
  
  
  *[14-latest][322],
  [14.0.1-14.28.21][323],
  [14.0.2-14.29.23][324],
  
  *[13-latest][325],
  [13.0.1-13.28][326],
  [13.0.2-13.29][327],
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[12-latest][348],
  [12.0.1-12.2][349],
  [12.0.2-12.3][350],
  
  
  *[11-latest][352],
  [11.0.1-11.2][353],
  [11.0.2-11.29][354],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[10-latest][425],
  [10u01-10.2][426],
  [10u02-10.3][427],
  
  *[9-latest][428],
  [9-ea][429],
  [9u01-9.0.1.3][430],
  
  
  
  *[8-latest][433],
  [8u05-8.1.0.6][434],
  [8u11-8.2.0.1][435],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[7-latest][528],
  [7u55-7.4.0.5][529],
  [7u60-7.5.0.1][530],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  *[6-latest][566],
  [6u49-6.4.0.6][567],
  [6u53-6.5.0.2][568],
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
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


  [11]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26-jre-headless-latest/Dockerfile
  [57]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26.0.0-26.28-jre-headless/Dockerfile
  
  [12]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25-jre-headless-latest/Dockerfile
  [63]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.0-25.28-jre-headless/Dockerfile
  [67]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.1-25.30-jre-headless/Dockerfile
  
  
  [13]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24-jre-headless-latest/Dockerfile
  [80]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.0-24.28-jre-headless/Dockerfile
  [85]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.1-24.30-jre-headless/Dockerfile
  
  
  [14]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23-jre-headless-latest/Dockerfile
  [97]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.0-23.28-jre-headless/Dockerfile
  [99]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.1-23.30-jre-headless/Dockerfile
  
  
  [15]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22-jre-headless-latest/Dockerfile
  [109]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.0-22.28-jre-headless/Dockerfile
  [115]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.1-22.30-jre-headless/Dockerfile
  
  
  [16]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21-jre-headless-latest/Dockerfile
  [123]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.0-21.28.85-jre-headless/Dockerfile
  [129]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.1-21.30-jre-headless/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  [17]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20-jre-headless-latest/Dockerfile
  [181]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20.0.0-20.28.85-jre-headless/Dockerfile
  [183]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20.0.1-20.30.11-jre-headless/Dockerfile
  
  
  [18]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19-jre-headless-latest/Dockerfile
  [189]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19.0.0-19.28.81-jre-headless/Dockerfile
  [193]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19.0.1-19.30.11-jre-headless/Dockerfile
  
  
  [19]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18-jre-headless-latest/Dockerfile
  [200]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18.0.1-18.30.11-jre-headless/Dockerfile
  [204]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18.0.2.1-18.32.13-jre-headless/Dockerfile
  
  
  [20]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17-jre-headless-latest/Dockerfile
  [210]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.0-17.28.13-jre-headless/Dockerfile
  [215]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.1-17.30.15-jre-headless/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [21]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15-jre-headless-latest/Dockerfile
  [311]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15.0.7-15.40.19-jre-headless/Dockerfile
  [315]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15.0.8-15.42.15-jre-headless/Dockerfile
  
  
  
  [22]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13-jre-headless-latest/Dockerfile
  [337]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13.0.11-13.48.19-jre-headless/Dockerfile
  [341]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13.0.12-13.50.15-jre-headless/Dockerfile
  
  
  
  [23]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11-jre-headless-latest/Dockerfile
  [369]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11.0.15-11.56.19-jre-headless/Dockerfile
  [371]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11.0.16.1-11.58.23-jre-headless/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [24]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8-jre-headless-latest/Dockerfile
  [471]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8u332-8.62.0.19-jre-headless/Dockerfile
  [475]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8u342-8.64.0.15-jre-headless/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [25]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26-jre-crac-latest/Dockerfile
  [55]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26.0.0-26.28-jre-crac/Dockerfile
  
  [26]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26-jdk-crac-latest/Dockerfile
  [56]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26.0.0-26.28-jdk-crac/Dockerfile
  
  [27]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25-jre-crac-latest/Dockerfile
  [64]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.0-25.28-jre-crac/Dockerfile
  [69]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.1-25.30-jre-crac/Dockerfile
  
  
  [28]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25-jdk-crac-latest/Dockerfile
  [65]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.0-25.28-jdk-crac/Dockerfile
  [70]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.1-25.30-jdk-crac/Dockerfile
  
  
  [29]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24-jre-crac-latest/Dockerfile
  [78]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.0-24.28-jre-crac/Dockerfile
  [83]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.1-24.30-jre-crac/Dockerfile
  
  
  [30]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24-jdk-crac-latest/Dockerfile
  [81]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.0-24.28-jdk-crac/Dockerfile
  [84]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.1-24.30-jdk-crac/Dockerfile
  
  
  [31]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23-jre-crac-latest/Dockerfile
  [94]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.0-23.28-jre-crac/Dockerfile
  [100]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.1-23.30-jre-crac/Dockerfile
  
  
  [32]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23-jdk-crac-latest/Dockerfile
  [96]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.0-23.28-jdk-crac/Dockerfile
  [102]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.1-23.30-jdk-crac/Dockerfile
  
  
  [33]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22-jre-crac-latest/Dockerfile
  [117]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.2-22.32-jre-crac/Dockerfile
  
  [34]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22-jdk-crac-latest/Dockerfile
  [111]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.0-22.28-jdk-crac/Dockerfile
  [114]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.1-22.30-jdk-crac/Dockerfile
  
  
  [35]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21-jre-crac-latest/Dockerfile
  [147]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.4-21.36-jre-crac/Dockerfile
  [149]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.5-21.38-jre-crac/Dockerfile
  
  
  
  
  
  
  [36]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21-jdk-crac-latest/Dockerfile
  [126]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.0-21.28.89-jdk-crac/Dockerfile
  [128]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.1-21.30-jdk-crac/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  [37]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17-jre-crac-latest/Dockerfile
  [263]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.12-17.52-jre-crac/Dockerfile
  [267]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.13-17.54-jre-crac/Dockerfile
  
  
  
  
  
  
  [38]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17-jdk-crac-latest/Dockerfile
  [240]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.8.1-17.44.55-jdk-crac/Dockerfile
  [244]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.8-17.44.17-jdk-crac/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  [39]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26-jre-latest/Dockerfile
  [59]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26.0.0-26.28-jre/Dockerfile
  
  [40]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25-jre-latest/Dockerfile
  [61]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.0-25.28-jre/Dockerfile
  [68]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.1-25.30-jre/Dockerfile
  
  
  [41]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24-jre-latest/Dockerfile
  [79]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.0-24.28-jre/Dockerfile
  [82]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.1-24.30-jre/Dockerfile
  
  
  [42]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23-jre-latest/Dockerfile
  [93]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.0-23.28-jre/Dockerfile
  [101]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.1-23.30-jre/Dockerfile
  
  
  [43]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22-jre-latest/Dockerfile
  [112]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.0-22.28-jre/Dockerfile
  [113]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.1-22.30-jre/Dockerfile
  
  
  [44]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21-jre-latest/Dockerfile
  [125]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.0-21.28.85-jre/Dockerfile
  [127]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.1-21.30-jre/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  [45]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20-jre-latest/Dockerfile
  [180]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20.0.0-20.28.85-jre/Dockerfile
  [184]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20.0.1-20.30.11-jre/Dockerfile
  
  
  [46]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19-jre-latest/Dockerfile
  [191]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19.0.0-19.28.81-jre/Dockerfile
  [192]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19.0.1-19.30.11-jre/Dockerfile
  
  
  [47]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18-jre-latest/Dockerfile
  [202]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18.0.1-18.30.11-jre/Dockerfile
  [203]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18.0.2.1-18.32.13-jre/Dockerfile
  
  
  [48]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17-jre-latest/Dockerfile
  [212]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.0-17.28.13-jre/Dockerfile
  [213]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.1-17.30.15-jre/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [49]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/16-jre-latest/Dockerfile
  [298]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/16.0.0-16.28.11-jre/Dockerfile
  [299]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/16.0.1-16.30.15-jre/Dockerfile
  
  
  [50]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15-jre-latest/Dockerfile
  [310]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15.0.7-15.40.19-jre/Dockerfile
  [314]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15.0.8-15.42.15-jre/Dockerfile
  
  
  
  [51]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13-jre-latest/Dockerfile
  [338]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13.0.11-13.48.19-jre/Dockerfile
  [339]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13.0.12-13.50.15-jre/Dockerfile
  
  
  
  [52]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11-jre-latest/Dockerfile
  [368]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11.0.15-11.56.19-jre/Dockerfile
  [373]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11.0.16.1-11.58.23-jre/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [53]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8-jre-latest/Dockerfile
  [472]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8u332-8.62.0.19-jre/Dockerfile
  [476]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8u342-8.64.0.15-jre/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [54]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26-latest/Dockerfile
  [58]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/26.0.0-26.28/Dockerfile
  
  [60]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25-latest/Dockerfile
  [62]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.0-25.28/Dockerfile
  [66]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/25.0.1-25.30/Dockerfile
  
  
  [76]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24-latest/Dockerfile
  [77]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.0-24.28/Dockerfile
  [86]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/24.0.1-24.30/Dockerfile
  
  
  [92]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23-latest/Dockerfile
  [95]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.0-23.28/Dockerfile
  [98]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/23.0.1-23.30/Dockerfile
  
  
  [108]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22-latest/Dockerfile
  [110]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.0-22.28/Dockerfile
  [116]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/22.0.1-22.30/Dockerfile
  
  
  [122]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21-latest/Dockerfile
  [124]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.0-21.28.85/Dockerfile
  [130]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/21.0.1-21.30/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  [178]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20-latest/Dockerfile
  [179]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20.0.0-20.28.85/Dockerfile
  [182]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/20.0.1-20.30.11/Dockerfile
  
  
  [188]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19-latest/Dockerfile
  [190]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19.0.0-19.28.81/Dockerfile
  [194]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/19.0.1-19.30.11/Dockerfile
  
  
  
  [199]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18-latest/Dockerfile
  [201]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18.0.1-18.30.11/Dockerfile
  [205]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/18.0.2.1-18.32.13/Dockerfile
  
  
  [209]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17-latest/Dockerfile
  [211]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.0-17.28.13/Dockerfile
  [214]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/17.0.1-17.30.15/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [296]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/16-latest/Dockerfile
  [297]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/16.0.0-16.28.11/Dockerfile
  [300]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/16.0.2-16.32.15/Dockerfile
  
  [302]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15-latest/Dockerfile
  [303]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15.0.1-15.28.13/Dockerfile
  [304]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/15.0.1-15.28.51/Dockerfile
  
  
  
  
  
  
  
  
  
  
  [322]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/14-latest/Dockerfile
  [323]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/14.0.1-14.28.21/Dockerfile
  [324]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/14.0.2-14.29.23/Dockerfile
  
  [325]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13-latest/Dockerfile
  [326]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13.0.1-13.28/Dockerfile
  [327]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/13.0.2-13.29/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  [348]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/12-latest/Dockerfile
  [349]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/12.0.1-12.2/Dockerfile
  [350]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/12.0.2-12.3/Dockerfile
  
  
  [352]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11-latest/Dockerfile
  [353]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11.0.1-11.2/Dockerfile
  [354]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/11.0.2-11.29/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [425]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/10-latest/Dockerfile
  [426]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/10u01-10.2/Dockerfile
  [427]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/10u02-10.3/Dockerfile
  
  [428]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/9-latest/Dockerfile
  [429]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/9-ea/Dockerfile
  [430]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/9u01-9.0.1.3/Dockerfile
  
  
  
  [433]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8-latest/Dockerfile
  [434]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8u05-8.1.0.6/Dockerfile
  [435]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/8u11-8.2.0.1/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [528]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/7-latest/Dockerfile
  [529]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/7u55-7.4.0.5/Dockerfile
  [530]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/7u60-7.5.0.1/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  [566]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/6-latest/Dockerfile
  [567]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/6u49-6.4.0.6/Dockerfile
  [568]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/ubuntu/6u53-6.5.0.2/Dockerfile
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  
  