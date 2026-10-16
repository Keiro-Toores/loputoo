# Lõputöö

## Mida rakendus võimaldab?

**Kasutajakonto**
Kasutaja saab registreeruda, sisse logida ja oma andmeid privaatselt hallata.



**Treeningkavade koostamine**
Kasutaja saab luua näiteks Upper/Lower või Push/Pull/Legs kava, lisada harjutusi ning määrata seeriad ja kordused.



**Treeningu salvestamine**
Iga treeningu ajal saab sisestada harjutuse, kasutatud raskuse, kordused ja seeriate arvu.



**Arengu jälgimine**
Graafikud näitavad, kuidas muutuvad näiteks rinnalt surumise raskus, kükkide tulemused ja kehakaal.



**Dashboard ehk avaleht pärast sisselogimist**
Kasutaja näeb oma viimast treeningut, nädalast treeningute arvu, aktiivseid kavasid ja arengut.

## Millised lehed tuleb valmis teha?

01
**Avaleht / Dashboard**
*Treeningute kokkuvõte, statistika ja kiirlingid.*

02
**Treeningkavad**
*Kavade loomine, muutmine ja kustutamine.*

03
**Harjutuste kogu**
*Harjutuste nimed, lihasgrupid ja kirjeldused.*

04
**Treeningu vaade**
*Seeriate, korduste ja raskuste sisestamine.*

05
**Progress**
*Graafikud ja varasemate tulemuste ajalugu.*

06
**Sisselogimine ja registreerimine**
*Kasutajakontod ja turvaline ligipääs.*

## Andmebaas

| Tabel | Milleks seda kasutatakse? |
|---|---|
| `users` | Kasutajate kontod |
| `exercises` | Harjutuste andmed |
| `workout_plans` | Kasutaja treeningkavad |
| `plan_exercises` | Millised harjutused kuuluvad kavasse |
| `workout_sessions` | Tegelikult tehtud treeningud |
| `exercise_sets` | Raskused, kordused ja seeriad |
| `body_metrics` | Kehakaalu ja muude mõõtmiste ajalugu |

## UI Examples

<img width="3152" height="1653" alt="JTE63Q8TjMQhtUmOsY5nreHLUZOyuOj5-R_r8nX8CxP5p44XXSC48pnzqXVJhCtj2kHWgIOBhib4OMFJQjUzHpqMLHHvy9fooDLFveIFJe_XmrprzBME4sXQgVj5lkM5Gd8svzHdL5AvP7mBdJA0-1UC70GFTf8-0fHfw2zoz-VYRwDIhOzrNEipkUAZvnk9" src="https://github.com/user-attachments/assets/da26b239-7a5c-4c81-a4db-52644dcb9c34" />

<img width="1280" height="900" alt="YmWxZ32XDj4OEhPae_zLy9Wnb6o5VAt2M7g61JQrCB3sn2OhAX85b0RJxDUSFx5catyZPk-lP4DBKgm2yajBsdeNAaV8dyOJtYpKhS9dGlQYj-Wp2dKR703bqUbkdgEQhhrpSqRA5weOYd-9E3q9jnRrRJm-ByFie6FUfDjaVfgWdJoOOwFImBK7O9HaymvE" src="https://github.com/user-attachments/assets/dece4c67-5700-4cc6-995e-98b38af4dd6c" />

<img width="1680" height="1260" alt="H8a5bFozoQ2ypcCY78aukanyFBZ3D788PrkrhPdtOSfqb_tVdhKEj5qk5l__a914nCi45DhHZsyYXnH-2pmrSOTvT7rpPvJpuDXryAybtt7Sh6qoAvZKUY9xNXLqsuU2_DXdfceqfLnCcmQveqXAEIyKma1aEEgajyfDtKqxZf9Ap5YtGPdVRmkvXWbAnXuO" src="https://github.com/user-attachments/assets/98e33a6f-601d-4401-959b-237f8949677e" />

<img width="1000" height="1000" alt="vh66M2cuCb_9jmIKh6O5PGooeCLuSGzf3LiQwnqt2QVP9Chf170kEQqVUrhmxVMwHkWpaFTvUpM7wRXYN8UQ-LbaSiLAEEMLQoRAPt5iRrAHEGMMpYFyv1dPibGu22xhp0y_ppI_U6btoEFv9yt7SeDhJ42oMnRmxWuQstGGvZi-G4C0uLd8n6k0oRF2rtF-" src="https://github.com/user-attachments/assets/463d5ed7-b750-4947-a257-057e007a66a5" />
<img width="1446" height="1097" alt="js1NyOa5dyuMKb5UNonv6pM3kTliEqDO1dKNDIaFY1dtSM8wkaWwqfD7vvYc8zhynl8NVTzEwEPvnzod4q1v3CQW3VqdAwGD9S8I0T9yFiMPALrfk2IgDVMsLw6jf4b3TdXcYpKrjr9jfX3RnVKNfzk4dquX2v82qEjqAAqalKlIKNM-z3gqyybMYlq8jJT8" src="https://github.com/user-attachments/assets/a2300561-75e1-461a-a641-675e52e8b0fe" />

<img width="1376" height="768" alt="N_eRY0hGQbpejr1nPblYTuSHwMFSb-9707TdrOLB92ba_DHt7wHbvpjbiSD91Y0N8MkQuIFw49oKYWK1g8W6NpciFLXwV0mXY9b8nxT7gaE12bQUwY7AX9uSOkFsV13Z8JmjQ2Hh3ybOkDFCvQQCrUjtmOrGfCxy5sCn_NiCIqPQ8Ufp8pfXuM-4HnNOVk9v" src="https://github.com/user-attachments/assets/704e2082-5697-434b-9c7e-a17940440a11" />
