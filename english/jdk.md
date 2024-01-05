# jdk

<p><span class="chinese">JDK模块化使用了Jigsaw模块化系统。</span><span class="english">JDK modularization uses the Jigsaw module system.</span></p>

<p><span class="chinese">当时的跨平台编译器运行良好，但只能在JDK上运行。</span><span class="english">The cross-compiler was an excellent piece of work but ran on JDK only.</span></p>

<p><span class="chinese">据Bloch所说，连JDK自己的close方法都有三分之二实现的不正确。</span><span class="english">Two thirds of the uses of the close method in the JDK itself are implemented incorrectly according to Bloch.</span></p>

<p><span class="chinese">还有一个遗留问题是JDK动态代理，由于他们对代理接口的限制因此很少需要集成。</span><span class="english">One of the remaining issues are JDK dynamic proxies which need a lot less integration due to their limitation to proxying interfaces.</span></p>

<p><span class="chinese">我们拥有交叉编译器，但却没有办法通过调用.NET环境中的库来自动替换掉对JDK的依赖。</span><span class="english">We had the cross-compiler but missed a way to automatically replace the JDK dependencies with calls to libraries in the .Net environment.</span></p>

<p><span class="chinese">该努力必然会创建一个简单、低层次的模块系统，其设计将聚焦于模块化JDK这个目标。</span><span class="english">This effort will, of necessity, create a simple, low-level module system whose design will be focused narrowly upon the goal of modularizing the JDK.</span></p>

<p><span class="chinese">这种二进制代码级别的改变固然是重要的一步，但也不能直接成为可执行程序，因为它还是包含一些对JDK的依赖。</span><span class="english">This byte code level change, although a big step, does not in itself bring us to true bootstrapping because we are still left with the JDK dependencies.</span></p>

<p><span class="chinese">指定了一个JRE目录，实际上只是指向了JDK的一部分。应该指向JDK安装的根目录，而非它的子目录JRE！</span><span class="english">If the selected JRE is actually part of a full JDK, please update its configuration to point to the JDK installation root directory, not to its included jre subdirectory.</span></p>

<p><span class="chinese">JDK中还是没有干这事的，你依旧需要创建另外一个辅助方法，有可能在你的实现中会使用位操作和位移动。</span><span class="english">There is nothing in the JDK to assist with this either, so you’ll need to create another helper method and probably use bitwise operations and bitshifting in your implementation.</span></p>

<p><span class="chinese">所以我们的任务就变成了创建一个前端处理器，能够修改Scala的源代码，将JDK直接替换为IKVM类库中的.NET相同功能，一种映射机制。</span><span class="english">The task therefore became creating a pre-processor that would modify the Scala source code directly replacing JDK dependencies with IKVM .Net equivalents, a major mapping exercise.</span></p>

