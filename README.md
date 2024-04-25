# CMCN
This is the code and data for our paper：“Chinese Medical Concept Normalization Using Continual Learning and Knowledge-Enhanced” This research involves three tasks altogether, and the code used in each task has been given the corresponding web disk link.

# Requirements
We have a requirements.txt file in each code download link, which allows you to run the following code after downloading：<br>
```
pip install -r requirements.txt
```

# Run
Each download link will include a complete model and the trained model. After downloading to local and installing the running environment, training can be performed through "bert_model_train.py", or testing can be performed through "bert_model_test.py", The expected structure of files is (Below is an example of the directory tree for "Multi_task_CNN_BERT（涉及了带辅助任务和不带辅助任务的" ):<br>
```
├─.idea
│  └─inspectionProfiles
├─1
│  ├─.idea
│  │  └─inspectionProfiles
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─1_dict
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─2
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─2_dict
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─3
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─3_dict
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─4
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─4_dict
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─5
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
├─5_dict
│  ├─bert
│  │  └─__pycache__
│  ├─data
│  │  └─JB
│  ├─model
│  │  ├─bert
│  │  └─chinese_L-12_H-768_A-12
│  ├─util
│  │  └─__pycache__
│  └─__pycache__
└─DICT
    ├─ccks
    │  ├─1_dict
    │  │  ├─bert
    │  │  │  └─__pycache__
    │  │  ├─data
    │  │  │  └─JB
    │  │  ├─model
    │  │  │  ├─bert
    │  │  │  └─chinese_L-12_H-768_A-12
    │  │  ├─util
    │  │  │  └─__pycache__
    │  │  └─__pycache__
    │  ├─2_dict
    │  │  ├─bert
    │  │  │  └─__pycache__
    │  │  ├─data
    │  │  │  └─JB
    │  │  ├─model
    │  │  │  ├─bert
    │  │  │  └─chinese_L-12_H-768_A-12
    │  │  ├─util
    │  │  │  └─__pycache__
    │  │  └─__pycache__
    │  ├─3_dict
    │  │  ├─bert
    │  │  │  └─__pycache__
    │  │  ├─data
    │  │  │  └─JB
    │  │  ├─model
    │  │  │  ├─bert
    │  │  │  └─chinese_L-12_H-768_A-12
    │  │  ├─util
    │  │  │  └─__pycache__
    │  │  └─__pycache__
    │  ├─4_dict
    │  │  ├─bert
    │  │  │  └─__pycache__
    │  │  ├─data
    │  │  │  └─JB
    │  │  ├─model
    │  │  │  ├─bert
    │  │  │  └─chinese_L-12_H-768_A-12
    │  │  ├─util
    │  │  │  └─__pycache__
    │  │  └─__pycache__
    │  └─5_dict
    │      ├─bert
    │      ├─data
    │      │  └─JB
    │      ├─model
    │      │  ├─bert
    │      │  └─chinese_L-12_H-768_A-12
    │      ├─util
    │      │  └─__pycache__
    │      └─__pycache__
    └─ICD10
        ├─1_dict
        │  ├─bert
        │  │  └─__pycache__
        │  ├─data
        │  │  └─JB
        │  ├─model
        │  │  ├─bert
        │  │  └─chinese_L-12_H-768_A-12
        │  ├─util
        │  │  └─__pycache__
        │  └─__pycache__
        ├─2_dict
        │  ├─bert
        │  │  └─__pycache__
        │  ├─data
        │  │  └─JB
        │  ├─model
        │  │  ├─bert
        │  │  └─chinese_L-12_H-768_A-12
        │  ├─util
        │  │  └─__pycache__
        │  └─__pycache__
        ├─3_dict
        │  ├─bert
        │  │  └─__pycache__
        │  ├─data
        │  │  └─JB
        │  ├─model
        │  │  ├─bert
        │  │  └─chinese_L-12_H-768_A-12
        │  ├─util
        │  │  └─__pycache__
        │  └─__pycache__
        ├─4_dict
        │  ├─bert
        │  │  └─__pycache__
        │  ├─data
        │  │  └─JB
        │  ├─model
        │  │  ├─bert
        │  │  └─chinese_L-12_H-768_A-12
        │  ├─util
        │  │  └─__pycache__
        │  └─__pycache__
        └─5_dict
            ├─bert
            │  └─__pycache__
            ├─data
            │  └─JB
            ├─model
            │  ├─bert
            │  └─chinese_L-12_H-768_A-12
            ├─util
            │  └─__pycache__
            └─__pycache__
```

# Basic experiment
The code for thirteen basic model experiments is published<br>

CNN Link: https://pan.quark.cn/s/3938563c1667 Extract code: h4GK<br>

CNN+AT Link: https://pan.quark.cn/s/d41c212c0a0a Extract code: LwG1<br>

GRU Link：https://pan.quark.cn/s/506237a235d0 Extract code：RK35<br>

GRU+AT Link：https://pan.quark.cn/s/506237a235d0 Extract code：RK35<br>

LINUXS Link：https://pan.quark.cn/s/2a867f2a1206 Extract code：sjJt<br>

LSTM Link：https://pan.quark.cn/s/6771c6d38117 Extract code：DLtK<br>

LSTM+AT Link：https://pan.quark.cn/s/45f467b258f2 Extract code：VaYT<br>

Random quantifier Link：https://pan.quark.cn/s/670edac70f0a Extract code：gARi<br>

Random vector word Link：https://pan.quark.cn/s/93ee5414f08a Extract code：NfzE<br>

External semantic feature Link：https://pan.quark.cn/s/3e60eb5ab8a0 Extract code：qFns<br>

Vector combination experiment Link：https://pan.quark.cn/s/a857ded18043 Extract code：fgXm<br>

English random vector Link：https://pan.quark.cn/s/2a1e30e3cbd1 Extract code：q5aX<br>

# Multi-tasking, BERT, hybrid neural networks
Below are some model experiments of multi-tasking, bert, and hybrid neural networks<br>

BERT_sentence Link：https://pan.quark.cn/s/a7b4c072a126 Extract code：q2MC<br>

BERT_X_CNN Link：https://pan.quark.cn/s/f58801aa05ee Extract code：x2Bq<br>

BERT_word Link：https://pan.quark.cn/s/c201c413ecd4 Extract code：uZKA<br>

BiGRU_CNN Link：https://pan.quark.cn/s/3a2ac226967c Extract code：iDBG<br>

BiLSTM_CNN Link：https://pan.quark.cn/s/a869a9b53f63 Extract code：uSMU<br>

chinese_L-12_H-768_A-12 Link：https://pan.quark.cn/s/3b93a0e4fa8a Extract code：JnZA<br>

Multi_task_CNN_BERT(Both with and without auxiliary tasks) Link：https://pan.quark.cn/s/a8b4b617e4af Extract code：JT6j<br>

# Continuous learning experiment
Here are some experiments for continuous learning<br>

1_dict_dynamic Link：https://pan.quark.cn/s/f22ae5fe7c38 Extract code：9F4R<br>

Part-of-speech experimental isolation Link：https://pan.quark.cn/s/899059ebca2a Extract code：aqTL<br>

dynamic_bert(BERT led continuous learning) Link：https://pan.quark.cn/s/73fe8bbd2c38 Extract code：RjJT<br>

dynamic_GCNN(GCNN led continuous learning) Link：https://pan.quark.cn/s/a395af85345a Extract code：LuMz<br>

E_x_fuse(Power function continuous learning) Link：https://pan.quark.cn/s/fa4f149d9783 Extract code：aK5i<br>

Ln_fuse(Logarithmic functions continue to learn）Link：https://pan.quark.cn/s/022827b3a7e4 Extract code：iTxc<br>

n_AND_ICD10（An optimal model combining parts of speech and dictionaries）Link：https://pan.quark.cn/s/4ce27d8c4331 Extract code：DBUB<br>

PartOfSpeech_a Link：https://pan.quark.cn/s/117296aa7442 Extract code：LzDB<br>

PartOfSpeech_d Link：https://pan.quark.cn/s/21ef8ffbd83c Extract code：mWgZ<br>

PartOfSpeech_n Link：https://pan.quark.cn/s/5b23640a30f8 Extract code：Ai83<br>

PartOfSpeech_v Link：https://pan.quark.cn/s/32d36fd4c1ae Extract code：Vz7i<br>
