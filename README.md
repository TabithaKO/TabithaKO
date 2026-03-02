### Hi, I'm Tabby 👋

I'm a PhD researcher at Brown University advised by [Professor Nora Ayanian](https://vivo.brown.edu/display/nayanian). My work is on robotic cloth manipulation — building the hardware, perception, and learning systems needed to handle fabric reliably on real robots.

---

### 🦾 [Sew Unit](https://tabithako.github.io/projects/sew-unit) — Bimanual Cloth Manipulation Platform

A bimanual robot platform I designed and built from scratch: custom aluminum extrusion frame, two inverted SO-101 arms, ROS2/MoveIt motion planning, and leader-follower teleoperation for data collection.

<video src="https://tabithako.github.io/assets/videos/sew-unit-mirror-bimanual.mp4" autoplay loop muted playsinline></video>

<video src="https://tabithako.github.io/assets/videos/sew-unit-teleop-leader.mp4" autoplay loop muted playsinline></video>

---

### 🧠 [Learning Cloth Dynamics](https://tabithako.github.io/projects/cloth-dynamics) — From Paper to Real Fabric

Took PhysTwin and PGND, got them running on cloth data I collected myself, then extended PGND with a differentiable render loss (DINOv2 + SSIM) and live camera conditioning at rollout time. Three model variants — each adds a new supervisory signal on top of the last.

<video src="https://tabithako.github.io/assets/videos/pgnd-ep0201-baseline.mp4" autoplay loop muted playsinline></video>
<video src="https://tabithako.github.io/assets/videos/pgnd-ep0201-phase2.mp4" autoplay loop muted playsinline></video>
<video src="https://tabithako.github.io/assets/videos/pgnd-ep0201-visual.mp4" autoplay loop muted playsinline></video>

*Baseline (geometry only) → Phase 2 (+ render loss) → Visual PGND (+ camera conditioning at rollout)*

---

### ✋ [Custom Grippers & Teleop Tools](https://tabithako.github.io/projects/grippers)

Two custom end-effectors: silicone FSR grippers with embedded force sensors for contact-aware grasping, and a UMI-inspired handheld teleop gripper with ArUco markers and IMU for imitation learning data collection.

<video src="https://tabithako.github.io/assets/videos/sew-unit-denim-pinch.mp4" autoplay loop muted playsinline></video>

---

### Research repos
- [`TabithaKO/PhysTwin`](https://github.com/TabithaKO/PhysTwin) — SO-101 cloth data pipeline, multi-camera perception, trajectory generation
- [`TabithaKO/pgnd`](https://github.com/TabithaKO/pgnd) — visual PGND: mesh-constrained Gaussian Splatting + DINOv2 camera conditioning

📄 [tabithako.github.io](https://tabithako.github.io) &nbsp;·&nbsp; 📫 tabitha.oanda@gmail.com &nbsp;·&nbsp; 👗 [Fashion](https://www.tkobytabithaoanda.com/)
