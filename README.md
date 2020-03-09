# ProyectoFinal
Predicción de calificados al mundial.

El propósito de este proyecto es predecir a los equipos americanos que van a calificar al mundial 2022.

La información se obtuvo de archivos descargados de la página kaggle.com, de estos archivos, uno contiene datos del Ranking FIFA, otro un histórico de partidos internacionales desde finales del siglo XIX a la fecha y uno más información de jugadores de los clubes de distintas ligas de un juego de video.

De estos archivos se filtraron datos de selecciones del continente americano, seis de CONCACAF y las diez de CONMEBOL, formándose los siguientes archivos: HISTORICO_CONCACAF.csv, HISTORICO_CONMEBOL.csv, SELECCIONES_CONCACAF.csv y SELECCIONES_CONMEBOL.csv. Los archivos ELIMINATORIA_CONMEBOL y HEXAGONAL_CONCACAF se elaboraron sin auxilarse de otros archivos.

El proyecto posee dos archivos de Jupyter Notebook, uno para el HEXAGONAL de CONCACAF y otro para la eliminatoria de CONMEBOL. Para ejecutarlos será necesario generar una carpeta denominada "datos_fifa" en la carpeta donde van a estar almacenados los archivos de Jupyter, y en esa carpeta nueva guardar los archivos csv.
