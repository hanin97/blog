### 使用GitLab和PicGo创建图床

<br>

**ps**：为什么使用GitLab呢？因为我用GitHub老是上传失败。

---
1. 在GitLab中建立自己的Group `group-name`，再在Group下建立Project `project-name`；
2. 下载并安装[PicGo](https://github.com/Molunerfinn/PicGo/releases)；
3. 配置PicGo，因为PicGo本身并不支持GitLab作为图床，需要安装插件，如下图：
   ![为PicGo安装GitLab插件](http://lcipm.com/Jineng/picture-bed/uploads/5c701837c05f415cd97156a231179b8f/installGitLab.png)
4. 点击左侧菜单栏`图床设置--GitLab图床`，按要求填写，如下图，其中`Token`需要在GitLab账户中的`Setting--Access Tokens`生成。
   ![配置GitLab图床](http://lcipm.com/Jineng/picture-bed/uploads/adeb9dfb360e744a3ae15a2c0b81ed69/setGitLabPicBed.png)
5. 大功告成，以后就直接`截图-->ctrl+shift+p（快捷键可修改）`就可以将截图上传至GitLab图床了，再`ctrl+c`就可以粘贴图片链接至markdown（或html等，可设置）中了。
