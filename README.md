### 工具箱

> 在开发的过程中封装起来的工具类

- ##### [给 RecylerView 的 item 设置分割线的工具类](https://github.com/Hndroid/ToolBox/blob/master/DividerItemDecoration.java) 

```java
// 给纵向的 RecylerView item 设置水平分割线
mRecyclerView.addItemDecoration(
    new DividerItemDecoration(mContext, DividerItemDecoration.VERTICAL_LIST));

//给网格状的 RecylerView item 设置分割线
mRecyclerView.addItemDecoration(
    new DividerItemDecoration(mContext, DividerItemDecoration.HORIZONTAL_LIST))
```


