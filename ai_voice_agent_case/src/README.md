# LLM_STT_TTS

# Initialize Git
git init

# Install ffmpeg for processing audio files 
brew install ffmpeg

# Initialize NPM
npm init -y

# Install Core Dependencies
npm install express multer openai node-whisper fluent-ffmpeg dotenv
npm install -D typescript @types/node @types/express @types/multer @types/fluent-ffmpeg ts-node-dev


# Initialize TypeScript
npx tsc --init

# Production Build Part 
npm run build
npm start

# Run the project 
npm run dev
