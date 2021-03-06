# IIS URL Rewrite 2.0 Cookbook

[![Cookbook Version](https://img.shields.io/cookbook/v/iis_urlrewrite.svg)](https://supermarket.chef.io/cookbooks/iis_urlrewrite)

This cookbook downloads and installs the IIS URL Rewrite 2.0 extension into Microsoft Internet Information Server.

## Requirements

### Platforms

- Windows 2008 or higher
- IIS 7 or 7.5\. IIS 8 may be supported as well, though Microsoft's documentation does not call it out as being explicitly supported by the module.
### Chef

- Chef 12.6+

### Cookbooks

- iis

## Usage

Add `recipe[iis_urlrewrite]` to your node's run_list.

## License and Author


**Author:** Julian Dunn ([jdunn@chef.io](mailto:jdunn@chef.io))

**Copyright:** 2014-2017, Chef Software, Inc.

```
Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
```
