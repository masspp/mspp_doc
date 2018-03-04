# Mass++ Data IO Interface

## Data IO Class (draft)
Mass++ ver2 の Data IO Class から、DataGroupNodeを除去し、Chromatogram と Spectrum を直接 Sample に接続した(SampleにDataGroupNode(DataSet)の機能の一部を移した)。
![Class Diagram draft](http://hautbois.jp/~masaki/mspp-common-lib/DataClass_draft1.png "Class diagram of Data IO Class")



## 参考資料
- [Class List of Mass++ Common Library v2.7.5(Doxygen)][1]
- [Class List of Mass++ mzML IO Plugin v2.7.5(Doxygen)][2]
- [Tutorial of Plug-in Developement for Mass++ v2][3]

 
 
 [1]:http://hautbois.jp/~masaki/mspp-common-lib/html/annotated.html
 [2]:http://hautbois.jp/~masaki/mspp-mzmlio/html/annotated.html
[3]: http://hautbois.jp/~masaki/mspp-common-lib/PluginTutorial_ja.pdf