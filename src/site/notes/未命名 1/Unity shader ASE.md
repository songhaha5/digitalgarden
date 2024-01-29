---
{"dg-publish":true,"permalink":"/未命名 1/Unity shader ASE/"}
---


# 1遮罩

## 材质设置
创建文件夹：图片、材质
![Pasted image 20240129141811.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129141811.png)
导入图片（Q群文件）：
![Pasted image 20240129133522.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129133522.png)
材质：创建shader
![Pasted image 20240129133626.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129133626.png)
接入界面：创建节点
![Pasted image 20240129133713.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129133713.png)
快捷键：按住T，再点击鼠标左键使用 
- T：贴图采样（Texture Sample 蓝色节点）
	- 更改名称
	- ![Pasted image 20240129134514.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134514.png)
	- ![Pasted image 20240129134522.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134522.png)
- U：UV采样（Texture Coordinates 橙色节点）
	- 更改uv节点映射
	- ![Pasted image 20240129134411.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134411.png)
	- ![Pasted image 20240129134355.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134355.png)
- 2：向量节点（Vector 绿色节点），控制贴图流动速度
- p：显示图片
- color（记得更改颜色）：鼠标右击输入![Pasted image 20240129134100.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134100.png)找Color【5】
- M：Multiply节点
更改设置
![Pasted image 20240129134227.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134227.png)
- ZwriteMode：off
- BlendRGB：Additive
更改Tags-type-Transparent
![Pasted image 20240129135450.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129135450.png)
右击创建材质
![Pasted image 20240129135617.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129135617.png)



## 项目设置
创建空物体，重命名post，并添加组件
Profile初始为空，需点击new
![Pasted image 20240129134844.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134844.png)
更改layer层
![Pasted image 20240129134701.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134701.png)
![Pasted image 20240129134652.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129134652.png)

摄像机添加组件，并更改Layer为post
![Pasted image 20240129135020.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129135020.png)
创建quad，将材质赋予
![Pasted image 20240129135350.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129135350.png)
如果需要面板显示，更改Type
![Pasted image 20240129135735.png](/img/user/%E6%9C%AA%E5%91%BD%E5%90%8D%201/Pasted%20image%2020240129135735.png)



# 2硬边溶解

更改项目设置
![](https://55-1324139197.cos.ap-beijing.myqcloud.com/pictures/20240129203210.png)

