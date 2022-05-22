# script-money

1. *微信名或昵称：* moonly_v
2. *discord的ID：* k8ssssss | Ultiverse#1673
3. *擅长的建设领域、语言或工具、熟练度：* 目前在开发基于selenium的自动化测试工具，本职工作是渗透工程师，擅长传统web漏洞挖掘，熟悉Python和golang，3年经验。
4. *每周能花在业余项目的时间：* 30小时左右
5. *区块链建设经验（产品、项目、黑客松、技术文章、代码贡献、艺术创作等）：* 写过一些技术文章，目前在开发基于selenium的自动化测试工具和测试项目节点存活监控脚本。
6. *用任意编程语言计算以下公式*
![](https://latex.codecogs.com/svg.image?\sum_{n=1}^{100}\left&space;(n^{3}-\sqrt[3]{n}&space;\right&space;))

```python
print(sum(list(map(lambda n: n**3-pow(n,1/3), range(1,101)))))
#25502149.836096782
```

```go
package main

import (
 "fmt"
 "math"
)

func main() {
 var n float64
 var s float64
 for n < 101 {
  s += math.Pow(n, 3) - math.Pow(n, 1/3)
  n++
 }
 fmt.Printf("%v", s)
}
```
