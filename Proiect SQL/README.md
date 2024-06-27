# Proiect-Practic-Bază de Date

<p>Pentru realizarea părții practice am ales crearea unei baze de date în MySQL. Pentru acest lucru a fost nevoie să instalez MySQL Workbench și MySQL Server. Deși în cazul meu nu a fost nevoie, în unele situații, o precondiție de instalare este existența Visual Studio C++ pe localul unde se dorește a se instala MySQL.</p>
    <h2>Instalare</h2>
    <p>Am folosit linkurile de mai jos pentru instalare:</p>
    <ul>
        <li><a href="https://visualstudio.microsoft.com/downloads/">Visual Studio</a></li>
        <li><a href="https://dev.mysql.com/downloads/workbench/">MySQL Workbench</a></li>
        <li><a href="https://download.cnet.com/MySQL-Database-Server/3000-10254_4-10585640.html">MySQL Database Server</a></li>
    </ul>
    <h2>Despre MySQL Workbench și MySQL Server</h2>
    <p>MySQL Workbench este o aplicație client dezvoltată de MySQL. Aceasta oferă o interfață grafică pentru gestionarea și administrarea bazelor de date MySQL (o aplicație client care permite utilizatorilor să interacționeze cu baza de date MySQL într-un mod mai ușor și mai vizual).</p>
    <p>MySQL Server reprezintă nucleul bazei de date MySQL. Este programul principal care gestionează stocarea și accesul la datele din baza de date (o componentă server care rulează baza de date).</p>
      <h2>Pași de Instalare</h2>
    
<p>Instalarea MySQL Workbench</p>
    <ol>
        <li>Descărcați MySQL Workbench aferent sistemului de operare utilizat, fără a fi nevoie să vă creați cont.</li>
        <li>Urmați pașii de instalare și debifați opțiunea “Launch Mysql Workbench now”, apoi click pe Finish.</li>
    </ol>
    
<p>Instalarea MySQL Server</p>
    <ol>
        <li>Click pe Downloads din meniul din partea de jos, și apoi pe MySQL Community (GPL) Downloads »;</li>
        <li>Am selectat din lista de downloads MySQL Community Server.</li>
        <li>Click pe imaginea pe care scrie MySQL Installer.</li>
        <li>Click pe primul link de download care apare.</li>
        <li>In fereastra care se deschide click pe “No thanks, just start my download”.</li>
    </ol>
    <p>După finalizarea descărcării aplicației, am deschis-o pentru a începe instalarea:</p>
    <ul>
        <li>Am selectat NO în popup-ul care întreaba de updates;</li>
        <li>În fereastra care se deschide:
            <ul>
                <li>Click pe plus-ul de lângă MySQL Servers, apoi pe cel de lângă MySQL Server, apoi pe cel de lângă opțiunea MySQL 8.0;</li>
                <li>Click pe ultima versiune disponibilă, apoi click pe săgețica verde;</li>
                <li>Click pe Next, apoi pe Execute, după care Next de cinci ori consecutiv;</li>
                <li>În fereastra care se deschide am definit o parolă și am apăsat Next, apoi Execute; La final click pe Next și apoi pe Finish.</li>
            </ul>
        </li>
    </ul>
    <h3>Începerea Proiectului în MySQL</h3>
    <p>Pentru începerea proiectului în MySQL am deschis MySQL Workbench-ul și m-am conectat la Serverul MySQL.</p>
    


    
  

    

<p>Cu ajutorul instrucțiunilor DDL și DML am creat și inserat datele în baza de date ”Spital”, cu trei tabele denumite <em>Pacienți</em> (care conține datele personale ale pacienților), <em>Medici</em> (conține informații despre medicii curanți ai pacienților) și <em>Internări</em> (în care apar informații despre spitalizarea pacienților).</p>
<p></p><img width="155" alt="Picture2" src="https://github.com/haeti/Proiect-SQL/assets/133394777/8de8724a-2bec-4786-9c1b-7014e8c5ce1f"></p>

<p></p><img width="353" alt="Picture3" src="https://github.com/haeti/Proiect-SQL/assets/133394777/f5db8852-6e1f-4c33-9a7a-a670c0a28c02"></p>

<p></p><img width="468" alt="Picture4" src="https://github.com/haeti/Proiect-SQL/assets/133394777/32b0865d-f9e8-4cf9-a76a-a19e8252fad8"></p>

<p><img width="468" alt="Picture5" src="https://github.com/haeti/Proiect-SQL/assets/133394777/e260d200-69e9-4ea8-bb1e-8a4455c645a6"></p>

<p><img width="416" alt="Picture6" src="https://github.com/haeti/Proiect-SQL/assets/133394777/37c97b77-5c98-416e-b086-4351d3129682"></p>
<p></p><img width="468" alt="Picture7" src="https://github.com/haeti/Proiect-SQL/assets/133394777/c1d3c17f-a94f-407c-9c3e-2811b51b237f"></p>

<p><li>Aici am updatat genul unuia dintre pacienti (din F in M) fiind introdus gresit initial: 
Coloana “gen”, pacientul cu id-ul nr.7:</li></p>

<p> <img width="463" alt="Picture8" src="https://github.com/haeti/Proiect-SQL/assets/133394777/1b107685-beba-4d81-9be6-427585d74866"></p>
<p><li>Folosind instructiunea “Alter” am adaugat inca o coloana tabelei “Internari”:</li></p>
<img width="430" alt="Picture9" src="https://github.com/haeti/Proiect-SQL/assets/133394777/0a157fc3-8e0d-448c-bc1b-81abdcb51f91">

<p><li>Si apoi cu instructiunea “Update” am populat si aceasta noua coloana “Salon_internare”:</li></p>
<p><img width="468" alt="Picture10" src="https://github.com/haeti/Proiect-SQL/assets/133394777/e5322481-3ae2-4b61-abbc-33ba3731859f"></p>
<p><li>Stergerea coloanei “Adresa” din tabela “Pacienti”:</li></p>
<p><img width="468" alt="Picture11" src="https://github.com/haeti/Proiect-SQL/assets/133394777/5af16728-b158-405f-8dc1-3a8dd3bae357"></p>
<p><li>Stergerea unei inregistrari de internare din tabela “internari”:</li></p>
<p><img width="468" alt="Picture12" src="https://github.com/haeti/Proiect-SQL/assets/133394777/6c438e6f-c3d0-4be0-85b4-e38009dae4f2"></p>
<h4>Instructiuni DQL:</h4>
<p><li>Selectarea tuturor pacientilor:</li></p>
<p></p><img width="375" alt="Picture13" src="https://github.com/haeti/Proiect-SQL/assets/133394777/00fa41ef-6a3e-437d-bd11-2db08989a22f"></p>
<p><li>Selectarea catorva coloane:</li></p>
<p></p><img width="297" alt="Picture14" src="https://github.com/haeti/Proiect-SQL/assets/133394777/b04ac53a-1a93-4ec8-92f2-6474d4144ee7"></p>
<p><li>Filtrarea cu “where” : am vrut sa vad cati pacienti internati in ziua de 10 au fost in salonul  nr 2:</li></p>
<p></p><img width="468" alt="Picture15" src="https://github.com/haeti/Proiect-SQL/assets/133394777/0d428fc2-eb35-47df-ac31-6e30dc5d0bff"></p>
<p><li>Filtrare cu AND si OR: am cerut sistemului sa imi arate toti pacientii de gen “M” nascuti inainte de 1990:</li></p>
<p></p><img width="468" alt="Picture16" src="https://github.com/haeti/Proiect-SQL/assets/133394777/16201fa6-e486-479e-be2d-674d07fb2f84"></p>
<p><li>Am cerut sistemului sa imi arate medicii care au ca specializare “cardiologie” sau “ortopedie”:</li></p>
<p><img width="468" alt="Picture17" src="https://github.com/haeti/Proiect-SQL/assets/133394777/7ff1e72f-e184-4123-9b1b-ff7fad17a082"></p>
<p><li>Functii agregate: am cerut sistemului sa imi arate nr total de pacienti:</li></p>
<p><img width="371" alt="1" src="https://github.com/haeti/Proiect-SQL/assets/133394777/652c67f3-b8dd-4d82-a2e5-979cbe1f1ac8"></p>
<p><li>Filtrare pe functii agregate: am cerut sistemului sa imi arate nr de medici per specializare:</li></p>
<p><img width="515" alt="2" src="https://github.com/haeti/Proiect-SQL/assets/133394777/29fb90bc-1b24-429c-b27e-91291a4f27a4"></p>

<h4>JOINS</h4>

<p><li>Inner join pentru a vedea medicii si pacientii pe care ii trateaza:</li></p>
<p><img width="468" alt="Picture20" src="https://github.com/haeti/Proiect-SQL/assets/133394777/2afbc869-4b14-44c9-8804-e78dff3abef5"></p>
<p><li>Left join:</li></p>
<p><img width="468" alt="Picture21" src="https://github.com/haeti/Proiect-SQL/assets/133394777/74684dc4-089f-407d-9ea2-5ead23f52d83"></p>
<p><li>Right join:</li></p>
<p></p><img width="468" alt="Picture22" src="https://github.com/haeti/Proiect-SQL/assets/133394777/5e503d63-8e2b-4a64-a53e-92bb3ede248f"></p>
<p><li>Cross join:</li></p>
<p><img width="468" alt="Picture23" src="https://github.com/haeti/Proiect-SQL/assets/133394777/78349cc6-9e5c-4cbf-8e12-e20100a92d25">
<img width="468" alt="Picture24" src="https://github.com/haeti/Proiect-SQL/assets/133394777/50ae97c6-0266-47bc-a66a-92ef85575a00">
<img width="458" alt="Picture25" src="https://github.com/haeti/Proiect-SQL/assets/133394777/692146d3-b08f-402d-96ed-2a3e525d7665"></p>
<p><li>Inner join cu limitare la primele 4 inregistrari:</li></p>
<p><img width="468" alt="Picture26" src="https://github.com/haeti/Proiect-SQL/assets/133394777/04518cc8-f3b4-46b6-8455-1eb6324ef56e"></p>
<p><li>Left join cu limitare la primele 5 inregistrari:</li></p>
<p><img width="468" alt="Picture27" src="https://github.com/haeti/Proiect-SQL/assets/133394777/7f99b0ed-8192-42e9-82be-064da9e9ce06"></p>
<p><li>Right join cu afisarea primelor 6 inregistrari:</li></p>
<p><img width="468" alt="Picture28" src="https://github.com/haeti/Proiect-SQL/assets/133394777/f91f0f4b-b1dc-4ded-a7b1-a82e6295cc6e"></p>
<p><li>Cross join cu limitare la primele 8 inregistrari:</li></p>
<img width="468" alt="Picture29" src="https://github.com/haeti/Proiect-SQL/assets/133394777/fb5ab0cb-9c38-4b82-966c-f6bfbe2d0947">
<p><li>Ordonarea pacientilor dupa data nasterii:</li></p>
<p><img width="361" alt="Picture30" src="https://github.com/haeti/Proiect-SQL/assets/133394777/ffe15d06-5f25-4f2f-bf6d-15fb63034429"></p>
<p><li>Subquery pentru a gasi pacientii internati de un anume medic:</li></p>
<p><img width="468" alt="Picture31" src="https://github.com/haeti/Proiect-SQL/assets/133394777/33a06080-4873-44ff-852d-7d17b3b47740"></p>
<p><li>Subquery pentru a gasi numele medicilor care au tratat pacienti:</li></p>
<p><img width="468" alt="Picture32" src="https://github.com/haeti/Proiect-SQL/assets/133394777/3bf538f5-b7a9-49c5-aea5-29689379e5c7"></p>
<h4>CHEI PRIMARE SI SECUNDARE; RELATII INTRE TABELE</h4>
<p><img width="468" alt="Picture33" src="https://github.com/haeti/Proiect-SQL/assets/133394777/d44f5c65-9a40-4f1f-a88d-a35d9e5ebb87"></p>
Reprezentarea grafică a tabelelor și a  relațiilor dintre ele


<h3>Cheile primare:</h3>
<p>În fiecare dintre cele trei tabele am definit câte o cheie primară:</p>
<ul>
    <li>în tabela <em>pacienți</em> cheia primară este <strong>id_pacient</strong> care identifică în mod unic fiecare pacient;</li>
    <li>în tabela <em>medici</em>, coloana <strong>id_medic</strong> identifică în mod unic fiecare medic;</li>
    <li>în tabela <em>internări</em> coloana <strong>id_internare</strong> identifică în mod unic fiecare înregistrare de internare.</li>
</ul>

<h3>Cheile secundare:</h3>
<p>Două dintre cheile primare joacă rol de chei secundare pentru tabela <em>internări</em>:</p>
<ul>
    <li>coloana <strong>id_pacient</strong> face referire la coloana <strong>id_pacient</strong> din tabela <em>pacienți</em>, stabilind relația dintre internări și pacienți;</li>
    <li>coloana <strong>id_medic</strong> în tabela <em>internări</em> face referire la coloana <strong>id_medic</strong> din tabelul <em>medici</em>, creând relația dintre internări și medici.</li>
</ul>

<p>Relația dintre tabelele <em>pacienți</em> și <em>internări</em> este o relație de tipul 1:n (one to many) deoarece un pacient (identificat ca <em>pacienți.id_pacient</em>) poate avea mai multe internări (<em>internări.id_pacient</em>).</p>

<p>Iar relația dintre tabelele <em>medici</em> și <em>internări</em> este tot 1:n deoarece un medic (<em>medici.id_medic</em>) poate cere multiple internări (<em>internari.id_medic</em>) pentru pacienții pe care îi tratează.</p>

<p>În concluzie, tabelul <em>internări</em> servește ca tabel intermediar care leagă tabelele <em>pacienți</em> și <em>medici</em> prin intermediul cheilor secundare <strong>id_pacient</strong> și <strong>id_medic</strong>.</p>








