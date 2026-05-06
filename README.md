🚀 Blue-Green Deployment Experiment
📌 Overview

This project demonstrates the concept of Blue-Green Deployment, a DevOps strategy used to achieve zero-downtime deployments and safer releases.

In this experiment, two identical environments (Blue and Green) are maintained. At any time, one serves live traffic while the other is used for testing new updates.

🎯 Objectives
Understand Blue-Green deployment strategy
Achieve zero downtime during deployment
Minimize risks during release
Practice environment switching
🧠 Concept
🔵 Blue Environment
Current live/production version
Handles user traffic
🟢 Green Environment
New version of the application
Used for testing before release
🔁 Switching

Once Green is verified:

Traffic is switched from Blue → Green
Green becomes the new production
🏗️ Architecture

User → Load Balancer → (Blue / Green Environment)

Load balancer routes traffic
Only one environment is live at a time
