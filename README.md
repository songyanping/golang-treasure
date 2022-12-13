# 引用golang-treasure工具包

示例：
```
import "github.com/songyanping/golang-treasure/pkg/utils"

func TestUtil(T *testing.T) {
    a1 := []string{"a", "b", "c"}
	a2 := utils.NewArrayUtil().ArrayToStr(a1)
	fmt.Println(a2)
}
```
