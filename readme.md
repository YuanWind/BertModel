# bert预训练模型  

google的bert预训练模型：  
		[BERT-Large, Uncased (Whole Word Masking)](https://storage.googleapis.com/bert_models/2019_05_30/wwm_uncased_L-24_H-1024_A-16.zip): 24-layer, 1024-hidden, 16-heads, 340M parameters  
		[BERT-Large, Cased (Whole Word Masking)](https://storage.googleapis.com/bert_models/2019_05_30/wwm_cased_L-24_H-1024_A-16.zip): 24-layer, 1024-hidden, 16-heads, 340M parameters  
		[BERT-Base, Uncased: 12-layer](https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-12_H-768_A-12.zip), 768-hidden, 12-heads, 110M parameters  
		[BERT-Large, Uncased: 24-layer](https://storage.googleapis.com/bert_models/2018_10_18/uncased_L-24_H-1024_A-16.zip), 1024-hidden, 16-heads, 340M parameters  
		[BERT-Base, Cased: 12-layer, 768-hidden](https://storage.googleapis.com/bert_models/2018_10_18/cased_L-12_H-768_A-12.zip), 12-heads , 110M parameters  
		[BERT-Large, Cased: 24-layer, 1024-hidden](https://storage.googleapis.com/bert_models/2018_10_18/cased_L-24_H-1024_A-16.zip), 16-heads, 340M parameters  
		[BERT-Base, Multilingual Cased (New, recommended)](https://storage.googleapis.com/bert_models/2018_11_23/multi_cased_L-12_H-768_A-12.zip): 104 languages, 12-layer, 768-hidden, 12-heads, 110M parameters  
		[BERT-Base, Multilingual Uncased (Orig, not recommended) (Not recommended, use Multilingual [Casedinstead)](https://storage.googleapis.com/bert_models/2018_11_03/multilingual_L-12_H-768_A-12.zip): 102 languages, 12-layer, 768-hidden, 12-heads, 110M parameters  
		[BERT-Base, Chinese](https://storage.googleapis.com/bert_models/2018_11_03/chinese_L-12_H-768_A-12.zip): Chinese Simplified and Traditional, 12-layer, 768-hidden, 12-heads, 110M parameters  

1. 先下载相应的预训练模型
2. 配置conf.py里边的路径
3. 利用extract_sen_vec.py 里的 gen_sen_vec()函数生成句向量，gen_word_vec()生成词向量