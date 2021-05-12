## 爬取自今日头条，包含10种分类：
### 财经、房产、教育、军事、科技、汽车、体育、游戏、娱乐、其他（三农、旅游、艺术等）
## 每条数据仅包含`新闻标题`和`标签`

- class.txt: 标签分类
- raw-data——raw data, 每类包含的数量 >1.7w 条
- sampled-17000——从各类raw-data中分别随机抽取的 1.7w 条数据
- train.csv/txt, test.csv/txt, valid.csv/txt——各含15w, 1w, 1w条数据，10种类型新闻数量平均