### algorithms
---
.rb
https://github.com/kanwei/algorithms

.py
https://github.com/keon/algorithms

.go
https://github.com/shady831213/algorithms

```ruby
require 'rubygems'
require 'algorithms'

max_heap = Containers::MaxHeap.new

include Containers
max_heap = MaxHeap.new
```

```py
from algorithms.sort import merge_sort

if __name__ == "__main__":
  my_list = [1, 8, 3, 5, 6]
  my_list = merge_sort(my_list)
  print(my_list)
```

```go
func (h *IntArray) Union(i interface{}) interface{} {
  h.heapIntArrays = h.heapIntArrays.Union(&(i.(*IntArray).heatIntArrays)).(heapIntArrays)
  h.heap.BuildHeap()
  return h
}

```


