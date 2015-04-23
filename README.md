# code_generator

Cookbook to be used by ChefDK to generate things ... like cookbooks.

## Usage

1. Clone to a directory
2. Reference directory when using `chef` to genereate a new cookbook

**Note**: The directory you clone to must match this "cookbook's" name ... in this case 'code_generator'.

### Example

```
chef generate cookbook test_cookbook -C 'Jacob McCann' -m 'jmccann.git@gmail.com' -g ~/chef/cookbook_generator
```

## License and Authors

Author:: Jacob McCann (<jmccann.git@gmail.com>)

With help from:
* https://medium.com/@echohack/creating-your-own-chef-cookbook-generator-5e998db1255b
* https://github.com/chef/chef-dk/tree/master/lib/chef-dk/skeletons/code_generator
