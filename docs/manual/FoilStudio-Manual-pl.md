# Foil Studio instrukcja obsługi

Android 0.1.127 (148)  ·  7 listopada 2026

Ta instrukcja prowadzi od edytowalnego projektu do cięcia, rysowania pisakiem, grawerowania pasywnego i bigowania. Opisuje Foil Studio dla Androida 0.1.127 (148), w tym ustawienia obiektów, układy produkcyjne, Print & Cut oraz aktualne sposoby łączenia z ploterami.

## 01 Pierwszy projekt

1. Wybierz docelowy ploter przed ustawieniem narzędzi. Otwórz przykład lub utwórz mały kształt, nadaj mu dokładne wymiary i przypisz narzędzie we właściwościach obiektu.

2. W zakładce Przygotowanie sprawdź załadowaną matę, granice projektu, narzędzia i liczbę kopii. Materiał jest przypisany do warstwy: otwórz Warstwy, a następnie Edytuj warstwę, aby go wybrać. Nowe projekty nadają warstwie Default bieżący materiał. Sprawdź zadanie wskazuje brakujące przypisanie; przed produkcją przetestuj rzeczywisty materiał.

3. W zakładce Cięcie wybierz właściwe Zadanie, jeśli projekt zawiera kilka zadań. Podgląd pokazuje to zadanie i jego znaczniki montażowe. Na żądanie potwierdź założony materiał, sprawdź etapy narzędzi, zamontuj wskazane narzędzie i uruchom zadanie świadomie. Obserwuj ploter i potwierdź zakończenie dopiero po zatrzymaniu ruchu.

4. Zapisz projekt i zachowaj wyeksportowaną kopię zapasową. W pomocy znajdziesz interaktywne lekcje oraz edytowalne przykłady. Nazwy przykładów w tej instrukcji wskazują odpowiadające im projekty w aplikacji.

### Plany i zakupy

Free obejmuje edycję i podgląd. Basic to jednorazowy zakup umożliwiający zapis, eksport, drukowanie i uruchamianie zadań plotera. Aktywna subskrypcja Pro obejmuje funkcje Basic oraz tworzenie i ponowne generowanie projektów w kreatorach pudełek i prac kreatywnych. Otwórz plany, aby zobaczyć oferty lub przywrócić zakupy.

## 02 W tej instrukcji

01  Pierwszy projekt

03  Cięcie rysowanie grawerowanie i bigowanie

04  Ustawienia narzędzi i kalibracja noża

05  Zaznaczanie i rysowanie kształtów

06  Tekst układy i kreatory

07  Importowanie zapisywanie i przywracanie projektów

08  Wektoryzacja obrazów i edycja krzywych

09  Przygotowanie i podgląd produkcji

10  Warstwy materiały i zadania

11  Naklejki i etykiety QR

12  Pasowanie wydruku i cięcia

13  Łączenie i sterowanie ploterem

14  Konfiguracja i obsługa HPGL i DMPL

15  Silhouette i AutoBlade

16  Praca z VEVOR Smart

17  Pomoc i zgłoszenia dotyczące ploterów

## 03 Cięcie rysowanie grawerowanie i bigowanie

### Cięcie

Przypisz nóż do konturów cięcia. Nowe kształty domyślnie używają Drag knife 45°; wybierz ostrze odpowiednie do materiału. Ustaw wysunięcie ostrza, przejścia, siłę i prędkość dla wybranego plotera. Wytnij mały kontur, sprawdź narożniki i zamknięcie, a następnie sprawdź i uruchom zadanie. Kalibracja noża pozwala dopracować offset i nadcięcie.

### Rysowanie

Przypisz pisak do linii lub obrysów, które chcesz narysować. Zamontuj go w uchwycie wymaganym przez wybrany ploter, a następnie sprawdź kontakt i podawanie tuszu na tym samym materiale. Sprawdź etap pisaka i uruchom go. Wektoryzacja obrazu śledzi obrysy: gruba linia na obrazie może dać dwie rysowane krawędzie.

### Grawerowanie

Przypisz narzędzie grawerujące do ścieżek znakowania. Użyj zgodnej końcówki do grawerowania pasywnego i zamocuj odpowiednią próbkę. Sprawdź prześwit oraz kontakt narzędzia, a następnie przetestuj siłę, prędkość i przejścia obsługiwane przez dany model. Oceń ślad przed sprawdzeniem i uruchomieniem pełnego etapu grawerowania.

### Bigowanie

Przypisz rylec do bigowania do linii zgięcia, a nóż do zewnętrznego konturu. Przetestuj rowek na takim samym kartonie i sprawdź jakość zgięcia. Nie przesuwaj arkusza między etapami. Kreator pudełek może utworzyć oddzielne ścieżki bigowania i cięcia; przed składaniem przeczytaj instrukcję montażu.

### Zadania łączone

Zadanie łączone wykonuje kolejno rysowanie pisakiem, grawerowanie, bigowanie i cięcie nożem. Sprawdź każdy etap i potwierdź każdą wymaganą zmianę narzędzia. Grafika przypisana do drukarki trafia do wydruku; obiekty pomocnicze nie są wykonywane przez ploter.

## 04 Ustawienia narzędzi i kalibracja noża

### Narzędzia i właściwości obiektu

Szacowany nacisk: 50–1000 g. Wszystkie warianty FilmCut używają tego samego przeliczenia PWM; rzeczywista siła nie jest mierzona.

Jeśli Zapisz nie zamyka edytora, popraw wyróżnione pole nacisku. Jego zakres zależy od wybranych jednostek.

Jednostki nacisku pozostają dostępne dla FilmCut i VEVOR. Zmiana jednostek nie przelicza liczby; sprawdź siłę przed zapisaniem.

Obiekty używają ustawień przypisanego narzędzia w zakresie obsługiwanym przez wybrany model. Wyłącz Użyj ustawień narzędzia we właściwościach obiektu, aby je zmienić. Inne modele zachowują swoje wartości. Profile HPGL/DMPL używają nacisku i prędkości z panelu plotera; właściwości obiektu nie pokazują tych wartości ani przełącznika. Przypisane ustawienia narzędzia sprawdzisz lub zmienisz we Właściwościach obiektu.

Obiekty zachowują przypisaną kopię ustawień narzędzia. Po edycji narzędzia w bibliotece wybierz jego zaktualizowany wpis we Właściwościach obiektu.

Na tablecie lub szerokim ekranie rozwiń warstwę w drzewie Warstwy. Dotknij obiektu, aby go zaznaczyć; przycisk zaznaczenia dodaje go lub usuwa z zaznaczenia. Menu warstwy i obiektu otwierają właściwości. Użyj Dodaj warstwę lub Przenieś do warstwy. Przytrzymaj nazwę obiektu, aby przeciągnąć go na warstwę. Po przeniesieniu obiekt otrzymuje materiał warstwy docelowej.

Wybierz model w Połączeniu. Narzędzia pokazują tylko jego ustawienia i zapamiętują wartości osobno dla każdego modelu. Prędkość fizyczna jest podawana w mm/s; Silhouette używa własnej skali siły i prędkości. Stare wartości nacisku zachowują znaczenie. Gramy FilmCut są szacunkowe, nie zmierzone.

Zaznacz obiekt i otwórz „Edytuj właściwości”. Ustaw nazwę, kolor, narzędzie i liczbę przejść. Prędkość i nacisk są dostępne dla modeli, które przyjmują je z aplikacji.

Każdy obiekt zachowuje własne ustawienia narzędzia. Kolor pomaga uporządkować rysunek; nie przypisuje narzędzia.

Obiekty drukarki należą do wydruku. Linie pomocnicze nie są cięte. Przed uruchomieniem sprawdź podgląd i przypisanie narzędzi.

Przykład w pomocy: Jeszcze jeden rozdział

### Kalibracja noża

Otwórz bibliotekę narzędzi i wybierz Kalibruj nóż pod wybranym nożem. Najpierw sprawdź wysunięcie ostrza, siłę i prędkość na jednej próbce. Szerokość końcówki nie jest używana do kompensacji noża.

Włącz Kompensację noża, aby stosować offset i nadcięcie. Offset to odległość od osi uchwytu do końcówki ostrza, a nadcięcie powtarza początek zamkniętego konturu. Otwarte ścieżki nie otrzymują nadcięcia. Kąt ostrza nie zmienia tej geometrii.

Nowe arkusze kalibracji ustawiają kierunek ostrza w świeżych obszarach odpadowych przed każdym konturem i przejściem. Pozostaw te miejsca wolne i używaj świeżego materiału do każdej próby. Starsze zapisane arkusze zachowują swój układ; wygeneruj nową kalibrację, aby dodać odcinki ustawiające ostrze.

Porównaj ponumerowane próbki offsetu i wybierz najczystsze narożniki. Nie zmieniaj siły, prędkości, głębokości ostrza ani materiału. Doprecyzuj porównanie lub wybierz Żadna nie jest dobra, aby sprawdzić inny zakres.

Przy stałym offsecie porównaj próbki nadcięcia przy zaznaczonym miejscu zamknięcia. Wybierz najmniejsze nadcięcie, które czysto zamyka kształt, a następnie sprawdź końcowy kwadrat, trójkąt i koło.

Przenieś każdą próbę do zwykłego ekranu Cięcie i uruchom ją ręcznie. Po zakończeniu wróć do kalibracji. Zapisz wybrany offset i nadcięcie w narzędziu dopiero po sprawdzeniu końcowej próbki. Eksport próby zachowuje dokładne ustawienia; pierwotny projekt pozostaje zachowany.

Każda próba używa tych samych pozycji. Przed każdą próbą, również doprecyzowaniem i powtórzeniem, załaduj świeży, niewycięty obszar lub nowy materiał.

Wybierz materiał do kalibracji noża. Pozostanie ten sam we wszystkich próbach.

Dołączony arkusz kalibracji jest podglądem z obiektami pomocniczymi. Użyj Kalibruj nóż, aby wygenerować próbę cięcia dla wybranego narzędzia i plotera.

Przykład w pomocy: Kalibracja noża

## 05 Zaznaczanie i rysowanie kształtów

### Zaznaczanie przesuwanie i rozmiar

Dotknij obiektu, aby go zaznaczyć, i przeciągnij, aby go przesunąć. Przeciągnij od pustego miejsca na macie, aby zaznaczyć kilka obiektów.

Dotknij obiektu dwa razy, aby pokazać uchwyty rozmiaru. Przeciągnij uchwyt, a potem wybierz „Zakończ zmianę rozmiaru”, aby wrócić do przesuwania.

Przesuwaj widok i zmieniaj powiększenie dwoma palcami. Powiększ widok przed edycją drobnych szczegółów.

Przytrzymaj etykietę Edytuj punkty lub Zaznacz obszar, aby zobaczyć opis gestów. Myszą najedź na etykietę.

Wpisz szerokość lub wysokość, aby ustawić rozmiar zaznaczenia. Zachowaj proporcje aktualizuje drugi wymiar. W sekcji Współczynnik skali znajdziesz suwaki i procenty. Środek zaznaczenia pozostaje w miejscu; grupy skalują się razem. Zastosuj tworzy jeden krok cofania.

Nowe konfiguracje używają widocznej siatki liniowej co 1 mm, mocniejszych linii, wąskich linijek i przyciągania co 1 mm. Zmień je w Siatka i skala. Zapisane ustawienia są zachowywane. Powiększenie może ukrywać drobne linie bez zmiany odstępu przyciągania.

Otwórz Kształty małą zakładką na lewej ramce: dotknij jej lub przesuń od niej w prawo. Kompaktowe ikony dopasowują się do wysokości maty. Na krótkim ekranie przewijaj listę narzędzi; strzałka zamykania pozostaje u góry. Przesuń w lewo lub dotknij strzałki, aby zamknąć panel.

Na tablecie lub szerokim ekranie rozwiń warstwę w drzewie Warstwy. Dotknij obiektu, aby go zaznaczyć; przycisk zaznaczenia dodaje go lub usuwa z zaznaczenia. Menu warstwy i obiektu otwierają właściwości. Użyj Dodaj warstwę lub Przenieś do warstwy. Przytrzymaj nazwę obiektu, aby przeciągnąć go na warstwę. Po przeniesieniu obiekt otrzymuje materiał warstwy docelowej.

Otwórz Szczegóły, aby uzyskać dodatkowe wskazówki. Pomoc zawiera pełne lekcje i edytowalne przykłady.

Przykład w pomocy: Małe podziękowanie

### Menu obiektu

Menu obiektu zaczyna się od właściwości i edycji treści, potem zawiera Przesuń, Skaluj i Obróć, a następnie Duplikuj i kolejność obiektów. Usuń jest na końcu. Wyrównaj i rozmieść oraz Wypełnij arkusz znajdziesz w Edytuj.

Zaznacz obiekt, a następnie przytrzymaj na nim palec bez przesuwania. Mysz: naciśnij i przytrzymaj przycisk.

W menu obiektu wybierz Przesuń, aby podać dokładne przesunięcie w poziomie i pionie, lub Skaluj, aby ustawić szerokość, wysokość albo współczynnik skali. Zgrupowane obiekty zmieniają się razem; rozgrupuj je, aby edytować poszczególne części.

Polecenia edycji znajdziesz również w „Edytuj”. Strzałka w dół przy krawędzi długiego menu pokazuje dalsze opcje.

Przykład w pomocy: Małe podziękowanie

### Kształty

Łuk rysuje ćwiartkę elipsy 90° w przeciągniętym obszarze. Wybierz Dodaj → Łuk, aby wpisać inny kąt.

Rysowanie odręczne pozostaje aktywne i zapisuje każdą kreskę po podniesieniu palca. Śledzi palec bez przyciągania do siatki. Dotknij ponownie aktywnej ikony rysowania odręcznego lub Zakończ rysowanie, aby wyjść.

Wybierz prostokąt, koło, elipsę, linię, łuk, trójkąt lub gwiazdę. Belka się zamknie. Przeciągnij po macie, aby zobaczyć podgląd kształtu; puść palec, aby dodać jeden obiekt i wrócić do zaznaczania. Samo dotknięcie niczego nie dodaje.

Przyciąganie korzysta z ustawień Siatka i skala. Zacznij na macie; drugi koniec pozostaje w jej granicach. Koło zachowuje jednakową szerokość i wysokość. Przytrzymaj gotowy obiekt i wybierz Skaluj lub Przesuń, aby wpisać dokładne wymiary i przesunięcia.

Dwa palce anulują niedokończony kształt i przesuwają lub powiększają widok. Aby anulować rysowanie, otwórz ponownie belkę Kształty i dotknij podświetlonego kształtu. Cofnij usuwa gotowy kształt w jednym kroku.

Przykład w pomocy: Trzy figury i odniesienie

## 06 Tekst układy i kreatory

### Edytuj tekst

Wybierz jeden parametryczny napis.

Jeśli kontury tekstu zostały poprawione ręcznie, utwórz nowy tekst, aby zmienić jego treść, albo zachowaj istniejące kontury.

Odstępy liter wymagają dołączonego fontu z obsługą składu.

Wybierz jeden napis i Edytuj tekst. Wysokość wielkich liter, szerokość, odstępy klastrów i dziewięć kotwic aktualizują jeden podgląd.

Zastosuj tworzy jeden krok cofania. Anuluj zachowuje oryginalny tekst, narzędzie i kontury.

Otwórz Szczegóły, aby uzyskać dodatkowe wskazówki. Pomoc zawiera pełne lekcje i edytowalne przykłady.

W krótkim oknie przewiń formularz do przycisków. Wpisywanie na klawiaturze zachowuje ten sam szkic.

Przykład w pomocy: Edytuj tekst

### Rozmieszczanie i powtarzanie

Zaznacz grafikę i użyj ikony Wyrównaj obok Cofnij i Ponów. Pasek akcji mieści się w szerokości obszaru roboczego i zawija się przy braku miejsca.

Wybierz Względem, a następnie dotknij ikony wyrównania lub rozmieszczania. Przytrzymaj ikonę, aby zobaczyć jej nazwę; przesuń pasek wyrównania, aby odsłonić kolejne ikony. Góra oznacza największe Y projektu.

Otwórz Opcje rozmieszczenia, aby ustawić marginesy obszaru roboczego lub zadany odstęp. Ikona strzałek przełącza rozmieszczanie w poziomie i pionie. Aby wskazać odniesienie, wybierz Obiekt odniesienia, dotknij ikony wskaźnika, a potem obiektu na podglądzie; pozostanie on nieruchomy.

Sprawdź duży podgląd lub otwórz go ikoną pełnego ekranu. Znacznik wyboru zatwierdza jedną operację możliwą do cofnięcia; krzyżyk anuluje bez zmiany projektu.

Zaznacz kilka obiektów i otwórz Edytuj → Układ. Wyrównaj, rozmieść lub powtórz obiekty, a przed zatwierdzeniem sprawdź podgląd.

Użyj „Grupuj”, aby zachować kompozycję razem. „Powiel” tworzy edytowalną kopię. „Cofnij” przywraca stan sprzed edycji.

Przykład „Rozkwit” zawiera powtórzone i obrócone płatki. Zmień jeden płatek i porównaj go z pozostałymi.

Przykład w pomocy: Rozkwit

### Wypełnij arkusz jednym motywem

Oryginał liczy się jako pierwsza kopia. Wybierz łączną liczbę lub oblicz maksimum; odstępy i cztery marginesy pozostają jawne.

Pozostałe włączone obiekty blokują komórki siatki. Zastosuj tworzy jeden krok cofania i zachowuje grupy oraz powiązaną grafikę.

Przykład w pomocy: Dwadzieścia cztery etykiety

### Edytowalne kreatory projektów

Dodaj → Kreator pudełek i Kreator projektów tworzą części z osobnymi rolami cięcia, bigowania, rysowania lub drukowania.

Zaznacz wygenerowaną część i otwórz ponownie kreator z menu „Edytuj”. Zmień wymiary, liczbę kopii lub arkusze i sprawdź podgląd.

Ponowne generowanie może zastąpić ręczne zmiany. Przed zatwierdzeniem przeczytaj potwierdzenie i instrukcje składania.

Otwórz Szczegóły, aby poznać ustawienia. W kreatorze pudełek otwórz Składanie, aby zobaczyć instrukcję składania.

Wybierz pudełko bez kleju z zamkniętymi narożnikami i ściankami zatrzaskowymi. Zacznij od próbki dopasowania, podaj zmierzoną grubość materiału i dostosuj luz zatrzasku. Szerokość zatrzasku określa języczki blokujące; luz wieczka jest ustawiany osobno.

Cztery ścianki wewnętrzne i składane narożniki tworzą różne konstrukcje naroży. Szufladka używa dwóch osobnych składanych kluczy złącza; zamontuj je przed wsunięciem tacki. Organizer przytrzymuje końce przegród pod ściankami. Pudełko sześciokątne używa wymiaru między równoległymi bokami i ma osobne wieczko.

Użyj małej próbki do sprawdzenia zagięć i połączeń na właściwym materiale. Dodatkowe warstwy nie określają nośności. Pudełko prezentacyjne zamyka się szerokim wsuwanym językiem i służy do lekkich, płaskich przedmiotów.

Pudełko z uchwytem to otwarta tacka z oddzielnym uchwytem zatrzaskowym. Przełóż każdy języczek uchwytu przez obie wyrównane szczeliny ścianek i sprawdź występy. Przed przenoszeniem przetestuj materiał i zawartość; nie określono nośności.

Przykład w pomocy: Prezent z okienkiem

## 07 Importowanie zapisywanie i przywracanie projektów

### Zachowaj własną kopię

Edytowalny import rysunku zachowuje obsługiwane jednolite kolory, warstwy źródłowe i oryginalne kontury. Sprawdź przypisania w Warstwach i przygotuj zadania przed cięciem.

PDF, EPS, zgodne pliki AI i CDR oferują edytowalne ścieżki, gdy można zachować całą wybraną stronę. Nieobsługiwany tekst, obrazy, przycinanie, gradienty lub efekty nadal można wstawić przez Renderuj do druku. Grubość obrysu nie jest odsunięciem ścieżki cięcia.

DXF zachowuje warstwy źródłowe i kolory, korzystając ze stałej palety podglądu. Style wydruku CAD i nieobsługiwane obiekty nie są odtwarzane.

Importuj warstwy PSD zachowuje obsługiwane warstwy pikselowe jako osobne, wyrównane obrazy do druku, wraz z nazwami i widocznością. Przy nieobsługiwanych efektach warstw wstaw scalony obraz.

Wstaw do drukowania zachowuje kolory i przezroczystość obrazu. Użyj opcji Obrysuj zamiast tego, aby utworzyć kontury do cięcia lub rysowania na podstawie kontrastu.

Edytowalny import SVG zachowuje jednolite kolory RGB i nazwane warstwy. Sprawdź przypisania w Warstwach i przygotuj zadania przed cięciem.

Wypełnienia SVG zachowują otwory i wzajemne położenie jako edytowalne kontury. Jeśli kształt ma wypełnienie i obrys, używany jest kolor wypełnienia. Aby zachować wygląd grubości obrysów, przezroczystości, gradientów i efektów, wybierz Renderuj do druku.

Podglądy SVG obejmują grafikę poza stroną źródłową. Przycinanie obiektów i oryginalne proporcje są zachowane.

Podglądy rysunków mają białe tło. CDR obejmuje drukowaną grafikę poza stroną źródłową, a DXF cały rysunek w przestrzeni modelu. Renderowany obraz wstawiony do druku odpowiada podglądowi.

Import obrazu obsługuje PNG, JPEG, WebP, GIF, BMP, ICO, TIFF i scalone podglądy PSD. Animacje i wielostronicowy TIFF używają pierwszej klatki lub strony. HEIC i AVIF zależą od urządzenia. Import z aparatu używa zdjęcia w pełnym rozmiarze.

Pliki rysunków wybierasz bez filtra typu, aby Android pokazywał także pliki CDR i AI. Podgląd druku DXF obejmuje geometrię po obu stronach początku układu.

Jeśli edytowalny rysunek wychodzi poza arkusz, wybierz Dopasuj rysunek do arkusza, aby widzieć wszystkie kontury. Może to zmniejszyć wymiary. Zachowaj oryginalne współrzędne zachowuje rozmiar i położenie źródłowe. Pusty podgląd PDF pliku AI wymaga ponownego eksportu lub innego formatu.

Wybierz Edytowalne ścieżki cięcia, aby zachować obsługiwane wektory, lub Renderuj do druku, aby wstawić pokazany obraz. Ustaw szerokość obrazu, sprawdź drobne szczegóły i wstaw go.

Otwórz przykład, aby go poznać. Dołączony oryginał pozostaje dostępny; zapisz zmienioną wersję jako własny projekt.

Nazwa projektu jest widoczna u góry. Znacznik wyboru oznacza zapis, a gwiazdka — niezapisane zmiany.

Aplikacja zapisuje aktywny projekt na tym urządzeniu, aby przywrócić go po powrocie z tła lub ponownym uruchomieniu. Po ponownym uruchomieniu sprawdź zadanie i ponownie potwierdź założony materiał oraz wyrównanie maty.

Przy otwieraniu innego projektu aplikacja pyta o niezapisaną pracę. Użyj Projekt → Zapisz lub Zapisz jako, jeśli pozwala na to Twój plan.

Zmiana języka dotyczy interfejsu i pomocy. Twój tekst oraz nazwy obiektów i plików pozostają bez zmian.

Przykład w pomocy: Małe podziękowanie

## 08 Wektoryzacja obrazów i edycja krzywych

### Edycja krzywych i węzłów

Przy zdjęciach użyj równomiernego światła i kontrastowego tła, a aparat ustaw na wprost rysunku. Zacznij od automatycznego kontrastu, porównaj obraz ze ścieżkami i powiększ szczegóły palcami. Uprość szczegóły po przekroczeniu limitu punktów cięcia. Opcjonalne usuwanie plamek zachowuje otwory. Wybierz Wytnij obrysy dla noża lub Narysuj obrysy dla pisaka. Wektoryzacja odwzorowuje obrysy, więc grube linie mają dwie krawędzie.

Podczas przygotowania podglądu obrysowywania widać postęp. Możesz anulować lub zmienić próg; wstawić można tylko najnowszy podgląd.

Wektoryzacja zaczyna z wygładzaniem 300%. Zmień Siłę wygładzania lub wyłącz Wygładzaj obrysy; podgląd aktualizuje się przed dodaniem. Porównaj Obraz ze ścieżkami i sprawdź drobne szczegóły. Wygładzanie krzywych w Edycji zachowuje przypisane narzędzie, nacisk i prędkość.

Obrysowanie obrazu wygładza schodki pikseli w ścieżki cięcia, zachowując narożniki, otwory i oddzielne kształty. Sprawdź podgląd przed wstawieniem; import tylko do druku zachowuje wygląd obrazu. Duże zdjęcia są automatycznie zmniejszane, aby zmieściły się w projekcie.

Zaznacz edytowalny obiekt i wybierz „Edytuj punkty”. Przeciągnij węzeł, aby zmienić kontur; powiększ widok dla precyzji.

Przytrzymaj etykietę Edytuj punkty lub Zaznacz obszar, aby zobaczyć opis gestów. Myszą najedź na etykietę.

Aproksymacja krzywych w Ustawieniach aplikacji określa dokładność nowych okręgów, elips i krzywych Béziera oraz zamiany łuków na odcinki dla ploterów. Domyślnie: 0,01 mm; mniejsze wartości tworzą więcej odcinków. Dokładne łuki FilmCut i istniejące rysunki z odcinków pozostają bez zmian. Zmiana dokładności wymaga ponownego sprawdzenia zadania. Zaokrąglanie współrzędnych urządzenia dodaje własny błąd.

Dodaj → Krzywa Béziera tworzy krzywą z punktów kontrolnych. Zachowaj kopię przed uproszczeniem lub wygładzeniem złożonego kształtu.

Otwórz Szczegóły, aby uzyskać dodatkowe wskazówki. Pomoc zawiera pełne lekcje i edytowalne przykłady.

Przykład w pomocy: Rozkwit

## 09 Przygotowanie i podgląd produkcji

### Prowadzony

Przygotowanie pokazuje zwarte ustawienia materiału, maty i plotera. Rozwiń Materiał lub Matę do cięcia, aby zobaczyć więcej ustawień. Otwórz bezpośrednio Podgląd produkcji, aby ustawić układ, zadania lub skorzystać z przewodnika.

Wybierz grafikę do przygotowania. Projekt pozostaje edytowalny.

Wybierz materiał i sprawdź ustawienia narzędzia każdego obiektu. Przetestuj je na małym kawałku rzeczywistego materiału.

Ustaw liczbę kopii, orientację, marginesy i nacięcia do wybierania we wspólnym układzie produkcji.

Sprawdź geometrię i obwiednię ruchów. Przegląd zadania zachowuje wszystkie kontrole gotowości i rejestracji.

Przejrzyj zadanie, zmieniaj narzędzia zgodnie z komunikatami i uruchom je jawnie. Dalej nigdy nie rozpoczyna ruchu.

W krótkim oknie przewiń formularz do przycisków. Wpisywanie na klawiaturze zachowuje ten sam szkic.

Przykład w pomocy: Prowadzony

### Podgląd produkcji

Projekt pozostaje bez zmian, dopóki nie wybierzesz Zastosuj układ do projektu.

Sprawdź drobne szczegóły, odległość od krawędzi i ustawienia narzędzi na próbce.

Otwórz Szczegóły, aby uzyskać dodatkowe wskazówki. Pomoc zawiera pełne lekcje i edytowalne przykłady.

Przykład w pomocy: Podgląd produkcji

## 10 Warstwy materiały i zadania

### Warstwy i zadania

Przypisz materiał w Edytuj warstwę. Każdy obiekt dziedziczy materiał swojej warstwy. Przeniesienie obiektu do innej warstwy zmienia jego materiał; narzędzia i liczba przejść pozostają przy obiekcie.

Edytowalny import SVG zachowuje jednolite kolory RGB i nazwane warstwy. Sprawdź przypisania w Warstwach i przygotuj zadania przed cięciem.

Wypełnienia SVG zachowują otwory i wzajemne położenie jako edytowalne kontury. Jeśli kształt ma wypełnienie i obrys, używany jest kolor wypełnienia. Aby zachować wygląd grubości obrysów, przezroczystości, gradientów i efektów, wybierz Renderuj do druku.

Edytowalny import rysunku zachowuje obsługiwane jednolite kolory, warstwy źródłowe i oryginalne kontury. Sprawdź przypisania w Warstwach i przygotuj zadania przed cięciem.

Wstaw do drukowania zachowuje kolory i przezroczystość obrazu. Użyj opcji Obrysuj zamiast tego, aby utworzyć kontury do cięcia lub rysowania na podstawie kontrastu.

Znaczniki montażowe to pomocnicze kwadraty cięcia, a nie optyczne znaczniki Print & Cut. Każda zmiana materiału wymaga potwierdzenia.

Potwierdź lustrzaną orientację HTV.

Kolejność montażu i cięcia są osobne. Użyj zapisanej odwrotnej transformacji arkusza, aby wyrównać warstwy.

Nowe warstwy otrzymują bieżący materiał. Materiał warstwy zmienisz w Edytuj warstwę.

Nowe projekty otrzymują bieżący materiał na warstwie Default. Brakujący materiał przypisz w Edytuj warstwę przed sprawdzeniem zadania.

Zadania dziedziczą materiał swoich warstw. Materiał zmienisz w Edytuj warstwę.

Przygotowanie pokazuje zwarte ustawienia materiału, maty i plotera. Rozwiń Materiał lub Matę do cięcia, aby zobaczyć więcej ustawień. Otwórz bezpośrednio Podgląd produkcji, aby ustawić układ, zadania lub skorzystać z przewodnika.

Zapisz ustawienia w Przygotuj zadania. W zakładce Cięcie wybierz zadanie produkcyjne, potwierdź założony materiał, sprawdź zadanie i wyrównanie maty przed rozpoczęciem.

Cięcie pokazuje wybór Zadania, nazwę materiału i duży podgląd. Narzędzia i liczbę przejść zmienisz we Właściwościach obiektu.

Wybierz zadanie w zakładce Cięcie, aby zobaczyć tylko jego elementy i znaczniki montażowe. Osobno potwierdź założony materiał przed sprawdzeniem zadania i rozpoczęciem cięcia.

Warstwy łączą organizację projektu z przypisaniami materiałów. Otwórz Edytuj warstwę, aby przypisać materiał. Przygotuj zadania pozwala ustawić znaczniki montażowe, kolejność zadań i położenie na arkuszu.

Na tablecie lub szerokim ekranie rozwiń warstwę w drzewie Warstwy. Dotknij obiektu, aby go zaznaczyć; przycisk zaznaczenia dodaje go lub usuwa z zaznaczenia. Menu warstwy i obiektu otwierają właściwości. Użyj Dodaj warstwę lub Przenieś do warstwy. Przytrzymaj nazwę obiektu, aby przeciągnąć go na warstwę. Po przeniesieniu obiekt otrzymuje materiał warstwy docelowej.

Kolor projektu, materiał i zadanie produkcyjne są niezależne. Kilka warstw projektu może należeć do jednego zadania, a ten sam materiał można wykorzystać w osobnych zadaniach.

Otwórz Szczegóły, aby uzyskać dodatkowe wskazówki. Pomoc zawiera pełne lekcje i edytowalne przykłady.

W krótkim oknie przewiń formularz do przycisków. Wpisywanie na klawiaturze zachowuje ten sam szkic.

Przykład w pomocy: Warstwy i zadania

## 11 Naklejki i etykiety QR

### Zrób naklejkę

Zaznaczone obiekty tworzą jedną naklejkę. Najpierw zaimportuj grafikę, potem ją zaznacz.

Odsunięcie to margines cięcia; nie dodaje białego atramentu.

Jeden arkusz w skali 1:1. Prepare zapisuje rozmiar papieru i marginesy oraz rezerwuje miejsce na znaczniki. Sprawdź marginesy po każdej zmianie drukarki.

Wydrukuj grafikę i znaczniki, potem użyj ręcznej rejestracji Print & Cut. Podgląd nigdy nie rozpoczyna cięcia.

Maskę sylwetki wybierasz jawnie; nieprzezroczysty obraz nie określa swojego tła.

Kreatory etykiet i naklejek mogą zastosować szkic i przejść do Zrób naklejkę lub Etykieta QR.

Użyj Podgląd i drukowanie, sprawdź ID arkusza i skalę 100%, a następnie potwierdź wydruk i marginesy drukarki przed przejściem do wyrównania.

Drukowanie wymaga Basic lub Pro. Otwórz Plany, aby przywrócić zakup lub wybrać plan.

Otwórz Szczegóły, aby uzyskać dodatkowe wskazówki. Pomoc zawiera pełne lekcje i edytowalne przykłady.

W krótkim oknie przewiń formularz do przycisków. Wpisywanie na klawiaturze zachowuje ten sam szkic.

Przykład w pomocy: Zrób naklejkę

### Etykieta QR

Sprawdzono całą kodowaną treść.

Pozostają osobne części i otwory. Podczas montażu zachowaj jasne tło i całą strefę ciszy.

Minimalny detal nie jest potwierdzony dla tego materiału. Wykonaj próbę i niezależnie zeskanuj wyprodukowany QR.

Strefa ciszy ma cztery moduły z każdej strony i mieści się w wybranym rozmiarze. Regeneracja jest jawna.

Rozmiar obejmuje strefę ciszy.

Przykład w pomocy: Etykieta QR

## 12 Pasowanie wydruku i cięcia

### Ręczne Print Cut

W ręcznym Print & Cut wydrukuj arkusz w rzeczywistym rozmiarze i sprawdź marginesy. Załaduj go bez narzędzia i ustaw środek uchwytu nad znacznikami A, B, D i C. Dopasuj pozycję małymi ruchami i zapisz ją po zatrzymaniu plotera.

Czwarty znacznik sprawdza wyrównanie z tolerancją 0,50 mm. Zamontuj narzędzie bez przesuwania arkusza i potwierdź Start cięcia. Używaj jednego uchwytu; narzędzia o innym fizycznym przesunięciu wymagają ponownego wyrównania.

Ponowne połączenie, przesunięcie materiału, edycja projektu lub opuszczenie aplikacji unieważnia ręczne wyrównanie. Wyrównaj arkusz ponownie. Pozycje wynikają z poleceń i obserwacji użytkownika, a nie z czujnika optycznego.

Przykład w pomocy: Ręczne Print & Cut

### Optyczne Print Cut

Ustawienia znaczników są zapisywane w projekcie. Po ponownym otwarciu Cięcia wydrukuj i potwierdź aktualny arkusz; dopasowanie i potwierdzenie załadowania nigdy nie są przywracane automatycznie.

Optyczne Print & Cut pomija ruch ustawiający ostrze przy początku maty i odbicie lustrzane samego cięcia, aby ścieżki pasowały do wydruku. Zwykłe zadania zachowują swoje ustawienia.

W Cięciu otwórz Ustawienia zaawansowane, a następnie Opcje Silhouette i włącz Optyczne Print & Cut. Ustaw znaczniki, wydrukuj arkusz w rzeczywistym rozmiarze i potwierdź załadowanie. Zmiana projektu lub znaczników wymaga nowego wydruku. Korekty XY działają tylko w aplikacji, w układzie wydrukowanego arkusza.

Drukuj aktualny arkusz w skali 100%, od lewego górnego rogu papieru. Marginesy drukarki nie mogą zasłaniać znaczników. Zachowaj 22 mm odstępu grafiki od znaczników do wewnątrz. Przed każdym etapem odbywa się nowy skan trzech znaczników; błąd skanu blokuje cięcie.

Przesuń materiał przesuwa załadowany arkusz z podniesionym narzędziem i ustawia nowy początek. Wymaga wolnej drogi i późniejszego potwierdzenia zatrzymania. Ładowanie i wysuwanie obsługuj na panelu plotera. Opcjonalny powrót do początku następuje po ostatnim etapie.

Domyślnie sprawdź zatrzymanie i wybierz Gotowe po transmisji. Zakończ po zgłoszeniu gotowości urządzenia może automatycznie zakończyć etap po ostatniej odpowiedzi gotowości; nie mierzy niezależnie ruchu silników. Błąd lub Stop zawsze wymaga obserwacji.

Przykład w pomocy: Optyczne Print & Cut

## 13 Łączenie i sterowanie ploterem

### Od projektu do wykonania

Materiały obejmują folie samoprzylepne i termotransferowe, materiały na naklejki, papier, karton, tkaniny i arkusze specjalne. Grubość nominalna opisuje przykładowy materiał; dopasuj ją do swojego arkusza. Brak grubości oznacza, że trzeba najpierw zmierzyć materiał. Dane folii nie obejmują podkładu, a czasem także kleju; sprawdzając prześwit narzędzia, uwzględnij wszystkie warstwy.

Wybór materiału nie ustawia docisku, prędkości ani wysunięcia ostrza. Dobierz je do wybranego plotera w ustawieniach narzędzia lub obiektu albo na panelu plotera. Mała próba cięcia pomoże dobrać liczbę przejść i głębokość; przy nacinaniu folii pozostaw podkład nieprzecięty. Sprawdź odbicie lustrzane dla folii termotransferowej.

Nowe projekty otrzymują bieżący materiał na warstwie Default. Brakujący materiał przypisz w Edytuj warstwę przed sprawdzeniem zadania.

W Połączeniu z ploterem wybierz producenta, model i połączenie, a następnie urządzenie i Połącz. Listy urządzeń odświeżają się automatycznie, gdy ploter jest rozłączony, a aplikacja widoczna; Odśwież urządzenia rozpoczyna nowe wyszukiwanie. Udziel dostępu do Bluetooth, gdy pojawi się prośba. Dla USB wybierz Połącz i zezwól na dostęp w Androidzie; łączenie będzie kontynuowane automatycznie. Ustawienia protokołu i opcje połączenia FilmCut są zgrupowane poniżej. Rozłącz ploter przed jego zmianą. Połączono oznacza nawiązanie łącza, a nie zakończenie ruchu. Automatyczne łączenie działa dla FilmCut i Bluetooth VEVOR Smart; nigdy nie wznawia zadania.

G-code zadania FilmCut dotyczy tylko FilmCut. Zapisany nagłówek i stopka pozostają dostępne po powrocie do FilmCut; inne plotery ich nie wysyłają.

Wybierz załadowany rozmiar w Przygotowanie → Mata do cięcia. Gotowe obszary robocze obejmują szerokości zapisane dla ploterów; zmień długość przez Zmień rozmiar maty lub zapisz własną matę. Rozmiary opisują użyteczny obszar projektu, a nie zewnętrzny wymiar maty nośnej.

W bibliotece mat dotknij pozycji, aby jej użyć. Przy dużym tekście lub krótkim oknie ikony sekcji przełączają materiały, narzędzia i maty; plus dodaje własną pozycję. Przytrzymaj ikonę, aby zobaczyć jej nazwę.

Sterowanie maszyną używa tych samych strzałek dla wszystkich ploterów. Wybierz odległość przesunięcia; zapisana wartość jest używana w zakresie obsługiwanym przez wybrany ploter. Potwierdź pierwszą czynność ręczną, potem przesuwaj lub podnoś i opuszczaj narzędzie bez powtarzania tego potwierdzenia. Bazowanie FilmCut i zmiana początku pracy zawsze wymagają osobnego potwierdzenia. FilmCut używa nacisku PWM, VEVOR Smart gramów, Silhouette własnej skali siły, a plotery HPGL/DMPL ustawień panelu. W VEVOR Smart 1–4 początkowy nacisk w sterowaniu ręcznym wynosi 250 g i można go zmieniać w zakresie 250–500 g. W VEVOR Smart funkcja Narzędzie w górę zleca ruch karetki o 0,025 mm w lewo i o tyle samo w prawo. Zapewnij wolne miejsce po obu stronach karetki. Kolejne przesunięcia zachowują stan narzędzia. FilmCut i Silhouette czekają na gotowość kontrolera; VEVOR Smart i HPGL/DMPL wymagają potwierdzenia zatrzymania przy zamykaniu sterowania ręcznego. Po zatrzymaniu lub błędzie sprawdź ploter przed kontynuacją. Zatrzymanie wysyłania nie zatrzymuje ruchów HPGL/DMPL zapisanych w buforze. Załaduj materiał przy użyciu panelu plotera.

„Projektowanie” służy do tworzenia obiektów. „Przygotowanie” pozwala sprawdzić układ i narzędzia. „Cięcie” zawiera podgląd i sterowanie zadaniem.

Sprawdź każdy etap narzędzia i dobierz ustawienia do materiału. Przećwicz pracę z wirtualnym ploterem przed użyciem urządzenia.

Przykłady służą do nauki i nie są skalibrowanymi profilami materiału. Przed produkcją wykonaj próbę na skrawku i sprawdź dopasowanie wydruku.

Otwórz Szczegóły, aby uzyskać dodatkowe wskazówki. Pomoc zawiera pełne lekcje i edytowalne przykłady.

Przykład w pomocy: Jeszcze jeden rozdział

## 14 Konfiguracja i obsługa HPGL i DMPL

### Plotery HPGL DMPL

W Połączeniu z ploterem wybierz producenta, model i połączenie, a następnie urządzenie i Połącz. Listy urządzeń odświeżają się automatycznie, gdy ploter jest rozłączony, a aplikacja widoczna; Odśwież urządzenia rozpoczyna nowe wyszukiwanie. Udziel dostępu do Bluetooth, gdy pojawi się prośba. Dla USB wybierz Połącz i zezwól na dostęp w Androidzie; łączenie będzie kontynuowane automatycznie. Ustawienia protokołu i opcje połączenia FilmCut są zgrupowane poniżej. Rozłącz ploter przed jego zmianą. Połączono oznacza nawiązanie łącza, a nie zakończenie ruchu. Automatyczne łączenie działa dla FilmCut i Bluetooth VEVOR Smart; nigdy nie wznawia zadania.

Interfejs drukarki USB łączy się bezpośrednio ze standardowym dwukierunkowym interfejsem z wejściem i wyjściem bulk. Interfejsy USB producenta wymagają osobnego sterownika. Dopasuj język plotera; do adapterów szeregowych wybierz USB–serial.

Dla CE LITE-50 wybierz jego profil Graphtec i połączenie USB. Na ploterze wybierz HPGL i początek LOWER LEFT. Pozostaw osie profilu: X do przodu, Y w prawo. Transmisja USB korzysta ze zgłaszanego przez ploter wolnego miejsca w buforze. Siłę i prędkość ustaw na panelu plotera. Obszar roboczy 498 mm obejmuje maksymalną szerokość cięcia; dostosuj długość do załadowanego materiału, maksymalnie 3000 mm.

Dla HPGL/DMPL mata projektu określa granice cięcia i sterowania maszyną oraz szerokość używaną do przeliczania osi. Połączenie zawiera ustawienia protokołu i transmisji. Dopasuj dostępny obszar załadowanego materiału do maty projektu. Limity modelu są sprawdzane przed ruchem.

Wybierz załadowany rozmiar w Przygotowanie → Mata do cięcia. Gotowe obszary robocze obejmują szerokości zapisane dla ploterów; zmień długość przez Zmień rozmiar maty lub zapisz własną matę. Rozmiary opisują użyteczny obszar projektu, a nie zewnętrzny wymiar maty nośnej.

W bibliotece mat dotknij pozycji, aby jej użyć. Przy dużym tekście lub krótkim oknie ikony sekcji przełączają materiały, narzędzia i maty; plus dodaje własną pozycję. Przytrzymaj ikonę, aby zobaczyć jej nazwę.

Sterowanie maszyną używa tych samych strzałek dla wszystkich ploterów. Wybierz odległość przesunięcia; zapisana wartość jest używana w zakresie obsługiwanym przez wybrany ploter. Potwierdź pierwszą czynność ręczną, potem przesuwaj lub podnoś i opuszczaj narzędzie bez powtarzania tego potwierdzenia. Bazowanie FilmCut i zmiana początku pracy zawsze wymagają osobnego potwierdzenia. FilmCut używa nacisku PWM, VEVOR Smart gramów, Silhouette własnej skali siły, a plotery HPGL/DMPL ustawień panelu. W VEVOR Smart 1–4 początkowy nacisk w sterowaniu ręcznym wynosi 250 g i można go zmieniać w zakresie 250–500 g. W VEVOR Smart funkcja Narzędzie w górę zleca ruch karetki o 0,025 mm w lewo i o tyle samo w prawo. Zapewnij wolne miejsce po obu stronach karetki. Kolejne przesunięcia zachowują stan narzędzia. FilmCut i Silhouette czekają na gotowość kontrolera; VEVOR Smart i HPGL/DMPL wymagają potwierdzenia zatrzymania przy zamykaniu sterowania ręcznego. Po zatrzymaniu lub błędzie sprawdź ploter przed kontynuacją. Zatrzymanie wysyłania nie zatrzymuje ruchów HPGL/DMPL zapisanych w buforze. Załaduj materiał przy użyciu panelu plotera.

Plotery bez przesuwania względnego używają docelowych współrzędnych X i Y oraz przycisku Przesuń; te pola określają cel, a nie odczytaną pozycję.

W Sterowaniu maszyną Współrzędne docelowe to docelowe pozycje X i Y. Otwórz Szczegóły, aby poznać zasady współrzędnych.

Profile Skycut, USCutter i Teneth obsługują podstawowe cięcie i rysowanie. Aktywne narzędzie, nacisk i prędkość ustaw na ploterze. Wyrównywanie kamerą i automatyczna zmiana narzędzi wymagają dodatkowej obsługi konkretnego modelu.

Dla urządzeń HPGL z udokumentowaną obsługą ESC.B włącz Kontrolę bufora w Ustawieniach protokołu. Połączenie musi zwracać dziesiętną liczbę wolnych bajtów zakończoną CR. Zamiast ograniczenia tempa aplikacja odpytuje bufor przed blokami do 256 bajtów, podczas cięcia i sterowania maszyną. XON/XOFF pozostaje dostępne, jeśli jest obsługiwane. Pełny bufor jest odpytywany co 100 ms przez maksymalnie 60 sekund; brak odpowiedzi zatrzymuje transmisję po 5 sekundach. Błąd zamyka połączenie bez powtarzania danych. Wolny bufor nigdy nie potwierdza zakończenia ruchu. Dla innych urządzeń i DMPL pozostaw tę opcję wyłączoną.

W Cut dla Generic procent oznacza wysłane dane, a nie wykonany ruch. Po wysłaniu całości pasek aktywności pozostaje widoczny podczas oczekiwania na koniec cięcia. Potwierdź zakończenie dopiero, gdy ploter wykona wszystkie ruchy. Zadanie przerwane lub odtworzone po restarcie jest oznaczone jako niepotwierdzone. Upływ czasu ani odebrany bajt nie kończą zadania automatycznie.

Wybierz dokładnego producenta i model lub Generic z HPGL albo DMPL, jeśli nie ma gotowego profilu. Profile modeli określają język, skalę i dostępne połączenia; nie rozpoznają podłączonego urządzenia. Graphtec obejmuje Craft Robo z własnym sposobem łączenia. VEVOR Smart używa własnego protokołu; profile KH, KI i SK korzystają z języka wskazanego dla danego modelu. Dopasuj ustawienia panelu podane w Ustawieniach protokołu. Ustaw obszar załadowanego materiału, narzędzie, siłę i prędkość na ploterze. Dostępność USB zależy od wybranego modelu. Wybierz jedno z jego dostępnych połączeń.

W profilach konkretnych modeli HPGL/DMPL sprawdź Osie współrzędnych przed połączeniem. To dodatnie kierunki poleceń widziane od przodu: do przodu oznacza od użytkownika wzdłuż osi podawania. Profile używają udokumentowanych osi, jeśli są dostępne; w pozostałych przypadkach wybierz je jawnie. Dopasuj początek na urządzeniu i wyłącz obrót, odbicie lustrzane oraz skalowanie. Przed zadaniem sprawdź mały ruch z podniesionym narzędziem. Port szeregowy wymaga obsługiwanego adaptera USB–szeregowego; pozostałe opcje używają przezroczystego adaptera SPP lub mostu surowego TCP.

Dla HPGL/DMPL włącz XON/XOFF lub ESC.B tylko wtedy, gdy obsługuje je urządzenie i połączenie, i dostosuj prędkość transmisji do bufora. Sterowanie maszyną używa wspólnych przycisków przesuwania oraz podnoszenia i opuszczania narzędzia. Zatrzymanie wysyłania zamyka łącze; ruch z bufora zatrzymaj na panelu plotera. Potwierdź zatrzymanie po zadaniu lub przy zamykaniu sterowania ręcznego. Każdy etap narzędzia uruchamia się osobno; przerwane zadania nigdy nie wznawiają się automatycznie.

Przykład w pomocy: Plotery HPGL / DMPL

## 15 Silhouette i AutoBlade

### Pierwsze zadanie Silhouette Craft Robo

W Połączeniu z ploterem wybierz producenta, model i połączenie, a następnie urządzenie i Połącz. Listy urządzeń odświeżają się automatycznie, gdy ploter jest rozłączony, a aplikacja widoczna; Odśwież urządzenia rozpoczyna nowe wyszukiwanie. Udziel dostępu do Bluetooth, gdy pojawi się prośba. Dla USB wybierz Połącz i zezwól na dostęp w Androidzie; łączenie będzie kontynuowane automatycznie. Ustawienia protokołu i opcje połączenia FilmCut są zgrupowane poniżej. Rozłącz ploter przed jego zmianą. Połączono oznacza nawiązanie łącza, a nie zakończenie ruchu. Automatyczne łączenie działa dla FilmCut i Bluetooth VEVOR Smart; nigdy nie wznawia zadania.

Sterowanie maszyną używa tych samych strzałek dla wszystkich ploterów. Wybierz odległość przesunięcia; zapisana wartość jest używana w zakresie obsługiwanym przez wybrany ploter. Potwierdź pierwszą czynność ręczną, potem przesuwaj lub podnoś i opuszczaj narzędzie bez powtarzania tego potwierdzenia. Bazowanie FilmCut i zmiana początku pracy zawsze wymagają osobnego potwierdzenia. FilmCut używa nacisku PWM, VEVOR Smart gramów, Silhouette własnej skali siły, a plotery HPGL/DMPL ustawień panelu. W VEVOR Smart 1–4 początkowy nacisk w sterowaniu ręcznym wynosi 250 g i można go zmieniać w zakresie 250–500 g. W VEVOR Smart funkcja Narzędzie w górę zleca ruch karetki o 0,025 mm w lewo i o tyle samo w prawo. Zapewnij wolne miejsce po obu stronach karetki. Kolejne przesunięcia zachowują stan narzędzia. FilmCut i Silhouette czekają na gotowość kontrolera; VEVOR Smart i HPGL/DMPL wymagają potwierdzenia zatrzymania przy zamykaniu sterowania ręcznego. Po zatrzymaniu lub błędzie sprawdź ploter przed kontynuacją. Zatrzymanie wysyłania nie zatrzymuje ruchów HPGL/DMPL zapisanych w buforze. Załaduj materiał przy użyciu panelu plotera.

Cięcie pokazuje duży podgląd. Narzędzia i przejścia edytujesz we Właściwościach obiektu. Ustawienia zaawansowane zawierają matę, rejestrację optyczną, powrót do początku i kończenie po gotowości urządzenia.

Dla Bluetooth LE włącz Bluetooth w Androidzie i wybierz Bluetooth LE w polu Połączenie. Lista odświeża się automatycznie i zachowuje wybór do zmiany modelu lub połączenia. Odśwież urządzenia pozwala nadać dostęp lub ponowić wyszukiwanie. USB wyszukuje tylko urządzenia USB. Przy początkowym błędzie BLE 133 aplikacja podejmuje do trzech prób połączenia. Późniejsze błędy nigdy nie powodują powtarzania poleceń ani wznawiania zadania.

Ustawienia znaczników są zapisywane w projekcie. Po ponownym otwarciu Cięcia wydrukuj i potwierdź aktualny arkusz; dopasowanie i potwierdzenie załadowania nigdy nie są przywracane automatycznie.

Optyczne Print & Cut pomija ruch ustawiający ostrze przy początku maty i odbicie lustrzane samego cięcia, aby ścieżki pasowały do wydruku. Zwykłe zadania zachowują swoje ustawienia.

W Cięciu otwórz Ustawienia zaawansowane, a następnie Opcje Silhouette i włącz Optyczne Print & Cut. Ustaw znaczniki, wydrukuj arkusz w rzeczywistym rozmiarze i potwierdź załadowanie. Zmiana projektu lub znaczników wymaga nowego wydruku. Korekty XY działają tylko w aplikacji, w układzie wydrukowanego arkusza.

Drukuj aktualny arkusz w skali 100%, od lewego górnego rogu papieru. Marginesy drukarki nie mogą zasłaniać znaczników. Zachowaj 22 mm odstępu grafiki od znaczników do wewnątrz. Przed każdym etapem odbywa się nowy skan trzech znaczników; błąd skanu blokuje cięcie.

Przesuń materiał przesuwa załadowany arkusz z podniesionym narzędziem i ustawia nowy początek. Wymaga wolnej drogi i późniejszego potwierdzenia zatrzymania. Ładowanie i wysuwanie obsługuj na panelu plotera. Opcjonalny powrót do początku następuje po ostatnim etapie.

Domyślnie sprawdź zatrzymanie i wybierz Gotowe po transmisji. Zakończ po zgłoszeniu gotowości urządzenia może automatycznie zakończyć etap po ostatniej odpowiedzi gotowości; nie mierzy niezależnie ruchu silników. Błąd lub Stop zawsze wymaga obserwacji.

Silhouette zmienia siłę i prędkość między obiektami w tym samym etapie narzędzia. Przejścia automatycznie powtarzają każdy obrys. Zmiany narzędzia, uchwytu, głębokości i kolejności procesu mogą wymagać osobnych etapów.

Obiekty używają ustawień przypisanego narzędzia w zakresie obsługiwanym przez wybrany model. Wyłącz Użyj ustawień narzędzia we właściwościach obiektu, aby je zmienić. Inne modele zachowują swoje wartości. Profile HPGL/DMPL używają nacisku i prędkości z panelu plotera; właściwości obiektu nie pokazują tych wartości ani przełącznika. Przypisane ustawienia narzędzia sprawdzisz lub zmienisz we Właściwościach obiektu.

Obiekty zachowują przypisaną kopię ustawień narzędzia. Po edycji narzędzia w bibliotece wybierz jego zaktualizowany wpis we Właściwościach obiektu.

AutoBlade jest dostępny dla etapów z nożem na Cameo 3, 4, 5 oraz Portrait 2 i 3, tylko w uchwycie 1. Włącz go w ustawieniach narzędzia lub obiektu i wybierz głębokość 0–10. Ta skala nie oznacza milimetrów.

Cameo 4, Cameo 5 i Portrait 3 muszą zgłosić AutoBlade przed regulacją. Pusty uchwyt, nieznane lub inne narzędzie blokuje zadanie. Na Cameo 3 i Portrait 2 potwierdź zamontowanie AutoBlade przed startem.

Po regulacji ostrza aplikacja sprawdza gotowość przed wysłaniem ścieżek cięcia. Stop może przerwać oczekiwanie. Po utracie połączenia regulacja nigdy nie jest automatycznie powtarzana.

Silhouette / Craft Robo obsługuje pisaki, noże ręczne i AutoBlade w wybranych modelach. Cameo i Portrait oferują optyczne Print & Cut.

W Połączeniu wybierz dokładny model. Wszystkie wymienione modele obsługują USB; Cameo 3–5 i Portrait 2–3 oferują też Bluetooth LE. Podawaj i wysuwaj materiał przyciskami plotera.

Aplikacja odpytuje stan gotowy/zajęty/brak materiału między małymi paczkami. Po ostatniej odpowiedzi gotowości sprawdź rezultat i wybierz Gotowe. Przerwane zadanie nie jest automatycznie wznawiane ani powtarzane. Stop żąda resetu; zawsze sprawdź fizyczne zatrzymanie.

Przykład w pomocy: Pierwsze zadanie Silhouette / Craft Robo

## 16 Praca z VEVOR Smart

### Pierwsze zadanie VEVOR Smart

Smart4 może korzystać z Bluetooth SPP lub USB przez OTG. USB to osobne połączenie z surowym PLT: przyznaj dostęp w Androidzie, potwierdź załadowanie maty i uruchom zadanie. Zapisane bajty nie potwierdzają końca ruchu. Poczekaj na zatrzymanie plotera przed potwierdzeniem zakończenia. USB obsługuje tylko rozpoznany interfejs Smart4; Smart1–3 korzystają z Bluetooth.

W Cięciu otwórz Ustawienia zaawansowane, aby znaleźć Użyj nacisku i prędkości z aplikacji oraz Wysuń.

W Połączeniu z ploterem wybierz producenta, model i połączenie, a następnie urządzenie i Połącz. Listy urządzeń odświeżają się automatycznie, gdy ploter jest rozłączony, a aplikacja widoczna; Odśwież urządzenia rozpoczyna nowe wyszukiwanie. Udziel dostępu do Bluetooth, gdy pojawi się prośba. Dla USB wybierz Połącz i zezwól na dostęp w Androidzie; łączenie będzie kontynuowane automatycznie. Ustawienia protokołu i opcje połączenia FilmCut są zgrupowane poniżej. Rozłącz ploter przed jego zmianą. Połączono oznacza nawiązanie łącza, a nie zakończenie ruchu. Automatyczne łączenie działa dla FilmCut i Bluetooth VEVOR Smart; nigdy nie wznawia zadania.

Sterowanie maszyną używa tych samych strzałek dla wszystkich ploterów. Wybierz odległość przesunięcia; zapisana wartość jest używana w zakresie obsługiwanym przez wybrany ploter. Potwierdź pierwszą czynność ręczną, potem przesuwaj lub podnoś i opuszczaj narzędzie bez powtarzania tego potwierdzenia. Bazowanie FilmCut i zmiana początku pracy zawsze wymagają osobnego potwierdzenia. FilmCut używa nacisku PWM, VEVOR Smart gramów, Silhouette własnej skali siły, a plotery HPGL/DMPL ustawień panelu. W VEVOR Smart 1–4 początkowy nacisk w sterowaniu ręcznym wynosi 250 g i można go zmieniać w zakresie 250–500 g. W VEVOR Smart funkcja Narzędzie w górę zleca ruch karetki o 0,025 mm w lewo i o tyle samo w prawo. Zapewnij wolne miejsce po obu stronach karetki. Kolejne przesunięcia zachowują stan narzędzia. FilmCut i Silhouette czekają na gotowość kontrolera; VEVOR Smart i HPGL/DMPL wymagają potwierdzenia zatrzymania przy zamykaniu sterowania ręcznego. Po zatrzymaniu lub błędzie sprawdź ploter przed kontynuacją. Zatrzymanie wysyłania nie zatrzymuje ruchów HPGL/DMPL zapisanych w buforze. Załaduj materiał przy użyciu panelu plotera.

Po ostatnim etapie narzędzia VEVOR otrzymuje PU0,0;PG;, aby wrócić i wysunąć matę. Zapewnij wolną przestrzeń dla maty i potwierdź Gotowe dopiero po zatrzymaniu ruchu.

VEVOR przez Bluetooth wysyła do 30 poleceń w pakiecie. Błędy CRC lub brak odpowiedzi pozwalają na trzy ponowienia po przerwach 0,5, 1 i 2 sekund. USB używa ograniczonych zapisów surowych danych i nigdy nie powtarza bloku po zapisie o niepewnym wyniku. Postęp transferu nie potwierdza końca ruchu; po przerwaniu transmisji sprawdź wynik.

Obrys ma szczegóły mniejsze od rozdzielczości plotera. Uprość lub powiększ projekt i sprawdź zadanie ponownie.

Po ponownym uruchomieniu z niepotwierdzoną operacją możesz dalej projektować. Wybierz Sprawdź poprzednią operację plotera, a potem Gotowe w Cięciu po sprawdzeniu, że ploter stoi. Cięcie i zmiana plotera pozostają zablokowane do potwierdzenia; zadanie nie jest wznawiane.

Aby zmienić połączony, bezczynny VEVOR, wybierz Zmień ploter przy wyborze producenta i modelu. Rozłączy to urządzenie i wstrzyma automatyczne łączenie, umożliwiając wybór innego plotera.

Użyj nacisku i prędkości z aplikacji w Cięciu jest domyślnie włączone. Wysyła nacisk i prędkość obiektu lub narzędzia. Wyłącz, aby użyć ustawień plotera; FS i VS nie są wysyłane. Prędkość to mm/min podzielone przez 60, zaokrąglone do całych mm/s: 2500 daje VS42. Dozwolony zakres to 600–18000 mm/min.

Połącz się raz, aby zapamiętać tożsamość Bluetooth i model. Automatyczne łączenie działa na pierwszym planie i nigdy nie wznawia zadania. Rozłącz wstrzymuje automatyczne próby.

W Przygotowaniu wybierz oryginalną matę VEVOR 12 × 12 lub 12 × 24 cali. Profile używają 304,8 × 304,8 mm oraz 304,8 × 609,7 mm. Mniejsze własne obszary pracy używają najmniejszego oryginalnego profilu, w którym się mieszczą.

Karta Cięcie pokazuje projekt przed sprawdzeniem, a przygotowaną ścieżkę narzędzia po sprawdzeniu. Rozpocznij cięcie pozostaje niedostępne, dopóki zadanie nie zostanie sprawdzone.

Nacisk i przejścia pochodzą z ustawień obiektu lub narzędzia. VEVOR podaje 10–500 gf dla prawego uchwytu i 50–500 gf dla lewego. Wartości FS nadal wymagają próby na materiale.

Naciśnij Rozpocznij cięcie i potwierdź narzędzie, matę oraz punkt początkowy. Potwierdzenie testu materiału pojawia się tylko wtedy, gdy wymaga go wybrany proces.

Smart 1 i 2 używają fizycznych przycisków podawania i startu. Gdy pojawi się prośba, naciśnij przycisk na maszynie i potwierdź w aplikacji. Nieznany stan materiału nie oznacza wysuniętej maty.

Gdy stan materiału jest nieznany, sprawdź maszynę i wybierz Sprawdź matę, aby ponowić odczyt. Aplikacja nie powtarza konfiguracji ani nie wysyła automatycznie zatrzymania. Utrata połączenia, brak odpowiedzi lub odrzucona konfiguracja blokują zadanie i wymagają sprawdzenia plotera.

Załaduj matę przyciskami plotera. Aby ją wysunąć, połącz się z nieruchomym ploterem i wybierz Wysuń na karcie Cięcie. Zapewnij macie swobodę ruchu, obserwuj ją i wybierz Gotowe, gdy będzie wysunięta, a ploter nieruchomy.

Zatrzymaj może przerwać cięcie lub wysuwanie, gdy ruch nadal trwa. Wybierz Gotowe po sprawdzeniu, że ploter jest nieruchomy. Poprawne połączenie pozostaje otwarte; przerwana sesja łączy się ponownie dopiero po obserwacji.

Procent oznacza potwierdzone dane Bluetooth lub zapisane dane USB, a nie wykonane cięcie. Pełny transfer nie dowodzi zakończenia pracy plotera. Potwierdź zakończenie po obserwacji maszyny.

Noże montuj w prawym uchwycie (R). Pisaki oraz narzędzia do bigowania i grawerowania używają lewego uchwytu (L). Aplikacja wybiera uchwyt dla każdego etapu; przed jego rozpoczęciem potwierdź zamontowane narzędzie.

W krótkim oknie przewiń formularz do przycisków. Wpisywanie na klawiaturze zachowuje ten sam szkic.

Przykład w pomocy: Pierwsze zadanie VEVOR Smart

## 17 Pomoc i zgłoszenia dotyczące ploterów

### Wsparcie ploterów

Otwórz Więcej, a potem Zgłoś problem z ploterem lub Poproś o obsługę nowego plotera. Przed zgłoszeniem problemu wybierz właściwy ploter. Raport obejmuje bieżącą sesję aplikacji; przygotuj go zaraz po błędzie.

Opisz problem, oczekiwany wynik i kroki jego odtworzenia. Zgłoszenie może zawierać wybrany ploter i ostatnie metadane połączenia. Nie uruchamia testu urządzenia.

Diagnostyka obejmuje bieżącą sesję aplikacji: model, protokół, ustawienia transmisji, postęp, potwierdzenia i kategorie błędów. Pomija adresy urządzeń, surowe polecenia, odpowiedzi i grafikę.

Dołączanie pełnego projektu jest domyślnie wyłączone. Pełny projekt może zawierać nazwy, tekst, zdjęcia i importowaną grafikę. Dołącz go tylko, jeśli chcesz przekazać go wsparciu.

Podaj producenta i dokładny model z etykiety. Dodaj dostępne połączenia, firmware i link do instrukcji, jeśli je znasz. Zgłoszenie nie włącza automatycznie obsługi plotera.

Sprawdź zgłoszenie, a następnie zapisz je lub udostępnij wsparciu e-mailem. Nic nie jest przesyłane automatycznie. Wybierz pocztę i sprawdź odbiorcę oraz załącznik przed wysłaniem.

Aby powtórzyć test, otwórz dołączony przykład na wolnej macie i postępuj zgodnie z lekcją. Samo zgłaszanie nie wysyła poleceń ani nie wznawia zadania. Zapisany raport nie jest wysłany; udostępnianie otwiera inną aplikację, w której dokończysz wysyłanie.

Przykład w pomocy: Plotery HPGL / DMPL
