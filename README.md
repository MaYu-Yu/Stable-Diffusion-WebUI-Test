# Stable Diffusion WebUI 教學

* ## 架設環境
    ### 測試環境 
    - Windows 11 22H2
    - Python 3.9.13
    ### 克隆 stable-diffusion-webui主程式
    - git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui
    ### 安裝於Windows
    - Install [Python 3.10.6](https://www.python.org/downloads/release/python-3106/) (Newer version of Python does not support torch), checking "Add Python to PATH".
    - Install [git](https://git-scm.com/download/win).
    - Download the stable-diffusion-webui repository, for example by running `git clone https://github.com/AUTOMATIC1111/stable-diffusion-webui.git`.
    - Run `webui-user.bat` from Windows Explorer as normal, non-administrator, user.
    ### webui-user.bat執行完畢後上方會有URL， http://127.0.0.1:7860/ (開啟網站都使用這個bat)
        ![image](https://github.com/MaYu-Yu/Stable-Diffusion-WebUI-Test/blob/master/readme_img/1.png)
    ### 安裝模組
    - [civitai](https://civitai.com/) 網站來找自己喜歡的圖片類型之模組
        - 按下download下載模組 
        - 從civitai的圖片按下info中的Copy Generation Data複製該張圖片參數
            ![image](https://github.com/MaYu-Yu/Stable-Diffusion-WebUI-Test/blob/master/readme_img/2.png)
        - 到WebUI的左下箭頭即可貼上完整參數
            ![image](https://github.com/MaYu-Yu/Stable-Diffusion-WebUI-Test/blob/master/readme_img/3.png)
    - 熱門動漫角色模組 [AbyssOrangeMix2](https://civitai.com/models/4437/abyssorangemix2-sfwsoft-nsfw) [AnythingElse V4](https://civitai.com/models/4855?modelVersionId=5581)
    - 下載完後，將模組放到 \stable-diffusion-webui\models\Stable-diffusion 中
    - 左上角Stable Diffusion checkpoint 選擇使用模組
        ![image](https://github.com/MaYu-Yu/Stable-Diffusion-WebUI-Test/blob/master/readme_img/4.png)
* ## Prompt參考範本
    - prompt:
        absurdres,1girl, small breasts(1.2), parted lips, blush, makeup, light smile,glow, thighs,
        school uniform, classroom, light rays, 
        (masterpiece), wallpaper,UHD
    - negative prompt:
        (worst quality:1.2), (low quality:1.2), (lowres:1.1), (monochrome:1.1), (greyscale), multiple views, comic, sketch, animal ears, pointy ears, blurry, transparent, see-through, zombie, (interlocked fingers:1.2), bad anatomy, bad hands, text, error, missing fingers, extra digit, fewer digits, cropped, jpeg artifacts, signature, watermark, username, artist name

* ## 參考網站
- Stable Diffusion - https://github.com/CompVis/stable-diffusion, https://github.com/CompVis/taming-transformers, https://github.com/AUTOMATIC1111/stable-diffusion-webui
- Nenly同学 B站第一套Stable Diffusion系统课程，来了！ - https://www.bilibili.com/video/BV12X4y1r7QB/?spm_id_from=333.999.0.0&vd_source=aacdb5a29cde586321259cd6b3bafda0
- 绘画指南 stable diffusion webui (SD webui)如何设置与使用 - https://www.tjsky.net/tutorial/488
- 使用ChatGPT生成Stable Diffusion prompt(提示词) - https://zhuanlan.zhihu.com/p/634833836
