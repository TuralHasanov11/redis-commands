# redis-commands

### Install Redis
```
sudo apt-get install redis
```

### Start Redist Server
```
redis-server
```

### Run CLI
```
redis-cli
```

### Quit
```
quit
```

### Insert data
```
SET name Jon
```

### Get data
```
GET name
```

### Delete data
```
DEL name
```

### Check data if exists
```
EXISTS name
```

### Get all keys
```
KEYS *
```

### Delete all keys
```
flushall
```

### Check expiration time
```
ttl name
```

### Set expiration after given seconds
```
expire name 10
```

### Insert data with expiration time
```
setex name 10 Jon
```

### Create or add value to array at the beginning or at the end
```
LPUSH arr Jon
RPUSH name Jon
```

### Iterate over array
```
LRANGE arr 0 -1
LRANGE arr 0 2
```

### Remove data from array from left or right
```
LPOP arr
RPOP arr
```

### Create or add data to set
```
sadd dataSet "Berrick"
```

### Get all data in set
```
smembers dataSet
```

### Remove data from set
```
srem dataSet "Jon"
```

### Create or insert data into hash
```
HSET person name Jon
```

### Get data from hash
```
HGET person name
```

### Check if data exist in hash
```
HEXISTS person name
```

### Remove data from hash
```
HDEL person name
```


