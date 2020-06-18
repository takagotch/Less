### Less
---
https://github.com/cowboyd/less.rb

http://lesscss.org/

```ruby
parser = Less::Parser.new
parser = Less::Parser.new :paths => ['./lib', 'other/lib'], :filenaem => 'mystyles.less'

tree = parser.parse(".class {width: 1+1}")
tree.to_css
tree.to_css(:compress => true)

```

```
bundle
rake

```

```
```

