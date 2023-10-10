# MathFlow

Aplicación web creada con el fin de proporcionar resultados y sus respectivos procesos para diferentes métodos numéricos.

## Client

EL front fue desarrollado sobre vite.

    npm run dev

## Server

El server fue creado en fastAPI, con un entorno virtual montado en conda con uvicorn.

    conda create --name mathflow-api python=3
    conda activate mathflow-api
    uvicorn app:app
