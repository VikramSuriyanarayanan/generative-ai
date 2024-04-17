See: https://github.com/VikramSuriyanarayanan/generative-ai/blob/main/gemini/getting-started/intro_gemini_python.ipynb to get started. 

# Generative AI

Welcome to the Google Cloud [Generative AI](https://cloud.google.com/ai/generative-ai) repository.

<a href="gemini"><img src="https://lh3.googleusercontent.com/eDr6pYKs1tT0iK0nt3pPhvVlP2Wn96fbGqbWgBAARRZ7isej037g_tWobjV8zQkxOsWzJuEH8p-fksczXUOeqxGZZIo_HUCdkn8q-a4fuwATD7Q9Xrs=w2456-l100-sg-rj-c0xffffff" style="width:35em"></a>

This repository contains notebooks, code samples, sample apps, and other resources that demonstrate how to use, develop and manage generative AI workflows using [Generative AI on Google Cloud](https://cloud.google.com/ai/generative-ai), powered by [Vertex AI](https://cloud.google.com/vertex-ai).

For more Vertex AI samples, please visit the [Vertex AI samples Github repository](https://github.com/GoogleCloudPlatform/vertex-ai-samples/).

## Using this repository

[![Applied AI Summit: The cloud toolkit for generative AI](https://img.youtube.com/vi/xT7WW2SKLfE/hqdefault.jpg)](https://www.youtube.com/watch?v=xT7WW2SKLfE)

<!-- markdownlint-disable MD033 -->
<table>

  <tr>
    <th></th>
    <th style="text-align: center;">Description</th>
    <th style="text-align: center;">Contents</th>
  </tr>
    <tr>
    <td>
      <img src="https://storage.googleapis.com/github-repo/img/gemini/Spark__Gradient_Alpha_100px.gif" width="45px">
      <br>
      <a href="gemini/"><code>gemini/</code></a>
    </td>
    <td>
      Discover Gemini through starter notebooks, use cases, function calling, sample apps, and more.
    </td>
    <td><a href="gemini/">Sample notebooks, apps, use cases</a></td>
  </tr>
  <tr>
    <td>
      <img src="https://www.gstatic.com/images/branding/gcpiconscolors/service_discovery/v1/24px.svg" width="40px">
      <br>
      <a href="search/"><code>search/</code></a>
    </td>
    <td>Use this folder if you're interested in using <a href="https://cloud.google.com/enterprise-search">Vertex AI Search</a>, a Google-managed solution to help you rapidly build search engines for websites and across enterprise data. (Formerly known as Enterprise Search on Generative AI App Builder)</td>
    <td><a href="search">Sample apps, use cases</a></td>
  </tr>
  <tr>
    <td>
      <img src="https://www.gstatic.com/images/branding/gcpiconscolors/dialogflow_cx/v1/24px.svg" width="40px">
      <br>
      <a href="conversation/"><code>conversation/</code></a>
    </td>
    <td>Use this folder if you're interested in using <a href="https://cloud.google.com/generative-ai-app-builder">Vertex AI Conversation</a>, a Google-managed solution to help you rapidly build chat bots for websites and across enterprise data. (Formerly known as Chat Apps on Generative AI App Builder)</td>
    <td><a href="conversation">Sample apps, use cases</a></td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/edit_note/default/40px.svg">
      <br>
      <a href="language/"><code>language/</code></a>
    </td>
    <td>
      Use this folder if you're interested in building your own solutions from scratch using Google's language foundation models (Vertex AI PaLM API).
      <ul>
        <li><a href="https://cloud.google.com/vertex-ai/docs/generative-ai/language-model-overview#palm-api"><code>text-bison</code></a> model</li>
        <li><a href="https://cloud.google.com/vertex-ai/docs/generative-ai/language-model-overview#palm-api"><code>chat-bison</code></a> model</li>
        <li><a href="https://cloud.google.com/vertex-ai/docs/generative-ai/language-model-overview#palm-api"><code>textembedding-gecko</code></a> model</li>
        <li><a href="https://cloud.google.com/vertex-ai/docs/generative-ai/code/code-models-overview"><code>code-bison</code></a> model</li>
        <li><a href="https://cloud.google.com/vertex-ai/docs/generative-ai/code/code-models-overview"><code>code-gecko</code></a> model</li>
        <li><a href="https://cloud.google.com/vertex-ai/docs/generative-ai/code/code-models-overview"><code>codechat-bison</code></a> model</li>
        <li>prompt design</li>
        <li>deploying apps</li>
        <li>tuning models</li>
        <li>grounded responses</li>
        <li><a href="https://www.langchain.com/">langchain</a> with Google's foundation models</li>
      </ul>
    </td>
    <td><a href="language">Sample notebooks, apps, use cases</a></td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/image/default/40px.svg">
      <br>
      <a href="vision/"><code>vision/</code></a>
    </td>
    <td>
      Use this folder if you're interested in building your own solutions from scratch using features from Imagen on Vertex AI (Vertex AI Imagen API).
      These are the features that Imagen on Vertex AI offers:
      <ul>
        <li>Image generation</li>
        <li>Image editing</li>
        <li>Visual captioning</li>
        <li>Visual question answering</li>
      </ul>
    </td>
    <td><a href="vision/">Sample notebooks, apps, use cases</a></td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/mic/default/40px.svg">
      <br>
      <a href="speech/"><code>speech/</code></a>
    </td>
    <td>
      Use this folder if you're interested in building your own solutions from scratch using features from Chirp, a version of Google's Universal Speech Model (USM) on Vertex AI (Vertex AI Chirp API).
    </td>
    <td><a href="speech/">Sample notebooks, apps, use cases</a></td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/build/default/40px.svg">
      <br>
      <a href="setup-env/"><code>setup-env/</code></a>
    </td>
    <td>Instructions on how to set up Google Cloud, the Vertex AI Python SDK, and notebook environments on Google Colab and Vertex AI Workbench.</td>
    <td><a href="setup-env">Setup instructions</a></td>
  </tr>
  <tr>
    <td>
      <img src="https://fonts.gstatic.com/s/i/short-term/release/googlesymbols/media_link/default/40px.svg">
      <br>
      <a href="RESOURCES.md"><code>RESOURCES.md</code></a>
    </td>
    <td>Learning resources (e.g. blogs, Youtube playlists) about Generative AI on Google Cloud</td>
    <td><a href="RESOURCES.md">Resources (e.g. videos, blogposts, learning paths)</a></td>
  </tr>
</table>
<!-- markdownlint-enable MD033 -->

## Related Repositories

- [Google Cloud Applied AI Engineering](https://github.com/GoogleCloudPlatform/applied-ai-engineering-samples)
- [Generative AI for Marketing using Google Cloud](https://github.com/GoogleCloudPlatform/genai-for-marketing)
- [Generative AI for Developer Productivity](https://github.com/GoogleCloudPlatform/genai-for-developers)
- Vertex AI Core
  - [Vertex AI Samples](https://github.com/GoogleCloudPlatform/vertex-ai-samples)
  - [MLOps with Vertex AI](https://github.com/GoogleCloudPlatform/mlops-with-vertex-ai)
  - [Developing NLP solutions with T5X and Vertex AI](https://github.com/GoogleCloudPlatform/t5x-on-vertex-ai)
  - [AlphaFold batch inference with Vertex AI Pipelines](https://github.com/GoogleCloudPlatform/vertex-ai-alphafold-inference-pipeline)
  - [Serving Spark ML models using Vertex AI](https://github.com/GoogleCloudPlatform/vertex-ai-spark-ml-serving)
  - [Sensitive Data Protection (Cloud DLP) for Vertex AI Generative Models (PaLM2)](https://github.com/GoogleCloudPlatform/Sensitive-Data-Protection-for-Vertex-AI-PaLM2)
- Conversational AI
  - [Contact Center AI Samples](https://github.com/GoogleCloudPlatform/contact-center-ai-samples)
  - [Reimagining Customer Experience 360](https://github.com/GoogleCloudPlatform/dialogflow-ccai-omnichannel)
- Document AI
  - [Document AI Samples](https://github.com/GoogleCloudPlatform/document-ai-samples)
- Duet AI
  - [Cymbal Superstore](https://github.com/GoogleCloudPlatform/cymbal-superstore)
- Cloud Databases
  - [GenAI Databases Retrieval App](https://github.com/GoogleCloudPlatform/genai-databases-retrieval-app)
- Other
  - [ai-on-gke](https://github.com/GoogleCloudPlatform/ai-on-gke)
  - [ai-infra-cluster-provisioning](https://github.com/GoogleCloudPlatform/ai-infra-cluster-provisioning)
  - [solutions-genai-llm-workshop](https://github.com/GoogleCloudPlatform/solutions-genai-llm-workshop)
  - [terraform-genai-doc-summarization](https://github.com/GoogleCloudPlatform/terraform-genai-doc-summarization)
  - [terraform-genai-knowledge-base](https://github.com/GoogleCloudPlatform/terraform-genai-knowledge-base)
  - [genai-product-catalog](https://github.com/GoogleCloudPlatform/genai-product-catalog)
  - [solutionbuilder-terraform-genai-doc-summarization](https://github.com/GoogleCloudPlatform/solutionbuilder-terraform-genai-doc-summarization)
  - [solutions-viai-edge-provisioning-configuration](https://github.com/GoogleCloudPlatform/solutions-viai-edge-provisioning-configuration)
  - [mis-ai-accelerator](https://github.com/GoogleCloudPlatform/mis-ai-accelerator)
  - [dataflow-opinion-analysis](https://github.com/GoogleCloudPlatform/dataflow-opinion-analysis)

## Contributing

Contributions welcome! See the [Contributing Guide](https://github.com/GoogleCloudPlatform/generative-ai/blob/main/CONTRIBUTING.md).

## Getting help

Please use the [issues page](https://github.com/GoogleCloudPlatform/generative-ai/issues) to provide suggestions, feedback or submit a bug report.

## Disclaimer

This repository itself is not an officially supported Google product. The code in this repository is for demonstrative purposes only.
