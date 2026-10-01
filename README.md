# 10_AI_code

En chatbot-app bygget med Expo, `react-native-gifted-chat` og OpenAI's API. På forsiden vælger du en af fem chatbot-figurer, og i chatten svarer en AI-tutor, der er sat op til at hjælpe med forretningsmodel-teori (Chesbrough).

## Kør appen lokalt

1. Installer dependencies:
   ```
   npm install
   ```
2. Opret en `.env`-fil i projektets rod med din egen OpenAI API-nøgle:
   ```
   OPENAI_API_KEY=din-egen-nøgle-her
   ```
   `.env` er allerede i `.gitignore`, så nøglen bliver ikke committet.
3. Start Expo:
   ```
   npx expo start
   ```
