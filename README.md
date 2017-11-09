javascript 图片查看器
用原生js写的图片查看器， 可旋转、放大、上一张、下一张和拖拽.无需引用jquery.
参数值需要传入 图片数组、跟当前点击的图片即可


<div id="imgView"></div>
var options = {

    dataList: dataList,   // 图片数组
  
    currentSrc: src       // 当前要显示的图片
  
};

ImgView("imgView", options);
