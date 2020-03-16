# es6-es10_practice
es6-es10特性练习，以及一些算法题练习，每日更新，每日进步一点点。

初始代码双引号用的比较多，js中最好是用单引号，后来的代码练习有所改进。
### Array练习总结
主要从数组的遍历、转换、生成、查找四个方面进行了语法对比练习。
重点了解forin forof from of fill find filter
了解js中的可遍历元素有哪些（后面有个章节会讲到）
es5中关于数组的知识还有很多，自己再去练习。

### 类
主要从类的声明、创建、属性（getter setter）和方法（静态方法）、继承进行了对比练习。
了解es5和es6类的关联（es6的类就是es5的语法糖）。

### 函数
主要从函数的参数默认值、不确定参数、箭头函数三个方面进行了语法对比练习。
要注意箭头函数中的this指向。

### Object的更新
主要讲了对象属性的缩写、set和map新数据结构、对象的深拷贝浅拷贝。
WeakSet和WeakMap，和set、map相似，只是加了限定条件，只能接收对象。
区分静态方法和实例方法，实例方法用实例对象去调用，不能直接用Class.function调用。

### 正则 regexp
正则表达式后面加u修饰符可以解决很多问题，这里举例不全，可以去参考阮一峰es6入门那本书；
额外资料可参考：unicode和编码方式概述。

### Template
使用模板字符串 ``+${}符号进行字符串换行、变量、表达式的处理。
使用 函数名+模板字符串（Tag函数形式）可以创建具有逻辑关系处理的字符串模板。

### Promise
关于异步操作，要记得用Promise对象去解决。 
then、catch都是Promise的实例方法。
resolve、reject，还有all(全到才得)、race(先到先得)都是Promise的静态方法。

### Reflect
反射机制，很多为取代Object中原有方法而设计，令类和对象都作为Reflect中静态方法的参数，使得对类和对象的处理更加灵活。
静态方法：apply、construct、以及替代原有Object方法的对应方法（包括读写原型方法、读写属性等等）；注:Object中的一些方法正在逐渐向Reflect迁移，且后续Object可能会移除这些旧方法。所以尽量学习使用Reflect的方法代替原有方法。

### Proxy
讲了基础语法new Proxy(target,{set/get})、几种应用场景中的灵活使用、撤销代理。

### 其他
这里关于let/const、Array/Object Destructure（解构赋值）、正则、字符串模板后续再做更新。（前面两组分别位于阮一峰《ES6标准入门》的第一章和第二章）
symbol