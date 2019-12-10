# API_ML_AI期末项目——Sceneing app

## 产品概况
| 发布日期 | 12/10/2019 |
| --------   | -----  |
| 项目名称 | Sceneing | 
| 文件状态 | 已完成 | 
| 文件主人 | 徐嘉慧 | 
| 领头设计师  | 徐嘉慧 | 
| 领头开发者  | 徐嘉慧 | 
| 领头测试者  | 徐嘉慧 | 

## 介绍

这是一款为有拍摄摄像需求的群体提供挑选拍摄场景帮助服务的app。

## 目标用户

有拍摄和摄像的目标，并且有特定场景需求的群体

## MRD（略）

#### 市场分析
随着人们经济条件的改善和生活水平的提高，现在很多小型影视拍摄团队，亦或是个人，都存在着想要寻找预期场景的需求，达到预期效果的目的。但由于资金和资源有限，无法实现高成本的效果，奈何只能在各大搜索引擎上寻求帮助。（如下图）

![需求.png](https://upload-images.jianshu.io/upload_images/9400767-c9a8e7e06e788df9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

![需求1.png](https://upload-images.jianshu.io/upload_images/9400767-51645a5ac1a72ca0.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


这种情况下，一要求发帖者描述准确，二要求其指定的区域条件相对较好，确实存在其描述的场景，三要求广大网友集思广益并且有建设性建议，以上三条条件缺一不可，故绝大多数情况下寻求无果。


## BRD（略）
伴随着互联网技术的提升，影视领域越来越“低门槛”，拍摄、摄像越来越大众化，寻常百姓可以很快掌握一些摄影摄像要领，并且只要人手有一部具备拍摄功能的手机，就能随时随地进行创作。
鉴于市场上很多群体有摄影摄像的需求，但因为拍摄成本和资源有限，在选择拍摄场景时陷入了困境，一方面想要以最低的成本获取最高的效益，一方面又想场景达到预期的效果这一用户场景的考虑，为此，我仅代表我们团队提出**“Sceneing”**这个产品，“scene”的意思是场景，而“sceneing”我们赋予它“寻找场景”的意思，简单通俗，易于记忆。
该产品**针对的就是小型影视制作团队，或是有摄影摄像需求的群体，帮助他们在前期挑选拍摄场景提供便利、合适的方案，提高工作效率，减少由于布景问题而产生的资金和人员损耗，达到预设效果甚至超过预设效果。**

## PRD
## 价值主张设计 15%
### 加值宣言 3%
为有拍摄、摄像需求的群体提供**挑选符合预期的场景**或是**因资源问题选择替代性场景**的服务，减少因租赁、布景等成本的支出。
### 核心价值 3%
1. 用户在网上找到符合预期的图片（前提是著名地标地点），奈何不知道地点在哪，可通过上传返回**地标名称**。

2. 通过图片内容识别给上传的图片**打上标签**，检索与标签相关的信息，返回**分类**的名称和对应的百科信息。根据识别结果的分类给出相关内容推荐。

3. 除此之外，根据用户上传的图片，通过相似图片的寻找，还会返回相关内容**推荐替代性场景**。


（产品安全管理）4. 若用户上传包含色情内容的图片，后台会进行检测并返回警示，警告用户并提示禁止下一步的操作
### 核心价值与用户痛点 3%

**痛点一** 
用户在网上无意中浏览到符合预期的拍摄场景（前提是较著名的地标地点），无奈不知道地点在哪。

**痛点二**
当用户上传图片后，想要查看与该图片同一分类下的其他图片，帮助他更好的进行挑选场景的任务。

**痛点三**
用户由于拍摄摄像需要，想要挑选预期中的场景，奈何因为资金和资源有限，无法实现真正亲临现场的目标，此时用户想要找到可替代的场景，营造场景相像的假象。

### 人工智能概率性与用户痛点 3%
| # | 人工智能 | 可能出现的问题 | 概率性 | 用户痛点 | 评价 |
| --- | --- | --- | --- | --- | --- |
| 1 | 地标识别 | 可能由于图片问题或者是匹配不当等原因导致识别的地标名称显示不出来或出错 | xx% | 可能会指引用户错误的方向 | **问题较大**，用户体验大大降低 |
| 2 | 通用物体和场景识别 | 可能由于图片问题导致返回的分类结果有差错 | xx% | 分类的内容可能没有一定的关联 | **问题不大**，用户体验可能会降低 |
| 3 | 图像搜索 | 上传的图片有一定的要求——尽量避免背景、其他干扰特征，否则在计算图片相似度时会有误差，造成检索结果不准确 | xx% | 输出的结果可能不是用户期望的 | 问题不大，用户体验可能会下降 |

### 需求列表与人工智能API加值 3%
| 序号 | 需求列表 | 人工智能 | 优先级 | 备注|
| --- | --- | --- | --- | --- |
| 1 | 拥有地标图片却不知道地标名称 | 地标识别 | 重要 | ff |
| 2 | 想要查看与该图片同一分类下的其他图片 | 通用物体和场景识别 | 次重要 | ff |
| 3 | 寻找相似图片内容替代难度性高的场景 | 图像搜索 | 重要 | ff |
| 4 | 禁止违规图片上传，维护产品良好风气 | 内容审核 | 次重要 | ff |


### 原型 20%
#### 原型1.交互及界面设计 5%
交互及界面设计：在PRD文件中是否有说明且原型是否有做到：交互及界面设计的某个核心交互环节使用了人工智能的加值

#### 原型2.信息设计 5%
信息设计：在PRD文件中是否有说明且原型是否有做到：信息设计的某个核心信息或设计使用了人工智能的加值

#### 原型3.原型文档 5%
原型文档：多少程度上有提供MVP可交互的原型文档，供它人在Github上下载使用

#### 原型4.口头操作说明 5%
口头操作说明：多少程度上在2-3分钟时间限制内，对听众留下了「的确这是个可行丶可用的人工智能加值产品」的印象

### API产品使用关键AI或机器学习之API的输出入展示 15%
### API1.使用水平 5%
使用水平：在PRD文件中是否有说明且展示，核心功能所应用的API之输入及输出

#### 核心功能API一：地标识别（百度智能云）


**调用输入**
```
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
```
{'log_id': 4511370718357138505, 'result': {'landmark': '杨梅坑'}}
# log_id为请求标识码，随机数，唯一，result为识别结果，landmark为地标名称，无法识别则返回空字符串
```
**输出示例二**
```
{
	'log_id': 6946576311633325961,
	'result': {
		'landmark': '城隍庙旅游区'
	}
}
```

#### 核心功能API二：图像搜索（百度智能云）


**调用输入**
```
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
**输出**
```
'''
相似图检索—入库 
'''
{'log_id': 2615798846622334216, 'cont_sign': '2277041864,3742307042'}
```
**调用输入**
```
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
**输出**
```
'''
相似图检索—检索 
'''
{'has_more': True, 'log_id': 3435434730661354600, 'result_num': 3, 'result': [{'score': 0.57360649108887, 'brief': '巴厘岛金巴兰海滩', 'cont_sign': '3300373147,1829607933'}, {'score': 0.40868338942528, 'brief': '深圳杨梅坑', 'cont_sign': '1554820251,3584136211'}, {'score': 0.56604534387589, 'brief': '惠女湾', 'cont_sign': '2418627335,4044647917'}]}
```


#### API2.使用比较分析 5%
使用比较分析：在PRD文件中是否有说明且提供连结证据，所使用的API是查找过最适用的（主要竞争者无或比较次），如考量其成熟度丶性价比丶等等

#### 地标识别（百度智能云）
- **接口描述**：该请求用于识别地标，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的地标识别结果。
- **HTTP 方法**：POST
- **请求URL**：https://aip.baidubce.com/rest/2.0/image-classify/v1/landmark
- **调用价目表**
![image.png](https://upload-images.jianshu.io/upload_images/9400767-fe6e764956f64100.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- **优势**
![image.png](https://upload-images.jianshu.io/upload_images/9400767-e4fd3578051204f4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
- **调用输入和输出在上述有提到，这里将不再列出**

#### 地标识别（聚合数据）
- **接口描述**：该请求用于识别地标，即对于输入的一张图片（可正常解码，且长宽比适宜），输出图片中的地标识别结果。
- **HTTP 方法**：POST
- **请求URL**：http://apis.juhe.cn/landmarkDetect/index
- **调用价目表**
![image.png](https://upload-images.jianshu.io/upload_images/9400767-ff2afa5739bc6492.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)


**调用输入**
```
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
```
{'reason': 'success', 'result': '巴黎圣母院', 'error_code': 0}
```

#### 地标识别（微软-使用域模型）
- **接口描述**：支持特定于域的进一步分析。有两种使用领域特定模型的方法：单独使用（范围分析）或作为分类功能的增强。其中增强的分类分析支持特定于域的模型，包括地名流和**地标**。
- **HTTP 方法**：POST
- **请求URL**：
- **调用价目表**
![image.png](https://upload-images.jianshu.io/upload_images/9400767-b8eb15a39f22aa87.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)



**调用输入**
```
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
```
<pre style="box-sizing: border-box; overflow: auto; font-family: monospace; font-size: inherit; display: block; padding: 1px 0px; margin: 0px; line-height: inherit; word-break: break-all; overflow-wrap: break-word; color: black; background-color: transparent; border: 0px; border-radius: 0px; white-space: pre-wrap; vertical-align: baseline;">{'result': {'landmarks': [{'name': 'Forbidden City', 'confidence': 0.9967284202575684}]}, 'requestId': 'ee466183-21b6-44b0-85da-46b108767670', 'metadata': {'width': 1080, 'height': 732, 'format': 'Jpeg'}}
</pre>

![image.png](https://upload-images.jianshu.io/upload_images/9400767-eb5a551960d44797.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

```

#### 评价：地标识别api
**百度智能云** 免费调用3000次，300万次以内3元千次，超过300万次1.8元千次，性价比高。而且优势有可视化图库管理，可以支持上传、编辑等功能，提供服务保障
**聚合数据** 一个账号免费次数只有10次，购买套餐选择不多，性价比不高，不太适合个人开发者
**微软** 需要在环境变量配置key和endpoint，相对比上述两者麻烦一点，个人用户可以免费一万次调用，而付费不仅可以调用量无限制，还可以增加QPS（每秒可发送请求数）
∴ 综上所述，选择**百度智能云**的地标识别api服务。

#### API3.使用后风险报告 5%
使用后风险报告：在PRD文件中是否有说明且提供连结证据，所使用的API类别的现在及未来发展性，如API市场竞争程度丶输入输出限制丶定价丶及可替代的程序库（改用自己开发的代码及数据库而不用API）等等

#### API4.加分项 3%
3个人工智能API：地标识别api、通用物体和场景识别api、图像搜索api
