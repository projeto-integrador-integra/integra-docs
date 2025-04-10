# 📐 Requisitos Não Funcionais

Esta seção descreve os requisitos não funcionais do sistema Integra, ou seja, as propriedades e qualidades desejadas na aplicação, que impactam na experiência do usuário, desempenho, acessibilidade, manutenibilidade e segurança.

---

## 1. Usabilidade

- RNF01 — O sistema deve ser simples de navegar e utilizar, com foco em usuários com pouca familiaridade com plataformas digitais.
- RNF02 — As mensagens e textos devem utilizar linguagem acessível, humana e inclusiva.
- RNF03 — As telas devem seguir padrões de design claros, com hierarquia visual bem definida e boa legibilidade.

---

## 2. Acessibilidade

- RNF04 — O sistema deve apresentar contraste adequado entre elementos e texto.
- RNF05 — As principais funcionalidades devem ser acessíveis por teclado.
- RNF06 — Os componentes devem seguir boas práticas de acessibilidade semântica (uso de `aria-labels`, landmarks, etc.).

---

## 3. Responsividade e compatibilidade

- RNF07 — O sistema deve ser responsivo e adaptável a diferentes tamanhos de tela (desktop, tablet e dispositivos móveis).
- RNF08 — O sistema deve funcionar nos principais navegadores modernos (Chrome, Firefox, Edge, Safari).

---

## 4. Desempenho

- RNF09 — O carregamento inicial das páginas deve ocorrer em até 3 segundos em conexões regulares.
- RNF10 — As imagens utilizadas devem ser otimizadas para a web (formato, peso e resolução).

---

## 5. Manutenibilidade

- RNF11 — O código do sistema deve ser organizado de forma modular, com uso de componentes reutilizáveis.
- RNF12 — O projeto deve utilizar versionamento com Git e seguir convenções claras de commits e branches.
- RNF13 — A documentação deve ser mantida atualizada durante o desenvolvimento.

---

## 6. Segurança

- RNF14 — Os dados dos usuários devem ser trafegados por conexão segura (HTTPS).
- RNF15 — As informações de autenticação devem ser gerenciadas por serviço confiável (Amazon Cognito).
- RNF16 — O sistema não deve expor credenciais sensíveis no código-fonte.

---

## Observações

- Estes requisitos servem como guia de qualidade e serão validados ao longo do desenvolvimento e testes do sistema.
