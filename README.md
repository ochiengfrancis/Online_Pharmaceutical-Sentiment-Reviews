# Online_Pharmaceutical-Sentiment-Reviews
This notebook is to analyse the sentiment of the drug users, according to reiews and various other features like the condition they are suffering from, the rating of the drugs used, data of the usage and others. Feature engineering will be perform to help predict the sentiments of the online customers based on their reviews, conditions and other variables.

           uniqueID         rating    usefulCount
count  161297.000000  161297.000000  161297.000000
mean   115923.585305       6.994377      28.004755
std     67004.445170       3.272329      36.403742
min         2.000000       1.000000       0.000000
25%     58063.000000       5.000000       6.000000
50%    115744.000000       8.000000      16.000000
75%    173776.000000      10.000000      36.000000
max    232291.000000      10.000000    1291.000000
*******************************************************************************
<class 'pandas.core.frame.DataFrame'>
RangeIndex: 161297 entries, 0 to 161296
Data columns (total 7 columns):
 #   Column       Non-Null Count   Dtype 
---  ------       --------------   ----- 
 0   uniqueID     161297 non-null  int64 
 1   drugName     161297 non-null  object
 2   condition    160398 non-null  object
 3   review       161297 non-null  object
 4   rating       161297 non-null  int64 
 5   date         161297 non-null  object
 6   usefulCount  161297 non-null  int64 
dtypes: int64(3), object(4)
memory usage: 8.6+ MB
None
********************************************************************************
uniqueID        int64
drugName       object
condition      object
review         object
rating          int64
date           object
usefulCount     int64
dtype: object
*********************************************************************************
uniqueID       False
drugName       False
condition       True
review         False
rating         False
date           False
usefulCount    False
dtype: bool

![image](https://user-images.githubusercontent.com/61507583/211147641-2a0fd803-346b-4641-956f-f81e683c40bc.png)
![image](https://user-images.githubusercontent.com/61507583/211147646-3fdb581a-38ea-4bf7-bcf2-33c2eac710bf.png)
![image](https://user-images.githubusercontent.com/61507583/211147651-e70e17cc-1629-46a0-bce8-73f8050fe218.png)
![image](https://user-images.githubusercontent.com/61507583/211147658-9e849870-9f82-4469-8b94-4c24ee87e3c4.png)
![image](https://user-images.githubusercontent.com/61507583/211147668-d6ac6f3b-45b6-491c-bd1c-86ed6099395f.png)
![image](https://user-images.githubusercontent.com/61507583/211147675-53c1abc1-3635-45ca-a846-3d7db3def39b.png)
![image](https://user-images.githubusercontent.com/61507583/211147680-5ba31d0f-5e38-4681-804f-df21295e9fea.png)
![image](https://user-images.githubusercontent.com/61507583/211147690-fe29b482-05ae-43b4-9681-b988d8607aed.png)
![image](https://user-images.githubusercontent.com/61507583/211147748-89d012d0-78b1-43fd-8784-c50c2b5df504.png)
![image](https://user-images.githubusercontent.com/61507583/211147784-2f687ccd-f5d7-45d8-bdd8-1716f3687485.png)








