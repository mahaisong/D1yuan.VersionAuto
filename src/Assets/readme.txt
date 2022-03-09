作者：mahaisong D1yuan
功能说明：项目build生成后，查看dll的属性下的版本号。
git地址：D1yuan.VersionAuto  https://github.com/mahaisong/D1yuan.VersionAuto
支持：netstandard2.1; net4.6+; netcore+; net6+;

————
版本号:
格式：{verNum.txt}.{buildNum.txt}。     初始值为：0.0.0.0     样例：1.0.1.53

1.存储在2个文件中。可以手动修改文件内容，来指定当前的dll版本号。
verNum.txt： 前缀大版本号，格式为1.1.1。
buildNum.txt ：小版本号=构建的次数,格式为53,。vs生成就自动+1---自增。
————

注意事项： 
1.多平台下，将会使用buildMultiTargeting。
2.targets文件名称一定要和nuget包的名称相同。
