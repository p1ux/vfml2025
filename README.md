# AI Chatbot Projekt – Starter Repo

Dette repo er et skelet til jeres AI Chatbot-projekt.

## 🎯 Opgave
I skal bygge en chatbot i C# og Blazor baseret på et af de fire scenarier:

- Hotel/Booking-bot
- Support-bot
- Uddannelses-bot
- Butiks-bot

Chatbotten skal bygges trinvist gennem kurset:
1. **Dag 2**: Lav et arkitekturdiagram og beslut jer for jeres lagdeling (UI, logik, data).
2. **Dag 3–9**: Implementer funktionalitet trin for trin (NLP, regler, state machine, ML.NET, hukommelse, UI/UX, test & logging).
3. **Dag 10**: Fremlæg jeres chatbot.

## 📂 Struktur
- `Chatbot/` → backend-logik (intents, state, NLP, ML.NET).
- `BlazorUI/` → frontend i Blazor, hvor brugeren chatter med botten.
- `Data/` → dummy data eller databaseforbindelse.
- `Services/` → NLP, hukommelse, integration med ekstern AI.

## 🚀 Kom i gang
1. Installer [.NET SDK](https://dotnet.microsoft.com/en-us/download).
2. Åbn repo i VS Code eller Visual Studio.
3. Kør:
   ```bash
   dotnet build
   dotnet run --project Chatbot
   ```
4. Start BlazorUI med:
   ```bash
   dotnet run --project BlazorUI
   ```
5. Åbn browseren på `https://localhost:5001` (eller den port, der står i terminalen).

## 🧑‍💻 Opgave til Dag 2
- Tegn jeres arkitekturdiagram (fx i draw.io, Lucidchart, eller som ASCII i README).  
- Placér diagrammet i repo’et under `/Docs/ArchitectureDiagram.png`.  
- Beskriv i README hvilken type chatbot I bygger (Hotel, Support, Uddannelse, Butik).
