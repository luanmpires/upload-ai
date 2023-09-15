<p align="center">
  
  
  <h1 align="center">Project NLW IA </h1>

 

Developed the video transcription project with AI and requests to OpenAI's AI, aiming at generating titles, descriptions, and other options.

</p>

## 🧭 Table of contents

- [🧭 Table of contents](#-table-of-contents)
<!-- - [🎥 Implementation Video](#-implementation-video) -->
- [👏 Learning and more Implementations](#-learning-and-more-implementations)
- [💡 Technologies Used](#-technologies-used)
  - [Back-end](#back-end)
  - [Front-end Web](#front-end-web)
- [📂 Folder Structure](#-folder-structure)
- [🚀 Running the Project](#-running-the-project)
  - [Back-end](#back-end-1)
  - [Front-end Web](#front-end-web-1)
<!-- - [🌎 License](#-license) -->
- [✒ Author](#-author)



## 👏 Learning and more Implementations

- Learned to use OpenAI's API.
- Learned to convert the video to MP3 using ffmpeg.wasm through the user's web browser.

## 💡 Technologies Used

### Back-end

- [x] Node.js
- [x] [Fastify](https://fastify.dev/)
- [x] [Prisma](https://www.prisma.io/client)
- [x] [TypeScript](https://www.typescriptlang.org/)
- [x] [fastify-multipart](https://github.com/fastify/fastify-multipart)
- [x] [Zod](https://zod.dev/)
- [x] [Openai](https://platform.openai.com/docs/api-reference)

### Front-end Web

- [x] [React](https://reactjs.org/)
- [x] [Vite](https://vitejs.dev/)
- [x] [TypeScript](https://www.typescriptlang.org/)
- [x] [Tawilndcss](https://tailwindcss.com/)
- [x] [RadixUi](https://www.radix-ui.com/primitives/docs/overview/introduction)
- [x] [Shadcn/ui](https://ui.shadcn.com/docs)
- [x] [Lucide React](https://lucide.dev/guide/packages/lucide-react)
- [x] [ffmpeg.wasm](https://ffmpegwasm.netlify.app/)
- [x] [Axios](https://axios-http.com/ptbr/)

## 📂 Folder Structure

```plainText
app
.
.
├── upload-ai-api               # Project Back-end
│   ├── src                       # Source files
│         ├── lib                   # Contains the connections
│         ├── routes                # Contains the routes
│         . server.ts               # Aplication entry
│   ├── tmp                       # MP3 files saved for transcription
│   . .env                        # Environment variables
│   . routes.http                 # Executing routes whit Rest Client
.
├── upload-ai-web               # Project Front-end Web
│   ├── src                       # Source files
│         ├── components            # Contains all global react components
│         ├── ffmpeg                # Contains ffmpeg files
│         ├── lib                   # Contains the connections
│         . main.tsx                # Aplication entry react
│   . index.html                  # Aplication entry
│
.
└── README.md
```

## 🚀 Running the Project

Clone the project

```bash
  git clone https://github.com/luanmpires/upload-ai.git
```

### Back-end

Enter the project directory

```bash
  cd upload-ai/api
```

Install with dependencies

```bash
  npm install
```

Create the file '.env' following the example in the '.env.example' file.

To create and obtain the OpenAI key, visit https://platform.openai.com/account/api-keys."

Create DB

```bash
  npx prisma migrate dev
```

Create data in the prompt table

```bash
  npx prisma db seed
```

Start the server

```bash
  npm run dev
```

### Front-end Web

Enter the project directory

```bash
  cd upload-ai/web
```

Install with dependencies

```bash
  npm install
```

Start the server

```bash
  npm run dev
```

<!-- ## 🌎 License

This project is under the MIT license. See the [LICENSE](https://github.com/luanmpires/nlw-ia-mastery-092023/blob/main/LICENSE) file for more details. -->

## ✒ Author

<p align="center">
  <img width="200px" alt="Luan Pires" title="Luan Pires" src="https://github.com/Luan Pires/default-readme/blob/main/assets/Luan Pires.svg" />

  <h3 align="center">Luan Pires</h3>
  
  <p align="center">  
    Made with love and hate 😅, get in touch!
  </p>
</p>  
  
<div align="center">

[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-1f6feb?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/luanmpires/)](https://www.linkedin.com/in/luanmpires/)
[![Gmail Badge](https://img.shields.io/badge/-luanmpires@gmail.com-1f6feb?style=flat-square&logo=Gmail&logoColor=white&link=mailto:luanmpires@gmail.com)](mailto:luanmpires@gmail.com)
[![GitHub Badge](https://img.shields.io/badge/-GitHub-1f6feb?style=flat-square&logo=GitHub&logoColor=white&link=https://github.com/luanmpires)](https://github.com/luanmpires)

</div>
