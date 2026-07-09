# 前言

欢迎来到本毕业设计分享，本次分享的项目是基于Spring Boot和Vue的毕业论文管理系统。该项目利用Java开发，使用MySQL数据库进行数据存储，配备完整的前端和后端代码、文档报告以及代码讲解，旨在帮助同学们更好地完成毕业设计。

# 内容介绍

本项目主要针对毕业论文管理工作，实现了学生、导师、管理员等角色的权限管理，包含论文选题、分配导师、提交论文、审核论文等功能。系统采用前后端分离的设计模式，前端负责展示和交互，后端负责数据处理和存储。通过本项目的实践，你可以了解到如何使用Spring Boot和Vue搭建一个完整的Web应用。

# 技术介绍

## 语言：Java
## 使用框架：Spring Boot
## 前端技术：JS、Vue、css3
## 开发工具：IDEA/Eclipse
## 数据库：MySQL 5.7/8.0
## 数据库管理工具：phpstudy/Navicat
## JDK版本：jdk1.8
## Maven：apache-maven 3.8.1-bin
## 前端环境：Node.Js 12\14\16

# 核心代码

以下为项目中的一部分核心代码，展示了如何使用Spring Boot实现论文管理的接口：

```java
@RestController
@RequestMapping("/api/paper")
public class PaperController {

    @Autowired
    private PaperService paperService;

    @PostMapping("/submit")
    public ResponseEntity<?> submitPaper(@RequestBody Paper paper) {
        // 保存论文
        paperService.save(paper);
        return new ResponseEntity<>(HttpStatus.OK);
    }

    @GetMapping("/list")
    public ResponseEntity<List<Paper>> listPapers() {
        // 查询论文列表
        List<Paper> papers = paperService.list();
        return new ResponseEntity<>(papers, HttpStatus.OK);
    }
}
```

# 免费源码获取

```
5000套系统成品在线演示视频，复制到流浪器： 
```
```
https://www.yuque.com/yuqueyonghux32e1j/kxdc9g/ad8oz3bamkxmay0e#Cxun
```
![下载](https://img12.360buyimg.com/ddimg/jfs/t1/339687/11/1349/28408/68ad865fF412d7877/adaa650483a100f2.jpg)

# 项目截图

![封面图片](https://img14.360buyimg.com/ddimg/jfs/t1/317986/29/24991/149860/689de7f1F27d53b2f/adf2df64f7f903c9.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/313231/25/26057/81377/689de7cfF66e841e0/4c93a621536bd898.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/313639/31/26486/63867/689de7cfF6e992b0c/da1bd8d5e16a2dc0.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/313357/4/26101/48526/689de7d0Fd8515596/0b74ebaa2a6d0391.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/290674/28/21618/77671/689de7cfFabea74f7/53c19832b9812931.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/327239/36/4659/75269/689de7d0F0564e2b2/3248f2ab71f9a114.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/308154/27/25708/65310/689de7d1Fb05d98fe/6c95c55fffc647c7.jpg)

![介绍图片](https://img10.360buyimg.com/ddimg/jfs/t1/291612/1/18973/82094/689de7d1Fc5ffe475/fce5af7d073bdf2a.jpg)

![介绍图片](https://img14.360buyimg.com/ddimg/jfs/t1/324129/20/4595/43688/689de7d1F0bd4ed2d/1375355f73ed10dc.jpg)

![介绍图片](https://img13.360buyimg.com/ddimg/jfs/t1/325475/36/4576/41489/689de7d2F477d8a37/2c9d8d8b48db9312.jpg)


## 万字文档
![文档介绍](https://img14.360buyimg.com/ddimg/jfs/t1/338393/1/3576/156947/68b1ad0cF74dc525c/ff9cd6c574295685.jpg)
