# case

> case ... esac 与其他语言中的 switch ... case 语句类似，是一种多分枝选择结构.

- 通过字符串字面量判断执行分支:

`case {{入参变量}} in {{字符字面量1}} {{执行语句块1}} ;; {{字符字面量2}}) {{执行语句块2}} ;; *) {{默认执行语句块}} ;; esac`

- 搭配通配符进行匹配，判断执行分支:

`case {{入参变量}} in {{通配符或者字符字面量}}) {{执行语句块1}} ; ;; {{通配符或者字符字面量}}) {{执行语句块1}}; ;; *) {{echo "what?"}}; ;; esac`
