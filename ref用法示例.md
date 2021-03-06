* **需求为：react项目中，点击复选框，在底部添加一栏；取消选中复选框，删除对应的一栏；在底部点击删除按钮，删除此栏同时取消上方复选框选中状态。**  
>![案例](./images/ref.png)    

* **思路：复选框部分作为子组件**  
>![复选框](./images/复选框.png)  

* **checked的值由state中的checkbox值决定，而父组件中，点击删除按钮后要执行子组件中的函数以改变子组件state中的值，此时就需要用到ref。**    
>![子组件中的函数](./images/子组件中的函数.png)   

* **方法为：在父组件引用子组件时，用下面这个语句：**    
>![ref](./images/ref1.png)  

* **这样子组件中的值就可以作为父组件中operationalCheckBoxItems对象中的属性，在父组件中打印this.operationalCheckBoxItems的结果为：**    
>![打印结果](./images/打印.png)   

* **删除功能：**    
>![删除功能](./images/用法.png)  

