# 🧠 Consultas Avançadas com MongoDB

Repositório com pipelines de agregação desenvolvidos como parte da atividade prática da disciplina **Banco de Dados (IFPB - MPTI)**, utilizando o **MongoDB Compass** e os datasets `series.json` e `noticias.json`.

## 📁 Estrutura do Repositório

mongo-consultas-avancadas/
├── series/
│ ├── consulta1-mediaNotas.json
│ ├── consulta2-atorJustinHartley.json
│ └── consulta3-usuariosCriticas.json
├── noticias/
│ └── (reservado para consultas futuras)
├── dados/
│ ├── series.json
│ └── noticias.json
└── README.md

---

## 📦 Dados utilizados

Os dados foram obtidos a partir do repositório:

- [series.json](https://raw.githubusercontent.com/ifpb/MPTI-BD/main/exemplos/06-mongo/series.json)
- [noticias.json](https://raw.githubusercontent.com/ifpb/MPTI-BD/main/exemplos/06-mongo/noticias.json)

---

## 🔍 Consultas

### 🔹 Consulta 1 — Média de notas por série

> Calcula a média das notas atribuídas nas críticas de usuários para cada série. Ordena da maior para a menor média.

📄 Arquivo: [`consulta1-mediaNotas.json`](series/notas_series.json)

---

### 🔹 Consulta 2 — Séries e personagens de Justin Hartley

> Exibe o nome da série e o personagem interpretado pelo ator *Justin Hartley*.

📄 Arquivo: [`consulta2-atorJustinHartley.json`](series/consulta_ator.json)

---

### 🔹 Consulta 3 — Ranking de usuários que mais postaram críticas

> Lista usuários e a quantidade de críticas postadas por cada um, em ordem decrescente e alfabética.

📄 Arquivo: [`consulta3-usuariosCriticas.json`](series/consulta_criticas.json)

---

## 🛠️ Ferramentas Utilizadas

- MongoDB Compass
- MongoDB Aggregation Pipeline
- Git & GitHub

---

## 👨‍💻 Autor

Samuel Marinho de Albuquerque  
Mestrando em Tecnologia da Informação — IFPB  
[github.com/samuel-marinho](https://github.com/samuel-marinho)
Email: samuelmarinho64@gmail.com
