# A7670C Render Deployment

## Overview
Static dashboard for live GPS & sensor data from A7670C 4G module.

## Steps
1. Push this repository to GitHub.
2. In Render, create a **New Static Site**.
3. Connect GitHub repo.
4. Set **Publish Directory** to `dashboard`.
5. Deploy → URL will show live charts.

**Note:** AT script runs locally to publish MQTT data. Browser updates live via public broker.
