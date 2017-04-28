<h1>EX02</h1>
在第一章的基础上添加了Servlet容器


问题：
访问Servlet容器出现问题，无法找到PrimitieServlet这个类  
原因：  
在浏览器访问时自动对输入的url进行了大小写转换，例如我
输入的是http://localhost:8080/servlet/PrimitiveServlet但自动
切换成了http://localhost:8080/servlet/Primitiveservlet，因此
我直接把类的名字改成了Primitiveservlet