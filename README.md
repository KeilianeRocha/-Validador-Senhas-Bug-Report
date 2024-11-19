# Validação de Senhas - Testes Manuais

Este projeto documenta os testes manuais realizados em um aplicativo de recarga de transporte público. O objetivo é verificar a consistência entre as mensagens de validação e a lógica de verificação de senhas.

---

## 📋 Estrutura do Projeto

- **testes-manuais/**: Cenários, checklist e relatório dos testes realizados.
- **imagens/**: Capturas de tela ilustrando os resultados dos testes.
- **documentos/**: Análise detalhada do bug identificado.

---

## 🔎 Descrição do Bug

### Problema
A mensagem de validação exige que a senha tenha:
- Pelo menos 8 caracteres.
- Pelo menos 1 letra maiúscula.
- Pelo menos 1 caractere especial.

**Porém, foi possível redefinir senhas que não seguem estas regras.**

### Impacto
- **Confusão do Usuário**: Regras não são aplicadas conforme o esperado.
- **Segurança Comprometida**: Redução da complexidade mínima da senha.

---

## 📂 Como Navegar no Projeto

1. Acesse a pasta `testes-manuais/` para revisar os cenários e os resultados dos testes.
2. Consulte a pasta `imagens/` para capturas de tela que ilustram os erros encontrados.
3. Leia o documento `analise-bug.md` para entender o impacto técnico do problema.

---

## 🚀 Conclusão
Este projeto reforça a importância de testes manuais para identificar inconsistências críticas e garantir a segurança dos usuários.




