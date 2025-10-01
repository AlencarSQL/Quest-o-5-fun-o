# Quest-o-5-fun-o
def media(notas):
    """
    Calcula a média das notas.
    
    Args:
        notas (list): Lista com as notas
    
    Returns:
        float: Média das notas
    """
    if len(notas) == 0:
        return 0
    return sum(notas) / len(notas)


def maior(notas):
    """
    Retorna a maior nota da lista.
    
    Args:
        notas (list): Lista com as notas
    
    Returns:
        float: Maior nota
    """
    return max(notas)


def menor(notas):
    """
    Retorna a menor nota da lista.
    
    Args:
        notas (list): Lista com as notas
    
    Returns:
        float: Menor nota
    """
    return min(notas)
