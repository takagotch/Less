### Less
---
.rb
https://github.com/cowboyd/less.rb

.js
https://github.com/less/less.js



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

```css


```

