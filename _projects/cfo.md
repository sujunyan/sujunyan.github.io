---
layout: page
title: "Follow the Sun and Go with the Wind: Carbon Footprint Optimized Timely E-Truck Transportation"
img: /assets/img/12.jpg
importance: 1
category: work
---
Joint work with [Qiulin Lin](https://lin-qiulin.github.io/), [Minghua Chen](https://www.mhchen.com/), and [Haibo Zeng](https://www.faculty.ece.vt.edu/zeng/index.html)

This project is a follow-up project of [Energy-Efficient Timely Transportation of Long-Haul Heavy-Duty Truck](https://www.mhchen.com/projects/trucking.html).

---
### **Highlights**
- <span style="color:red">Best paper award</span> at ACM e-Energy 2023 
- We study an **important yet challenging problem** , namely the carbon footprint optimization problem for e-trucks.
- We provide a **novel problem formulation** , which incurs low model complexity and reveals a useful problem structure.
- We develop an **efficient algorithm** with performance guarantee.
- **Key idea** : The problem is easy either when there is no charging or when there is only charging. Our idea is to separate the combined challenging problem into those two easy subproblems and combine their solutions.
- Carbon-optimized solutions save up to **28%** carbon footprint compared to baseline alternatives.

---

### **Slides**

<iframe  src="{{ '/assets/pdf/cfo.slides.pdf' | relative_url }}" width="100%" height="500">
</iframe>

<iframe src="https://onedrive.live.com/embed?resid=246D3C20B0FC822F%21350&amp;authkey=!AFe9PhuYTjFYlyE&amp;em=2&amp;wdAr=1.7777777777777777&amp;wdEaaCheck=0" width="100%" height="500px" frameborder="0">这是嵌入 <a target="_blank" href="https://office.com">Microsoft Office</a> 演示文稿，由 <a target="_blank" href="https://office.com/webapps">Office</a> 提供支持。</iframe>

---

### **Description**

We study the carbon footprint optimization (CFO) of a heavy-duty e-truck traveling from an origin to a destination across a national highway network subject to a hard deadline, by optimizing path planning, speed planning, and intermediary charging planning. Such a CFO problem is essential for carbon-friendly e-truck operations. However, it is notoriously challenging to solve due to (i) the hard deadline constraint, (ii) positive battery state-of-charge constraints, (iii) non-convex carbon footprint objective, and (iv) enormous geographical and temporal charging options with diverse carbon intensity. Indeed, we show that the CFO problem is NP-hard. 

As a key contribution, we show that under practical settings it is equivalent to finding a generalized restricted shortest path on a stage-expanded graph, which extends the original transportation graph to model charging options. Compared to alternative approaches, our formulation incurs low model complexity and reveals a problem structure useful for algorithm design. We exploit the insights to develop an efficient dual-subgradient algorithm that always converges. 
As another major contribution, we prove that (i) each iteration only incurs polynomial-time complexity, albeit it requires solving an integer charging planning problem optimally, and (ii) the algorithm generates optimal results if a condition is met and solutions with bounded optimality loss otherwise. 

Extensive simulations based on real-world traces show that our scheme reduces up to 28% carbon footprint compared to baseline alternatives. The results also demonstrate that e-truck reduces 56% carbon footprint than internal combustion engine trucks.


---
### **Publications**
###### **Notes**
E-Energy'23 [1] is one of the first work that gives the problem formulation for the CFO problem and gives an efficient algorithm for solving CFO. CDC'23 [2] supplements e-Energy'23 [1] by studying the theoretic hardness of CFO and provide a bi-criteria approximation algorithm with stronger theoretic performance guarantee (but much higher run-time complexity). Poster and demo papers [3,4] give some preliminary results in the early stage of this project.

##### **Conference Papers**
[1] **J. Su** , Q. Lin, and M. Chen, “Follow the Sun and Go with the Wind: Carbon Footprint Optimized Timely E-Truck Transportation”, in Proceedings of 14th International Conference on Future Energy Systems (ACM e-Energy 2023), Orlando, Florida, June 20 - 23, 2023. **(Best Paper Award).** [[pdf](https://www.mhchen.com/papers/CFO_eEnergy.23.pdf)] [[arxiv](https://arxiv.org/abs/2305.11912)]

[2] **J. Su**, Q. Lin, M. Chen, and H. Zeng, “Minimizing Carbon Footprint for Timely E-Truck Transportation: Hardness and Approximation Algorithm”, (invited), in Proceedings of the 62th IEEE Conference on Decision and Control (CDC), Singapore, December 13-15, 2023. [[arxiv](https://arxiv.org/abs/2308.09866)]

##### **Poster and Demo Papers**

[3] **J. Su**, M. Chen, and H. Zeng, “Energy Efficient Timely Transportation : A Comparative Study of Internal Combustion Trucks and Electric Trucks”, in Proceedings of the 8th ACM International Conference on Systems for Energy-Efficient Built Environments, Cities, and Transportation (ACM BuildSys 2021), Coimbra, Portugal, November 17-18, 2021. (poster paper) [<a href="{{ '/assets/pdf/buildsys21.etruck.pdf' | relative_url }}">pdf</a>]

[4] **J. Su**, M. Chen, and H. Zeng, “E2Pilot: An Energy-Efficient Navigation System for Long-haul Timely Truck Transportation”, in Proceedings of 13th International Conference on Future Energy Systems (ACM e-Energy 2022), virtual conference, June 28 - July 1, 2022. (demo paper) [<a href="{{ '/assets/pdf/eenergy22.e2pilot.demo.pdf' | relative_url }}">pdf</a>]

##### **Patent**

[5] M. Chen., **J. Su**, and Q. Lin, "Carbon Footprint Optimized Timely E-Truck Transportation", 8 Feb 2024, (Filed) U.S. Patent Application No. 18/436,350.
