---
layout: page
title: Energy Delay Distortion Problem
description: Keywords - online algorithms, theoritical comp sci, maths
img: assets/img/tifr-1.png
importance: 5
category: work
---
An energy-limited source trying to transmit multiple packets to a destination with possibly different sizes is considered. With limited energy, the source cannot potentially transmit all bits of all packets. In addition, there is a delay cost associated with each packet. Thus, the source has to choose, how many bits to transmit for each packet, and the order in which to transmit these bits, to minimize the cost of distortion (introduced by transmitting lower number of bits) and queueing plus transmission delay, across all packets. Assuming an exponential metric for distortion loss and linear delay cost, we show that the optimal order of transmission is the increasing order of packet sizes and optimization problem is jointly convex. Hence, the problem can be exactly solved using convex solvers, however, because of the complicated expression derived from the KKT conditions, no closed form solution can be found even with the simplest cost function choice made in the paper. To facilitate a more structured solution, a discretized version of the problem is also considered, where time and energy are divided in discrete amounts. In any time slot (fixed length), bits belonging to any one packet can be transmitted, while any discrete number of energy quanta can be used in any slot corresponding to any one packet, such that the total energy constraint is satisfied. The discretized problem is a special case of a multi-partitioning problem, where each packet's utility is super-modular and the proposed greedy solution is shown to incur cost that is at most 2-times of the optimal cost.

More information  can be found here:
<ul>
  <li><a href="https://ieeexplore.ieee.org/document/8600172"> NCC 2018 paper</a></li>
</ul>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/tifr-2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Representative image for the problem formulation
</div>
