# my-vec
Implementing Vec from scratch

### A Vec has:  
 - a pointer to allocation
 - the size of allocation
 - the number of elements

1. Layout  
    Unique 标准库的Unique没有对它的内容做任何有趣的保证，因此不需要new, 因此避免传入null