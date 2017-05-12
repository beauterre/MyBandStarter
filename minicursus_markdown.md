 # Minicursus MarkDown Schrijven

Markdown is een veilig alternatief voor HTML en wordt gebruikt door Wiki's en Github. Markdown maakt gebruik van 'platte tekst', waardoor het minder gevoelig is voor XSS-attacks.
Als je je gebruikers de ruimte wilt geven om opmaak te gebruiken, is het goed om te overwegen markdown ook in je eigen projecten te gebruiken ivm veiligheid (markdown kan minder goed script gebruiken, wil je alles weten over deze aanvallen voorkomen: zie onderste link! )

---

`__vet__` geeft 
__vet__

---

`_schuin_` geeft 
_schuin_

---

`# Kop 1` geeft
# Kop 1
---
`## Kop 2`
## Kop 2
---
`### Kop 3`
### Kop 3
---
`* test`
`* test` geeft

* test
* test

Vergeet niet de spaties!

---

`> Quote or inset` geeft
> Quote or inset

---

`![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")` geeft

![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

---

etc.. 

Zie voor meer markdown mogelijkheden hieronder of open gewoon de markdown files op deze github.

> Let op: github ondersteund minder features van MD dan Dillinger.
> Als je schrijft voor Github, hou daar dan rekening mee.
> Je kunt met Preview kijken of het goed gaat.

Overigens zijn zowel deze minicursus, de wiki markdown en de markdown cheatsheet geschreven in markdown.
Geef wel aan hoe krachtig het toch kan zijn.
Het is de voertaal voor open source projecten.

# resources

* https://nl.wikipedia.org/wiki/Markdown
* <https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet>
* Editor online:  <http://dillinger.io/>
* Wysiwyg editor online: <https://simplemde.com/>
*Veilig zijn bij het gebruiken van Markdown. <https://github.com/showdownjs/showdown/wiki/Markdown's-XSS-Vulnerability-(and-how-to-mitigate-it)>
