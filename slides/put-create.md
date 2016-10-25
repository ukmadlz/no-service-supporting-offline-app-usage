#  PUT Create

```
db.put(doc, [docId], [docRev], [options], [callback]);

var doc = {
  _id: "wow",
  event: "World of Watson",
  type: "conference",
  date: "2016-10-25"
}
db.put(doc, function(err, response) {
  if (err) { return console.log(err); }
  // handle response
});
```
