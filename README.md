# Pitanje 1:
U Bin/Debug folder je su dodane .dll i još jedna .pdb datoteka.
Dogodio se exception tj. naš program se ne može pokrenuti jer nema .dll datoteke.
Poslat ću .exe i .dll datoteke.

# Pitanje 2:
Konzolna aplikacija je koristila novu verziju class library asemblija i prikazala novi string.
Razlog tome je da konzolna aplikacija ima referencu na class library projekt pa pokretanje konzolne aplikacije znači automatsko pokretanje i build class library projekta.

# Pitanje 3:
Build proces je uspio, a u packages direktorij je opet dostupan NodaTime.
