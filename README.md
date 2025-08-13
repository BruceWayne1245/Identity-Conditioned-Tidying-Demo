## 🎥 Demo Video (2 min)
- **Direct MP4:** https://github.com/BruceWayne1245/Identity-Conditioned-Tidying-Demo/releases/download/v1.0-demo/demo-identity-conditioned-tidying.mp4.mp4

### Key features
- **LLM-in-the-Loop Placement Reasoning** — When a previously unseen object appears, the system feeds a summary of prior interactions and CLIP multi-label attributes into GPT-4o to infer a placement suggestion, which is written to `/placement_prompt` for planning and execution.

- **Preference-Aware Continual Learning** — Collaborative filtering + pattern reasoning continuously refine user preferences. The desktop is discretised into nine zones (A–I) to track long-term habits and adapt when habits change; core state is shared via a `scene_objects` structure in rosparam.

- **Occlusion-Robust Real-Time Tracking** — YOLOv5 tracking is augmented with pixel-displacement / disappearance thresholds and a 3-second stability check; positions are re-evaluated with RealSense 3D and logged to rosparam.

