1.安装 Python 3.10.6 版，把其他版卸载
2.添加环境变量
    系统变量里找 PATH 添加 C:\Users\DELL\AppData\Local\Programs\Python\Python310

3.用清华源安装，遇到 诸如 gfpgan、clip 安装不成功，可以试下如下代码

D:\stable-diffusion-webui\venv\Scripts\python.exe -m pip install clip -i http://pypi.douban.com/simple/ --trusted-host pypi.douban.com

pip install gfpgan -i http://pypi.douban.com/simple/ --trusted-host pypi.douban.com
pip install clip -i http://pypi.douban.com/simple/ --trusted-host pypi.douban.com

git config --global --add safe.directory D:/stable-diffusion-webui/repositories/stable-diffusion-stability-ai
git config --global --add safe.directory D:/stable-diffusion-webui/repositories/k-diffusion

4.要把下载好的模型文件 v1-5-pruned-emaonly.ckpt 放到 D:\stable-diffusion-webui\models\Stable-diffusion 文件夹里


===========================
https://github.com/lkwq007/stablediffusion-infinity/blob/master/docs/setup_guide.md#windows
stablediffusion-infinity/docs/setup_guide.md

If you use AMD GPUs, you need to install the ONNX runtime pip install onnxruntime-directml (only works with the stablediffusion-inpainting model, untested on AMD devices).


资源：
模型下载站：https://civitai.com/
