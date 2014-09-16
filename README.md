bountiful-test
=============

[![Build Status](https://travis-ci.org/example/bountiful-test.png?branch=master)](https://travis-ci.org/example/bountiful-test)

Quick Start
-----------


Attributes
----------

* `node['bountiful-test']['option']` – Description of option. *(default: something)*

Resources
---------

### bountiful_test

The `bountiful_test` resource defines a something.

```ruby
bountiful_test 'name' do
  option 'a'
end
```

* `option` – Description of option. *(default: node['bountiful-test']['option'])*
