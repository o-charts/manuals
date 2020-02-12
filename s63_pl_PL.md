---
layout: default_pl_PL
---

# Warunki używania S-63 UserPermit

- Wtyczka S-63 nie jest dostępna ani dla Androida, ani dla iOS.

- Nie sprzedajemy map S-63, dostarczamy tylko zezwolenia S-63 *UserPermit*, które są narzędziem niezbędnym do licencjonowania tych map od ich sprzedawców, takich jak [Chartworld](https://www.chartworld.com/shop/off_enc).

- Aby kupić mapę S-63 od dowolnego dostawcy, musisz posiadać UserPermit. Mapy licencjonowane dla OpenCPN z UserPermit S-63 należy używać tylko przy ustawieniu OpenCPN zgodnie z normą S-63.

- Możesz używać każdej z kupionych map na 5 *systemach* równocześnie lub zachować kopie do użycia w przypadku utraty systemu. Wygenerujemy OpenCPN *InstallPermit* dla każdego systemu oddzielnie. InstallPermit wiąże zestaw map S-63 z OpenCPN dla jednego systemu. Nie należy mylić OpenCPN InstallPermit z CellPermit dla komórki S-63.

- *System* jest kombinacją urządzenia (device) i systemu operacyjnego (OS). Jeśli którykolwiek z tych elementów ulegnie zmianie, system zostanie rozpoznany jako nowy, stracisz swoją licencję i trzeba będzie wykorzystać następny InstallPermit.

- Jeśli wykorzystasz 5 instalacji, będziesz musiał zakupić nowe zezwolenie UserPermit i odtąd licencjonować mapy dla tego nowego UserPermit. W tym nowym cyklu będziesz miał 5 kolejnych możliwości instalacji (5 zezwoleń InstallPermit).

- Twoja licencja powinna przetrwać aktualizację systemu operacyjnego (OS), progamu OpenCPN, oraz wtyczki do OpenCPN, jednak stracisz ją przy ponownej instalacji systemu operacyjnego.

- Raz uzyskana licencja UserPermit nie może zostać zwrócona.

- Po wygenerowaniu InstallPermit dla jednego systemu, nie można anulować lub przenieść go do innego systemu (sprzęt + system operacyjny).

- Warunki dotyczące aktualizowania i daty ważności map S-63 sprawdź u ich dostawcy.

# Instalacja UserPermit/InstallPermit oraz map S-63

![kroki](./assets/images/s63.png)

1. *System* to komputer, na którym będziesz używać OpenCPN. Zestaw map, na który od sprzedawcy map uzyskasz licencję dla danego systemu, może być używany tylko na nim. Pobierz i zainstaluj [wtyczkę S-63](https://opencpn.org/OpenCPN/plugins/s63.html) (dla odpowiedniej wersji OpenCPN).
    
2. Przejdź do OpenCPN, *Opcje → Wtyczki → S63* i włącz wtyczkę. Następnie przejdź do OpenCPN, *Opcje → Mapy → Mapy S63 → Klucze/zezwolenia* i utwórz plik identyfikatora systemu (*Fingerprint*) dla swojego systemu, naciskając przycisk *Utwórz identyfikator systemu*.
    
3. Przejdź do [sklepu o-charts](https://o-charts.org/shop) i kup UserPermit.
    
4. Przejdź do [Moje zezwolenia UserPermit S-63](https://o-charts.org/shop/index.php?fc=module&module=ocpermits&controller=ocpermits) i utwórz InstallPermit, przesyłając plik Fingerprint, wygenerowany przed chwilą i przypisz go do twojego S-63 UserPermit.
    
5. Odwiedź sklep dostawcy map S-63 i kup mapy S-63, których potrzebujesz, wykorzystując swój UserPermit S-63 dla OpenCPN. Czasami dostawca poprosi o "HW-ID", zignoruj to pytanie.
    
6. Ściągnij i rozpakuj swoje zestawy map S-63. Powinien tam być katalog o nazwie ROOT_ENC (zawierający komórki mapy), znajdziesz tam także plik o nazwie PERMIT.txt zawierający CellPermit.
    
7. Przejdź do OpenCPN, *Opcje → Mapy → Mapy S63 → Klucze/zezwolenia*. Wprowadź swój UserPermit i przetestuj go wciskając *Nowy UserPermit*. Wprowadź swój InstallPermit i przetestuj go wciskając *Nowy InstallPermit*.
    
8. Przejdź do OpenCPN, *Opcje → Mapy → Mapy S63 → Komórki map*. Zainstaluj zezwolenia CellPermit poprzez wciśniecie przycisku *Importuj zezwolenia CellPermit* i wybranie pliku PERMIT.txt w zestawie map S-63. Zaimportuj zestawy map S-63, naciskając *Importuj mapy/korekty* i wskazując katalog ENC_ROOT.
    
9. OpenCPN utworzy niezbędne pliki eSENC. Instalacja została zakończona!

# Najczęściej zadawane pytania

> **Dlaczego mapy S-63?**
> 
> Są to oficjalne i zwykle najbardziej aktualne z dostępnych map. Mapy wektorowe używane w rekreacji są w najlepszym przypadku tworzone na podstawie tych map (niekiedy będą zawierały pewne dodatkowe specyficzne informacje).

> **Dlaczego trzeba płacić za UserPermit?**
> 
> Musimy pobierać takie opłaty, by móc współpracować z IHO. Administracja i koszty są ograniczone do minimum. W przypadku, gdy odniesiemy wielki sukces ekonomiczny, fundusze zostaną przeznaczone na rozwój OpenCPN.

> **Jak liczony jest "system" w przypadku komputera z wyborem systemu podczas uruchamiania?**
> 
> Każda kombinacja sprzęt + system operacyjny liczona jest oddzielnie i wymaga własnego InstallPermit.

> **A co z instalacją na maszynie wirtualnej?**
> 
> To nie zadziała. Musimy zapobiegać klonowaniu systemów.

> **Musiałem ponownie zainstalować system operacyjny. Teraz InstallPermit jest już nieważny.**
> 
> Wygeneruj nowy InstallPermit.

> **Mój komputer uległ uszkodzeniu. Czy mogę odzyskać mapy?**
> 
> Tak, także w tym przypadku będzie to "kosztowało" jeden InstallPermit dla nowego komputera.

> **Czy mogę zainstalować InstallPermit oraz mapy na nośniku USB i przenosić je między różnymi systemami?**
> 
> To byłoby rozwiązanie z kluczem sprzętowym. Sądzimy, że rozsyłanie USB lub DVD na cały świat, nie byłoby dla nas wykonalne. Dlatego zdecydowaliśmy się na klucz programowy. Więc odpowiedź na dziś brzmi: nie.

> **Ile kosztują mapy S-63 (i czemu czasami są tak drogie)?**
> 
> Cena detaliczna map jest ustalona przez poszczególne Biura Hydrograficzne (HO). Ich użytkownikami jest przemysł żeglugowy albo oficjalne agendy rządowe, nie żeglarze rekreacyjni. To jest znany problem i powód, dla którego mapy S-63 są obecnie bardzo rzadko używane w rekreacji. Potrzebny będzie silny lobbing, aby uzyskać lepsze rozwiązania i niższe ceny. Pomoc lub wsparcie osób, która mają odpowiednie kontakty, będą mile widziane.

> **Kończy się okres ważności mojej licencji. Co się stanie?**
> 
> Mapa nie zniknie, ale będzie wyświetlane ostrzeżenie.

> **OpenCPN jest oprogramowaniem open source. Gdzie znajdę kod wtyczki?**
> 
> Aby pracować z mapami S-63, musimy mieć pewność, że nie będą dostępne żadne kopie niezaszyfrowanych komórek map. Dlatego wtyczka ma część open-source i część binarną. Podobnie jak wtyczki komercyjnych map BSB4 albo NV-charts.
