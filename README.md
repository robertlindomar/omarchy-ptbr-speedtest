# Omarchy PT-BR — Teste de velocidade (rede)

Tradução para português brasileiro do plugin `omarchy.speedtest` do Omarchy.

**ID do clone:** `robertlindomar.omarchy-ptbr.speedtest`

## O que é traduzido

- Textos e tooltips da interface em pt-BR
- Descrições do manifest quando aplicável
- Teste de velocidade da internet com medidores de download e upload

Tipos: panel. Entry points: Panel.qml.

## Instalação

### Pelo Omarchy (recomendado)

1. Clone este repositório em `~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.speedtest/`
2. Valide: `omarchy plugin validate ~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.speedtest`
3. Habilite: `omarchy plugin enable robertlindomar.omarchy-ptbr.speedtest`
4. Reinicie o shell: `omarchy-restart-shell`

Ou use o instalador do monorepo principal (inclui todos os plugins):

```bash
git clone https://github.com/robertlindomar/omarchy-ptbr-github.git
cd omarchy-ptbr-github
./install.sh
```

### Manual

```bash
git clone https://github.com/robertlindomar/omarchy-ptbr-speedtest.git ~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.speedtest
omarchy plugin validate ~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.speedtest
omarchy plugin enable robertlindomar.omarchy-ptbr.speedtest
omarchy-restart-shell
```

## Remoção

```bash
omarchy plugin disable robertlindomar.omarchy-ptbr.speedtest
rm -rf ~/.config/omarchy/plugins/robertlindomar.omarchy-ptbr.speedtest
omarchy-restart-shell
```

Para remover todos os plugins pt-BR de uma vez, use o desinstalador do monorepo:

```bash
cd omarchy-ptbr-github
./uninstall.sh
```

## Licença e dependências

- **Licença:** MIT (ver `LICENSE`). Obra derivada do plugin upstream `omarchy.speedtest`.
- **Requisitos:** Omarchy instalado, Hyprland em execução, Quickshell (incluído no Omarchy).
- **Dependências externas:** nenhuma além do stack Omarchy/Quickshell.

## Origem

Plugin baseado em: `omarchy.speedtest`

Projeto principal: https://github.com/robertlindomar/omarchy-ptbr-github

## Aviso

Projeto comunitário e **não oficial**. Não modifique `/usr/share/omarchy`.

## Problemas / traduções faltando

Abra uma issue em https://github.com/robertlindomar/omarchy-ptbr-github/issues ou neste repositório.
