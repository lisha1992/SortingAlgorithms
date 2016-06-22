# Searching Algorithms

1. Sequential Search </br>
从数据结构线形表的一端开始，顺序扫描，依次将扫描到的结点关键字与给定值k相比较，若相等则表示查找成功；若扫描结束仍没有找到关键字等于k的结点，表示查找失败。</br>
查找成功时的平均查找长度为:  (n+1)/2. </br>
查找不成功时，需要n+1次比较，时间复杂度为O(n).</br>

2. Binary Search</br>
用给定值k先与中间结点的关键字比较，中间结点把线形表分成两个子表若相等则查找成功；若不相等，再根据k与该中间结点关键字的比较结果确定下一步查找哪个子表，这样递归进行，直到查找到或查找结束发现表中没有这样的结点。</br>
最坏情况下，关键词比较次数为log2(n+1)，且期望时间复杂度为O(log2n)</br>




# Sorting Algorithms

1. Merge sort</br>
 divide and conquer algorithm </br>
Step1: Divide the unsorted list into n sublists, each containing 1 element (a list of 1 element is considered sorted).
Step2: Repeatedly merge sublists to produce new sorted sublists until there is only 1 sublist remaining. This will be the sorted list.  </br>
Dividing: divide the original list into 2 parts until each sublist only has 1 element </br>
Sorting by list[0] </br>
Merging the sorted lists.  </br>






   
