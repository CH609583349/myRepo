# MyRepo
Software Innovation Class Demo  
陈  皓 118037910046  
尹君豪 118037910066  
李萍萍 118037910030  
[![HitCount](http://hits.dwyl.io/CH609583349/myRepo.svg)](http://hits.dwyl.io/CH609583349/myRepo)
## Hypothesis
每当人们走进图书馆时，面对海量的图书信息，可能会有选择的困难。有时候，一些人可能只是想读一读有意义的书籍，增长见识，然而对于具体读哪些书，可能没有确定的目标。并且，图书馆的书种类丰富，如何快速定位自己感兴趣的书籍是一个较为艰难的过程。
## Customer Validation
### 第一次客户验证
针对我们提出的Hypothesis，我们设计了调查问卷来进行我们的第一次用户验证。我们把客户对象定得比较窄，于是调查人群主要集中于会使用学校图书馆资源的学生和教职工群体。最终我们获得了22个样本信息。根据对图书馆图书推荐系统潜在用户的第一次调研统计结果的分析，我们可以发现，大部分同学有去图书馆借书的习惯，然而大部分同学每个月借书的数目为0到1本，少部分同学每个月借2-5本书。至于借书的喜好，大多数同学平时会借阅与专业相关的和与爱好相关的书籍，英语类和工具类图书的借阅比例相对较小。超过70%的同学有图书推荐的需求。具体的统计分析结果如下图所示：
![调研结果1](https://github.com/LPP2016/myRepo/blob/master/img-storage/%E5%9B%BE%E7%89%87%201.png)
![调研结果2](https://github.com/LPP2016/myRepo/blob/master/img-storage/%E5%9B%BE%E7%89%87%202.png)
![调研结果3](https://github.com/LPP2016/myRepo/blob/master/img-storage/%E5%9B%BE%E7%89%87%203.png)
![调研结果4](https://github.com/LPP2016/myRepo/blob/master/img-storage/%E5%9B%BE%E7%89%87%204.png)
### 第二次客户验证
我们与上海交通大学图书馆合作，为我们提供了2013~2016年的全部借阅记录。在第一次的验证基础上，我们通过对数据进行有针对性的分析，绘制出如下的图表。该表表示为每个院系的学生借阅的最多三类书。根据这张图表，我们将学生的借阅爱好分为以下两类：个人兴趣和专业兴趣。
![Cate](https://github.com/CH609583349/myRepo/blob/master/img-storage/cate.png)
附录：[关于图书馆推荐系统的调研_38269641.docx](./关于图书馆推荐系统的调研_38269641.docx)
## Scope of our product
我们的产品面向全体上海交通大学在校本科生，为他们提供精准的、合适的、个性化的图书借阅推荐，解决本科生在修课程的时候无法找到合适辅助资料的烦恼。
## Solution
根据当前我们提出的假设和调研发现的问题，我们提出了一个关于实现图书馆图书推荐系统Web端的解决方案，根据不同类型的同学们的喜好，推荐适合其阅读并符合其个人阅读兴趣的图书。
### Solution Validation
我们的产品原型比较简单，所涉及的主要页面如下图所示。学生在登录进来之后会提供给学生推荐的书籍列表，对于新加入的用户会提供热门书籍（cold start）。
![Cate](https://github.com/CH609583349/myRepo/blob/master/img-storage/prototype.png)
