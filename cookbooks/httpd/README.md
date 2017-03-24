# httpd Cookbook

Httpd cookbook for: install, start, enable and configure httpd.



## Requirements

CentOs or any RedHat based distros.

### Platforms

- CentOs

### Chef

- Chef 12.0 or later

### Cookbooks

- `toaster` - httpd needs toaster to brown your bagel.

## Usage

### httpd::default

Just include `httpd` in your node's `run_list`:

```json
{
  "name":"my_node",
  "run_list": [
    "recipe[httpd]"
  ]
}
```

## Contributing

1. Fork the repository on Github
2. Create a named feature branch (like `add_component_x`)
3. Write your change
4. Write tests for your change (if applicable)
5. Run the tests, ensuring they all pass
6. Submit a Pull Request using Github

## License and Authors

Authors: Ahmad Moawad

