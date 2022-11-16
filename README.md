# Full-Stack Authentication with Vue.js, Spring Boot, and Spring Security

I have been building a lot of tutorials on how to get started with Spring Security. In almost all of these tutorials, I have focused on the backend with Spring Boot and Spring Security.

- [Spring Security JWT](https://youtu.be/KYNR5js2cXE)
- [Spring Security JWT - Username & Password](https://youtu.be/UaB-0e76LdQ)
- [Spring Security CORS](https://youtu.be/HRwlT_etr60)
- [Spring Security JDBC](https://youtu.be/d7ZmZFbE_qY)

I have not really talked about the frontend. In this tutorial, I will show you how to build a full-stack application with Spring Boot, Spring Security, and Vue.js. The same concepts would apply no matter what frontend framework you are using.

If you're interested in the video version of this tutorial, [reach out](https://twitter.com/therealdanvega) and let me know!

## Getting Started

You should be familiar with the following technologies:

- Backend:
  - [Spring Boot](https://spring.io/projects/spring-boot)
  - [Java 17](https://openjdk.org/projects/jdk/17/)
  - [Spring Web](https://docs.spring.io/spring-framework/docs/current/reference/html/web.html#spring-web)
  - [Spring Security](https://spring.io/projects/spring-security)
- Frontend:
  - [Vue 3](https://vuejs.org/)
  - [Vite](https://vitejs.dev/)
  - [TypeScript](https://www.typescriptlang.org/)
  - [Pinia](https://pinia.vuejs.org/)
  - [Vue Router](https://router.vuejs.org/)
  - [Tailwind CSS](https://tailwindcss.com/)

### Prerequisites

- [Node.js](https://nodejs.org/) version 16.0 or higher
- [Java 17](https://openjdk.org/projects/jdk/17/) or higher

### Running the application

To run the application, you need to start the backend and the frontend. You can do this by running each application in a separate terminal.

```bash
cd frontend
npm install
npm run dev
```

```bash
cd backend
./mvnw spring-boot:run
```

You can run both applications at once by using the script `run.sh` in the root directory.
