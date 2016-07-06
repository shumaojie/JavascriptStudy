#Javascript 学习笔记#
##注意点##
1. 变量命名是 var , 弱变量
2. <script>   书写代码    </script>
3. 所有的变量包括函数都是一个对象








##常用点##
1. 页面关闭  window.close()
2. 字符串替换  items[i]=items[i].replace(/被替换的字符串，没有双冒号/g,"替换成的字符串")
3. 把mysql通过php读出，然后利用javascript转换为json
4. 通过URL来传递参数,JS通过函数来实现参数的获取
function GetQueryString(name) {
	var reg = new RegExp("(^|&)" + name + "=([^&]*)(&|$)");
	var r = window.location.search.substr(1).match(reg);
	return (r!=null)? decodeURI(r[2]):null;
}
5. 如何在<script></script>来运行程序
6. click事件在谷歌浏览器和IE浏览器中的区别，事件的触发与响应
7. $.get少用，推荐使用$.post
8. ajax来进行前后端交互
9. 闭包程序 
<script>
    //优势是防止参数内存泄漏
	$(function()
	{
		
     //to do
		
	});
</script>
10. 

