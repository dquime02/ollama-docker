# ollama-docker

Docker compose para levantar `Ollama` en un entorno docker junto a la base de datos vectorial `Qdrant` y `Open WebUI` para
la interfaz de chat de Ollama.

## Levantar contenedores

```bash
docker compose up -d
```

### Detener y eliminar contenedores

```bash
docker compose down
```

> Nota: no elimina los volúmenes. Para eliminar contenedores con volúmenes el comando es: `docker compose down -v`

## Descargar modelos

Comando para descargar modelos:

```bash
docker exec ollama ollama pull codellama
```
