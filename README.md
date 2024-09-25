# Image Analyzer Tool

This project is an **Image Analyzer Tool** developed using **Next.js** and integrates with the **ChatGPT API**, along with other services for image analysis and processing. The tool allows users to upload images and receive detailed analysis and feedback about the content within the image, leveraging the power of modern AI technologies.

## Features

- **Image Upload & Processing**: Users can upload images which are processed using various APIs, including image recognition and metadata extraction.
- **AI-Powered Analysis**: The tool uses the **ChatGPT API** to provide insights, descriptions, and explanations of image content.
- **Real-time Updates**: Leveraging the built-in capabilities of **Next.js**, the page auto-updates as new data is received, giving users immediate feedback.
- **Optimized Performance**: Integrated with **next/font** to optimize font loading and ensure fast, seamless user experiences.
- **Scalable & Deployed on Vercel**: Deployed on the **Vercel Platform** for easy scalability, performance, and hassle-free maintenance.

## Getting Started

### Development Server

To start the development server, run:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Once started, open [http://localhost:3000](http://localhost:3000) in your browser to interact with the app.

You can begin by modifying the main logic in `app/page.js`. The tool supports **live reloading**, so changes will reflect immediately.

### Prerequisites

- **Node.js** and **npm** (or **yarn** or **pnpm**)
- API access to the **ChatGPT API** and other image processing APIs (e.g., **AWS Rekognition**, **Google Vision API**, etc.)

### Installation

Clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/Saipradyumnagoud/image-analyzer-tool.git
cd image-analyzer-tool
npm install
```

Set up the required environment variables for API keys:

```bash
# .env.local
NEXT_PUBLIC_CHATGPT_API_KEY=<your-chatgpt-api-key>
NEXT_PUBLIC_IMAGE_API_KEY=<your-image-api-key>
```
