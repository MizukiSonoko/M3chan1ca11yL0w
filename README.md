
# Code for Law
![Logo](https://s3-ap-northeast-1.amazonaws.com/mizukisonoko/MLlogo.png)  
  
## Concept
```
if(法律 == Code){ 
    ...
```

## Sample
 

### 判例データ
```
重大な過失がある(X):-
	居眠り運転(X).
```
### 状態
```
運転者(甲,車両).
居眠り運転(甲).
建造物(会津大学).
所有(県,会津大学).
```

### Judgement
```
?- 罰則(甲,損壊,会津大学,B).
B = 六月以下の禁錮又は十万円以下の罰金 .
```

