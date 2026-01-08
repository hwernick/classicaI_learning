Classical Learning

An LLM-powered application for engaging in structured educational dialogue outside of traditional classroom settings.

Overview

Classical Learning explores how Socratic dialogue can be adapted into a modern, interactive format using large language models. The goal is to guide users through thoughtful questioning that encourages reflection, clarification, and critical thinking.

Motivation

Socratic dialogue is typically confined to classrooms, seminars, or one-on-one instruction. This project asks whether that mode of inquiry can be made more accessible. 

The experiment here is whether an LLM, when carefully constrained and prompted, can support meaningful dialogue that helps users examine their assumptions, articulate their thinking, and explore ideas more deeply.

Key Features

Guided Socratic-style dialogue driven by structured prompts

Separation between dialogue and note-taking to support reflection

Analysis of the users conversational patterns and recurring ideas

Persistent chat history and conversation context

Document upload to ground discussions in external material

How It Works 

The application consists of a frontend interface for dialogue and notes, backed by a server that manages conversation state and communicates with an LLM API.

The backend is responsible for:

Maintaining dialogue context

Applying system prompts that enforce a Socratic style

Handling uploaded documents and user notes

The frontend focuses on presenting conversations clearly and making it easy to move between dialogue and reflection.

Tech Stack

Frontend: React / React Native (Expo)

Backend: Node.js with TypeScript

LLM Integration: OpenAI API

Project Status

The goal of this project was to explore a concept rather than a ship a production-ready application. Development focused on architecture and prompt design, and the project is not currently being actively extended or deployed.

