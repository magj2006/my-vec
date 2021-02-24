# my-vec
Implementing Vec from scratch

### A Vec has:  
 - a pointer to allocation
 - the size of allocation
 - the number of elements

1. Layout  
    Unique 标准库的Unique没有对它的内容做任何有趣的保证，因此不需要new, 因此避免传入null

2. 关于内存分配文档中写的通过heap, 但是官方已经标记为不稳定， 所以改用alloc，希望后面能顺利