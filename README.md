### Simple find shoe with HTTP get call

```
intent {
  goal: FindShoe
}
```

### HTTP call with query param

```
intent {
  goal: FindShoeFiltering
  value: Type(Formal)
}
```

### HTTP call that returns an error

```
intent {
  goal: FindShoeError
}
```

### HTTP use that includes headers

```
intent {
  goal: FindShoeReturnHeaders
}
```

### HTTP post call

```
intent {
  goal: CreateShoe
}
```

### Remote endpoint

```
intent {
  goal: FindShoeRemoteEndpoint
}
```

### Coming soon: More complicated remote endpoint