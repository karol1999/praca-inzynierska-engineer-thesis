# Metryki oprogramowania w zastosowaniu do określenia samodzielności pracy programistycznej
# Software metrics applied to plagiarism detection of program code
###### ![alt text](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/pl.png "flaga polska") Streszczenie [PL]:	
W ramach pracy stworzono strukturę i wykonano implementacje programu, który na 
podstawie obliczonych metryk oprogramowania analizuje je pod kątem zbieżności przy użyciu 
różnych narzędzi. Aplikacja pozwala na wybór plików do analizy, obliczenie dla nich metryk 
oprogramowania, oraz procesowania ich pod kątem szukania plagiatu przy użyciu wzoru korelacji. 
Również przez zapis danych do plików aplikacja może posłużyć użytkownikowi tylko do liczenia 
metryk, a potem ich użycia wedle uznania. Dodatkowo przedstawiono historię ewolucji zarówno 
metryk i jak i urządzeń, które służyły do posługiwania się nimi w kontekście znajdywania 
podobieństw oraz zarysowano, jak się je oblicza.
Analizując wyniki można powiedzieć, że aplikacja działa, ale nie jest wolna od wad. Dla 
każdej zmienionej wersji, niezależnie czy jest to bardziej lub mniej zaawansowany kod i od 
procesowanych metryk aplikacja wykrywa plagiat. Każdy z poszczególnych wyników analizy, więcej 
lub bardziej różni się od siebie – jest to spowodowane użyciem innych metryk, które są odrębnie 
wydajne dla poszczególnych kodów źródłowych (a do testów używano kody, które diametralnie 
różniły się ilością linii, jak i koncepcją). Warto mieć na uwadze, że również zmiany, które 
wprowadzono w poszczególnych wersjach programów inaczej będą oddziaływać na metryki, a więc
finalnie na wynik. W programie użyto różnych metryk do analizy w celu przeprowadzenia badania 
na szeroką skalę oraz aby potencjalnie przyszłe programy, które będą testowane nie 
skompromitowały narzędzia
###### ![alt text](https://raw.githubusercontent.com/stevenrskelton/flag-icon/master/png/16/country-4x3/gb.png "flaga en") Summary [EN]:	

The purpose of the study was to perform a statistical analysis of real estate sales offers using the web 
scraping technique. To achieve the intended result, server and web applications were created. The web scraping technique was discussed 
with examples of already existing solutions intended for collecting data from websites. The concept of the solution was shown by defining
the requirements, presenting the structure of the database, web and server application, describing the process of the data retrieval function. 
Implementation included the creation of a server application with a mechanism for the automatic extraction of information from online auction 
site and saving them in the database. The web application has been created for configuring the data retrieval functions and seeing the results
of their actions in the form of a result list. The implementation also contained creating charts that were used for presenting statistical 
analysis. The result of the work was presented with verification of graphical interface, which was performed on a mobile device. The summary
contains conclusions and considerations on the possibilities of further project development.

###### słowa kluczowe:
java, ekstrakcja danych, współczynniki korelacji, antyplagiat, statystyka, UML, analiza leksykalna

###### keywords:
java, data extraction, correlation coefficients, anti-plagiarism, statistics, UML, lexical analysis
