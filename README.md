# Search-skills-of-GitHub-project

一些github上开源项目搜索的小技巧    
首先来看一下github上的一般项目结构：项目名、描述、源代码、readme文件，这些都可以作为搜索项    


## github如何找开源项目？  
in:搜索字段 项目名 限制条件    

## 单条件查找
名字中包含spring boot的项目:    
1、in:name springboot   	
2、in:readme springboot  

## 多条件查找,只需在后追加条件即可  
1、名字中包含springboot且start大于3000    
in:name spring boot stars:>3000   	

2、名字中包含sprintboot且fork数大于3000   
in:name spring boot fork:>3000    

3、readme中包含springboot且fork>3000  
in:readme spring boot fork:>3000   

4、description中包含微服务，用java编写，且2019-9-30后有更新的  
in:description 微服务 language:java pushed:>2019-09-30   


stars:>1000 star>1000  
forks:>1000 fork>1000  
pushed:>2019-09-01 2019年9月1日后有更新的  
language:java 用Java编写的项目  
