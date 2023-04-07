# ibd_viewer
mysql innodb .ibd文件解析器

### 示例
#### 查看所有页的页号和类型
![图片](https://user-images.githubusercontent.com/49143209/230388154-dd95f714-c10a-40fe-824d-19fbc5c0a6ee.png)
#### 查看索引根
![图片](https://user-images.githubusercontent.com/49143209/230390654-4fd85882-2afc-4728-860b-bb4ba8ba47cf.png)
#### 查看具体页的数据,可以看到行记录
![图片](https://user-images.githubusercontent.com/49143209/230540266-d0541e56-7392-4a80-8893-aeefd60b5b46.png)

### 支持

1. MySQL 8.0
2. 行格式为Compact、Dynamic 和 Compressed
3. B+树节点、FilPageTypeFspHdr
