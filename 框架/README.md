## Java框架

### Spring In Action
#### Spring Security
1、entry-point-ref
配置一个AuthenticationEntryPoint的实现类. 这个类的作用是, 当一个未授权的用户请求非公有资源时, 这个类的commence方法将会被调用, 定义如何处理这个请求.常用的有LoginUrlAuthenticationEntryPoint实现类, 把请求重定向到登录页面. 也可以自定义一个实现类, 处理具体的操作, 如记录日志, 返回到自定义的403页面等等.

2、