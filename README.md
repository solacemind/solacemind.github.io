# talk2me.github.io
Talk2Me: AI powered emotional support platform offering daily personalized, empathetic conversations to help users navigate mental health challenges. Free, private, and accessible.

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Talk2Me: Accessible AI for Emotional Support</title>
    <style>
        /* CSS for a clean, modern, Gen Z-friendly look */
        :root {
            --primary-color: #92DD09; /* Bright Lime Green (from banner) */
            --secondary-color: #E6E1D9; /* Light Beige/Gray (from banner) */
            --text-color: #1A1A1A; /* Dark Text */
            --font-family: 'Arial', sans-serif; /* Use a clean, modern font */
        }

        body {
            font-family: var(--font-family);
            margin: 0;
            padding: 0;
            background-color: var(--secondary-color);
            color: var(--text-color);
            line-height: 1.6;
        }

        /* Utility for centering content */
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }

        /* Banner/Hero Section */
        .hero {
            background-image: url('./assets/talk2me-banner.png'); /* IMPORTANT: Ensure path is correct */
            background-size: cover;
            background-position: center;
            height: 60vh; /* Adjust height as needed */
            display: flex;
            align-items: center;
            justify-content: center;
            text-align: center;
            margin-bottom: 40px;
            position: relative;
        }
        
        .hero-overlay {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            /* Optional: Add a subtle overlay if text is hard to read on the banner */
            /* background: rgba(0, 0, 0, 0.1); */
        }

        /* Content Sections */
        section {
            padding: 40px 0;
        }

        h1 {
            font-size: 3em;
            color: var(--primary-color);
            text-align: center;
            margin-bottom: 5px;
        }

        h2 {
            color: var(--primary-color);
            font-size: 2em;
            border-bottom: 3px solid var(--primary-color);
            padding-bottom: 10px;
            margin-top: 0;
        }

        /* Feature Grid */
        .feature-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 30px;
            margin-top: 20px;
        }

        .feature-card {
            background-color: white;
            padding: 25px;
            border-radius: 12px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            transition: transform 0.2s;
        }

        .feature-card:hover {
            transform: translateY(-5px);
        }

        .feature-card h3 {
            color: var(--text-color);
            font-size: 1.5em;
            margin-top: 0;
        }

        /* Roadmap List */
        .roadmap-list {
            list-style: none;
            padding: 0;
        }

        .roadmap-list li {
            background-color: white;
            padding: 15px;
            margin-bottom: 15px;
            border-left: 5px solid var(--primary-color);
            border-radius: 4px;
        }
        
    </style>
</head>
<body>

    <div class="hero">
        <div class="hero-overlay">
            </div>
    </div>

    <div class="container">
        
        <section id="overview">
            <h2>🧠 Concept Overview</h2>
            <p><strong>Talk2Me</strong> is a groundbreaking, **free AI-powered emotional support platform** designed to democratize access to mental health resources. Our core offering is a full-hour daily support session with an empathetic, personalized AI listener.</p>
            <p>We aim to dismantle common barriers to traditional therapy—including <strong>cost, social stigma, and lack of awareness</strong>—by providing a private, judgment-free space for individuals to process their thoughts and mental health challenges.</p>
            
            <h3>Target Audience 🎯</h3>
            <p>Individuals aged <strong>16 and older</strong> who are actively seeking mental health support but are constrained by financial, social, or geographic barriers. This includes students, low-income individuals, and anyone uncomfortable with or unable to access in-person therapy.</p>
        </section>

        <section id="features">
            <h2>✨ Core Features & Tech Stack</h2>
            <div class="feature-grid">
                
                <div class="feature-card">
                    <h3>Empathetic AI Conversations (NLP)</h3>
                    <p>Real-time dialogue powered by **Natural Language Processing (NLP)** that recognizes emotion, intent, and context for supportive listening.</p>
                </div>
                
                <div class="feature-card">
                    <h3>Personalized Support (ML)</h3>
                    <p>**Machine Learning (ML)** models analyze user language, tone, and engagement patterns to adapt responses and tailor coping exercises.</p>
                </div>

                <div class="feature-card">
                    <h3>Generative Activities (GenAI)</h3>
                    <p>**Generative AI** designs custom journaling prompts, guided meditations, or self-reflection tasks based on the specific emotions discussed.</p>
                </div>
            </div>
        </section>

        <section id="ethics">
            <h2>🔒 Ethical Commitment & Privacy</h2>
            <p>Mental health data is highly sensitive. Our commitment to user trust is paramount:</p>
            <ul>
                <li>**End-to-End Encryption:** All user conversations are secured with E2EE.</li>
                <li>**Anonymity:** All data used for training the AI model is strictly **anonymized**.</li>
                <li>**Transparent Policy:** Data is **never shared with third parties for advertising.**</li>
            </ul>
        </section>

        <section id="roadmap">
            <h2>🗺️ Implementation Roadmap</h2>
            <ul class="roadmap-list">
                <li><strong>Phase 1: Research & Prototyping</strong> — Conversational flow design based on CBT/DBT frameworks.</li>
                <li><strong>Phase 2: Core Application Development</strong> — Secure data handling and full ML/NLP model integration.</li>
                <li><strong>Phase 3: Closed Beta Testing</strong> — Collaboration with clinical advisors and detailed feedback cycles.</li>
                <li><strong>Phase 4: Official Launch</strong> — Full-scale launch on **iOS & Android** stores.</li>
            </ul>
        </section>

    </div>
    
</body>
</html>
