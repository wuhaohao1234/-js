## 字符串操作
* 获取字符串长度：len(str)
* 字符串格式化："yingxs{}".format("com")
* 字符串拼接："yingxs"+"com"
* 字符串替换："yingxs_com".replace("_","")
* 字符串的索引："yingxs.com"[0],"yingxs.com"[0:8]
* 去除字符串两边的空格："    yingxs.com   ".strip()
* a = "ying" in "yingxs.com" ,true判断一个字符串是否包含在另一个字符串中

## 列表操作
* 列表长度 ：len(a)
* 向列表中追加数据： a.append("yingxs")
* 列表的索引
    * a[1]
    * a[2:5]      从第二个开始到第五个之前的数据
    * a[2:5:2]       从第二个开始到第五个之前的数据，步长为2
    * a[5:2:-2]       和前一个数据的顺序相反，步长为-2所以是倒着取值
    * a[::-1]       和a中顺序相反，步长为-1
* 列表的扩展
    * [1,2]+[3,4] 或者 a.extend([3,4])
    * ["a","b",123].index("b")获取指定元素的索引
    * [1,2,3,1].insert(0,1)
    * [1,2,3,1].remove(1)

## 字典操作
* a={}定义一个空字典
* a["xioaming"]=10 在a中添加或更新禁止对 "xiaoming":10
* a["xiaoming"]获取键对应的值
* b=a.pop("xiaoming")删除xiaoming的键值对，同时返回值
* c = {"xiaohua":32} a.update(c) 把c中的键值对更新到a中
* a["xiaohua"]=[1,2,3]
* a['xiaohua']={"age":18,"grade":3}

## 循环
### range()函数，能够快速生成一个可迭代对象
range(12) 生成包含0-11的数字的可迭代对象
range(1,10)生成包含1-9的数字的可迭代对象
range(1,10，3)步长为3

* list(range(1,10)) 变成一个列表，也是一种强制类型转换

## 全局变量与局部变量
* 全局变量在函数中可以引用，但是不能修改
* 在函数中出现a=10意味着创建局部变量a
* 如果需要在函数中修改全局变量，需要使用global来声明 global a=30





















