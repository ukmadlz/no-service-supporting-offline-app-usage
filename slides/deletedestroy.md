#  Delete / Destroy

```
db.remove(docId, [docRev], [options], [callback]);

db.get('wow', function(err, doc) {
  if (err) { return console.log(err); }
  db.remove(doc, function(err, response) {
    if (err) { return console.log(err); }
    // handle response
  });
});
```
