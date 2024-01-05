# 死信

<p><span class="chinese">不应创建日记或死信队列。</span><span class="english">You do not create a journal or dead-letter queue.</span></p>

<p><span class="chinese">该消息会放入发送队列管理器的死信队列中。</span><span class="english">The message is placed in the sending queue manager's Dead Letter Queue.</span></p>

<p><span class="chinese">但是，新建队列没有配置为使用死信队列。</span><span class="english">However, newly created queue managers are not configured to use a dead letter queue.</span></p>

<p><span class="chinese">如果消息传递失败，则不会在死信队列中保留该消息的任何记录。</span><span class="english">If a message fails delivery, no record of it is maintained in the dead-letter queue.</span></p>

<p><span class="chinese">我们认为最佳实践是每个队列管理器拥有一个死信队列。</span><span class="english">It is considered a best practice for each queue manager to have a dead letter queue.</span></p>

<p><span class="chinese">大象的灵魂崩溃了，并至死信自己无法改变、超越和重生。</span><span class="english">The elephant's soul falls apart and it believes no chance to renew, reborn and recover.</span></p>

<p><span class="chinese">过去，监视一个可疑死信投递点全靠人力艰苦作业。</span><span class="english">Time was when monitoring a suspected dead-letter box involved laborious work by humans.</span></p>

<p><span class="chinese">例如，在ActiveMQ还没有一强大的死信处理能力的时候我们正在使用它。</span><span class="english">For instance, we were using ActiveMQ when it did not have a strong dead letter processing capability.</span></p>

<p><span class="chinese">通常在阅读应答消息，或机器纪录或死信队列中的消息时使用。</span><span class="english">Typically used when reading response messages, or messages in machine journals or dead-letter queues.</span></p>

<p><span class="chinese">存储在死信队列中的消息算在队列所驻留的计算机的大小配额内。</span><span class="english">Messages stored in dead-letter queues count against the size quota for the computer where the queue resides.</span></p>

<p><span class="chinese">存储在日记和死信队列中的消息计数以队列所在计算机的配额为限。</span><span class="english">Messages stored in journal and dead-letter queues count against the quota for the computer where the queue resides.</span></p>

<p><span class="chinese">当前驻留在队列中的字节总数。对于计算机队列实例，这代表着死信队列。</span><span class="english">The total number of bytes that currently reside in the queue. for the computer queues instance this represents the dead letter queue.</span></p>

<p><span class="chinese">当前驻留在队列中的消息总数。对于计算机队列实例，这代表着死信队列。</span><span class="english">The total number of messages that currently reside in the queue. for the computer queues instance this represents the dead letter queue.</span></p>

<p><span class="chinese">在要求最可靠的环境中，将死信处理程序设置为触发器，以便自动重试死消息而无需人工介入。</span><span class="english">In more robust environments, set up a dead-letter handler as a trigger so that the dead messages are automatically re-tried without intervention.</span></p>

<p><span class="chinese">为每个队列管理器创建和分配一个死信队列，并使用它来捕获由于网络或目的地问题而未发送的消息，这是一个很好的实践。</span><span class="english">It's a good practice to create and assign one for each queue manager and use it to catch messages that are not sent due to network or destination issues.</span></p>

<p><span class="chinese">死信队列是由发送应用程序的队列管理器管理的队列，可以存储未能传递或已过期的消息。</span><span class="english">The dead-letter queue is a queue managed by the sending application's queue manager that stores messages that have failed to be delivered or have expired.</span></p>

<p><span class="chinese">说明消息目标队列的属性。通常在阅读应答消息，或机器纪录或死信队列中的消息时使用。</span><span class="english">Property indicating the destination queue of the message. Typically used when reading response messages, or messages in machine journals or dead-letter queues.</span></p>

<p><span class="chinese">MS运行过程中，队列或持久化主题中存在的死信成为系统性能的瓶颈和系统运行的不安全因素。</span><span class="english">In the running process of a JMS server, a dead message in the queue or durable topic is the bottleneck of system performance and one of the incertitude factors.</span></p>

<p><span class="chinese">该结构包含目标队列的名称和将消息放在死信队列上的原因。</span><span class="english">This structure includes the name of the destination queue and the reason why the message was put on the dead-letter queue. Table 3 lists the main fields in MQDLH</span></p>

<p><span class="chinese">因为不存在其他消息遭到拒绝的指示，所以除非您请求将消息发送到死信队列，否则发送应用程序可能丢失该消息。</span><span class="english">Because no other indication of message rejection exists, the sending application can lose the message unless you request that it be sent to the dead-letter queue.</span></p>

