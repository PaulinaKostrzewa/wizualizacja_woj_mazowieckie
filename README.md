Całość zaimplementowana w bibliotece Bokeh.

# Wizualizacja dla gmin w województwie mazowieckim:

- wizualizacja_woj_mazowieckie.ipynb zawiera wizualizację przedstawiającą podział woj. mazowieckiego na gminy i wybrane wielkości w danej gminie - nasycenie koloru oznacza stopień natężenia wielkości w danej gminie

kod inspirowany na podstawie artykułu: https://towardsdatascience.com/a-complete-guide-to-an-interactive-geographical-map-using-python-f4c5197e23e0


# Wizualizacje na szczeblu powiatowym dla Polski:

- wizualizacja_woj_mazowieckie_v3a.ipynb zawiera przerobioną wersję na szczebel powiatowy z wizualizacji poprzedniej
- aplikacja.ipynb zawiera wizualizację na szczeblu powiatowym:
    * te samą co powyżej + dodana wizualizacja wykres liniowy na przestrzeni lat jak zmieniają się wybrane wielkości dla KONKRETNEGO powiatu


aby uruchomić programy wywołać komendę np.
` bokeh serve --show wizualizacja_woj_mazowieckie.ipynb` 
w lokalizacji do której sklonowaliśmy repozytorium
