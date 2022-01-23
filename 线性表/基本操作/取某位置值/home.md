```cpp
//算法2.2　顺序表的取值
Status GetElem(SqList L, int i, ElemType &e) {
	if (i < 1 || i > L.length)//判断i值是否合理，若不合理，返回ERROR
		return ERROR; 
	
    e = L.elem[i - 1]; //elem[i-1]单元存储第i个数据元素
	return OK;
}
```