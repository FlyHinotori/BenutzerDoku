Datenbankmodell
====================================================

Ablehnungsgrund
----------------------------------------------------

===========	===				===============
Spaltenname	Typ				Primärschlüssel
===========	===				===============
ablg_id		int				X
ablg_bez	nvarchar(100)	 	
===========	===				===============

+-------------+---------------+-----------------+
| Spaltenname | Typ           | Primärschlüssel |
+=============+===============+=================+
| ablg_id     | int           | x               |
+-------------+---------------+-----------------+
| ablg_bez    | nvarchar(100) |                 |
+-------------+---------------+-----------------+

Anrede
----------------------------------------------------

Spaltenname | Typ | Primärschlüssel
--- | --- | ---
anr_id | int | X
anr_bez | nvarchar(100) | 

Auftrag
----------------------------------------------------

Spaltenname | Typ | Primärschlüssel
--- | --- | ---
auf_id | int | X
sta_id | int | 
aart_id | int | 
knd_id | int | 
mst_id | int | 
ablg_id | int | 
flh_id_beginn | int | 
flh_id_ende | int | 
auf_panzahl | numeric(4,0) | 
auf_dauer_h | numeric(6,2) | 
auf_wuensche | nvarchar(500) | 
auf_preis | numeric(10,2) | 
auf_zusatzkosten | numeric(10,2) | 
auf_faellig_am | datetime | 