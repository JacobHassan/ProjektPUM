Projekt Uczenie maszynowe:  NY-House-Dataset
Kacper Obrębski
Szymon Jabłoński
Celem jest predykcja ceny nieruchomości.

Zbiór danych zawiera 4802 instancje i kolumny określające:
BROKERTITLE: Title of the broker
TYPE: Type of the house
PRICE: Price of the house
BEDS: Number of bedrooms
BATH: Number of bathrooms
PROPERTYSQFT: Square footage of the property
ADDRESS: Full address of the house
STATE: State of the house
MAIN_ADDRESS: Main address information
ADMINISTRATIVE_AREA_LEVEL_2: Administrative area level 2 information
LOCALITY: Locality information
SUBLOCALITY: Sublocality information
STREET_NAME: Street name
LONG_NAME: Long name
FORMATTED_ADDRESS: Formatted address
LATITUDE: Latitude coordinate of the house
LONGITUDE: Longitude coordinate of the house

Skrypt importuje niezbędne biblioteki, wczytuje dane z pliku CSV do DataFrame, zmienia nazwy kolumn, definiuje typy kolumn i konwertuje je na odpowiednie typy. Następnie sprawdza kształt DataFrame, sprawdza obecność brakujących wartości, usuwa duplikaty i sprawdza, czy istnieją wartości mniejsze od zera w określonych kolumnach. Skrypt również usuwa znak '#' z kolumny 'FORMATTED_ADDRESS' i na końcu koduje pewne kolumny za pomocą LabelEncoder.
