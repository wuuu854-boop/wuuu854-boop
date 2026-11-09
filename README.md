### UAV systems × AI

Open-source work on drone autonomy: simulation-first, measured, and explicit
about what has not been run yet.

- 📦 **[uav-yolo-offboard-tracking](https://github.com/wuuu854-boop/uav-yolo-offboard-tracking)** — PX4 + Gazebo + ROS 2 closed loop: detection → ground projection → Offboard approach. 117 tests, an installable `uav_tracking` package, a ROS build CI that runs the nodes; the SITL trials are still pending.
- 🧰 **[Skills](https://github.com/wuuu854-boop/uav-yolo-offboard-tracking/tree/main/skills)** — seven debugging procedures this stack actually produced (QoS silence, camera mount, world plugins, intrinsics, version drift, numpy ABI, claim-to-CSV).
- 🔧 **[Adoption guide](https://github.com/wuuu854-boop/uav-yolo-offboard-tracking/blob/main/docs/adoption.md)** — what to change for your own target, camera or scene, and the check that proves it worked.
- 📄 Every number traces to a CSV, and every claim carries a [verification record](https://github.com/wuuu854-boop/uav-yolo-offboard-tracking/blob/main/docs/verification-log.md).
- 🤝 Upstream contribution: [PX4-ROS2-Gazebo-YOLOv8#43](https://github.com/monemati/PX4-ROS2-Gazebo-YOLOv8/pull/43).

<sub>Sim-to-real, measured.</sub>