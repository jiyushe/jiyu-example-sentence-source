# homography

<p><span class="chinese">本文系统地研究了求解单应矩阵的三种算法。</span><span class="english">In this paper, the homography matrix algorithms are studied thoroughly.</span></p>

<p><span class="chinese">在平面测量问题中，单应矩阵扮演着十分重要的角色。</span><span class="english">As same as other problems in computer vision, the homography matrix computation is very sensitive to noise.</span></p>

<p><span class="chinese">针对摄像机绕光心旋转的情形，讨论了在这种特殊情形下单应矩阵具有的性质。</span><span class="english">What properties the homography should have when the camera rotates around its optical center was discussed.</span></p>

<p><span class="chinese">利用单应矩阵的特性及近距离的双目一致性约束进行标定。</span><span class="english">Characteristic homography matrix and consistency constraints in close range are employed in this calibration.</span></p>

<p><span class="chinese">通过这个原理就可以推导出投影矩阵在满足一定条件下可由单应矩阵得到。</span><span class="english">It is therefore concluded that a projection matrix can be computed through homography under certain condition.</span></p>

<p><span class="chinese">使图象间共面特征基元的匹配效率提高。</span><span class="english">In the image matching algorithm, a RANSAC homography method is proposed to improve the efficiency of coplanar feature matching.</span></p>

<p><span class="chinese">平面测量以及平面单应问题的研究还有很多其他的应用，如矫正图象的射影失真、实现旋转图象序列的整合等等。</span><span class="english">The research on plane measurement and homography has many other applications, such as rectifying images, registering image sequences, etc.</span></p>

<p><span class="chinese">利用由近似的摄像机投影模型导出的单应性关系，实现两个摄像机图像之间的目标匹配。</span><span class="english">The object matching on two image planes of the two cameras is achieved by homography relation educed from an approximate camera projective model.</span></p>

<p><span class="chinese">本文给出基于中值流滤波器的改进的RANSAC算法，保证了对应矩阵计算结果具有较高的精确性和稳定性。</span><span class="english">An improved RANSAC algorithm based on the modified median flow filter is presented to improve the stability and accuracy of homography calculation.</span></p>

<p><span class="chinese">低端摄像头、高效率的特征提取方法和一致性矩阵求解算法使系统扩展成本大大降低。</span><span class="english">The low-performance cameras, high efficient feature extraction method and sophisticated solution for homography make the cost of expanding the system low.</span></p>

<p><span class="chinese">给出仿射坐标系下场景中平面与像平面的单应关系、绝对二次曲线及其图像的表示。</span><span class="english">This paper first presents the homography between a plane in the scene and a plane of the image, and the absolute conic in space under an affine coordinates.</span></p>

<p><span class="chinese">最后，从仿射重构所获得的无穷远平面单应矩阵标定摄像机内参数，进而得到度量重构。</span><span class="english">Third, the camera intrinsic parameters are calibrated by means of the infinite homography obtained in the second step, and a metric reconstruction is obtained.</span></p>

<p><span class="chinese">根据两幅图像中的平面约束，证明了图像对的基础矩阵和同形矩阵的乘积具有反对称的性质。</span><span class="english">According to the planar constraints, we proved that the product of the fundamental matrix and the homography matrix of an image pair is an antisymmetric matrix.</span></p>

<p><span class="chinese">首先，一个分段的双线性模型和5个5元的颜色编码的图像被用于构造的投影仪和一台摄像机的图像平面之间的单应性。</span><span class="english">Firstly, a piecewise bilinear model and five 5-ary color coding images are used to construct the homography between the image planes of a projector and a camera.</span></p>

<p><span class="chinese">该系统支持基于单应矩阵的算法和基于柱面坐标的全自动全景拼图算法。</span><span class="english">This system can not only support the algorithm based on homography matrix, but also support automated panoramic mosaicing method based on cylindrical coordinates.</span></p>

<p><span class="chinese">该方法以导管架上表面为参考平面，依据其单应矩阵及它与海平面之间的夹角计算出海面图像的单应。</span><span class="english">The approach takes the jacket upper surface as a reference plane, computes the homography of ocean surface by the homography of reference plane and jacket launching angle.</span></p>

<p><span class="chinese">然后把检测到特征角点作为图像中的运动目标，利用KLT跟踪算法，确定各特征角点的精确位置，从而得到图像之间精确的单应性变换矩阵。</span><span class="english">Then the detected corners were regarded as moving objects in the images, located accurately by the KLT track algorithm, and accurate homography matrix between the two images was obtained.</span></p>

<p><span class="chinese">论述由位于正交平面上的特征点对集合复原无穷远单应性矩阵和摄像机内参数的新算法。</span><span class="english">A new algorithm is presented to determine infinite homography matrix and camera intrinsic matrix parameters under one camera motion set from the matched-point sets on two orthogonal planes.</span></p>

<p><span class="chinese">重点介绍了根据特征直线计算平面单应矩阵时的数据归一化方法。</span><span class="english">A normalization method on line based homography estimation is mainly introduced, and the effect of the normalization to the distance measurement in long distances is analyzed by experiments.</span></p>

<p><span class="chinese">利用平面间单应性矩阵解决了标识部分被遮挡情况下的虚实配准问题，一定程度上提高了系统的健壮性、可用性。</span><span class="english">We use Homography to solve the problem of registration when marker is partly occluded. Our method really improves the robustness and practicability of marker based Augmented Reality systems.</span></p>

