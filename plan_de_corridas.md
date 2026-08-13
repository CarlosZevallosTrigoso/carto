# Plan de corridas — Base de artistas contemporáneos
Código de corrida: `[FASE]-[EVENTO][EDICIÓN]`. Ejemplo: `F1-VEN24` = Fase 1, Bienal de Venecia 2024.
Estado: ✔ ejecutada · ▶ en cola · ◇ opcional/decisión pendiente

## F0 · Cimientos (ejecutada)
Consolidación de fuentes propias y primer canon. Base resultante: 1746 artistas.
- F0-CON ✔ Consolidación CSVs (Vitamin P1-P3, Base propia, ArtReview, Frieze) + HTML
- F0-DOC14 ✔ · F0-DOC13 ✔ · F0-DOC12 ✔ · F0-DOC11 ✔ documenta 11-14
- F0-TUR ✔ Turner Prize (parcial; hueco 1986-1998 → F1-TUR86)
- F0-WHI00 a F0-WHI24 ✔ Whitney Biennial, serie completa 2000-2024 (13 ediciones)
- F0-TATE ✔ Primera capa factual Tate (relleno incremental, sigue activa en cada corrida)

## FV · Serie Vitamin (Phaidon) — ejecutada
Circuito de consagración editorial por nominación de pares. Fuente: inventario compilado
(documento Compass, 11-08-2026). Chips de fuente limpios; la cobertura parcial de nueve
tomos se documenta aquí, no en el chip: la ausencia de un artista en un tomo parcial no es informativa.
- FV-D05 ✔ Vitamin D 2005 (109/109) · FV-PH06 ✔ Vitamin Ph 2006 (121/121)
- FV-3D09 ✔ Vitamin 3-D 2009 (117/117) · FV-T19 ✔ Vitamin T 2019 (110/113: 3 nombres
  perdidos en la fuente del inventario, completar vía índice A-Z)
- FV-P316 ✔ Vitamin P3 como verificación cruzada del CSV original (discrepancia: 2 nombres
  ausentes del CSV, Nathan Cash Davidson y Yuan Yuan, ya incorporados)
- FV-PAR ✔ Nueve tomos parciales: P (3), P2 (+4), D2 (15), C (24), D3 (15), C+ (25),
  Txt (41), V (29), P4 (31) — nombres verificados, listas no exhaustivas
- FV-COMP-A ✔ Barrido web de tomos parciales (11-08-2026): la web abierta está agotada —
  todos los distribuidores repiten el mismo blurb que el inventario ya capturó. Rendimiento:
  +2 nombres de Vitamin D3 (Rachel Goodyear, Rebecca Salter) vía artículo de Phaidon.
  Cobertura resultante: P 3/114 · P2 76/115 · D2 15/115 · C 24/102 · D3 17/100 ·
  C+ 25/108 · Txt 41/103 · V 29/100 · P4 31/108 (~704 nombres restantes).
- FV-COMP-B ◇ Vía única restante: índices A-Z de los ejemplares — préstamo controlado en
  Internet Archive (P: vitaminpnewpersp0000unse; D2: vitamind2newpers0000unse), ejemplares
  físicos (biblioteca PUCP tiene parte de la serie), o API search-inside de IA vía Colab.
  Acción de Carlos; los tomos parciales quedan operativos con chips verificados entretanto.

## FC · Compendios editoriales (Cream, Prime, Beers y geográficos) — ejecutada
Consagración generacional y correctiva-geográfica. Fuente: segundo inventario Compass
(11-08-2026). Base tras FC: 2420.
- FC-CRE98 ✔ Cream 1998 (56/100: tramo A-L; M-Z solo en ejemplar físico)
- FC-FCR00 ✔ Fresh Cream 2000 (100/100) · FC-CRE03 ✔ Cream 3 2003 (100/100;
  los 10 «Source Artists» EXCLUIDOS por ser categoría de referentes históricos, no del survey)
- F6-NMT09 ✔ (adelantada) New Museum Triennial 2009 «Younger Than Jesus», exposición 50/50;
  el directorio de ~500 no está en línea
- FC-100P14 ✔ 100 Painters of Tomorrow (~77/100) · FC-100S19 ✔ 100 Sculptors of Tomorrow (20/100)
- FC-PRI22 ✔ Prime 2022 (33/107)
- FC-AFR21 ✔ African Artists (11 de 316: floor; excluidos históricos Onabolu/Sekoto/Muafangejo)
- FC-LAT23 ✔ Latin American Artists (floor de 6; solo Coco Fusco entra como contemporánea;
  FLAG PERÚ: Martín Chambi documentado en el tomo, fuera de alcance contemporáneo)
- FC-21C14 ✔ The 21st-Century Art Book (floor de 10) · FC-ACF13 ✔ Art Cities of the Future (2/96)
- FC-COMP ◇ Pendiente por ejemplar físico/escaneo: Ice Cream 2007 (0/100), Art Now 1-4 (0),
  Great Women Artists/Painters (0 útiles), tramo M-Z de Cream, índices de African/Latin American
  (bloque peruano prioritario), atribución curador→artista de la serie Cream (solo en impreso)

## F1 · Canon central
Estado al 11-08-2026: serie Venecia 2007-2024 COMPLETA (7 ediciones, muestra internacional
solamente, regla de vivos con precedente Adkins/Hammer para muertos en preparación).
- F1-VEN24 ✔ 142 vivos (Nucleo Storico póstumo excluido) · F1-VEN22 ✔ 123 vivos
- F1-VEN19 ✔ 79/79 · F1-VEN15 ✔ 121 vivos (plataformas excluidas, colectivos productores dentro)
- F1-VEN13 ✔ 108 vivos (outsiders/históricos/colecciones anónimas excluidos)
- F1-VEN09 ✔ 82 vivos (bloque GUTAI excluido como ancla histórica)
- F1-VEN07 ✔ 84 vivos (fuente: anuncio Artforum, listas web mezclan pabellones;
  LeWitt y Rhoades con marca; León de Oro a Ferrari registrado)
- F1-VEN03 ▶ SIGUIENTE. Requiere decisión editorial de Carlos: la edición Bonami
  (~380 participantes) delegó diez sub-muestras a curadores invitados (incluye
  «The Structure of Survival» de Grynsztejn con eje latinoamericano). ¿Se cosecha todo
  el archipiélago con un solo chip, o solo el núcleo curado por Bonami?
- Leones de Oro registrados en hitos: 1997 Abramović · 2007 Ferrari, Jacir · 2009 Rehberger,
  Djurberg, Ono, Baldessari · 2013 Sehgal, Henrot, Lassnig, Merz · 2015 Piper, Im, El Anatsui ·
  2019 Jafa, Epaminonda, Durham · 2022 Leigh, Vicuña, Fritsch, Cherri · 2024 Maiolino, Yalter,
  Mataaho · 2001 Herrero (vía lote Carlos)
- Pendientes de la fase: TUR86, HBP, LDO (consolidación histórica), MDU ◇, PNG ◇, DOC10 ◇, DOC15 ◇

## Colas de catálogo F2-SPB (ediciones con documentación web insuficiente)
- SPB24 (1998, Herkenhoff «Antropofagia», 326 participantes): solo 4 verificados de los
  Roteiros (Konaté, Kentridge, Dias & Riedweg, Fraser). Catálogo Roteiros en Issuu →
  candidato prioritario a extracción Colab (la edición más citada de la historia de la bienal).
- SPB25 (2002, Hug «Iconografias metropolitanas», 194 participantes): solo 10 verificados
  vía prensa (segmento ciudad utópica). Elenco completo en catálogo Issuu (3 tomos:
  Cidades, Países, Brasil) → candidato a extracción con Colab.
- SPB26 (2004): representaciones nacionales solo en catálogo Issuu (71 de 135 cosechados).
- SPB33 (2018): colas «among others» de las muestras Borges y Caldas (catálogo impreso).
- SPB29 (2010): ~11 adiciones tardías no incluidas en la lista de anuncio (159 vs 148).

## F2-HAB · Bienal de La Habana: estado tras la cosecha del dominio histórico
COMPLETAS (listas oficiales/testigo vía universes-in-universe.de, accesible):
- 6ª 1997 «El individuo y su memoria»: 178 ingeridos (8 peruanos, cohorte fotografía).
- 7ª 2000-01 «Uno más cerca del otro»: 168 ingeridos (exposición central; anotaciones
  Haupt de no-participantes respetadas).
- 8ª 2003: 147 ingeridos (lista oficial Centro Wifredo Lam, país por país; 2 peruanos).
PENDIENTES:
- 5ª 1994 y anteriores (1ª 1984, 2ª 1986, 3ª 1989, 4ª 1991): solo catálogos impresos;
  el dominio viejo da ficha técnica sin elenco. Wikipedia EN lista participantes notables
  por edición (Belkin, Arden Quin, Ferrari 1984; premiados 1986 Bedia, Capelán, Chissano,
  Chowdury) → cosecha parcial posible, sujeta a política «histórico-exhibido» (muchos
  fallecidos). Nota: Pat Binder expuso en 1994 y 1997.
- 12ª 2015 «Entre la idea y la experiencia»: PARCIAL hecha (~38 de 90 invitados
  internacionales, vía Artishock/Arteinformado; secciones cubanas masivas de Zona Franca
  no cosechadas). CORRECCIÓN de registro: universes.art NO tiene índices por edición de
  la 9ª-13ª (verificado por navegación de Carlos); la vía para 9ª, 10ª, 11ª y 13ª es
  prensa/reseñas por edición (rendimiento parcial) o catálogos.
- 11ª 2012 «Prácticas artísticas e imaginarios sociales»: PARCIAL hecha (~24 de 115+,
  vía EcuRed/BOMB/Cancillería/Excelencias; sección Caribe completa).
- 9ª 2006 «Dinámicas de la cultura urbana»: PARCIAL hecha (~23 de 100+, vía reseña
  Herzberg/Art Nexus: las 8 personales completas + colectiva parcial). Flags borde F8:
  Jean Nouvel (arquitecto), Carlos Saura (cineasta).
- 10ª 2009, 13ª 2019: pendientes vía prensa/Web Archive (Carlos excavando snapshots de
  bienalhabana.cult.cu, bienalhabana.fcbc.cu, bienaldelahabana.org). HALLAZGO: universes.art tiene
  páginas por edición bajo /es/bienal-de-la-habana/AÑO (2012 confirmada) aunque el menú
  no las exponga; exigen JavaScript (inaccesibles para Claude) → Carlos puede probarlas
  en navegador con /2009, /2015, /2019 y copiar índices si existen
  → navegación manual de Carlos, o prensa por edición (rendimiento bajo). La 9ª tiene
  reseña académica de Julia Herzberg con nombres sueltos.
- 14ª 2021-22: mínima hecha (6 nombres + contexto boicot).

## F4-DAK · Estado tras la primera excavación
2002, 2004 (dominio histórico UiU, la 2002 con datos de nacimiento) y 2022 (lista oficial
C&) COMPLETAS; 2024 «The Wake» parcial (44/58); 2016 y 2018 (era Njami) mínimas con los
Grand Prix Senghor registrados (Limoud 2016, Adjovi 2018). Colas: 1998/2000 (catálogos,
INHA los tiene en sala), 2006-2014 (prensa/catálogos; el catálogo 2010 citado en Wikipedia).

## F2-CUE · Estado y colas
13ª-16ª cosechadas (14ª completa; 13ª y 15ª casi completas; 16ª completa) + premios de
adquisición registrados como hitos (mecanismo consagratorio propio de Cuenca, incluida la
doble premiación de Magdalena Fernández 2009/2011). Colas: ediciones 1987-2014 (el
Catálogo de la Colección en fundacion.bienaldecuenca.org/wp-content/ documenta los
premiados de TODAS las ediciones históricas → candidato Colab de alto valor); 17ª (2025)
en curso, lista aún no consolidada.

## FLAGS «histórico-exhibido» acumulados (política F8 pendiente de Carlos)
Peruanos/latinoamericanos fallecidos exhibidos por bienales, excluidos por regla de vivos:
Taller NN (SPB35), Museo Travesti del Perú/Campuzano (SPB31), Martín Chambi (VEN24),
Jorge Eielson (CUE14 2018), CADA (SPB29), Yeguas del Apocalipsis (resuelto: miembros
ingresados como individuos vía HAB6).

## F2-MER · Colas de catálogo
Los catálogos en PDF de la 1ª, 4ª, 5ª, 6ª y 7ª están en descarga gratuita en
bienalmercosul.art.br/publicacoes; el de la 8ª (2011, Hug, 105 artistas con «lista de
artistas e coletivos» indexada) está en dokumen.pub; el de la 9ª en Scribd/Issuu.
Candidatos ideales al pipeline Colab de extracción → cerrarían 2ª-5ª, 7ª, 8ª completas.
MER10 (2015, Fidelis, 402 artistas): parcial ~43 vía Itaú/Arteinformado; el grueso
(incluido el componente indígena y las representaciones históricas) solo en catálogo.
Excluidos históricos (Aleijadinho, Bispo, Guignard, Cícero Dias, Pedro Américo y otros);
dudosos de estado vital omitidos (Noviello, Gorini, Estrada, Vicuña, Ramírez).
MER9 parcial hecha (~35 de 60, por sedes vía Secretaría de Cultura RS).
MER12 (2020, Giunta, virtual): lista no consolidada en prensa; catálogo digital de la
edición en bienalmercosul.art.br → cola Colab. Solo Baltar verificada.

## VETA NUEVA F8-UIU · Datos de nacimiento en el dominio histórico
universes-in-universe.de aloja listas CON año/lugar de nacimiento y residencia para varias
bienales (confirmado: São Paulo 27ª en /car/sao-paulo/eng/2006/artists.htm; probable para
otras ediciones SPB y Mercosur). Veta de enriquecimiento masivo de pendientes sin gastar
búsquedas del investigador → corridas F8 dedicadas.

## F2-HAB · Bienal de La Habana: diagnóstico y vía de completamiento (histórico)
Ninguna edición tiene lista oficial consolidada en la web (solo cifras agregadas y nombres
sueltos en prensa cubana). Cosechado: 14ª cobertura mínima (Kcho, Azcona, Isabel Muñoz,
Sonia Cunliffe [Perú], La Usurpadora, Mréjen) + elenco transversal Wikipedia (~21 nombres,
hito genérico «edición por precisar»). Contexto 14ª: boicot «Por qué decimos NO» (oct 2021,
post-11J). VÍA DE COMPLETAMIENTO: Universes in Universe documenta las ediciones 7ª (2000)
a 12ª (2015) artista por artista, pero bloquea acceso automatizado → candidata a navegación
manual de Carlos o al chat investigador (las URLs siguen el patrón
universes-in-universe.de/car/habana/ y universes.art/en/bienal-habana). Ediciones
fundacionales (1984: 800 artistas de 22 países; 1986: 690 de 57) solo en catálogos.

## fuentes.csv · Registro canónico de fuentes (nuevo derivado, 13-08-2026)
Una fila por unidad de cosecha respaldada por chip (edición de bienal, tomo editorial,
lista o premio), más capas factuales sin chip (Tate, veta UiU, investigador). Columnas:
chip, tipo, evento_o_titulo, edicion, anio, titulo_edicion, curaduria, cobertura,
n_ingeridos, via_fuente, fase_corrida, fecha_corrida, notas. Los 38 chips de la maestra
están cubiertos (verificación automática en cada corrida). Regla: se alimenta con cada
corrida nueva; lo pendiente sigue viviendo en este plan, no en fuentes.csv.

## Circuito investigador (paralelo, activo)
Chat Claude aparte con /mnt/user-data/outputs/instrucciones_investigacion.md y lotes de
lotes_pendientes.csv. Fusión por id, campos vacíos solamente, fechas normalizadas a año.
Primer ciclo: lote de 25 fusionado aquí + ~420 registros fusionados por Carlos en su copia
y auditados/adoptados (11-08). Cobertura factual: 57% (1626/2845). Pendientes: 1172.
Flag F8: id 1 «Banu Cennetoğlu (Facilitator)» requiere limpieza de nombre.


Venecia (muestra internacional curada), cierre documenta, premios de consagración.
- F1-VEN24 ▶ Venecia 2024 «Stranieri Ovunque» (Pedrosa) — prioridad 1, corrige sesgo
- F1-VEN22 ▶ Venecia 2022 «The Milk of Dreams» (Alemani)
- F1-VEN19 ▶ Venecia 2019 (Rugoff) · F1-VEN15 ▶ 2015 (Enwezor) · F1-VEN13 ▶ 2013 (Gioni)
- F1-VEN09 ▶ Venecia 2009 (Birnbaum) · F1-VEN07 ▶ 2007 (Storr) · F1-VEN03 ▶ 2003 (Bonami)
- F1-DOC10 ◇ documenta X 1997 (Catherine David) — fuera de ventana 2000, decisión Carlos
- F1-DOC15 ◇ documenta 15 2022 (ruangrupa) — propuesta: solo colectivos invitados (~65)
- F1-TUR86 ▶ Turner Prize 1986-1998 (completar hueco)
- F1-HBP ▶ Hugo Boss Prize (listas cortas completas)
- F1-LDO ▶ León de Oro Venecia (filtrar homónimo de cine)
- F1-MDU ◇ Premio Marcel Duchamp · F1-PNG ◇ Preis der Nationalgalerie

## F2 · Sur latinoamericano
Columna vertebral de fuentes: Universes in Universe (universes.art) + archivos de fundaciones.
- F2-SPB98 a F2-SPB25 ▶ Bienal de São Paulo, 24ª (1998, Herkenhoff) a 36ª (2025)
- F2-HAB ▶ Bienal de La Habana (ediciones desde 2000; hacia atrás si la fuente lo permite)
- F2-MER ▶ Bienal do Mercosul, Porto Alegre (incluye la 6ª pedagógica de Camnitzer, 2007)
- F2-CUE ▶ Bienal de Cuenca (circuito andino; captura peruanos ausentes de otras listas)
- F2-TPS ◇ Trienal Poligráfica de San Juan · F2-SFE ◇ SITE Santa Fe

## F3 · Asia y Medio Oriente
- F3-GWA ▶ Bienal de Gwangju, desde 1995 (fundacional)
- F3-SHJ ▶ Bienal de Sharjah, desde la 6ª (2003, giro curatorial)
- F3-EST ◇ Bienal de Estambul: 10ª (2007, Hou Hanru) COMPLETA (96 participantes vía
  universes-in-universe.de/car/istanbul/esp/2007/artists.htm, versión en tablas del sitio
  en español; con año/lugar de nacimiento y residencia para la mayoría). 31 cruces con la
  base, 65 altas. Flags F8-BORDE acumulados: Koolhaas/AMO, Teddy Cruz, Fiuza Faustino,
  Yushi Uehara (arquitectura), Egoyan y Funari (cine), Barnbrook (diseño), Helvacıoğlu
  (sonido), Multiplicity (agencia interdisciplinar). Sin datos en la fuente: Democracia,
  Elveris & Göktan (pendientes). Corridas 13-08: 8ª (2003, Cameron, «Poetic Justice»)
  COMPLETA, 84 entradas vía /car/istanbul/2003/e-artist-print.htm, solo nombres+país
  (hallazgo peruano: Bryce sube a 3 fuentes; Mehretu llega a 11 con este chip); 9ª (2005,
  Esche/Kortun, «İstanbul») COMPLETA, 53 vía /eng/2005/artists.htm, solo nombres.
  Decisiones: Superflex/Haaning separados (regla 4, ambos con ficha propia); Erek & Erkal,
  Tzaig & Shaham, Ugay & Maskalev, Wieder & Fezer en fila conjunta; alias nuevos Do-Ho
  Suh→Do Ho Suh y Pawel→Paweł Althamer (ł no descompone en NFD); Alptekin dado de alta
  como «Hüseyin Bahri Alptekin» (grafía corta en la fuente 2005). Recurrencia
  intra-institucional sin chip doble: Ataman, Atay, Oda Projesi (2003+2005+2007).
  Resto de la serie: 1987-2001 sin lista en el dominio histórico (verificar), 2009 en
  universes.art (bloqueado, navegación de Carlos), 2011+ por anuncios de prensa.
- F3-KOC ▶ Kochi-Muziris Biennale, completa
- F3-APT ▶ Asia Pacific Triennial, Brisbane
- F3-SHA ◇ Shanghai · F3-TAI ◇ Taipei · F3-YOK ◇ Yokohama

## F4 · África y diásporas
- F4-DAK ▶ Dak'Art, Bienal de Dakar (principal del continente; fuente: Universes in Universe)
- F4-BAM ◇ Rencontres de Bamako (fotografía africana)

## F5 · Europa no comercial
- F5-BER ▶ Berlin Biennale, completa desde 1998
- F5-MAN ▶ Manifesta, completa desde 1996
- F5-SKM ▶ Skulptur Projekte Münster (1997, 2007, 2017)
- F5-CAR ▶ Carnegie International (lista internacional pese a sede estadounidense)
- F5-LYO ◇ Bienal de Lyon · F5-LIV ◇ Liverpool Biennial

## F6 · Observatorios de emergencia
Estrato pre-consagración: hace visible el embudo en el tiempo.
- F6-NMT ▶ New Museum Triennial · F6-MLA ▶ Made in L.A.
- F6-GNY ◇ Greater New York (PS1) · F6-TTT ◇ Tate Triennial

## F7 · Capa factual masiva
- F7-MOMA ✔ (13-08-2026) Ingesta Artists.csv del MoMA (15 932 registros, vía Colab de
  Carlos por el bloqueo Git LFS). Rendimiento: 398 fechas de nacimiento llenadas (solo
  personas con género declarado; colectivos saltados porque BeginDate=fundación), 193
  enlaces Wikidata en fichas sin enlace. Salvaguardas: 21 conflictos de fecha NO
  sobrescritos (log_moma_conflictos.csv, a revisión manual: incluye Sillman, Tomaselli,
  Sepuya, Atlas con divergencias grandes) y 149 fallecidos según MoMA registrados en
  log_moma_fallecidos.csv como insumo de la política F8-FALL. Homónimos internos del
  MoMA: ninguno presente en la base.
- F7-WIKI ▶ Corrida Colab Wikidata (notebook ya entregado; corrida de Carlos)
- F7-TATE2 ▶ Segunda pasada Tate con matching laxo supervisado (homónimos a revisión manual)

## F8 · Depuración editorial
Decisiones de Carlos con propuesta de Claude:
- F8-BORDE ▶ Participantes de borde (cineastas, músicos, bandas, arquitectos, escritores)
- F8-FALL ✔ RESUELTA (13-08-2026, decisión de Carlos): base histórica inclusiva. Los
  fallecidos entran; columna nueva fecha_muerte en la maestra (respaldada con 149 fechas
  del log MoMA); los cinco flags «histórico-exhibido» dados de alta (Taller NN,
  Campuzano/Museo Travesti, Chambi, Eielson, CADA). La regla de póstumos de bienales
  (exclusión de exhibidos ya fallecidos ANTES de la edición) se mantiene para chips de
  bienales de vivos ya cosechadas; las exposiciones-hito F11 entran completas.
- F8-COL ▶ Colectivos menores y duos redundantes con sus miembros
- F8-DUP ▶ Cacería de duplicados por variantes de nombre (alias, transliteraciones)

## F9 · Vocabulario e interpretación
- F9-VOC ▶ Propuesta de vocabulario controlado: ~30 temas, ~18 medios (aprobación Carlos)
- F9-IDX ▶ Columna calculada «índice de consagración» + filtro por nº de fuentes en el HTML
- F9-INT01… ▶ Lotes interpretativos de 25-30 fichas/sesión, priorizando multi-fuente

## F11 · Exposiciones-hito (nueva fase, 13-08-2026)
Dispositivos consagratorios de evento único; chip propio por exposición; entran completas
incluyendo fallecidos (política F8-FALL resuelta). Estrato histórico asumido.
- F11-MAG ✔ Magiciens de la Terre (1989, Pompidou/Villette, J.-H. Martin): 98 unidades
  derivadas de la ficha oficial del catálogo digital Kandinsky (obras por artista);
  30 cruces (Meireles, Huang Yong Ping, Yang Jiechang, Abramović, Bourgeois, Paik,
  Kruger, Jaar, Samba, Kingelez, Mahlangu, Bruly Bouabré, Bedia...), 68 altas
  (Kane Kwei & Paa Joe, Tokoudagba, Munyaradzi, Liautaud, Camara, Mawandjul, Wunuwun,
  la familia Linares, comunidad Yuendumu...). Grafías normalizadas con alias declarados
  (Yang Jie Chang, Yongping Huang, Twin Seven Seven, Laurence Weiner en la fuente).
  Cotejo 98 vs 100 declarados pendiente contra catálogo impreso.
- F11-WAB ✔ (13-08) When Attitudes Become Form «Live in Your Head» (1969, Kunsthalle
  Bern, Szeemann): 69/69 vía documento MACBA que reproduce el catálogo razonado de
  Szeemann (Bezzola/Kurzmeyer 2007). Incluye póstumos Klein y Pascali (política F8-FALL).
  Buren NO figura en el elenco oficial (intervención clandestina, dato con miga para
  clases). Grafías normalizadas: Boetti a la ficha existente «Alighiero e Boetti»,
  Sandback y Wegman a formas establecidas. Itinerancia (Haus Lange Krefeld, ICA Londres)
  registrada en fuentes.csv, sin chip aparte.
- F11-ANT ✔ (13-08) Ante América (1992, Biblioteca Luis Ángel Arango, Bogotá;
  Mosquera/Ponce de León/Weiss): 26/26 por triangulación MADC + ICAA + El Tiempo.
  11 cruces (Jaar, Salcedo, Bedia, Durham, Mendieta, Camnitzer, Duclós, B. González,
  Hincapié, Alves, Edwards); 15 altas (Capelán, Caro, Cardoso, Toledo, Chagoya,
  Gómez-Peña, Elso, los jamaiquinos Brown y George, el haitiano André Pierre...).
  Póstumos Mendieta y Elso incluidos (F8-FALL).
- F11-CYC ◇ (13-08) Cocido y crudo (1994-95, Reina Sofía, Dan Cameron): PARCIAL 56/86
  vía archivo Kopystiansky (Flickr, transcripción del catálogo). Cruces fuertes con el
  canon de los 90 (Orozco, Hatoum, Dumas, Kcho, Kingelez, Miyajima, Tiravanija, Green,
  Odenbach, Doherty, R. López Cuenca, Dittborn...). Resto de la lista solo en catálogo
  impreso (ISBN 84-8026-042-4, biblioteca Reina Sofía/PUCP) → cola de completamiento.
  «McCarthy, Marlene» de la fuente asumida como Marlene McCarty [REVISAR].
- F11-UTS ✔ (13-08) Under the Same Sun (2014, Guggenheim NY, Pablo León de la Barra):
  40 unidades reconstruidas de PIPA Prize (elenco NY) + ARTnews + lista de itinerancia
  SLG. PERUANOS: Andrade Tudela (sube a 3 chips) y el dúo Mantilla & Chaves (alta;
  también en viewing room CPPC → conexión doble con el circuito Cisneros).
  Cruces masivos con CIFO/CPPC/Daros: la muestra funciona como escaparate Guggenheim
  del mismo circuito de consagración que esos dispositivos construyen (León de la Barra
  curador UBS MAP; Herrero, Pica, Galindo, Prieto, Bruguera, Téllez, Zaccagnini,
  Joskowicz, Lamelas, García Torres, Castillo Deball, Cesarco todos multi-dispositivo).
  Itinerancia Jumex 2015 / SLG 2016 sin chip aparte.
- F11-RAD ✔ (13-08) Radical Women: Latin American Art 1960-1985 (2017, Hammer, PST:
  LA/LA; Fajardo-Hill/Giunta): 121 unidades desde el archivo digital oficial del Hammer
  (120 declarados; el archivo separa a Mayer y Bustamante además de su colectivo Polvo
  de Gallina Negra). BLOQUE PERUANO de cuatro: Teresa Burga (que suma su segundo
  dispositivo del día tras CIFO), Gloria Gómez-Sánchez, Johanna Hamann y Victoria Santa
  Cruz, las tres últimas altas nuevas: la recuperación feminista es la vía por la que
  entran a la base, dato de primera para clases. Alias: «Marta María Pérez» y «Yeni y
  Nan» unificados con fichas existentes (Pérez Bravo, Yeni & Nan). Itinerancia
  Brooklyn Museum / Pinacoteca São Paulo 2018 sin chip aparte.
- F11-TSC ✔ (13-08) The Short Century (2001, Villa Stuck, Múnich; Enwezor): 55/55 vía
  Contemporary And. El eje africano histórico entra completo gracias a F8-FALL: Sekoto,
  Keïta, Enwonwu, Mancoba, Ndiaye, Feni, los modernos de la independencia (sin
  retroactividad sobre el chip African Artists, cuyas exclusiones se mantienen).
  Cruces con Magiciens (Bruly Bouabré, Kingelez, Twins Seven-Seven), Dak'Art y Estambul
  2003 (Bhimji, Geers, Mthethwa): la genealogía Magiciens→Short Century→documenta 11 del
  circuito africano queda legible en las fichas. Kentridge suma su noveno chip.
  Flags F8-BORDE: Isaac Julien (cine) incluido por figurar en el elenco.
- F11-GLC ✔ (13-08) Global Conceptualism (1999, Queens Museum; Farver/Camnitzer/Weiss
  con once curadores regionales, entre ellos Enwezor, Ramírez, Gao Minglu): 137 unidades
  del elenco oficial de la página del museo. La exposición-tesis del conceptualismo
  multicéntrico: ingresa el bloque latinoamericano fundacional (Tucumán Arde como
  colectivo, Bony, Carreira, Greco, Grippo, Jacoby, Escari, Antonio Manuel), el
  conceptualismo japonés (Matsuzawa, Akasegawa, Hi Red Center), el coreano Min Joong,
  el este europeo (Koller, Filko, Kantor, Erdély) y el soviético (Kabakov, Komar &
  Melamid, Monastyrsky). Camnitzer figura como curador (no como artista) en este
  dispositivo: nota para el análisis del doble rol. Decisiones de dúos/colectivos y
  flags borde (Lippard, Siegelaub) declaradas en fuentes.csv.
- F11-INF ◇ (13-08) Information (1970, MoMA; Kynaston McShine): PARCIAL 62 unidades de
  las 75 fichas en línea del índice del MoMA (la paginación JS bloqueó el resto; el
  catálogo declara ~150 participantes de 15 países). Completar por navegación de Carlos
  (moma.org/artists?exhibition_id=2686, segunda página) o por el catálogo del 50
  aniversario → cola. Bloque latinoamericano visible: Oiticica, Minujín, Ferrer, Puente
  y el colectivo Barrio Campo Rico de Canóvanas (Puerto Rico): la tesis de Ramírez
  sobre el conceptualismo latinoamericano temprano tiene aquí su antecedente
  institucional. Decisiones de dúos declaradas en fuentes.csv.
- F11-COM ◇ (13-08) Cities on the Move (1997-1999, Hanru/Obrist): PARCIAL 68 unidades
  trianguladas de AAA (etiquetas CotM2 + facetas del archivo fotográfico), FORMER WEST,
  ShanghART y Flash Art; el catálogo Viena/Burdeos declara 103 y la serie 150+, con
  elencos variables por sede (rasgo estructural de la muestra, no defecto de la
  cosecha). Entra el eje asiático noventero que faltaba: Cantón (Big Tail Elephant:
  Lin Yilin, Chen Shaoxiong, Liang Juhui), el pop coreano-tailandés (Choi Jeonghwa,
  Rawanchaikul, Kusolwong, Sriwanichpoom), el sudeste (Arahmaiani, Dono, Gill, Liew
  Kung Yu) y la escena japonesa (Mori, Murakami, Araki, Hanayo). Arquitectos con flag
  borde-arquitectura global. Hanru cierra el día presente en tres chips curatoriales
  (Estambul 2007, CotM; Gwangju pendiente). Completar por catálogo Hatje → cola.
- F11 SALDADA salvo Century City (2001, Tate), que queda como opcional a decisión de
  Carlos.
- F3-GWA26 ✔ (13-08) Serie Gwangju INAUGURADA por la 16ª edición (2026, Ho Tzu Nyen,
  «You Must Change Your Life», en curso septiembre-noviembre): 45 unidades del elenco
  íntegro de e-flux. PERUANA: Maya Watanabe. Cruces notables: Lygia Clark y Július
  Koller póstumos (F8-FALL rindiendo en bienales vivas), Eviner desde Estambul.
  La serie histórica 1995-2024 queda en cola con vía definida: e-flux/ARTnews por
  edición (universes.art bloqueado por JS); prioridad sugerida: 2002 (Esche/Hanru/
  Sung), 2008 (Enwezor), 2024 (Bourriaud).

## F12 · Museos (nueva fase, 13-08-2026)
- F12-DAR ✔ (13-08, fuente aportada por Carlos) Colección Daros Latinamerica, Zúrich:
  118/118 vía daros-latinamerica.net. DECISIÓN EDITORIAL declarada: suma chip pese a ser
  colección, por selectividad de escala compendio (~118 nombres curados, no colección
  masiva); la regla colección-sin-chip sigue vigente para colecciones museales de miles.
  Cruces fuertes con Ante América y el circuito bienal (Bedia, Jaar, Salcedo, Camnitzer,
  Caro, Cardoso, Gómez-Peña, Mendieta, Meireles, Bruguera, Macchi, Rennó...) que
  confirman a Daros como consagración europea del corpus latinoamericano. Estrato
  histórico dentro (Torres-García, Clark, Oiticica, Gego, Soto, Ferrari, Schendel,
  Arden Quin...). Colectivos: Los Carpinteros, Quintapata; dúo Pareja & Chavez.
  Alias aplicados: Apóstol→Apostól (grafía de la base a revisar), Bedia.
  SIN PERUANOS en la colección: dato con miga para el argumento del embudo.
- F12-CIF ✔ (13-08) CIFO Grants & Commissions (Cisneros Fontanals, Miami), serie
  2004-2026 completa según la página oficial: 191 premiados con hito por año. 2005 y
  2021 no figuran en la página (declarado; verificar si hubo ediciones). Dispositivo de
  premiación por nominación de comité, complementario de Daros: NUEVE peruanos en la
  serie (Burga 2014, Ortiz 2012, Ruiz 2009, Nakamura y Damiani 2016, Fiedler 2017,
  Martínez Garay 2019, Randall-Weeks 2024, Solís Bravo 2026), dato de oro para el
  contraste consagración-coleccionismo vs consagración-premio. Alias: Pareja & Chavez
  (orden invertido respecto de Daros) unificado en la ficha existente.
- F12-CPPC ✔/◇ (13-08) Colección Cisneros (CPPC) vía donaciones al MoMA: Modern Gift
  2016 COMPLETA (37/37, post.moma.org con conteo de obras; núcleo de abstracción
  geométrica: Clark, Oiticica, Pape, Gego, Soto, Otero, Schendel, Maldonado, la escuela
  concreta brasileña y rioplatense) y Contemporary Gift 2018 PARCIAL (22/48 del
  comunicado oficial; resto en mo.ma/cisneros → cola). Chip único «Colección Cisneros
  (CPPC)» con hito por donación, mismo criterio de selectividad que Daros. HALLAZGOS
  PERUANOS: David Zink Yi en el Contemporary Gift, y la iniciativa global CPPC donó
  también al MALI de Lima (junto a Blanton, MAM Buenos Aires, Bronx Museum y Reina
  Sofía) → la donación CPPC-MALI es corrida candidata de alto interés local, vía
  prensa/MALI.
- Ecosistema Daros mapeado (13-08): CPPC sin índice público (vías: donación MoMA 2016,
  catálogo «Concrete Invention», Cisneros Research Guide; peruanos confirmados: Aramburu,
  Mantilla & Chaves); ESCALA (Essex, ~800 obras) con catálogo en línea dinámico → vía
  investigador o navegación de Carlos, discutir chip vs capa factual; pendientes de
  sondear: ISLAA, Halle Collection, Jumex (probable capa factual), Hochschild (¿catálogo
  público? consultar a Carlos).
Política aprobada: la retrospectiva/individual institucional suma chip por museo; la
presencia en colección alimenta capa factual e hitos sin chip (evita que colecciones
masivas aplasten el índice). Cola inicial con balance Sur-Sur: MALBA, MASP, MAM-SP,
Museo de la Solidaridad Allende, MUAC, Chopo, Tamayo, MALI, MAC Lima, Reina Sofía,
MACBA, Pompidou, Tate Modern, Stedelijk, Van Abbemuseum, Zeitz MOCAA, Mathaf, M+,
Mori, MMCA Seúl, New Museum, Studio Museum Harlem. Vía de cosecha por decidir museo a
museo (archivos de exposiciones en línea de calidad muy dispar).

## F10 · Publicación
- F10-GH ▶ GitHub Pages: separar CSV del HTML, README, licencia de datos
- F10-PED ◇ Vista pedagógica: subconjunto peruano/latinoamericano destacado
