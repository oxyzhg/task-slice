# Task Slice

### Install

### Usage

```js
import TaskSlice from 'task-slice';

// 要展示在页面的数据
const datalist = [];
// 请求返回的数据
const response = [...1000];
TaskSlice.init(100, i => datalist.push({ name: i }));
```
