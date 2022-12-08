# Chinese_Malicious_Web_Pages_Dataset_And_Detection
中文恶意网页检测数据集与检测方法 网络安全 数据挖掘 自然语言处理 深度学习 文本分类 模式识别

## 中文恶意网页检测数据集与检测方法

![中文恶意网页检测数据集列表1](https://github.com/JiangYanting/Chinese_Malicious_Web_Pages_Dataset_And_Detection/blob/main/%E4%B8%AD%E6%96%87%E6%81%B6%E6%84%8F%E7%BD%91%E9%A1%B5%E6%95%B0%E6%8D%AE%E5%88%97%E8%A1%A801.png)

![中文恶意网页检测数据集列表2](https://github.com/JiangYanting/Chinese_Malicious_Web_Pages_Dataset_And_Detection/blob/main/%E4%B8%AD%E6%96%87%E6%81%B6%E6%84%8F%E7%BD%91%E9%A1%B5%E6%95%B0%E6%8D%AE%E5%88%97%E8%A1%A802.png)

若在科研论文、项目工程中使用了该数据集，欢迎引用我们的工作：
> Yanting Jiang, Di Wu. A novel Chinese malicious webpages detection method based on the pre-trained language model[C]. The 19th International Conference of Web Information Systems and Applications（WISA 2022）, 2022.
   
>   @InProceedings{10.1007/978-3-031-20309-1_14,
>   author="Jiang, Yanting and Wu, Di",
>   title="An Integrated Chinese Malicious Webpages Detection Method Based on Pre-trained Language Models and Feature Fusion",
>   booktitle="Web Information Systems and Applications",
>   year="2022",
>   publisher="Springer International Publishing",
>   address="Cham",
>   pages="155--167",
>   abstract="This paper proposed an integrated Chinese malicious webpages detection method. Firstly, we collected and released a Chinese malicious webpages detection >   dataset called ``ChiMalPages'' containing URLs and HTML/JavaScript files, and specified the detailed types of malicious pages according to relevant laws. Secondly, >   we designed a feature template for Chinese webpages and ranked each feature's importance based on information gain of the Random Forest algorithm. Thirdly, we 
>   fine-tuned BERT on the external URLs classification task and text on webpages, respectively producing new models ``BERT-URL'' and ``BERT-web-text''. The    
>   performance of pre-trained models is obviously superior to the baseline models. Finally, we integrated features from manual templates, BERT-URL and BERT-web-text, >   and the classification F1 score reaches 79.84{\%}, increasing by 7.37{\%} compared with manually designed webpage features. Experiments proved that our method 
>   based on BERT is useful and not biased on detailed classes.",
>   isbn="978-3-031-20309-1"
>   }

### 1. 简介
    
    针对中文恶意网页检测的数据稀缺，难以获取的问题。构建并发布了中文恶意网页检测数据集。
    每一个样本包含网页URL、HTML网页文件、JavaScript代码文件。

### 2. 数据规模
    
    包含521个中文恶意网页。恶意网页的种类涉及博彩类、钓鱼类（冒充正常页面）、色情类、违法交易类等。

### 3. 数据下载地址
    中文恶意网页列表（含URL）的地址：见项目的“中文恶意网页列表+URL.xlsx”文件。
    
    中文恶意网页HTML与JavaScript文件下载地址：请联系作者微信jyt629000，或qq：540980735。

    （经人工检测，恶意网页绝不含木马病毒，可以放心下载）
