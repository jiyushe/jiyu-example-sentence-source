# microkernel

<p><span class="chinese">Mach所使用的微内核的方法，并没有获得很大的成功。</span><span class="english">The microkernel approach, taken by Mach, was not a great success.</span></p>

<p><span class="chinese">使用面向资源微核有几个主要的优点。</span><span class="english">The use of a resource-oriented microkernel has several key benefits.</span></p>

<p><span class="chinese">金匮回生液、金匮激活丹不诱发昆明属小鼠微核形成。</span><span class="english">"Jinguihuishengyi" and "Jinguijihuodang" do not lead to construction of mouse's microkernel.</span></p>

<p><span class="chinese">尽管一个微内核离完整的操作系统还很远，但这样的设计达到了我们的主要目标。</span><span class="english">While a microkernel is by no means a complete operating system, this design achieves a major goal.</span></p>

<p><span class="chinese">微内核在执行任何调用之前，首先会检查该调用是否被许可。</span><span class="english">However, before executing any call, the microkernel first checks to make sure the call is permitted.</span></p>

<p><span class="chinese">除了提供伸缩性更好的环境之外，微核还能提供稳定性优势。</span><span class="english">In addition to providing a more scalable environment, the microkernel can offer reliability advantages.</span></p>

<p><span class="chinese">实际上，Windsor仅仅是封装了MicroKernel并提供了一些外部的配置信息和代理支持。</span><span class="english">In fact, Windsor just aggregates the MicroKernel and provides external configuration and proxy support.</span></p>

<p><span class="chinese">如果客户端请求了端点并未提供的表示类型，那么微核就可以起到媒介的作用。</span><span class="english">If a client requests a representation type that an endpoint does not provide then the microkernel can intermediate.</span></p>

<p><span class="chinese">context对象是microkernel的一个接口，在逻辑请求与具体代码之间架起了一座桥梁。</span><span class="english">The context object is an interface to the microkernel which allows an endpoint to bridge between logical requests and physical code.</span></p>

<p><span class="chinese">帖子引起的反应，托沃兹，造成一个众所周知的争论和单片微内核设计。</span><span class="english">Theposting elicited the response of Torvalds, which resulted in a wellknown debate over the microkernel and monolithic kernel designs.</span></p>

<p><span class="chinese">微内核由于其结构清晰，易扩充和移植等特点，成为一种备受关注的技术。</span><span class="english">Microkernel becomes an attention-attracting technology because of its clear structure , and its advantage for expansion and transplantation.</span></p>

<p><span class="chinese">相比之下，微核操作系统提供动态抛出功能的方法，从而提供伸缩性更好的环境。</span><span class="english">In contrast, microkernel operating systems provide the means to discard functionality dynamically, allowing a much more scalable environment.</span></p>

<p><span class="chinese">之前我们了解的上下文对象context就是一个统一的POSIX的例子，就像是被称作NetKernel基础API的微核的抽象。</span><span class="english">The context object we saw earlier is an example of a uniform POSIX like abstraction around the microkernel called the NetKernel Foundation API.</span></p>

<p><span class="chinese">微内核在设计之初并没有关注性能问题，这导致了第一代微内核在性能上广遭诟病。</span><span class="english">Performance is scarcely attended to when the microkernel is in its embryonic stage, which led to the notoriety of the first generation microkernel.</span></p>

<p><span class="chinese">NetKernel的逻辑模型集中于信息处理，而且通过一个微内核将逻辑模型与物理层对象和API干净地分离。</span><span class="english">NetKernel's logical model is focused on information processing and is cleanly separated from the physical level of objects and APIs by a microkernel.</span></p>

<p><span class="chinese">这种设计的好处就是，内核的体积大大减小，用户态的服务线程提高了系统的灵活性和安全性。</span><span class="english">The benefit of microkernel and user-level system service is the greatly reduced kernel size, together with the flexibility and security of the whole system.</span></p>

<p><span class="chinese">将操作系统的结构重新组织为一个运行于内核态的微内核，外加若干用户进程去完成真正的操作系统任务。</span><span class="english">reorganize the operating system as a tiny microkernel that runs in kernel mode, along with some number of user processes that do the real work of the operating system.</span></p>

<p><span class="chinese">高度模块化的设计使微内核对进程间通信的依赖度极高，因而进程间通信的性能直接影响到微内核的性能。</span><span class="english">High-level modularization renders the microkernel exceedingly dependent on the inter-process communication, which therefore can directly affect the performance of the microkernel.</span></p>

<p><span class="chinese">提出了采用微内核结构的卫星操作系统设计方案，并且就该设计方案的实现细节进行了介绍和讨论。</span><span class="english">A scheme of real- time satellite operating system design based on microkernel architecture is presented and the implementation of this scheme is introduced and discussed in detail.</span></p>

<p><span class="chinese">NetKernel的中心是一个REST风格或面向资源的微核，专门负责为物理代码解析逻辑URI请求并在空闲的CPU上安排执行请求。</span><span class="english">At the heart of NetKernel is a RESTful or resource-oriented microkernel responsible for resolving logical URI requests to physical code endpoints and scheduling the request on an available CPU core.</span></p>

