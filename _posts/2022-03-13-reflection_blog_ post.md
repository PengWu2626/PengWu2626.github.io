---
layout: post
title: Reflection Blog Post
---
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
<div>
<style scoped>
.container1{
  background: radial-gradient(#1b2735 0%, #090a0f 100%);
  border-radius: 20px;
}
.glassBox {
  width: 100%;
  height: 400px;
  max-width: 300px;
  border-radius: 20px;
  background: rgba(255, 255, 255, 0.1);
  -webkit-backdrop-filter: blur(2px);
          backdrop-filter: blur(2px);
  border: 1px solid rgba(255, 255, 255, 0.2);
  border-right-color: rgba(255, 255, 255, 0.1);
  border-bottom-color: rgba(255, 255, 255, 0.1);
  box-shadow: 0 20px 30px rgba(0, 0, 0, 0.1);
  padding: 15px;
  position: relative;
  display: flex;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  margin-left: auto;
  margin-right: auto;
  top: 25px;
}
.glassBox, .glassBox * {
  box-sizing: border-box;
  transition: 400ms;
}
.glassBoximgBox img {
  display: block;
  width: 280px;
  height: 200px;
  opacity: 95%;
}
.glassBoxtitle {
  text-align: center;
  margin-top: 15px;
  color: white;
  font-size: 20px;
  font-weight: 400;
  font-family: "Lato";
  opacity: 90%;
}
.glassBox:hover .glassBoximgBox {
  transform: translateY(-50px);
}
.glassBox:hover .glassBoximgBox img {
  transform: translate(-20px, -40px) rotate(-15deg) scale(1.4);
}
#stars {
  width: 1px;
  height: 1px;
  background: transparent;
  box-shadow: 1946px 908px #FFF , 1964px 300px #FFF , 951px 1906px #FFF , 540px 1957px #FFF , 695px 1646px #FFF , 1095px 1164px #FFF , 1734px 1337px #FFF , 248px 1590px #FFF , 551px 335px #FFF , 356px 579px #FFF , 125px 465px #FFF , 1121px 1601px #FFF , 783px 1580px #FFF , 1758px 170px #FFF , 713px 1621px #FFF , 8px 1156px #FFF , 637px 1737px #FFF , 447px 1698px #FFF , 37px 574px #FFF , 257px 459px #FFF , 1649px 1990px #FFF , 1201px 1977px #FFF , 84px 1375px #FFF , 1864px 1317px #FFF , 1122px 190px #FFF , 1894px 719px #FFF , 1132px 162px #FFF , 1653px 1356px #FFF , 1366px 590px #FFF , 642px 1989px #FFF , 846px 759px #FFF , 692px 816px #FFF , 613px 1471px #FFF , 439px 330px #FFF , 601px 799px #FFF , 1619px 1275px #FFF , 1328px 84px #FFF , 1548px 919px #FFF , 1318px 646px #FFF , 547px 598px #FFF , 1629px 1706px #FFF , 1188px 720px #FFF , 1071px 201px #FFF , 969px 841px #FFF , 126px 1560px #FFF , 545px 1232px #FFF , 24px 1926px #FFF , 911px 866px #FFF , 1779px 1253px #FFF , 1868px 812px #FFF , 1760px 797px #FFF , 40px 808px #FFF , 1863px 1783px #FFF , 1536px 872px #FFF , 1551px 1537px #FFF , 1550px 904px #FFF , 1627px 1706px #FFF , 933px 334px #FFF , 340px 1547px #FFF , 82px 1151px #FFF , 1484px 1647px #FFF , 502px 1182px #FFF , 489px 1581px #FFF , 814px 1137px #FFF , 741px 1479px #FFF , 375px 282px #FFF , 1982px 966px #FFF , 401px 1271px #FFF , 1770px 752px #FFF , 1653px 800px #FFF , 390px 1367px #FFF , 1685px 1930px #FFF , 1717px 1879px #FFF , 1528px 487px #FFF , 334px 1101px #FFF , 24px 229px #FFF , 447px 1692px #FFF , 1511px 656px #FFF , 480px 1209px #FFF , 92px 603px #FFF , 39px 1131px #FFF , 1172px 1040px #FFF , 974px 1602px #FFF , 555px 1864px #FFF , 1877px 311px #FFF , 1536px 1721px #FFF , 801px 1474px #FFF , 1125px 992px #FFF , 1725px 765px #FFF , 260px 776px #FFF , 639px 904px #FFF , 341px 541px #FFF , 621px 673px #FFF , 1612px 536px #FFF , 1055px 938px #FFF , 1129px 1494px #FFF , 36px 814px #FFF , 1295px 854px #FFF , 746px 1055px #FFF , 1990px 82px #FFF , 232px 299px #FFF , 665px 684px #FFF , 1489px 1340px #FFF , 733px 34px #FFF , 279px 818px #FFF , 1168px 1671px #FFF , 1771px 622px #FFF , 79px 1133px #FFF , 1966px 31px #FFF , 863px 1026px #FFF , 1000px 1792px #FFF , 875px 322px #FFF , 29px 1974px #FFF , 980px 1407px #FFF , 1039px 1150px #FFF , 1606px 203px #FFF , 933px 920px #FFF , 633px 1154px #FFF , 882px 1372px #FFF , 1416px 211px #FFF , 1549px 1913px #FFF , 1220px 1433px #FFF , 921px 1679px #FFF , 1400px 1518px #FFF , 1028px 829px #FFF , 10px 1301px #FFF , 1282px 1005px #FFF , 633px 311px #FFF , 1074px 1545px #FFF , 315px 1808px #FFF , 1755px 1328px #FFF , 1268px 37px #FFF , 1495px 1108px #FFF , 1526px 658px #FFF , 993px 1368px #FFF , 1817px 571px #FFF , 1848px 876px #FFF , 233px 977px #FFF , 373px 939px #FFF , 1451px 1273px #FFF , 1855px 205px #FFF , 87px 1814px #FFF , 1184px 723px #FFF , 128px 330px #FFF , 822px 252px #FFF , 1588px 1278px #FFF , 411px 1537px #FFF , 1047px 513px #FFF , 1920px 339px #FFF , 54px 1458px #FFF , 284px 1415px #FFF , 38px 707px #FFF , 613px 1688px #FFF , 321px 912px #FFF , 561px 807px #FFF , 172px 54px #FFF , 1747px 1080px #FFF , 216px 1316px #FFF , 349px 1979px #FFF , 366px 277px #FFF , 1860px 1085px #FFF , 1135px 1527px #FFF , 1826px 610px #FFF , 1876px 67px #FFF , 272px 1456px #FFF , 421px 824px #FFF , 1733px 248px #FFF , 1699px 1745px #FFF , 1004px 946px #FFF , 773px 1309px #FFF , 81px 767px #FFF , 905px 1498px #FFF , 426px 967px #FFF , 989px 99px #FFF , 327px 1135px #FFF , 1695px 216px #FFF , 951px 1899px #FFF , 303px 1719px #FFF , 1297px 44px #FFF , 15px 1163px #FFF , 785px 772px #FFF , 752px 1846px #FFF , 1385px 1352px #FFF , 1853px 419px #FFF , 1333px 1667px #FFF , 251px 709px #FFF , 268px 1520px #FFF , 806px 119px #FFF , 1196px 24px #FFF , 92px 987px #FFF , 1077px 111px #FFF , 580px 365px #FFF , 423px 249px #FFF , 48px 746px #FFF , 1580px 1887px #FFF , 354px 1212px #FFF , 1716px 1606px #FFF , 699px 453px #FFF , 420px 123px #FFF , 852px 1550px #FFF , 1155px 1415px #FFF , 1803px 1983px #FFF , 1042px 987px #FFF , 1597px 1619px #FFF , 1734px 1317px #FFF , 607px 294px #FFF , 1635px 452px #FFF , 1688px 1854px #FFF , 809px 519px #FFF , 94px 884px #FFF , 1572px 1943px #FFF , 653px 1511px #FFF , 1470px 1358px #FFF , 605px 298px #FFF , 1528px 854px #FFF , 1433px 206px #FFF , 856px 223px #FFF , 1798px 1843px #FFF , 68px 498px #FFF , 1172px 264px #FFF , 289px 812px #FFF , 1485px 798px #FFF , 393px 1725px #FFF , 1602px 1846px #FFF , 1154px 882px #FFF , 1328px 570px #FFF , 358px 1933px #FFF , 984px 806px #FFF , 1828px 500px #FFF , 128px 767px #FFF , 1411px 1985px #FFF , 1529px 1202px #FFF , 1726px 518px #FFF , 1803px 860px #FFF , 496px 778px #FFF , 1379px 518px #FFF , 1982px 603px #FFF , 1355px 528px #FFF , 1139px 732px #FFF , 310px 143px #FFF , 739px 1056px #FFF , 178px 230px #FFF , 967px 1959px #FFF , 1267px 1697px #FFF , 1089px 586px #FFF , 1975px 1896px #FFF , 1837px 246px #FFF , 241px 442px #FFF , 401px 397px #FFF , 1240px 69px #FFF , 1378px 851px #FFF , 789px 460px #FFF , 1646px 1853px #FFF , 1663px 307px #FFF , 763px 1445px #FFF , 1402px 1552px #FFF , 1862px 1868px #FFF , 1624px 1785px #FFF , 66px 1978px #FFF , 639px 1251px #FFF , 358px 780px #FFF , 1770px 932px #FFF , 1263px 1718px #FFF , 1294px 1184px #FFF , 1595px 631px #FFF , 832px 1738px #FFF , 1755px 319px #FFF , 1083px 1707px #FFF , 1947px 760px #FFF , 711px 1764px #FFF , 1021px 1658px #FFF , 292px 1730px #FFF , 423px 157px #FFF , 525px 1981px #FFF , 604px 1590px #FFF , 437px 1673px #FFF , 1106px 1642px #FFF , 1434px 389px #FFF , 172px 780px #FFF , 1438px 1461px #FFF , 1438px 734px #FFF , 875px 1650px #FFF , 403px 774px #FFF , 1051px 351px #FFF , 297px 1048px #FFF , 576px 1604px #FFF , 1384px 1191px #FFF , 1309px 1083px #FFF , 1505px 1624px #FFF , 1617px 972px #FFF , 760px 133px #FFF , 667px 759px #FFF , 450px 1965px #FFF , 359px 1220px #FFF , 1065px 295px #FFF , 1365px 1608px #FFF , 533px 240px #FFF , 1696px 653px #FFF , 1630px 1748px #FFF , 864px 1010px #FFF , 615px 1098px #FFF , 792px 775px #FFF , 1491px 458px #FFF , 1989px 969px #FFF , 1487px 1938px #FFF , 1566px 1435px #FFF , 1884px 1144px #FFF , 1666px 1024px #FFF , 1239px 1600px #FFF , 1016px 1057px #FFF , 1381px 1482px #FFF , 1408px 1865px #FFF , 1361px 1515px #FFF , 330px 136px #FFF , 775px 985px #FFF , 1406px 1074px #FFF , 612px 769px #FFF , 1569px 262px #FFF , 1411px 139px #FFF , 1784px 1019px #FFF , 780px 1370px #FFF , 174px 1741px #FFF , 1154px 161px #FFF , 1237px 1435px #FFF , 975px 346px #FFF , 1px 775px #FFF , 692px 536px #FFF , 1322px 20px #FFF , 1427px 979px #FFF , 329px 568px #FFF , 75px 627px #FFF , 1733px 1665px #FFF , 976px 1163px #FFF , 1653px 123px #FFF , 799px 1241px #FFF , 574px 628px #FFF , 615px 31px #FFF , 1519px 695px #FFF , 1575px 634px #FFF , 17px 240px #FFF , 807px 843px #FFF , 487px 574px #FFF , 447px 1134px #FFF , 819px 1487px #FFF , 781px 1877px #FFF , 449px 789px #FFF , 956px 1124px #FFF , 48px 1071px #FFF , 340px 1196px #FFF , 1782px 517px #FFF , 1097px 1871px #FFF , 1987px 962px #FFF , 1847px 1109px #FFF , 1960px 752px #FFF , 1114px 577px #FFF , 1122px 572px #FFF , 1112px 1849px #FFF , 629px 1235px #FFF , 865px 1004px #FFF , 1730px 53px #FFF , 629px 1540px #FFF , 1192px 526px #FFF , 104px 1078px #FFF , 1102px 1207px #FFF , 313px 1198px #FFF , 703px 1083px #FFF , 812px 1403px #FFF , 128px 1292px #FFF , 1676px 1653px #FFF , 1143px 1291px #FFF , 52px 95px #FFF , 1893px 337px #FFF , 597px 332px #FFF , 1451px 951px #FFF , 53px 777px #FFF , 828px 1903px #FFF , 478px 653px #FFF , 819px 1286px #FFF , 898px 1758px #FFF , 82px 503px #FFF , 188px 1697px #FFF , 1209px 549px #FFF , 1244px 1537px #FFF , 489px 1376px #FFF , 16px 1857px #FFF , 1564px 1246px #FFF , 910px 442px #FFF , 362px 1444px #FFF , 710px 1907px #FFF , 341px 95px #FFF , 1385px 1543px #FFF , 1581px 546px #FFF , 1335px 1927px #FFF , 1619px 1693px #FFF , 185px 559px #FFF , 101px 1683px #FFF , 963px 284px #FFF , 1507px 466px #FFF , 834px 1912px #FFF , 1367px 1649px #FFF , 329px 960px #FFF , 3px 1307px #FFF , 1351px 855px #FFF , 248px 1912px #FFF , 417px 481px #FFF , 1728px 1167px #FFF , 1247px 1408px #FFF , 362px 835px #FFF , 1433px 582px #FFF , 267px 742px #FFF , 1292px 321px #FFF , 318px 1268px #FFF , 1153px 535px #FFF , 1631px 388px #FFF , 1622px 1634px #FFF , 1087px 1375px #FFF , 230px 316px #FFF , 1513px 1451px #FFF , 217px 98px #FFF , 824px 1955px #FFF , 1398px 829px #FFF , 1019px 1396px #FFF , 1490px 354px #FFF , 129px 792px #FFF , 362px 1228px #FFF , 663px 1735px #FFF , 402px 1690px #FFF , 862px 1645px #FFF , 892px 677px #FFF , 540px 1905px #FFF , 246px 1818px #FFF , 1580px 1419px #FFF , 427px 1655px #FFF , 1411px 514px #FFF , 988px 630px #FFF , 399px 886px #FFF , 190px 184px #FFF , 599px 1866px #FFF , 77px 681px #FFF , 31px 636px #FFF , 1547px 689px #FFF , 1161px 269px #FFF , 904px 658px #FFF , 1167px 1130px #FFF , 499px 73px #FFF , 1631px 1762px #FFF , 1628px 1727px #FFF , 812px 1507px #FFF , 1916px 1744px #FFF , 136px 481px #FFF , 1966px 1233px #FFF , 1906px 1053px #FFF , 449px 1307px #FFF , 1897px 717px #FFF , 1359px 936px #FFF , 1825px 1448px #FFF , 405px 1004px #FFF , 875px 210px #FFF , 182px 1398px #FFF , 1px 1276px #FFF , 290px 1917px #FFF , 1182px 169px #FFF , 86px 1884px #FFF , 707px 659px #FFF , 1461px 658px #FFF , 1459px 1504px #FFF , 697px 67px #FFF , 584px 929px #FFF , 1670px 457px #FFF , 1487px 786px #FFF , 1609px 773px #FFF , 1196px 264px #FFF , 1787px 492px #FFF , 1139px 800px #FFF , 871px 246px #FFF , 310px 1752px #FFF , 1572px 516px #FFF , 1326px 456px #FFF , 1336px 1374px #FFF , 1036px 52px #FFF , 1448px 580px #FFF , 1642px 1470px #FFF , 460px 332px #FFF , 1376px 295px #FFF , 1598px 330px #FFF , 1604px 16px #FFF , 1339px 385px #FFF , 269px 842px #FFF , 555px 33px #FFF , 304px 9px #FFF , 1803px 471px #FFF , 956px 1456px #FFF , 1999px 792px #FFF , 1900px 590px #FFF , 865px 1011px #FFF , 296px 807px #FFF , 674px 1129px #FFF , 1204px 1824px #FFF , 1981px 1164px #FFF , 1313px 1128px #FFF , 914px 778px #FFF , 1584px 751px #FFF , 1141px 1501px #FFF , 1691px 519px #FFF , 1166px 179px #FFF , 1405px 1470px #FFF , 1087px 275px #FFF , 1293px 1295px #FFF , 684px 772px #FFF , 512px 41px #FFF , 1332px 175px #FFF , 623px 1047px #FFF , 468px 1765px #FFF , 1591px 1839px #FFF , 632px 1910px #FFF , 767px 348px #FFF , 179px 1367px #FFF , 149px 337px #FFF , 24px 92px #FFF , 891px 984px #FFF , 337px 1247px #FFF , 795px 10px #FFF , 1070px 1548px #FFF , 1621px 1828px #FFF , 965px 1359px #FFF , 386px 145px #FFF , 1925px 852px #FFF , 85px 1280px #FFF , 429px 1850px #FFF , 627px 1973px #FFF , 831px 1918px #FFF , 154px 1001px #FFF , 42px 803px #FFF , 1806px 1695px #FFF , 1672px 1251px #FFF , 1008px 164px #FFF , 1677px 606px #FFF , 319px 367px #FFF , 1409px 171px #FFF , 1608px 1465px #FFF , 1611px 122px #FFF , 1166px 361px #FFF , 752px 72px #FFF , 10px 1356px #FFF , 885px 787px #FFF , 768px 1074px #FFF , 1968px 869px #FFF , 783px 200px #FFF , 1908px 1766px #FFF , 1035px 724px #FFF , 1949px 249px #FFF , 426px 1244px #FFF , 98px 961px #FFF , 1206px 312px #FFF , 1856px 1596px #FFF , 1074px 1563px #FFF , 606px 799px #FFF , 41px 415px #FFF , 1874px 909px #FFF , 718px 1702px #FFF , 1509px 902px #FFF , 1089px 1940px #FFF , 277px 1200px #FFF , 1300px 1531px #FFF , 1159px 1481px #FFF , 1195px 1130px #FFF , 1534px 970px #FFF , 1785px 316px #FFF , 472px 1461px #FFF , 72px 1968px #FFF , 1433px 741px #FFF , 1522px 1385px #FFF , 1921px 1847px #FFF , 175px 330px #FFF , 1499px 299px #FFF , 342px 575px #FFF , 266px 424px #FFF , 808px 585px #FFF , 1574px 1417px #FFF , 80px 1814px #FFF , 441px 545px #FFF , 85px 515px #FFF , 80px 17px #FFF , 1844px 1030px #FFF , 1542px 1957px #FFF , 377px 845px #FFF , 880px 356px #FFF , 971px 89px #FFF , 997px 1360px #FFF , 1665px 1325px #FFF , 189px 1376px #FFF , 1721px 1211px #FFF , 282px 413px #FFF , 1001px 1466px #FFF , 1102px 1769px #FFF , 1981px 1468px #FFF , 1378px 1020px #FFF , 314px 1747px #FFF , 127px 616px #FFF , 454px 1346px #FFF , 1992px 506px #FFF , 1009px 705px #FFF , 751px 1967px #FFF , 1481px 100px #FFF , 35px 1596px #FFF , 354px 1369px #FFF , 168px 1483px #FFF , 819px 247px #FFF , 1557px 473px #FFF , 1695px 17px #FFF , 27px 156px #FFF , 826px 408px #FFF , 920px 682px #FFF , 1113px 686px #FFF , 599px 1941px #FFF , 549px 1517px #FFF , 427px 1711px #FFF , 1427px 675px #FFF , 324px 572px #FFF , 792px 1956px #FFF , 298px 719px #FFF , 542px 812px #FFF , 1152px 1899px #FFF , 1571px 1789px #FFF , 1024px 1767px #FFF , 1344px 1158px #FFF , 101px 1823px #FFF , 1610px 638px #FFF , 1194px 268px #FFF , 1544px 1718px #FFF , 624px 1017px #FFF , 134px 1952px #FFF , 594px 1403px #FFF , 1523px 1393px #FFF , 868px 395px #FFF , 397px 1155px #FFF , 1801px 966px #FFF , 691px 213px #FFF , 1834px 520px #FFF , 1958px 275px #FFF , 49px 1028px #FFF , 1879px 661px #FFF , 798px 1442px #FFF , 115px 1782px #FFF , 1758px 1639px #FFF , 276px 1770px #FFF , 1999px 108px #FFF , 1503px 1137px #FFF , 732px 1798px #FFF , 1990px 564px #FFF , 1329px 744px #FFF , 612px 984px #FFF , 75px 972px #FFF , 518px 1267px #FFF , 268px 1025px #FFF , 1148px 1277px #FFF , 1715px 826px #FFF , 1568px 1779px #FFF , 1786px 1129px #FFF , 933px 1678px #FFF , 1240px 355px #FFF , 1947px 260px #FFF , 643px 1081px #FFF , 944px 1979px #FFF , 1085px 1230px #FFF , 385px 554px #FFF , 74px 1896px #FFF , 948px 1147px #FFF , 939px 1186px #FFF , 1987px 607px #FFF , 1915px 1030px #FFF , 489px 475px #FFF , 740px 552px #FFF , 1246px 480px #FFF , 130px 1830px #FFF , 1259px 1927px #FFF , 352px 601px #FFF , 1874px 1190px #FFF , 383px 1103px #FFF , 431px 652px #FFF , 507px 40px #FFF , 562px 178px #FFF , 1560px 1392px #FFF , 1279px 1734px #FFF , 1791px 1639px #FFF , 1027px 1274px #FFF , 127px 143px #FFF , 936px 515px #FFF , 1226px 1898px #FFF , 709px 1471px #FFF , 1317px 591px #FFF , 304px 424px #FFF , 1133px 524px #FFF , 1229px 860px #FFF , 1694px 1594px #FFF , 1398px 434px #FFF , 25px 904px #FFF , 625px 695px #FFF , 1472px 1280px #FFF , 1102px 78px #FFF;
  animation: animStar 50s linear infinite;
}
#stars:after {
  content: " ";
  position: absolute;
  top: 2000px;
  width: 1px;
  height: 1px;
  background: transparent;
  box-shadow: 1946px 908px #FFF , 1964px 300px #FFF , 951px 1906px #FFF , 540px 1957px #FFF , 695px 1646px #FFF , 1095px 1164px #FFF , 1734px 1337px #FFF , 248px 1590px #FFF , 551px 335px #FFF , 356px 579px #FFF , 125px 465px #FFF , 1121px 1601px #FFF , 783px 1580px #FFF , 1758px 170px #FFF , 713px 1621px #FFF , 8px 1156px #FFF , 637px 1737px #FFF , 447px 1698px #FFF , 37px 574px #FFF , 257px 459px #FFF , 1649px 1990px #FFF , 1201px 1977px #FFF , 84px 1375px #FFF , 1864px 1317px #FFF , 1122px 190px #FFF , 1894px 719px #FFF , 1132px 162px #FFF , 1653px 1356px #FFF , 1366px 590px #FFF , 642px 1989px #FFF , 846px 759px #FFF , 692px 816px #FFF , 613px 1471px #FFF , 439px 330px #FFF , 601px 799px #FFF , 1619px 1275px #FFF , 1328px 84px #FFF , 1548px 919px #FFF , 1318px 646px #FFF , 547px 598px #FFF , 1629px 1706px #FFF , 1188px 720px #FFF , 1071px 201px #FFF , 969px 841px #FFF , 126px 1560px #FFF , 545px 1232px #FFF , 24px 1926px #FFF , 911px 866px #FFF , 1779px 1253px #FFF , 1868px 812px #FFF , 1760px 797px #FFF , 40px 808px #FFF , 1863px 1783px #FFF , 1536px 872px #FFF , 1551px 1537px #FFF , 1550px 904px #FFF , 1627px 1706px #FFF , 933px 334px #FFF , 340px 1547px #FFF , 82px 1151px #FFF , 1484px 1647px #FFF , 502px 1182px #FFF , 489px 1581px #FFF , 814px 1137px #FFF , 741px 1479px #FFF , 375px 282px #FFF , 1982px 966px #FFF , 401px 1271px #FFF , 1770px 752px #FFF , 1653px 800px #FFF , 390px 1367px #FFF , 1685px 1930px #FFF , 1717px 1879px #FFF , 1528px 487px #FFF , 334px 1101px #FFF , 24px 229px #FFF , 447px 1692px #FFF , 1511px 656px #FFF , 480px 1209px #FFF , 92px 603px #FFF , 39px 1131px #FFF , 1172px 1040px #FFF , 974px 1602px #FFF , 555px 1864px #FFF , 1877px 311px #FFF , 1536px 1721px #FFF , 801px 1474px #FFF , 1125px 992px #FFF , 1725px 765px #FFF , 260px 776px #FFF , 639px 904px #FFF , 341px 541px #FFF , 621px 673px #FFF , 1612px 536px #FFF , 1055px 938px #FFF , 1129px 1494px #FFF , 36px 814px #FFF , 1295px 854px #FFF , 746px 1055px #FFF , 1990px 82px #FFF , 232px 299px #FFF , 665px 684px #FFF , 1489px 1340px #FFF , 733px 34px #FFF , 279px 818px #FFF , 1168px 1671px #FFF , 1771px 622px #FFF , 79px 1133px #FFF , 1966px 31px #FFF , 863px 1026px #FFF , 1000px 1792px #FFF , 875px 322px #FFF , 29px 1974px #FFF , 980px 1407px #FFF , 1039px 1150px #FFF , 1606px 203px #FFF , 933px 920px #FFF , 633px 1154px #FFF , 882px 1372px #FFF , 1416px 211px #FFF , 1549px 1913px #FFF , 1220px 1433px #FFF , 921px 1679px #FFF , 1400px 1518px #FFF , 1028px 829px #FFF , 10px 1301px #FFF , 1282px 1005px #FFF , 633px 311px #FFF , 1074px 1545px #FFF , 315px 1808px #FFF , 1755px 1328px #FFF , 1268px 37px #FFF , 1495px 1108px #FFF , 1526px 658px #FFF , 993px 1368px #FFF , 1817px 571px #FFF , 1848px 876px #FFF , 233px 977px #FFF , 373px 939px #FFF , 1451px 1273px #FFF , 1855px 205px #FFF , 87px 1814px #FFF , 1184px 723px #FFF , 128px 330px #FFF , 822px 252px #FFF , 1588px 1278px #FFF , 411px 1537px #FFF , 1047px 513px #FFF , 1920px 339px #FFF , 54px 1458px #FFF , 284px 1415px #FFF , 38px 707px #FFF , 613px 1688px #FFF , 321px 912px #FFF , 561px 807px #FFF , 172px 54px #FFF , 1747px 1080px #FFF , 216px 1316px #FFF , 349px 1979px #FFF , 366px 277px #FFF , 1860px 1085px #FFF , 1135px 1527px #FFF , 1826px 610px #FFF , 1876px 67px #FFF , 272px 1456px #FFF , 421px 824px #FFF , 1733px 248px #FFF , 1699px 1745px #FFF , 1004px 946px #FFF , 773px 1309px #FFF , 81px 767px #FFF , 905px 1498px #FFF , 426px 967px #FFF , 989px 99px #FFF , 327px 1135px #FFF , 1695px 216px #FFF , 951px 1899px #FFF , 303px 1719px #FFF , 1297px 44px #FFF , 15px 1163px #FFF , 785px 772px #FFF , 752px 1846px #FFF , 1385px 1352px #FFF , 1853px 419px #FFF , 1333px 1667px #FFF , 251px 709px #FFF , 268px 1520px #FFF , 806px 119px #FFF , 1196px 24px #FFF , 92px 987px #FFF , 1077px 111px #FFF , 580px 365px #FFF , 423px 249px #FFF , 48px 746px #FFF , 1580px 1887px #FFF , 354px 1212px #FFF , 1716px 1606px #FFF , 699px 453px #FFF , 420px 123px #FFF , 852px 1550px #FFF , 1155px 1415px #FFF , 1803px 1983px #FFF , 1042px 987px #FFF , 1597px 1619px #FFF , 1734px 1317px #FFF , 607px 294px #FFF , 1635px 452px #FFF , 1688px 1854px #FFF , 809px 519px #FFF , 94px 884px #FFF , 1572px 1943px #FFF , 653px 1511px #FFF , 1470px 1358px #FFF , 605px 298px #FFF , 1528px 854px #FFF , 1433px 206px #FFF , 856px 223px #FFF , 1798px 1843px #FFF , 68px 498px #FFF , 1172px 264px #FFF , 289px 812px #FFF , 1485px 798px #FFF , 393px 1725px #FFF , 1602px 1846px #FFF , 1154px 882px #FFF , 1328px 570px #FFF , 358px 1933px #FFF , 984px 806px #FFF , 1828px 500px #FFF , 128px 767px #FFF , 1411px 1985px #FFF , 1529px 1202px #FFF , 1726px 518px #FFF , 1803px 860px #FFF , 496px 778px #FFF , 1379px 518px #FFF , 1982px 603px #FFF , 1355px 528px #FFF , 1139px 732px #FFF , 310px 143px #FFF , 739px 1056px #FFF , 178px 230px #FFF , 967px 1959px #FFF , 1267px 1697px #FFF , 1089px 586px #FFF , 1975px 1896px #FFF , 1837px 246px #FFF , 241px 442px #FFF , 401px 397px #FFF , 1240px 69px #FFF , 1378px 851px #FFF , 789px 460px #FFF , 1646px 1853px #FFF , 1663px 307px #FFF , 763px 1445px #FFF , 1402px 1552px #FFF , 1862px 1868px #FFF , 1624px 1785px #FFF , 66px 1978px #FFF , 639px 1251px #FFF , 358px 780px #FFF , 1770px 932px #FFF , 1263px 1718px #FFF , 1294px 1184px #FFF , 1595px 631px #FFF , 832px 1738px #FFF , 1755px 319px #FFF , 1083px 1707px #FFF , 1947px 760px #FFF , 711px 1764px #FFF , 1021px 1658px #FFF , 292px 1730px #FFF , 423px 157px #FFF , 525px 1981px #FFF , 604px 1590px #FFF , 437px 1673px #FFF , 1106px 1642px #FFF , 1434px 389px #FFF , 172px 780px #FFF , 1438px 1461px #FFF , 1438px 734px #FFF , 875px 1650px #FFF , 403px 774px #FFF , 1051px 351px #FFF , 297px 1048px #FFF , 576px 1604px #FFF , 1384px 1191px #FFF , 1309px 1083px #FFF , 1505px 1624px #FFF , 1617px 972px #FFF , 760px 133px #FFF , 667px 759px #FFF , 450px 1965px #FFF , 359px 1220px #FFF , 1065px 295px #FFF , 1365px 1608px #FFF , 533px 240px #FFF , 1696px 653px #FFF , 1630px 1748px #FFF , 864px 1010px #FFF , 615px 1098px #FFF , 792px 775px #FFF , 1491px 458px #FFF , 1989px 969px #FFF , 1487px 1938px #FFF , 1566px 1435px #FFF , 1884px 1144px #FFF , 1666px 1024px #FFF , 1239px 1600px #FFF , 1016px 1057px #FFF , 1381px 1482px #FFF , 1408px 1865px #FFF , 1361px 1515px #FFF , 330px 136px #FFF , 775px 985px #FFF , 1406px 1074px #FFF , 612px 769px #FFF , 1569px 262px #FFF , 1411px 139px #FFF , 1784px 1019px #FFF , 780px 1370px #FFF , 174px 1741px #FFF , 1154px 161px #FFF , 1237px 1435px #FFF , 975px 346px #FFF , 1px 775px #FFF , 692px 536px #FFF , 1322px 20px #FFF , 1427px 979px #FFF , 329px 568px #FFF , 75px 627px #FFF , 1733px 1665px #FFF , 976px 1163px #FFF , 1653px 123px #FFF , 799px 1241px #FFF , 574px 628px #FFF , 615px 31px #FFF , 1519px 695px #FFF , 1575px 634px #FFF , 17px 240px #FFF , 807px 843px #FFF , 487px 574px #FFF , 447px 1134px #FFF , 819px 1487px #FFF , 781px 1877px #FFF , 449px 789px #FFF , 956px 1124px #FFF , 48px 1071px #FFF , 340px 1196px #FFF , 1782px 517px #FFF , 1097px 1871px #FFF , 1987px 962px #FFF , 1847px 1109px #FFF , 1960px 752px #FFF , 1114px 577px #FFF , 1122px 572px #FFF , 1112px 1849px #FFF , 629px 1235px #FFF , 865px 1004px #FFF , 1730px 53px #FFF , 629px 1540px #FFF , 1192px 526px #FFF , 104px 1078px #FFF , 1102px 1207px #FFF , 313px 1198px #FFF , 703px 1083px #FFF , 812px 1403px #FFF , 128px 1292px #FFF , 1676px 1653px #FFF , 1143px 1291px #FFF , 52px 95px #FFF , 1893px 337px #FFF , 597px 332px #FFF , 1451px 951px #FFF , 53px 777px #FFF , 828px 1903px #FFF , 478px 653px #FFF , 819px 1286px #FFF , 898px 1758px #FFF , 82px 503px #FFF , 188px 1697px #FFF , 1209px 549px #FFF , 1244px 1537px #FFF , 489px 1376px #FFF , 16px 1857px #FFF , 1564px 1246px #FFF , 910px 442px #FFF , 362px 1444px #FFF , 710px 1907px #FFF , 341px 95px #FFF , 1385px 1543px #FFF , 1581px 546px #FFF , 1335px 1927px #FFF , 1619px 1693px #FFF , 185px 559px #FFF , 101px 1683px #FFF , 963px 284px #FFF , 1507px 466px #FFF , 834px 1912px #FFF , 1367px 1649px #FFF , 329px 960px #FFF , 3px 1307px #FFF , 1351px 855px #FFF , 248px 1912px #FFF , 417px 481px #FFF , 1728px 1167px #FFF , 1247px 1408px #FFF , 362px 835px #FFF , 1433px 582px #FFF , 267px 742px #FFF , 1292px 321px #FFF , 318px 1268px #FFF , 1153px 535px #FFF , 1631px 388px #FFF , 1622px 1634px #FFF , 1087px 1375px #FFF , 230px 316px #FFF , 1513px 1451px #FFF , 217px 98px #FFF , 824px 1955px #FFF , 1398px 829px #FFF , 1019px 1396px #FFF , 1490px 354px #FFF , 129px 792px #FFF , 362px 1228px #FFF , 663px 1735px #FFF , 402px 1690px #FFF , 862px 1645px #FFF , 892px 677px #FFF , 540px 1905px #FFF , 246px 1818px #FFF , 1580px 1419px #FFF , 427px 1655px #FFF , 1411px 514px #FFF , 988px 630px #FFF , 399px 886px #FFF , 190px 184px #FFF , 599px 1866px #FFF , 77px 681px #FFF , 31px 636px #FFF , 1547px 689px #FFF , 1161px 269px #FFF , 904px 658px #FFF , 1167px 1130px #FFF , 499px 73px #FFF , 1631px 1762px #FFF , 1628px 1727px #FFF , 812px 1507px #FFF , 1916px 1744px #FFF , 136px 481px #FFF , 1966px 1233px #FFF , 1906px 1053px #FFF , 449px 1307px #FFF , 1897px 717px #FFF , 1359px 936px #FFF , 1825px 1448px #FFF , 405px 1004px #FFF , 875px 210px #FFF , 182px 1398px #FFF , 1px 1276px #FFF , 290px 1917px #FFF , 1182px 169px #FFF , 86px 1884px #FFF , 707px 659px #FFF , 1461px 658px #FFF , 1459px 1504px #FFF , 697px 67px #FFF , 584px 929px #FFF , 1670px 457px #FFF , 1487px 786px #FFF , 1609px 773px #FFF , 1196px 264px #FFF , 1787px 492px #FFF , 1139px 800px #FFF , 871px 246px #FFF , 310px 1752px #FFF , 1572px 516px #FFF , 1326px 456px #FFF , 1336px 1374px #FFF , 1036px 52px #FFF , 1448px 580px #FFF , 1642px 1470px #FFF , 460px 332px #FFF , 1376px 295px #FFF , 1598px 330px #FFF , 1604px 16px #FFF , 1339px 385px #FFF , 269px 842px #FFF , 555px 33px #FFF , 304px 9px #FFF , 1803px 471px #FFF , 956px 1456px #FFF , 1999px 792px #FFF , 1900px 590px #FFF , 865px 1011px #FFF , 296px 807px #FFF , 674px 1129px #FFF , 1204px 1824px #FFF , 1981px 1164px #FFF , 1313px 1128px #FFF , 914px 778px #FFF , 1584px 751px #FFF , 1141px 1501px #FFF , 1691px 519px #FFF , 1166px 179px #FFF , 1405px 1470px #FFF , 1087px 275px #FFF , 1293px 1295px #FFF , 684px 772px #FFF , 512px 41px #FFF , 1332px 175px #FFF , 623px 1047px #FFF , 468px 1765px #FFF , 1591px 1839px #FFF , 632px 1910px #FFF , 767px 348px #FFF , 179px 1367px #FFF , 149px 337px #FFF , 24px 92px #FFF , 891px 984px #FFF , 337px 1247px #FFF , 795px 10px #FFF , 1070px 1548px #FFF , 1621px 1828px #FFF , 965px 1359px #FFF , 386px 145px #FFF , 1925px 852px #FFF , 85px 1280px #FFF , 429px 1850px #FFF , 627px 1973px #FFF , 831px 1918px #FFF , 154px 1001px #FFF , 42px 803px #FFF , 1806px 1695px #FFF , 1672px 1251px #FFF , 1008px 164px #FFF , 1677px 606px #FFF , 319px 367px #FFF , 1409px 171px #FFF , 1608px 1465px #FFF , 1611px 122px #FFF , 1166px 361px #FFF , 752px 72px #FFF , 10px 1356px #FFF , 885px 787px #FFF , 768px 1074px #FFF , 1968px 869px #FFF , 783px 200px #FFF , 1908px 1766px #FFF , 1035px 724px #FFF , 1949px 249px #FFF , 426px 1244px #FFF , 98px 961px #FFF , 1206px 312px #FFF , 1856px 1596px #FFF , 1074px 1563px #FFF , 606px 799px #FFF , 41px 415px #FFF , 1874px 909px #FFF , 718px 1702px #FFF , 1509px 902px #FFF , 1089px 1940px #FFF , 277px 1200px #FFF , 1300px 1531px #FFF , 1159px 1481px #FFF , 1195px 1130px #FFF , 1534px 970px #FFF , 1785px 316px #FFF , 472px 1461px #FFF , 72px 1968px #FFF , 1433px 741px #FFF , 1522px 1385px #FFF , 1921px 1847px #FFF , 175px 330px #FFF , 1499px 299px #FFF , 342px 575px #FFF , 266px 424px #FFF , 808px 585px #FFF , 1574px 1417px #FFF , 80px 1814px #FFF , 441px 545px #FFF , 85px 515px #FFF , 80px 17px #FFF , 1844px 1030px #FFF , 1542px 1957px #FFF , 377px 845px #FFF , 880px 356px #FFF , 971px 89px #FFF , 997px 1360px #FFF , 1665px 1325px #FFF , 189px 1376px #FFF , 1721px 1211px #FFF , 282px 413px #FFF , 1001px 1466px #FFF , 1102px 1769px #FFF , 1981px 1468px #FFF , 1378px 1020px #FFF , 314px 1747px #FFF , 127px 616px #FFF , 454px 1346px #FFF , 1992px 506px #FFF , 1009px 705px #FFF , 751px 1967px #FFF , 1481px 100px #FFF , 35px 1596px #FFF , 354px 1369px #FFF , 168px 1483px #FFF , 819px 247px #FFF , 1557px 473px #FFF , 1695px 17px #FFF , 27px 156px #FFF , 826px 408px #FFF , 920px 682px #FFF , 1113px 686px #FFF , 599px 1941px #FFF , 549px 1517px #FFF , 427px 1711px #FFF , 1427px 675px #FFF , 324px 572px #FFF , 792px 1956px #FFF , 298px 719px #FFF , 542px 812px #FFF , 1152px 1899px #FFF , 1571px 1789px #FFF , 1024px 1767px #FFF , 1344px 1158px #FFF , 101px 1823px #FFF , 1610px 638px #FFF , 1194px 268px #FFF , 1544px 1718px #FFF , 624px 1017px #FFF , 134px 1952px #FFF , 594px 1403px #FFF , 1523px 1393px #FFF , 868px 395px #FFF , 397px 1155px #FFF , 1801px 966px #FFF , 691px 213px #FFF , 1834px 520px #FFF , 1958px 275px #FFF , 49px 1028px #FFF , 1879px 661px #FFF , 798px 1442px #FFF , 115px 1782px #FFF , 1758px 1639px #FFF , 276px 1770px #FFF , 1999px 108px #FFF , 1503px 1137px #FFF , 732px 1798px #FFF , 1990px 564px #FFF , 1329px 744px #FFF , 612px 984px #FFF , 75px 972px #FFF , 518px 1267px #FFF , 268px 1025px #FFF , 1148px 1277px #FFF , 1715px 826px #FFF , 1568px 1779px #FFF , 1786px 1129px #FFF , 933px 1678px #FFF , 1240px 355px #FFF , 1947px 260px #FFF , 643px 1081px #FFF , 944px 1979px #FFF , 1085px 1230px #FFF , 385px 554px #FFF , 74px 1896px #FFF , 948px 1147px #FFF , 939px 1186px #FFF , 1987px 607px #FFF , 1915px 1030px #FFF , 489px 475px #FFF , 740px 552px #FFF , 1246px 480px #FFF , 130px 1830px #FFF , 1259px 1927px #FFF , 352px 601px #FFF , 1874px 1190px #FFF , 383px 1103px #FFF , 431px 652px #FFF , 507px 40px #FFF , 562px 178px #FFF , 1560px 1392px #FFF , 1279px 1734px #FFF , 1791px 1639px #FFF , 1027px 1274px #FFF , 127px 143px #FFF , 936px 515px #FFF , 1226px 1898px #FFF , 709px 1471px #FFF , 1317px 591px #FFF , 304px 424px #FFF , 1133px 524px #FFF , 1229px 860px #FFF , 1694px 1594px #FFF , 1398px 434px #FFF , 25px 904px #FFF , 625px 695px #FFF , 1472px 1280px #FFF , 1102px 78px #FFF;
}
#stars2 {
  width: 2px;
  height: 2px;
  background: transparent;
  box-shadow: 104px 1451px #FFF , 642px 1288px #FFF , 1003px 1952px #FFF , 1638px 1347px #FFF , 1477px 1767px #FFF , 1425px 99px #FFF , 1279px 46px #FFF , 1182px 413px #FFF , 568px 609px #FFF , 480px 1236px #FFF , 579px 329px #FFF , 341px 1380px #FFF , 312px 675px #FFF , 1356px 1955px #FFF , 1287px 1966px #FFF , 339px 1548px #FFF , 1571px 1118px #FFF , 109px 311px #FFF , 560px 47px #FFF , 725px 459px #FFF , 105px 1040px #FFF , 445px 1301px #FFF , 607px 322px #FFF , 1969px 686px #FFF , 750px 1627px #FFF , 1436px 1628px #FFF , 1517px 1508px #FFF , 1437px 1775px #FFF , 549px 306px #FFF , 224px 948px #FFF , 1260px 1338px #FFF , 1321px 1195px #FFF , 652px 64px #FFF , 1214px 34px #FFF , 1311px 59px #FFF , 1540px 249px #FFF , 309px 705px #FFF , 377px 276px #FFF , 931px 412px #FFF , 250px 800px #FFF , 70px 1113px #FFF , 889px 1851px #FFF , 702px 318px #FFF , 994px 378px #FFF , 940px 1420px #FFF , 380px 777px #FFF , 262px 912px #FFF , 1503px 1515px #FFF , 379px 1255px #FFF , 8px 199px #FFF , 729px 1142px #FFF , 1956px 804px #FFF , 638px 1426px #FFF , 104px 1254px #FFF , 1121px 936px #FFF , 1264px 1121px #FFF , 421px 176px #FFF , 1178px 1844px #FFF , 439px 1489px #FFF , 636px 1507px #FFF , 112px 911px #FFF , 742px 692px #FFF , 87px 718px #FFF , 298px 1215px #FFF , 1990px 1296px #FFF , 538px 620px #FFF , 1069px 1790px #FFF , 735px 1815px #FFF , 1425px 741px #FFF , 1695px 271px #FFF , 815px 1450px #FFF , 1725px 374px #FFF , 151px 473px #FFF , 1067px 1655px #FFF , 1453px 1896px #FFF , 377px 892px #FFF , 763px 957px #FFF , 824px 654px #FFF , 1005px 527px #FFF , 1507px 711px #FFF , 1159px 652px #FFF , 400px 1937px #FFF , 800px 1016px #FFF , 839px 1191px #FFF , 858px 741px #FFF , 370px 759px #FFF , 1341px 1186px #FFF , 908px 1564px #FFF , 1782px 1031px #FFF , 198px 1982px #FFF , 1310px 1998px #FFF , 564px 1258px #FFF , 714px 273px #FFF , 77px 791px #FFF , 235px 1833px #FFF , 241px 1786px #FFF , 1207px 1703px #FFF , 773px 1034px #FFF , 1902px 1369px #FFF , 1691px 1569px #FFF , 1023px 1489px #FFF , 436px 819px #FFF , 1595px 613px #FFF , 1387px 699px #FFF , 374px 1457px #FFF , 1123px 1491px #FFF , 1199px 538px #FFF , 1121px 1716px #FFF , 1731px 958px #FFF , 1165px 1642px #FFF , 1537px 1571px #FFF , 1618px 1200px #FFF , 1764px 1707px #FFF , 71px 1227px #FFF , 663px 1769px #FFF , 1421px 1558px #FFF , 956px 209px #FFF , 1718px 951px #FFF , 288px 972px #FFF , 1341px 115px #FFF , 176px 1664px #FFF , 972px 970px #FFF , 534px 1345px #FFF , 1748px 1372px #FFF , 763px 1355px #FFF , 947px 1725px #FFF , 1210px 874px #FFF , 1400px 950px #FFF , 935px 1564px #FFF , 1486px 436px #FFF , 1921px 1623px #FFF , 1170px 799px #FFF , 350px 883px #FFF , 221px 994px #FFF , 1819px 498px #FFF , 740px 907px #FFF , 794px 695px #FFF , 1954px 912px #FFF , 697px 281px #FFF , 1253px 1558px #FFF , 23px 1455px #FFF , 1127px 390px #FFF , 260px 569px #FFF , 1263px 981px #FFF , 229px 1375px #FFF , 982px 731px #FFF , 171px 1622px #FFF , 1346px 3px #FFF , 691px 951px #FFF , 1341px 655px #FFF , 970px 373px #FFF , 279px 240px #FFF , 832px 323px #FFF , 1911px 609px #FFF , 1482px 752px #FFF , 1203px 12px #FFF , 1678px 868px #FFF , 1667px 1258px #FFF , 529px 1889px #FFF , 1809px 187px #FFF , 482px 1628px #FFF , 74px 1985px #FFF , 647px 448px #FFF , 58px 1870px #FFF , 167px 616px #FFF , 1002px 1413px #FFF , 1692px 612px #FFF , 547px 1602px #FFF , 1265px 805px #FFF , 1521px 1533px #FFF , 315px 596px #FFF , 1127px 216px #FFF , 1285px 354px #FFF , 1196px 272px #FFF , 658px 985px #FFF , 1504px 777px #FFF , 1247px 1120px #FFF , 1592px 1961px #FFF , 1826px 1626px #FFF , 1917px 1852px #FFF , 295px 886px #FFF , 1830px 534px #FFF , 1975px 1999px #FFF , 510px 622px #FFF , 932px 1754px #FFF , 1361px 524px #FFF , 1932px 1155px #FFF , 1180px 1506px #FFF , 1806px 635px #FFF , 497px 904px #FFF , 1590px 928px #FFF , 608px 8px #FFF , 1877px 1756px #FFF , 1026px 1905px #FFF , 1631px 928px #FFF , 394px 621px #FFF , 433px 1439px #FFF , 1409px 32px #FFF , 1576px 888px #FFF , 69px 1567px #FFF;
  animation: animStar 100s linear infinite;
}
#stars2:after {
  content: " ";
  position: absolute;
  top: 2000px;
  width: 2px;
  height: 2px;
  background: transparent;
  box-shadow: 104px 1451px #FFF , 642px 1288px #FFF , 1003px 1952px #FFF , 1638px 1347px #FFF , 1477px 1767px #FFF , 1425px 99px #FFF , 1279px 46px #FFF , 1182px 413px #FFF , 568px 609px #FFF , 480px 1236px #FFF , 579px 329px #FFF , 341px 1380px #FFF , 312px 675px #FFF , 1356px 1955px #FFF , 1287px 1966px #FFF , 339px 1548px #FFF , 1571px 1118px #FFF , 109px 311px #FFF , 560px 47px #FFF , 725px 459px #FFF , 105px 1040px #FFF , 445px 1301px #FFF , 607px 322px #FFF , 1969px 686px #FFF , 750px 1627px #FFF , 1436px 1628px #FFF , 1517px 1508px #FFF , 1437px 1775px #FFF , 549px 306px #FFF , 224px 948px #FFF , 1260px 1338px #FFF , 1321px 1195px #FFF , 652px 64px #FFF , 1214px 34px #FFF , 1311px 59px #FFF , 1540px 249px #FFF , 309px 705px #FFF , 377px 276px #FFF , 931px 412px #FFF , 250px 800px #FFF , 70px 1113px #FFF , 889px 1851px #FFF , 702px 318px #FFF , 994px 378px #FFF , 940px 1420px #FFF , 380px 777px #FFF , 262px 912px #FFF , 1503px 1515px #FFF , 379px 1255px #FFF , 8px 199px #FFF , 729px 1142px #FFF , 1956px 804px #FFF , 638px 1426px #FFF , 104px 1254px #FFF , 1121px 936px #FFF , 1264px 1121px #FFF , 421px 176px #FFF , 1178px 1844px #FFF , 439px 1489px #FFF , 636px 1507px #FFF , 112px 911px #FFF , 742px 692px #FFF , 87px 718px #FFF , 298px 1215px #FFF , 1990px 1296px #FFF , 538px 620px #FFF , 1069px 1790px #FFF , 735px 1815px #FFF , 1425px 741px #FFF , 1695px 271px #FFF , 815px 1450px #FFF , 1725px 374px #FFF , 151px 473px #FFF , 1067px 1655px #FFF , 1453px 1896px #FFF , 377px 892px #FFF , 763px 957px #FFF , 824px 654px #FFF , 1005px 527px #FFF , 1507px 711px #FFF , 1159px 652px #FFF , 400px 1937px #FFF , 800px 1016px #FFF , 839px 1191px #FFF , 858px 741px #FFF , 370px 759px #FFF , 1341px 1186px #FFF , 908px 1564px #FFF , 1782px 1031px #FFF , 198px 1982px #FFF , 1310px 1998px #FFF , 564px 1258px #FFF , 714px 273px #FFF , 77px 791px #FFF , 235px 1833px #FFF , 241px 1786px #FFF , 1207px 1703px #FFF , 773px 1034px #FFF , 1902px 1369px #FFF , 1691px 1569px #FFF , 1023px 1489px #FFF , 436px 819px #FFF , 1595px 613px #FFF , 1387px 699px #FFF , 374px 1457px #FFF , 1123px 1491px #FFF , 1199px 538px #FFF , 1121px 1716px #FFF , 1731px 958px #FFF , 1165px 1642px #FFF , 1537px 1571px #FFF , 1618px 1200px #FFF , 1764px 1707px #FFF , 71px 1227px #FFF , 663px 1769px #FFF , 1421px 1558px #FFF , 956px 209px #FFF , 1718px 951px #FFF , 288px 972px #FFF , 1341px 115px #FFF , 176px 1664px #FFF , 972px 970px #FFF , 534px 1345px #FFF , 1748px 1372px #FFF , 763px 1355px #FFF , 947px 1725px #FFF , 1210px 874px #FFF , 1400px 950px #FFF , 935px 1564px #FFF , 1486px 436px #FFF , 1921px 1623px #FFF , 1170px 799px #FFF , 350px 883px #FFF , 221px 994px #FFF , 1819px 498px #FFF , 740px 907px #FFF , 794px 695px #FFF , 1954px 912px #FFF , 697px 281px #FFF , 1253px 1558px #FFF , 23px 1455px #FFF , 1127px 390px #FFF , 260px 569px #FFF , 1263px 981px #FFF , 229px 1375px #FFF , 982px 731px #FFF , 171px 1622px #FFF , 1346px 3px #FFF , 691px 951px #FFF , 1341px 655px #FFF , 970px 373px #FFF , 279px 240px #FFF , 832px 323px #FFF , 1911px 609px #FFF , 1482px 752px #FFF , 1203px 12px #FFF , 1678px 868px #FFF , 1667px 1258px #FFF , 529px 1889px #FFF , 1809px 187px #FFF , 482px 1628px #FFF , 74px 1985px #FFF , 647px 448px #FFF , 58px 1870px #FFF , 167px 616px #FFF , 1002px 1413px #FFF , 1692px 612px #FFF , 547px 1602px #FFF , 1265px 805px #FFF , 1521px 1533px #FFF , 315px 596px #FFF , 1127px 216px #FFF , 1285px 354px #FFF , 1196px 272px #FFF , 658px 985px #FFF , 1504px 777px #FFF , 1247px 1120px #FFF , 1592px 1961px #FFF , 1826px 1626px #FFF , 1917px 1852px #FFF , 295px 886px #FFF , 1830px 534px #FFF , 1975px 1999px #FFF , 510px 622px #FFF , 932px 1754px #FFF , 1361px 524px #FFF , 1932px 1155px #FFF , 1180px 1506px #FFF , 1806px 635px #FFF , 497px 904px #FFF , 1590px 928px #FFF , 608px 8px #FFF , 1877px 1756px #FFF , 1026px 1905px #FFF , 1631px 928px #FFF , 394px 621px #FFF , 433px 1439px #FFF , 1409px 32px #FFF , 1576px 888px #FFF , 69px 1567px #FFF;
}
#stars3 {
  width: 3px;
  height: 3px;
  background: transparent;
  box-shadow: 1540px 1649px #FFF , 1607px 1982px #FFF , 1741px 372px #FFF , 1835px 499px #FFF , 1195px 1790px #FFF , 692px 1420px #FFF , 217px 1039px #FFF , 492px 1784px #FFF , 432px 285px #FFF , 1492px 25px #FFF , 522px 1844px #FFF , 1728px 1571px #FFF , 852px 1050px #FFF , 1534px 1068px #FFF , 12px 469px #FFF , 619px 1771px #FFF , 1825px 1631px #FFF , 1739px 705px #FFF , 1730px 101px #FFF , 662px 1555px #FFF , 574px 677px #FFF , 80px 1676px #FFF , 1701px 302px #FFF , 1542px 1827px #FFF , 1098px 1030px #FFF , 460px 1864px #FFF , 1535px 544px #FFF , 1933px 289px #FFF , 514px 573px #FFF , 675px 878px #FFF , 705px 1336px #FFF , 264px 1802px #FFF , 350px 673px #FFF , 950px 277px #FFF , 1621px 1013px #FFF , 460px 352px #FFF , 1507px 1878px #FFF , 1470px 1377px #FFF , 617px 198px #FFF , 1918px 163px #FFF , 1157px 955px #FFF , 1034px 1983px #FFF , 1979px 15px #FFF , 1689px 1312px #FFF , 1390px 1733px #FFF , 314px 236px #FFF , 1357px 1056px #FFF , 770px 1890px #FFF , 1693px 839px #FFF , 1006px 1871px #FFF , 1287px 414px #FFF , 1874px 1088px #FFF , 620px 1525px #FFF , 1875px 1687px #FFF , 1094px 1358px #FFF , 713px 641px #FFF , 157px 1856px #FFF , 111px 1205px #FFF , 1628px 1062px #FFF , 1245px 101px #FFF , 1992px 38px #FFF , 183px 902px #FFF , 1930px 1930px #FFF , 643px 747px #FFF , 1135px 1310px #FFF , 1363px 668px #FFF , 403px 1177px #FFF , 1693px 876px #FFF , 262px 33px #FFF , 1567px 585px #FFF , 1600px 1886px #FFF , 1261px 257px #FFF , 1787px 1818px #FFF , 1970px 1572px #FFF , 1482px 1354px #FFF , 1203px 1000px #FFF , 183px 714px #FFF , 1851px 1770px #FFF , 173px 1702px #FFF , 780px 42px #FFF , 347px 192px #FFF , 647px 1752px #FFF , 1985px 1507px #FFF , 403px 1368px #FFF , 1561px 478px #FFF , 1521px 1549px #FFF , 1936px 1271px #FFF , 813px 218px #FFF , 1316px 1566px #FFF , 1800px 579px #FFF , 24px 1528px #FFF , 1148px 961px #FFF , 1146px 867px #FFF , 1539px 954px #FFF , 603px 964px #FFF , 1594px 1040px #FFF , 266px 1587px #FFF , 1629px 1704px #FFF , 583px 1643px #FFF , 1408px 961px #FFF;
  animation: animStar 150s linear infinite;
}
#stars3:after {
  content: " ";
  position: absolute;
  top: 2000px;
  width: 3px;
  height: 3px;
  background: transparent;
  box-shadow: 1540px 1649px #FFF , 1607px 1982px #FFF , 1741px 372px #FFF , 1835px 499px #FFF , 1195px 1790px #FFF , 692px 1420px #FFF , 217px 1039px #FFF , 492px 1784px #FFF , 432px 285px #FFF , 1492px 25px #FFF , 522px 1844px #FFF , 1728px 1571px #FFF , 852px 1050px #FFF , 1534px 1068px #FFF , 12px 469px #FFF , 619px 1771px #FFF , 1825px 1631px #FFF , 1739px 705px #FFF , 1730px 101px #FFF , 662px 1555px #FFF , 574px 677px #FFF , 80px 1676px #FFF , 1701px 302px #FFF , 1542px 1827px #FFF , 1098px 1030px #FFF , 460px 1864px #FFF , 1535px 544px #FFF , 1933px 289px #FFF , 514px 573px #FFF , 675px 878px #FFF , 705px 1336px #FFF , 264px 1802px #FFF , 350px 673px #FFF , 950px 277px #FFF , 1621px 1013px #FFF , 460px 352px #FFF , 1507px 1878px #FFF , 1470px 1377px #FFF , 617px 198px #FFF , 1918px 163px #FFF , 1157px 955px #FFF , 1034px 1983px #FFF , 1979px 15px #FFF , 1689px 1312px #FFF , 1390px 1733px #FFF , 314px 236px #FFF , 1357px 1056px #FFF , 770px 1890px #FFF , 1693px 839px #FFF , 1006px 1871px #FFF , 1287px 414px #FFF , 1874px 1088px #FFF , 620px 1525px #FFF , 1875px 1687px #FFF , 1094px 1358px #FFF , 713px 641px #FFF , 157px 1856px #FFF , 111px 1205px #FFF , 1628px 1062px #FFF , 1245px 101px #FFF , 1992px 38px #FFF , 183px 902px #FFF , 1930px 1930px #FFF , 643px 747px #FFF , 1135px 1310px #FFF , 1363px 668px #FFF , 403px 1177px #FFF , 1693px 876px #FFF , 262px 33px #FFF , 1567px 585px #FFF , 1600px 1886px #FFF , 1261px 257px #FFF , 1787px 1818px #FFF , 1970px 1572px #FFF , 1482px 1354px #FFF , 1203px 1000px #FFF , 183px 714px #FFF , 1851px 1770px #FFF , 173px 1702px #FFF , 780px 42px #FFF , 347px 192px #FFF , 647px 1752px #FFF , 1985px 1507px #FFF , 403px 1368px #FFF , 1561px 478px #FFF , 1521px 1549px #FFF , 1936px 1271px #FFF , 813px 218px #FFF , 1316px 1566px #FFF , 1800px 579px #FFF , 24px 1528px #FFF , 1148px 961px #FFF , 1146px 867px #FFF , 1539px 954px #FFF , 603px 964px #FFF , 1594px 1040px #FFF , 266px 1587px #FFF , 1629px 1704px #FFF , 583px 1643px #FFF , 1408px 961px #FFF;
}
@keyframes animStar {
  from {
    transform: translateY(0px);
  }
  to {
    transform: translateY(-2000px);
  }
}
.glasscontainer{
  display: inline-flex;
  flex-flow: wrap;
  justify-content: center;
  align-items: center;
  z-index: 1;
}
.glasscontainer .card{
  position: relative;
  width: 300px;
  height: 400px;
  margin: 20px;
  box-shadow: 20px 20px 50px rgb(0, 0, 0, 0.5);
  border-radius: 5px;
  background: rgb(255, 255, 255, 0.1);
  overflow: hidden;
  border-top: 1px solid rgba(255, 255, 255, 0.5);
  border-left: 1px solid rgba(255, 255, 255, 0.5);
  backdrop-filter: blur(5px);
}
.glasscontainer .card .content{
  padding: 10px;
  transform: translateY(50px);
  opacity: 85%;
  transition: 0.5s;
  text-align: center;
}
.glasscontainer .card:hover .content{
  transform: translateY(0px);
  opacity: 100%;
}
.glasscontainer .card .content h2{
  position: relative;
  left: 80px;
  font-size: 4em;
  color: rgba(255, 255, 255, 1.9);
  pointer-events: none;
}
.glasscontainer .card .content p{
  text-align: center;
  font-size: 0.9em;
  color: white;
  font-weight: 400;
  opacity: 100%;
}
.glasscontainer .card .content li{
  color:white;
  text-align: left;
}
.myglasstable{
  background: radial-gradient(#1b2735 0%, #090a0f 100%);
  border-radius: 20px;
}
.piccontainer{
  display: inline-flex;
  flex-flow: wrap;
  justify-content: center;
  align-items: center;
  z-index: -1;
}
.piccontainer .piccard{
  position: relative;
  width: 100;
  height: 100;
  margin: 20px;
  box-shadow: 20px 20px 50px rgb(0, 0, 0, 0.5);
  border-radius: 5px;
  background: rgb(255, 255, 255, 0.1);
  overflow: hidden;
  border-top: 1px solid rgba(255, 255, 255, 0.5);
  border-left: 1px solid rgba(255, 255, 255, 0.5);
  backdrop-filter: blur(5px);
}
.piccontainer .piccard .content{
  padding: 10px;
  transform: translateY(50px);
  opacity: 85%;
  transition: 0.5s;
  text-align: center;
}
.testimonial {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(350px, 1fr));
  grid-gap: 20px;
}
.testimonial .introcard {
  position: relative;
  margin: 0 auto;
  width: 350px;
  background: radial-gradient(#1b2735 0%, #090a0f 100%);
  padding: 20px;
  box-sizing: border-box;
  text-align: center;
  box-shadow: 0 10px 40px rgba(0, 0, 0, 0.5);
  overflow: hidden;
}
.testimonial .introcard .layer {
  position: absolute;
  top: calc(100% - 2px);
  left: 0;
  height: 100%;
  width: 100%;
  z-index: 1;
  transition: 0.5s;
  opacity: 90%;
  background: linear-gradient(#03a9f4, #e91ee3);
}
.testimonial .introcard:hover .layer {
  top: 0;
  opacity: 90%;
}
.testimonial .introcard .introcontent {
  position: relative;
  z-index: 2;
}
.testimonial .introcard .introcontent p {
  display: flex;
  margin: 15px;
  height: 150px;
  width: 300px;
  overflow-y: scroll;
  font-size: 15px;
  line-height: 24px;
  text-align: left;
  color: white;
}
.testimonial .introcard .introcontent .image {
  width: 250px;
  height: 250px;
  margin: 0 auto;
  border-radius: 50%;
  overflow: hidden;
  border: 4px solid #fff;
  box-shadow: 0 10px 20px rgba(0, 0, 0, 0.2);
}
.testimonial .introcard .introcontent .details h2 {
  color: white;
  font-size: 18px;
}
.testimonial .introcard .introcontent .details span {
  color: white;
  font-size: 14px;
  transition: 0.5s;
}
::-webkit-scrollbar {
  width: 5px;
}
::-webkit-scrollbar-track {
  background:none;
  border-radius: 100px;
}
::-webkit-scrollbar-thumb {
  border-radius: 100px;
  background-image: linear-gradient(180deg, pink 0%, lightblue 99%);
  opacity: 20%;
}


}

</style>

<div id='stars'></div>
<div id='stars2'></div>
<div id='stars3'></div>

<div class="container1">
<div class="glassBox">
  <div class="glassBoximgBox">
    <img src="/images/meme1.png" alt="Dog Image"> 
    <h3 class="glassBoxtitle">Voted<br> Python is the best!</h3>
  </div>
  </div>
<br><br>
</div>
</div>

## About Us
### (I copied our group members' introduction from Campuswire.)
<p>I added some random profile pictures for my group members, just for fun. LOL</p>
<div class="testimonial">
  <div class="introcard">
    <div class="layer"></div>
    <div class="introcontent">
    <h5 style="color:white;">Campuswire Intro</h5>
      <p>
        Where are you from?<br><br>
        I moved to Century City six years ago. Before that, I lived in San Francisco for one year and seven years in Vancouver, Canada.<br><br>
        What is your major, or what are you interested in?<br><br>
        I am majoring in Applied Mathematics, but I am interested in computer science.<br><br>
        Why are you interested in advanced Python programming?<br><br>
        I'm interested in advanced Python programming because I think Python is an essential skill, and I want to explore more powerful tools which I can use in my future career.<br><br>
        What's a fun fact about you? <br><br>
        A fun fact about me is that I like to cuddle with my french bulldog.
      </p>
      <div class="image"><img src="/images/cartoon.png" alt="cartoon">
      </div>
      <div class="details">
        <h2>Peng</h2> <br> <span>myself</span>
      </div>
    </div>
  </div>

  <div class="introcard">
    <div class="layer"></div>
    <div class="introcontent">
         <h5 style="color:white;">Campuswire Intro</h5>
      <p>
        Where are you from?<br><br>
        I am from Jilin, a northeast province in China. I am a transfer student here. I spent my first two years of college in UC Davis, and I just moved to LA for 4 months.<br><br>
        What is your major, or what are you interested in?<br><br>
        My major is financial actuarial math. I am interested in marketing, and the skills I learn in data would be a helpful tool to become a good marketer.<br><br>
        Why are you interested in advanced Python programming?<br><br>
        I want to learn more programming and data skills. Even though I won’t be a programmer in the future, the programming skills is widely used in many areas.<br><br>
        What’s a fun fact about you?<br><br>
        I love dancing and I have a flexible body to do some amazing movements.
      </p>
      <div class="image"><img src="/images/random1.jpg" alt="cartoon">
      </div>
      <div class="details">
        <h2>Jiamu</h2> <br> 
      </div>
    </div>
  </div>

  <div class="introcard">
    <div class="layer"></div>
    <div class="introcontent">
         <h5 style="color:white;">Campuswire Intro</h5>
      <p>
        Where are you from?<br><br>
        I live in Westwood since the last quarter. Before that, I lived in Alhambra. And I still visit back to Alhambra to have Chinese cuisines. If any of you're interested in Chinese cuisines, highly recommend visiting this place.<br><br>
        What is your major, or what are you interested in?<br><br>
        My major is Applied Mathematics. After taking math 142, I found mathematical modeling is super cool stuff.<br><br>
        Why are you interested in advanced Python programming?<br><br>
        After taking PIC 16A with professor Chodrow, I found out that coding is fun and super practical. So I decide to take this class. Besides, it becomes a demand in most careers.<br><br>
        What’s a fun fact about you?<br><br>
        My favorite Spider-Man actor is Tom Holland!!!
      </p>
      <div class="image"><img src="/images/random2.jpg" alt="cartoon">
      </div>
      <div class="details">
        <h2>Weixin</h2> <br>
      </div>
    </div>
  </div>

  <div class="introcard">
    <div class="layer"></div>
    <div class="introcontent">
        <h5 style="color:white;">Campuswire Intro</h5>
      <p>
        Where are you from?<br><br>
        I am from China, but I am living in Portland now. I moved from LA to Portland last year. Now I love it more than LA.<br><br>
        What is your major, or what are you interested in?<br><br>
        My major is Applied Mathematics. I am interested in solving problems. Now programming is my another big interest.<br><br>
        Why are you interested in advanced Python programming?<br><br>
        I am interested in advanced Python programming because I want to be a data scientist. Python is the best tool to work and deal with data.<br><br>
        What’s a fun fact about you?<br><br>
        A fun fact about me is that I climbed a 30 feet pole and installed a cross arm on it which is half of my weight.
      </p>
      <div class="image"><img src="/images/random3.jpg" alt="cartoon">
      </div>
      <div class="details">
        <h2>Miao</h2> <br>
      </div>
    </div>
  </div>

</div>


<br>
Our group (**Peng** (myself), **Jiamu**, **Weixin**, and **Miao**) made the web app called **Dog Facial Recognition**. Our web app used three machine learning models. First, our web app will detect if the image contains any human face. Then, it will detect the uploaded image is a dog or cat. Finally, the web app will show the top three most likely dog breeds.




## Our Webapp Links
<!-- - Here is the [link](https://github.com/PengWu2626/PIC16B_GroupProject) to the GitHub repository containing the code of this project.

- Here is the [link](https://dogfr.nicholastec.com) for our webapp running on the AWS platform. Thanks to my group member Jiamu, she developed this. (**Recommended** with Much Faster Boot Time)

- Here is the [Heroku link](https://pic16b-dog-facial-recognition.herokuapp.com/) for our webapp. (Long Boot Time)

- Here is the [Heroku link](https://pic16b-dogfr-short.herokuapp.com) for the short version of our webapp, which removed face detecting and the drop zone. (Long Boot Time) -->

<table class="myglasstable">
  <tr>
    <td>
      <div class="glasscontainer">
      <div class="card">
      <div class="content">
      <h2 style="color:rgb(228, 228, 240); font-size: 20px; top: -50px;">GitHub</h2>
      <i class="fa fa-github fa-5x fa-spin" style="color:lightpink"></i>
      <br>
      <br>
      <p>Here is the <a href ='https://github.com/PengWu2626/PIC16B_GroupProject'>link</a> to the GitHub repository containing the code of this project.</p>
      </div>
      </div>
      </div>
    </td>
    <td>
      <div class="glasscontainer">
      <div class="card">
      <div class="content">
      <h2 style="color:rgb(228, 228, 240); font-size: 20px; top: -50px;">I am Moose</h2>
      <img src="/images/moose.JPG" height="250" width="300" alt="Moose Image">
      </div>
      </div>
      </div>
    </td>
  </tr>
  <tr>
    <td>
      <div class="glasscontainer">
      <div class="card">
      <div class="content">
      <h2 style="color:rgb(228, 228, 240); font-size: 20px; top: -50px;">AWS Link</h2>
      <p>
      <ul>
      <li><strong>Recommended:</strong><br> Here is the <a href ='https://dogfr.nicholastec.com'>link</a> for our webapp running on the AWS platform. Thanks to my group member Jiamu, she developed this. (Faster Boot Time)</li>
      </ul>
      </p>
      </div>
      </div>
      </div>
    </td>
     <td>
      <div class="glasscontainer">
      <div class="card">
      <div class="content">
      <h2 style="color:rgb(228, 228, 240); font-size: 20px; top: -50px;">Heroku Link</h2>
      <p>
      <ul>
      <li>Here is the <a href ='https://pic16b-dog-facial-recognition.herokuapp.com/'>link</a> for our webapp. (Long Boot Time)</li>
      <li>Here is the <a href ='https://pic16b-dogfr-short.herokuapp.com'>link</a> for the short version of our webapp, which removed face detecting and the drop zone. (Long Boot Time)</li>
      </ul>
      </p>
      </div>
      </div>
      </div>
    </td>
  </tr>
</table>

## Overall, what did you achieve in your project? 

I mainly designed this project, assigned minimal tasks to each group member that they must do, and helped our group members with any questions. For instance, I asked Jiamu to write a face detection model to determine if the user uploaded image contains any human face. Also, I assigned each of Weixin and Miao to build two different models using transfer learning for dog breed classification.

My main achievement for this project is to make sure our webapp is working. I gathered all models from our group members, did image processing inside our webapp, and wrote the most part of the [view page](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/templates/view.html) and [app.py](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/app.py) file. I had many ideas that popped up while building our webapp, so I decided to write some extra features in our webapp.

Extra Features:

- I wrote a `web scraping` called [DogTime Scraper](https://github.com/PengWu2626/PIC16B_GroupProject/tree/main/DogTime_scraper) to get all characteristics for each dog breed from the [DogTime](https://dogtime.com/dog-breeds/profiles).

- I wrote a [Drag Upload page](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/templates/drag_upload.html) and all relative codes that contain a [Drop zone](https://flask-dropzone.readthedocs.io/en/latest/index.html) that allows the user to drag an image to upload.
<img src="/images/reflection_blog_ post_images/Drag_Upload_Page.png" alt="Drag Upload Page Image">  

- I wrote a [Click Gallery Upload page](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/templates/display_uploads.html) and all relative codes to display all user-uploaded images, and users can click on each image to get the predicting result from our models. 
<img src="/images/reflection_blog_ post_images/Click_Gallery_Upload.png" alt="Click Gallery Upload Image"> 

- I wrote a [DogTime Information page](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/templates/doginformation.html) and all relative codes to generate bar charts with 26 characterizes that I scraped from Dogtime from a user-selected dog breed.
<img src="/images/reflection_blog_ post_images/DogTime_Information.png" alt="DogTime Information Image"> 

- I wrote the [Find Your Best Dog page](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/templates/findyourdog.html) and all relative codes to find matched dog breeds from the user-selected numbers.
<img src="/images/reflection_blog_ post_images/Find_Your_Best_Dog.png" alt="Find Your Best Dog Image"> 


## What are two aspects of your project that you are especially proud of? 

1. Adding CSS and Javascript made our webapp more interactive and beautiful. Therefore, I searched for many cool effects that we can use inside our web page. I modified some cool CSS effects codes that I found online. For example, I combined these two beautiful [Parallax Star backgrounds](https://codepen.io/saransh/pen/LYGbwj) and [Shooting Star backgrounds](https://codepen.io/alphardex/pen/RwrVoeL) and added the [Glassmorphism](https://hype4.academy/tools/glassmorphism-generator) effects. Unfortunately, I did not have any prior experience with CSS and Javascript, and I had to use them inside many for loops, which increased the difficulty of building our webapp. 


2. I successfully developed our webapp on Heroku. In the beginning, I used `pip freeze` and copied all dependence names inside the [requirements.txt](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/requirements.txt). No surprise, the slug size was way too large. So I created another short version of this project in the [pic16b_group_project_short_version](https://github.com/PengWu2626/pic16b_group_project_short_version) repository, which removed face detecting and drop zone. After researching how to reduce the slug size, I noticed that changing `tensorflow` to `tensorflow-cpu` in the `requirements.txt` and removing all unnecessary dependencies and files helped a lot. However, even the webapp had a slug size of less than 500 MB; there were still many problems while deploying the app; for example, I found an error that said there was no such file by using view logs, but the webapp was working fine locally. Finally, I found out that I named some files which contained some capital letters. Furthermore, once I updated all file names to lowercase locally, the GitHub desk did not show any changes. I did not expect this much difficulty to develop on Heroku, so I am especially proud to build our webapp successfully.

## What are two things you would suggest doing to further improve your project?


1. Two days before our final presentation, I wanted to remove the background, cut out the dog from the image, and then display it with `Glassmorphism` effects inside the `Find Your Best Dog` page. However, it was impossible for me to do each image manually, so I wondered if there existed a model that would automatically remove a picture's background. Luckily, I found it is possible by using the `Image Segmentation` from TensorFlow. I would research more information about `image segmentation` and `object detection` if I had more time to improve our project.


2. I did not use any database for this project. I wish I could use the database to store and access all prediction results for all uploaded images.

## How does what you achieved compare to what you set out to do in your proposal? 


We achieved all planned deliverables in our [proposal](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/proposal.md), and I added more extra features to this project.
Since one of my group members successfully wrote a model to detect if an image contains any human face. So, I added some cool CSS effects. 

For example, dog breed prediction will be hidden when the model detects the uploaded image containing any human face. Then our web app will prompt the user that the uploaded picture might include humans.

<img src="/images/reflection_blog_ post_images/Face_detected1.png" alt="Face detected1 Image"> 

 Finally, the user needs to click the `Continue to show the prediction` button to see the predictions.

<img src="/images/reflection_blog_ post_images/Face_detected2.png" alt="Face detected2 Image"> 

## What are three things you learned from the experience of completing your project? 

1. I am still exploring GitHub; I had never used GitHub before this class. When I was thinking about displaying random images for each dog breed in the top three predictions, I learned that I could upload our dataset inside another repository and access all photos using the image URL. This method allows me to show multiple images for each dog breed without increasing slug size. I uploaded our training dataset inside the repository [pic16b-stanford-dog-dataset](https://github.com/PengWu2626/pic16b-stanford-dog-dataset). [Here](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/data/get_sample_images_path.ipynb) is the detail information about how I obtained all Image URLs.


2. I learned enough fundamental skills to build a simple interactive webapp using Flask. 


3. I learned how to use the TensorFlow package inside Flask locally on M1 Mac using Miniforge Environment. The instruction is inside the [README.md](https://github.com/PengWu2626/PIC16B_GroupProject/blob/main/README.md) file.

## How will your experience completing this project will help you in your future studies or career? 


The experience of building a project as a team is important for me.
Furthermore, I want to become a software engineer after I graduate; therefore, this hands-on project can better prepare me to fit in my future job environment. Before this class, I mainly practice many codes as a back-end developer. Therefore, I am grateful that this project let me practice many front-end skills, which I have always wanted to study.


<script type="text/javascript" src="/static/vanilla-tilt.js"></script>
  <script>
    VanillaTilt.init(document.querySelectorAll(".card"), {
    max: 25,
    speed: 400,
    glare: true,
    "max-glare": 1,
    })
  </script>