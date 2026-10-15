# HoldLight — Accessible Climbing

**CPT208 — Human-Centric Computing**

A mobile-first climbing assistance app for blind and low-vision climbers. It combines layered route previews with real-time next-hold guidance using camera, audio and speech interactions.

[Live Portfolio](https://yuuu-05.github.io/CPT208-ClimbProject-C2-4/) · [Design Repository](https://github.com/June412/holdlight-design-portfolio) · [Demo Video](https://github.com/Yuuu-05/HoldLight/releases/tag/project-demo)

## Run

Requires Node.js 20+, Python 3.10+ and MongoDB. Create the frontend and backend `.env` files from their `.env.example` templates; configure `MONGO_URI` and `JWT_SECRET`. See [Deployment](DEPLOYMENT.md) for environment settings, Python dependencies and vision model weights.

From the repository root:

```bash
npm run install:all
npm run dev:backend
```

In a second terminal:

```bash
npm run dev:frontend
```
