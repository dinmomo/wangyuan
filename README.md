## wangyuan.github.io
## 50个前端小项目跟踪做
## 每天做一个争取做完，早日学到vue和react
# day0

CSS:弹性盒子布局中的flex属性:让所有弹性盒模型对象的子元素都有相同的长度，且忽略它们内部的内容。

JavaScript:利用[].filter.call()方法可快速实现简单的选项卡切换。如上述示例源码:
<js>
const panelItems = document.querySelectorAll(".container > .panel");
panelItems.forEach(item => {
    item.addEventListener('click',() => {
        [].filter.call(item.parentElement.children,el => el !== item).forEach(el => el.classList.remove('active'));
        item.classList.add('active')
    });
});
</js>
