# Projeto: Testes de API Rest com Postman e Validação de Back-end (Sprint 4)

## 📌 Sobre o Projeto
Este projeto prático foi desenvolvido durante o bootcamp de Engenharia de QA da TripleTen Brasil. O foco central foi realizar a garantia de qualidade do back-end do sistema "Urban.Grocers", validando endpoints, processamento de dados e regras de negócio através de requisições HTTP utilizando o Postman. Todas as falhas críticas encontradas foram integradas e reportadas no Jira.

## 🛠️ Escopo Técnico e Atividades Executadas
* **Análise de Documentação Técnica (ApiDoc):** Interpretação de especificações e requisitos de back-end para mapear os endpoints `/api/v1/kits/{id}/products` e `/order-and-go/v1/delivery`.
* **Design de Testes para APIs:** Criação de cenários de testes abrangentes baseados em payloads JSON positivos e negativos, cobrindo estruturas de objetos, arrays (como listas com 30 e 31 itens) e tipos de dados.
* **Validação de Métodos e Parâmetros:** Testes rigorosos em Path Parameters e Request Bodies, forçando comportamentos inesperados do sistema com valores nulos, vazios, negativos, strings longas e caracteres especiais (`@@@`, `Teste`).
* **Análise de Respostas HTTP:** Verificação analítica dos códigos de status de retorno esperados (ex: `200 OK`, `400 Bad Request`, `404 Not Found`, `405 Method Not Allowed`) versus as respostas reais do servidor para identificar vulnerabilidades e erros genéricos (como falhas de tratamento gerando `500 Internal Server Error`).
* **Gestão e Rastreabilidade no Jira:** Identificação e abertura detalhada de Bug Reports amarrados diretamente aos endpoints afetados e vinculados à ferramenta de gestão (Tickets `CAM-36` a `CAM-54`).

## 🧰 Ferramentas Utilizadas
* **Execução e Validação de Requisições:** Postman / HTTP Client
* **Estruturação de Casos de Teste:** Google Sheets
* **Gerenciamento e Bug Tracking:** Jira / Atlassian Ecosystem

## 🔗 Artefatos e Entregáveis deste Projeto
* [Acesse aqui a Planilha Completa de Casos de Teste de API e Links do Jira](https://docs.google.com/spreadsheets/d/1OV0VGFxSrHOGa5wJnooNnhSgalaK-XHt/edit?gid=222111639#gid=222111639)
