文档/文件夹名	                         说明	                                                                     效果
RNN+LSTM.pptx	  rnn缺点，lstm如何改进，其结构介绍	
     lstm1	                  较简单的lstm模型	                                                预测结果随训练代数增多而精确
     lstm2	                  随机生成偏置权值，计算交叉熵训练模型	                预测结果随训练代数增多而精确
 lstm_poems	  lstm生成五言古诗	                                                预计效果为根据输入文字生成藏头诗


lstm_poems博文链接：

https://blog.csdn.net/weixin_44791964/article/details/104092269?ops_request_misc=%257B%2522request%255Fid%2522%253A%2522159126763519725247613278%2522%252C%2522scm%2522%253A%252220140713.130102334.pc%255Fblog.%2522%257D&request_id=159126763519725247613278&biz_id=0&utm_medium=distribute.pc_search_result.none-task-blog-2~blog~first_rank_v1~rank_blog_v1-1-104092269.pc_v1_rank_blog_v1&utm_term=%E8%AF%97

		
lstm_poems的GitHub链接：

https://github.com/bubbliiiing/poems-generator		

		
lstm_poems程序运行报错未解决，如果您运行成功可以分享一下给我，谢谢
报错信息：
InvalidArgumentError (see above for traceback): No OpKernel was registered to support Op 'CudnnRNN' used by node cu_dnnlstm_1/CudnnRNN (defined at D:\anaconda3\envs\tensorflow-gpu\lib\site-packages\keras\layers\cudnn_recurrent.py:517) with these attrs: [is_training=true, seed2=0, input_mode="linear_input", T=DT_FLOAT, dropout=0, rnn_mode="lstm", direction="unidirectional", seed=87654321]
Registered devices: [CPU]
Registered kernels:
  device='GPU'; T in [DT_HALF]
  device='GPU'; T in [DT_FLOAT]
  device='GPU'; T in [DT_DOUBLE]

         [[node cu_dnnlstm_1/CudnnRNN (defined at D:\anaconda3\envs\tensorflow-gpu\lib\site-packages\keras\layers\cudnn_recurrent.py:517) ]]
