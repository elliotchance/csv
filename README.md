# csv

- [func Read(f os.File) []string](#Read)
- [func Write(f os.File, fields []string)](#Write)

## Read

```
func Read(f os.File) []string
```

Read fetches the next CSV line from the file. If there is no more data to be
read the returned array will have zero elements.

## Write

```
func Write(f os.File, fields []string)
```

Write will append a new record to the file. The fields must contain at least
one element.

