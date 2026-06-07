# AI-Powered Marketing Automation Platform

A multi-agent AI marketing platform built using CrewAI and Gemini 2.5 Flash that automates market research, marketing strategy development, content planning, content creation, blog writing, and SEO optimization.

## Overview

Marketing teams often spend significant time researching markets, creating content strategies, drafting social media posts, writing blogs, and optimizing content for search engines. This project streamlines these activities by orchestrating multiple specialized AI agents that collaborate to generate a complete marketing workflow.

The platform leverages CrewAI's multi-agent framework to coordinate marketing experts, content creators, blog writers, and SEO specialists, enabling businesses to automate large portions of their content marketing process.

## Features

* Market Research Automation

  * Competitor and industry analysis
  * Trend identification
  * Audience research

* Marketing Strategy Generation

  * Campaign planning
  * Marketing recommendations
  * Strategic content direction

* Content Calendar Creation

  * Content scheduling
  * Topic planning
  * Platform-specific content organization

* Social Media Content Generation

  * Post drafts
  * Captions
  * Marketing copy

* Blog Content Creation

  * Topic research
  * Blog drafting
  * Long-form content generation

* SEO Optimization

  * SEO-focused content refinement
  * Keyword integration
  * Search visibility improvements

## Architecture

The system consists of four specialized AI agents:

### Head of Marketing

Responsible for:

* Market research
* Marketing strategy development
* Campaign planning

### Content Creator (Social Media)

Responsible for:

* Content calendar generation
* Social media post creation
* Reel script generation

### Content Writer (Blogs)

Responsible for:

* Blog topic research
* Blog drafting
* Long-form content creation

### SEO Specialist

Responsible for:

* SEO analysis
* Content optimization
* Search engine visibility improvements

## Tech Stack

### AI & Agent Framework

* CrewAI
* Google Gemini 2.5 Flash

### Development

* Python
* Pydantic
* Python Dotenv

### Tools

* SerperDevTool
* ScrapeWebsiteTool
* DirectoryReadTool
* FileReadTool
* FileWriterTool

## Workflow

1. Conduct market research
2. Generate marketing strategy
3. Create content calendar
4. Draft social media content
5. Generate reel scripts
6. Research blog topics
7. Draft blog content
8. Perform SEO optimization

The entire workflow is executed sequentially through CrewAI's orchestration engine.