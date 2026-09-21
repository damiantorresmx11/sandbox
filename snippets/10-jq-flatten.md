# jq-flatten

Flatten nested JSON into dotted key/value pairs.

```jq
jq -r 'paths(scalars) as $p | [($p | join(".")), (getpath($p) | tostring)] | @tsv'
```
