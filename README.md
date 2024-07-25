
# 这个项目是关于什么的？
## 这个项目提供了一个精心整理的DLL劫持候选列表，从以下杀毒软件中提取


![下载 (2)](https://github.com/user-attachments/assets/e3dea0f4-63f6-461e-979e-ba8009afa9e5)
![下载 (1)](https://github.com/user-attachments/assets/876ffe57-3fa3-477d-9e65-ec87181b5c23)
![下载](https://github.com/user-attachments/assets/88751c56-7a4a-447e-9de3-55303b508c8e)
![下载 (10)](https://github.com/user-attachments/assets/0d2fea58-870b-442d-a4c0-1d29a428179d)
![下载 (9)](https://github.com/user-attachments/assets/1d034b46-2d4b-4a94-bc64-7279f4aac578)
![下载 (2)](https://github.com/user-attachments/assets/9271706d-9ced-4198-b998-7486ad356938)
![下载 (8)](https://github.com/user-attachments/assets/0f50275f-e231-43a8-baca-69a25f3adb07)
![下载 (7)](https://github.com/user-attachments/assets/35598b21-f6d0-4cbc-ab6b-dddd5810eb64)
![下载 (6)](https://github.com/user-attachments/assets/78ce8812-f108-47eb-8d53-586fad8d1285)
![下载 (1)](https://github.com/user-attachments/assets/943aa846-ccf6-44fc-bcad-1dd079a20029)
![下载 (5)](https://github.com/user-attachments/assets/9d8fab59-4460-4b17-88d1-6d184f769dcc)
![下载 (4)](https://github.com/user-attachments/assets/902f4bdc-b3e0-4cc3-86d8-6cf29891b4fb)
![下载](https://github.com/user-attachments/assets/132fd50c-6343-4f38-a322-3fa491e8c7a3)
![下载 (3)](https://github.com/user-attachments/assets/c31f7e90-d5a9-4cb5-801c-31b8bd6a127c)




### DLL（Dynamic Link Library）劫持是一种常见的攻击技术，攻击者通过替换或篡改合法的DLL文件，以便在目标系统上执行恶意代码。DLL劫持的原理是利用应用程序在加载DLL时的搜索顺序漏洞，使应用程序加载攻击者提供的恶意DLL文件，而不是合法的DLL文件。

### DLL劫持的类型主要包括以下几种：

## 1.预加载攻击（Preloading Attack）：
攻击者在应用程序的启动目录或系统搜索路径中放置恶意DLL，利用应用程序在加载DLL时优先搜索这些路径的特性，使应用程序加载恶意DLL。

## 2.路径劫持（Path Hijacking）：
攻击者通过修改系统环境变量（如PATH变量），使应用程序在加载DLL时从攻击者控制的路径中加载恶意DLL。

## 3.清单劫持（Manifest Hijacking）：
某些应用程序通过清单文件（Manifest）指定需要加载的DLL文件及其版本。攻击者可以篡改清单文件，使应用程序加载恶意DLL。

## 4.符号链接攻击（Symbolic Link Attack）：
攻击者在文件系统中创建符号链接，使应用程序加载恶意DLL。符号链接可以指向攻击者控制的文件或目录，从而实现劫持。

## 5.注册表劫持（Registry Hijacking）：
Windows系统通过注册表配置某些应用程序需要加载的DLL文件路径。攻击者可以修改注册表键值，使应用程序加载恶意DLL。

## 6.依赖关系劫持（Dependency Hijacking）：
应用程序依赖于其他第三方DLL文件，如果这些DLL文件本身依赖于其他DLL，攻击者可以通过替换这些依赖DLL来劫持执行流程。

## 7.Side-loading攻击：
攻击者在合法应用程序目录中放置恶意DLL，利用应用程序自动加载目录中存在的同名DLL的特性，使应用程序加载并执行恶意代码。

## 预防DLL劫持的措施包括：

1.确保应用程序目录的安全性，避免未经授权的用户能够写入或修改。
2.使用完整路径加载DLL文件，而不是依赖于系统搜索路径。
3启用和配置Windows的安全特性，如AppLocker或Device Guard，限制未签名或未批准的代码执行。
4.定期检查和更新系统与应用程序，确保所有软件都是最新版本，修复已知的漏洞。


# 支持项目
如果您觉得这个项目有用，并愿意支持我的工作，您可以通过比特币捐款：

## 比特币地址：bc1qzwd50xcndq3n52d83yy3uwxpxzmhadjsruyhvg  
##             bc1qy2csn85w52y0m0x809uukjef93hg5j4jec5wna

非常感谢您的支持！


# Support the Project
If you find this project helpful and would like to support my work, you can donate via Bitcoin and help me buy a cup of coffee:

## Bitcoin Address: bc1qzwd50xcndq3n52d83yy3uwxpxzmhadjsruyhvg    
##                  bc1qy2csn85w52y0m0x809uukjef93hg5j4jec5wna

Thank you very much for your support!











