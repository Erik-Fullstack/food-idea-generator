# Food Recipe Generator with AI

A modern web application that combines AI-powered recipe generation with semantic search capabilities. This project demonstrates the use of multiple AI technologies including LLMs for recipe generation and vector embeddings for intelligent recipe search.

## 🚀 Features

### Frontend (React + TypeScript)
- **Recipe Generation**: Generate custom recipes based on available ingredients using AI
- **Recipe Management**: Save, view, and organize your favorite recipes
- **Semantic Search**: Find recipes using natural language queries
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Modern UI**: Built with shadcn/ui components and Tailwind CSS

### Backend (Python + FastAPI)
- **RESTful API**: Complete CRUD operations for recipe management
- **Semantic Search**: AI-powered recipe search using sentence transformers
- **Vector Embeddings**: Automatic embedding generation for semantic similarity
- **PostgreSQL Database**: Robust data storage with JSON support
- **Docker Support**: Easy deployment with containerization

## 🧠 AI Technologies Used

1. **Large Language Models (LLMs)**: For generating creative and contextual recipes
2. **Sentence Transformers**: For semantic search using the `all-MiniLM-L6-v2` model
3. **Vector Embeddings**: For similarity-based recipe recommendations
4. **Natural Language Processing**: For understanding search queries and recipe content

Ta chansen och påbörja arbetet på ett projekt ni varit sugna på att göra länge! Fokus ligger inte endast på att få allting att fungera utan snarare att utforska och se, var går det fel och vad är svårt med AI?

Instruktioner
Skapa en webb-applikation inom valfritt ramverk (React, Next, Vite). Tips är att välja ett "stort" språk för att underlätta utveckling med AI. Applikationen ska innehålla minst en AI-komponent som fyller en tydlig funktion i applikationen (chattbot, bildgenerering, sökning etc.)

Tips:

Innan ni sätter igång och kodar - sätt upp en tydlig plan, gör research, välj ramverk med omsorg, planera applikationen.
Bedömning
Krav för Godkänt
Applikationen använder en LLM eller annan AI-teknik (bildgenereringsmodeller, ljudgenereringsmodeller, semantisk sökning med embeddings)

Applikationen ska helt (eller delvis) utvecklas med stöd av AI (Github CoPilot, Gemini CLI, Cursor, ChatGPT)

Applikationen ska vara väldokumenterad/välkommenterad (visa på förståelse för koden) och arbetet med den kan användas som underlag till era skriftliga inlämningar (uppgift 1).

I readme.md ska även en reflektion över följande vara med:

Vilken ny AI-teknik/bibliotek identifierade ni och hur tillämpade ni det?
Motivera varför ni valde den AI-tekniken/det biblioteket.
Varför behövdes AI-komponenten? Skulle ni kunna löst det på ett annat sätt?
Vidareutveckling för Väl Godkänt
Visat på stor säkerhet och skicklighet i sin identifikation och tillämpning av AI-komponenten
Ex. använt de mer avancerade tekniker vi gått igenom, hittat egna bibliotek eller på annat sätt fördjupat sig.
Visat på stor säkerhet och skicklighet i sitt avgörande kring om AI var en lämplig lösning
Inlämning
Ett github repo med fullständig kod samt readme.md som innehåller svar på de reflekterande frågorna ovan.
Kodinlämning i Canvas med länk till git repository (t.ex. GitHub)
Inlämning senast måndag den 20e oktober kl. 23:59
Kursmål som uppfylls (7-8) enligt kursplan
Självständigt identifiera och tillämpa ny AI-teknik eller bibliotek i syfte att lösa programmeringsproblem. Analysera en teknisk problemställning och avgöra när AI är en lämplig lösning och när det inte är det. Både i utvecklandet av applikationen samt i applikationen självt.

Förslag på applikationer
Embeddings

Anteckningssök: Sök i egna anteckningar med embeddings (Supabase). Rekommendationslista: Hitta liknande filmer/böcker/produkter via embeddings.

LLMs

FAQ-bot: Använd en LLM för att svara på frågor (med eller utan embeddings). (Reflektera över hallucinationer och behovet av egen data.) Idégenerator: En liten webapp där man kan få förslag (t.ex. middagsidéer, träningspass, reserutter). (Reflektera över kvalitet, bias och kostnader.) Text-till-text filter: Låt en användare mata in text och få en omskriven version (t.ex. mer formell, kortare, på annan stil). (Diskutera när AI är värdefullt vs. vanlig regex/replace.)

Andra AI-API:er

Bild- eller ljudgenerator: Bygg ett litet gränssnitt där man skickar promptar till ett API som returnerar en bild eller ljud. (Reflektera kring kontroll, begränsningar, upphovsrätt?.)

MEN! - Dessa är bara förslag! Låt fantasin flöda - använd AI för att hjälpa er med idé -> planering -> utförande.