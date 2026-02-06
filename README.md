```md
# 📡 Sigma – Documentação de Integração da API

Este repositório contém o site estático de documentação da API Tomografia do Canavial – Sigma Digital Geotecnologias no Agro.

A documentação descreve todos os endpoints, estruturas de dados, formatos JSON e regras de integração utilizadas pelas usinas
e parceiros para envio e consumo de informações agrícolas (talhões, chuvas, pragas, geometrias GIS, etc).

O site é publicado via **GitHub Pages**.

---

## 🌐 Acesso à documentação

O site está disponível em:

```
https://sigma-geo.github.io/api.sigma/
```

* 📘 Documentação completa da API REST
* 📊 Especificação detalhada de colunas e tipos
* 🐛 Monitoramento de pragas (Broca, Cigarrinha, Lagarta Fora, Solo)
* 🌧️ Dados meteorológicos
* 🔐 Autenticação via Bearer Token
* 🖨️ Botão de exportação em PDF
* 📱 Layout responsivo (desktop e mobile)
---

## 🔐 Autenticação da API
Todas as requisições utilizam token via Header:

```
http
Authorization: Bearer SEU_TOKEN_AQUI
```
---

## 🔗 Endpoints principais

Exemplo:

```text
GET  /api/historico-safra?usina={usina}
POST /api/historico-safra?usina={usina}

GET  /api/precipitacao?usina={usina}
POST /api/precipitacao?usina={usina}

GET  /api/base-talhoes?usina={usina}
POST /api/base-talhoes?usina={usina}

GET  /api/lagarta-fora?usina={usina}
POST /api/lagarta-fora?usina={usina}

GET  /api/broca?usina={usina}
POST /api/broca?usina={usina}

GET  /api/cigarrinha?usina={usina}
POST /api/cigarrinha?usina={usina}

GET  /api/pragas-solo?usina={usina}
POST /api/pragas-solo?usina={usina}
```

## 🖨 Exportar PDF

Clique no botão:

```
Exportar PDF
```

Ou use:

```
Ctrl + P
```

O layout já está preparado para impressão em A4.

---

## 📞 Contato técnico

Para dúvidas sobre integração ou API:

* Justino Neto — Gerente de Projetos e Integrações
* Victoria Vagner — Coordenadora de Geoprocessamento

(Os contatos completos estão no final da documentação.)

---
## 📄 Licença

Este projeto é privado e destinado exclusivamente à documentação técnica da Sigma.

Uso restrito a clientes e parceiros autorizados.
```
