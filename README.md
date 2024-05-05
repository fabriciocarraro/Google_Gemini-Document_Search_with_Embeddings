# Google Gemini - Document Search with Embeddings

This GitHub repository contains a Google Colab notebook that showcases the integration and use of Google's generative AI library, google-generativeai, within a Colab environment. The notebook demonstrates various operations such as model listing, embedding generation, and retrieval-based document search using the Google AI models.

## Features
1. Model Exploration:
- The notebook includes code to list all available models from the library that support the embedding content generation method, providing insights into the specific models you can work with.
2. Embedding Content:
- Demonstrates how to generate embeddings for a given piece of text using a specific model. This is crucial for tasks like document retrieval, where the semantic understanding of content is necessary.
3. Document Retrieval:
- Implements a document retrieval system where documents are represented by their embeddings. A search query is embedded, and the notebook retrieves the document most similar to the query from a predefined list, using the cosine similarity between embeddings.
4. Interactive Search Example:
- The notebook allows for interactive testing with an example query about traveling to Europe, showcasing how the document retrieval system can be utilized in practical scenarios.
5. Content Generation:
- In addition to retrieval, the notebook also demonstrates content generation using a generative model to rewrite text in a casual style, showing the flexibility of Google's generative AI models in handling various text transformation tasks.
