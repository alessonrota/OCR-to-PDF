# OCR-to-PDF
Código composto com Tesseract e PyPDF para reconhecimento de imagens e conversão em documentos .pdf


1 - Crie um diretório de trabalho para o projeto:

    Crie um novo diretório em seu sistema operacional para o projeto de conversão de imagens JPG em PDF.
    Por exemplo, crie um diretório chamado "conversor-pdf" no desktop.

2 - Adicione as imagens JPG ao diretório:

    Copie as imagens JPG que deseja converter para PDF para o diretório de trabalho que você criou no passo anterior.

3 - Abra o terminal:

    Abra o terminal (no Windows, use o PowerShell) e navegue até o diretório de trabalho que você criou no passo anterior.

4 - Inicie o ambiente virtual:

    Execute o seguinte comando para iniciar o ambiente virtual:
  `python -m venv venv`

    Isso criará um novo diretório chamado "venv" no diretório de trabalho que você criou. O ambiente virtual é uma forma de isolar as dependências do projeto em um ambiente separado para evitar conflitos com outras bibliotecas do Python.

5 - Ative o ambiente virtual:

    Execute o seguinte comando para ativar o ambiente virtual:
    `source venv/bin/activate`
    Isso ativará o ambiente virtual e o prompt do terminal deve mudar para indicar que o ambiente virtual está ativo.

6 - Instale as dependências necessárias:

    Execute o seguinte comando para instalar as dependências necessárias para o projeto:
    `pip install PyPDF2 numpy pytesseract`
