## IE11 strict 模式下不允许一个属性有多个定义  

react项目中，在IE11上运行，报了**strict 模式下不允许一个属性有多个定义**这个错误，但在别的浏览器就没事   
>![](./images/IE11严格模式报错.png)   


找了好久才发现，这是因为在<AntdSelect>组件中定义了两次属性style  
>![](./images/IE11严格模式报错代码.png)   