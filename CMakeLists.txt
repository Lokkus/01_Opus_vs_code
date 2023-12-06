cmake_minimum_required(VERSION 3.10)

project(01_Opus)

# Ustaw wersję języka C++
set(CMAKE_CXX_STANDARD 14)

# Dodaj pliki nagłówkowe

include_directories(${CMAKE_SOURCE_DIR}/inc)

# Dodaj pliki źródłowe
set(SOURCE_FILES
    src/03_Typy.cpp
    src/04_Operatory.cpp
    src/06_Funkcje.cpp
    src/10_vector.cpp
    src/11_Wskazniki.cpp
    src/16_Klasy.cpp
    src/17_String.cpp
    src/19_Wyjatki.cpp
    src/20_Klasa_skladnik_klasa_lokalna.cpp
    src/21_Konstruktory_destruktory.cpp
    src/22_Konstruktor_kopiujacy_i_przenoszacy.cpp
    src/24_Wskazniki_do_elementow_klasy.cpp
    src/25_konwersje_definiowane_przez_uzytkownika.cpp
    src/26_Przeladowanie_operatorow.cpp
    src/27_Unie_pola_bitowe.cpp
    src/30_Lambda.cpp
    src/31_Dziedziczenie_klas.cpp
    src/32_Polimorfizm.cpp
    src/33_Strumien_wej_wyj.cpp
    src/main.cpp
)


# Dodaj plik wykonywalny
add_executable(${PROJECT_NAME} ${SOURCE_FILES} ${HEADER_FILES})
