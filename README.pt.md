---

**Idioma / Language / Langue / Lingua / Idioma:**
[EN](README.md) | [FR](README.fr.md) | [ES](README.es.md) | [IT](README.it.md) | [PT](README.pt.md)

> *Versões multilíngues produzidas com [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — pipeline de tradução SFL-first do mesmo autor.*

---

# sfl-arquitetura-llm-primeiro

**© 2026 Simon Drury (sjd_datascapes)**

---

## O que é isto

Uma especificação pública e datada de uma arquitetura LLM baseada na Linguística Funcional Sistêmica (LFS).

A afirmação central: a linguística funcional sistêmica — e em particular as metafunções ideacional, interpessoal e textual — constitui o quadro correto para o design de LLM, a engenharia de prompts e a orquestração de agentes. Não se trata de aplicar a LFS *sobre* um LLM. Trata-se da LFS como *sistema operacional* do LLM.

---

## O problema com o design atual dos LLM

Os LLM atuais e seus prompts de sistema são:

- ideacionalmente subespecificados (sem arquitetura de campo/domínio baseada em princípios)
- interpessoalmente incoerentes (sem modelagem baseada em princípios de papel, postura ou tenor)
- textualmente ad hoc (sem estrutura baseada em princípios de gênero, registro ou fluxo de informação)

Resultado: os usuários dedicam um tempo considerável a corrigir falhas de nível de sistema que nunca deveriam ter sido incorporadas.

---

## A arquitetura LFS-first

### 1. O registro como parâmetro de design primário

Toda interação com um LLM é governada por um contexto de situação. As três variáveis de registro — campo, tenor, modo — devem ser codificadas explicitamente como parâmetros de nível de sistema, não inferidas de forma estocástica.

- **Campo**: Qual domínio de atividade está em jogo? Qual estrutura de conhecimento o rege?
- **Tenor**: Qual é a relação de papéis? Quais estruturas de obrigação e afeto se aplicam?
- **Modo**: Qual é o canal retórico? Qual densidade e fluxo de informação são esperados?

### 2. As metafunções como sistema de tipagem de agentes

As três metafunções não são meras categorias analíticas. Numa arquitetura LFS-first, tornam-se papéis funcionais para agentes e subprocessos:

- **Agente ideacional**: gere o conhecimento do domínio, a construalização experiencial, as relações lógicas
- **Agente interpessoal**: gere a postura, a avaliação, a obrigação, a modalidade, as relações de papel
- **Agente textual**: gere a coesão, a estrutura informativa, o sequenciamento genérico, a progressão temática

### 3. O gênero como especificação de saída

A saída não é «uma resposta». É uma instância de gênero — um processo social por etapas orientado para um objetivo. O gênero deve ser especificado explicitamente antes da geração, não inferido das características superficiais do prompt.

### 4. Engenharia de prompts LFS-first

Os prompts não são instruções em linguagem natural. São operadores meta-textuais sobre um espaço funcional sistêmico. Um prompt LFS-first bem formado especifica:

- o registro do texto alvo
- a estrutura de gênero esperada
- a ponderação metafuncional necessária
- os parâmetros de avaliação e modalidade

---

## Implementações

Os repositórios a seguir implementam aspectos desta arquitetura:

- [systemic_func_context-wrapper](https://github.com/simon-drury/systemic_func_context-wrapper) — wrapper de instrução LFS para prompts
- [sfl-translation-agent](https://github.com/simon-drury/sfl-translation-agent) — agente de tradução multilíngue baseado em LFS
- [browser_bridge_-sfl-playground-extension_sjd_datascapes](https://github.com/simon-drury/browser_bridge_-sfl-playground-extension_sjd_datascapes) — análise LLM multi-modelo LFS-first
- [numerai-sfl-pipeline](https://github.com/simon-drury/numerai-sfl-pipeline) — pipeline multi-agente informado por LFS

---

## Licença

Esta especificação é de uso livre para uso pessoal, acadêmico e open source não comercial.
Qualquer uso comercial (que gere receita direta ou indiretamente) requer uma licença separada do autor.

Agradece-se o contacto caso esteja previsto um uso comercial. As condições de licença estão abertas a discussão.

**Contacto**: simondrury2010@gmail.com | [LinkedIn](https://www.linkedin.com/in/simon-drury-60b881293)

---

*Primeira publicação: março de 2026. Datado no GitHub como anterioridade.*
