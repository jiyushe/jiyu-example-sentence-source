# allocator

<p><span class="chinese">实现一个简单的分配程序</span><span class="english">Implementing a simple allocator</span></p>

<p><span class="chinese">分配程序不能将空闲空间拼合为更大的内存块。</span><span class="english">The allocator can't coalesce free space into larger blocks.</span></p>

<p><span class="chinese">对系统页分配器的借口，不需要加缓存锁。</span><span class="english">Interface to system's page allocator. No need to hold the cache-lock.</span></p>

<p><span class="chinese">这是非常简单的代码，它不调用分配器。</span><span class="english">It is implemented as a thin layer on top of the power-of-two allocator.</span></p>

<p><span class="chinese">分配器，它的值类型与容器的值类型相同。</span><span class="english">Alloc An allocator whose value type is the same as the container's value type.</span></p>

<p><span class="chinese">对于分配器来说对这样的事情很难做出更明智的猜测。</span><span class="english">And it is difficult for the allocator to make more informed guesses about this matter.</span></p>

<p><span class="chinese">首先，奉两龙来袭通过分配器和登记命名单位。</span><span class="english">First of all, the instructions from two incoming queues pass through Allocator and Register Rename units.</span></p>

<p><span class="chinese">从软件模型上分析，动态约束优化调度的组件包括动态解析器、动态分配器和推理引擎。</span><span class="english">The components of the software model include a dynamic generator, a dynamic allocator and an inference engine.</span></p>

<p><span class="chinese">该方法释放您先前创建的内存块，并使得从分配程序例程返回的所有指针失效。</span><span class="english">It frees every memory block you created earlier and invalidates all the pointers returned from the allocator routines.</span></p>

<p><span class="chinese">尽管如此，这些年来，这个分配器已经进化到做了一些大部分用户都可以接受的取舍。</span><span class="english">However, over the years, the allocator has evolved to make trade-offs that the majority of users find to be acceptable.</span></p>

<p><span class="chinese">不过，如果不熟悉分配程序的设计，那么定制分配程序通常会带来比它们解决的问题更多的问题。</span><span class="english">However, if you aren't familiar with allocator design, custom allocators can often create more problems than they solve.</span></p>

<p><span class="chinese">消除这个问题的同时仍然维持可移植的对齐就需要分配器不征用任何额外的开销。</span><span class="english">Eliminating this problem while still maintaining portable alignment would require that the allocator not impose any overhead.</span></p>

<p><span class="chinese">每个分配器都是模块特定的，并可确保函数体位于模块基址的正偏移位置。</span><span class="english">Each allocator is module-specific and ensures that the function body will be at a positive offset from the base of the module.</span></p>

<p><span class="chinese">如果局部化是唯一的目标，分配器可能总是尽可能接近的分配每个连续的块。</span><span class="english">If locality were the only goal, an allocator might always allocate each successive chunk as close to the previous one as possible.</span></p>

<p><span class="chinese">为了通融最差情况下的对齐需求，就得为了对齐块而强迫分配器跳过几个字节，从而增加了浪费。</span><span class="english">Accommodating worst-case alignment requirements increases wastage by forcing the allocator to skip over bytes in order to align chunks.</span></p>

<p><span class="chinese">本文展现了这个分配器的一些主要设计目标，算法以及实现考虑。</span><span class="english">This article presents a description of some of the main design goals, algorithms, and implementation considerations for this allocator.</span></p>

<p><span class="chinese">第8章的存储分配程序将说明如何使用联合来强制一个变量在特定类型的存储边界上对齐。</span><span class="english">The storage allocator in Chapter 8 shows how a union can be used to force a variable to be aligned on a particular kind of storage boundary.</span></p>

<p><span class="chinese">在一些程序中仍然时分需要有一种高速缓冲，但是它并没有在该分配器中被实现--对很小的块进行后备。</span><span class="english">There remains one kind of caching that is highly desirable in some applications but not implemented in this allocator -- lookasides for very small chunks.</span></p>

<p><span class="chinese">介绍了降压配注器和降黏配注器的结构以及初步地面试验结果。</span><span class="english">Structure of depressurization injection allocator and viscosity- breaking injection allocation, as well as their primary surface test results, are introduced.</span></p>

<p><span class="chinese">对目前国内、外所使用的各种热计量仪表进行了分析与比较，指出在我国集中供热的现有条件下，电子式热分配表是一种比较适用的热计量仪表。</span><span class="english">Meters domestic and abroad are analyzed and compared. The electric heat allocator is adequate heat metering instrument to the centralized heat-supply in our country.</span></p>

