# Clase 02 — Agente RAG con Mistral

## Descripción
Bot que responde preguntas sobre datos de ventas usando 
LangChain + Mistral Small + ChromaDB como base vectorial.

## Estado actual
- [x] Normalización del dataset (4 tablas limpias)
- [x] Conexión con Mistral Small via API
- [x] Agente con LangChain funcionando
- [x] System prompt restrictivo (solo responde sobre ventas)
- [ ] RAG con ChromaDB (en progreso, problemas de conexión en Colab)

## Archivos
- `01_normalizacion.ipynb` → limpieza y normalización del dataset
- `02_agente_rag.ipynb` → agente con Mistral + RAG en desarrollo

## Stack
- Python 3.12
- LangChain 1.2.15
- Mistral Small (mistral-small-latest)
- ChromaDB
- Google Colab
