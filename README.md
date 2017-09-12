## 使用方式

本分支修改了[https://github.com/CocoaPods/pod-template.git](https://github.com/CocoaPods/pod-template.git)中ruby的执行脚本，当执行`pod lib create zztest4 --template-url=https://github.com/ygm900/pod-template.git`命令时，原先脚本中提出的问题，将会被设置为如下默认答案：

问："What language do you want to use?", ["Swift", "ObjC"

答：objc

问："Would you like to include a demo application with your library", ["Yes", "No"]

答：yes

问："Which testing frameworks will you use", ["Specta", "Kiwi", "None"]

答：none

问："Would you like to do view based testing", ["Yes", "No"]

答：no

问："What is your class prefix"

答：ZZ

## Requirements:

- CocoaPods 1.0.0+
