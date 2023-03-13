## 云原生K8s全栈架构师实战文档

## K8s技术QQ交流群：612388919
## 作者QQ：727585266

## 书籍配套视频：

**提供免费更新、免费技术问答、免费岗位推荐、受益终身【平均月薪25K】**

	腾讯：
	    K8s全栈架构师：https://ke.qq.com/course/2738602
	    K8s管理员认证CKA：https://ke.qq.com/course/3382340?tuin=2b5e11f2
	    K8s安全专家CKS：https://ke.qq.com/course/4161957?tuin=2b5e11f2
	    CKA+架构师：https://ke.qq.com/course/package/38982?tuin=2b5e11f2
	    超级套购：https://ke.qq.com/course/package/41755?tuin=2b5e11f2
	51CTO：
	    全栈架构师：https://edu.51cto.com/course/23845.html
	    K8s管理员认证CKA：https://edu.51cto.com/course/27103.html
	    K8s安全专家CKS：https://edu.51cto.com/course/29792.html 
	    CKA+架构师：https://edu.51cto.com/topic/4973.html
	    超级套购：https://edu.51cto.com/topic/5174.html


# 勘误
### 非常抱歉给大家带来的不便，书中的错误更正如下：
1. 182页 9.3.2小节 第一个`kubectl run`命令改为`kubectl create deployment nginx-server`，错误原因：由于版本问题，`kubectl run`变为了创建Pod，创建Deployment需要用`kubectl create deployment`。
2. 77页
````
successThreshold: 1 # 表示检查成功1次表示就绪
failureThreshold: 2 # 检测失败2次表示未就绪
````
3. 71页 Node节点描述的Docker Engine: 负责对容器的管理，写成了负载对容器的管理
