# template-vakantie-blog
Template for creating blogs for holidays.

## Setup een nieuwe new_repo
### Maak een nieuwe repo en import de template files
- Maak een nieuwe repo in GitHub zonder README en gitignore file
- Import de code van de template met de quick setup
  - Quick set up opent nadat je de nieuwe repo hebt gemaakt zonder readme en gitignore
  - Onderaan staat import
  - Kopieer en plak de link van de template
  - Wacht totdat GitHub meldt _Importing complete!_
- Clone de nieuwe repo naar lokaal  
  `git clone github-url-new-repo`

### Verwijder de history van de template
  - Verwijder de .git folder  
    `rm -rf .git`
  - Creëer een nieuwe .git folder  
    `git init`
  - Stage de files en folders  
    `git add .`  
    `git commit -m "Initial commit"`
  - Push naar de nieuwe new_repo  
    `git remote add origin <github-url-new-repo>`  
    `git push -u --force origin master`

### Aanpassen files
- .config.yml
  - title
  - description
  - URL GitHub repo
  - URL folder location
- README
  - edit tekst
- about.md
  - edit tekst

### Aanwijzigen voor gebruik:
- In de drafts-folder staat:
  - een template voor de posts
  - de style-guide met handige info
- er staat een file in de folders _posts_ en _images_ om er voor te zorgen dat de folder in GitHub aanwezig is. De files kunnen verwijderd worden als er een post of image aan de betreffende folder is toegevoegd.
