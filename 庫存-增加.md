#一、 商品增加
1. admin/controller/catalog/product.php
```
public function add();
```

2. admin/model/catalog/product.php
```
public function addProduct($data);
```

#二、 必要欄位
1. product_id
2. model
3. quantity(自訂)
4. stock_status_id


#三、 初步計畫
1. 先同步這四個欄位
2. 有必要可能要調整欄位屬性(PrimaryKey)
