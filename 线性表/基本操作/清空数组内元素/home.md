```cpp
//清空数组元素
//其实只是让它长度归零
//里面存在的元素看成默认初始化
void ClearList(SqList &L){//引用传递
    L.length = 0; //数组内元素数量为0
}

```