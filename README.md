# bert-bilstm-crf
pytorch
1、程序描述：用pytorch 搭建了bert+bilstm+crf的模型，实现了命名实体识别。

2、运行环境
   torch 1.0.0
   python 3.6
   pytorch_pretrained_bert 0.6
   
3、程序结构
   ---bert_lstm_crf_pytorch
      --data
        -data/bert   存放bert模型
        -data/model  存放训练好的模型
        -data/train.txt   训练集
        -data/test.txt    测试集
      --model
         -model/bert_lstm_crf.py   bert+bilstm+crf模型
         -model/crf.py
      --constants.py   训练过程中用到的超参数
      --train.py      
      --utils.py
 
 4、运行方法
   4.1 下载bert pytorch的模型，放入data/bert文件夹中，可以下载我用的模型，链接：https://pan.baidu.com/s/1EjHdPtIa-Nbsy6KblSKhug 
       提取码：2nlz 
   4.2 CUDA_VISBLE_DEVICES = 1 python train.py
 
 5、说明
    研一第一次写，写的不好，请多多指教。
 
