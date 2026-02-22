---
hide:
  - navigation
---

# CS479: Machine Learning for 3D Data

<h3><b>
<a href="http://mhsung.github.io/" target="_blank">Minhyuk Sung</a>, <a href="https://www.kaist.ac.kr/" target="_blank">KAIST</a>, Spring 2026
</b></h3>
<br />

![Teaser](assets/teaser.png){ width=97.5% }[^1]

[^1]: Teaser image credits (from left to right):<br>Mildenhall et al., NeRF: Representing Scenes as Neural Radiance Fields for View Synthesis, ECCV 2020.<br>https://huggingface.co/blog/gaussian-splatting<br>Hwang and Sung, Occupancy-Based Dual Contouring, SIGGRAPH Asia 2024.<br>



## Time & Location
**Time**: Mon/Wed 1:00 p.m. - 2:15 p.m. (KST)   
**Location**: E3-5 Room 210


## Description
3D Data are widely used in many applications in computer vision, computer graphics, and robotic, such as autonomous driving, AI-assisted 3D object/scene design, augmented reality, and physical robot interaction. Along with the recent increasing demands on processing and analyzing such 3D data, there has been tremendous progress in developing novel technologies, especially based on deep learning. In this course, we will cover the recent advances in machine learning techniques for 3D data and also discuss the remaining challenges. 

## Prerequisites
### Required
- [CS371] Introduction to Deep Learning
### Recommended
- [CS380] Introduction to Computer Graphics
- [CS484] Introduction to Computer Vision


## Course Staff
**Instructor**: [Minhyuk Sung](https://mhsung.github.io/){:target="_blank"} ([mhsung@kaist.ac.kr](mailto:mhsung@kaist.ac.kr))

**Course Assistants:**

- Mingue Park ([kicikicik@kaist.ac.kr](mailto:kicikicik@kaist.ac.kr))
- Kyeongmin Yeo ([aaaaa@kaist.ac.kr](mailto:aaaaa@kaist.ac.kr))
- Daehyeon Choi ([daehyeonchoi@kaist.ac.kr](mailto:daehyeonchoi@kaist.ac.kr))
- Jisung Hwang ([4011hjs@kaist.ac.kr](mailto:4011hjs@kaist.ac.kr))


## Past Years
- [CS479: Machine Learning for 3D Data (Spring 2025)](https://mhsung.github.io/kaist-cs479-spring-2025/){:target="_blank"}
- [CS479: Machine Learning for 3D Data (Fall 2023)](https://mhsung.github.io/kaist-cs479-fall-2023/){:target="_blank"}
- [CS492(A): Machine Learning for 3D Data (Spring 2022)](https://mhsung.github.io/kaist-cs492a-spring-2022/){:target="_blank"}
- [CS492(H): Machine Learning for 3D Data (Spring 2021)](https://mhsung.github.io/courses/kaist-cs492h-spring-2021/){:target="_blank"}


## Grading
- [Programming Assignments](./programming-assignments): 20%
- [3D Segmentation Competition](./): 20%
- [3D Rendering Contest](./3d-rendering-contest): 20%
- Exams: 30%
- In-Class Participation: 10%


## AI Coding Assistant Tool Policy
**You are allowed (and even encouraged) to utilize AI coding assistant tools**, such as ChatGPT, Copilot, Codex, and Code Intelligence, for your programming assignments and projects. Utilizing AI coding assistant tools will not be deemed as plagiarism. However, it is still strictly prohibited to directly copy code from the Internet or from someone else. Doing so will lead to a score of zero and a report to the university.


## Important Dates
ALL ASSIGNMENTS ARE DUE 23:59 KST.
(Subject to Change)

- Assignment 1 Submission Due: ~~April 1 (Tuesday), 23:59 KST~~ ~~April 8 (Tuesday), 23:59 KST~~ ==April 9 (Wednesday), 23:59 KST==   
- 3D Rendering Contest Sign-Up Due: ~~April 6 (Sunday), 23:59 KST~~ ==April 8 (Tuesday), 23:59 KST== 
- Assignment 2 Submission Due: ==April 27 (Sunday), 23:59 KST==
- Assignment 3 Submission Due: ==May 20 (Tuesday), 23:59 KST==
- Assignment 4 Submission Due: ==June 10 (Tuesday), 23:59 KST==
- 3D Rendering Contest Submission Due: ==May 31 (Saturday), 23:59 KST==  


## Schedule
(Subject to Change) 

| Week | Mon | Topic | Wed | Topic |
| :----: | :----: | :----: | :----: | :----: |
| 1  | Feb 24 | **Course Introduction**<br>[**Slides**]({{links.lec01}}){:target="_blank"} | Feb 26 | **3D Representations**<br>[**Slides**]({{links.lec02}}){:target="_blank"}<br>[**Recording**]({{links.rec02}}){:target="_blank"} | 
| 2  | Mar 3  | No Class (Substitute Holiday for<br>the Independence Movement Day) | Mar 5 | **Point Clouds 1**<br>[**Slides**]({{links.lec03}}){:target="_blank"}<br>[**Recording**]({{links.rec03}}){:target="_blank"} | 
| 3  | Mar 10 | **Point Clouds 2**<br>[**Slides**]({{links.lec04}}){:target="_blank"}<br>[**Recording**]({{links.rec04}}){:target="_blank"} | Mar 12 | ==Assignment 1 Session:==<br>[**PointNet**]({{links.asgmt1}}){:target="_blank"}<br>[**Slides**]({{links.asgmt1_slides}}){:target="_blank"} | 
| 4  | Mar 17 | **Implicit Neural Representations**<br>[**Slides**]({{links.lec05}}){:target="_blank"}<br>[**Recording**]({{links.rec05}}){:target="_blank"} | Mar 19 | **Image-to-3D 1:<br>Camera Model**<br>[**Slides**]({{links.lec06}}){:target="_blank"}<br>[**Recording**]({{links.rec06}}){:target="_blank"} | 
| 5  | Mar 24 | **Image-to-3D 2<br>Epipolar Geometry**<br>[**Slides**]({{links.lec07}}){:target="_blank"}<br>[**Recording**]({{links.rec07}}){:target="_blank"} | Mar 26 | **Neural Radiance Fields (NeRF)**<br>[**Slides**]({{links.lec08}}){:target="_blank"}<br>[**Recording**]({{links.rec08}}){:target="_blank"} | 
| 6  | Mar 31 | **Hybrid Representations**<br>[**Slides**]({{links.lec09}}){:target="_blank"}<br>[**Recording**]({{links.rec09}}){:target="_blank"} | Apr 2 | ==Assignment 2 Session==:<br>[**NeRF**]({{links.asgmt2}}){:target="_blank"}<br>[**Slides**]({{links.asgmt2_slides}}){:target="_blank"} | 
| 7  | Apr 7  | **Gaussian Splatting**<br>[**Slides**]({{links.lec10}}){:target="_blank"}<br>[**Recording**]({{links.rec10}}){:target="_blank"} | Apr 9 | ==Midterm Summary== | 
| 8  | Apr 14 | ==Midterm== | Apr 16 | No Class (Midterm Week) | 
| 9  | Apr 21 | ==Guest Lecture 1:==<br>[**Jiahui Huang**](./guest-lecture-jiahui-huang){:target="_blank"}<br>[**Recording**]({{links.guest_rec01}}){:target="_blank"} | Apr 23 | ==Demo Session:==<br>[**NeRFStudio**]({{links.demo}}){:target="_blank"}<br>[**Slides**]({{links.demo_slides}}){:target="_blank"} | 
| 10  | Apr 28 | ==Assignment 3 Session==:<br>[**Gaussian Splatting**]({{links.asgmt3}}){:target="_blank"}<br>[**Slides**]({{links.asgmt3_slides}}){:target="_blank"}<br>[**Slides**]({{links.asgmt3_slides}}){:target="_blank"} | Apr 30 | ==Guest Lecture 2:==<br>[**Songyou Peng**](./guest-lecture-songyou-peng){:target="_blank"}<br>[**Recording**]({{links.guest_rec02}}){:target="_blank"} | 
| 11 | May 5 | No Class (Children’s Day) | May 7 | **Representation Conversion 1**<br>[**Slides**]({{links.lec11}}){:target="_blank"}<br>[**Recording**]({{links.rec11}}){:target="_blank"} | 
| 12 | May 12 | **Representation Conversion 2**<br>[**Slides**]({{links.lec12}}){:target="_blank"}<br>[**Recording**]({{links.rec12}}){:target="_blank"} | May 14 |  No Class (Break) | 
| 13 | May 20 | ==Guest Lecture 3<br>(Mar 20 (Tue) 4:00 p.m.):==<br>[**Matthias Nießner**](./guest-lecture-matthias-niessner){:target="_blank"}<br>[**Recording**]({{links.guest_rec03}}){:target="_blank"} | May 21 |  ==Assignment 4 Session:==<br>[**Marching Squares**]({{links.asgmt4}}){:target="_blank"}<br>[**Slides**]({{links.asgmt4_slides}}){:target="_blank"} | 
| 14 | May 26 | **Mesh Deformation**<br>[**Slides**]({{links.lec13}}){:target="_blank"}<br>[**Recording**]({{links.rec13}}){:target="_blank"} | May 28 |  **3D Geneneration**<br>[**Slides**]({{links.lec14}}){:target="_blank"}<br>[**Recording**]({{links.rec14}}){:target="_blank"} | 
| 15 | Jun 2 | ==Project Presentations 1== | Jun 4 |==Project Presentations 2== |
| 16 | Jun 9 | No Class (Final Week) | Jun 11 | No Class (Final Week) |

