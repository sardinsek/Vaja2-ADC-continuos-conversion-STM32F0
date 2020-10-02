# Vaja2-ADC-continuos-conversion-STM32F0
1.) Glede na vašo razvojno ploščico in razširitveno vezje z tipkami ter potenciometri, izberite ustrezni analogni vhod. Kateri pin je to? PC0.
2.) Glede na potenciometer na vaši ploščici izberite-obkljukajte ustrezni kanal/pin. Na zaslonu se vam mora usterzno pobarvati izbrani pin v zeleno barvo. Kaj se izpiše poleg pina? ADC_IN10.
3.) V Clock Configuration spremenimo APB1 peripheral clock (MHz) na 16 MHz. (potrdite z ENTER) Kaj opazite? VSE FREKVENCE V SYSTEM CLOCK MUX-U SE NASTAVIJO NA 16 MHz.
4.) Kolikšna je sedaj preskalirana frekvenca takta fpreskalirana? 4 MHz.
5.) Koliko znaša pravi čas vzorčenja tvz v mikro sekundah?  62.875 ms.
Komentar delovanja:
Branje potenciometra PC0 s ploščico STM32F0 deluje dobro, vendar pri branju ne moremo prebrati maksimalne vrednosti, verjetno zato, ker pride do manjših napak pri branju. Med tem, ko minimalno vrednost pa lahko preberemo. Ploščica STM32F0 deluje veliko hitreje, kot ploščica Arduino, ztato bi pri takšnem branju raje uporabljala ploščico STM32F0.
