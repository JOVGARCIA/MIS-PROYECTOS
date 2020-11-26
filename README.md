# MIS-PROYECTOS

import re

def digitos(input_string: str):
    return re.search(r'\d', input_string).group()
