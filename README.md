# ExtractImagesPDF
 Extract Images From PDF files

Criei esse executável, para poder extrair imagens de arquivos em PDF.

Foram utilizadas as bibliotecas:
<br>-TKINTER (para selecionar o arquivo em PDF no computador)
<br>-MESSAGE BOX (TKINTER) - Para informar ao usuário que as imagens foram salvas na pasta em que o arquivo PDF se encontra
<br>-PDF(PIKEPDF) para ler o arquivo em PDF
<br>-PDFIMAGE(PIKEPDF) para extrair as imagens do arquivo PDF
<br>-PATHLIB (para criar uma pasta, no local onde o arquivo em PDF se encontra, e posteriormente salvar as imagens sequenciadas nesta pasta criada)

...todo esse projeto foi realizado no JUPYTER NOTEBOOK (pela facilidade em executar os códigos por partes).
<br>Foi necessário salvar o arquivo na extensão .py, para que a biblioteca usada posterior (PYINSTALLER) pudesse ler esse arquivo
<br>Criei um AMBIENTE VIRTUAL, para poder instalar as bibliotecas necessárias(citadas acima), para que o arquivo final não ficasse pesado (devido bibliotecas desnecessárias, instaladas no meu computador)
<br>Para a criação do arquivo executável, foi utilizada a biblioteca PYINSTALLER.
