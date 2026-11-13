# Pamella RR Studio — Designer Skill

Skill de direção de arte e design para a marca **Pamella RR Studio**, com os ativos oficiais enviados pela marca, guia de identidade e prompt mestre estratégico.

## Conteúdo

```text
.
├── SKILL.md
├── BRAND-GUIDE.md
├── README.md
├── references/
│   └── prompt-mestre-original.md
└── assets/
    ├── Logo/
    ├── Nome/
    ├── Icone/
    ├── Elementos Graficos/
    └── 01 - Outros/
```

## Instalação

### Claude Code
Copie a pasta `pamella-rr-studio` para:

```text
.claude/skills/pamella-rr-studio/
```

No projeto em que deseja usar a skill, o caminho completo será:

```text
seu-projeto/
└── .claude/
    └── skills/
        └── pamella-rr-studio/
            ├── SKILL.md
            ├── BRAND-GUIDE.md
            ├── references/
            └── assets/
```

A skill pode ser versionada junto ao projeto. Para uso pessoal/global no Claude Code, copie a pasta para o diretório de skills pessoais suportado pela sua instalação.

### Outros agentes compatíveis com o formato Agent Skills
O arquivo `SKILL.md` segue a convenção de skills baseada em diretório. Copie a pasta inteira para o diretório de skills reconhecido pelo agente que você utiliza. A descoberta automática e o caminho de instalação variam conforme a ferramenta.

## Como usar

Depois de instalar, solicite tarefas normalmente, por exemplo:
- “Crie um carrossel educativo sobre retenção de extensão de cílios.”
- “Monte uma tabela de preços elegante com os serviços e valores que vou enviar.”
- “Revise esta arte e corrija a hierarquia visual mantendo a identidade.”
- “Crie capas de destaques para Instagram usando os ícones oficiais.”

A skill orienta o agente a consultar os arquivos em `assets/` e o prompt mestre em `references/`.

## Observações sobre os ativos
- Os arquivos originais foram preservados, inclusive nomes e subpastas.
- Existem versões roxas e douradas, composições para diferentes fundos, ícones e elementos gráficos em SVG/PNG.
- Escolha a variante pelo nome e pelo contraste com o fundo real. Não recolora nem distorça os logos.
- A paleta do guia é uma referência digital extraída dos arquivos fornecidos; o logo original prevalece.

## Publicação no GitHub

1. Crie um repositório, por exemplo `pamella-rr-studio-skill`.
2. Extraia o ZIP.
3. Envie todo o conteúdo da pasta para a raiz do repositório.
4. Faça o commit inicial.

```bash
git init
git add .
git commit -m "Add Pamella RR Studio designer skill"
git branch -M main
git remote add origin https://github.com/SEU-USUARIO/pamella-rr-studio-skill.git
git push -u origin main
```

Substitua `SEU-USUARIO` pelo seu usuário do GitHub.

## Licença
Os logotipos, ícones e demais elementos de marca pertencem à Pamella RR Studio e são fornecidos para uso nos materiais da própria marca. Não redistribua os ativos como recursos genéricos nem os utilize para outras marcas sem autorização.
