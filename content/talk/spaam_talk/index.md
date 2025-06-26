---
title: "Deepfake Detection Using Anomaly Detection Techniques"
summary: "Presented at the University of Warwick SPAAM Seminar, UK."

event: "University of Warwick SPAAM Seminar"

url_slides: "uploads/SPAAM_seminar_2024.pptx"
url_video: "https://www.youtube.com/watch?v=5GjcaH_HzNM"
date: 2024-06-20T09:00:00Z # Use ISO 8601 format for date and time

links:
 - name: "Website"
   url: "https://warwick.ac.uk/fac/sci/maths/research/events/seminars/areas/spaam/"


---
Recent advances in generative models, such as generative adversarial networks (GANs) and diffusion models, have enabled the creation of highly realistic fake images and videos. In particular, the generation of fake human faces, or so-called deepfakes, has become increasingly popular, with such images/videos often being used for malicious purposes. Consequently, many deepfake detection techniques have been developed to counteract this threat. The most common approach to deepfake detection involves training a binary classifier model on both real and fake images, which performs well on deepfake generation methods seen during training but struggles against unseen manipulations. To address this limitation, we propose to formulate deepfake detection as a one-class anomaly detection problem. Specifically, we introduce a differential anomaly detection framework that uses only real images during training. Preliminary results show promising generalisation performance across different manipulation methods.