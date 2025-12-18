# TODO Client - React Frontend

React frontend for the TODO application deployed on EC2.

## Setup

1. Install dependencies:
```bash
npm install
```

2. Create `.env` file:
```bash
VITE_API_URL=http://your-ec2-server-url:5000
```

3. Start development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Deployment

The built files in `dist/` folder can be served by any web server.