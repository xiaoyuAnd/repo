# 自我介绍
## 主要资料：
姓名：张伯利     
性别：男   
年龄：23   
现居：上海（老家：山东）   
## 学习经历
* 18年开始接触前端，当时在学校上大三，断断续续的学到了20年，发现自己还是啥都不会，自学太浪费时间了，没有人指导。
* 19年从B站上开始了解饥人谷，从模拟前端面试开始，逐渐开始了解方方。
* 20年报名饥人谷，开始了系统的前端学习，学习进行中~~~~~  
## 代码展示
### 数组去重
```javascript
function unique(arr){   
  var newArr = [];
   for (var i=0; i<arr.length;i++){
    if(newArr.indexOf(arr[i]) == -1){
        newArr.push(arr[i])
    }
   }
  return newArr;
}
var arr = [23,24,13,3,0,24,23,8];
unique(arr);
```
