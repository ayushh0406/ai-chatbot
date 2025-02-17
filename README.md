<a href="https://chat.vercel.ai/"> <img alt="Next.js 14 and App Router-ready AI chatbot." src="app/(chat)/opengraph-image.png"> <h1 align="center">Next.js AI Chatbot</h1> </a>

<p align="center"> An Open-Source AI Chatbot Template Built With Next.jsand the AI SDK by Vercel. </p>

<p align="center"> <a href="#features"><strong>Features</strong></a> · <a href="#model-providers"><strong>Model Providers</strong></a> · <a href="#deploy-your-own"><strong>Deploy Your Own</strong></a> · <a href="#running-locally"><strong>Running Locally</strong></a> </p> <br/>

Features
Next.js App Router
hiii

Advanced routing for seamless navigation and performance

React Server Components (RSCs) and Server Actions for server-side rendering and increased performance

AI SDK

Unified API for generating text, structured objects, and tool calls with LLMs

Hooks for building dynamic chat and generative user interfaces

Supports OpenAI (default), Anthropic, Cohere, and other model providers

shadcn/ui

Styling with Tailwind CSS

Component primitives from Radix UI for accessibility and flexibility

Data Persistence

Vercel Postgres powered by Neon for saving chat history and user data

Vercel Blob for efficient file storage

NextAuth.js

Simple and secure authentication

Model Providers
This template ships with OpenAI gpt-4o as the default. However, with the AI SDK, you can switch LLM providers to OpenAI, Anthropic, Cohere, and many more with just a few lines of code.

Deploy Your Own
You can deploy your own version of the Next.jsAI Chatbot to Vercel with one click:


Running Locally
You will need to use the environment variables defined in.env.example to run Next.jsAI Chatbot. It's recommended you use Vercel Environment Variables for this, but a .env file is all that is necessary.

> Note: You should not commit your .env file or it will expose secrets that will allow others to control access to your various OpenAI and authentication provider accounts.

Install Vercel CLI: npm i -g vercel

Link local instance with Vercel and GitHub accounts (creates .vercel directory): vercel link

Download your environment variables: vercel env pull

bash
pnpm install
pnpm dev
Your app template should now be running on localhost:3000.
