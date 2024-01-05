# frustum

<p><span class="chinese">摄像机视景外剔除对象花费的时间。</span><span class="english">Time spent culling objects outside the camera frustum.</span></p>

<p><span class="chinese">剩下的缀片通过视见体进行剔除。</span><span class="english">All remaining patches are culled against the viewing frustum.</span></p>

<p><span class="chinese">Unity会自动剔除视见平截头体之外的对象。</span><span class="english">Unity will automatically cull objects outside the viewing frustum.</span></p>

<p><span class="chinese">所有顶点都被视图截锥的前平面所剪辑。</span><span class="english">All vertices are clipped by the front plane of the viewing frustum.</span></p>

<p><span class="chinese">一个好的结构可以加快视锥剔除和遮挡筛选。</span><span class="english">A good organizational hierarchy can speed frustum and occlusion culling.</span></p>

<p><span class="chinese">在此基础上进行摄影机裁剪和物体的碰撞检测及响应。</span><span class="english">And then carries on frustum culling and collision detection and response based on it.</span></p>

<p><span class="chinese">这个函数返回由给定的视窗和投影矩阵定义的视景的六个面。</span><span class="english">This function returns six planes of a frustum defined by given view & projection matrix.</span></p>

<p><span class="chinese">观察角度和切割面共同定义了视域。</span><span class="english">Together, the viewing angle and the clipping planes define what is called the view frustum.</span></p>

<p><span class="chinese">我们用视见体的六个面去剪裁缀片的包围盒。</span><span class="english">To do this we clip the patches' bounding boxes against all six sides of the viewing frustum.</span></p>

<p><span class="chinese">注意，我们正在使用过滤纹理，过滤平截头体，并关闭了过滤。</span><span class="english">Note that we are using the filter texture, the filter frustum , and the we have turned off filtering.</span></p>

<p><span class="chinese">因此与投影机平截头体相交的几何体都会受到影响。</span><span class="english">By default, Ignore Layers is none so all geometry that intersects the Projector frustum will be affected.</span></p>

<p><span class="chinese">了利用好这些坐标，我们首先需根据视图锥截体的可视区重新定义它们。</span><span class="english">To make use of these coordinates, we must first re-define them in terms of the visible area of the viewing frustum.</span></p>

<p><span class="chinese">为了过滤掉反向投影，我们需要一个新的平截头体，让它指向我们想要过滤的方向。</span><span class="english">To filter the back projection, we need a new frustum for the filter which points in the direction we wish to filter.</span></p>

<p><span class="chinese">本文论述了锥台形空心件挤压成形工艺和模具设计要点，给出了实用的模具结构。</span><span class="english">A dissertation is made on the process and main points of the die design for extruding the hollow parts of the frustum type.</span></p>

<p><span class="chinese">当圆柱与圆台正交时，其相贯线可用一般方法作出，但其正面投影和水平投影上相贯线的最右点不能准确定位。</span><span class="english">The line of intersection can be made with a general method when the cylinder and frustum of a cone are normal to each other.</span></p>

<p><span class="chinese">利用场景图在视景体内的快速裁剪技术，有效提高图元的归属判断速度。</span><span class="english">The procedure of primitives belongingness determining is speeded up using the fast view frustum culling technology of scene graph.</span></p>

<p><span class="chinese">等边双圆锥台壳体在内压的作用下，赤道环焊缝处易产生失稳起皱，且胀形后所得容器圆度较差。</span><span class="english">Under internal pressure, equilateral frustum shell tends to wrinkle at the equator, and the circular degree of the obtained vessel is poor.</span></p>

<p><span class="chinese">这个改进的外型的优点是绕第一角点的膨胀会把截锥上的初始压力系数减少到很低的值。</span><span class="english">Benefit of this modified shape is that the expansion around the first corner reduces the initial pressure coefficient on the frustum to low values.</span></p>

<p><span class="chinese">因为我们已经定好屏幕相关值，我们现在所要做的就是依据正切来将其放大几倍以找出这个点在锥截体中的比值。</span><span class="english">Since we have already normalized our screen values, all we need to do is multiply them by the tangent to find a ratio for this point in the frustum.</span></p>

<p><span class="chinese">在古巴比伦数学中，正四棱台体积公式的表现形式和现代形式相比十分复杂。</span><span class="english">In ancient Babylonian mathematics, the expression of volume formula for the frustum of a square pyramid is much more complicated than its modern form.</span></p>

