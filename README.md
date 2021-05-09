## 爬取自今日头条，包含10种分类：
### 财经、房产、教育、军事、科技、汽车、体育、游戏、娱乐、其他（三农、人文、艺术等）
## 每条数据仅包含`新闻标题`和`标签`

- class.txt: 标签分类
- raw-xxx.csv——raw data, 每类包含的数量 >2w 条
- sampled-20000-xxx.csv——从raw-xxx.csv中随机抽取的 2w条数据
- train.csv, test.csv, valid.csv——各含18w, 1w, 1w条数据，10种类型新闻数量平均