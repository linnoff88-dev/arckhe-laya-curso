ï»¿# Laya & Jev ê¢â¬â decisêÂµes estruturadas na prêÂ¡tica

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="48" />
  <p><strong>Arckhé AI</strong></p>
</div>


Curso INEMA no **formato v2**, em repositêÂ³rio separado do projeto executêÂ¡vel.

**[Abrir curso](https://inematds.github.io/laya-curso/)** êÂ· **[Projeto prêÂ¡tico](https://github.com/inematds/laya)** êÂ· **[Guia](https://inematds.github.io/laya/guia/)**

4 trilhas, 8 mêÂ³dulos, 48 têÂ³picos com exercêÂ­cios e respostas comentadas. Fundamentos, instalaêÂ§êÂ£o, Router e tokens, triagem em portuguêÂªs, integraêÂ§êÂ£o com agentes, avaliaêÂ§êÂ£o e especializaêÂ§êÂ£o. Fontes e ressalvas em `fontes.html`.

## Ler e estudar

Abra `index.html` ou sirva a pasta com `python3 -m http.server 8080`. HTML, CSS, JS, diagramas e imagens sêÂ£o locais. Funciona sem Tailwind CDN ou build no navegador.

- Progresso, dêÂºvidas, seleêÂ§êÂ£o de texto, notas e destaques.
- Minha jornada, exportaêÂ§êÂ£o/importaêÂ§êÂ£o JSON, retomada entre mêÂ³dulos.
- Temas claro, escuro, sêÂ©pia, foco e contraste; preferêÂªncias de leitura.
- Sem login nem backend: estado no localStorage deste navegador, com fallback efêÂªmero. Exporte para backup e troca de dispositivo. Em file:// o escopo de armazenamento depende do navegador; use servidor local para persistêÂªncia entre pêÂ¡ginas consistente.
- Sem JavaScript o conteêÂºdo continua legêÂ­vel; acordeêÂµes de trilha comeêÂ§am abertos.

## Manter

ConteêÂºdo autoral em `scripts/content.py`, gerador em `scripts/build.py`. Camada v2 copiada para `assets/`, com correêÂ§êÂµes locais documentadas em `FALHAS.md`. O gerador usa os assets jêÂ¡ presentes; nêÂ£o depende da skill instalada para reconstruir depois do clone.

```bash
python3 scripts/build.py
python3 scripts/check.py
```

VersêÂ£o: v1.1.0. Imagens fornecidas pelo usuêÂ¡rio; nêÂ£o sêÂ£o evidêÂªncia têÂ©cnica. O vêÂ­deo e materiais integrais de terceiros ficam no acervo local de pesquisa e sêÂ£o referenciados, nêÂ£o republicados integralmente. NêÂ£o treinamos um modelo nem executamos Jev neste curso. LicenêÂ§a Apache 2.0 para o cêÂ³digo; atribuiêÂ§êÂµes upstream no projeto prêÂ¡tico.

---

<div align="center">
  <img src="capa/logo.svg" alt="Arckhé AI" height="32" />
  <p><strong>Arckhé AI</strong></p>
</div>