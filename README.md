
## 个人博客开发 
[个人博客](https://nbjqr.xyz)开发mini框架，基于node插件一大堆又怕数据丢失，就放在github上了。

### 一：安装软件
* 安装 `git` 
* 安装 `nodejs`
### 二：安装node插件
1. 全局安装hexo插件 `npm install hexo-cli -g`
2. 下载git源码到  `git clone https://github.com/caojiurui/blog_dev.git 目录`
3. `cd 目录`，解压 `node_modules` 到当前目录
### 三：本地调试博客页面
* 清空缓存 `hexo clean`
* 调试启动服务 `hexo s --debug`
### 四：发布到github
* 生产静态页面 `hexo g`
* 推送到github `hexo d`
	> git的配置在`_config.yml` 的 `deploy` 属性

#### 备注
* 假如部署到github主页上，项目名称为 `<username>.github.io`
* 假如需要配置域名，域名直接配置到 `/source/CNAME` 文件，不带协议前缀

---
##### 参考文档：
1. Hexo简介(by 墨飞_Max)：[https://www.cnblogs.com/mophy/p/7016331.html](https://www.cnblogs.com/mophy/p/7016331.html)
2. Hexo简洁主题推荐 (by 屠城9441) [https://www.haomwei.com/technology/maupassant-hexo.html](https://www.haomwei.com/technology/maupassant-hexo.html)

<br/>

**[我的博客：树洞X](https://nbjqr.xyz)**
