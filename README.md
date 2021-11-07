Jest oprogramowanie typu *open source* służące do konwertowania dokumentów pomi>

Pod poniższym linkiem można obejrzeć przykłady użycia:

https://pandoc.org/demos.html

Oprogramowanie to można pobrać z spod adresu: https://pandoc.org/installing.html

Jeżei chcemy konwertować do formatu *latex* i *pdf* trzeba doinstalować oprogra>

Gdyby podczas konwersji do formatu pdf pojawił się komunikat o niemożliwości zn>


Pod adresem (*http://gitlab.com/mniewins66/templatemn.git*) znajduje się
przykładowy plik Markdown z którego można wygenerować prezentację w
formacie *pdf* wykorzystując klasę latexa *beamer*.

W tym celu należy wydać polecenie z poziomu terminala:

```$pandoc templateMN.md -t beamer -o prezentacja.pdf```
