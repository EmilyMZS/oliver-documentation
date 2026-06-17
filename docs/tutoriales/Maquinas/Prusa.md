# **Impresora 3D Prusa MK4S**

<p align="center">
  <img src="../imgspr/Prusa.webp" width="400" /><br>
  
</p>

## **Introducción**

La **Prusa MK4S** es una de las impresoras 3D más recomendadas para principiantes y entornos educativos.  
Combina **facilidad de uso, confiable y da excelentes resultados** gracias a su sistema de **autonivelación automática**, su **asistente de calibración inteligente** y el software **PrusaSlicer**.

Desde el primer encendido, guía al usuario paso a paso evitando errores comunes. Su funcionamiento es **silencioso**, su mantenimiento **sencillo**, y su comunidad **muy activa**, lo que facilita resolver dudas y aprender rápidamente.

## **Materiales compatibles**

| Material | Descripción | Temp. boquilla / cama | Dificultad | Recomendado para |
|:---------|:-------------|:---------------------:|:-----------:|:-----------------|
| **PLA** | Ideal para principiantes, biodegradable y fácil de imprimir | 200 °C / 60 °C | Fácil | Figuras, prototipos, piezas decorativas |
| **PETG** | Resistente, flexible y duradero | 240 °C / 85 °C | Media | Piezas funcionales y exteriores |
| **ABS** | Resiste altas temperaturas, puede deformarse sin cámara cerrada | 250 °C / 100 °C | Difícil | Piezas estructurales y mecánicas |
| **ASA** | Similar al ABS, pero más estable frente a rayos UV | 255 °C / 100 °C | Difícil | Piezas exteriores |
| **TPU** | Material elástico y flexible | 230 °C / 60 °C |  Media | Protectores, juntas, fundas |
| **Nylon** | Muy resistente y duradero | 260 °C / 90 °C |  Difícil | Engranajes, bisagras, componentes técnicos |
| **PC(policarbonato)** | Alta resistencia al impacto y al desgaste (menor que al PETG) | 270°/ 110° | Media | Componentes técnicos |
| **PVB** | Filamento transparente y resistencia a la tracción | 215°/75° | Difícil | Pantallas de lámpraras y joyería | 

>  **Consejo:** si estás comenzando, imprime con **PLA**. Es económico, seguro y no requiere una cabina cerrada.

## **Componentes principales de la Prusa MK4S**

<p align="center">
  <img src="../imgspr/Componentes.jpg" width="550" /><br>
  
</p>

Componentes enumerados:

1. Carrete de filamento
2. Marco
3. Eje Z
4. Nextruder - Sensor de carga que mejora la precisión
5. Motor paso a paso del eje x
6. Caja electrónica - Se accede a lo puertos Ethernet y Wi-fi desde atrás
7. Motor paso a paso del eje Z
8. LCD
9. Portacarrete
10. Eje X  
11. Fuente de alimentación
12. Lámina de impresión
13. Cama caliente
14. Puerto USB
15. Perilla giratoria

## **Software de laminado: PrusaSlicer**

El programa **PrusaSlicer** convierte los modelos 3D en instrucciones que la impresora entiende, llamadas **G-code**.


## **Interfaz de Prusa Slicer**

<p align="center">
<img src="../imgspr/Interfaz.jpg" width="550" /><br>
</p>

1. Abre las opciones de "Print", "Filament" y "Printer sttings"
2. "Add" sirve para importar modelos en 3D
3. El botón de "Delete" sirve para borrar los modelos que esten en la interfaz
4. Sirve para cambiar entre modos "Simple", "Avanzado" y "Experto"
5. Configuraciones para velocidad y calidad
6. Seleccionar el material
7. Seleccionar la impresora
8. Configurar "Infill", "Supports" y "Brim"
9. Información sobre el tamaño del modelo y el tiempo de duración de la impresión (Después de sleccionar "Slice")
10. Slice
11. Clic derecho sobre el modelo para abrir nu menú sobre información
12. Modelar la prevista en 3D 
13. Cambiar entre el editor 3D y el modo de prevista
14. "Move", "Scale", "Rotate", "Cut", "Paint-on-supports" y "Seam Painting Tools" 
 

### **Pasos básicos**
1. Abre **PrusaSlicer**.  
2. Selecciona **Original Prusa MK4S** como impresora.  
3. Carga tu modelo 3D (`Archivo > Importar > Modelo STL`).  
4. Ajusta su posición y orientación con **Move**, **Rotate**, y **Scale**.  
5. Configura los parámetros principales:
   - Material: PLA recomendado para iniciar
   - Altura de capa: 0.20 mm (estándar)  
   - Relleno: 20 %  
   - Soportes: Solo si hay partes que "vuelan" o huecos grandes  
   - Infill: Tipo de relleno geometrico que sea de nuestro agrado
   - Brim: Para incrementar la adherencia del modelo sobre la primera capa
6. Selecciona **Slice Now** para generar el archivo.  
7. Guarda el `.gcode` en una memoria USB.  

> **Dato técnico:** el archivo G-code contiene coordenadas (X, Y, Z), temperatura y flujo de extrusión para cada capa.

<p align="center">
 <img src="../imgspr/Arc_subido_pr.png" width="550" /><br>
</p>

### **Seleccionar el color para la impresión**

1. Seleccionar la prevista
2. Utilizar el controlo deslizante para seleccionar en que capa de la impresión quieres modificar el color
3. Dar clic en el icono de "+" naranja
4. Aparecerá una vista previa de cómo se verá el color, si lo quieres deshacer da clic en el botón gris que aparecerá en vez del naranja
5. Exportar el .gcode para imprimir 

<p align="center">
<img src="../imgspr/Color.jpg" width="550" /><br>
</p>

## **Pantalla táctil**

<p align="center">
<img src="../imgspr/Pantalla.jpg" width="550" /><br>
</p>

1.- Print

    Cuando se selcciona está opción lo que muestra son todos los archivos que están guardados en la USB que esta conectada, si no hay USB  note dejara seleccionar la opción



2.- Preheat

   Aquí se abre un menú en donde podemos seleccionar el tipo de material que vamos a usar y la impresora automaticamente se calentara de acuerdo al material seleccionado
<p align="center">
<img src="../imgspr/Preheat.jpg" width="550" /><br>
</p>

3.- Filament 

   Aquí se muestran las opciones que nos da el botón de "Filament", las cuales se autoexplican
<p align="center">
<img src="../imgspr/Filament.jpg" width="550"/><br>
</p>

4- Control

   Aquí se muestran varias elecciones para manipular varios factores de la impresora como el movimiento de los ejes

<p align="center">
<img src="../imgspr/Control.jpg" width="550"/><br>
</p>

5.- Settings

 Permite controlar y personalizar el comportamiento de la máquina a un nivel más profundo

<p align="center">
<img src="../imgspr/Settings.jpg" width="550"/><br>
Aquí se muestran algunas de las opciones
</p>

6.- Info

Aquí se nos proporciona toda la información de los detalles sobre la impresora

<p align="center">
<img src="../imgspr/Info.jpg" width="550"/><br>
</p>

## **Preparación y calibración inicial**

1. Enciende la impresora y espera que cargue el menú principal.  
2. Dirígete a **Settings > Calibration > Selftest**.  
3. El sistema verificará:  
   - Movimiento de los ejes (X, Y, Z)  
   - Sensor de filamento  
   - Calibración del extrusor y de la cama calefactora  
4. Si todo está correcto, mostrará **Selftest Passed**.

> **No es necesario nivelar manualmente la cama.**  
> La MK4S usa sensores de carga y un sistema de calibración automática (Load Cell) que mide la presión real de contacto.



##  **Cargar o cambiar el filamento**

1. Menú > **Filament > Load Filament**.  
2. El extrusor calentará la boquilla automáticamente.  
3. Corta la punta del filamento de modo que qude un poco afilado
3. Inserta el filamento y deja que el motor lo guíe.  
4. Espera a que salga un flujo uniforme.  
5. Para cambiar material: **Unload Filament** → luego carga el nuevo.  
6. Corta el exceso de material antes de iniciar la impresión.

> **Precaución:** nunca toques la boquilla caliente (puede superar los 250 °C).



##  **Iniciar una impresión**

1. Inserta la memoria USB con el archivo `.gcode` 
2. Menú > Print > selecciona el modelo  
3. La impresora precalienta la cama y la boquilla automáticamente
4. Observa la primera capa: debe verse uniforme y bien adherida  
5. Si el filamento no se adhiere, ajusta con **Live Z Adjust**  

> La MK4S tiene la función de *Input Shaper*, un sistema que reduce vibraciones y mejora la calidad de impresión a altas velocidades.

##  **Retirar la pieza impresa**

1. Espera a que la temperatura de la cama baje a menos de 35 °C.  
2. Retira la **hoja magnética** y flexiónala suavemente.  
3. Usa una espátula con cuidado si la pieza está muy adherida.  
4. Limpia la cama con alcohol isopropílico antes de la siguiente impresión.  

## **Mantenimiento básico**

- Limpia la boquilla con aguja o cepillo de latón.  
- Lubrica varillas y husillos cada 3 meses.  
- Mantén los ventiladores libres de polvo.  
- Guarda el filamento en bolsas con desecante.  
- Actualiza el firmware desde [help.prusa3d.com](https://help.prusa3d.com/).  

## **Resolución de problemas comunes**

| Problema | Posible causa | Solución |
|-----------|----------------|-----------|
| Primera capa no se adhiere | Cama sucia o mal calibrada | Limpia la cama y ajusta el eje Z |
| No sale filamento | Boquilla obstruida | Calienta y limpia o reemplaza la boquilla |
| Filamento quebradizo | Humedad o mala calidad | Usa filamento seco y revisa el tubo guía |
| Capas desplazadas | Correas flojas o atascos | Ajusta correas y verifica los ejes |
| Impresión detenida | Fallo de energía o USB defectuosa | Usa otro dispositivo o la función *Resume Print* |

##  **Recomendaciones finales**

- Inicia con modelos simples como el **3DBenchy** o un **cubo de calibración**.  
- No apagues la impresora hasta que se enfríe por completo.  
- Mantén el área de trabajo limpia y bien ventilada.  
- Aprende nuevos perfiles de impresión en [Printables.com](https://www.printables.com/).  

###  **Conclusión**

La **Prusa MK4S** permite a cualquier persona iniciarse en la impresión 3D sin complicaciones.  
Su diseño inteligente, sensores avanzados y software intuitivo hacen que el aprendizaje sea fluido y confiable.  
Con práctica y curiosidad, podrás dominar las técnicas de impresión, calibración y diseño 3D desde los primeros proyectos.
