# vector

## 简介（后期可能会继续添加）
1.vector是STL中的循序容器，是一种动态的数组。vector的存储被自动处理，根据需要被扩展或者收缩。但由于vector中存放有额外的信息用来记录数据（如：大小，容量等等），因此，通常它比静态数组占用更多的内存空间。

2.与关联容器不同，vector中的元素存放是连续的，这意味着我们即可以通过iterator操作，也可以通过传统指针加上偏移量来进行操作。

3.vector优先于动态分配的数组。因为通过使用new申请的内存空间，存在内存泄漏的危险，有时还会泄漏资源和破坏内存。

4.vector的容量每次以2的倍数增长。 

5.vector存在一个特例化vector<bool>

6.特别值得一提的是，vector是C++通向C和其他语言的通道。

7.注意迭代器失效的情况

## 资料
《Effective STL》 13 - 18条