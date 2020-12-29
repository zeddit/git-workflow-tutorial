# git-workflow-tutorial

learn git workflow by doing!

理解workflow机制，各种branch机制及其在github network graph上的效果，如commit history的保留情况，分支情况等等。

### Conclusion

1. merge 操作可以看到分支汇聚，但删除已merge的分支后，只剩下主分支；

2. rebase 操作看不到分叉的分支，主分支和子分支完全一致；

最终在主分支上实现的效果是一致的；子分支由于merge后会删除，没有影响。
