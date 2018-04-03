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

```
MIT License

Copyright (c) 2018 Bai HongHua

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

