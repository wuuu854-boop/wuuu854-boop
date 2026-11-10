### UAV systems × AI

Open-source work on drone autonomy: simulation-first, measured, and explicit
about what has not been run yet.

- 📦 **[uav-yolo-offboard-tracking](https://github.com/wuuu854-boop/uav-yolo-offboard-tracking)** — PX4 + Gazebo + ROS 2 closed loop: detection → tracking → ground projection → Offboard approach. **9/9 SITL trials, 0.73 m median landing error**, 201 unit tests + 11 ROS integration tests, a container that is built and tested on every push.
- 🧠 **A scene-specific YOLO11n** (mAP@50 0.96 held out) with the decoder bug that made it unusable found and fixed — and an honest [report](https://github.com/wuuu854-boop/uav-yolo-offboard-tracking/blob/main/docs/model.md) on why it does not fly yet.
- 🧰 **[Skills](https://github.com/wuuu854-boop/uav-yolo-offboard-tracking/tree/main/skills)** — ten debugging procedures this stack actually produced, from QoS silence to a PX4 gz bridge with no magnetometer.
- 📄 Every number traces to a CSV, and every claim carries a [verification record](https://github.com/wuuu854-boop/uav-yolo-offboard-tracking/blob/main/docs/verification-log.md).
- 🤝 Upstream contribution: [PX4-ROS2-Gazebo-YOLOv8#43](https://github.com/monemati/PX4-ROS2-Gazebo-YOLOv8/pull/43).

<sub>Sim-to-real, measured.</sub>