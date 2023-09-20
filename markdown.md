


<h1 style="color:#a9e8d2; font-size: 70px;">Digitale Ära & Echtzeitkommunikation</h1>

<section>
</section>

<section>
Unverzichtbare Bedeutung in der heutigen Zeit
</section>

<section>
Zügiger Informationsaustausch zwischen Schülern und Lehrern
</section>

<section>
Marktdominanz durch große Unternehmen
</section>

<section>
Amerikanische Firmen mit proprietärer Software
</section>

<section>
WhatsApp, Telegram, Discord
</section>

---


<h1 style="color:#a9e8d2; font-size: 80px;">Technologie</h1>

<section>
</section>

<section>
Relevante Alternative zu bestehenden Lösungen
</section>

<section>
Performance auf hohem Niveau
</section>
<section>
Hohe Sicherheitsstandards
</section>

<section>
Zeitgemäßes und benutzerfreundliches Design
</section>

<section>
Einsatz neuester Technologien
</section>

<section>
Zukunftsichere Lösung
</section>

---

<h1 style="color:#a9e8d2; font-size: 70px;">Überblick</h1>

- design
- user authentication
- session context
- endpoints
- realtime socketio
- datenbank



---



<h1 style="color:#a9e8d2; font-size: 150px;">Frontend</h1>

---

<img src="./images/mainpage.png">

---

## Design

 <div style="display: flex; justify-content: space-between; align-items: center; gap:40px;">
    <div>
        <img src="./images/figma.png" />
    </div>
    <ul style="width: 80%;" >
      <li style="margin-bottom:10px">Ansprechendes modernes Design.</li>
        <li style="margin-bottom:10px">Ermutigt effiziente Kommunikation.</li>
        <li style="margin-bottom:10px">Responsive und Layouts. </li>
        <li style="margin-bottom:10px">Prototypen in Figma erstellt</li>
    </ul>
</div>


---

### Login


<div style="display: flex; justify-content: space-between; align-items: center;">
    <ul style="width: 70%;" >
        <li>Email + Passwort</li>
        <br />
        <li>Globaler sessionContext</li>
        <br />
        <li>Error handling</li>
        <br />
    </ul>
    <div>
        <img src="./images/login.png" />
    </div>
</div>

---
### Chat

<div style="display: flex; justify-content: space-between; align-items: center;">
    <div>
        <img src="./images/Chat.png" />
    </div>
    <ul style="width: 70%;" >
        <li>Live Update</li>
        <br />
        <li>Funktionaler Input</li>
        <br />
        <li>Dynamische Images</li>
        <br />
    </ul>
</div>

---

### Navigation

<div style="display: flex; justify-content: space-between; align-items: center;">
    <ul style="width: 70%;" >
        <li>Guppen und Direkt</li>
        <br />
        <li>Funktionsbutton</li>
        <br />
        <li>New Chat Funktion</li>
        <br />
    </ul>
    <div style="display: flex; gap: 20px;" >
        <img style="max-height: 75vh"  src="./images/sidebar.png" />
        <img style="max-height: 75vh"  src="./images/newChat.png" />
    </div>
</div>

---

### Profile

<div style="display: flex; justify-content: space-between; align-items: center; gap: 50px;">
    <div>
        <img style="max-height: 75vh"  src="./images/profile.png" />
    </div>
    <ul style="width: 70%;" >
        <li>Profilbild  ändern</li>
        <br />
        <li>Passwort ändern</li>
        <br />
        <li>Andere Profile einsehen</li>
        <br />
    </ul>
</div>

---

---



<h1 style="color:#a9e8d2; font-size: 160px;">Backend</h1>

---

## Daten Management

<div style="display: flex; justify-content: space-between; align-items: center; gap:40px;">
    <div>
        <img src="./images/backend_start.png" />
    </div>
    <ul style="width: 80%;" >
      <li style="margin-bottom:10px">Daten werden aus JSON-Datei eingelesen</li>
        <li style="margin-bottom:10px">Passwörter werden gehasht</li>
    </ul>
</div>

---
### Benutzerauthentifizierung

<section>
</section>
<section>
<img style="height: 500px; width: 500px;" src="./images/express-session.webp"/>
</section>



<section>

<ul style="width: 80%;" >
    <li style="margin-bottom:10px">Authentifizierungsstatus & Benutzerinformationen</li>
    <li style="margin-bottom:10px">express-session als middleware</li>
    <li style="margin-bottom:10px">Session-Daten serverseitig gespeichert</li>
</ul>
</section>

<section>
<video style="height: 800px; width: 900px;" data-autoplay src="./images/demonstrate_session.mp4"></video>
</section>

---

## Endpoints

 
<ul style="width: 80%;" >
<li style="margin-bottom:10px">Frontend sendet Anfragen</li>
<li style="margin-bottom:10px">Backend als RESTful API</li>
<li style="margin-bottom:10px">Einfache Erweiterung und Skalierung der Applikation</li>
</ul>

<img src="./images/endpoint.png" />

---

## Socket.io

<div style="display: flex; justify-content: space-between; align-items: center; gap:40px;">
    <div>
        <img style="height: 400px; width: 1000px;" src="./images/sockets.png" />
    </div>
</div>
Socket.io informiert Teilnehmer

---

## Datenbank

<div style="display: flex; justify-content: space-between; align-items: center; gap:40px;">
    <div>
        <img src="" />
    </div>
    <ul style="width: 80%;" >
      <li style="margin-bottom:10px">Robustes relationales Datenbankmanagementsystem</li>
      <li style="margin-bottom:10px">Sichere Speicherung von Benutzerdaten und Nachrichten</li>
      <li style="margin-bottom:10px">Gewährleistung von Datenkonsistenz und Zuverlässigkeit</li>
    </ul>
</div>



<!-- <h1 style="color:rgb(47, 178, 143); font-size: 60px;">Zusammenfassung</h1>


<section>
    <ul>
        <li>Umfassendes schulisches Kommunikationsnetzwerk</li>
        <li>Benutzerzentriertes Design</li>
        <li>Robuste Authentifizierung</li>
        <li>Effizientes Sitzungsmanagement</li>
        <li>Klare Endpunkte</li>
        <li>Skalierbare Plattform</li>
    </ul>
</section> -->
