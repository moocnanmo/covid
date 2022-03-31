# 仿丁香医生实时疫情数据项目

### 下载依赖

```javascript
npm install
```

### 启动项目

``` javascript
npm run dev
```

### 项目介绍

##### 该项目借鉴【丁香医生实时疫情数据页面】的布局，实现了疫情信息可视化展示的功能

api来源：天行数据、腾讯、丁香医生

技术栈：vue+axios+vant+echarts+swiper

### 技术点

1.组件拆分

2.封装了<svg-icon>组件

3.移动端适配方案

4.配置了公共的api文档，易于维护

5.echarts封装了折线图、地图映射插件

6.当设备大小发生变化时，如切换屏幕，echarts图表宽度自适应调整

7.封装了table组件，可支持树形数据，表列头实现吸顶效果

8.性能优化：使用节流和防抖函数

### 部分效果截图

![在这里插入图片描述](https://img-blog.csdnimg.cn/3380bacc9c334c8393adc626df3c60b6.png#pic_center)
