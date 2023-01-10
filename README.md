# Klasifikátor obrázků s použitím ConvNet

### cile
* zprovoznit jupyter
* vytvořit dataset
* načíst data
* rozdělit data
* vytrenovat sít

### Spuštění
1. stáhnout python
2. stáhnout jupyter
   ```
   pip install notebook
   ```
3. vytvořit venv pro projekt
    * v příkazovém řádku si otevřeme složku s projektem a napíšeme:
    ```
    python -m venv nazev
    ```
    * aktivujeme virtuální prostředí (pro windows):
    ```
    .\***nazev***\scripts\activate
    ```
4. instalovat ipykernel
    * Umožní připojit venv k jupyter notebooku
    ```
    pip install ipykernel
    python -m ipykernel install --name=nazev
    ```
    * Pro kontrolu si vypíšeme list všech dostupných venv/kernelů
    ```
    jupyter kernelspec list
    ```
5. spustit jupyter
   ```
   jupyter notebook
   ```
   * V UI otevřeme správný projekt
6. nastavíme správné venv pro projekt
   * v liště nahoře klikne na ***kernel > change kernel > nazev***


### zdroje 
* https://cs231n.github.io/convolutional-networks/
* https://towardsdatascience.com/a-comprehensive-guide-to-convolutional-neural-networks-the-eli5-way-3bd2b1164a53
* https://www.youtube.com/watch?v=jztwpsIzEGc
* https://www.youtube.com/watch?v=FmpDIaiMIeA
* https://www.youtube.com/watch?v=19LQRx78QVU&t=2344s
