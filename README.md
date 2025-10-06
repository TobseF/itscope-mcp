# <img src=".idea/icon.svg" width="36"/> ITscope MCP AI agent

[![Java-21](https://img.shields.io/badge/Java-21-red.svg?style=flat&logo=Java&logoColor=white)](https://jdk.java.net/21/)
[![Kotlin](https://img.shields.io/badge/Kotlin-2.2.20-7F52FF.svg?style=flat&logo=Kotlin&logoColor=white)](https://kotlinlang.org/docs/whatsnew17.html)
[![Spring](https://img.shields.io/badge/Spring-6.2.1-6DB33F.svg?style=flat&logo=SpringBoot&logoColor=white)](https://spring.io/projects/spring-boot)

> 🖐️ **Disclaimer**  
> This is a part-time project and not an official ITscope product.  
> The current state is a work in progress.

Provides an AI chatbot for the [ITscope](https://www.itscope.com) platform.

### 🛠️ Setup

Add the following spring properties to [application.properties](src/main/resources/application.properties):
* `ai.koog.google.api-key`: OpenAI Api Key ([API key page](https://platform.openai.com/api-keys))
* `de.itscope.api.account.id`: ITscope Account ID ([Persönlicher ITscope API Zugang](https://guide.itscope.com/kb/authentifizierung-ueber-api-zugangsdaten/))
* `de.itscope.api.key`: ITscope API-Key ([Persönlicher ITscope API Zugang](https://guide.itscope.com/kb/authentifizierung-ueber-api-zugangsdaten/))

### 🚀 Start

Run the class `de.itscope.ai.mcp.ITscopeMcpApplication` in your IDE.  
Alternatively, you can also run the application using Gradle:
```shell
gradle bootRun
```