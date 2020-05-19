A port of the "Fleetman" project from the Istio and Kubernetes training course. The intention of this project is to integrate with a real "live" security tracking system and to potentially move it towards a commercial release.

Note: This is not aligned with any particular training course - if you're looking for the repo for a training course (Istio, Kubernetes) then this probably isn't it! Look for k8s-fleetman or istio-fleetman!

See the Issue tracker for work in progress, but the starting point is:

[] Initial support for the Rewire Security 104 Pro Tracker https://www.amazon.co.uk/gp/product/B00WAE5UMM
[] CRUD Support for Vehicles / Devices
[] Support full authentication and authorization, maybe using Auth0, maybe not.
[] Integrate a commercial API Gateway such as Kong
[] New Alerting System which will initially support a "Zone Out" alert. SMS alerts.
[] Remove the Redundant Position Simulator
[] Integrate a full Publish/Subscribe system instead of a Queue
