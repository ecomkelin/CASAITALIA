## [返回目录](../readme.md)  

### 4. 产品架构  &nbsp;&nbsp;&nbsp;&nbsp; [<<上一章（产品简介）](./3_Description.md) [下一章（详细功能）>>](./5_Function.md)
##### 公司系统采用分层架构

#### 4.1 信息结构图
  ![信息机构图](./4_Img/1.jpg)
#### 4.2 产品结构图
  ![产品结构图](./4_Img/2.jpg)
---

```flow
st=>start: Start
e=>end
op=>operation: My Operation
cond=>condition: Yes or No?

st->op->cond
cond(yes)->e
cond(no)->op
