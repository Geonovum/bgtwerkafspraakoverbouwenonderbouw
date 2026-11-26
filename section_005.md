
# Afbakeningsregels van registratie van overbouw en onderbouw {#792BF0F2}
Delen van panden die zich boven maaiveld bevinden (overbouw):   
<ol type='1'><li>De geometrie van overbouw van een pand wordt in de BGT vastgelegd met het objecttype Pand en een relatieve hoogte &gt; 0.</li>
<li>Een overbouw kan alleen voorkomen als er ook een pand met dezelfde BAG-identificatie op maaiveld (relatieve hoogte is 0) aanwezig is, met uitzondering van de in paragraaf 10.7.1 van de catalogus BGT 2.1 genoemde uitzonderingen. Zie voorbeeld A in de Bijlage.</li>
<li>Alleen de uítstekende delen - uítstekend ten opzichte van maaiveld - van de overbouw worden afgebakend (zoals uitkragende delen van panden);</li>
<li>De geometrie van uítstekende delen (zoals verblijfsruimtes hangend boven maaiveld) krijgen een relatieve hoogte &gt; 0, zoveel mogelijk in overeenstemming met de werkelijke situatie.</li>
<li>Meerdere overbouwen met dezelfde relatieve hoogte &gt; 0 die bij één BGT pand horen op maaiveld (d.w.z. met eenzelfde BAG-identificatie) worden vastgelegd als afzonderlijke BGT panden met dezelfde relatieve hoogte &gt; 0 (dus niet als multi-geometrie);</li>
<li>Overlapping is alleen toegestaan tussen geometrieën van overbouw met verschillende relatieve hoogte; er is geen overlap toegestaan tussen geometrieën van overbouw met gelijke relatieve hoogte.</li>
<li>Niet betreedbare kolommen op maaiveld worden niet uitgesneden in de geometrie van de overbouw.</li>
</ol>
<br/>
<br/>
Delen van panden die zich onder maaiveld bevinden (onderbouw):  
<br/>
<br/>
<ol type='1'><li>De geometrie van onderbouw van een pand wordt in de BGT vastgelegd met het objecttype Pand en een relatieve hoogte &lt; 0.</li>
<li>Een onderbouw kan alleen voorkomen als er ook een pand met dezelfde BAG-identificatie op maaiveld (met relatieve hoogte = 0), aanwezig is.</li>
<li>Geheel ondergrondse panden, - die niet horen bij een  pand op maaiveld, met status bestaand én met dezelfde BAG-identificatie -, zijn geen onderbouw. Ze worden met een relatieve hoogte &lt; 0 vastgelegd  en zijn daarmee een uitzondering op de regel dat panden altijd op maaiveld liggen, net als bv brugwachterhuisjes ook een uitzondering zijn. Zie voorbeeld C in de bijlage.</li>
<li>Alleen de uítstekende delen - uítstekend ten opzichte van maaiveld - van de onderbouw worden afgebakend (zoals uitkragende delen van panden);</li>
<li>De geometrie van uítstekende delen (zoals kelders of inpandige parkeergarages) krijgen een relatieve hoogte &lt; 0, zoveel mogelijk in overeenstemming met de werkelijke situatie.</li>
<li>Meerdere onderbouwen met dezelfde relatieve hoogte &lt; 0 die bij één BGT pand horen op maaiveld (d.w.z. met eenzelfde BAG-identificatie) worden vastgelegd als afzonderlijke BGT panden met dezelfde relatieve hoogte &lt; 0  (dus niet als multi-geometrie);</li>
<li>Overlapping is alleen toegestaan tussen geometrieën van onderbouw met verschillende relatieve hoogte; er is geen overlap toegestaan tussen geometrieën van onderbouw met gelijke relatieve hoogte.</li>
<li>Als één BAG pand ondergrondse delen (bijvoorbeeld parkeerkelder) én bovengrondse delen (bijvoorbeeld ingangen/trappenhuisjes/liften/ etc.) heeft (die niet als afzonderlijk BAG pand(en) zijn benoemd), dan worden:<ul><li>    De  bovengrondse delen als BGT pand op maaiveld vastgelegd (multivlak als het meerdere losse delen zijn)</li>
<li>    Het ondergrondse deel wordt vastgelegd als onderbouw, met hetzelfde BAG-identificatie, waarbij alleen de uítstekende delen van de geometrie worden opgenomen(d.w.z. dat de ingangen/trappenhuisjes/liften/ etc. uitgesneden worden in de geometrie van de onderbouw). Zie voorbeeld B.</li>
</ul>
</li>
<li>Niet betreedbare kolommen op maaiveld worden niet uitgesneden in de geometrie van de onderbouw.</li>
</ol>
<br/>
<br/>
Panden op maaiveld:  
<br/>
<br/>
<ol type='1'><li>Geometrie van panden op maaiveld blijven op relatieve hoogte = 0 en de afzonderlijke geometrieën vormen samen een multi-vlak.</li>
</ol>
<br/>
<br/>
Totale pand:  
<br/>
<br/>
<ol type='1'><li>De samengestelde 2D-projectie van alle geometrieën van het BGT pand bij elkaar, waarbij onderlinge overlap is geëlimineerd, is topologisch aangesloten én is gelijk aan de BAG geometrie van dat pand.</li>
<li>Van de BGT panden met dezelfde BAG-identificatie mag maar één BGT pand de volledige nummeraanduidingsreeks (NAR) krijgen, die gerelateerd is aan dat BAG-pand. Deze NAR wordt geplaatst in een BGT pand (met status = bestaand) met een relatieve hoogte = 0. Voor een geheel ondergronds pand met relatieve hoogte &lt; 0 wordt de NAR in dat pand geplaatst.</li>
</ol>
