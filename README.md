# Focus Dark Minimal

Tema dark minimalista para VS Code: visual limpo, alto foco e ótima legibilidade para programar por horas.

![Script](https://i.imgur.com/7Yx4YOX.png)

## Sobre

**Focus Dark Minimal** é um tema dark e minimalista para **foco total**, **UI limpa** e **legibilidade** consistente. Contraste equilibrado, sintaxe clara e superfícies discretas — ideal para longas sessões de código.

* 🖤 **Dark de verdade**: fundo escuro consistente, sem “cinza lavado”.
* 🔤 **Sintaxe legível**: cores pensadas para reduzir fadiga visual.
* 🧭 **UI discreta**: painéis, breadcrumbs e status bar na medida.
* ⚡ **Produtividade**: menos ruído = mais flow.

## Instalação

### Marketplace

1. Abra o VS Code → **Extensões** (Ctrl/Cmd + Shift + X).
2. Pesquise por **“Focus Dark Minimal – Tema para VS Code”**.
3. Clique em **Install** e depois em **Set Color Theme**.

### Local (.vsix)

```bash
code --install-extension ultra-dark-minimal-0.0.1.vsix
```

### Como ativar

1. `Ctrl/Cmd + K` e depois `Ctrl/Cmd + T`.
2. Selecione **Focus Dark Minimal**.

## Paleta de cores

| Papel                | Cor       |
| -------------------- | --------- |
| Fundo editor         | `#0F0F10` |
| Texto padrão         | `#EAEAEA` |
| Comentários          | `#7A7F87` |
| Delimitadores/Chaves | `#B5BBC3` |
| Strings              | `#E6D06C` |
| Keywords             | `#C77CFF` |
| Functions/Methods    | `#6BD0FF` |
| Vars/Props           | `#FF9E64` |
| Erros                | `#FF5D62` |
| Avisos               | `#FFD166` |
| Info                 | `#4DD0E1` |

> Ajuste conforme seu `themes/focus-dark-minimal-color-theme.json`.

## Solução de problemas

* Tema não aparece na lista?
  Verifique o `"name"` dentro do arquivo do tema (não só o `displayName` da extensão). Depois: Developer: Reload Window.
* Terminal/Output não acompanham as cores?
  Aplique overrides via `workbench.colorCustomizations` (exemplo acima).
* Conflito com ícones/UX?
  Desative extensões de UI agressivas ou ajuste `"workbench.iconTheme"`.

## Roadmap

* Ampliação de escopo de cores para mais linguagens.
* Variante **High Contrast Soft.**
* Paletas alternativas (Monochrome / Blue-ish).

## Contribuindo

1. Abra issue com screenshot, linguagem e trecho de código.
2. Sugira cores (hex) com justificativa.
3. Pull requests são bem-vindos.

## Licença

MIT — use, adapte e bora codar feliz.

## Criado por

> **Vittor F. Serra**
