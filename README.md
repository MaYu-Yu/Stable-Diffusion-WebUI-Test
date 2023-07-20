# Stable Diffusion WebUI 教學

* ## 架設環境
    ### 測試環境 Windows 11 22H2
    ### 克隆 stable-diffusion-webui主程式
    git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui
    ### 安裝使用 NVidia GPU CUDA核心
    1. Download `sd.webui.zip` from [v1.0.0-pre](https://github.com/AUTOMATIC1111/stable-diffusion-webui/releases/tag/v1.0.0-pre) and extract it's contents.
    2. Run `update.bat`.
    3. Run `run.bat`.
    > For more details see [Install-and-Run-on-NVidia-GPUs](https://github.com/AUTOMATIC1111/stable-diffusion-webui/wiki/Install-and-Run-on-NVidia-GPUs)
    ### 安裝於Windows
    1. Install [Python 3.10.6](https://www.python.org/downloads/release/python-3106/) (Newer version of Python does not support torch), checking "Add Python to PATH".
    2. Install [git](https://git-scm.com/download/win).
    3. Download the stable-diffusion-webui repository, for example by running `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git`.
    4. Run `webui-user.bat` from Windows Explorer as normal, non-administrator, user.
    ### webui-user.bat執行完畢後上方會有URL， EX: http://127.0.0.1:7860/ 開啟網頁即可使用
    ### 安裝模組
    - 可以先下載現在熱門的 [AbyssOrangeMix2](https://civitai.com/models/4437/abyssorangemix2-sfwsoft-nsfw) 作為練習
    - 也可以從 [civitai](https://civitai.com/) 來找自己喜歡的圖片類型之模組
    - 下載完後，將模組放到 \stable-diffusion-webui\models\Stable-diffusion 中
    - 左上角Stable Diffusion checkpoint 選擇使用模組
* ## Prompt參數類型

* ## 架設環境 

* ## 參考網站
- Stable Diffusion - https://github.com/CompVis/stable-diffusion, https://github.com/CompVis/taming-transformers, https://github.com/AUTOMATIC1111/stable-diffusion-webui
- Nenly同学 B站第一套Stable Diffusion系统课程，来了！ - https://www.bilibili.com/video/BV12X4y1r7QB/?spm_id_from=333.999.0.0&vd_source=aacdb5a29cde586321259cd6b3bafda0
- 绘画指南 stable diffusion webui (SD webui)如何设置与使用 - https://www.tjsky.net/tutorial/488