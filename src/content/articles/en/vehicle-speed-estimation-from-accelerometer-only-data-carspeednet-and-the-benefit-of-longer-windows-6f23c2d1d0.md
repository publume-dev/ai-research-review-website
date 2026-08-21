---
decisionKey: "6f23c2d1d004d643fde7adb8e1e62ea787ef189975ee490216bd89a0dda0961e"
language: "en"
title: "Vehicle Speed Estimation from Accelerometer-Only Data: CarSpeedNet and the Benefit of Longer Windows"
summary: "CarSpeedNet estimates vehicle speed using only smartphone accelerometer data, without gyroscope or other inputs. Experiments show that increasing the input window from 1 second to 4 seconds reduces the root-mean-square error from 2.9 m/s to 1.8 m/s."
publishedAt: "2026-08-21T14:06:18.549Z"
score: 0.85
topics:
  - "Machine Learning"
  - "Applied ML"
topicIds:
  - "machine-learning-168tuwc"
  - "applied-ml-1tlxfzz"
sourceUrls:
  - "https://arxiv.org/abs/2401.07468"
---

CarSpeedNet is a learning-based model that estimates vehicle speed from a window of three-axis smartphone acceleration, without requiring gyroscope, wheel-odometry, vehicle-bus, or positioning input at inference. The model has 178,169 parameters, with 32-bit weights occupying about 0.68 MiB.

In experiments on 13.2 hours of on-road driving, increasing the input window from 1 second to 4 seconds reduced the root-mean-square error from 2.9 m/s to 1.8 m/s and the mean absolute error from 1.3 m/s to 0.72 m/s on a 0.5-hour holdout. This suggests that longer temporal context improves speed estimation accuracy.

The paper is a preprint under review, so results have not yet been peer-reviewed. Additionally, the evaluation relies on a single driving session dataset, and generalizability to diverse conditions is not established.
