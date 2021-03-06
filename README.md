# API_ML_AI期末项目——Sceneing APP

#### “20x20”ppt 如果无法下载，可以点击以下链接保存至百度云盘进行查看，谢谢！
#### 链接：https://pan.baidu.com/s/1nOsbf9NnCODhXM3waLeQLw 密码：sr1w

## 产品概况
| 发布日期 | 12/10/2019 |
| --------   | -----  |
| 项目名称 | Sceneing | 
| 文件状态 | 完善中 | 
| 文件主人 | 徐嘉慧 | 
| 领头设计师  | 徐嘉慧 | 
| 领头开发者  | 徐嘉慧 | 
| 领头测试者  | 徐嘉慧 | 

## 介绍

这是一款为有拍摄摄像需求的群体提供挑选拍摄场景帮助服务的app。

## 一、MRD（略写）

#### 目标用户

有拍摄和摄像目的，并且有特定场景需求的群体。

#### 市场分析
随着人们经济条件的改善和生活水平的提高，现在很多小型影视拍摄团队，亦或是个人，都存在着想要寻找预期场景的需求，达到预期效果的目的。但由于资金和资源有限，无法实现高成本的效果，奈何只能在各大搜索引擎上寻求帮助。（如下图）

![需求.png](https://upload-images.jianshu.io/upload_images/9400767-c9a8e7e06e788df9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![需求1.png](https://upload-images.jianshu.io/upload_images/9400767-51645a5ac1a72ca0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


这种情况下，一要求发帖者描述准确，二要求其指定的区域条件相对较好，确实存在其描述的场景，三要求广大网友集思广益并且有建设性建议，以上三条条件缺一不可，故绝大多数情况下寻求无果。

#### 竞品分析

其实不仅是查找相似场景，现如今很多查找相似商品、文章等已经应用在方方面面。例如：电商平台的“猜你喜欢”功能，它根据用户历史行为、标签、社交以及物品属性等，通过大数据分析，计算用户可能感兴趣的物品列表，做个性化推荐；再例如……

目前市面上与我们项目相似的针对型产品还没有，但有相似的服务。例如：[百度识图](https://graph.baidu.com/pcpage/index?tpl_from=pc) 该服务的价值主张是“百度识图，鉴你所见”，产品介绍是“识别任务、搜索服饰、寻找高清素材、浏览相似美图、尽在百度识图！”
在百度识图上传一张地标图，结果显示如下：
![地标图上传.png](https://upload-images.jianshu.io/upload_images/9400767-71524ae9d214cd34.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
百度识图会返回相关商品、图片来源、相似图片的结果。
其优点在于“相关商品”“图片来源”这两项功能，延展性更广，让用户多方位多维度了解图片内容信息。
而劣势在于“相似图片”功能，由上图返回的结果可示，百度识图只是展示该地标的其他角度、类型的图片，并无推荐相似、相关场景这种服务；无移动端app，用户使用起来不方便。

**总结：** 根据“竞品”分析，可以得出，我们可以从移动端app的角度切入，打造“以用户为中心”即为用户提供便利、人性化的服务。即便服务维度上没有竞品广，但是我们的产品针对性更强，服务更深入，为目标用户提供个性化服务，增强用户对该产品的粘性。

## 二、BRD（略写）

#### 简述问题

市面上关于相似商品、信息、服务推荐等的技术和服务已相对成熟且应用广泛，然而针对**相似场景推荐**的产品或服务却寥寥无几，尽管这一市场需求不小。所以我们可以从这一角度切入，解决该痛点，满足这一用户群体的需求，提供人性化服务。

#### 产品价值

伴随着互联网技术的提升，影视领域越来越“低门槛”，拍摄、摄像越来越大众化，寻常百姓可以很快掌握一些摄影摄像要领，并且只要人手有一部具备拍摄功能的手机，就能随时随地进行创作。

鉴于市场上很多群体有摄影、摄像的需求，但因为成本和资源有限，在选择拍摄场景时陷入了困境，一方面想要以最低的成本获取最高的效益，一方面又想场景达到预期的效果这一用户场景的考虑，为此，我仅代表我们团队提出 **“Sceneing”** 这个产品，“scene”的意思是场景，而“sceneing”我们赋予它“寻找场景”的意思，简单通俗，易于记忆。

该产品 **针对的就是小型影视制作团队，或是有摄影、摄像需求的群体，帮助他们在前期挑选拍摄场景提供便利、合适的方案，提高工作效率，减少由于布景问题而产生的资金和人员损耗，达到预设效果甚至超过预设效果。**


#### 商业模式（盈利）
1. 推荐相似场景图片一次性能返回最多50张图片，而如果需要实施“换一批”功能的话，需要充值会员，即可在会员时间内进行“换一批”操作。
2. 一个账号一天最多只能上传并搜索10张图片（包括“识别地标”和“找相似场景”），而如果有需要上传并搜索10张以上的图片的话，需要充值会员，即可再会员时间内进行同个账号上传并搜索无限图片的操作。

**以下是会员充值设定：**

| 会员设定 | 时间 | 充值金额 |
| --- | --- | --- |
| 1 | 一个月 | 10元 |
| 2 | 三个月 | 28元 |
| 3 | 一年 | 99元 |
| 4 | 永久 | 200元 |

#### 需要哪些资源，我们有没有能力完成
| 资源 | 有无能力完成 | 负责部门 |
| --- | --- | --- |
| 可能需要爬取众多网站上各式各样旅游景点的图片，特别是有代表性、美观的图片，用来建数据库。 | 有 | 爬虫工作有关部门 |
| 后台运营和维护，即便用户需求量大，也保证app的正常运行 | 有 | 运营维护技术有关部门 |

## 三、PRD
## 3.1 价值主张设计 
### 加值宣言
为有拍摄、摄像需求的群体提供**挑选符合预期的场景**或是**因资源问题选择替代性场景**的服务，减少因租赁、布景等成本的支出。
### 核心价值
1. 用户在网上找到符合预期的图片（前提是著名地标地点），奈何不知道地点在哪，可通过上传返回**地标名称**。

2. 通过图片内容识别给上传的图片**打上标签**，检索与标签相关的信息，返回**分类**的名称和对应的百科信息。根据识别结果的分类给出相关内容推荐。

3. 根据用户上传的图片，通过相似图片的寻找，还会返回相关内容**推荐替代性场景**。

（产品安全管理，暂不做）4. 若用户上传包含色情内容的图片，后台会对**图片内容和质量进行检测**并返回警示，警告用户并提示禁止下一步的操作。

### 用户痛点

**痛点一** 
用户在网上无意中浏览到符合预期的拍摄场景（前提是较著名的地标地点），无奈不知道地点在哪。

**痛点二**
当用户上传图片后，想要查看与该图片同一分类下的其他图片，帮助他更好的进行挑选场景的任务。

**痛点三**
用户由于拍摄摄像需要，想要挑选预期中的场景，奈何因为资金和资源有限，无法实现真正亲临现场的目标，此时用户想要找到可替代的场景，营造场景相像的假象。

**痛点四**
平台上出现用户上传的包含色情暴力等内容的图片，造成不良风气。

### 需求列表与人工智能API加值
| 序号 | 需求列表（痛点） | 人工智能API | 优先级 | 备注|
| --- | --- | --- | --- | --- |
| 1 | 拥有地标图片却不知道地标名称 | 地标识别 | 重要 | 无 |
| 2 | 想要查看与该图片同一分类下的其他图片 | 通用物体和场景识别/图像标签分类 | 次重要 | 无 |
| 3 | 寻找相似图片内容替代难度性高的场景 | 图像搜索 | 重要 | 无 |
| 4 | 禁止违规图片上传，维护产品良好风气 | 内容审核 | 次重要 | 暂不做 |

### 人工智能概率性与用户痛点
| # | 人工智能 | 可能出现的问题 | 准确度 | 用户痛点 | 评价 |
| --- | --- | --- | --- | --- | --- |
| 1 | 地标识别 | 可能由于图片问题或者是匹配不当等原因导致识别的地标名称显示不出来或出错 | 90%以上 | 可能会指引用户错误的方向 | **问题较大**，用户体验大大降低 |
| 2 | 通用物体和场景识别/图像标签分类 | 可能由于图片问题导致返回的分类结果有差错 | 90%以上 | 分类的内容可能没有一定的关联 | 问题不大，用户体验可能会降低 |
| 3 | 图像搜索 | 上传的图片有一定的要求——尽量避免背景、其他干扰特征，否则在计算图片相似度时会有误差，造成检索结果不准确 | 90%以上 | 输出的结果可能不是用户期望的 | 问题不大，用户体验可能会下降 |
| 4 | 图片内容审核 | 可能由于判断不准确导致某些合规的图片不能上传 | 90%以上 | 用户不能上传某些“擦边”的图片 |问题不大，属于概率极小情况 |

## 3.2 原型 

#### 产品架构图
![Sceneing APP.png](https://upload-images.jianshu.io/upload_images/9400767-8c95756277ff6361.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

### 交互及界面设计

**以下为核心交互页面：**

![核心交互页面1.png](https://upload-images.jianshu.io/upload_images/9400767-a0b3cd5a9c2e39ab.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

① 此页面调用了**地标识别api**。用户上传图片，后台会进行分析并得出该图标的相关地标信息，最终返回“地点名称”的值，对应显示在原型中的“地点”的文本框内；
此页面还调用了**通用物体和场景识别api**。用户上传图片，后台根据分析图片的数据点，输出图片中的多个“物体/场景名称”和“百科信息内容描述”，对应显示在原型中的“分类标签”“地标特色”“百科信息”的文本框内。
[具体交互详情可点击查看原型文档的【1.首页-1.1识别地点-识别后信息】页面](https://nfunm086.github.io/API_Prototype/#g=1&p=%E8%AF%86%E5%88%AB%E5%90%8E%E4%BF%A1%E6%81%AF)

![核心交互页面2.png](https://upload-images.jianshu.io/upload_images/9400767-4e6705e601755991.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

② 此页面调用了**相似图像搜索api**。用户上传图片，后台会把该图片与后台的图片库进行快速对比测试，最终从相似度最高为序把返回的图片依次呈现在“滑动模式”的左、右两侧。
[具体交互详情可点击查看原型文档的【1.首页-1.2找相似场景-场景推荐（滑动模式）】页面](https://nfunm086.github.io/API_Prototype/#g=1&p=%E5%9C%BA%E6%99%AF%E6%8E%A8%E8%8D%90%EF%BC%88%E6%BB%91%E5%8A%A8%E5%BD%A2%E5%BC%8F%EF%BC%89)

### 信息设计

[具体流程拆分和api调用的结合可点击查看原型文档的【主要功能流程图】](https://nfunm086.github.io/API_Prototype/#g=1&p=%E4%B8%BB%E8%A6%81%E5%8A%9F%E8%83%BD%E6%B5%81%E7%A8%8B%E5%9B%BE)

### 原型文档
- **[原型链接](https://nfunm086.github.io/API_Prototype/)**

- **[原型文档下载链接](https://github.com/NFUNM086/API_ML_AI_final/blob/master/Sceneing%E5%8E%9F%E5%9E%8B.rp
)**

### 口头操作说明
该APP有两个核心功能，一是地标识别，二是找相似场景。点击“地标识别”按钮进入手机的系统自带相册，用户可以选择上传相册内已有照片或者现场拍摄。**当确定图片后，后台会调用【地标识别api】和【通用物体和场景识别】对图片进行分析和打标签（分类），最终返回图片的地标名称、分类标签、相关信息。**

这时候，用户可以选择“找相似”按钮跳转至该产品的第二个核心功能——找相似场景。当然也可以在首页点击“找相似场景”按钮，同样进入手机自带相册，用户同样可以选择上传相册内已有照片或者现场拍摄。**当确定图片后，后台会调用【相似图像搜索api】对图片进行分析并在数据库找到与之相关度较高的图片，按相关度由高到低的顺序展示在页面上。**该页面有两个展示模式，一是“滑动模式”，二是“列表模式”，两者只是展示图片形式不同，内容是相同的。**同样地，用户可以点击“查看详情”或“详情”进入上段描述的“地标识别”页面，形成两个核心功能的紧密交互和联系。**

## 3.3 API产品使用关键AI或机器学习之API的输出入展示 
### API1.使用水平

#### 核心功能API一：地标识别（百度智能云）

**调用输入**
```python
# encoding:utf-8
import requests
import base64
# 获取你的access_token
host = 'https://aip.baidubce.com/oauth/2.0/token?grant_type=client_credentials&client_id=你的AK&client_secret=你的SK'  
# client_id 为官网获取的App Key， client_secret 为官网获取的Secret Key
response = requests.get(host)
if response:
    print(response.json())

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/landmark"
# 二进制方式打开图片文件
f = open('图片路径', 'rb')
img = base64.b64encode(f.read())
params = {"image":img}
access_token = '你的token'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```
**输出示例一**
```python
{'log_id': 4511370718357138505, 'result': {'landmark': '杨梅坑'}}
# log_id为请求标识码，随机数，唯一，result为识别结果，landmark为地标名称，无法识别则返回空字符串
```
**输出示例二**
```python
{
	'log_id': 6946576311633325961,
	'result': {
		'landmark': '城隍庙旅游区'
	}
}
```

#### 核心功能API二：相似图像搜索（百度智能云）
主要分为**图像入库**和**相似图像检索**两个步骤：

**调用输入（图像入库）**
```python
# encoding:utf-8
import requests 

host = 'https://aip.baidubce.com/oauth/2.0/token?grant_type=client_credentials&client_id=你的AK&client_secret=你的SK'
# client_id 为官网获取的AK， client_secret 为官网获取的SK
response = requests.get(host)
if response:
    print(response.json())

import requests
import base64

'''
相似图检索—入库 （控制台的图库管理在线手动上传也可以）
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/realtime_search/similar/add"
# 二进制方式打开图片文件
f = open('图片路径', 'rb')
img = base64.b64encode(f.read())

params = {"brief":"{\"name\":\"小度\", \"id\":\"1\"}","image":img,"tags":"1,1"}  # "brief"的意思是“摘要”，输出{"name":"小度", "id":"1"}这个的摘要；"tags"的意思是“分类”， 有两个分类，输出两个1
access_token = '你的token'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```
**输出（图像入库）**
```python
'''
相似图检索—入库 
'''
{'log_id': 2615798846622334216, 'cont_sign': '2277041864,3742307042'}
```
**调用输入（相似图像检索）**
```python
'''
相似图检索—检索
'''

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v1/realtime_search/similar/search"
# 二进制方式打开图片文件
f = open('C:\\Users\\Lenovo\\Desktop\\abc\\999.jpg', 'rb')
img = base64.b64encode(f.read())

params = {"image":img,"pn":10,"rn":5}
access_token = '24.7236947ac4e0a0f9b5de85a2b6a1fe18.2592000.1578387925.282335-17961157'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```
**输出（相似图像检索）**
```python
'''
相似图检索—检索 
'''
{'has_more': True, 'log_id': 3435434730661354600, 'result_num': 3, 'result': [{'score': 0.57360649108887, 'brief': '巴厘岛金巴兰海滩', 'cont_sign': '3300373147,1829607933'}, {'score': 0.40868338942528, 'brief': '深圳杨梅坑', 'cont_sign': '1554820251,3584136211'}, {'score': 0.56604534387589, 'brief': '惠女湾', 'cont_sign': '2418627335,4044647917'}]}
```

#### 核心功能API三：通用物体和场景识别（百度智能云）
**调用输入**
```python
# encoding:utf-8
import requests 

# client_id 为官网获取的AK， client_secret 为官网获取的SK
host = 'https://aip.baidubce.com/oauth/2.0/token?grant_type=client_credentials&client_id=你的AK&client_secret=你的SK'
response = requests.get(host)
if response:
    print(response.json())

import requests
import base64

request_url = "https://aip.baidubce.com/rest/2.0/image-classify/v2/advanced_general"
# 二进制方式打开图片文件
f = open('图片路径', 'rb')
img = base64.b64encode(f.read())

params = {"image":img}
access_token = '24.4df7beea4c26f69ff9f9211c3d26d907.2592000.1578584383.282335-17992992'
request_url = request_url + "?access_token=" + access_token
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```

**输出**
```python
{'log_id': 3705053088486162506, 'result_num': 5, 'result': [{'score': 0.910103, 'root': '', 'keyword': '玉屏峰'}, {'score': 0.71172, 'root': '自然风景-山峦', 'keyword': '山峦'}, {'score': 0.410596, 'root': '商品-工艺品', 'keyword': '工艺品'}, {'score': 0.226717, 'root': '植物-树', 'keyword': '树'}, {'score': 0.035858, 'root': '商品-家装建材', 'keyword': '石头'}]}
```

### API2.使用比较分析

#### 地标识别（百度智能云）
- **接口描述**：该请求用于识别地标，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的地标识别结果。
- **HTTP 方法**：POST
- **请求URL**：https://aip.baidubce.com/rest/2.0/image-classify/v1/landmark
- **调用价目表**

![image.png](https://upload-images.jianshu.io/upload_images/9400767-fe6e764956f64100.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- **优势**
![image.png](https://upload-images.jianshu.io/upload_images/9400767-e4fd3578051204f4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- **调用输入和输出在【API1】有提到，这里将不再列出**

#### 地标识别（聚合数据）
- **接口描述**：该请求用于识别地标，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的地标识别结果。
- **HTTP 方法**：POST
- **请求URL**：http://apis.juhe.cn/landmarkDetect/index
- **调用价目表**
![image.png](https://upload-images.jianshu.io/upload_images/9400767-10028d72c361ec67.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**调用输入**
```python
import requests,json
import base64

request_url = "http://apis.juhe.cn/landmarkDetect/index"
# 二进制方式打开图片文件
f = open('本地图片路径', 'rb')
img = base64.b64encode(f.read())

params = {"image":img,"key":'你的key'}

request_url = request_url
headers = {'content-type': 'application/x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
if response:
    print (response.json())
```

**输出示例**
```python
{'reason': 'success', 'result': '巴黎圣母院', 'error_code': 0}
```

#### 地标识别（微软-使用域模型）
- **接口描述**：支持特定于域的进一步分析。有两种使用领域特定模型的方法：单独使用（范围分析）或作为分类功能的增强。其中增强的分类分析支持特定于域的模型，包括地名流和**地标**。
- **HTTP 方法**：POST
- **调用价目表**

![image.png](https://upload-images.jianshu.io/upload_images/9400767-b8eb15a39f22aa87.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

**调用输入**
```python
import requests
# If you are using a Jupyter notebook, uncomment the following line.
# %matplotlib inline
import matplotlib.pyplot as plt
from PIL import Image
from io import BytesIO
import os,sys

# Add your Computer Vision subscription key and endpoint to your environment variables.
if 'key1' in os.environ:
    subscription_key = os.environ['key1']
else:
    print("\nSet the COMPUTER_VISION_SUBSCRIPTION_KEY environment variable.\n**Restart your shell or IDE for changes to take effect.**")
    sys.exit()

if 'endpoint1' in os.environ:
    endpoint = os.environ['endpoint1']

landmark_analyze_url = endpoint + "vision/v2.1/models/landmarks/analyze"

# Set image_url to the URL of an image that you want to analyze.
image_url = "https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1575896154848&di=2af9f17bc075b955decf4949d9360597&imgtype=jpg&src=http%3A%2F%2F5b0988e595225.cdn.sohucs.com%2Fimages%2F20190106%2Fbd92199fb23344209b88b0497c73eeeb.jpeg"

headers = {'Ocp-Apim-Subscription-Key': subscription_key}
params = {'model': 'landmarks'}
data = {'url': image_url}
response = requests.post(
    landmark_analyze_url, headers=headers, params=params, json=data)
response.raise_for_status()

# The 'analysis' object contains various fields that describe the image. The
# most relevant landmark for the image is obtained from the 'result' property.
analysis = response.json()
assert analysis["result"]["landmarks"] is not []
print(analysis)
landmark_name = analysis["result"]["landmarks"][0]["name"].capitalize()

# Display the image and overlay it with the landmark name.
image = Image.open(BytesIO(requests.get(image_url).content))
plt.imshow(image)
plt.axis("off")
_ = plt.title(landmark_name, size="x-large", y=-0.1)
```
**输出示例一**
```python
<pre style="box-sizing: border-box; overflow: auto; font-family: monospace; font-size: inherit; display: block; padding: 1px 0px; margin: 0px; line-height: inherit; word-break: break-all; overflow-wrap: break-word; color: black; background-color: transparent; border: 0px; border-radius: 0px; white-space: pre-wrap; vertical-align: baseline;">{'result': {'landmarks': [{'name': 'Forbidden City', 'confidence': 0.9967284202575684}]}, 'requestId': 'ee466183-21b6-44b0-85da-46b108767670', 'metadata': {'width': 1080, 'height': 732, 'format': 'Jpeg'}}
</pre>

![image.png](https://upload-images.jianshu.io/upload_images/9400767-eb5a551960d44797.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```

### 评价：地标识别api
| 不同家的地标识别api服务 | 个人评价 |
| --- | --- |
| 百度智能云 | 免费调用3000次，300万次以内3元千次，超过300万次1.8元千次，性价比高。而且优势有可视化图库管理，可以支持上传、编辑等功能，提供服务保障 |
| 聚合数据 | 一个账号免费次数只有10次，购买套餐选择不多，性价比不高，不太适合个人开发者 |
| 微软 | 需要在环境变量配置key和endpoint，相对比上述两者麻烦一点，个人用户可以免费一万次调用，而付费不仅可以调用量无限制，还可以增加QPS（每秒可发送请求数）|

#### ∴ 综上所述，选择**百度智能云**的地标识别api服务。

#### 相似图像搜索（百度智能云）
（分为图像入库和图像检索两个步骤）
- **接口描述**：在自建图库中找到与检索图片语义相似的图片集，并给出相似度打分（综合图片类型、颜色、内容、布局等特征）。
- **HTTP 方法**：POST
- **请求URL**：https://aip.baidubce.com/rest/2.0/image-classify/v1/realtime_search/similar/add（图像入库）
https://aip.baidubce.com/rest/2.0/image-classify/v1/realtime_search/similar/search（图像检索）
- **调用价目表**
![相似图像搜索（百度智能云）价目表.png](https://upload-images.jianshu.io/upload_images/9400767-cf21438c799ff606.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

[价格详情请点击此处](https://ai.baidu.com/ai-doc/IMAGESEARCH/Zk3bczq54)
- **优势**
![相似图像搜索（百度智能云）产品优势.png](https://upload-images.jianshu.io/upload_images/9400767-6b35959b6de298b1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- **调用输入和输出在【API1】有提到，这里将不再列出**

#### 相似图像搜索（阿里云）
（分为创建图库、添加样本图片和图像检索三个步骤）
- **接口描述**：检测指定图片和相似图库中的样本图片的相似度。
- **HTTP 方法**：POST
- **请求URL**：/green/similarity/library/add（创建图库）
/green/similarity/image/add（添加样本图片）
/green/image/scan（图像检索）
- **调用价目表**
![相似图搜索（阿里云）价目表.png](https://upload-images.jianshu.io/upload_images/9400767-7442140ea42fc659.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

[价格详情请点击此处](https://www.aliyun.com/price/product/?spm=a2c4g.11186623.2.13.416f6961v2LznE#/lvwang/detail)

#### 相似图像搜索（我知图）
（分为图片添加、图片搜索两个步骤，其中这两个步骤分别有本地上传和url上传两种方法）
- **接口描述**：本服务提供基于图像内容的相似图像搜索. 即用输入图片本身的颜色分布, 几何形状, 纹理来搜索相似图片, 并将结果按与输入图片的相似度打分排序。
- **HTTP方法**：POST
- **请求URL**：http://apisim20.wozhitu.com:8084/vsearchtech/api/v1.0/apisim_additem（图片添加）
http://apisim20.wozhitu.com:8084/vsearchtech/api/v1.0/apisim_search（图片搜索）
- **调用价目表**
![相似图像搜索（我知图）价目表.png](https://upload-images.jianshu.io/upload_images/9400767-b18861d645dc24e5.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **优势**
![相似图像搜索（我知图）优势.png](https://upload-images.jianshu.io/upload_images/9400767-7f7e5f7b7620dc1f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **调用输入（上传图片）**
```python
'''
上传图片
'''
import requests

data = {
		'apikey': '【输入你的apikey~我花钱买的~】',
        'imgname':'church.jpg',
        'catid':'21',
        'kwds':'',
        'labels':'',
        'title':'石室大教堂',
        'info':''
       }
files = [
        ('photo', ('dog1.jpg', open('C:\\Users\\Administrator\\Desktop\\abc\\004.jpg', 'rb'), 'image/jpg'))
       
]       
response = requests.post('http://apisim20.wozhitu.com:8084/vsearchtech/api/v1.0/apisim_additem',data=data, files=files)
print(response.text)
```
- **输出（上传图片）**
```python
{"class":"vs.vscommon.AnyData","data":"OK","v":0}
```

如果不确定自己上传图片成功没有，可以进行“查询图片”，以下为调用示例
- **调用输入（查询图片）**
```python
# 查询图片
import requests

data = {
		'apikey': '【输入你的apikey~我花钱买的~】',
        'imgname':'church1.jpg'
       }
response = requests.post('http://apisim20.wozhitu.com:8084/vsearchtech/api/v1.0/apisim_detail',data=data)
print(response.text)
```

- **输出正确示例（查询图片）**
```python
{"class":"vs.vscommon.ImageSearchResultEntry","imgName":"church1.jpg","imgRelativePath":"0_All/10037_dynamicuidmapping.10037/0_All_Categories/20_20/church1.jpg","imgUrl":null,"info":"蓝天下的石室大教堂","keyword":"教堂","productPageUrl":null,"score":0.0,"tagsList":"30","title":"石室大教堂"}
```
- **输出错误示例（查询图片）**
```python
{"class":"vs.vscommon.ImageSearchResultEntry","imgName":null,"imgRelativePath":null,"imgUrl":null,"info":null,"keyword":null,"productPageUrl":null,"score":0.0,"tagsList":null,"title":null}
```

- **调用输入（图像搜索）**
```python
# 上传图片搜索
import requests

data = {
		'apikey': '【输入你的apikey~我花钱买的~】',
        'catid':'0',
        'subject':'',
        'labeland':'',
        'labelor':'',
        'labelnot':''
       }
files = [
        ('photo', ('008.jpg', open('C:\\Users\\Administrator\\Desktop\\abc\\008.jpg', 'rb'), 'image/jpg'))
       
]       
response = requests.post('http://apisim20.wozhitu.com:8084/vsearchtech/api/v1.0/apisim_search', data=data, files=files)
print(response.text)
```

- **输出示例（图像搜索）**
```python
{"class":"vs.vscommon.ImageSearchResultSet","header":{"class":"vs.vscommon.ImageSearchResultHeader","itemsFound":3,"requestParams":"[catid:0, apikey:CHUIGAWEI-10037-2020.01.09.17.51.30-15cd322ab1f0a1720f70b1f2d6c58875, subject:, labelnot:, labeland:, labelor:, photo:org.springframework.web.multipart.commons.CommonsMultipartFile@21b6b78f, controller:imgSimRest, action:[GET:getxxx, POST:apisim_search, DELETE:deletexxx]]","searchTimeMillSec":76},"itemGroupStatsTreeSet":[],"resultList":[{"class":"vs.vscommon.ImageSearchResultEntry","imgName":"church1.jpg","imgRelativePath":"0_All/10037_dynamicuidmapping.10037/0_All_Categories/20_20/church1.jpg","imgUrl":null,"info":"蓝天下的石室大教堂","keyword":"教堂","productPageUrl":null,"score":0.65605617,"tagsList":"30","title":"石室大教堂"},{"class":"vs.vscommon.ImageSearchResultEntry","imgName":"church3.jpg","imgRelativePath":"0_All/10037_dynamicuidmapping.10037/0_All_Categories/23_23/church3.jpg","imgUrl":null,"info":"仰视石室大教堂","keyword":"教堂","productPageUrl":null,"score":0.615116,"tagsList":"30","title":"石室大教堂"},{"class":"vs.vscommon.ImageSearchResultEntry","imgName":"church.jpg","imgRelativePath":"0_All/10037_dynamicuidmapping.10037/0_All_Categories/21_21/church.jpg","imgUrl":null,"info":null,"keyword":null,"productPageUrl":null,"score":0.60945016,"tagsList":null,"title":"石室大教堂"}]}
```

### 评价：相似图像搜索api
| 不同家的地标识别api服务 | 个人评价 |
| --- | --- |
| 百度智能云 | api文档很详细具体，也有示例代码可供参考、优点在于除了用代码调用外，还提供控制台的图库管理，可实现在线一次上传最后10张图片和在线搜索图片的测试功能，缺点是接口调用无法批量上传图片 |
| 阿里云 | 分为三个步骤，过于麻烦，且无示例代码提供，还未调用成功，排除 |
| 我知图 | 不提供免费服务，生成key必须缴费，最低版20元/月，api文档逻辑不够规范和详细，调用api返回的json值不够直观清晰，且图片上传只能为JPG格式、300 – 800像素，总体体验一般 |

#### ∴ 综上所述，选择**百度智能云**的相似图像搜索api服务。

#### 通用物体和场景识别（百度智能云）
- **接口描述**：该请求用于通用物体及场景识别，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的多个物体及场景标签。
- **HTTP方法**：POST
- **请求URL**：https://aip.baidubce.com/rest/2.0/image-classify/v2/advanced_general
- **调用价目表**

![通用物体和场景识别（百度智能云）价目表.png](https://upload-images.jianshu.io/upload_images/9400767-718811ec65936bb6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **优势**

![通用物体和场景识别（百度智能云）产品优势.png](https://upload-images.jianshu.io/upload_images/9400767-4ed2a5346c415f8c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **调用输入和输出在【API1】有提到，这里将不再列出**

#### 图像标签（阿里云）
- **接口描述**：该请求用于通用物体及场景识别，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的多个物体及场景标签。
- **HTTP方法**：POST
- **请求URL**：https://dtplus-cn-shanghai.data.aliyuncs.com/image/tag
- **调用价目表**

![图像打标（阿里云）价目表.png](https://upload-images.jianshu.io/upload_images/9400767-174945e3671c4a78.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

- **调用输入**
```python
import requests
import base64
import json

'''
通用物体和场景识别
'''

request_url = "https://dtplus-cn-shanghai.data.aliyuncs.com/image/tag"

param = {"type":0,
          "image_url":"https://timgsa.baidu.com/timg?image&quality=80&size=b9999_10000&sec=1578585230135&di=dbd34e43564b1d13992ff9729fa4cc85&imgtype=0&src=http%3A%2F%2Fres.co188.com%2Fdata%2Fdrawing%2Fimg640%2F5954315204080.jpg",
          "Access Key ID":'输入你的Access ID Key',
          "Access Key Secret":'输入你的Access Secret Key'
         }

request_url = request_url

response = requests.post(request_url, params=param)
# if response:
    # print (response.json())
print(response.text)
```

- **输出示例**
```python
Body：{
  "tags": [
    {
      "value": "教堂",
      "confidence": 66
    },
    {
      "value": "钟楼",
      "confidence": 64
    },
    {
      "value": "建筑",
      "confidence": 12
    },
    {
      "value": "城堡",
      "confidence": 11
    }
  ],
  "errno": 0,
  "request_id": "637be35f-7bc6-4e8a-9175-a4756c7b9b0a"
}
```

#### 物体和场景识别（Face++旷视）
- **接口描述**：调用者提供图片文件或者图片URL，进行图片分析，识别图片场景和图片主体。
- **HTTP 方法**：POST
- **请求URL**：https://api-cn.faceplusplus.com/imagepp/beta/detectsceneandobject
- **调用价目表**
因为是beta版，所以目前为[免费](https://www.faceplusplus.com.cn/v2/pricing-details/#api_5)

- **优势**

![Face++物体和场景识别优势.png](https://upload-images.jianshu.io/upload_images/9400767-1af78b428199f64a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


- **调用输入**
```python

import requests
import base64
import urllib.request
import urllib.error
import time

request_url = "https://api-cn.faceplusplus.com/imagepp/beta/detectsceneandobject"

image_url = r"C:\\Users\\Administrator\\Desktop\\abc\\087.jpg"

# 二进制方式打开图片文件
f = open('C:\\Users\\Administrator\\Desktop\\abc\\087.jpg', 'rb')
img = base64.b64encode(f.read())

params = {"image_url":image_url,"api_key":'输入你的api_key',"api_secret":'输入你的api_secret'}
access_token = '输入你的access_token'
request_url = request_url + "?access_token=" + access_token
headers = {'Content-Type': 'application / x-www-form-urlencoded'}
response = requests.post(request_url, data=params, headers=headers)
# if response:
    # print (response.json())
print(response.text)

```

- **输出失败报错**
```python
{"time_used": 1, "error_message": "MISSING_ARGUMENTS: api_key", "request_id": "1578580521,7ce6d568-1234-4a61-a577-57ce5e50fc85"}
```
寻求[网上解答](https://stackoverflow.com/questions/48652293/faceplusplus-error-message-missing-arguments-api-key-with-react-native-f)，尝试后无果。

### 评价：物体和场景识别/图像标签api
| 不同家的地标识别api服务 | 个人评价 |
| --- | --- |
| 百度智能云 | 准确性较高，有每日免费调用500次数 |
| 阿里云 | 没有免费调用次数 |
| Face++ | 调用失败，尚未找到解决办法，排除 |

#### ∴ 综上所述，选择**百度智能云**的通用物体和场景识别api服务。

### API3.使用后风险报告 5%
#### ① API市场竞争程度
| API名称 | API市场竞争程度 |
| --- | --- |
| 地标识别 | 市场上主流公司（包括百度智能云、微软、聚合数据等）的图像识别api分类下都有地标识别。竞争较大，看哪家识别精确度高则哪家优胜。 | 
| 图像搜索 | 图像搜索是个热门的api，主要是因为能够返回相似内容的图片，应用场景多元。目前为止比较热门的是百度智能云家的。 |
| 通用物体和场景识别/图像标签 | 市场上主流公司（包括百度智能云、阿里、Face++等）都有场景识别的api。大同小异都是分类、打标签的功能。竞争较大，看哪家分类准确、标签元素多元则哪家优胜。 |

#### ②输入输出限制
| API名称 | 输入输出限制 |
| --- | --- |
| 地标识别 | **输入限制** 图片可正常解码，且长宽比适宜，大小不超过4M。最短边至少15px，最长边最大4096px； **输出限制** 若地标无法识别则返回空字符串。 |
| 图像搜索 | **输入限制** 检索图和入库的原图要尽量保持场景一致性； **输出限制** 只能返回图片及其摘要信息 |
| 通用物体和场景识别/图像标签 | **输入限制** 图片可正常解码，且长宽比适宜，图片大小不超过4M。最短边至少15px，最长边最大4096px； **输出限制** 只能返回摘要信息，无法返回图片。 |

### API4.加分项 3%
3个人工智能API：地标识别api、通用物体和场景识别/图像标签api、图像搜索api
