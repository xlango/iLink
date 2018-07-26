1.项目管理和综合工具:maven<br>
(1)Maven安装和配置:参考https://www.yiibai.com/maven/maven_environment_setup.html<br>
(2)Eclipse和IDEA配置Maven<br>

2.Spring版本：5.0.7<br>
3.MVC：Spring MVC配置<br>
(1)jar包:spring-webmvc.jar<br>
(2)web.xml配置SpringMVC监听类：org.springframework.web.context.ContextLoaderListener<br>
(3)SpringMVC核心配置文件：spring-mvc.xml  配置自动扫描的包、配置视图解析器 如何把 handler方法返回值解析为实际的物理视图、配置静态资源映射静态资源交给默认的Servlet、配置 mvc:annotation-driven标签开启注解<br>
(4)@RestController =@Controller+@ResponseBody<br>
(5)@RequestMapping("/")<br>
(6)页面跳转使用 ModelAndView<br>

4.实现文件上传下载：参考：https://blog.csdn.net/jronzhang/article/details/61210700<br>
(1)相关jar包：commons-fileupload、commons-io、commons-codec<br>
(2)Spring核心文件配置：bean  multipartResolver   maxUploadSize设置最大上传文件大小       defaultEncoding设置编码<br>
(3)下载测试url：http://localhost:8080/iLink/file/down