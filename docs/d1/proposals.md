# Proposals

Protocols improvement proposals.

## Key-value channel properties

Support for key-value based channel properties such that they can be individually retrieved and set,

Given a channel property such as:

```
topic=Programming,website=deavmi.assigned.network
```

### Setting key values

One would have been able to construct this with a command such as:

```
setProp,<channel>,topic,Programming
```

And a successive call to:

```
setProp,<channel>,website,deavmi.assigned.network
```

### Retrieving keys

One can retrieve a list of the keys for this channel property as so:

```
getKeys,<channel>
```

Which would return:

```
topic,website
```

### Retrieving values

One can retrieve the value of a given key of the channel's property via:

```
getprop,<channel>,topic
```

Which would return:

```
Programming
```

## Key-value status messages

Similiar to that of channel properties improvement mentioned above.
