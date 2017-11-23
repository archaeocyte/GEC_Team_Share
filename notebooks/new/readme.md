### Demands for Implementation:
### 安装须知：

* Packages Required: h5py, numpy, pandas, cv2, tqdm, keras, sklearn, tensorflow.
* 需要安装的库：h5py, numpy, pandas, cv2, tqdm, keras, sklearn, tensorflow 

* We need to copy the images in test-jpg-additional to test-jpg. 
* 需要先把test-jpg-additional 里的图片复制到 test-jpg 中


### List of documents
### 文件列表

* main.ipynb
* Main entrance, determining key parameters and constructing model structure.
* 运行入口，配置关键参数和构造模型结构

* easy_util.ipynb
* Realized some functions to be equipped in the Main function, such as data loading, outputing, F2 score computing and model training.
* 实现了一些函数方便主文件调用，如读入数据、写出结果、计算F2score、训练模型等

* ipynb_importer.py
* This one is used for importing other .ipynb documents on notebooks.
* 无需关心其代码实现，用途是使notebook可以import其他的.ipynb文件
