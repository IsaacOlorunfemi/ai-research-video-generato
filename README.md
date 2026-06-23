# ai-research-video-generato
AI-powered n8n workflow that researches trending AI topics, generates slideshow content, creates images with Ideogram, produces videos with HeyGen, and stores outputs automatically in Google Drive.
# AI Research & Video Generator

## Overview

This project is an end-to-end AI content generation pipeline built in n8n. The workflow automatically discovers trending AI topics, researches them, generates engaging content, creates visual assets, and produces short-form videos ready for publishing.

The goal is to automate the entire content creation process from topic discovery to final video generation with minimal human intervention.

---

## Features

### 1. Topic Discovery

* Searches for trending discussions related to AI, AI agents, automation, and no-code tools.
* Uses Perplexity to identify high-interest topics.

### 2. Content Research

* Scrapes relevant source articles using Firecrawl.
* Extracts website content for analysis and content generation.

### 3. Topic Selection

* Evaluates topics based on:

  * Viral potential
  * Controversy and engagement
  * Authority positioning
  * Relevance to the AI industry
* Selects the strongest topic automatically using GPT.

### 4. Slideshow Creation

* Generates a 7-slide content structure:

  * Hook
  * Key insights
  * Actionable takeaways
  * Call to action
* Optimized for short-form social media content.

### 5. Image Generation

* Creates cinematic visual concepts for each slide.
* Generates custom images using Ideogram.
* Organizes assets automatically in Google Drive.

### 6. Video Production

* Converts slideshow concepts into video prompts.
* Uploads generated assets to HeyGen.
* Creates short-form AI-generated videos automatically.

### 7. Asset Management

* Creates dedicated folders for each topic.
* Stores images and final videos in Google Drive.
* Updates workflow records after successful generation.

---

## Workflow Architecture

Topic Research
→ Content Scraping
→ Topic Selection
→ Slideshow Generation
→ Visual Prompt Creation
→ Image Generation
→ Asset Upload
→ Video Generation
→ Google Drive Storage

---

## Technology Stack

### Automation

* n8n

### AI Models

* OpenAI GPT-5
* OpenAI GPT-5 Mini

### Research & Retrieval

* Perplexity
* Firecrawl

### Media Generation

* Ideogram
* HeyGen

### Storage

* Google Drive

---

## Required Credentials

Before running the workflow, configure:

* OpenAI API
* Perplexity API
* Firecrawl API
* Ideogram API
* HeyGen API
* Google Drive OAuth

---

## Importing the Workflow

1. Download the workflow JSON file.
2. Open n8n.
3. Select Import Workflow.
4. Upload the JSON file.
5. Configure all required credentials.
6. Activate the workflow.

---

## Use Cases

* AI content marketing
* Social media automation
* Thought leadership content
* Short-form video generation
* Automated research pipelines
* AI agency content production

---

## Notes

This workflow is designed as a production-ready content automation system. It combines research, content generation, image creation, video generation, and asset management into a single automated pipeline.
