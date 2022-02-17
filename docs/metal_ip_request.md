## metal ip request

Request an IP block

### Synopsis

Example:

metal ip request --quantity [quantity] --facility [facility_code] --type [address_type]

	

```
metal ip request [flags]
```

### Options

```
  -c, --comments string     General comments
  -f, --facility string     Code of the facility
  -h, --help                help for request
  -p, --project-id string   Project ID (METAL_PROJECT_ID)
  -q, --quantity int        Number of IP addresses to reserve
      --tags strings        Tags to add, comma-separated for multiple, or repeat multiple times
  -t, --type string         Address type public_ipv4 or global_ipv6
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

* [metal ip](metal_ip.md)	 - IP operations

