# Proiect-Practic-Bază de Date

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
<p></p><img width="368" alt="Picture18" src="https://github.com/haeti/Proiect-SQL/assets/133394777/6fd9741e-e8e1-4ebb-9853-fd28aab7f429"></p>
<p><li>Filtrare pe functii agregate: am cerut sistemului sa imi arate nr de medici per specializare:</li></p>
<p></p><img width="468" alt="Picture19" src="https://github.com/haeti/Proiect-SQL/assets/133394777/8d9b7b57-934a-40ac-ac7b-f210b089ea06"></p>
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








