RemasterShadhi: AI Multi-Language Lyric Generator
📝 Project Overview
RemasterShadhi is a single-page web application designed to help songwriters and creatives quickly generate original song lyrics based on a specific theme, emotion, or story. Leveraging the power of the Gemini API, the tool can craft structured lyrics (Intro, Verses, Chorus, Bridge, Outro) in multiple languages, with fine-tuned control over genre, mood, audience, and rhyme style.
✨ Key Features
Intelligent Lyric Generation: Uses the powerful Gemini-2.5-Flash model for creative and contextually relevant lyric writing.
Multi-Language Support: Generate lyrics in English, Hindi, Tamil (தமிழ்), and Malayalam (മലയാളം).
Structured Song Output: Automatically formats the output into standard song sections: INTRO, VERSE 1, CHORUS, VERSE 2, BRIDGE, OUTRO.
Advanced Controls: Customize generation using optional parameters:
Genre: Pop, Rock, Hip-Hop, Folk, Filmi, etc.
Mood/Tone: Happy, Melancholy, Romantic, etc.
Audience
Rhyme Scheme
Artist Style Imitation
Dark-Mode Aesthetic: A modern, dark, and highly responsive UI built for excellent mobile usability.
🚀 How to Use
The application runs entirely within a single index.html file.
Enter a Theme: Provide the core idea for your song in the "Enter a theme, emotion, or story" textbox (e.g., "The feeling of leaving your hometown," "A broken promise under the monsoon rain").
Select Language: Choose your desired output language (e.g., Tamil).
Adjust Advanced Options (Optional): Click "Advanced Options" to specify a Genre, Mood, Rhyme Scheme, or target an Artist Style for more personalized results.
Generate: Click the "Generate Lyrics" button.
Review: The generated lyrics will appear below, clearly marked with sections.
🛠 Technology Stack
This is a minimalist, serverless application focused on front-end functionality and API integration.
HTML5: The core structure of the application.
JavaScript (ES Modules): Handles all application logic, user interaction, and API communication, including exponential backoff for robust retries.
Tailwind CSS: Used for utility-first, fully responsive styling.
Gemini API (gemini-2.5-flash-preview-09-2025): Powers the core lyric generation functionality.
⚙️ Setup and Configuration
Since this is a single static HTML file, running it is straightforward.
Local Execution: Clone or download the repository and open index.html directly in your web browser.
API Key: To run the application, you need to configure the Gemini API key.
In a production environment, you would typically use a secure backend proxy to manage your API key.
For testing or local deployment, replace the placeholder const apiKey = ""; in the <script> block with your actual key if the environment does not provide it automatically.
<!-- end list -->
