### 纯CSS3实现checkbox的switch效果
- 首先是因为语龙桑【我】在面试中被问到了这个题，所以才找了相关资料琢磨写了一下
- 主色调采用了美团绿🌚
- [线上效果](https://poisonallong.github.io/css3-switch-checkbox/css3-switch-checkbox.html)
- 主要的知识点其实是应用了CSS3的`:checked`伪类选择器</br>它表示任何处于选中状态的radio(`<input type="radio">`), checkbox (`<input type="checkbox">`) 或(`"select"`) 元素中的option HTML元素("option")) 。用户通过点击元素或选择其他的值，可以改变该元素的 :checked 状态，并:checked属性赋给一个新的对象(例如其他的option值)。</br>具体的内容可以参考[MDM web docs](https://developer.mozilla.org/zh-CN/docs/Web/CSS/:checked)上的资料
- 关于兼容性问题目前只是测试了Chrome 等有时间再来填这个坑

