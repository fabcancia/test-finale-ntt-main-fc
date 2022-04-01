# Solutions NoSQL

## Queries

1. `db.ristoranti.find().sort({"name":1})`
2. `db.ristoranti.find({"grades.score" : {$mod :[7,0]}},{"restaurant_id" : 1, "name" : 1, "grades" : 1})`
3. `db.ristoranti.find({"address.coord.1" : {$gt : 42, $lte : 52}},{"restaurant_id" : 1, "name" : 1, "address" : 1,"coord" : 1})`
4. `db.ristoranti.find({ "grades.1.date": ISODate("2014-08-11T00:00:00Z"), "grades.1.grade":"A" ,    "grades.1.score" : 9 }, {"restaurant_id" : 1,"name":1,"grades":1})`
5. `db.ristoranti.find({$or: [{name: /^Wil/},{"$and": [{"cuisine" : {$ne :"American"}}, {"cuisine" : {$ne :"Chinese"}}]}]},{"restaurant_id" : 1,"name":1,"borough":1,"cuisine" :1})`
 
## Multiple Questions

1. B
2. D
3. C
4. C
5. A
6. C
7. D