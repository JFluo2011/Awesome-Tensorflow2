# Awesome-Tensorflow2 💛 [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
基于Tensorflow2开发的优秀扩展包及项目
![Tensorflow](https://github.com/1044197988/Awesome-Tensorflow2/blob/master/Logo/Logo.jpg)

# Tensorflow2说明
2019 谷歌开发者大会于 9 月 10 日和 11 日在上海举办，大会将分享众多开发经验与工具。在第一天的 KeyNote 中，谷歌发布了很多开发工具新特性，并介绍而它们是如何构建更好的应用。值得注意的是，TensorFlow 刚刚发布了 2.0 RC01 版和 1.15，谷歌表示 1.15 是 1.x 的最后一次更新了。TensorFlow 2.0 相信大家已经非常熟悉了，它重点还是放在优化 Keras 和 Eager Execution 的能力，它希望通过这这两种 API 简化整个开发流程。所以，未来的趋势肯定是Tensorflow2.0，在此我整合了许多的优秀库及项目到这个贡献库里。

# 提示
有些项目目前仍在进行中，将在未来支持Tensorflow2，这样的项目也包含在下面列表中。（意味着目前并不支持Tensorflow2）

# Contents <a name="TOC" />👈
<!-- MarkdownTOC depth=4 -->
* [Tutorials](#github-tutorials)
* [Model](#Model)
* [Projects](#Projects)
* [Other](#other)
<!-- /MarkdownTOC --> 

## Tutorials 💛💛💛💛💛<a name="github-tutorials" />
* [tensorflow.google.cn](https://tensorflow.google.cn/beta)
* [dragen1860/TensorFlow-2.x-Tutorials](https://github.com/dragen1860/TensorFlow-2.x-Tutorials)
* [czy36mengfei/tensorflow2_tutorials_chinese](https://github.com/czy36mengfei/tensorflow2_tutorials_chinese)
* [yusugomori/deeplearning-tf2](https://github.com/yusugomori/deeplearning-tf2)


## Model 💛💛💛💛💛<a name="Model" />
### Classification
* [tensorflow/models](https://github.com/tensorflow/models)
该存储库包含在TensorFlow中实现的许多不同模型。
* [1044197988/TF.Keras-Commonly-used-models](https://github.com/1044197988/TF.Keras-Commonly-used-models)
该贡献库为我整理的一些常用的分类、分割模型，包含分割的一些指标、损失函数，但不提供预训练模型的载入。
![Classification](https://github.com/1044197988/Awesome-Tensorflow2/blob/master/Logo/1.png)
![Segmentation](https://github.com/1044197988/Awesome-Tensorflow2/blob/master/Logo/2.png)

#### Large library
* [qubvel/classification_models](https://github.com/qubvel/classification_models#architectures)

#### Model
* [qubvel/efficientnet](https://github.com/qubvel/efficientnet)
* [nsarang/MnasNet](https://github.com/nsarang/MnasNet)
* [calmisential/MobileNetV3_TensorFlow2](https://github.com/calmisential/MobileNetV3_TensorFlow2)
* [calmisential/TensorFlow2.0_ResNet](https://github.com/calmisential/TensorFlow2.0_ResNet)
* [calmisential/TensorFlow2.0_InceptionV3](https://github.com/calmisential/TensorFlow2.0_InceptionV3)
* [calmisential/MobileNetV3_TensorFlow2](https://github.com/calmisential/MobileNetV3_TensorFlow2)
* [calmisential/TensorFlow2.0_Image_Classification](https://github.com/calmisential/TensorFlow2.0_Image_Classification)

##### Capsnet model
* [prabhuomkar/hicr-capsnet](https://github.com/prabhuomkar/hicr-capsnet)

##### Semi-supervised learning
* [ntozer/mixmatch-tensorflow2.0](https://github.com/ntozer/mixmatch-tensorflow2.0)
* [schatty/prototypical-networks-tf](https://github.com/schatty/prototypical-networks-tf)

##### Generative-models and Self encoder
* [timsainb/tensorflow2-generative-models](https://github.com/timsainb/tensorflow2-generative-models)
* [DequanZhu/GANs-collections-tf2.0_keras-eager_mode](https://github.com/DequanZhu/GANs-collections-tf2.0_keras-eager_mode)
* [Hourout/GAN-keras](https://github.com/Hourout/GAN-keras)
* [Net-Mist/style-transfer-tf2](https://github.com/Net-Mist/style-transfer-tf2)
* [mnicnc404/CartoonGan-tensorflow](https://github.com/mnicnc404/CartoonGan-tensorflow)
* [ialhashim/StyleGAN-Tensorflow2](https://github.com/ialhashim/StyleGAN-Tensorflow2)
* [leafinity/SAGAN-tensorflow2.0](https://github.com/leafinity/SAGAN-tensorflow2.0)
* [Lornatang/TensorFlow2-GAN](https://github.com/Lornatang/TensorFlow2-GAN)
* [ppooiiuuyh/SinGAN-tensorflow2.0](https://github.com/ppooiiuuyh/SinGAN-tensorflow2.0)
* [hollygrimm/tf2-cyclegan](https://github.com/hollygrimm/tf2-cyclegan)
* [drewszurko/tensorflow-WGAN-GP](https://github.com/drewszurko/tensorflow-WGAN-GP)

### Segmentation
#### Large library
* [qubvel/segmentation_models](https://github.com/qubvel/segmentation_models)

#### Model
* [srihari-humbarwadi/FastFCN_TF2.0](https://github.com/srihari-humbarwadi/FastFCN_TF2.0)
* [bonlime/keras-deeplab-v3-plus](https://github.com/bonlime/keras-deeplab-v3-plus)
* [matterport/Mask_RCNN](https://github.com/matterport/Mask_RCNN)
* [srihari-humbarwadi/DeepLabV3_Plus-Tensorflow2.0](https://github.com/srihari-humbarwadi/DeepLabV3_Plus-Tensorflow2.0)

### Super resolution
#### Model
* [krasserm/super-resolution](https://github.com/krasserm/super-resolution)

### Object detection
#### Model
* [zzh8829/yolov3-tf2](https://github.com/zzh8829/yolov3-tf2)
* [srihari-humbarwadi/YOLOv1-TensorFlow2.0](https://github.com/srihari-humbarwadi/YOLOv1-TensorFlow2.0)
* [cjpurackal/m2det-tf](https://github.com/cjpurackal/m2det-tf)
* [reliefs/mtcnn-tensorflow2](https://github.com/reliefs/mtcnn-tensorflow2)
* [1044197988/Centernet-Tensorflow2.0](https://github.com/1044197988/Centernet-Tensorflow2.0)
* [calmisential/TensorFlow2.0_FasterRCNN](https://github.com/calmisential/TensorFlow2.0_FasterRCNN)

###NLP Model
#### Large library
* [tensorflow/tensor2tensor](https://github.com/tensorflow/tensor2tensor)

#### Model
* [codertimo/BERT-tf2](https://github.com/codertimo/BERT-tf2)
* [ShaneTian/TextCNN](https://github.com/ShaneTian/TextCNN)
* [strutive07/transformer-tensorflow2.0](https://github.com/strutive07/transformer-tensorflow2.0)
* [thisisiron/nmt-attention-tf](https://github.com/thisisiron/nmt-attention-tf)
* [kpe/bert-for-tf2](https://github.com/kpe/bert-for-tf2)
* [akanyaani/gpt-2-tensorflow2.0](https://github.com/akanyaani/gpt-2-tensorflow2.0)

## Projects 💛💛💛💛💛<a name="Projects" />
* [Shathe/Semantic-Segmentation-Tensorflow-2](https://github.com/Shathe/Semantic-Segmentation-Tensorflow-2)
* [jason9693/MusicTransformer-tensorflow2.0](https://github.com/jason9693/MusicTransformer-tensorflow2.0)
* [xingchensong/Speech-Transformer-tf2.0](https://github.com/xingchensong/Speech-Transformer-tf2.0)
* [liushuan/YOLO-V3-Tensorflow2.0-Face-Detect-via-Wider-Face](https://github.com/liushuan/YOLO-V3-Tensorflow2.0-Face-Detect-via-Wider-Face)
* [ybsdegit/captcha_keras](https://github.com/ybsdegit/captcha_keras)
* [drukka/command-words-recognition-keras](https://github.com/drukka/command-words-recognition-keras)
* [RaidasGrisk/tf2-fots](https://github.com/RaidasGrisk/tf2-fots)
* [RaidasGrisk/tf2-crnn](https://github.com/RaidasGrisk/tf2-crnn)
* [bryanlimy/tf2-transformer-chatbot](https://github.com/bryanlimy/tf2-transformer-chatbot)
* [DequanZhu/FaceNet-and-FaceLoss-collections-tensorflow2.0](https://github.com/DequanZhu/FaceNet-and-FaceLoss-collections-tensorflow2.0)
* [Fei-Wang/insightface](https://github.com/Fei-Wang/insightface)
* [1044197988/Semantic-segmentation-of-remote-sensing-images](https://github.com/1044197988/Semantic-segmentation-of-remote-sensing-images)

## Other 💛💛💛💛💛<a name="Other" />
### 脚本
* [hacker-lin/train_test_valid_split](https://github.com/hacker-lin/train_test_valid_split)
* [ravindrabharathi/tf_utils](https://github.com/ravindrabharathi/tf_utils)
### 解释性工具
* [sicara/tf-explain](https://github.com/sicara/tf-explain)
### 推荐系统模型
* [cheungdaven/DeepRec](https://github.com/cheungdaven/DeepRec)
* [Hourout/CTR-keras](https://github.com/Hourout/CTR-keras)
* [hojinYang/recsys-implementation.tensorflow2](https://github.com/hojinYang/recsys-implementation.tensorflow2)
### 用于分布式培训，评估，模型选择和快速原型制作。
* [zurutech/ashpy](https://github.com/zurutech/ashpy)
### AutoML
* [keras-team/keras-tuner](https://github.com/keras-team/keras-tuner)
* [keras-team/autokeras](https://github.com/keras-team/autokeras)
* [tensorflow/adanet](https://github.com/tensorflow/adanet)
### 元学习
* [siavash-khodadadeh/MetaLearning-TF2.0](https://github.com/siavash-khodadadeh/MetaLearning-TF2.0)
### 强化学习
* [danaugrs/huskarl](https://github.com/danaugrs/huskarl)
* [keiohta/tf2rl](https://github.com/keiohta/tf2rl)
### 神经结构化学习
* [neural-structured-learning](https://github.com/tensorflow/neural-structured-learning)
### 强大的扩展
* [tensorflow/addons](https://github.com/tensorflow/addons)
### 迭代矩阵平方根归一化网络（称为快速MPN-COV），该网络非常有效，适合大规模数据集
* [XuChunqiao/Tensorflow-Fast-MPNCOV](https://github.com/XuChunqiao/Tensorflow-Fast-MPNCOV)
### TF-GAN是用于培训和评估生成对抗网络GAN的轻量级库。
* [tensorflow/gan](https://github.com/tensorflow/gan)
### 官方数据集包
* [tensorflow/datasets](https://github.com/tensorflow/datasets)


