# Label selectors
inside **{}** brackets

- equals: **=**
- not equals: **!=**
- regexp match: **~**
- regexp not match: **!~**

# Range selector
inside **[]** brackets

time values:
- s
- m
- h
- d
- w
- y

# Offset
keyword **offset**

time values:
- s
- m
- h
- d
- w
- y

# Select time

keyword **@**

value epoch

# Operators

## math operators



node_cpu_seconds_total{cpu='0'} / 100

## comparison operators

### filtering
node_cpu_seconds_total{cpu='0'} > 100

### calculate bool
node_cpu_seconds_total{cpu='0'} > bool 100

### logica
- AND
- OR
- UNLESS