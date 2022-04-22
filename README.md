# countdown1
分钟倒计时元素，用于自定义多少分钟进行倒计时显示<br>
普通属性<br>
data-countdownid	设置分钟倒计时元素的唯一id值	sddd<br>
输出属性<br>
data-x-counttime	设置分钟倒计时元素输出总秒数	300<br>
# 注意事项
1、分钟倒计时元素的发出事件名称：<br>
①、分钟倒计时元素倒计时还剩一分钟发出的事件：事件名称为 counttime<br>
②、分钟倒计时元素倒计时结束发出的事件：事件名称为 counttimeend<br>
2、找到元素的div 设置分钟倒计时元素，设置元素的唯一id值；<br>
3、该元素是分钟倒计时，直接在元素上设置分钟数，如5分钟，则设置05分00秒，120分钟则设置120分钟00秒；<br>
4、可以在元素外设置按钮，每个按钮都设置对应的class名称；如：开始按钮( countdownstart)、暂停按钮( countdownpause)、继续按钮( countdowngoon)、结束按钮( countdownstop);<br>
5、如果控制显示隐藏可以通过给每个按钮添加一个hide类，然后通过显示添加类删除类来控制页面显示按钮显示问题；<br>
