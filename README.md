# proyecto1-analisis_excel-yasira_b
Análisis de datos y dashboard interactivo en Excel. 1er proyecto del Bootcamp Data Analyst P2. 

Creación de dashboard interactivo en Excel a partir de una base de datos de un .csv
Los datos son de la organización Kiva loans y están libres para descargar desde el siguiente enlace:
https://www.kaggle.com/datasets/kiva/data-science-for-good-kiva-crowdfunding

Desarrollo del dashboard:
    1. Se genera el libro de excel y se enlaza al dataset (.csv) sin importar datos, para no hacer el libro pesado y que GitHub no ponga pegas para subirlo. 
    2. Se realiza limpieza de datos con Power Query, eliminación de duplicados, errores y filas inservibles.
    3. Se genera hoja dónde irán las tablas dinámicas de las que beberá la hoja del dashboar.
    4. El propósito es general por lo que nos centramos en mostrar/trabajar 4 puntos:
        1. Big numbers: recuentos, máximos, porcentajes para hacernos una idea global. 
            Lo situamos en la esquina superior derecha para captar la atención y el interés del público general.
        2. Simulador de préstamos: creamos con tablas dinámicas, segmentadores y una barra de desplazamiento con VBA un simulador para que el público pueda ver las opciones reales que tienen. Sittuamos este justo debajo de los bignumbers en la esquina inferior izquierda
        3. Mapa de calor: Realizamos un mapa de calor con el número de préstamos concedidos, que nos señala las zonas del globo dónde más préstamos se han dado. Este lo situamos en el centro, porque por estética nos encajaba mejor a pesar de pretender un diseño en Z o F. Hemos decidido sacrificar esa parte. 
        4. Gráfico circular de actividades por sectores: Se realizan dos gráficos, uno de anillo y otro circular, contenido en el primero. El central es estático y muestra los sectores, mientras que el anillo es dinámico y muestra las actividades del sector que hemos escogido más abajo. 
    
    Para que el diseño fuera armonioso y en la línea de la web de Kiva, se han escogido los colores principales con un colorpicker y se han aplicado al dashboard. También se ha buscado un logo en formato png para incluirlo. 

    5. Una vez finalizado el dashboard, se ocultan las hojas auxiliares y se procede a limpiar la vista eliminando lineas de cuadrículas, cintas de opciones, etc. dejando el dashboard únicamente visible para que la experiencia sea de aplicación y no muestre que excel está corriendo por debajo. 

    *Fue necesario cambiar el formato del libro a .xlsm para poder integrar la barra de desplazamiento con código VBA. 

    ![Dashboard image](image.png)