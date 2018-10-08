### ALL Soltuions



## sol918 

循环数值求最大和 ：sum 为当前联系和为0 prev 状态<0 置位0，更新一个max状态，内环和
同时求一个最小值， prev>0 更新为 0,特别注意 
### 当sum==prev 时，continue； 并非最小 。
最大为sum-prev 外环和

## sol919 binary tree 中序遍历
https://github.com/zengjichen/interview/blob/master/leetcode/Sol919.md

## sol919  DP 动态规划 
https://github.com/zengjichen/interview/blob/master/leetcode/Sol920.md
i，j j表示不同的歌曲，分为i和i-1， 考虑前面的i-1和j-1种，则第i为 N-（j-1）里面挑一种。
                                               a[i][j]+=a[i-1][j-1]*(j-k);
此外若j>k,可重复，则 a[i][j]+=a[i-1][j]*(j-k);
