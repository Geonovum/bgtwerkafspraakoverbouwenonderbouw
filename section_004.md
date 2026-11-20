
# Afbakeningsregels van registratie van overbouw en onderbouw {#792BF0F2}
<span>Delen van panden die zich boven maaiveld bevinden (overbouw): </span>  
<ol type='1'><li><span>De geometrie van overbouw van een pand wordt in de BGT vastgelegd met het objecttype Pand en een relatieve hoogte &gt; 0.</span></li>
<li><span>Een overbouw kan alleen voorkomen als er ook een pand met dezelfde BAG-identificatie op maaiveld (relatieve hoogte is 0) aanwezig is, met uitzondering van de in paragraaf 10.7.1 van de catalogus BGT 2.1 genoemde uitzonderingen. Zie voorbeeld A in de Bijlage.</span></li>
<li><span>Alleen de </span><span><u>uít</u></span><span>stekende delen - uítstekend ten opzichte van maaiveld - van de overbouw worden afgebakend (zoals uitkragende delen van panden);</span></li>
<li><span>De geometrie van </span><span><u>uít</u></span><span>stekende delen (zoals verblijfsruimtes hangend boven maaiveld) krijgen een relatieve hoogte &gt; 0, zoveel mogelijk in overeenstemming met de werkelijke situatie.</span></li>
<li><span>Meerdere overbouwen met dezelfde relatieve hoogte &gt; 0 die bij één </span><span>BGT pand</span><span> horen op maaiveld (d.w.z. met eenzelfde BAG-identificatie) worden vastgelegd als afzonderlijke BGT panden met dezelfde relatieve hoogte &gt; 0 (dus niet als </span><span>multi</span><span>-geometrie);</span></li>
<li><span>Overlapping is alleen toegestaan tussen geometrieën van overbouw met verschillende relatieve hoogte; er is geen overlap toegestaan tussen geometrieën van overbouw met gelijke relatieve hoogte.</span></li>
<li><span>Niet betreedbare kolommen op maaiveld worden niet uitgesneden in de geometrie van de overbouw.</span></li>
</ol>
<br/>
<br/>
<span>Delen van panden die zich onder maaiveld bevinden (onderbouw):</span>  
<ol type='1'><li><span>De geometrie van onderbouw van een pand wordt in de BGT vastgelegd met het objecttype Pand en een relatieve hoogte &lt; 0.</span></li>
<li><span>Een onderbouw kan alleen voorkomen als er ook een pand met dezelfde BAG-identificatie op maaiveld (met relatieve hoogte = 0), aanwezig is.</span></li>
<li><span>Geheel ondergrondse panden, - die niet horen bij </span><span>een  pand</span><span> op maaiveld, met status bestaand én met dezelfde BAG-identificatie -, zijn geen onderbouw. Ze worden met een relatieve hoogte &lt; 0 </span><span>vastgelegd  en</span><span> zijn daarmee een uitzondering op de regel dat panden altijd op maaiveld liggen, net als bv </span><span>brugwachterhuisjes</span><span> ook een uitzondering zijn. Zie voorbeeld C in de bijlage.</span></li>
<li><span>Alleen de </span><span><u>uít</u></span><span>stekende delen - uítstekend ten opzichte van maaiveld - van de onderbouw worden afgebakend (zoals uitkragende delen van panden);</span></li>
<li><span>De geometrie van uítstekende delen (zoals kelders of inpandige parkeergarages) krijgen een relatieve hoogte &lt; 0, zoveel mogelijk in overeenstemming met de werkelijke situatie.</span></li>
<li><span>Meerdere onderbouwen met dezelfde relatieve hoogte &lt; 0 die bij één </span><span>BGT pand</span><span> horen op maaiveld (d.w.z. met eenzelfde BAG-identificatie) worden vastgelegd als afzonderlijke BGT panden met dezelfde relatieve hoogte &lt; </span><span>0  (</span><span>dus niet als </span><span>multi</span><span>-geometrie);</span></li>
<li><span>Overlapping is alleen toegestaan tussen geometrieën van onderbouw met verschillende relatieve hoogte; er is geen overlap toegestaan tussen geometrieën van onderbouw met gelijke relatieve hoogte.</span></li>
<li><span>Als één BAG pand ondergrondse delen (bijvoorbeeld parkeerkelder) én bovengrondse delen (bijvoorbeeld ingangen/trappenhuisjes/liften/ etc.) heeft (die niet als afzonderlijk BAG pand(en) zijn benoemd), dan worden:</span><ul><li>    <span>De  bovengrondse</span><span> delen als </span><span>BGT pand</span><span> op maaiveld vastgelegd (multivlak als het meerdere losse delen zijn)</span></li>
<li>    <span>Het ondergrondse deel wordt vastgelegd als onderbouw, met hetzelfde BAG-identificatie, waarbij alleen de uítstekende delen van de geometrie worden </span><span>opgenomen(</span><span>d.w.z. dat de ingangen/trappenhuisjes/liften/ etc. uitgesneden worden in de geometrie van de onderbouw). Zie voorbeeld B.</span></li>
</ul>
</li>
<li><span>Niet betreedbare kolommen op maaiveld worden niet uitgesneden in de geometrie van de onderbouw.</span></li>
</ol>
<br/>
<br/>
<span>Panden op maaiveld:</span>  
<ol type='1'><li><span>Geometrie van panden op maaiveld blijven op </span><i><span>relatieve hoogte = 0 </span></i><span>en de afzonderlijke geometrieën vormen samen een </span><span>multi</span><span>-vlak.</span></li>
</ol>
<br/>
<br/>
<span>Totale pand:</span>  
<ol type='1'><li><span>De samengestelde 2D-projectie van alle geometrieën van het </span><span>BGT pand</span><span> bij elkaar, waarbij onderlinge overlap is geëlimineerd, is topologisch aangesloten én is gelijk aan de BAG geometrie van dat pand.</span></li>
<li><span>Van de BGT panden met dezelfde BAG-identificatie mag maar één </span><span>BGT pand</span><span> de volledige </span><span>nummeraanduidingsreeks</span><span> (NAR) krijgen, die gerelateerd is aan dat BAG-pand. Deze NAR wordt geplaatst in een </span><span>BGT pand</span><span> (met status = bestaand) met een relatieve hoogte = 0. Voor een geheel ondergronds pand met relatieve hoogte &lt; 0 wordt de NAR in dat pand geplaatst.</span></li>
</ol>
