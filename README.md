# Embedbase Nextra Template

This is a template for creating a **ChatGPT-powered QA documentation** with [Nextra](https://nextra.site)  thanks to [Embedbase](https://embedbase.xyz) and [OpenAI](https://openai.com).


## How it works

* we index `.mdx` files with [Embedbase](https://github.com/another-ai/embedbase)
* when you search, we use semantic search with [Embedbase](https://github.com/another-ai/embedbase) to find the most relevant snippets
* we then ask GPT-3 to give a summary of the snippets


![ezgif com-video-to-gif (1)](https://user-images.githubusercontent.com/11430621/220747631-f69cf532-e464-4ec1-ac04-75018f77d561.gif)


[**Live Demo →**](https://embedbase-nextra-docs-template.vercel.app/)

[![](.github/screenshot.png)](https://embedbase-nextra-docs-template.vercel.app/)

## Quick Start

Click the button to clone this repository and deploy it on Vercel:

[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2Fanother-ai%2Fchat-gpt-powered-nextra&env=EMBEDBASE_API_KEY,OPENAI_API_KEY&envDescription=Get%20your%20API%20key%20on%20Embedbase%20website%20at%20https%3A%2F%2Fapp.embedbase.xyz%20and%20your%20OpenAI%20key%20at%20https%3A%2F%2Fplatform.openai.com%2Faccount%2Fapi-keys)

Remember to add `EMBEDBASE_API_KEY` to your [repository secrets](https://docs.github.com/en/rest/actions/secrets) to automatically sync your documentation to [Embedbase](https://embedbase.xyz) on push.

## Local Development

First, run `pnpm i` to install the dependencies.

Then, run `pnpm dev` to start the development server and visit localhost:3000.

## License

This project is licensed under the MIT License.
