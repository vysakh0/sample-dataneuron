This project uses dataneuron with csv as the datasource


https://github.com/user-attachments/assets/5d767894-b52e-4233-8e6c-30bb3ca771b3

Install

```
pip install dataneuron[csv]
```

I have created a context called product. Please the folder inside context called `product`

You can customise the content except the structure of the table name, column names, `names`
are important.

```
dnn --chat product
```

Ask questions like `email of jane`, note jane is not in the sample data, you can add new data
to the csv file and playaround for the accuracy.

Once you feel it is ready, you can then start using it through SDK or API.
Please chek https://www.dataneuron.dev/ for more.



