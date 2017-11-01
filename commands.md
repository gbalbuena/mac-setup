

# Commands

## rm

Delete everything except ```*.txt```

`find . -type f -not -name '*.txt' -print0 | xargs -0 rm --`

