# repo-1.2
PRIMO REPOSTILIO
def hanoi(n, origine, destinazione, ausiliario):
    """
    Sposta n dischi dal perno 'origine' al perno 'destinazione'
    utilizzando 'ausiliario' come supporto temporaneo.
    """
    if n == 1:
        print(f"Sposta disco 1 da {origine} a {destinazione}")
        return
    # Sposta n-1 dischi dall'origine all'ausiliario
    hanoi(n - 1, origine, ausiliario, destinazione)
    # Sposta il disco più grande dall'origine alla destinazione
    print(f"Sposta disco {n} da {origine} a {destinazione}")
    # Sposta i n-1 dischi dall'ausiliario alla destinazione
    hanoi(n - 1, ausiliario, destinazione, origine)

# Esempio di utilizzo per 3 dischi
hanoi(3, 'A', 'C', 'B')
HAIL PANE

provato PAITON ma fallice

riprovato ma errora
