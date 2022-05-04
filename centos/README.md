What is Azul Zulu? 
======================================

Azul Zulu builds of OpenJDK are fully tested, and TCK compliant builds of OpenJDK for Linux, Windows, and macOS operating systems.

Azul Zulu Builds of OpenJDK are available for free unlimited use and are commercially supported by Azul as a part of the Azul Platform Core bundle.
Check out [Azul Platform Core][3] for more information.

Alpine, Centos, Debian, and Ubuntu Docker official images of Zulu are available in the following repositories:

  * [azul/zulu-openjdk-alpine][4]
  * [azul/zulu-openjdk-centos][5]
  * [azul/zulu-openjdk-debian][6]
  * [azul/zulu-openjdk][7]

Tags and `Dockerfile` links
===========================

Most Recent
-----------
 
   * [`18.0.1-18.30.11`, `18-latest` (*18-latest/Dockerfile)*][10]
   * [`17.0.3-17.34.19`, `17-latest` (*17-latest/Dockerfile)*][12]
   * [`16.0.2-16.32.15`, `16-latest` (*16-latest/Dockerfile)*][27]
   * [`15.0.7-15.40.19`, `15-latest` (*15-latest/Dockerfile)*][35]
   * [`14.0.2-14.29.23`, `14-latest` (*14-latest/Dockerfile)*][45]
   * [`13.0.11-13.48.19`, `13-latest` (*13-latest/Dockerfile)*][48]
   * [`12.0.2-12.3`, `12-12.1` (*12-12.1/Dockerfile)*][60]
   * [`11.0.14.1-11.54.25`, `11-latest` (*11-latest/Dockerfile)*][64]
   * [`10u02-10.3`, `10-latest` (*10-latest/Dockerfile)*][81]
   * [`9u07-9.0.7.1`, `9-ea` (*9-ea/Dockerfile)*][84]
   * [`8u332-8.62.0.19`, `8-latest` (*8-latest/Dockerfile)*][89]
   * [`7u342-7.54.0.13`, `7-latest` (*7-latest/Dockerfile)*][128]
   * [`6u119-6.22.0.3`, `6-latest` (*6-latest/Dockerfile)*][162]

Previous
--------

Earlier Ubuntu Docker image tags of Azul Zulu:

  * [17-jre-headless-latest][22],
  [17.0.0-17.28.13-jre-headless][23],
  [17.0.1-17.30.15-jre-headless][24],
  [17.0.2-17.32.13-jre-headless][25],
  [17.0.3-17.34.19-jre-headless][26],
  
  * [17-jre-latest][13],
  [17.0.0-17.28.13-jre][18],
  [17.0.1-17.30.15-jre][19],
  [17.0.2-17.32.13-jre][20],
  [17.0.3-17.34.19-jre][21],
  
  * [16-jre-latest][28],
  [16.0.0-16.28.11-jre][32],
  [16.0.1-16.30.15-jre][33],
  [16.0.2-16.32.15-jre][34],
  
  * [18-latest][10],
  [18.0.1-18.30.11][11],
  
  * [17-latest][12],
  [17.0.0-17.28.13][14],
  [17.0.1-17.30.15][15],
  [17.0.2-17.32.13][16],
  [17.0.3-17.34.19][17],
  
  * [16-latest][27],
  [16.0.0-16.28.11][29],
  [16.0.1-16.30.15][30],
  [16.0.2-16.32.15][31],
  
  * [15-latest][35],
  [15.0.0-15.27.17][36],
  [15.0.1-15.28.13][37],
  [15.0.1-15.28.51][38],
  [15.0.2-15.29.15][39],
  [15.0.3-15.32.15][40],
  [15.0.4-15.34.17][41],
  [15.0.5-15.36.13][42],
  [15.0.6-15.38.17][43],
  [15.0.7-15.40.19][44],
  
  * [14-latest][45],
  [14.0.1-14.28.21][46],
  [14.0.2-14.29.23][47],
  
  * [13-latest][48],
  [13.0.1-13.28][49],
  [13.0.2-13.29][50],
  [13.0.3-13.31.11][51],
  [13.0.4-13.33.25][52],
  [13.0.5-13.35.17][53],
  [13.0.6-13.37.21][54],
  [13.0.7-13.40.15][55],
  [13.0.8-13.42.17][56],
  [13.0.9-13.44.13][57],
  [13.0.10-13.46.15][58],
  [13.0.11-13.48.19][59],
  
  * [12-12.1][60],
  [12-latest][61],
  [12.0.1-12.2][62],
  [12.0.2-12.3][63],
  
  * [11-latest][64],
  [11.0.1-11.2][65],
  [11.0.2-11.29][66],
  [11.0.3-11.31][67],
  [11.0.4-11.33][68],
  [11.0.5-11.35][69],
  [11.0.6-11.37][70],
  [11.0.7-11.39.15][71],
  [11.0.8-11.41.23][72],
  [11.0.9-11.43.21][73],
  [11.0.10-11.45.27][74],
  [11.0.11-11.48.21][75],
  [11.0.12-11.50.19][76],
  [11.0.13-11.52.13][77],
  [11.0.14-11.54.23][78],
  [11.0.15-11.56.19][79],
  [11.0.14.1-11.54.25][80],
  
  * [10-latest][81],
  [10u01-10.2][82],
  [10u02-10.3][83],
  
  * [9-ea][84],
  [9-latest][85],
  [9u01-9.0.1.3][86],
  [9u04-9.0.4.1][87],
  [9u07-9.0.7.1][88],
  
  * [8-latest][89],
  [8u11-8.2.0.1][90],
  [8u20-8.3.0.1][91],
  [8u25-8.4.0.1][92],
  [8u31-8.5.0.1][93],
  [8u40-8.6.0.1][94],
  [8u45-8.7.0.5][95],
  [8u51-8.8.0.3][96],
  [8u60-8.9.0.4][97],
  [8u65-8.10.0.1][98],
  [8u66-8.11.0.1][99],
  [8u72-8.13.0.5][100],
  [8u92-8.15.0.1][101],
  [8u102-8.17.0.7][102],
  [8u112-8.19.0.1][103],
  [8u121-8.20.0.5][104],
  [8u131-8.21.0.1][105],
  [8u144-8.23.0.3][106],
  [8u152-8.25.0.1][107],
  [8u162-8.27.0.7][108],
  [8u172-8.30.0.1][109],
  [8u181-8.31.0.1][110],
  [8u192-8.33.0.1][111],
  [8u202-8.36.0.1][112],
  [8u212-8.38.0.13][113],
  [8u222-8.40.0.25][114],
  [8u232-8.42.0.21][115],
  [8u232-8.42.0.23][116],
  [8u242-8.44.0.11][117],
  [8u252-8.46.0.19][118],
  [8u262-8.48.0.51][119],
  [8u272-8.50.0.21][120],
  [8u275-8.50.0.53][121],
  [8u282-8.52.0.23][122],
  [8u292-8.54.0.21][123],
  [8u302-8.56.0.21][124],
  [8u312-8.58.0.13][125],
  [8u322-8.60.0.21][126],
  [8u332-8.62.0.19][127],
  
  * [7-latest][128],
  [7u65-7.6.0.1][129],
  [7u72-7.7.0.1][130],
  [7u76-7.8.0.3][131],
  [7u79-7.9.0.2][132],
  [7u80-7.10.0.1][133],
  [7u85-7.11.0.3][134],
  [7u91-7.12.0.3][135],
  [7u95-7.13.0.1][136],
  [7u101-7.14.0.5][137],
  [7u111-7.15.0.5][138],
  [7u121-7.16.0.1][139],
  [7u131-7.17.0.5][140],
  [7u141-7.18.0.3][141],
  [7u154-7.20.0.3][142],
  [7u161-7.21.0.3][143],
  [7u171-7.22.0.3][144],
  [7u181-7.23.0.1][145],
  [7u191-7.24.0.1][146],
  [7u201-7.25.0.5][147],
  [7u211-7.27.0.1][148],
  [7u222-7.29.0.5][149],
  [7u232-7.31.0.5][150],
  [7u242-7.34.0.5][151],
  [7u252-7.36.0.5][152],
  [7u262-7.38.0.11][153],
  [7u272-7.40.0.15][154],
  [7u282-7.42.0.13][155],
  [7u285-7.42.0.51][156],
  [7u292-7.44.0.11][157],
  [7u302-7.46.0.11][158],
  [7u312-7.48.0.11][159],
  [7u332-7.52.0.11][160],
  [7u342-7.54.0.13][161],
  
  * [6-latest][162],
  [6u53-6.5.0.2][163],
  [6u56-6.6.0.1][164],
  [6u59-6.7.0.2][165],
  [6u63-6.8.0.1][166],
  [6u69-6.9.0.3][167],
  [6u73-6.10.0.3][168],
  [6u77-6.11.0.2][169],
  [6u79-6.12.0.2][170],
  [6u83-6.13.0.7][171],
  [6u87-6.14.0.1][172],
  [6u89-6.15.0.1][173],
  [6u93-6.16.0.1][174],
  [6u97-6.17.0.1][175],
  [6u99-6.18.0.3][176],
  [6u103-6.19.0.1][177],
  [6u107-6.20.0.1][178],
  [6u113-6.21.0.3][179],
  [6u119-6.22.0.3][180],
  

Usage
=====

This Azul Zulu repository supports numerous versions of OpenJDK-based Java SE JDKs. Versions 7-17 of Azul Zulu are compliant with Java SE 7-17 respectively.

To run a container of your choice, use commands below as an example.

For Azul Zulu OpenJDK 11, run:

    docker run -it --rm azul/zulu-openjdk-centos:11 java -version

  [1]: https://www.azul.com/files/ZuluDocker60.gif
  [2]: https://www.azul.com/
  [3]: https://www.azul.com/products/core/
  [4]: https://hub.docker.com/r/azul/zulu-openjdk-alpine
  [5]: https://hub.docker.com/r/azul/zulu-openjdk-centos
  [6]: https://hub.docker.com/r/azul/zulu-openjdk-debian
  [7]: https://hub.docker.com/r/azul/zulu-openjdk


  [22]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17-jre-headless-latest/Dockerfile
  [23]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.0-17.28.13-jre-headless/Dockerfile
  [24]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.1-17.30.15-jre-headless/Dockerfile
  [25]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.2-17.32.13-jre-headless/Dockerfile
  [26]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.3-17.34.19-jre-headless/Dockerfile
  
  [13]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17-jre-latest/Dockerfile
  [18]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.0-17.28.13-jre/Dockerfile
  [19]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.1-17.30.15-jre/Dockerfile
  [20]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.2-17.32.13-jre/Dockerfile
  [21]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.3-17.34.19-jre/Dockerfile
  
  [28]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16-jre-latest/Dockerfile
  [32]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.0-16.28.11-jre/Dockerfile
  [33]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.1-16.30.15-jre/Dockerfile
  [34]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.2-16.32.15-jre/Dockerfile
  
  [10]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18-latest/Dockerfile
  [11]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/18.0.1-18.30.11/Dockerfile
  
  [12]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17-latest/Dockerfile
  [14]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.0-17.28.13/Dockerfile
  [15]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.1-17.30.15/Dockerfile
  [16]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.2-17.32.13/Dockerfile
  [17]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/17.0.3-17.34.19/Dockerfile
  
  [27]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16-latest/Dockerfile
  [29]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.0-16.28.11/Dockerfile
  [30]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.1-16.30.15/Dockerfile
  [31]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/16.0.2-16.32.15/Dockerfile
  
  [35]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15-latest/Dockerfile
  [36]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.0-15.27.17/Dockerfile
  [37]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.1-15.28.13/Dockerfile
  [38]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.1-15.28.51/Dockerfile
  [39]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.2-15.29.15/Dockerfile
  [40]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.3-15.32.15/Dockerfile
  [41]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.4-15.34.17/Dockerfile
  [42]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.5-15.36.13/Dockerfile
  [43]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.6-15.38.17/Dockerfile
  [44]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/15.0.7-15.40.19/Dockerfile
  
  [45]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/14-latest/Dockerfile
  [46]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/14.0.1-14.28.21/Dockerfile
  [47]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/14.0.2-14.29.23/Dockerfile
  
  [48]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13-latest/Dockerfile
  [49]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.1-13.28/Dockerfile
  [50]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.2-13.29/Dockerfile
  [51]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.3-13.31.11/Dockerfile
  [52]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.4-13.33.25/Dockerfile
  [53]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.5-13.35.17/Dockerfile
  [54]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.6-13.37.21/Dockerfile
  [55]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.7-13.40.15/Dockerfile
  [56]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.8-13.42.17/Dockerfile
  [57]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.9-13.44.13/Dockerfile
  [58]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.10-13.46.15/Dockerfile
  [59]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/13.0.11-13.48.19/Dockerfile
  
  [60]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/12-12.1/Dockerfile
  [61]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/12-latest/Dockerfile
  [62]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/12.0.1-12.2/Dockerfile
  [63]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/12.0.2-12.3/Dockerfile
  
  [64]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11-latest/Dockerfile
  [65]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.1-11.2/Dockerfile
  [66]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.2-11.29/Dockerfile
  [67]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.3-11.31/Dockerfile
  [68]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.4-11.33/Dockerfile
  [69]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.5-11.35/Dockerfile
  [70]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.6-11.37/Dockerfile
  [71]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.7-11.39.15/Dockerfile
  [72]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.8-11.41.23/Dockerfile
  [73]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.9-11.43.21/Dockerfile
  [74]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.10-11.45.27/Dockerfile
  [75]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.11-11.48.21/Dockerfile
  [76]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.12-11.50.19/Dockerfile
  [77]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.13-11.52.13/Dockerfile
  [78]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.14-11.54.23/Dockerfile
  [79]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.15-11.56.19/Dockerfile
  [80]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/11.0.14.1-11.54.25/Dockerfile
  
  [81]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/10-latest/Dockerfile
  [82]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/10u01-10.2/Dockerfile
  [83]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/10u02-10.3/Dockerfile
  
  [84]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9-ea/Dockerfile
  [85]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9-latest/Dockerfile
  [86]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9u01-9.0.1.3/Dockerfile
  [87]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9u04-9.0.4.1/Dockerfile
  [88]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/9u07-9.0.7.1/Dockerfile
  
  [89]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8-latest/Dockerfile
  [90]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u11-8.2.0.1/Dockerfile
  [91]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u20-8.3.0.1/Dockerfile
  [92]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u25-8.4.0.1/Dockerfile
  [93]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u31-8.5.0.1/Dockerfile
  [94]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u40-8.6.0.1/Dockerfile
  [95]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u45-8.7.0.5/Dockerfile
  [96]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u51-8.8.0.3/Dockerfile
  [97]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u60-8.9.0.4/Dockerfile
  [98]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u65-8.10.0.1/Dockerfile
  [99]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u66-8.11.0.1/Dockerfile
  [100]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u72-8.13.0.5/Dockerfile
  [101]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u92-8.15.0.1/Dockerfile
  [102]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u102-8.17.0.7/Dockerfile
  [103]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u112-8.19.0.1/Dockerfile
  [104]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u121-8.20.0.5/Dockerfile
  [105]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u131-8.21.0.1/Dockerfile
  [106]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u144-8.23.0.3/Dockerfile
  [107]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u152-8.25.0.1/Dockerfile
  [108]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u162-8.27.0.7/Dockerfile
  [109]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u172-8.30.0.1/Dockerfile
  [110]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u181-8.31.0.1/Dockerfile
  [111]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u192-8.33.0.1/Dockerfile
  [112]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u202-8.36.0.1/Dockerfile
  [113]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u212-8.38.0.13/Dockerfile
  [114]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u222-8.40.0.25/Dockerfile
  [115]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u232-8.42.0.21/Dockerfile
  [116]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u232-8.42.0.23/Dockerfile
  [117]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u242-8.44.0.11/Dockerfile
  [118]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u252-8.46.0.19/Dockerfile
  [119]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u262-8.48.0.51/Dockerfile
  [120]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u272-8.50.0.21/Dockerfile
  [121]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u275-8.50.0.53/Dockerfile
  [122]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u282-8.52.0.23/Dockerfile
  [123]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u292-8.54.0.21/Dockerfile
  [124]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u302-8.56.0.21/Dockerfile
  [125]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u312-8.58.0.13/Dockerfile
  [126]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u322-8.60.0.21/Dockerfile
  [127]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/8u332-8.62.0.19/Dockerfile
  
  [128]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7-latest/Dockerfile
  [129]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u65-7.6.0.1/Dockerfile
  [130]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u72-7.7.0.1/Dockerfile
  [131]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u76-7.8.0.3/Dockerfile
  [132]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u79-7.9.0.2/Dockerfile
  [133]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u80-7.10.0.1/Dockerfile
  [134]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u85-7.11.0.3/Dockerfile
  [135]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u91-7.12.0.3/Dockerfile
  [136]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u95-7.13.0.1/Dockerfile
  [137]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u101-7.14.0.5/Dockerfile
  [138]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u111-7.15.0.5/Dockerfile
  [139]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u121-7.16.0.1/Dockerfile
  [140]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u131-7.17.0.5/Dockerfile
  [141]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u141-7.18.0.3/Dockerfile
  [142]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u154-7.20.0.3/Dockerfile
  [143]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u161-7.21.0.3/Dockerfile
  [144]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u171-7.22.0.3/Dockerfile
  [145]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u181-7.23.0.1/Dockerfile
  [146]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u191-7.24.0.1/Dockerfile
  [147]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u201-7.25.0.5/Dockerfile
  [148]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u211-7.27.0.1/Dockerfile
  [149]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u222-7.29.0.5/Dockerfile
  [150]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u232-7.31.0.5/Dockerfile
  [151]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u242-7.34.0.5/Dockerfile
  [152]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u252-7.36.0.5/Dockerfile
  [153]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u262-7.38.0.11/Dockerfile
  [154]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u272-7.40.0.15/Dockerfile
  [155]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u282-7.42.0.13/Dockerfile
  [156]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u285-7.42.0.51/Dockerfile
  [157]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u292-7.44.0.11/Dockerfile
  [158]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u302-7.46.0.11/Dockerfile
  [159]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u312-7.48.0.11/Dockerfile
  [160]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u332-7.52.0.11/Dockerfile
  [161]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/7u342-7.54.0.13/Dockerfile
  
  [162]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6-latest/Dockerfile
  [163]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u53-6.5.0.2/Dockerfile
  [164]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u56-6.6.0.1/Dockerfile
  [165]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u59-6.7.0.2/Dockerfile
  [166]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u63-6.8.0.1/Dockerfile
  [167]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u69-6.9.0.3/Dockerfile
  [168]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u73-6.10.0.3/Dockerfile
  [169]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u77-6.11.0.2/Dockerfile
  [170]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u79-6.12.0.2/Dockerfile
  [171]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u83-6.13.0.7/Dockerfile
  [172]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u87-6.14.0.1/Dockerfile
  [173]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u89-6.15.0.1/Dockerfile
  [174]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u93-6.16.0.1/Dockerfile
  [175]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u97-6.17.0.1/Dockerfile
  [176]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u99-6.18.0.3/Dockerfile
  [177]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u103-6.19.0.1/Dockerfile
  [178]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u107-6.20.0.1/Dockerfile
  [179]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u113-6.21.0.3/Dockerfile
  [180]: https://github.com/zulu-openjdk/zulu-openjdk/blob/master/centos/6u119-6.22.0.3/Dockerfile
  