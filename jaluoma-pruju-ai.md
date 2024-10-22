# Pruju AI
Status: Demonstration

## Repository
https://github.com/jaluoma/pruju-ai

## About
> Pruju AI is a teaching assistant that allows students to interact with the teacher's course materials.

It is an Python based approach that leverages langchain for parts of it's LLM interactions. This allows for a wide range of tools to be incorporated easily, including some of the langchain monitoring systems, such as LangSmith.

Moodle course data is loaded via an ingestion script `moodle.py` that uses Moodle web services to fetch specified course content in to it's vector store (typically a Qdrant vector database).