Read_Me! 

How to use it? 

1. Arrange df! : df must be setted as like [ item_text, .... ], it is very important to set the item_text on 'col = 0' , 'MakeShoprt' is setted to do embedding on col = 0
3. Make model: model = MakeShortForm()
4. Do embedding :  model.embedding(df)
5. Find_cluste : if you want to know how many clusters neded?, Use this Elbow Method, 'model.find_clustes()'
6. Short item! : shorted_df = model.short(n_clusters= x,  n_items = y ),  x is what you want clusters number , y is how many you want items

Use like this~! 
---

1. arrange df \n
   df = pd.read_csv('/content/drive/MyDrive/ex/big_5test_Tocsv.csv', index_col = 0)

3. Make model \n
   model = MakeShortForm()

5. Do embedding \n
   model.embedding(df)

7. Find_cluste \n
   model.find_nclustes()

9. Short item! \n
    shorted_df = model.short(n_clusters= 5,  n_items = 25)

11. fanal step \n use this index, or col = 0

---


