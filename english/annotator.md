# annotator

<p><span class="chinese">标注器是基本的文本分析组件。</span><span class="english">An Annotator is the basic text analysis component.</span></p>

<p><span class="chinese">用在表注释器内以选择一整列。</span><span class="english">Use inside the table annotator to select an entire column.</span></p>

<p><span class="chinese">您将在下一个步骤的注释器类中使用这些类。</span><span class="english">You use these classes in the annotator code in the next step.</span></p>

<p><span class="chinese">比如说，您可以为每个包实现一个注释者。</span><span class="english">You could, for example, implement one annotator aspect per package.</span></p>

<p><span class="chinese">如果这能够解决该问题，那么注释器将返回一个比较长的返回值。</span><span class="english">If this solves the problem, your annotator may return unexpectedly long return values.</span></p>

<p><span class="chinese">对于更复杂的文本分析任务，可能需要开发定制的注释器。</span><span class="english">For more complex text analysis tasks, the development of a custom annotator may be of interest.</span></p>

<p><span class="chinese">通过扩展正则表达式注释器的规则，可以执行许多文本分析任务。</span><span class="english">Many text analysis tasks can be addressed by extending the rules of the regular expression annotator.</span></p>

<p><span class="chinese">现在，安装的正则表达式注释器已经配置了所需的规则集。</span><span class="english">The installed version of the regular expression annotator now has the desired set of rules configured.</span></p>

<p><span class="chinese">定制开发的注释器可以替换正则表达式注释器，或者与它部署在一起。</span><span class="english">A custom-developed annotator would replace or be deployed together with the provided regular-expression annotator.</span></p>

<p><span class="chinese">将注释器和映射文件链接到集合之后，就可以对文档进行爬行、解析和编制索引。</span><span class="english">With both the annotator and the mapping file linked to the collection, documents can be crawled, parsed, and indexed.</span></p>

<p><span class="chinese">现在，集合已经可以用定制的注释器处理文档，并将结果存储在它的搜索索引中。</span><span class="english">Now the collection is ready to process documents with the customized annotator and store the results in its search index.</span></p>

<p><span class="chinese">请使用注释者方面方法，参与只发生在对注释类型的共同理解这一级别。</span><span class="english">With the annotator aspect approach, the participation occurs only at the level of a shared understanding of annotation type.</span></p>

<p><span class="chinese">这个文件包含一组规则，这些规则定义注释器应该处理的字符和数字序列的类型以及处理的方式。</span><span class="english">This file contains a set of rules that define on what type of character or number sequences the annotator should act and how it should act.</span></p>

<p><span class="chinese">由正则表达式注释器执行的额外文本分析会影响性能，会降低解析器的最大吞吐量。</span><span class="english">The additional text analysis performed by the regular expression annotator does have a performance impact and will reduce the maximum parser throughput.</span></p>

<p><span class="chinese">例如，如果您在一个行中运行多个注释器，那么其中一个注释器能够访问之前运行的注释器创建的注释。</span><span class="english">For example, if you are running multiple annotators in a row, one annotator can access the annotations that were created by previously running annotators.</span></p>

