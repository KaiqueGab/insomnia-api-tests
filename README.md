# Testes de API – Insomnia

Este repositório contém uma coleção **Insomnia** com testes automatizados (Insomnia Tests) para a API pública **Restful Booker**. O foco é validar cenários de **autenticação**, **CRUD de bookings** e **healthcheck**.

> Arquivo principal: `Insomnia_2026-02-20.yaml`

---

## 🚀 Visão geral
- **Ferramenta**: Insomnia (coleções + testes nativos por script)
- **Escopo**:
  - `AUTH`: criação de token de acesso (cenários **positivos** e **negativos**)
  - `BOOKING`: criar, consultar (por ID e por parâmetros), atualizar (PUT), atualizar parcialmente (PATCH) e excluir
  - `HEALTHCHECK`: endpoint `/ping`
- **Ambiente**: variáveis de ambiente dentro da coleção (base URL e dados padrão) 
