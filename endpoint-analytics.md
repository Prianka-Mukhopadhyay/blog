---
title: "The New and Fresh analytics in Inference Endpoints"
thumbnail: /blog/assets/endpoint-analytics/thumbnail.png
authors:
- user: erikkaum
- user: beurkinger
- user: rtrm
- user: co42
- user: michellehbn
---

# Analytics is important

Analytics and metrics are key to understanding your deployment’s performance. Are your [Inference Endpoints](https://endpoints.huggingface.co) overloaded? How many requests are they handling? Well-visualized, relevant metrics displayed in real-time are crucial for monitoring and debugging.

We realized our analytics dashboard needed a refresh. As we debug endpoints ourselves, we’ve felt the same pain as our users. So, we planned several improvements to provide a better experience.
# What’s New?

⏰ Real-Time Metrics: Data now updates in real-time, giving you an up-to-the-second view of your endpoint’s performance. Monitor request latency, response times, and error rates instantly. We’ve also reworked the backend to ensure data loads quickly, even for high-traffic endpoints.

<p align="center">
  <video width="100%" autoplay loop muted playsinline>
    <source src="https://huggingface.co/datasets/huggingface/documentation-images/resolve/main/blog/endpoint-analytics/send_request.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>

🔬 Customizable Time Ranges & Auto-Refresh: We know that different users need different views, so we’ve made it easier to zoom in on a specific time range or track long-term trends. You can also enable auto-refresh, ensuring that your dashboard stays up to date without needing to manually reload.

<p align="center">
  <video width="100%" autoplay loop muted playsinline>
    <source src="https://huggingface.co/datasets/huggingface/documentation-images/resolve/main/blog/endpoint-analytics/custom_time_zoom.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</p>

🔄 Replica Lifecycle View: Track each replica’s lifecycle, from initialization to termination, observing all state transitions. This helps you understand your endpoint, even with multiple replicas running simultaneously.

<p align="center">
  <img src="https://huggingface.co/datasets/huggingface/documentation-images/resolve/main/blog/endpoint-analytics/replica_status.png"><br>
</p>

We’re continuously iterating on these updates and welcome your feedback. Let us know what works, what doesn’t, and what you’d like to see next! 🙌
Check out the changes at [Inference Endpoints](https://endpoints.huggingface.co) .
