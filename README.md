# 🎬📚🎵 Cross-Media Recommendation Engine Demo

Welcome to the **Cross-Media Recommendation Engine**! This is an early-stage demo project aimed at providing personalized entertainment recommendations across movies, TV series, books, and music, powered by **AI**.

---

## 🚀 Project Overview

This project is designed to help users discover related content across different entertainment mediums. Starting with a movie, the app retrieves its features using **The Movie Database (TMDB) API** and leverages **GPT-4o** to suggest recommendations based on the user's selection of category (movies, TV series, books, or music).

### Current Features:
1. **Movie Feature Extraction**:  
   - The app connects to TMDB API to fetch metadata for the input movie.
2. **AI-Powered Recommendations**:  
   - The metadata is passed to GPT-4o with carefully designed prompts to generate recommendations tailored to the chosen category.
3. **Interactive Gradio Interface**:  
   - Users can select the recommendation category via a simple interface powered by **Gradio**.

---

## 💡 Planned Enhancements

This is just the beginning! Here’s what’s coming next:
1. **Expanded Input Options**:  
   - Allow recommendations starting from books, music, or TV series, not just movies.
2. **Multi-API Integration**:  
   - Incorporate additional APIs (e.g., OpenLibrary for books, Spotify for music) to broaden the recommendation scope.
3. **Improved Model Performance**:  
   - Replace GPT-4o with an **open-source model** trained specifically for this task.
4. **Enhanced Recommendation Logic**:  
   - Develop a more robust system to improve recommendation quality and relevance.

---

## 🛠️ Getting Started

### Prerequisites:
To run this project, you need the following API keys:
1. **OpenAI API Key** (for GPT-4o or any LLM implementation).  
2. **TMDB API Key** (for fetching movie metadata).  

Ensure you have both API keys and proper authorization set up in your environment variables.
