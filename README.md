# HPA-VPA
🔹 Horizontal Autoscaling

In Kubernetes, horizontal autoscaling means adding or removing pods (instances) of an application based on demand. Instead of making a single pod bigger, Kubernetes creates more replicas when traffic increases and reduces them when traffic drops. This is handled using the Horizontal Pod Autoscaler (HPA), which typically monitors CPU or memory usage (or custom metrics). It helps ensure your application can handle load spikes while optimizing resource usage during low demand.

🔹 Vertical Autoscaling

Vertical autoscaling means increasing or decreasing the resources (CPU/memory) assigned to a single pod instead of adding more pods. In Kubernetes, this is done using the Vertical Pod Autoscaler (VPA). It adjusts resource requests/limits automatically based on usage. Unlike horizontal scaling, vertical scaling may require restarting pods to apply new resource values, making it less suitable for real-time scaling but useful for optimizing resource allocation.
