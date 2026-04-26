# edgeHackathon
# 🎓 SmartPlan - SJSU Academic Advising AI Agent

**SmartPlan** is a conversational AI-powered academic advising system designed to help San José State University (SJSU) students navigate their degree requirements, understand course prerequisites, and plan their academic journey.

## Overview

SmartPlan leverages a **Graph RAG (Retrieval-Augmented Generation)** architecture to deliver accurate, context-aware academic advising. The system combines:

- **Neo4j Graph Database**: Stores course catalog data, prerequisites, and degree requirements as a knowledge graph
- **Claude AI (Anthropic)**: Natural language understanding and generation for intelligent conversations
- **Streamlit**: User-friendly web interface for students to ask questions in plain English

## Features

✨ **Conversational Interface**: Ask natural language questions about courses and prerequisites  
📚 **Prerequisite Analysis**: Understand course dependencies and progression paths  
🎯 **Qualification Check**: Learn which courses you're eligible to take based on completed courses  
🔗 **Full Prerequisite Chains**: Explore complete prerequisite hierarchies for any course  
💾 **Conversation Memory**: Multi-turn conversations with persistent context  
🗑️ **Session Management**: Clear conversation history and reset chat state

## Quick Start

### Prerequisites

- Python 3.9+
- Neo4j Aura instance (cloud-hosted) or Neo4j Desktop/Server
- Anthropic API key (Claude access)
- Git

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/ReetiShah/edgeHackathon.git
   cd edgeHackathon
