# NewSkills

---

## O que é uma "Skill"?

Uma skill responde a uma pergunta simples:

> *"Como aplico essa ideia em produção — e onde ela quebra?"*

Cada skill inclui:

- Contexto e problema resolvido
- Quando usar / quando **não** usar
- Checklist de implementação
- Armadilhas comuns
- Métricas de monitoramento
- Alternativas e fallbacks
- Referência ao paper original

Formato pensado para leitura humana e uso direto por IAs, copilots e agentes.

---

## Estrutura do Repositório

```
/
├── skills/
│   ├── uncertainty/
│   ├── interpretability/
│   ├── privacy/
│   ├── drift/
│   └── ...
├── templates/
│   └── new-skill-template.md
├── README.md
└── LICENSE
```

---

## Níveis de Maturidade

Cada skill declara explicitamente seu nível de confiabilidade:

| Nível | Significado |
|---|---|
| Experimental | Testado em ambiente controlado |
| Validado | Reproduzido com dados reais |
| Relato de Produção | Evidência prática de uso em produção |

Transparência operacional, não marketing.

---

## Como Usar

**1. Clone o repositório**

```bash
git clone https://github.com/seuuser/ml-signal.git
```

**2. Navegue por categoria**

As skills são autoexplicativas e independentes entre si.

**3. Copie, adapte e use**

Tudo está sob Licença MIT. Atribuição é bem-vinda, não obrigatória.

---

## Contribuindo

Contribuições são bem-vindas — desde que mantenham o padrão.

**Aceito:**
- Sugestões de papers via Issues
- Melhorias em skills existentes
- Novas skills usando o template padrão

**Não aceito:**
- Resumos sem aplicação prática
- Conteúdo puramente acadêmico
- Skills sem trade-offs explícitos

Antes de contribuir: `templates/new-skill-template.md`

---

## Licença

MIT — use à vontade, atribua quando possível.

---

## Curadoria

Curado por [@seuuser](https://github.com/seuuser).  
Processo aberto. Decisões públicas. Evolução contínua.

O objetivo não é ser o único. É ser o mais útil, consistentemente.
