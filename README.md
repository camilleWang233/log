8.11
1.dropevent.html
Document: drop event
事件句柄 : addEventListener(event, function, useCapture)
event : 不可缺省; 类型->字符串; 作用->指定事件名(不要使用 "on" 前缀)
function : 不可缺省; 类型->普通函数; 作用->指定要事件触发时执行的函数
useCapture : 可缺省; 类型->boolean; 作用->指定事件是否在捕获或冒泡阶段执行(true代表捕获阶段,false(默认)代表冒泡阶段),

Js事件流(捕获阶段-目标阶段-冒泡阶段)

2.回调函数（recall function）