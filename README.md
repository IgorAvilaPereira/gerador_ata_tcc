# 📄 Gerador Institucional de Ata e Declarações de TCC

## 📌 Descrição

Este repositório contém uma **aplicação web institucional** desenvolvida para **geração automatizada de documentos acadêmicos** relacionados à **defesa de Trabalhos de Conclusão de Curso (TCC)**.

A aplicação permite gerar, de forma padronizada e segura:

* **Ata de Defesa Final de TCC**
* **Declaração de Orientação**
* **Declaração de Coorientação** (quando aplicável)
* **Declarações de Participação em Banca Examinadora**

Todos os documentos são gerados **diretamente no navegador**, sem necessidade de backend, banco de dados ou serviços externos.

---

## 🎯 Finalidade Institucional

Este sistema foi projetado para apoiar:

* Coordenações de curso
* Professores orientadores
* Secretarias acadêmicas
* Comissões de TCC

Com foco em:

* Padronização documental
* Redução de erros manuais
* Agilidade na emissão de documentos oficiais
* Facilidade de impressão e arquivamento

---

## 🧩 Funcionalidades

### Formulário de Dados

A aplicação disponibiliza um formulário para preenchimento dos seguintes campos:

* Nome completo do(a) aluno(a)
* Título do Trabalho de Conclusão de Curso
* Data e horário da defesa
* Presidente / Orientador
* Coorientador (opcional)
* Membros da banca examinadora
* Coordenador(a) do curso (responsável pela assinatura)
* Resultado da defesa
* Nota final

---

### Geração de Documentos

A partir dos dados informados, o sistema possibilita:

* **Geração individual da Ata de Defesa**
* **Geração completa de todos os documentos** (Ata + Declarações)

Cada documento é:

* Aberto em **nova aba ou janela** do navegador
* Disponibilizado com botão **Imprimir**
* Editável antes da impressão (quando necessário)

---

## 🛠️ Arquitetura e Tecnologias

* **HTML5** — estrutura da aplicação
* **CSS3** — layout e responsividade
* **JavaScript (Vanilla)** — lógica de geração dos documentos

> Não há dependências externas ou frameworks.

---

## 🔐 Segurança e Confiabilidade

* Os dados são processados **exclusivamente no navegador**
* Nenhuma informação é armazenada ou transmitida
* Função de sanitização (`escapeHtml`) evita inserção indevida de código HTML

---

## ▶️ Modo de Uso

1. Acesse https://html-preview.github.io/?url=https://github.com/IgorAvilaPereira/gerador_ata_tcc/blob/main/ata.html
2. Preencha o formulário com os dados da defesa
3. Selecione uma das opções:

   * **Gerar ATA**
   * **Gerar Tudo (ATA + Declarações)**
4. Revise os documentos, edite se necessário e imprima (botão Imprimir)

---

## ⚠️ Requisitos Técnicos

* Navegador web atualizado (Chrome, Firefox, Edge)
* Permissão para abertura de pop-ups (necessária para os documentos)

---

## 🏫 Adequação Institucional

Os textos, logotipos e denominações podem ser facilmente adaptados para:

* Outros cursos
* Outros campi
* Outras instituições de ensino

Recomenda-se validação prévia junto à coordenação e setor jurídico/acadêmico da instituição.

---

## 📄 Licença e Uso

Uso permitido para fins **acadêmicos, administrativos e institucionais**.

Este projeto pode ser reutilizado e adaptado, desde que respeitadas as normas internas da instituição.

---

## ✍️ Resumo Executivo

> Aplicação web institucional para geração automática, padronizada e segura de atas e declarações de defesa de TCC, pronta para uso acadêmico e administrativo.
