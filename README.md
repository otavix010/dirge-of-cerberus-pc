<h1 align="center">Dirge of Cerberus: Final Fantasy VII — port nativo para PC</h1>

<p align="center"><i>Dirge of Cerberus: Final Fantasy VII (PS2, NTSC-U SLUS-21419): port nativo para PC por recompilação estática (PS2Recomp). Em desenvolvimento (o port ainda vai começar).</i></p>

<p align="center">
  <a href="https://github.com/otavix010/dirge-of-cerberus-pc/commits/main"><img alt="Última atualização" src="https://img.shields.io/github/last-commit/otavix010/dirge-of-cerberus-pc?label=%C3%BAltima%20atualiza%C3%A7%C3%A3o"></a>
  <a href="https://github.com/otavix010/otavix-launcher/releases/latest"><img alt="Baixar o Otavix Launcher" src="https://img.shields.io/badge/Otavix%20Launcher-baixar-b00020"></a>
  <img alt="Windows 10/11" src="https://img.shields.io/badge/Windows-10%2F11-0078d4">
  <img alt="Linux: não suportado no momento" src="https://img.shields.io/badge/Linux-n%C3%A3o%20suportado-lightgrey">
  <img alt="Em preparação" src="https://img.shields.io/badge/situa%C3%A7%C3%A3o-em%20prepara%C3%A7%C3%A3o-f5a623">
</p>

<p align="center">
  <a href="#estado-atual-em-desenvolvimento">Estado atual: em desenvolvimento</a> ·
  <a href="#plataformas-e-situação">Plataformas e situação</a> ·
  <a href="#o-que-você-vai-precisar">O que você vai precisar</a> ·
  <a href="#licença-e-créditos">Licença e créditos</a> ·
  <a href="#english-summary">English</a>
</p>

> **Projeto de fãs, sem fins lucrativos.** *Final Fantasy VII* e *Dirge of Cerberus* são marcas registradas da Square Enix; este projeto não tem relação com a Square Enix. Este repositório **não contém o jogo**: você vai precisar da **sua própria cópia** do DVD (a versão americana, **SLUS-21419**).

Port nativo para PC por **recompilação estática** com o motor PS2 próprio do projeto, no mesmo esquema dos outros ports de PlayStation 2 do Otavix: o seu PC gera e compila o jogo a partir da sua ISO.

## Estado atual: em desenvolvimento

**O port ainda vai começar.** Antes, estamos fortalecendo a base comum dos ports de PS2 (tradutor, runtime, IOP, VU1 e GS) com os primeiros jogos: [Spawn: Armageddon](https://github.com/otavix010/spawn-armageddon-pc), [Ghost Rider](https://github.com/otavix010/ghost-rider-pc), [Medal of Honor: European Assault](https://github.com/otavix010/moh-european-assault-pc) e [10.000 Bullets](https://github.com/otavix010/10000-bullets-pc). As novidades vão aparecendo em `NOVIDADES.md` e na página do jogo no Otavix Launcher.

## Plataformas e situação

| | |
|---|---|
| Situação | **em preparação**: o port ainda não existe; este repositório guarda o plano e as novidades |
| Gerador (`gerar.cmd`) | **ainda não existe** |
| Desempenho | **sem dado**: o jogo ainda não inicia no nosso motor |
| Windows 10/11 | alvo do port |
| Linux / SteamOS | **não suportado no momento** (só o port de *God of War: Ascension* tem versão Linux, beta) |

Quando o port começar a rodar, este README ganha os requisitos, o desempenho medido (PC 1, PC 2, Notebook e Portátil) e as perguntas frequentes, como nos [ports que já geram](https://github.com/otavix010/god-of-war-2-pc).

## O que você vai precisar

- A ISO da versão americana: Redump **"Dirge of Cerberus - Final Fantasy VII (USA)"** (SLUS-21419).
- Windows 10/11 de 64 bits, um processador x86-64 (AVX2 ajuda, mas não é obrigatório) e espaço para a geração (alguns GB).

## Licença e créditos

- **O nosso código**: [MIT](LICENSE).
- **O motor do port** (o motor PS2 próprio do projeto, que o gerador vai baixar pronto) não é coberto pela licença MIT; os avisos de terceiros dele ficam no `TERCEIROS.txt` do pacote.
- *Final Fantasy VII* e *Dirge of Cerberus* são marcas registradas da Square Enix. Este é um projeto de fãs, sem fins lucrativos, sem relação com a Square Enix nem endossado por ela.

## English summary

A **native PC port** of *Dirge of Cerberus: Final Fantasy VII* (PlayStation 2, 2006) by **static recompilation** with the project's own PS2 engine. **Work in progress: the port has not started yet** — we are first strengthening the shared PS2 base with the first four games. You will need your own copy of the **American** release (SLUS-21419, Redump "Dirge of Cerberus - Final Fantasy VII (USA)") as an .iso. *Final Fantasy VII* and *Dirge of Cerberus* are trademarks of Square Enix; this is a non-commercial fan project, not affiliated with or endorsed by Square Enix.
