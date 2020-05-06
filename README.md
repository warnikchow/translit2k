# translit2k
Sentence-level To-Korean Transliteration for Code-mixed G2P

## Environment
Under Python 3.6.6

## Install
```
git clone https://github.com/warnikchow/translit2k
cd translit2k
pip install -r Requirements.txt
git clone https://github.com/muik/transliteration
```
- Optional
```
git clone https://github.com/scarletcho/KoG2P
pip install https://github.com/Kyubyong/g2pK
```

## HowTo
In python console:
```
>>> from sentranslit import sentranslit as trans
>>> trans('1999년 8월29일은 john가 mary을 만난 날로 매년 3시15분 방 3-147에서 의식이 거행된다')
'천구백구십구년 팔월이십구일은 존이 메리를 만난 날로 매년 세시십오분 방 삼다시일사칠에서 의식이 거행된다'
```

## ToDo
DL-based en-ko transliteration module currently preparing deployment.
