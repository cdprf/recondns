<h1 align="center">
  <br>
  <a href="https://github.com/blackcode666/recondns"><img src="https://github.com/blackcode666/recondns/blob/main/images/banner.png" alt="recondns"></a>
  <br>
  reconDNS
  <br>
</h1>


<p align="center">
  <a href="https://github.com/blackcode666/recondns/releases/tag/v2.2.2">
    <img src="https://img.shields.io/badge/release-v2.2.2-green">
  </a>
   </a>
  <a href="https://www.gnu.org/licenses/gpl-3.0.en.html">
      <img src="https://img.shields.io/badge/license-GPL3-_red.svg">
  </a>
    <a href="https://github.com/blackcode666/recondns/issues?q=is%3Aissue+is%3Aclosed">
    <img src="https://img.shields.io/github/issues-closed-raw/blackcode666/recondns.svg">
  </a>
  <a href="https://github.com/blackcode666/recondns/wiki">
    <img src="https://img.shields.io/badge/doc-wiki-blue.svg">
  </a>
</p>

 
<h3 align="center">Sumário</h3>

**ReconDNS** automatiza todo o processo de reconhecimento para você. Realiza o trabalho de enumeração de subdomínios, junto com diversos checks de várias vulnerabilidades e o máximo de informação possível do seu alvo.

O **ReconDNS** utiliza de várias técnicas (passive, bruteforce, permutations, certificate transparency, source code scraping, analytics, DNS records...) na enumeração dos subdomínios que ajudam você a selecionar os subdomínios mais interesantes para que você saia na frente.

O mesmo também realiza vários checks de vulnerabilidades como XSS, Open Redirects, SSRF, CRLF, LFI, SQLi, testes de SSL, DNS Zone Transfers e muito mais. Além disso é perfomado diversas técnicas de OSINT, fuzzing de diretórios, dorking, escaneamento de portas e scan do nuclei no seu alvo.

Também foi desenvolvido com objetivo de automatizar e facilitar o trabalho de profissionais da área de cibersegurança.

Então, o que está esperando? Bora! :boom:

📔 Tabela de Conteúdos
-----------------
- [💿 Instalação:](#-installation)
  - [a) No seu PC/VPS/VM](#a-in-your-pcvpsvm)
  - [b) Docker container 🐳 (2 options)](#b-docker-container--2-options)
    - [1) Pelo DockerHub](#1-from-dockerhub)
    - [2) Pelo repositório](#2-from-repository)
- [⚙️ Arquivo de configuração:](#️-config-file)
- [Uso:](#usage)
- [Exemplos de uso:](#example-usage)
- [Suporte ao Axiom: :cloud:](#axiom-support-cloud)
- [Suporte ao BBRF: :computer:](#bbrf-support-computer)
- [Vídeo de Demonstração:](#sample-video)
- [:fire: Características :fire:](#fire-features-fire)
  - [Osint](#osint)
  - [Subdomains](#subdomains)
  - [Hosts](#hosts)
  - [Webs](#webs)
  - [Extras](#extras)
- [Mindmap/Workflow](#mindmapworkflow)
  - [Data Keep](#data-keep)
    - [Comandos principais:](#main-commands)
  - [Como contribuir:](#how-to-contribute)
  - [Precisa de ajuda? :information_source:](#need-help-information_source)
- [Isenção de responsabilidade](#disclaimer)


# Mapa Mental

![Mindmap](https://github.com/blackcode666/recondns/blob/main/images/mindmapDNS.jpg)

<h1 align="center">
  <br>
  <a href="https://github.com/blackcode666/recondns"><img src="https://github.com/blackcode666/recondns/blob/main/images/logo_Omar_Pentester.png" alt="recondns"></a>
  <br>
  blackcode666 - reconDNS - Omar Passos
  <br>
</h1>

The material contained in this repository is licensed under GNU GPLv3.
