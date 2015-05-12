The project is on hold from some time as there are pending bugs on OS X/Linux with .NET runtime based on `mono`:  
https://github.com/aspnet/Home/issues/498

# M101Blog
A place to create a Blog from M101N course when finished

## DB restore command:

```
echo db.dropDatabase() | mongo blog
mongorestore dump
mongo blog
```
