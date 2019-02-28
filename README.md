# test

Upstream 仓库已经修改了这里，现在我也修改这里，亦即现在两处是直接冲突的了 【这是本地修改后的内容】

此前 origin 与 Upstream 没有发生冲突，可以直接 pull ，现在发生冲突后，看直接 pull 会发生什么？【这是 Upstream 的内容】

此前已经 pull upstream ，现在修改本地文件，但 upstream 是没有变化的，然后再直接 pull upstream ，看会怎样？

git pull upstream master
From https://github.com/jing-chan/test
 * branch            master     -> FETCH_HEAD
Already up to date.

符合预期。