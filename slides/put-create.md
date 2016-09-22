#  PUT Create

```
db.put(doc, [docId], [docRev], [options], [callback]);

var doc = {
  _id: "brumjs",
  event: "BrumJS",
  type: "conference",
  date: "2015-09-22"
}
db.put(doc, function(err, response) {
  if (err) { return console.log(err); }
  // handle response
});
```
