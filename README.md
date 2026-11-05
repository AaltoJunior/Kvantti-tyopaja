# Pytho/jupyter notebook pohjaisten työpajojen luonti binderiä varten

1. Tee uusi julkinen github repository tai voit myös forkata tämän repositoryn.
2. Kopio repositoryysi tämän repositoryn rakenne ja tiedostot
3. Työpajan binder linkki on muotoa `https://junior-binderhub.aalto.fi/v2/gh/AaltoJunior/REPOSITORYN_NIMI/HEAD?urlpath=lab/tree/notebooks/README.ipynb` jossa korvaat `REPOSITORYN_NIMI` kohdan github reopsitoryn nimellä.
4. Laita tämä linkki dioihin ja wikiin työpajaa varten
5. Repositoryyn tehdyt muutokset päivittyvät automaattisesti binderiin

## Tietoja systeemistä

`/notebooks/` kansio on työpajan .ipynb tiedostoja varten. README.ipynb on aloitustiedosto joka latautuu automaattisesti linkkin avattaessa. `FI/`, `EN/`, `SE/` kansiot ovat työpajan eri kielisiä versioita varrten. Näiden kansioiden sisällä nimeämisperjaate on `FI_työpajan_nimi.ipynb`.

`/.jupyter/...` kansio on jupyterin asetuksia varten. Näitä ei tarvitse muokata! Perus asetukset ovat laitettu valmiiksi.

`/binder/` kansiossa on `requirements.txt` tiedosto jossa voidaa määritellä kirjaastoja mitä työpajassa tarvitaan.

Tämä `README.md` tiedosto on yleinen GitHubissa käytetty tiedosto jossa kerrotaan repositorystä, joten työpajasi repositoryssä voit laittaa tähän tiedostoon perustiotoja ja kuvaksen pajasta.

Työkaliua [junior-binderhub.aalto.fi](https://junior-binderhub.aalto.fi/) voi myös käyttää binder linkin tekemiseen, mutta tälle ei ole tarvetta.
