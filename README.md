#Proiect Cloud Computing

#Aplicaţie web Astronomy Info App

Realizat de: Porcianu Andreea-Diana, grupa 1121 SIMPRE, anul 1, sem. II 

Link video - prezentare proiect https://youtu.be/-x27JiLWLnE 

Link publicare Vercel https://cc-proiect-mfa7j3ze9-porcianudiana.vercel.app/
               Github https://github.com/porcianudiana/cc-proiect

##Introducere

  Această prezentare cuprinde infomaţii despre aplicația web creată numită "Astronomy Info App". Această aplicație utilizează două servicii în cloud, baza de date MongoDB și platforma de deploy Vercel. Pentru a conecta aceste două servicii, aplicația utilizează un API REST.
Astronomy Info App este o aplicație destinată amatorilor și pasionaților de astronomie. Aceasta oferă informații despre stele, planete și alte obiecte cosmice.
  Pentru a stoca informațiile, Astronomy Info App utilizează o bază de date MongoDB. Această bază de date este scalabilă și permite accesul la informații din orice locație. Prin intermediul API-ului REST, aplicația poate accesa aceste informații și le poate afișa utilizatorilor.
  În ceea ce privește platforma de deploy, Astronomy Info App este găzduită pe Vercel. Această platformă oferă un mediu rapid și sigur pentru aplicațiile web, iar integrarea cu GitHub facilitează procesul de deploy și de actualizare a codului.
  În final, prin intermediul API-ului REST, Astronomy Info App poate comunica cu MongoDB și Vercel, permițând astfel utilizatorilor să acceseze informațiile din baza de date și să vizualizeze aplicația pe Vercel. Această aplicație este ideală pentru oricine dorește să afle mai multe despre cosmos și să exploreze misterele din univers.


##Descriere problemă
 
   Cloud computing este o tehnologie care permite utilizatorilor să acceseze și să utilizeze resurse IT (cum ar fi servere, stocare, aplicații și servicii) prin intermediul internetului, în loc să fie nevoie să le dețină și să le gestioneze în mod direct. Aplicabilitatea cloud computing este vastă și poate fi benefică pentru o gamă largă de organizații și industrii. 
  Astronomy info app este o aplicație web care oferă informații despre astronomie, cum ar fi informații despre planete, stele, galaxii și alte obiecte cerești. Pentru a furniza aceste informații, aplicația utilizează două servicii în cloud: MongoDB și Vercel.
  MongoDB este un sistem de gestionare a bazelor de date NoSQL, care permite stocarea și gestionarea datelor într-un mod scalabil și flexibil. Astronomy info app utilizează MongoDB pentru a stoca informațiile despre obiectele cerești, astfel încât acestea să poată fi accesate rapid și eficient.
 Vercel este o platformă de dezvoltare și de găzduire a aplicațiilor web, care permite dezvoltatorilor să creeze și să ruleze aplicații web rapide și scalabile. Astronomy info app utilizează Vercel pentru a gazdui aplicația și pentru a asigura o experiență de utilizare fluidă și rapidă.
  Prin utilizarea acestor două servicii în cloud, Astronomy info app beneficiază de o serie de avantaje, inclusiv:

 - Capacitatea de a crește și de a scădea resursele în funcție de nevoile utilizatorilor.
 - Capacitatea de a menține disponibilitatea aplicației în cazul unor probleme tehnice sau de mentenanță.
 - Eficiență
 - Accesibilitate

  Aplicaţia Astronomy Info App oferă posibilitatea vizitatorilor de a adăuga informaţii pe site şi de asemenea de a şterge anumite informaţii.
http://localhost:3000/
![image](https://github.com/porcianudiana/cc-proiect/assets/91715475/855e9f9e-9a0c-4c97-b96d-1b91399e3d6a)

http://localhost:3000/insert
![image](https://github.com/porcianudiana/cc-proiect/assets/91715475/1c00e1e9-d86b-47de-b48c-896db06f5f23)
 

Datele vor fi înregistrate în baza de date MongoDB la fiecare introducere.
      
##Descriere API

   API (Application Programming Interface) este un set de instrucțiuni și protocoale de comunicare care permit interacțiunea între două sau mai multe aplicații software.
În general, un API definește un set de metode de acces și operațiuni pe care le poate realiza o aplicație pentru a comunica și a interacționa cu o altă aplicație sau sistem. API-urile pot fi utilizate pentru a permite accesul la funcționalități ale altor aplicații sau pentru a integra date și servicii din diferite surse.

##Flux de date

  Exemple de request / response

  GET: http://localhost:3000/api/records?id=645ff5672599fefb0abd2f19
  ![image](https://github.com/porcianudiana/cc-proiect/assets/91715475/03bd2166-31df-4137-a1f6-a88d7278b109)
 
  GET: http://localhost:3000/api/records
  ![image](https://github.com/porcianudiana/cc-proiect/assets/91715475/ea5caf86-5b7c-4181-b817-14c65b5f45a2)
 
Metoda POST

![image](https://github.com/porcianudiana/cc-proiect/assets/91715475/d9fb2a6f-ce76-40fa-85bd-5a0a0276723f)
 
Metoda PUT

 ![image](https://github.com/porcianudiana/cc-proiect/assets/91715475/5f95a23b-5dbb-4596-9961-e0a82a880d7a)

Metoda DELETE
![image](https://github.com/porcianudiana/cc-proiect/assets/91715475/cd688025-7a27-4680-8d58-5c5f1b01f1e1)
 
 Baza de date MongoDB
 ![image](https://github.com/porcianudiana/cc-proiect/assets/91715475/b215f1fd-32b3-4184-9eff-b7ddc58d666c)

  Metodele de autentificare şi autorizări sunt cele necesare pentru conectarea la baza de date MongoDB şi se află în fişierul .env din proiect.
