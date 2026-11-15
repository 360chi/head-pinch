# Head Crusher

Crush heads, pets and cars through your phone camera, the old trick of squashing something far away between your fingers. Open https://360chi.github.io/head-pinch/ in Safari, tap Start, allow the camera.

- **Targets:** people's heads (100), animals such as cats, dogs and horses (150), and cars, trucks, buses and motorbikes (200). A target that is moving pays 1.5x.
- **One crusher:** only one hand crushes at a time, and only when its fingertips are inside the crush zone. Hands resting at the edges are ignored.
- **Crush zone:** by default the top 15%, bottom 25% and 10% on each side are dead zones. Tap the crop button to drag the edges.

Face, hand and object tracking is MediaPipe Tasks Vision (Google, Apache-2.0) with the EfficientDet-Lite0 COCO model, all served from this repo. Nothing leaves the phone.
