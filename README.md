# Aplicație Marketplace Online

Această aplicație Django permite utilizatorilor să interacționeze cu un marketplace online, având posibilitatea de a-și crea un cont, a se loga, a adăuga produse și a comunica cu vânzătorii.

## Funcționalități

- **Creare cont**: Utilizatorii își pot crea un cont pentru a accesa funcționalitățile aplicației.
- **Logare**: Utilizatorii se pot loga în contul lor pentru a gestiona produsele și mesajele.
- **Adăugare produse**: Utilizatorii pot adăuga produse în marketplace.
- **Editare produse**: Utilizatorii pot edita informațiile despre produsele lor.
- **Mesaje**: Utilizatorii pot schimba mesaje cu vânzătorii pentru întrebări și negocieri.


## Cerințe

- Python 3.x
- Django
- Pachetul `requirements.txt` pentru instalarea dependențelor

## Instalare

Pentru a utiliza aplicația:

1. Clonează repository-ul într-un mediu virtual compatibil cu Python.
2. Instalează dependențele din terminal folosind comanda:

   ```bash
   pip install -r requirements.txt

3. Navighează în directorul proiectului:

    ```bash
    cd online-market-place 

4. Creează un mediu virtual:

    '''bash 
    python -m venv venv

5. Activează mediul virtual:

- Pe Windows:

    '''bash
    venv\Scripts\activate

- Pe macOS/Linux:

    '''bash
    source venv/bin/activate

6. Instalează dependențele:

    '''bash
    pip install -r requirements.txt

7. Aplică migrațiile bazei de date:

    '''bash
    python manage.py migrate

8. Creează un superuser (opțional, pentru a accesa panoul de administrare):

    '''bash
    python manage.py createsuperuser

## Rulare Aplicație

Pentru a rula aplicația, folosește comanda:

    '''bash
    python manage.py runserver

## Accesarea Aplicației

Odată ce serverul este pornit, deschide un browser și navighează la:

    http://127.0.0.1:8000/

## Instrucțiuni pentru utilizatori

1. Creare cont: Accesează pagina de înregistrare pentru a crea un cont nou.

2. Logare: Odată ce ai un cont, loghează-te folosind datele tale.

3. Adăugare produse: După logare, poți adăuga produse folosind formularul de adăugare.

4. Mesaje cu vânzătorii: Poți accesa mesajele și răspunde la întrebările vânzătorilor din profilul tău.

5. Editare produse: Accesează lista produselor tale pentru a le edita sau șterge.
