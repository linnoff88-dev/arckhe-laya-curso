# Laya & Jev â€” decisÃµes estruturadas na prÃ¡tica

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso INEMA no **formato v2**, em repositÃ³rio separado do projeto executÃ¡vel.

**[Abrir curso](https://inematds.github.io/laya-curso/)** Â· **[Projeto prÃ¡tico](https://github.com/inematds/laya)** Â· **[Guia](https://inematds.github.io/laya/guia/)**

4 trilhas, 8 mÃ³dulos, 48 tÃ³picos com exercÃ­cios e respostas comentadas. Fundamentos, instalaÃ§Ã£o, Router e tokens, triagem em portuguÃªs, integraÃ§Ã£o com agentes, avaliaÃ§Ã£o e especializaÃ§Ã£o. Fontes e ressalvas em `fontes.html`.

## Ler e estudar

Abra `index.html` ou sirva a pasta com `python3 -m http.server 8080`. HTML, CSS, JS, diagramas e imagens sÃ£o locais. Funciona sem Tailwind CDN ou build no navegador.

- Progresso, dÃºvidas, seleÃ§Ã£o de texto, notas e destaques.
- Minha jornada, exportaÃ§Ã£o/importaÃ§Ã£o JSON, retomada entre mÃ³dulos.
- Temas claro, escuro, sÃ©pia, foco e contraste; preferÃªncias de leitura.
- Sem login nem backend: estado no localStorage deste navegador, com fallback efÃªmero. Exporte para backup e troca de dispositivo. Em file:// o escopo de armazenamento depende do navegador; use servidor local para persistÃªncia entre pÃ¡ginas consistente.
- Sem JavaScript o conteÃºdo continua legÃ­vel; acordeÃµes de trilha comeÃ§am abertos.

## Manter

ConteÃºdo autoral em `scripts/content.py`, gerador em `scripts/build.py`. Camada v2 copiada para `assets/`, com correÃ§Ãµes locais documentadas em `FALHAS.md`. O gerador usa os assets jÃ¡ presentes; nÃ£o depende da skill instalada para reconstruir depois do clone.

```bash
python3 scripts/build.py
python3 scripts/check.py
```

VersÃ£o: v1.1.0. Imagens fornecidas pelo usuÃ¡rio; nÃ£o sÃ£o evidÃªncia tÃ©cnica. O vÃ­deo e materiais integrais de terceiros ficam no acervo local de pesquisa e sÃ£o referenciados, nÃ£o republicados integralmente. NÃ£o treinamos um modelo nem executamos Jev neste curso. LicenÃ§a Apache 2.0 para o cÃ³digo; atribuiÃ§Ãµes upstream no projeto prÃ¡tico.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>