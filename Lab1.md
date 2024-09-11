# Laborator 1: Crearea unei aplicații simple de gestionare a notițelor (To-Do List)

## Descriere
Acest laborator este destinat creării unei aplicații simple pentru gestionarea sarcinilor (**To-Do List**). Aplicația va permite utilizatorilor să adauge, să editeze și să elimine sarcini.

## Checkpointuri

### **Checkpoint 1: Crearea interfeței de utilizator (UI)**

- Designul paginii principale care va afișa lista de sarcini.
- Adăugarea unui formular pentru a introduce o sarcină nouă (câmpuri text pentru titlu și descriere).
- Implementarea unui buton pentru adăugarea sarcinii în listă.

**Scop:** Studenții trebuie să creeze o interfață simplă, user-friendly, și să asigure navigarea corectă între pagini.

---

### **Checkpoint 2: Gestionarea listei de sarcini**

- Implementarea funcționalității de adăugare a sarcinilor în listă.
- Afișarea sarcinilor salvate într-un format **ListView**.
- Salvarea datelor local, folosind stocarea pe dispozitiv (**SharedPreferences** sau o bază de date simplă locală).

**Scop:** Studenții trebuie să înțeleagă cum să stocheze datele într-o aplicație mobilă și să gestioneze actualizările UI în mod dinamic.

---

### **Checkpoint 3: Editarea, ștergerea sarcinilor și unit testing**

- Implementarea funcționalității pentru a edita o sarcină existentă.
- Adăugarea opțiunii de ștergere a sarcinilor din listă.
- Asigurarea persistenței datelor, astfel încât toate sarcinile să fie disponibile chiar și după ce aplicația este închisă.
- **Unit Testing:** Scrieți teste unitare pentru funcționalitățile principale (adăugare, ștergere, editare) pentru a asigura că aplicația funcționează corect.

**Scop:** Studenții trebuie să implementeze funcții de manipulare a datelor și să creeze teste unitare pentru a asigura funcționalitatea corectă a aplicației.

---

## Sarcini adiționale pentru nota 9 și 10

### **Pentru nota 9:**

1. **Bază de date SQL implementată pe internet:**
   - Implementați o bază de date SQL (de exemplu, PostgreSQL, MySQL) care să fie deploitată online (de exemplu, folosind un serviciu precum Heroku, AWS RDS, sau Azure).
   - Asigurați persistența datelor pentru sarcini într-o bază de date online, accesibilă de pe orice dispozitiv.

2. **Cache în Redis:**
   - Integrați Redis în aplicație pentru a îmbunătăți performanța. Utilizați Redis ca sistem de cache pentru datele frecvent accesate (de exemplu, lista de sarcini).

3. **Funcționalitate adițională:**
   - Adăugați o funcționalitate suplimentară, cum ar fi prioritizarea sarcinilor (ex: sarcini "urgente", "medii", "joase") sau crearea de notificări push pentru sarcini importante.

**Scop:** Studenții trebuie să demonstreze abilități avansate de integrare a bazelor de date distribuite și de optimizare a performanței aplicației folosind caching.

---

### **Pentru nota 10:**

1. **Bază de date NoSQL și dockerizare:**
   - Implementați o bază de date NoSQL (de exemplu, MongoDB) și asigurați-vă că aplicația este dockerizată, astfel încât să poată fi rulată într-un container. 
   - Creați un fișier `Dockerfile` și un `docker-compose.yml` pentru a facilita rularea aplicației și a bazei de date în containere separate.

2. **Distribuirea bazei de date și Load Balancing (RabbitMQ sau Round Robin):**
   - Implementați un sistem de distribuire a bazei de date folosind RabbitMQ pentru gestionarea mesajelor sau un algoritm de Load Balancing (ex: Round Robin).
   - Asigurați scalabilitatea aplicației prin distribuirea sarcinilor între servere/baze de date.

**Scop:** Studenții trebuie să demonstreze o înțelegere profundă a arhitecturii distribuite și a scalabilității aplicațiilor web moderne, folosind tehnologii avansate precum Docker, RabbitMQ și baze de date NoSQL.

---

## Concluzie:
La finalul acestui laborator, studenții vor avea o aplicație simplă și funcțională pentru gestionarea sarcinilor zilnice, cu opțiuni de adăugare, editare și ștergere, și cu persistența datelor. Cei care vor implementa sarcinile adiționale vor demonstra cunoștințe avansate în gestionarea bazelor de date și scalabilitate.

