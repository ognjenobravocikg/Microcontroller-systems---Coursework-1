# MIPS-prvi-doma-i-zadatak-2023
ReadME domaći zadatak iz MIPS-a

STUDENT: OGNJEN OBRADOVIĆ 631/2021 RTSI

Budući da koristim latinicu za izradu domaćeg zadatka pisao sam svoje ime kao Ognjen pa mi u ovom slučaju ime ima 6 slova.

PORT: Ognjen ima više suglasnika nego samoglasnika, pa sam koristio PORT B
PIN: Ognjen(6)+Obradović(9) % 6 = 3
                  
PROTEUS:
Za izradu domaćeg zadatka koristio sam otpornik, takodje i jednu diodu kako bih mogao da detektujem promene signala. Koristio sam kao i do sada na vežbama mikrokontroler STM32F103C6. Dioda želimo da prikaže PVM signal, u elektronici on izgleda ovako:
domaci

STM32IDE:
U podešavanjima RCC , za high speed clock sam koristio Crystal/Ceramic Resonator, a budući da signal šaljem preko mikrokontolera na PIN postavio sam PIN 3 kao GPIO-OUTPUT. Unutar koda sam u beskonačnoj for petlji koja simulira rad našeg mikrokontolera, slao sledeće:

jedinicu 6ms, a potom nulu 9ms (jedinicu broj slova u imenu, a nulu broj slova u prezimenu milisekundi),
dato sam ponavljao 6 puta, a potom sam

slao jedinicu 9ms, a potom nulu 6ms
dato ponavljao 9 puta, nakon čega bi se ciklus ponovio.
