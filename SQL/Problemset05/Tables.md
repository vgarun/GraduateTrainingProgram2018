# TableList

| select * from musician |
| --- |

| m_no | m_name | born | died | born_in | living_in |
| --- | --- | --- | --- | --- | --- |
| 1 | Fred Bloggs | 02/01/48 |  | 1 | 2 |
| 2 | John Smith | 03/03/50 |  | 3 | 4 |
| 3 | Helen Smyth | 08/08/48 |  | 4 | 5 |
| 4 | Harriet Smithson | 09/05/1909 | 20/09/80 | 5 | 6 |
| 5 | James First | 10/06/65 |  | 7 | 7 |
| 6 | Theo Mengel | 12/08/48 |  | 7 | 1 |
| 7 | Sue Little | 21/02/45 |  | 8 | 9 |
| 8 | Harry Forte | 28/02/51 |  | 1 | 8 |
| 9 | Phil Hot | 30/06/42 |  | 2 | 7 |
| 10 | Jeff Dawn | 12/12/45 |  | 3 | 6 |
| 11 | Rose Spring | 25/05/48 |  | 4 | 5 |
| 12 | Davis Heavan | 03/10/75 |  | 5 | 4 |
| 13 | Lovely Time | 28/12/48 |  | 6 | 3 |
| 14 | Alan Fluff | 15/01/35 | 15/05/97 | 7 | 2 |
| 15 | Tony Smythe | 02/04/32 |  | 8 | 1 |
| 16 | James Quick | 08/08/1924 |  | 9 | 2 |
| 17 | Freda Miles | 04/07/1920 |  | 9 | 3 |
| 18 | Elsie James | 06/05/47 |  | 8 | 5 |
| 19 | Andy Jones | 08/10/58 |  | 7 | 6 |
| 20 | Louise Simpson | 10/01/48 | 11/02/98 | 6 | 6 |
| 21 | James Steeple | 10/01/47 |  | 5 | 6 |
| 22 | Steven Chaytors | 11/03/56 |  | 6 | 7 |
|        Number of records: 22 |

| select * from place |
| --- |

| place_no | place_town | place_country |
| --- | --- | --- |
| 1 | Manchester | England |
| 2 | Edinburgh | Scotland |
| 3 | Salzburg | Austria |
| 4 | New York | USA |
| 5 | Birmingham | England |
| 6 | Glasgow | Scotland |
| 7 | London | England |
| 8 | Chicago | USA |
| 9 | Amsterdam | Netherlands |
|        Number of records: 9 |

| select * from performer |
| --- |

| perf_no | perf_is | instrument | perf_type |
| --- | --- | --- | --- |
| 1 | 2 | violin | classical |
| 2 | 4 | viola | classical |
| 3 | 6 | banjo | jazz |
| 4 | 8 | violin | classical |
| 5 | 12 | guitar | jazz |
| 6 | 14 | violin | classical |
| 7 | 16 | trumpet | jazz |
| 8 | 18 | viola | classical |
| 9 | 20 | bass | jazz |
| 10 | 2 | flute | jazz |
| 11 | 20 | cornet | jazz |
| 12 | 6 | violin | jazz |
| 13 | 8 | drums | jazz |
| 14 | 10 | violin | classical |
| 15 | 12 | cello | classical |
| 16 | 14 | viola | classical |
| 17 | 16 | flute | jazz |
| 18 | 18 | guitar | not known |
| 19 | 20 | trombone | jazz |
| 20 | 3 | horn | jazz |
| 21 | 5 | violin | jazz |
| 22 | 7 | cello | classical |
| 23 | 2 | bass | jazz |
| 24 | 4 | violin | jazz |
| 25 | 6 | drums | classical |
| 26 | 8 | clarinet | jazz |
| 27 | 10 | bass | jazz |
| 28 | 12 | viola | classical |
| 29 | 18 | cello | classical |
|        Number of records: 29 |

| select * from composer |
| --- |

| comp_no | comp_is | comp_type |
| --- | --- | --- |
| 1 | 1 | jazz |
| 2 | 3 | classical |
| 3 | 5 | jazz |
| 4 | 7 | classical |
| 5 | 9 | jazz |
| 6 | 11 | rock |
| 7 | 13 | classical |
| 8 | 15 | jazz |
| 9 | 17 | classical |
| 10 | 19 | jazz |
| 11 | 10 | rock |
| 12 | 8 | jazz |
|        Number of records: 12 |

| select * from band |
| --- |

| band_no | band_name | band_home | band_type | b_date | band_contact |
| --- | --- | --- | --- | --- | --- |
| 1 | ROP | 5 | classical | 30/01/01 | 11 |
| 2 | AASO | 6 | classical |  | 10 |
| 3 | The J Bs | 8 | jazz |  | 12 |
| 4 | BBSO | 9 | classical |  | 21 |
| 5 | The left Overs | 2 | jazz |  | 8 |
| 6 | Somebody Loves this | 1 | jazz |  | 6 |
| 7 | Oh well | 4 | classical |  | 3 |
| 8 | Swinging strings | 4 | classical |  | 7 |
| 9 | The Rest | 9 | jazz |  | 16 |
|        Number of records: 9 |

| select * from plays_in |
| --- |

| player | band_id |
| --- | --- |
| 1 | 1 |
| 1 | 7 |
| 3 | 1 |
| 4 | 1 |
| 4 | 7 |
| 5 | 1 |
| 6 | 1 |
| 6 | 7 |
| 7 | 1 |
| 8 | 1 |
| 8 | 7 |
| 10 | 2 |
| 12 | 2 |
| 13 | 2 |
| 14 | 2 |
| 14 | 8 |
| 15 | 2 |
| 15 | 8 |
| 17 | 2 |
| 18 | 2 |
| 19 | 3 |
| 20 | 3 |
| 21 | 4 |
| 22 | 4 |
| 23 | 4 |
| 25 | 5 |
| 26 | 6 |
| 27 | 6 |
| 28 | 7 |
| 28 | 8 |
| 29 | 7 |
|        Number of records: 31 |

| select * from composition |
| --- |

| c_no | comp_date | c_title | c_in |
| --- | --- | --- | --- |
| 1 | 17/06/75 | Opus 1 | 1 |
| 2 | 21/07/76 | Here Goes | 2 |
| 3 | 14/12/81 | Valiant Knight | 3 |
| 4 | 12/01/82 | Little Piece | 4 |
| 5 | 13/03/85 | Simple Song | 5 |
| 6 | 14/04/86 | Little Swing Song | 6 |
| 7 | 13/05/87 | Fast Journey | 7 |
| 8 | 14/02/76 | Simple Love Song | 8 |
| 9 | 21/01/82 | Complex Rythms | 9 |
| 10 | 23/02/85 | Drumming Rythms | 9 |
| 11 | 18/03/78 | Fast Drumming | 8 |
| 12 | 13/08/84 | Slow Song | 7 |
| 13 | 14/09/68 | Blue Roses | 6 |
| 14 | 15/11/83 | Velvet Rain | 5 |
| 15 | 16/05/82 | Cold Wind | 4 |
| 16 | 18/06/83 | After the Wind Blows | 3 |
| 17 |  | A Simple Piece | 2 |
| 18 | 12/01/85 | Long Rythms | 1 |
| 19 | 12/02/88 | Eastern Wind | 1 |
| 20 |  | Slow Symphony Blowing | 2 |
| 21 | 12/07/90 | A Last Song | 6 |
|        Number of records: 21 |

| select * from has_composed |
| --- |

| cmpr_no | cmpn_no |
| --- | --- |
| 1 | 1 |
| 1 | 8 |
| 2 | 11 |
| 3 | 2 |
| 3 | 13 |
| 3 | 14 |
| 3 | 18 |
| 4 | 12 |
| 4 | 20 |
| 5 | 3 |
| 5 | 13 |
| 5 | 14 |
| 6 | 15 |
| 6 | 21 |
| 7 | 4 |
| 7 | 9 |
| 8 | 16 |
| 9 | 5 |
| 9 | 10 |
| 10 | 17 |
| 11 | 6 |
| 12 | 7 |
| 12 | 19 |
|        Number of records: 23 |

| select * from concert |
| --- |

| concert_no | concert_venue | concert_in | con_date | concert_orgniser |
| --- | --- | --- | --- | --- |
| 1 | Bridgewater Hall | 1 | 06/01/95 | 21 |
| 2 | Bridgewater Hall | 1 | 08/05/96 | 3 |
| 3 | Usher Hall | 2 | 03/06/95 | 3 |
| 4 | Assembly Rooms | 2 | 20/09/97 | 21 |
| 5 | Festspiel Haus | 3 | 21/02/95 | 8 |
| 6 | Royal Albert Hall | 7 | 12/04/93 | 8 |
| 7 | Concertgebouw | 9 | 14/05/93 | 8 |
| 8 | Metropolitan | 4 | 15/06/97 | 21 |
|        Number of records: 8 |

| select * from performance |
| --- |

| pfrmnc_no | gave | performed | conducted_by | performed_in |
| --- | --- | --- | --- | --- |
| 1 | 1 | 1 | 21 | 1 |
| 2 | 1 | 3 | 21 | 1 |
| 3 | 1 | 5 | 21 | 1 |
| 4 | 1 | 2 | 1 | 2 |
| 5 | 2 | 4 | 21 | 2 |
| 6 | 2 | 6 | 21 | 2 |
| 7 | 4 | 19 | 9 | 3 |
| 8 | 4 | 20 | 10 | 3 |
| 9 | 5 | 12 | 10 | 4 |
| 10 | 5 | 13 | 11 | 4 |
| 11 | 3 | 5 | 13 | 5 |
| 12 | 3 | 6 | 13 | 5 |
| 13 | 3 | 7 | 13 | 5 |
| 14 | 6 | 20 | 14 | 6 |
| 15 | 8 | 12 | 15 | 7 |
| 16 | 9 | 16 | 21 | 8 |
| 17 | 9 | 17 | 21 | 8 |
| 18 | 9 | 18 | 21 | 8 |
| 19 | 9 | 19 | 21 | 8 |
| 20 | 4 | 12 | 10 | 3 |
|        Number of records: 20 |
