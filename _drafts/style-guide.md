===== Blog =====
- Site: https://prudento-nl.github.io/2017-09-frankrijk/
- GitHub posts: https://github.com/Prudento-NL/2017-09-frankrijk/tree/master/_posts

===== Format posts =====
---
layout: post
title: Het aftellen is begonnen!
date: 2017-08-20
---
Tekst

===== Format file name =====
- YEAR-MONTH-DAY-title.md
- 2011-12-31-new-years-eve-is-awesome.md

===== URL =====
Indien verwezen wordt naar directories waarin documenten of images staan.
Toevoegen in _config.yml
URL: "https://prudento-nl.github.io/2017-09-frankrijk"
images: "https://prudento-nl.github.io/2017-09-frankrijk/images"

===== Comments =====
<!--- commentaar --->

===== Handig =====
Graden teken °: Ctrl+Shift and type u+00b0

===== Links =====
- alles in de tekst
  [Jekyll](http://jekyllrb.com/)
- In de tekst de verwijzing tussen rechte haken en onderaan de blog de verwijzing zoals in Jekyll WERKT NIET IN GITHUB.

===== Images =====
- Maak een directory voor de images. LET OP! De URL moet toegevoegd worden aan_config.yml.
- File namen zonder spaties bijvoorbeeld dag1a.jpg, dag1b.jpg, etcetera

> > > > > > DIT WERKT:
![Kasteel]({{ site.images }}/dag7.jpg?raw=true)
--------------------------------------------
- Image uit een directory bijvoorbeeld ‘Images’:
  ![Je eigen tekst]({{ site.url }}/directory/filenaam.jpg)
  Voorbeeld ![Dulfer]({{ site.url }}/images/dulfer.jpg)
- Image op een website:
  ![Je eigen tekst](Hyperlink)
  Voorbeeld ![Mickey](https://forum.nl.forgeofempires.com/index.php?attachments/glitter_krabbel_plaatje_003-gif.881/)

===== Image met link naar eigen directory =====
- Ga naar de Image folder
- Klik op het gewenste bestand >> Het plaatje opent.
- Links klik op het plaatje en kopieer de link (copy image address)
- https://github.com/Prudento-NL/test/blob/master/images/mickey.jpg?raw=true
- Plak de volledige link in het deel waar het plaatje staat (achter img src)
  <a href="http://www.prudento.nl/">
    <img src="https://github.com/Prudento-NL/test/blob/master/images/mickey.jpg?raw=true">
  </a>

===== Image met link naar een externe locatie  ======
<a href="https://meta.stackoverflow.com/users/44330/jason-s">
 <img src="https://www.gravatar.com/avatar/dd5a7ef1476fb01998a215b1642dfd07?s=128&d=identicon&r=PG">
</a>

===== Resize =====
Bij mobiel: gebruik fotoresizer
- resize naar format 800x600

===== Referenties =====

- Markdown (GFM): https://guides.github.com/features/mastering-markdown/
