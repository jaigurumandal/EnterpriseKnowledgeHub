# AI-Powered Enterprise Knowledge Assistant

## Problem Statement
Enterprise teams struggle to quickly find accurate information across internal documents.
Traditional search lacks context and understanding.

## Solution
A secure, AI-powered web application that allows users to query enterprise documents
using Generative AI with Retrieval-Augmented Generation (RAG).

## Key Features
- Secure authentication & role-based access
- Document ingestion and semantic search
- AI-powered question answering grounded in enterprise data
- Cost-controlled and auditable AI usage

## Tech Stack
- Backend: ASP.NET Core, C#
- Frontend: Blazor
- Cloud: AWS (S3, Cognito, ECS)
- Database: MySQL
- AI: OpenAI / AWS Bedrock
- Architecture: Clean Architecture

## High-Level Architecture
Blazor UI → ASP.NET Core API → AI & Data Services
- Documents stored in S3
- Metadata in MySQL
- Embeddings in Vector Database
- AI responses generated using RAG
