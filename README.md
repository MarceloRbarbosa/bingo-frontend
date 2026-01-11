Frontend do sistema **Bingo Driven**, interface do bingo e interação com a API.

 
## Deploy 

**Aplicação em produção (Vercel)**
```
https://bingo-frontend-six.vercel.app/
``` 

## STACK
<ul>
  <li>Frontend Web</li>
  <li>React</li>
  <li>JavaScript</li>
  <li>Vercel</li>
  <li>Github Actions</li>
</ul>

## Variáveis de ambiente

Crie um arquivo .env com:
```
VITE_BACKEND=http://localhost:5000
```

## Executando sem Docker

```
npm install
npm run dev
``` 

## Executando com Docker
```
docker build -t bingo-frontend .
docker run -p 8080:80 --env-file bingo-frontend
```

## Executando com Docker Compose
```
docker compose up -d
```

## Testes 

```
npm run test:ci
```

## CD 

**CD**
<li>Build automático no VERCEL</li>
<li>Utilização de GitHub Actions</li>

