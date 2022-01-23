# c语言实现

```cpp
//算法2.1 顺序表的初始化
Status InitList_Sq(SqList &L) { //使用引用传递
	//构造一个空的顺序表L

	//为顺序表分配一个大小为MAXSIZE的数组空间
    L.elem = new Book[MAXSIZE]; //ElemType为Book
	if (!L.elem)
		exit(OVERFLOW); //存储分配失败退出
	L.length = 0; //空表长度为0
	return OK;
}


```