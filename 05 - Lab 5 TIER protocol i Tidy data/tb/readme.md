# Środowisko
1. conda 22.9.0
2. Python 3.8
3. pandas 1.2.4
4. Windows 10
5. PyCharm 2022.2.3

# Struktura projektu
1. `analysis_data` - zawiera pliki wygenerowane przez skrypty
   1. `tidy_tb.csv` - plik wynikowy zgodny z Tidy data
   2. `DataAppendix.md` - data appendix
2. `command_files` - pliki wykonywalne
    1. `pick.dataset.py` - wybiera zestaw danych na podstawie liczby liter w nazwisku
    2. `tidy_up_data.ipynb` - przekształca plik `./original_data/tb.csv` w plik `./analysis_data/tidy_tb.csv`, zgodny z
       Tidy data
3. `documents` - zawiera pliki wynikowe
   1. `tidy_tb.csv` - plik wynikowy zgodny z Tidy data
4. `original_data` - oryginalne dane i metadane
   1. `metadata`
      1. `metadata_guide.md` - opis danych i załączników
   2. `tb.csv` - plik z oryginalnymi danymi 

# Odtworzenie wyników
1. Należy uruchomić skrypt `pick_dataset.py` aby sprawdzić, że `tb.csv` jest właściwym plikiem.
2. Należy uruchomić Jupyter Notebook `tidy_up_data.ipynb` w celu wygenerowania pliku `tidy_tb.csv`