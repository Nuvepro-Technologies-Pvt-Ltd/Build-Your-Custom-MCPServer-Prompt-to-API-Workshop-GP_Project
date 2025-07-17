# Project Overview

This project is structured into two main components, each focusing on a specific functionality in building and demonstrating an MCP (Model-Controlled Processor) Server integrated with a Movie Ticket Booking System.

## 1. BuildingMCPServer
This folder contains the implementation of the MCP Server, which acts as a bridge between natural language queries and backend API calls. It converts user instructions into structured API requests using rule-based or LLM-powered tools.

### Key Files:
1. mcp_server.py: Core MCP server logic. Handles natural language input, tool invocation, and structured API call generation.

2. API_Documentation.md: Describes the API endpoints (e.g., /movies, /bookings) used by the MCP server to interact with the backend.

3. README.md: Instructions on how to set up and run the MCP server.


## 2. MovieTicketBookingSystem
This folder contains the full-stack Movie Ticket Booking Application, used by the MCP server to demonstrate real-world API interactions.

1. Subfolders:
    - node-backend/: RESTful API backend built with Node.js. Exposes endpoints for movies, bookings, cancellations, etc.

    - react-frontend/: React-based UI that allows users to browse and book movie tickets manually (for comparison or fallback).

2. README.md: Setup instructions for backend and frontend.

3. start-app.bat: Batch script to start both frontend and backend services locally.

Detailed setup and usage instructions are provided within each respective folder.

