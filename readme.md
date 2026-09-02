Flexbox

Flexbox passar bra för mina aktivitetskort eftersom korten ska ligga i en riktning.

I koden använder jag display: flex på (containern) .kort-rad. Korten blir flex-items och gap skapar mellanrum mellan korten. Jag använder också flex-wrap så att korten kan flytta till en ny rad på en smal skärm.

Grid används för layout med rader och kolumner samtidigt. Jag använde inte Grid idag eftersom mina kort bara behöver en riktning.

<!--<section>
  <div style="display: flex;">
    <div class="card" style="display: flex">Workshop</div>
    <div class="card">Fika</div>
    <div class="card">Brädspel</div>
  </div>
</section>

.card {
  margin: 20px;
}-->

 Feedback

FEEDBACK 1: Stylingen finns i HTML-filen. Stylingen ska vara i en extern style.css fil och länkas till HTML med tag link.
.

FEEDBACK 2: Korten är skrivna med div, och avståndet mellan dem skapas med margin: 20px så det är bättre att använda article för varje kort och gap på (containern).


FEEDBACK 3: Använd inte display: flex på varje .card. Flexbox passar bättre på containern inte på varje kort.


