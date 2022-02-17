## metal user get

Retrieves information about the current user or a specified user.

### Synopsis

Returns either information about the current user or information about the specified user, if it is available. User information is typically only available if the user shares projects with the current user.

```
metal user get [-i <User_UUID>] [flags]
```

### Examples

```
  # Retrieve information about the current user:
  metal user get

  # Retrieve the information of the user with UUID 25862acd-c71e-4322-a2ef-5b73fdf5c5b2:
  metal user get -i 25862acd-c71e-4322-a2ef-5b73fdf5c5b2
```

### Options

```
  -h, --help        help for get
  -i, --id string   UUID of the user
```

### Options inherited from parent commands

```
      --config string        Path to JSON or YAML configuration file
      --exclude strings      Comma seperated Href references to collapse in results, may be dotted three levels deep
      --filter stringArray   Filter 'get' actions with name value pairs.
                              Filter is not supported by all resources and is implemented as request query parameters.
      --include strings      Comma seperated Href references to expand in results, may be dotted three levels deep
  -o, --output string        Output format (*table, json, yaml)
      --search string        Search keyword for use in 'get' actions. Search is not supported by all resources.
      --sort-by string       Sort fields for use in 'get' actions. Sort is not supported by all resources.
      --sort-dir string      Sort field direction for use in 'get' actions. Sort is not supported by all resources.
      --token string         Metal API Token (METAL_AUTH_TOKEN)
```

### SEE ALSO

* [metal user](metal_user.md)	 - User operations

