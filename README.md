# Position-comparation
https://position-comparation.pages.dev/
输入税后工资、房租、通勤花费、通勤时长、工作时长等参数来计算每个岗位的时薪、日薪如何，并且根据时薪为标准排序哪些工作对于你来说是最有性价比的。
数据保存在浏览器本地localstorage，保证安全。
同时也可以导出&导入.json文件来与他人共享
![Example](https://github.com/user-attachments/assets/b04c50f5-d76e-493c-9664-d392de103e85)

2025/02/11 更新
现在可以看去掉房租和通勤成本后每月你到手多少（列 每月到手收入（元/月））
增加一个属性"每日居家天数"，会影响通勤成本和通勤时间
增加一列“占时收入幸福度”，会根据 到手收入 和 工作平均每天占用的时间 来大致计算每份工作可能带给你的幸福度,
一天固定被占用超过9小时20开始引入惩罚因子，幸福度开始下降
此后当超过10小时、11小时时候再次更激烈地惩罚幸福度，并在工作时长达到12小时时到达巅峰。
![image](https://github.com/user-attachments/assets/818aa4ec-d987-4024-83be-685eb0d7b159)
鼠标悬浮在同一公司名的项时，这个公司的岗位都会被高亮
当岗位有提供混合工作或纯线上的时候 “平均每天占用” 列可以显示
![image](https://github.com/user-attachments/assets/38f54069-c664-453d-9843-602a3c5c8dd2)
可以输入自己目前岗位的幸福度，方便让系统给出推荐，输入后低于目前幸福度的岗位幸福度列为红，高于目前幸福度则为绿
![image](https://github.com/user-attachments/assets/02740b06-b8ff-4fec-85ca-9d774ef1490c)

2025/02/12 更新
右上增加了一个固定的工具栏 点击右上角可以折叠
增加一个假设房租上涨的工具，因为在积极寻找工作的时候有的时候并不确定陌生地区的房价、这有助于快速参考当房价变化时的幸福度
增加“房租”，“通勤时间”列
![update](https://github.com/user-attachments/assets/28321495-abb4-4d93-8946-b8e75e900bb1)
增加批量更改房租、因为大多数时候一家公司的不同岗位租房参考往往一样
![image](https://github.com/user-attachments/assets/8d87b4b3-e1b4-4b7d-8301-b0b38809429b)
