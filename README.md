# MongoDB
Task 1

1.db.products.find({})

2.db.products.find({ product_price: { $gte: 400, $lte: 800 } })

3.db.products.find({ $or: [{product_price: { $lt: 400 } }, { product_price: { $gt: 600 } }] })

4.db.products.find({ product_price: { $gt: 500 } }).limit(4)

5.db.products.find({}, { _id: 0, product_name: 1, product_material: 1 })

6.db.products.find({ id: 10 })

7.db.products.find({}, { _id: 0, product_name: 1, product_material: 1 })

8.db.products.find({ product_material: { $regex: /soft/i } })

9.db.products.find({ product_color: "indigo", product_price: 492.00 })

10.db.products.deleteMany({ product_price: 28 })
