# bolg-test
## 这是我写的第一行java代码
`System.out.println("Hello World");`
****
## 这是我写的一个代码片段
```java
private static void printFields(Class cl) {
        Field[] fields = cl.getDeclaredFields();

        for (Field f : fields) {
            Class type = f.getType();
            String name = f.getName();
            System.out.print("\t");
            String modifiers = Modifier.toString(f.getModifiers());
            if (modifiers.length() > 0) System.out.print(modifiers + " ");
            System.out.println(type.getName() + " " + name + ";");
        }
   }
```
****
## 我平时的爱好是
* 唱
* 跳
* rap
* ~~足球~~ 篮球
****
## 我最喜欢的明星是
1. 新垣结衣
2. 石原里美
3. 花泽香菜
