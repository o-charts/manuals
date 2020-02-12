---
layout: default_pl_PL
---

# Warunki używania map oeRNC

- Mapy oeRNC mogą być używane tylko w OpenCPN.

- Jeśli szczegółowe warunki używania konkretnej mapy nie pozwalają na więcej, możesz używać mapy na 2 systemach. Powiązanie systemu z licencją mapy nazywamy "przypisaniem".

- Możesz używać wszystkich przypisań jednocześnie, albo zachować jedno z nich - do użycia w przypadku utraty głównego systemu lub wprowadzenia w nim zmian powodujących utratę jednego z przypisań licencji.

- *System* jest kombinacją urządzenia (device) i systemu operacyjnego (OS). Jeśli którykolwiek z tych elementów ulegnie zmianie, system będzie rozpoznany jako nowy, co spowoduje unieważnienie licencji i konieczne będzie skorzystanie z wolnego przypisnia.

- Twoja licencja powinna przetrwać aktualizację: systemu operacyjnego, programu OpenCPN oraz wtyczki do niego, jednak stracisz ją przy ponownej instalacji systemu operacyjnego (na tym samym sprzęcie!), konieczne będzie dokonanie kolejnego przypisania map.

- Jeśli dokonałeś już wszystkich dozwolonych przypisań systemów do twoich map i chcesz używać map w następnym systemie - musisz kupić kolejną licencję map.

- *Klucz sprzętowy USB* traktowany jest jak jeden "system". Klucz sprzętowy USB umożliwia zainstalowanie map oeSENC w dowolnej liczbie urządzeń. Jednak tylko w urządzeniu, do którego podłączony jest klucz sprzętowy USB, licencja staje się aktywna i mapy działają.

- Po pobraniu map do pierwszego systemu, opłata nie może być zwrócona. Jeśli masz utworzony system i przypisane do niego mapy, ale ich jeszcze nie pobierałeś, nadal możesz otrzymać zwrot opłaty.

- Po pobraniu map dla jednego systemu nie ma możliwości anulowania tej operacji ani przeniesienia map do innego zestawu urządzenie — system operacyjny.

- Będziesz miał możliwość aktualizowania swoich map przez rok od daty zakupu. Mapy aktualizowane są z różną częstotliwością:
    
    - Kwartalnie: Imray - Karaiby wschodnie, Imray - Adriatyk i Morze Jońskie, Imray - Morze Egejskie i wschodnia część Morza Śródziemnego.
    - Nieokreślony: Mapy Explorer (Bahamy).
- Licencja wygasa po roku od daty zakupu. Po wygaśnięciu licencji pobrane wcześniej mapy będą nadal działały w systemie, ale ich aktualizacja nie będzie już możliwa.

- Przez okres 1 roku możesz przypisać swoje mapy do systemu. Po upływie okresu licencyjnego przypisanie nowego systemu nie będzie możliwe.

# Instalacja map

Jeśli system, w którym chcesz zainstalować mapy **jest podłączony do Internetu**, wykonaj kroki opisane w punkcie **pozyskiwanie map online**. To prostszy i zalecany sposób.

Jeśli system, w którym chcesz zainstalować mapy **NIE jest podłączony do Internetu** postępuj zgodnie z instrukcjami podanymi w punkcie **Pozyskiwanie map offline**.

W celu zainstalowania map na **Androidzie** postępuj jak przy **pozyskiwaniu map online**.

## Pozyskiwanie map online

1. Pobierz i zainstaluj [wtyczkę oeRNC](https://opencpn.org/OpenCPN/plugins/oernc.html) (tylko dla OpenCPN w wersji 5.0 lub wyższej). Jeśli wtyczka oeRNC jest już zainstalowana, zaktualizuj ją do najnowszej wersji.

2. Przejdź do OpenCPN, *Opcje → Wtyczki → oeRNC* i włącz wtyczkę.

3. Przejdź do [sklepu o-charts](https://o-charts.org/shop/14-oernc) i kup licencje na zestawy map, którymi jesteś zainteresowany. Zapamiętaj dane dostępu do sklepu o-charts (e-mail i hasło), będziesz ich potrzebować później. Pomiń ten krok, jeśli już kupiłeś mapy.

4. Jeśli chcesz przypisać swoje mapy do [ klucza USB ](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), podłącz go do teraz port USB. Pomiń ten krok jeśli nie posiadasz klucza sprzętowego USB.

5. Przejdź do OpenCPN, *Opcje → Mapy→ Mapy oeRNC*. Na karcie "Moje mapy" naciśnij *Odśwież listę map*. Użyj strzałek, aby wyświetlić ukryte zakładki.

6. Zaloguj się danymi dostępu do sklepu o-charts.

7. Jeśli używasz klucza USB, zignoruj ten krok. Po pierwsze - musisz zidentyfikować swój system za pomocą *nazwy systemu*. Jeśli instalujesz mapy oeRNC po raz pierwszy w tym systemie, wybierz *nowy system* i podaj nazwę składającą się z 3-15 znaków (tylko litery i cyfry bez spacji czy znaków specjalnych). Jeśli system był już używany, wybierz z listy odpowiadającą mu *nazwę systemu*. Jeśli wybierzesz złą *nazwę systemu* instalacja map może się odbyć, ale nie będą one działać. Jeśli instalujesz mapy w drugim systemie lub przeinstalowałeś system operacyjny, wybierz *Nowy*, aby utworzyć nowe przypisanie.

8. Postępuj zgodnie z instrukcjami na ekranie aby przypisać, pobrać i zainstalować dla systemu (lub klucza USB) zestawy map, których licencje kupiłeś w sklepie o-charts. Po wykorzystaniu wszystkich dostępnych przypisań mapy nie będą dostępne dla kolejnych. 

### Uaktualnienia - online

Powinieneś sprawdzać *Opcje → Mapy → Mapy oeSENC * od czasu do czasu, aby dowiadywać się czy dostępna jest aktualizacja. Aktualizacje online są przyrostowe, ale nie martw się, wtyczka oeRNC zadba o to, aby pobrane zostały wszystkie niezbędne aktualizacje pośrednie, które mogłeś przegapić.

## Pozyskiwanie map do Androida

1. Zainstaluj najnowszą wersję [OpenCPN dla Androida 4.4 (lub wyższego)](https://play.google.com/store/apps/details?id=org.opencpn.opencpn) ze Sklepu Play. Upewnij się, że używasz oficjalnej aplikacji OpenCPN.

2. Zainstaluj wtyczkę [oeRNC dla aplikacji OpenCPN](https://play.google.com/store/apps/details?id=org.opencpn.oerncplugin) ze Sklepu Play. Otwórz aplikację i kliknij na "Instaluj wtyczkę oeRNC".

3. Przejdź do [sklepu o-charts](https://o-charts.org/shop/14-oernc) i kup licencje na zestawy map, którymi jesteś zainteresowany. Pomiń ten krok, jeśli już kupiłeś mapy. Zapamiętaj dane dostępu do sklepu o-charts (e-mail i hasło), będziesz ich potrzebować później.

4. Przejdź do OpenCPN, *Opcje → Mapy→ Mapy oeRNC*. Na karcie "Moje mapy" naciśnij *Odśwież listę map*. Użyj strzałek, aby wyświetlić ukryte zakładki.

5. Zaloguj się do sklepu o-charts za pomocą swojego e-mail i hasła.

6. Postępuj zgodnie z instrukcjami na ekranie aby przypisać, pobrać i zainstalować w systemie zestawy map, których licencje kupiłeś w sklepie o-charts. Nie zapomnij sprawdzać od czasu do czasu, czy nowa aktualizacja jest dostępna.

## Pozyskiwanie map offline

W przypadku systemów bez połączenia z Internetem musisz utworzyć plik identyfikatora tego systemu, aby - po przeniesieniu go na komputer z dostępem do Internetu - zażądać wygenerowania i pobrać zestaw map dla sytemu docelowego. Zakładamy, że najnowsze wersje OpenCPN i wtyczki oeRNC są zainstalowane w systemie docelowym.

1. Jeśli chcesz przypisać swoje mapy do [ klucza USB ](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), podłącz go do teraz port USB. Pomiń ten krok jeśli nie posiadasz klucza sprzętowego USB.

2. Przejdź do OpenCPN, *Opcje → Wtyczki → oeRNC* i włącz wtyczkę.

3. Wejdź w *Ustawienia* i kliknij *Utwórz plik ID dla klucza USB...*- jeśli masz klucz USB, lub *Utwórz plik identyfikatora systemu...</ em> jeśli nie masz klucza sprzętowego. Wtyczka poda ścieżkę dostępu do pliku *Fingerprint*. W przypadku Windows i macOS kopia jest tworzona bezpośrednio na pulpicie. W przypadku Linuxa plik jest tworzony w katalogu ~/.opencpn.</p></li> 
    
4. Skopiuj plik *Fingerprint* na przenośny nośnik i znajdź jakiś komputer z dostępem do Internetu.
    
5. Przejdź do [sklepu o-charts](https://o-charts.org/shop/14-oernc) i kup licencje na zestawy map oeRNC, którymi jesteś zainteresowany. Pomiń ten krok, jeśli już kupiłeś mapy.
    
6. Przejdź do strony [Moje mapy oeRNC](https://o-charts.org/shop/module/occharts/occhartsOernc) i utwórz tam *identyfikator systemu*, przesyłając plik *Fingerprint*. Pozostaw *nazwę systemu* pustą jeśli używasz klucza USB.
    
7. Wybierz ów nowy *identyfikator systemu* dla każdego zestawu map, który chcesz przypisać do tego systemu. Raz dokonane przypisanie, nie może być zmienione.
    
8. Zażądaj przygotowania map, klikając przycisk, *Przygotuj*. Po kilku chwilach otrzymasz 2 linki: jeden do map, drugi do pliku z kluczami do ich odszyfrowania. Skopiuj oba pliki na jakiś nośnik przenośny i przenieś je na system docelowy.
    
9. W systemie docelowym rozpakuj plik map do wybranego katalogu i skopiuj pliki kluczy do tego samego folderu, w którym znajdują się rozpakowane mapy (.oernc). Zainstaluj mapy jak zwykle. Jeśli przypisałeś swoje mapy do klucza USB, musisz go podłączyć, aby móc korzystać z map.</ol> 
    
### Uaktualnienia - online
    
Aby zaktualizować zestaw map, przejdź do strony [Moje mapy oeRNC](https://o-charts.org/shop/module/occharts/occhartsOernc). W kolumnie *aktualizacje* pokazana będzie ostatnia aktualizacja, którą pobrałeś. W kolumnie *Ostatnia aktualizacja* znaleźć można informację o aktualnym wydaniu dostępnym dla danego zestawu map. Jeśli te daty są różne, pojawi się przycisk *Zażądaj*. Aktualizacje offline są niezależne i kompletne, nie martw się o aktualizacje pośrednie, które mogłeś pominąć wcześniej. Usuń stary zestaw map z OpenCPN, lub zachowaj go w innym katalogu. Pobierz i zainstaluj nowy zestaw.
    
# Najczęściej zadawane pytania
    
    > **Dla jakich systemów operacyjnych istnieją wtyczki oeSENC i oeRNC?**
    > 
    > Mapy oeSENC i oeRNC działają w Windows, Mac, Android i Linux (w tym także ARM).
    > 
    > **A czy mogę zainstalować oprogramowania na maszynie wirtualnej?**
    > 
    > To nie zadziała. Musimy zapobiegać klonowaniu systemów.
    > 
    > **Czy można używać map oeSENC i oeRNC na iOS?**
    > 
    > Nie. Nie istnieje wersja OpenCPN dla iOS.
    > 
    > **Jak liczony jest "system" w przypadku komputera z wyborem systemu podczas uruchamiania?**
    > 
    > Każda kombinacja sprzęt + system operacyjny liczona jest oddzielnie.
    > 
    > **Dlaczego trzeba płacić za mapy oeSENC i oeRNC?**
    > 
    > Musimy dostosować się do wymogów instytucji posiadających prawa do map. Instytucje te określają opłaty i warunki licencyjne. Administracja i koszty są ograniczone do minimum. W przypadku, gdy odniesiemy wielki sukces ekonomiczny, fundusze zostaną przeznaczone na rozwój OpenCPN.
    > 
    > **OpenCPN jest oprogramowaniem open source. Gdzie znajdę kod wtyczki?**
    > 
    > Aby wykorzystywać mapy oeSENC i oeRNC musimy mieć pewność, że nie będą dostępne żadne kopie niezaszyfrowanych komórek map. Dlatego wtyczka ma część open-source i część binarną. Podobnie, jak wtyczki komercyjnych map BSB4 albo NV-charts.
