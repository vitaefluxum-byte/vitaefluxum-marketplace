---
name: vitaefluxum
description: Crea i revisa personatges realistes, blueprints, vestuari, escenaris, storyboards 3x3, reconstruccions de fotogrames i prompts de vídeo amb timeline per als projectes audiovisuals de VitaeFluxum. Utilitza-la quan calgui continuïtat visual, identitat estable, lateralitat anatòmica o preparació d'imatges per animar; no és per a miniatures de YouTube ni per a edició tècnica convencional de vídeo.
---

# Skill VitaeFluxum

Ajuda a construir material visual cinematogràfic reutilitzable mantenint la identitat del personatge i la continuïtat entre imatges i vídeos.

## Selecció del flux

- Per crear o consolidar una cara, un cos, un personatge o vestuari, llegeix [references/prompts-personajes.md](references/prompts-personajes.md) i utilitza únicament el bloc corresponent.
- Per crear un escenari, integrar-hi el personatge, preparar un storyboard 3x3 o reconstruir-ne un fotograma, llegeix [references/prompts-personajes.md](references/prompts-personajes.md).
- Per animar una imatge o preparar un vídeo a Grok, FlexClip o una altra eina, llegeix [references/video-timeline.md](references/video-timeline.md).

No enganxis tots els prompts en una sola generació. Tria el flux mínim que resol la petició.

## Principis obligatoris

1. Les imatges aprovades són la font principal. No redissenyar allò que ja mostren.
2. Dreta i esquerra sempre signifiquen el costat anatòmic del personatge, no el costat de l'espectador.
3. Fixa abans de generar la identitat, les marques, la roba, els objectes, la mà que els sosté i l'orientació de l'escenari.
4. Mantén asimetries humanes subtils i plausibles. Evita pell plàstica, perfecció publicitària, textura artificial i aparença de render.
5. Si falta informació imprescindible, inventa-la de manera conservadora i converteix-la en continuïtat per als resultats posteriors.
6. Revisa el resultat abans d'aprovar-lo. Si hi ha un error de lateralitat, identitat, anatomia, vestuari, objectes, escenari o numeració, corregeix-lo sense alterar el que ja és correcte.

## Treball amb imatges

Quan la petició impliqui crear o editar una imatge, utilitza l'eina d'imatges disponible. Etiqueta mentalment cada entrada com a identitat, vestuari, escenari, composició o objectiu d'edició. Conserva els invariants de manera explícita al prompt.

Per a storyboards:

- exactament nou quadres iguals;
- numeració `1–9`, d'esquerra a dreta i de dalt a baix;
- mateix personatge, roba, lloc, llum i eix espacial;
- angles variats però físicament compatibles;
- una sola acció narrativa coherent.

Quan l'usuari escull un número, reconstrueix exclusivament aquell quadre. No el substitueixis per un altre, no barregis fotogrames i elimina només la quadrícula i el número.

## Validació abans d'entregar

Comprova visualment:

- mateixa identitat, edat, cos, cabell i roba;
- marques i objectes al costat anatòmic i a la mà correcta;
- mans, dits, braços, cames i peus plausibles;
- perspectiva, contacte, escala, ombres i direcció de llum coherents;
- escenari i elements permanents sense desaparicions ni reflexos;
- numeració i selecció correctes en storyboards;
- absència de text accidental, logotips o marques d'aigua.

No prometis perfecció abans de veure el resultat. Si una limitació del generador impedeix corregir un error després d'intents raonables, explica-la clarament.

## Lliurament

Mostra el resultat i resumeix les decisions de continuïtat rellevants. Si és un prompt, entrega'l complet i llest per copiar, preferentment en castellà quan el material sigui per al canal de YouTube de VitaeFluxum.
