# serialization

<p><span class="chinese">序列化所牵扯的问题要多一些。</span><span class="english">The serialization case is a bit more problematic.</span></p>

<p><span class="chinese">进程外调用的序列化开销。</span><span class="english">Serialization overhead for the out-of-process call.</span></p>

<p><span class="chinese">串行化会带来一些与安全有关的问题。</span><span class="english">Serialization brings with it some security concerns.</span></p>

<p><span class="chinese">所有这些与自定义序列化有什么关系呢？</span><span class="english">What does all of this have to do with custom serialization?</span></p>

<p><span class="chinese">二进制序列化的主要问题就是它的脆弱性。</span><span class="english">Much of the problem with binary serialization is its brittleness.</span></p>

<p><span class="chinese">一个业务组件可以支持不同类型的系列化。</span><span class="english">A business component can support different types of serialization.</span></p>

<p><span class="chinese">为数据模型包括一个基于序列化的XML模式。</span><span class="english">Inclusion of an XML Schema based serialization for its data model.</span></p>

<p><span class="chinese">它提供了双向工程并且允许XMI模型的串行化。</span><span class="english">It provides round-trip engineering and allows XMI model serialization.</span></p>

<p><span class="chinese">如果使用模式制导的序列化，则可以避免这类问题。</span><span class="english">Such problems can be avoided if the serialization is guided by a schema.</span></p>

<p><span class="chinese">保存这个引用是为了加快日后对同一个类的序列化。</span><span class="english">This reference is kept to speed up future serialization of the same class.</span></p>

<p><span class="chinese">这将更快地实现JSON对象的序列化和反序列化。</span><span class="english">This will allow faster serialization and de-serialization of JSON objects.</span></p>

<p><span class="chinese">本文将介绍几种测试对象串行化的方法。</span><span class="english">In this article I demonstrate the various ways to test object serialization.</span></p>

<p><span class="chinese">使用二进制代码做序列化的问题之一就是你无法去查看结果。</span><span class="english">One of the problems with binary serialization is you can't look at the result.</span></p>

<p><span class="chinese">通过序列化和反序列化去复制一个单例对象。</span><span class="english">Copies of a singleton object that has undergone serialization and deserialization.</span></p>

<p><span class="chinese">串行化格式可以说是代码基础中最脆弱、健壮性最差的部分。</span><span class="english">Serialization formats can be the most fragile and least robust parts of a code base.</span></p>

<p><span class="chinese">定制绑定定义了序列化和逆序列化运行时的行为。</span><span class="english">The custom binder defines the run time behavior for serialization and deserialization.</span></p>

<p><span class="chinese">但是“由代码开始”并不意味着必须通过直接序列化来暴露数据模型。</span><span class="english">But start-from-code doesn’t have to mean exposing a data model by direct serialization.</span></p>

<p><span class="chinese">如果不存在任何自定义属性，则序列化管理器必须返回空集合。</span><span class="english">The serialization manager must return an empty collection if no custom properties exist.</span></p>

<p><span class="chinese">在服务器上，解析或串行化不会引入替换字符。</span><span class="english">Substitution characters are not introduced during parsing or serialization on the server.</span></p>

<p><span class="chinese">动态方法可以使得不需要编写自订序列化和还原序列化程式码。</span><span class="english">Dynamic methods can eliminate the need to write custom serialization and deserialization code.</span></p>

