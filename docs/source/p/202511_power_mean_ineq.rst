幂平均不等式
============

定义
------

一组正数 :math:`a_1,a_2,\cdots,a_n` 的 :math:`x` 次幂平均定义为

.. math::

    M_x(a_1,a_2,\cdots,a_n) = \left(\frac{1}{n}\sum_{i=1}{n}{a_i^x}\right)^{\frac{1}{x}}.

其中当 :math:`x=0` 时, 补充定义

.. math::

    M_0(a_1,a_2,\cdots,a_n) = \sqrt[n]{a_1a_2\cdots a_n}.

可以证明这个补定义使其在实数域上连续.  使用 Jensen 不等式,
或者求导后再利用 Jensen 不等式, 结合调整系数可知其单调递增.

可视化
------

下面是幂平均不等式的图像示例,
这里仅考虑二元情况.  ( 这是 2025 年 11 月 02 日的快照, 可以在
`这里 <https://www.desmos.com/calculator/ws2hyfu6d6?embed>`_ 查看,
或者查看 `当前版本 <https://www.desmos.com/calculator/ulqgaha9uq>`_ . )

.. raw:: html

    <iframe src="https://www.desmos.com/calculator/ws2hyfu6d6?embed"
        width="600" height="600"
        style="border: 1px solid #ccc" frameborder=0>
    </iframe>
