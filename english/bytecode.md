# bytecode

<p><span class="chinese">获取待执行的下一个字节码。</span><span class="english">Fetches the next bytecode to execute.</span></p>

<p><span class="chinese">这使对字节码的切片和切块变得容易。</span><span class="english">This makes slicing and dicing your bytecode easy.</span></p>

<p><span class="chinese">从本质上说，我是在实现自己的字节码即时检验器。</span><span class="english">In essence, I was implementing my own on-the-fly validator for the bytecode.</span></p>

<p><span class="chinese">实际上，AOP可以视作是操作字节码的高阶语言。</span><span class="english">In fact, AOP can be seen as a high level language for bytecode manipulation.</span></p>

<p><span class="chinese">另一个可产生快速执行代码的方法就是直接产生JVM字节码。</span><span class="english">Another way to get fast executing code is to generate the JVM bytecode directly.</span></p>

<p><span class="chinese">您是否想转换方法，但是又不愿在字节码中启动程序呢？</span><span class="english">Do you want to try transforming methods, but are reluctant to start programming in bytecode?</span></p>

<p><span class="chinese">惟一的要求是字节码修改应该是确定性的且可预测的。</span><span class="english">The only proviso is that the bytecode modifications should be deterministic and predictable.</span></p>

<p><span class="chinese">这个切面在方法调用周围加入建立和停止StopWatch实例的字节码。</span><span class="english">This aspect surrounds method calls with bytecode that creates and stops a StopWatch instance.</span></p>

<p><span class="chinese">我也写一个字节码教程从写作角度喀拉喀托汇编代码。</span><span class="english">I also wrote a bytecode tutorial from the perspective of writing bytecode in Krakatau assembler.</span></p>

<p><span class="chinese">字节码的相关操作设计得十分细致，以确保子系统的紧密性与性能。</span><span class="english">Bytecode operations have been carefully designed to ensure subsystem compactness and performance.</span></p>

<p><span class="chinese">了解的字节码和类文件格式，最好的方法就是读JVM规范。</span><span class="english">The best way to learn about bytecode and the classfile format is to just read the JVM specification.</span></p>

<p><span class="chinese">在添加了堆栈状态跟踪之后，字节码问题的跟踪可以精确到代码的具体行。</span><span class="english">After I added the stack state tracking, bytecode problems became traceable to a particular line of code.</span></p>

<p><span class="chinese">是的，我们为虚拟机生成字节码，可以为多种架构产生不同的原生代码。</span><span class="english">Yes, we produce bytecode for the VM, which can optionally produce native code for several architectures.</span></p>

<p><span class="chinese">这很方便，如果不支持的话，编译器会一次生成基本兼容的字节码。</span><span class="english">It is convenient, if unsupported, and the compiler generates mostly compatible bytecode in a single pass.</span></p>

<p><span class="chinese">在上一期文章中，我演示了如何用运行时字节码生成来代替反射。</span><span class="english">In the earlier article, I demonstrated how run-time bytecode generation can be used to replace reflection.</span></p>

<p><span class="chinese">第一种方式是一种简单的字节码语言，您可以用它来创建脚本，并且将其下载到工作单元之中。</span><span class="english">The first is a simple bytecode language that you can use to create scripts that you download into the unit.</span></p>

<p><span class="chinese">在解析器使用字节码之后，我们目前实现的编译时优化有</span><span class="english">Some of the compile-time optimizations we're looking at, now that we have a bytecode representation, include</span></p>

<p><span class="chinese">它使用这种依赖关系树优化为每个应用和达尔维克缓存存储它的字节码。</span><span class="english">It uses this dependency tree to optimize the bytecode for every application and stores it in the Dalvik cache.</span></p>

<p><span class="chinese">即使适当地采取了这些安全性措施，也并非所有通过字节码验证的代码都被允许运行。</span><span class="english">Even with these security measures in place, not all code that passes bytecode verification should be allowed to run.</span></p>

<p><span class="chinese">如果被设置了，混淆器在把所有东西打包成.apk文件之前，自动地对应用程序字节码进行混淆处理。</span><span class="english">If it is, ProGuard automatically processes the application's bytecode before packaging everything into an .apk file.</span></p>

