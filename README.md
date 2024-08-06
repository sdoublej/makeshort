Read_Me! 

How to use it? 

1. Arrange df! : df must be setted as like [ item_text, .... ], it is very important to set the item_text on 'col = 0' , 'MakeShoprt' is setted to do embedding on col = 0
3. Make model: model = MakeShortForm()
4. Do embedding :  model.embedding(df)
5. Find_cluste : if you want to know how many clusters neded?, Use this Elbow Method, 'model.find_clustes()'
6. Short item! : shorted_df = model.short(n_clusters= x,  n_items = y ),  x is what you want clusters number , y is how many you want items

Use like this~! 
---

1. arrange df
df = pd.read_csv('/content/drive/MyDrive/ex/big_5test_Tocsv.csv', index_col = 0)

3. Make model
model = MakeShortForm()

4. Do embedding
model.embedding(df)

5. Find_cluste
model.find_nclustes()

6. Short item!
shorted_df = model.short(n_clusters= 5,  n_items = 25)

7. fanal step, use this index, or col = 0

---


