# Udacity Data Analyst Nanodegree (DAND)

[Udacity数据分析师纳米学位](https://cn.udacity.com/dand)

## 完成的数据分析项目

### 1. [湾区共享单车分析报告](https://github.com/leesper/become-data-analyst/blob/master/P0_BayAreaBikeShareAnalysis/Bay_Area_Bike_Share_Analysis.ipynb)

“共享单车分析”项目是“数据分析入门”纳米学位的第一个项目，该项目调查了美国某共享单车公司的真实数据，旨在让学员初步熟悉数据的收集，整理，研究和展示工作。本人负责完成整个报告的撰写工作。为了完成该分析报告，我首先写下了6个我认为可以使用数据来回答的问题。然后按照课程要求阅读了来自Tyler Field最佳分析报告，并根据他的分析判断自己之前提出的问题是否能够得到回答。随后，我抽取了项目提供的真实数据一部分样本，进行观察，使用项目提供的代码对行程数据进行精简。在探索性数据分析过程中，我首先查看了数据的一些初步趋势，比如2013年9月有超过27000次出行，单车平均单次骑行时间都在30分钟之内，中位数为10.72分钟（即有一半的行程比它短，另一半的行程比它长）。然后查看了年费用户与非年费用户的区别，发现前者的行程比后者多大概50%，但绝大部分人骑行时间都在30分钟内（这跟收费策略有关，该公司规定骑行超过30分钟就要收取额外费用）。进一步查看60分钟以内的骑行数据，会发现5-10分钟左右的出行次数最多。在最后的自行分析过程中，我读取了全部的数据并进行分析，发现跟样本得到的结论有所不同，比如平均骑行时间是65.86分钟，对于年费用户而言，60分钟内骑行次数最多的还是5-10分钟用户，而非年费用户则是10-15分钟的最多；还有就是非年费用户骑行超过50分钟以上的人大有人在，他们可能是来当地游玩的游客，所以骑行的时间长一些，会额外付一些费用。有趣的发现是，年费用户平均骑行9.83分钟，而非年费用户平均骑行65.86分钟，结合上面阅读过的数据分析报告，可以知道前者是上班族，主要用共享单车实现到地铁站的“最后一公里”通勤，而后者则是游客，有骑车到处游玩的需要。该项目完成后，本人体验了一把数据分析的工作内容，熟悉了数据整理和分析的大致流程，为继续学习后续内容打下初步的基础。

### 2. [斯特鲁普效应分析报告](https://github.com/leesper/become-data-analyst/blob/master/P1_StroopEffectAnalysis/P1_StroopEffectAnalysis.ipynb)

“斯特鲁普效应数据分析”项目是“数据分析入门”纳米学位的第二个项目，项目调查了该实验心理学中的典型现象，并结合实验提供直观的数据，并根据结果利用统计推断得到结论。本人负责完成整个数据分析和报告的撰写工作。为了完成该分析报告，我首先了解了问题背景，并对实验要进行的内容进行初步了解。然后根据实验指导提供的网页链接体验了一下该心理学实验，即当表示颜色的词汇与其显示的颜色不相符合时，会对实验者准确说出颜色造成干扰。紧接着我对实验提供的数据进行了分析，找出自变量和因变量，并提供零假设和对立假设的描述。在查看了样本数据的分布后，决定选用相依样本t检验作为统计检验模型。在进行统计假设检验的过程中，我首先进行描述性统计，给出均值和标准差等数据，然后计算置信区间，得出拒绝零假设的结论，也就是说颜色的不一致的确会干扰实验者对颜色的辨识。该项目完成后，本人对统计假设检验的实际应用能力得到了提高。

### 3. [泰坦尼克号乘客分析报告](https://github.com/leesper/become-data-analyst/blob/master/P2_investigate_dataset/P2investivate_dataset.ipynb)

“泰坦尼克号乘客数据分析”项目是“数据分析入门”纳米学位的第三个项目，数据取自kaggle平台上真实的竞赛数据，提供了一组泰坦尼克号上乘客的人口学数据和基本信息，该项目提出了一系列的问题（比如对于乘客生还率的研究）并通过数据分析从多个角度探索了数据，回答了问题。本人负责完成整个数据集的探索和报告撰写工作。为了完成该报告，我遵循了数据分析的一般过程，对数据内容进行初步探索并提出了10个比较感兴趣的问题：乘客的总体生还情况如何？年龄，性别，客舱等级等是否对生还率造成一定的影响？等等。首先，我对数据进行了整理和检查，过滤掉某些缺失的数据，确保数据是没有问题的。接着对数据进行了系统的分析，包括查看汇总信息，乘客的年龄分布，不同年龄段乘客的生还率，不同客舱等级乘客的生还率，不同性别乘客的生还率等等，特别是分析了性别是否对儿童乘客的生还率造成影响。并在报告的最后给出了结论：头等舱乘客生还率较高，女性乘客生还率较高，儿童乘客生还率较高，且对于儿童乘客而言性别对生还率的影响大幅降低。

### 4. [优达学城A/B测试试验分析报告](https://github.com/leesper/become-data-analyst/blob/master/P7_ABTest/P7_AB_test.ipynb)

“优达学城A/B测试”项目是“数据分析入门”纳米学位的第四个项目，数据来源于优达学城运行过的真实的试验，该试验旨在改进在线教育平台“开始免费试学”的业务流程，进一步提高用户的体验，降低学习挫败感并提高付费度。本人负责将整个试验的想法变成一个完整定义的A/B测试设计并分析结果，最后提供一个高层次的后续试验描述。为了完成该报告，我首先仔细了解了试验的背景以及要实施的举措。然后按照A/B测试的规范，先进行度量选择，包括不变度量和评估度量，并针对每个度量详细解释了它能或者不能作为不变度量或者评估度量的原因。随后对选择的评估度量（总转化率，净转化率和留存率）分别计算了标准差，并分别分析了其分组单元和分析单元情况。接着对试验的规模进行了选择，由于使用留存率时估算出来的页面浏览量太大，导致试验需要进行很长时间所以把这个度量放弃了。最后我对试验数据进行了分析，包括完整性检查和结果分析，并根据净转化率不具备统计和实际显著性建议暂不实施该改变，而是提出了一个后续试验的方案以进行进一步的A/B测试。报告完成后，我对A/B测试在产品增量改进中的应用加深了认识，提高了应用能力。

### 5. [贵阳市地图数据清洗与分析报告（OpenStreetMap）](https://github.com/leesper/become-data-analyst/blob/master/P3_OpenStreetMap/P3_open_street_map.ipynb)

“整理OpenStreeMap数据”是“数据分析进阶”纳米学位的第一个项目，地图数据来源于OpenStreeMap，通过该项目能学习和掌握数据加工和整理的基本技能。本人负责整个地图数据的加工，整理和撰写分析报告。为了完成该项目，我下载了贵阳市的地图数据，数据格式为XML。拿到数据后我做的第一件事就是浏览数据，人工观察一下数据的内容和格式，简单写几行代码统计一下标签个数，发现至少存在以下几个问题：1. 一些数据点的经纬度不在有效范围内；2. 道路的英文名称出现不只一种缩写或拼写错误；3. 一些数据点的名称出现中英文混合；4. 电话号码格式不统一或出现错误；5. 门牌号格式不统一。然后我对这些问题进行了修复，首先写代码分析了所有经纬度值，发现其与地图边界数据经纬度值存在的最大误差不超过5，考虑到GPS定位产生的误差以及不影响后续分析，没有做处理。但是对于其他四种错误，都写了代码进行格式修复或者对少量录入错误进行手工修正。最后我将清洗后的数据导入SQLite数据库，并对地图数据进行了进一步的探索。比如调查数量最多的生活设施都有哪些，贡献地图数据最多的用户排名等等，并对数据的改进进行了建议，列出各种可能的改进方案以及优缺点。分析完成后，我获得了数据整理和清洗的经验，提高了自己处理实际问题的能力。

### 6. [探索性数据分析：白葡萄酒口感与化学成分](https://github.com/leesper/become-data-analyst/blob/master/P4_Explore_Summarize_Data/winesEDA.md)

“白葡萄酒口感与化学成分”是“数据分析进阶”纳米学位的第二个项目，数据有4898条，13个变量，包含专家口感评分和各种化学成分，如酒石酸，乙酸，柠檬酸，硫酸盐和残糖量等等。通过该项目能够掌握使用R语言进行探索性数据分析（EDA）必备的各项技能。本人负责整个数据分析报告的撰写。为了完成该项目，我首先阅读并理解各变量的基本含义，对数据集进行最基本的调查，按照自己的理解创建了三个新变量：质量等级，残糖等级和固定二氧化硫含量。然后我对数据集进行了多个角度的探索分析，第一步先进行单变量分析，通过直方图和箱线图研究各数值型变量分布，通过柱状图研究各因子型变量数量；第二步进行双变量分析，先创建相关矩阵和散点图矩阵观察变量之间可能的相关关系，然后研究两两变量之间的关系，观察到一些有趣的现象，比如品质较高的葡萄酒酒精含量中位数往往偏高，酒精和残糖量都分别与密度有很强的相关性等等；最后一步进行了多变量分析，重点研究了残糖量，密度，酒精含量，固定二氧化硫含量之间的相关关系，并尝试建立线性回归模型，我发现虽然强相关，但单单使用酒精或者残糖量建立的线性回归模型对密度的预测质量都不是很高，最后我结合了残糖量，酒精含量和固定二氧化硫含量，建立了综合的线性回归模型，对密度的预测质量（R平方）达到了约91.45%。项目完成后我对分析过程进行了总结，认真梳理了收获和遇到的挫折，为下一步真正学习和掌握机器学习算法做好准备。

### 7. [机器学习项目：从安然公司邮件中识别欺诈嫌疑人](https://github.com/leesper/become-data-analyst/blob/master/P5_Enron_MachineLearning/P5_Enron_Machine_Learning.ipynb)

“从安然公司邮件中识别欺诈嫌疑人”是“数据分析进阶”纳米学位的第三个项目，数据来自于2001年安然破产案公开的数据，大约有20个特征，分为三类，分别涉及安然公司财务数据，邮件数据和POI（嫌疑人）标签。本人负责整个项目的实施，运用机器学习算法基于这些数据构建嫌疑人识别器，用于识别有欺诈嫌疑的安然员工。为了完成该项目，我首先通过项目资料理解各特征的基本含义，然后绘制散点图观察数据，去除掉一些有问题的异常值，并将一些缺失值较多的特征去掉，一些与其他特征相关性较强的特征也去掉，比如某些特征之和产生的新特征。在此基础上，我创建了两个新特征，分别代表“当事人发给POI邮件占总发送邮件的比例”和“当事人收到POI邮件占总收到邮件的比例”。这些比例越高，当事人自己就越有可能是POI。完成手动特征选择后，我通过SelectKBest对特征进行智能评分，然后将得分低于2.0的特征去除，最后保留了14个特征。最后我通过GridSearchCV对主成分分析和分类器算法进行封装和调参，拟合数据，自动选出“最优参数+最优模型”的分类器。交叉验证采用的是StratifiedShuffleSplit算法，该算法通过打乱顺序然后分为多个分层的容器来将数据分为测试集和训练集，每个容器中的数据集目标类别（label）比例是按照完整数据集的类别比例进行分配的。然后我对得到的若干训练集+测试集数据用分类器进行拟合，调用sklearn.metrics.f1_score计算得到一个f1分数，最后汇总多次计算的f1分数平均值作为性能评估标准。最后我选择了性能最好的支持向量机分类器，最优参数为C=1.0，class_weight='balanced'，kernel='sigmoid'和gamma=0.1，PCA的n_components参数为4。得到的精确度0.331，即被标记为POI的人中有33.1%为真正的POI；召回率0.862，即所有为POI的人中有86.2%被正确的标记。该项目完成后我对什么是“机器学习”有了更深入的认识，特别是如何选择特征和自动调整最优参数。

### 8. [数据可视化项目：Prosper贷款人职业分布与贷款状态所占比例](https://leesper.github.io/prosper_datavis/index.html)

“创建有效的数据可视化”是“数据分析进阶”纳米学位的第四个项目，数据来自于美国P2P平台Prosper.com，有81个变量，113937项贷款数据。本人负责从数据集中提取出贷款人职业与贷款状态信息，研究贷款人职业与不良贷款之间是否存在某种关联关系。为了完成该任务，我首先使用R语言将我需要的数据从原始数据中抽取出来，将多余的数据去掉，将80M的数据精简为6M。接着我使用Bootstrap模板做了一个带导航菜单的界面，提供下拉菜单选择年份。然后我开始运用D3.js做数据可视化，先是将美国地图的地理数据和我之前整理的贷款数据读入内存，并在此基础上对贷款数据进行聚合运算，并清洗，加工和整理，形成了两类数据：以国家为单位的贷款数据（含按年分组的信息）和以各州为单位的贷款数据（同样含按年分组的信息），然后我利用地理信息数据绘制了美国地图，利用贷款数据绘制了正则化的堆叠柱状图，用于以国家为单位或者以州为单位显示贷款人职业分布和不良贷款比例之间的信息。在此基础上我增加了动画和互动效果，旨在提高阅读者对可视化的理解能力，当用户操作鼠标移动到地图上某个位置时，地图能动态显示该地区简称和贷款数量，并能通过柱状图看到该地区的具体情况。最后数据可视化得出的结论是：“职业身份对贷款不良率具有显著的影响，受教育程度较高，收入颇为丰厚的“脑力劳动”职业者，如法官，律师，飞行员，医生，军官，分析师和程序员等不良贷款所占比例较低；而不需要接受太高教育的“体力劳动”职业者，不良贷款所占比例有所增加，且内陆或不发达州的贷款率偏少。”

## 所获荣誉

![](https://github.com/leesper/become-data-analyst/blob/master/dand1.jpg)

![](https://github.com/leesper/become-data-analyst/blob/master/dand2.jpg)
