# Bit a Bit · Club de programació del pati

Web del club de programació **Bit a Bit** (curs 2026-27). Es fa al pati, dimarts i dimecres, a l'aula d'informàtica.

L'alumnat fa una prova de nivell, tria què vol fer i rep un camí personalitzat amb recursos (en català, castellà o anglés, en eixe ordre de preferència). Al final s'apunta al club amb un formulari de Microsoft Forms que ja arriba mig omplit.

## Com funciona

1. **Punt de partida**: novell/a, conec un poc els blocs, domine bé els blocs, ja programe amb codi o ja conec altres eines.
2. **Prova de nivell**: unes poques preguntes que s'adapten a les respostes per comprovar el nivell triat.
3. **Què vols fer**: crear un videojoc, programar de veres, robots (Maqueen Lite i micro:bit), intel·ligència artificial, competir (Upsteam i Olimpiada Informàtica), ser monitor/a (2n de Batxillerat), altres coses (mecanografia, disseny, seguretat i Linux) o encara no ho sé.
4. **El teu camí**: passos i recursos segons el nivell i l'objectiu, amb un minijoc relacionat.
5. **Normes i inscripció**: cal confirmar les normes de l'aula i omplir el formulari.

## Minijocs

Pac-Man, Maqueen, Taller de prompts, Munta un agent, Entrena la IA, Cerca binària, Caça l'error, Terminal LliureX, Sí o no al club? i Teclat ràpid.

## Normes de l'aula

1. Tracta bé els equips.
2. Respecta el professorat i els companys.
3. Segueix les indicacions del professor.
4. Fes un ús correcte d'Internet.
5. Avisa si alguna cosa no funciona o es trenca.
6. Deixa el lloc com l'has trobat.
7. Vens a aprendre i a ajudar.

Qui no les complisca no podrà continuar venint al club.

## Tecnologia

Tot està en un sol fitxer, `index.html` (HTML, CSS i JavaScript sense dependències). No cal cap servidor: es publica amb GitHub Pages o s'obri directament al navegador.

Per a canviar el formulari d'inscripció, edita la variable `FORMS_PREFILL` d'`index.html` amb l'enllaç precomplet del teu formulari.

## Publicar-la amb GitHub Pages

1. Puja `index.html` a l'arrel del repositori.
2. Settings → Pages → Source: *Deploy from a branch*, branca `main`, carpeta `/ (root)`.
3. Al cap d'uns minuts estarà a `https://<usuari>.github.io/<repositori>/`.

## Actualitzar-la

```bash
git add index.html README.md
git commit -m "Actualitza recursos"
git push
```
