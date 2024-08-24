# Verificador de Actas / Venezuela 2024
## Descripción

A raíz de la disputa por los resultados en la elección presidencial de Venezuela, este notebook para Google Colab permite leer masivamente las actas de la elección, usando pyzbar para leer el código QR que cada una contiene identificando su mesa y los resultados de cada candidato. Luego, suma los datos de cada acta y lo muestra en pantalla.

## Características
<b>Escaneo de Códigos QR:</b> Lee los códigos QR de archivos de imagen en un directorio de Google Drive.

<b>Procesamiento de Datos:</b> Extrae y procesa los resultados de la elección a partir de los datos en los códigos QR.

<b>Visualización:</b> Resume y visualiza los votos totales para cada candidato usando Matplotlib.

## Requisitos
<b>Bibliotecas de Python:</b>

- pillow (para el manejo de imágenes)

- pyzbar (para la decodificación de códigos QR)

- matplotlib (para la creación de gráficos)

## Instrucciones
Subir las imágenes de las actas de la elección a una carpeta en Google Drive. ~~Al día de hoy la mejor fuente es https://resultadosconvzla.com/ que dice tener cerca del 81% de las actas, pero requeriría descargar manualmente cada una (si alguien sabe dónde están todas disponibles en un .rar, avisen). La otra opción es esperar a que https://www.cne.gob.ve/ (actualmente offline) los publique.~~ UPDATE: Las mismas pueden descargarse con: https://drive.google.com/drive/folders/1S0Sz-3x0Jn9VL0_HK_-sDDSY_oE6mclH (créditos a @mis2centavos y @xaixi en X/Twitter).

Reemplazar en el código el directorio '/content/drive/My Drive/Actas' con la ruta a la carpeta propia.

## Ejemplo de Salida con 3 actas
<b>Votos Totales por Candidato:</b> El gráfico de barras muestra el número total de votos para cada candidato.

![a](https://github.com/user-attachments/assets/1037a1df-843d-498f-ba33-4213966f3538)

<b>Resultados Impresos:</b> Los votos totales para cada candidato se imprimen en pantalla.

![b](https://github.com/user-attachments/assets/1fd9cfcd-f06c-48d6-b783-ba11781e0353)

# ENGLISH VERSION
# Records Verification / Venezuela 2024
## Description
In light of the dispute over the results in the Venezuelan presidential election, this notebook for Google Colab allows for the mass reading of election records, using pyzbar to read the QR code that each one contains, identifying its table and the results for each candidate. It then sums the data from each record and displays it on the screen.

## Features
<b>QR Code Scanning:</b> Reads QR codes from image files in a Google Drive directory.

<b>Data Processing:</b> Extracts and processes election results from the data in the QR codes.

<b>Visualization:</b> Summarizes and visualizes the total votes for each candidate using Matplotlib.

## Requirements
<b>Python Libraries:</b>

- pillow (for image handling)

- pyzbar (for QR code decoding)

- matplotlib (for graph creation)

## Instructions
Upload the images of the election records to a folder in Google Drive. ~~Currently, the best source is https://resultadosconvzla.com/, which claims to have around 81% of the records but would require manually downloading each one (if anyone knows where they are all available in a .rar, let me know). Another option is to wait for https://www.cne.gob.ve/ (currently offline) to publish them.~~ UPDATE: They can be downloaded from: https://drive.google.com/drive/folders/1S0Sz-3x0Jn9VL0_HK_-sDDSY_oE6mclH (credits to @mis2centavos and @xaixi on X/Twitter).

Replace the directory '/content/drive/My Drive/Actas' in the code with the path to your own folder.

## Example Output with 3 Records

<b>Total Votes per Candidate:</b> The bar chart shows the total number of votes for each candidate.

![a](https://github.com/user-attachments/assets/1037a1df-843d-498f-ba33-4213966f3538)

<b>Printed Results:</b> The total votes for each candidate are printed on the screen.

![b](https://github.com/user-attachments/assets/1fd9cfcd-f06c-48d6-b783-ba11781e0353)

