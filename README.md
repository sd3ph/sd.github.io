<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AADRI White Paper - Intelligent Conversational AI for Academic Profiles</title>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&family=Crimson+Pro:wght@400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            line-height: 1.8;
            color: #4a5568;
            background: #f7fafc;
            padding: 40px 20px;
            font-size: 15px;
            font-weight: 400;
        }
        
        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #ffffff;
            box-shadow: 0 1px 3px rgba(0,0,0,0.06), 0 1px 2px rgba(0,0,0,0.08);
            padding: 80px 90px;
        }
        
        header {
            margin-bottom: 60px;
            padding-bottom: 40px;
            border-bottom: 1px solid #e2e8f0;
        }
        
        .logo-area {
            text-align: center;
            margin-bottom: 50px;
        }
        
        h1 {
            font-family: 'Crimson Pro', serif;
            font-size: 3em;
            color: #1a202c;
            margin-bottom: 16px;
            font-weight: 600;
            letter-spacing: -0.5px;
        }
        
        .subtitle {
            font-size: 1.15em;
            color: #718096;
            margin-top: 12px;
            font-weight: 400;
            line-height: 1.6;
        }
        
        .meta {
            display: flex;
            justify-content: center;
            gap: 30px;
            color: #a0aec0;
            font-size: 0.9em;
            margin-top: 30px;
            font-weight: 500;
        }
        
        .meta-item {
            display: flex;
            align-items: center;
            gap: 8px;
        }
        
        .abstract {
            background: #f7fafc;
            padding: 40px;
            margin: 50px 0;
            border-left: 3px solid #1a202c;
        }
        
        .abstract h2 {
            font-family: 'Crimson Pro', serif;
            font-size: 1.3em;
            color: #1a202c;
            margin-bottom: 20px;
            font-weight: 600;
            letter-spacing: -0.3px;
        }
        
        .abstract p {
            color: #4a5568;
            font-size: 0.98em;
            line-height: 1.9;
        }
        
        section {
            margin: 50px 0;
        }
        
        h2 {
            font-family: 'Crimson Pro', serif;
            color: #1a202c;
            font-size: 1.85em;
            margin-bottom: 25px;
            font-weight: 600;
            letter-spacing: -0.4px;
            margin-top: 60px;
        }
        
        h2:first-of-type {
            margin-top: 0;
        }
        
        h3 {
            font-family: 'Inter', sans-serif;
            color: #2d3748;
            font-size: 1.1em;
            margin-top: 35px;
            margin-bottom: 18px;
            font-weight: 600;
            letter-spacing: -0.2px;
        }
        
        p {
            margin-bottom: 18px;
            color: #4a5568;
            line-height: 1.85;
            text-align: left;
        }
        
        .callout {
            padding: 25px 30px;
            margin: 30px 0;
            border-radius: 4px;
        }
        
        .problem {
            background: #fffbeb;
            border-left: 3px solid #f59e0b;
        }
        
        .solution {
            background: #f0fdf4;
            border-left: 3px solid #10b981;
        }
        
        .callout strong {
            display: block;
            font-weight: 600;
            color: #1a202c;
            margin-bottom: 10px;
            font-size: 0.95em;
        }
        
        .callout p {
            margin: 0;
            color: #4a5568;
        }
        
        ul {
            margin: 20px 0;
            padding-left: 0;
            list-style: none;
        }
        
        li {
            margin-bottom: 16px;
            padding-left: 24px;
            position: relative;
            color: #4a5568;
            line-height: 1.8;
        }
        
        li:before {
            content: "•";
            position: absolute;
            left: 6px;
            color: #cbd5e0;
            font-weight: bold;
        }
        
        li strong {
            color: #2d3748;
            font-weight: 600;
        }
        
        ul ul {
            margin-top: 12px;
            margin-bottom: 12px;
        }
        
        ul ul li {
            font-size: 0.96em;
            margin-bottom: 10px;
        }
        
        .team-section {
            background: #f7fafc;
            padding: 45px;
            margin-top: 70px;
            border-radius: 4px;
            border: 1px solid #e2e8f0;
        }
        
        .team-section h2 {
            margin-top: 0;
            margin-bottom: 35px;
        }
        
        .team-role {
            margin: 28px 0;
        }
        
        .team-role strong {
            color: #2d3748;
            display: block;
            margin-bottom: 12px;
            font-weight: 600;
            font-size: 0.95em;
        }
        
        .team-role p {
            color: #4a5568;
            margin: 0;
            line-height: 1.75;
        }
        
        footer {
            text-align: center;
            margin-top: 70px;
            padding-top: 40px;
            border-top: 1px solid #e2e8f0;
            color: #a0aec0;
            font-size: 0.88em;
        }
        
        .section-number {
            color: #cbd5e0;
            font-weight: 600;
            margin-right: 8px;
        }
        
        @media print {
            body {
                background: white;
                padding: 0;
            }
            .container {
                box-shadow: none;
                padding: 60px;
            }
        }
        
        @media (max-width: 768px) {
            .container {
                padding: 40px 30px;
            }
            h1 {
                font-size: 2.2em;
            }
            h2 {
                font-size: 1.6em;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <header>
            <div class="logo-area">
                <h1>AADRI</h1>
                <p class="subtitle">An Intelligent Conversational AI for Academic Profiles</p>
                <div class="meta">
                    <div class="meta-item">
                        <span>Version 2.0</span>
                    </div>
                    <div class="meta-item">
                        <span>October 14, 2025</span>
                    </div>
                </div>
            </div>
        </header>

        <div class="abstract">
            <h2>Executive Summary</h2>
            <p>In the academic and professional world, the dissemination of information about a researcher's work is traditionally limited to static documents like curriculum vitae and personal websites. These formats, while comprehensive, lack interactivity and can be cumbersome for users seeking specific information. This white paper details the design, architecture, and features of Aadri, a virtual chatbot assistant developed to address this challenge. Aadri leverages a Retrieval-Augmented Generation (RAG) architecture powered by the Google Gemini API to provide a dynamic, conversational, and context-aware interface to a scientific professional profile. The system is designed not only to answer questions accurately based on a grounded knowledge base but also to engage users through a sophisticated, persona-driven interaction model, setting up a new standard for professional self-presentation.</p>
        </div>
        <section>
            <h2><span class="section-number">01</span> Introduction</h2>
            <p>The modern academic landscape requires researchers to communicate their work effectively to a diverse audience, including prospective students, potential collaborators, research institutions, and industry partners. The traditional CV, while a staple of academic life, is a one-way communication tool. It presents information in a linear, non-interactive format, forcing the reader to manually parse dense text to find relevant details.</p>
            
            <div class="callout problem">
                <strong>The Challenge</strong>
                <p>How can a researcher present their extensive body of work—including publications, research interests, teaching experience, and professional activities—in a way that is engaging, accessible, and tailored to the individual user's query?</p>
            </div>
            
            <div class="callout solution">
                <strong>The Solution</strong>
                <p>Aadri, a bespoke conversational AI assistant. Aadri transforms the test user profile's (Dr. Suman Dutta) static professional profile into an interactive dialogue. By simply asking questions in natural language, users can explore his work in depth, receive contextually relevant information, and have a more personal and efficient experience.</p>
            </div>
        </section>

        <section>
            <h2><span class="section-number">02</span> Technical Architecture</h2>
            <p>Aadri is built on a modern web stack, combining a responsive frontend with a powerful AI backend. The core of its intelligence lies in the RAG architecture, which ensures that all responses are grounded in factual data.</p>
            
            <h3>Frontend Infrastructure</h3>
            <ul>
                <li><strong>Framework:</strong> React with TypeScript, providing a robust, type-safe foundation for the user interface.</li>
                <li><strong>Styling:</strong> Tailwind CSS is used for a utility-first approach to create a clean, modern, and fully responsive design that works seamlessly across all devices.</li>
                <li><strong>UI Components:</strong> The interface is modular, with distinct components for the user preamble, the chat interface, and modals for end-of-chat actions, ensuring a clean separation of concerns.</li>
            </ul>
            
            <h3>AI Backend & Logic</h3>
            <ul>
                <li><strong>Language Model:</strong> The application utilizes Google's gemini-2.5-flash model via the @google/genai SDK. This model is chosen for its strong balance of performance, reasoning capabilities, and support for streaming responses.</li>
                <li><strong>Retrieval-Augmented Generation (RAG):</strong> Instead of relying solely on the model's pre-trained knowledge, Aadri uses a RAG approach. The entire professional profile of Dr. Dutta is stored in a KNOWLEDGE_BASE_TEXT constant. This text is passed to the Gemini API as part of a detailed systemInstruction, effectively "grounding" the model and compelling it to answer questions based only on this provided context. This prevents hallucination and ensures the accuracy of the information provided.</li>
                <li><strong>Prompt Engineering:</strong> The systemInstruction is meticulously crafted to define Aadri's persona, its conversational rules, and its special content generation capabilities. This is the cornerstone of the chatbot's unique and sophisticated behavior.</li>
            </ul>
        </section>

        <section>
            <h2><span class="section-number">03</span> Key Features and Innovations</h2>
            <p>Aadri's design goes beyond a simple question-and-answer bot. It incorporates several innovative features to create a rich and human-like user experience.</p>
            
            <ul>
                <li><strong>Context-Aware Conversational Memory:</strong> The entire chat history is sent with each new user query. This enables Aadri to understand follow-up questions, resolve pronoun references (e.g., "tell me more about that paper"), and maintain a coherent, multi-turn conversation.</li>
                
                <li><strong>Persona-Driven, Creative Responses:</strong> The system prompt instructs Aadri to be "helpful, professional, highly articulate, and conversational." More importantly, for key queries like "what are your research interests?", it is explicitly forbidden from listing bullet points. Instead, it must synthesize the information into a unique, eloquent, and compelling narrative each time, showcasing advanced creative generation.</li>
                
                <li><strong>Controlled Information Disclosure:</strong> For list-based queries (e.g., publications, work experience), Aadri employs a step-by-step interaction model. It presents only the first item and asks the user if they wish to proceed, preventing information overload and making the dialogue more interactive.</li>
                
                <li><strong>Multimodal User Input:</strong> The application integrates the browser's Web Speech API, allowing users to ask questions via voice. This enhances accessibility and provides a more natural interaction method.</li>
                
                <li><strong>Engaging User Experience:</strong> The platform includes personalized welcome forms, streaming responses with typing indicators, suggestive questions to guide new users, comprehensive chat export and feedback mechanisms, and graceful error handling that ensures the system never fabricates answers when information is unavailable.</li>
            </ul>
        </section>

        <section>
            <h2><span class="section-number">04</span> Benefits and Impact</h2>
            
            <ul>
                <li><strong>For Potential Visitors:</strong> Provides a highly efficient and engaging way to find specific information about Dr. Dutta's work without needing to read a lengthy document. The natural language interface makes complex academic information more accessible.</li>
                
                <li><strong>For the Researcher:</strong> Serves as an innovative digital business card that actively engages visitors. It automates responses to frequently asked questions and can capture contact details and feedback from potential collaborators or students.</li>
                
                <li><strong>For the Academic Community:</strong> Presents a forward-thinking model for how researchers can leverage AI to communicate their work more effectively and broadly.</li>
            </ul>
        </section>

        <section>
            <h2><span class="section-number">05</span> Future Roadmap</h2>
            <p>While Aadri 2.0 is a robust and feature-rich application, there are several avenues for future enhancement:</p>
            <ul>
                <li><strong>Dynamic Knowledge Base:</strong> Transitioning from a static text file to a vector database. This would allow for automatic ingestion of new publications from sources like arXiv or Google Scholar, ensuring the knowledge base is always up to date.</li>
                
                <li><strong>Advanced Function Calling:</strong> Integrating external APIs to fetch real-time data, such as live citation counts, direct links to full-text articles, or university course catalogs.</li>
                
                <li><strong>True Multimodality:</strong> Expanding beyond text and voice to include generating diagrams, charts, or simplified animations to explain complex scientific concepts mentioned in the research.</li>
            </ul>
        </section>

        <section>
            <h2><span class="section-number">06</span> Conclusion</h2>
            <p>Aadri is more than a chatbot; it is a proof-of-concept for the future of professional and academic communication. By combining the power of the Google Gemini API with a thoughtfully designed RAG architecture and a user-centric interface, it creates a conversational experience that is intelligent, reliable, and deeply engaging. It successfully bridges the gap between static data and dynamic user interaction, providing a powerful tool for any professional looking to present their work in the age of AI.</p>
        </section>

        <div class="team-section">
            <h2>Project Team</h2>
            
            <div class="team-role">
                <strong>Conception & Development</strong>
                <p>S Dutta [School of AI, Amrita Vishwa Vidyapeetham]</p>
            </div>
            
            <div class="team-role">
                <strong>Quality Testing Team</strong>
                <p>Selva Vignesh V, Rithvik K, Raghuraman V, Madhan S, Anirudh, Vipin S, N Manoj Kumar, Harshith KV, KCS Reddy, V Ashwin Krishna, R Gagan Chowdary, BLHS Reddy, M Sharma, A Sheshank Royal, Dhruv, CSH Reddy, M. Venkat, B. Jayan, K. Bhanuprakash, Nethaaji S, Kanish Visyanth C, K Adarsh, JK Kavipranidan, Danush M, Gurucharan, Revanth S, Athul V RR, B Surya Charan Tej, Abinav, Kirithik B, KVSP Praneeth, Kamalesh, Sidharth M, S. Sujitkumar, M. Hemanth Kumar, V Amruth Chowdary [Students of BTech AID (Core), School of AI, Amrita Vishwa Vidyapeetham]</p>
            </div>
            
            <div class="team-role">
                <strong>Consultants & Review</strong>
                <p>AMP Biswas [Tata Consultancy Services], A. Dutta [Cognizant Technology Solutions], S. Das [University of Luxembourg]</p>
            </div>
        </div>

        <footer>
            <p>© 2025 AADRI Project · School of AI, Amrita Vishwa Vidyapeetham</p>
        </footer>
    </div>
</body>
</html>
