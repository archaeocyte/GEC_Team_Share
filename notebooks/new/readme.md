### 运行要求
* 需要装的库：h5py, numpy, pandas, cv2, tqdm, keras, sklearn, tensorflow

* 需要先把test-jpg-additional 里的图片复制到 test-jpg 中


### 文件列表
* main.ipynb
运行入口，配置关键参数和构造模型结构

* easy_util.ipynb
实现了一些函数方便主文件调用，如读入数据、写出结果、计算F2score、训练模型等

* ipynb_importer.py
无需关心其代码实现，用途是使notebook可以import其他的.ipynb文件
