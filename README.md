数组
栈
队列
链表
二分搜索树
堆

线段树
Trie
并查集

AVL
红黑树
哈希表

平摊分析：Amortized Analysis, resize时候会引入。
remove_last时resize太过着急，出现复杂度震荡，使用lazy方案：
扩容2倍，缩容1/2