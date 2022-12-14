# Wprowadzenie do języka Python

## Lab 00. Przygotowanie środowiska pracy.

W trakcie zajęć jako środowisko IDE będzie wykorzystywane oprogramowanie Visual Studio Code. Jest to darmowe oprogramowanie firmy Microsoft, które w krótkim czasie zdobyło bardzo wielu użytkowników dzięki możliwości instalacji wielu dodatków, które pozwalają dostosować narzędzie do konkretnego projektu. Mimo, że natywnie VSC wspiera takie języki jak C++ i C# (platforma .NET) to dzięki plug-inom można dodać wsparcie kolejnych języków, a wtyczka pozwalająca na wsparcie języka Python jest jedną z najbardziej popularnych.

**Krok 1** – pobieramy i instalujemy Visual Studio Code ze strony https://code.visualstudio.com/ oraz oprogramowanie PyCharm Community Edition ze strony https://www.jetbrains.com/pycharm/download/. W zależności od platformy (Windows, macOS, Linux) wybieramy odpowiednią paczkę.

**Krok 2** – instalacja interpretera języka Python. 
Na stronie https://www.python.org/ przechodzimy do podstrony Downloads i odnajdujemy wersję 3.9.13. (https://www.python.org/downloads/release/python-3913/). Następnie w części **Files** (na dole strony) odnajdujemy paczkę dla naszego systemu operacyjnego. Jeżeli nie jesteśmy pewni czy dysponujemy wersją 32 czy 64-bitową systemu operacyjnego, można to sprawdzić wybierając z menu kontekstowego (prawy przycisk myszy) opcję 'Właściwości' na ikonie Ten komputer (lub Mój komputer) w przypadku systemu Windows. Dla wersji 64-bit właściwą paczką dla systemu Windows będzie `Windows x86-64 executable installer`, a dla 32-bitowej `Windows x86 executable installer`.
Uruchomienie pobranego pliku skutkuje pojawieniem się okna podobnego do poniższego.

![Instalacja krok 1](images/lab_00_1.png)
 
Jeżeli jest to jedyny interpreter języka Python w naszym systemie, możemy dodać interpreter do ścieżki systemowej (zmienna środowiskowa **PATH**). Spowoduje to możliwość korzystania z interpretera nie tylko bezpośrednio z folderu, do którego został zainstalowany. Zaznaczamy więc checkbox _**„Add Python 3.9 to PATH”**_. Jest to opcja zalecana. 

W przypadku gdy w naszym systemie jest już zainstalowany interpreter Pythona i instalator to wykryje, pojawi się opcja o nazwie `Upgrade Now` jak na poniższym zrzucie ekranu. **Wybranie jej nadpisze tę wersję interpretera, co może mieć negatywne skutki dla działania projektów, które zostały na tej wersji budowane**.

Jeżeli chcemy zainstalować interpreter w domyślnej zaproponowanej lokalizacji, wybieramy opcję **„Install Now”**. Jeżeli chcemy wybrać inną ścieżkę i zobaczyć dodatkowe opcje wybieramy **„Customize installation”**. Poniżej podgląd okna z wyborem opcji do zainstalowania.

![Instalacja krok 1](images/lab_00_2.png)

Wybranie **„Next”** wyświetli poniższe okno, gdzie możemy wybrać inną ścieżkę instalacji.

![Instalacja krok 1](images/lab_00_3.png)

Dla naszych potrzeb wystarczą opcje domyślne, można jedynie wskazać inną ścieżkę instalacji.

**Krok 3** - instalacja środowiska PyCharm.  
Tutaj nie powinno być żadnych problemów w trakcie tego procesu.

**Krok 4** – (tylko w przypadku korzystania z Visual Studio Code) - instalacja plug-inu.
Uruchamiamy Visual Studio Code (przykładowe okno poniżej) i wybieramy po lewej stronie ikonę _**Extensions**_. 

![Instalacja krok 1](images/lab_00_4.png) 
 
Wyszukujemy frazę „Python” i na odpowiednim elemencie z listy wybieramy _**Install**_ (na screenie poniżej plug-in jest już zainstalowany).
 
![Instalacja krok 1](images/lab_00_5.png)

To już prawie wszystko, aby móc pracować z językiem Python z wykorzystaniem Visual Studio Code. Szczegóły i dodatkowe możliwości narzędzia zostaną zaprezentowane podczas zajęć.
