# c语言实现

```cpp
//销毁线性表L

void DestroyList(SqList &L){//引用传递

	if (L.elem){//判断是否存在L
		delete L.elem; //释放空间
	}
}

}
```