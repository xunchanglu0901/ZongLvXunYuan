# 棕榈学院python课程
### lesson3
##### zip()函数起到拉链作用，对两个或多个列表同位置元素进行对应匹配
##### zip()函数用于将可迭代的对象作为参数，将对象中对应的元素打包成一个个元组，然后返回由这些元组组成的列表
##### 如果各个迭代器的元素个数不一致，则返回列表长度与最短的对象相同，利用 * 号操作符，可以将元组解压为列表
###### >>>a = [1,2,3]
###### >>> b = [4,5,6]
###### >>> c = [4,5,6,7,8]
###### >>> zipped = zip(a,b)     # 打包为元组的列表
###### [(1, 4), (2, 5), (3, 6)]
###### >>> zip(a,c)              # 元素个数与最短的列表一致
###### [(1, 4), (2, 5), (3, 6)]
###### >>> zip(*zipped)          # 与 zip 相反，*zipped 可理解为解压，返回二维矩阵式
###### [(1, 2, 3), (4, 5, 6)]
###### for循序写字典，字典添加内容的方式比较特别，需要注意
###### B = [4, 7, 2, 6, 6, 8, 8, 10, 4]
###### C ={}
###### for i in set(B):
######     C[str(i)] = [B.count(i)]
######     #print([B.count(i)])
###### print(C)

### lesson3
##### 列表元素交换位置; 冒泡排序; "\*"三角形
