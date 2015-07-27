<img src="images/cover.png"/>

# 关于本书

这本书的主题是函数范式（Functional paradigm），我们将使用世界上最流行的函数式编程语言：JavaScript 来讲述这一主题。可能一些人会觉得选择 JavaScript 有违当前对这门语言的主流看法：它主要是命令式（Imperative）的。但我认为，这是学习函数式编程的最好方式，因为：

 * 你很有可能在日常工作中使用它

    这让你有机会在实际的编程过程中学以致用，而不是在空闲时间使用一门晦涩的函数式编程语去做一些玩具性质的项目。

 * 你不必从头学起就能开始编写程序

    在纯函数式编程语言中，你必须使用 monad 才能打印变量或者读取 DOM 节点。这里随着学习如何净化代码库，我们可以使用一些小技俩实现上述效果。JavaScript 也更容易入门，因为它是一门混合范式的语言，你随时可以在感觉吃力的时候退回到原有的编程习惯上去。

 * 这门语言完全有能力书写高级的函数式代码

    只需借助一到两个微型类库就能提供模拟类似 Scala 或 Haskell 这类语言所需的全部特性。虽然面向对象编程（Object-oriented programing）思想主导着业界，但很明显 OOP 在 JavaScript 里非常古怪：就像在高速公路上露营或者穿着橡胶套鞋跳踢踏舞。我们不得不到处使用 `bind` 以防 `this` 不知不觉地变了，这门语言里没有类[^目前还没有]，我们还发明了各种各样的变通方法来应对忘记调用 `new` 关键字的情况，私有成员只有通过闭包（Closure）才能实现。对大多数人来说，函数式编程看起来更加自然。

以上说明，强类型的函数式语言毫无疑问将会成为本书所示范式的最佳试验场。JavaScript 是我们学习这种范式的一种手段，你将它应用于什么地方完全取决于你自己。幸运的是，所有的接口都是数学的，因而也是普适的。最终你会发现你习惯了 swiftz、scalaz、haskell 和 purescript，以及其他各种数学偏向的语言。

# 目录

## 第 1 部分

* [第 1 章: 我们在做什么？](ch1.md)
  * [介绍](ch1.md#介绍)
  * [一个简单例子](ch1.md#一个简单例子)
* [第 2 章: 一等公民的函数](ch2.md)
  * [快速概览](ch2.md#快速概览)
  * [为何钟爱一等公民](ch2.md#为何钟爱一等公民)
* [第 3 章: 纯函数的好处](ch3.md)
  * [再次强调“纯”](ch3.md#再次强调“纯”)
  * [副作用可能包括...](ch3.md#副作用可能包括)
  * [八年级数学](ch3.md#八年级数学)
  * [追求“纯”的理由](ch3.md#追求“纯”的理由)
  * [总结](ch3.md#总结)
* [第 4 章: 柯里化（currying）](ch4.md)
  * [没你就活不下去](ch4.md#没你就活不下去)
  * [不仅仅是双关语／特殊的酱料](ch4.md#不仅仅是双关语／特殊的酱料)
  * [总结](ch4.md#总结)
* [第 5 章: 代码组合](ch5.md)
  * [函数饲养](ch5.md#函数饲养)
  * [pointfree](ch5.md#pointfree)
  * [debug](ch5.md#debug)
  * [范畴论](ch5.md#范畴论)
  * [总结](ch5.md#总结)
* [Chapter 6: Example Application](ch6.md)
  * [Declarative Coding](ch6.md#declarative-coding)
  * [A flickr of functional programming](ch6.md#a-flickr-of-functional-programming)
  * [A Principled Refactor](ch6.md#a-principled-refactor)
  * [In Summary](ch6.md#in-summary)

## Part 2

* [Chapter 7: Hindley-Milner and Me](ch7.md)
  * [What's your type?](ch7.md#whats-your-type)
  * [Tales from the cryptic](ch7.md#tales-from-cryptic)
  * [Narrowing the possibility](ch7.md#narrowing-the-possibility)
  * [Free as in theorem](ch7.md#free-as-in-theorem)
  * [In Summary](ch7.md#in-summary)
* [Chapter 8: Tupperware](ch8.md)
  * [The Mighty Container](ch8.md#the-mighty-container)
  * [My First Functor](ch8.md#my-first-functor)
  * [Schrödinger’s Maybe](ch8.md#schrodingers-maybe)
  * [Pure Error Handling](ch8.md#pure-error-handling)
  * [Old McDonald had Effects…](ch8.md#old-mcdonald-had-effects)
  * [Asynchronous Tasks](ch8.md#asynchronous-tasks)
  * [A Spot of Theory](ch8.md#a-spot-of-theory)
  * [In Summary](ch8.md#in-summary)
* [Chapter 9: Monadic Onions](ch9.md)
  * [Pointy Functor Factory](ch9.md#pointy-functor-factory)
  * [Mixing Metaphors](ch9.md#mixing-metaphors)
  * [My chain hits my chest](ch9.md#my-chain-hits-my-chest)
  * [Theory](ch9.md#theory)
  * [In Summary](ch9.md#in-summary)



# Plans for the future

* Part 1 is a guide to the basics. I'm updating as I find errors since this is the initial draft. Feel free to help!
* Part 2 will address type classes like functors and monads all the way through to traversable. I hope to squeeze in transformers and a pure application.
* Part 3 will start to dance the fine line between practical programming and academic absurdity. We'll look at comonads, f-algebras, free monads, yoneda, and other categorical constructs.


