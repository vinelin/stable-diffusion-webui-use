# 本体
stable diffusion webui 本体 
 链接：https://pan.baidu.com/s/1c-nB2KRt6bDE67cRmhtMHQ?pwd=88y3 
提取码：88y3  

源：https://github.com/AUTOMATIC1111/stable-diffusion-webui

# 升级补丁（仅百度云下载需要）
放入 根目录modules文件夹
sd_models.py

# 启动器
放入根目录
链接：https://pan.baidu.com/s/1A7F_v-8fb30aKJVgePzxEg?pwd=e1pn 
提取码：e1pn

使用启动器启动

# 模型安装
https://civitai.com/

如何使用各种模型具体教程：https://github.com/civitai/civitai/wiki/How-to-use-models
下面是简述
## 类型cpkt  模型

放入models\Stable-diffusion
## 名字中带有vae 美化模型
放入models\VAE

## 类型safetensors lora模型 类似于一个插件
lora文件
分两种情况
### 百度云旧版
1. 确保已经安装 [Additional Networks extension](https://github.com/kohya-ss/sd-webui-additional-networks), 可以在extensions标签中确认。
2. 安装好后重启Stable-diffusion
3. 下载LoRA模型文件
4. 放在 extensions/sd-webui-additional-networks/models/lora 文件夹
5. 在 txt2img or img2img 标签, 下拉  Additional Networks 在页面最下方区域
6. 确保已经启用
7. 设置Model 1为你下载的lora模型
8. 设置权重1到0.85作为一个好的开始，然后根据需要调整

### 去github自行下载新版
1. 已经整合这个功能
2. 下载lora模型
3. 放在 models/lora 文件夹
4. Click on the show extra networks button under the Generate button (purple icon)
5. Go to the Lora tab and refresh if needed
6. Click on the one you want to apply, it will be added in the prompt
7. Make sure to adjust the weight, by default it's :1 which is usually to high

## 类型pt
放在embeddings文件夹

## 注意
可以查看是否安装成功
![image](https://user-images.githubusercontent.com/28559480/220238178-1abf455e-3449-490a-9982-fc45be6e8a77.png)

