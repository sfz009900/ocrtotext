# ocrtotext
# 使用windows自带的Windows.Media.Ocr进行截图翻译,可一键复制原文,译文,和覆盖译文到截图时的地方

支持ollama,openai,自定义接口和翻译提示词,可以管理多套提示词比如"推特专用","普通模式"
![image](https://github.com/user-attachments/assets/cb3e7f0b-3979-464b-8fe7-1538285b0ff5)

# 和使用的translators库里的一大堆的翻译免费翻译接口
https://github.com/UlionTse/translators
![image](https://github.com/user-attachments/assets/8d62f595-88b4-4c19-8230-442bf0203fb5)

# 这是使用有道翻译的免费截图的大概演示效果:


https://github.com/user-attachments/assets/d6c92e76-5d9a-4e1a-93e5-069e13329407

# 自带一个gemma27b的免费测试服务器,可以选择"推特模式"和"普通模式",每个IP每天只能翻译30次
![image](https://github.com/user-attachments/assets/ec6175ca-e497-47b3-9e4e-8e63457628d6)

# 这是推特模式的翻译风格效果
原文:
![image](https://github.com/user-attachments/assets/f458d469-3e0b-44bf-ad32-2113dc26a6fa)

译文:
![image](https://github.com/user-attachments/assets/138d9b51-ee89-4a05-85ff-4ecc9231225e)

# 截图翻译的效果对比:
原文:
![image](https://github.com/user-attachments/assets/118b0ed4-2ee5-4aff-8d56-ef24206cac10)

译文:
![image](https://github.com/user-attachments/assets/d4ef221e-6f24-4892-8298-4668420dbd44)


# 注意事项,
# 1:如果直接运行报错,就去这里增加个这个英文
![image](https://github.com/user-attachments/assets/519cb2f8-a7ca-45f7-8b96-53ef1a5de7b9)
# 2:现在只是玩具版,可能很多地方不稳定和不完善
# 3:后面有精力再弄个启动EXE后本地开个5000端口的"沉浸式翻译"中转接口,比如http://127.0.0.1:5000/translate直接放到沉浸式翻译就可以用gemma27b的推特模式和普通模式啥的
