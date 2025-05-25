<img src="./images/logo.jpg" width="256" />

<div id="sidebar">
  <a href="./README.en.md" target="_blank">
    <font color=#0000FF size=5px>[ENGLISH]</font>
  </a>
</div>

### Introduction

**XTDrone** is a general-purpose UAV simulation platform based on **PX4**, **ROS**, and **Gazebo**. It supports multirotor aircraft (including quadcopters and hexacopters), fixed-wing aircraft, hybrid VTOL aircraft (including quadplanes, tailsitters, and tiltrotors), as well as other unmanned systems such as unmanned ground vehicles (UGVs), unmanned surface vehicles (USVs), and robotic arms. Algorithms validated on XTDrone can be easily deployed onto real drones.

<img src="./images/vehicles.png" width="640" />

The single-UAV simulation architecture is shown below. For more details, see the paper:

**K. Xiao, S. Tan, G. Wang, X. An, X. Wang and X. Wang**, "XTDrone: A Customizable Multi-rotor UAVs Simulation Platform," *2020 4th International Conference on Robotics and Automation Sciences (ICRAS)*, 2020, pp. 55–61.  
DOI: [10.1109/ICRAS49812.2020.9134922](https://doi.org/10.1109/ICRAS49812.2020.9134922)  
Preprint: **[arXiv:2003.09700](https://arxiv.org/abs/2003.09700)**

<img src="./images/architecture_1_cn.png" width="640" height="480" />

The multi-UAV simulation architecture is shown below. For more details, see the paper:

**K. Xiao, L. Ma, S. Tan, Y. Cong, X. Wang**, "Implementation of UAV Coordination Based on a Hierarchical Multi-UAV Simulation Platform," *Advances in Guidance, Navigation and Control. Lecture Notes in Electrical Engineering*, vol 644. Springer, Singapore, 2022.  
DOI: [10.1007/978-981-15-8155-7_423](https://doi.org/10.1007/978-981-15-8155-7_423)  
Preprint: **[arXiv:2005.01125](https://arxiv.org/abs/2005.01125)** (2020)

<img src="./images/architecture_2_cn.png" width="640" />

> If you use XTDrone for simulation verification in academic papers, please cite one of the above publications.

This platform allows developers to quickly validate algorithms such as:

- **Stereo SLAM**  
  <img src="./images/vslam.gif" width="640" height="360" />

- **Visual-Inertial Odometry**  
  <img src="./images/vio.gif" width="640" height="360" />

- **Visual Dense Reconstruction**  
  <img src="./images/dense_reconstruction.gif" width="640" height="360" />

- **2D LiDAR SLAM**  
  <img src="./images/laser_slam_2d.gif" width="640" height="360" />

- **3D LiDAR SLAM**  
  <img src="./images/laser_slam_3d.gif" width="640" height="360" />

- **2D Motion Planning**  
  <img src="./images/2d_motion_planning.gif" width="640" height="360" />  
  <img src="./images/2d_motion_planning_new.gif" width="640" height="360" />

- **3D Motion Planning**  
  <img src="./images/3d_motion_planning.gif" width="640" height="360" />

- **Swarm Motion Planning**  
  <img src="./images/swarm_motion_planning.gif" width="640" height="306" />

- **Object Detection and Tracking**  
  <img src="./images/human_tracking.gif" width="640" height="360" />

- **Multi-UAV Formation**  
  <img src="./images/formation_1.gif" width="640" height="360" />  
  <img src="./images/formation_2.gif" width="640" height="360" />

- **Multi-UAV Precision Landing**  
  <img src="./images/multi_precision_landing.gif" width="640" height="360" />

- **Fixed-Wing Aircraft**  
  <img src="./images/planes.gif" width="640" height="360" />

- **VTOL Aircraft**  
  <img src="./images/vtols.gif" width="640" height="360" />

- **Unmanned Ground Vehicles (UGVs)**  
  <img src="./images/ugv.gif" width="640" height="360" />  
  <img src="./images/ugv_planning.gif" width="640" height="398" />

- **Unmanned Surface Vehicles (USVs)**  
  <img src="./images/usv.gif" width="640" height="360" />

- **Aerial Manipulators**  
  <img src="./images/robotic_arm.gif" width="640" height="360" />

### Tutorials

See the [XTDrone User Manual](https://www.yuque.com/xtdrone/manual_cn)

### Project Team

- **Founders**: Kun Xiao, Shaochang Tan  
- **Advisor**: Xiangke Wang  
- **Development Team**: Kun Xiao, Shaochang Tan, An Zhuo, Guanzheng Wang, Lan Ma, Yuke Li, Qipeng Wang, Xinyu Hu, Xinning Wu, Jiayi Zheng, Yufan Peng, Zijun Zheng, Jiarun Yan, Feng Yi, Ruoqiao Guan, Wenxin Hu, Yi Bao, Xudong Liu, Jie Min, Chuanlu Liu, Ciyu Ruan, Dehao Kong

### Join Us

We welcome UAV developers to join our team and grow together.  
If interested, please send your resume (including your experience with PX4, ROS, and Gazebo) to <zhuoan@stu.pku.edu.cn>.  
Let’s improve the XTDrone simulation platform together!

### Contributors

Many thanks for your contributions to XTDrone:  
Chen Keyan, Xu Jiangwei, Lu Yongguang, Chen Gao, Sun Changhao, Nie Ying, Kong Fanjie, Li Chaoran, Li Xudong, Zhang Huaqing, Lin Zihan, He Yao

### UAV Simulation Group – China Robotics Competition

The **2024 China Robotics Competition** has concluded. For competition details, see the [official website](http://crc.drct-caa.org.cn/index.php). The UAV Simulation Group used XTDrone as its platform.  
The **2025 UAV Simulation Group** will continue to be organized by the XTDrone team. We look forward to your participation and showcase of talent!

### Collaboration

If you wish to collaborate with the XTDrone team, please contact An Zhuo at <zhuoan@stu.pku.edu.cn>.
