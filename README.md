# OptimizedCAD

My AutoCAD commands ported for both English & Spanish versions.

This library is part of the [Getting Architecture Done](http://www.gettingarchitecturedone.com/?utm_source=github&utm_medium=GADKit) project. Follow [@GettingArchDone](http://twitter.com/GettingArchDone) on Twitter or [Facebook](http://facebook.com/gettingarchitecturedone) to keep updated. Join at [gettingarchitecturedone.com](gettingarchitecturedone.com).

## Usage

Copy and paste the following commands into your *acad.pgp* file. Commands for both English and Spanish AutoCAD versions are provided.

## References
* [Command Translator](http://www.cadforum.cz/cadforum_en/command.asp?ini=M&lan=ES)

## English acad.pgp

;Create Polyline

A, *PLINE

;Create Line

AA, *LINE

;Create Spline

SC, *SPLINE	

;Match Properties

F, *MATCHPROP

;Offset

FF, *OFFSET

;Join

V, *JOIN

;Move

D, *MOVE

;Scale

ES, *SCALE

;Trim

R, *TRIM 

;Stretch

TT, *STRETCH

;Symmetry / Mirror

S, *MIRROR

;Align

W, *ALIGN

;Rotate

G, *ROTATE
 
;Explode
X, *EXPLODE

;Boundary

CC, *BOUNDARY

;Polyline Edit

ED, *PEDIT

;Copy

C, *COPY

;Erase

E, *ERASE

;Measure Distance

DD, *DIST 

;Chamfer

Q, *CHAMFER

;Arrange Objects' Order

B, *DRAWORDER

;Create Text Object

T, *MTEXT

;Hatch (Sombrear)

SS, *HATCH

CA, *LAYON	

CD, *LAYISO	

CS, *LAYOFF 


CW, *LAYMCUR	

CE, *LAYDEL 

CQ, *LAYCUR 

CF, *LAYMRG

;Properties

Ç, *PROPERTIES

;Plot

TR, *PLOT

;Options

OP, *OPTIONS

;2012-10-20

;Preview

RE, *PREVIEW

;2012-10-25

;Set New Coordinate System

SCS, *UCS


## Spanish acad.pgp

;Polilínea

A, *POL

;Línea

AA, *LINEA

;Igualar propiedades

F, *IGUALARPROP

;Desfase

FF, *DESFASE

;Unir polilínea

V, *UNIR

;Spline

SC, *SPLINE

;Desplazar 

D, *DESPLAZA

;Equidistancia (Offset)

EE, *EQDIST

;Escalar
ES, *ESCALA

;Recortar

R, *RECORTA

;Chaflán

Q, *CHAFLAN

;Estirar

TT, *ESTIRA

;Simetría

S, *SIMETRIA

;Alinear

W, *ALINEAR

;Girar

G, *GIRA

;Descomponer

X, *DESCOMP

;Contorno

CC, *CONTORNO

;Editar polilínea

;Utilizada para convertir líneas en polilíneas.

ED, *EDITPOL

;Copiar

C, *COPIA

;Borrar

E, *BORRA

;Ordenar Objetos

B, *OB

;Medir Distancia

DD, *DIST

;Crear Texto:

T, *TEXTOM

;Sombrear

SS, *SOMBREA

;MARK: Estados de capa

;Encender Capa

CA, *LAYON

;Aislar Capa

CD, *LAYISO

;Apagar Capa

CS, *LAYOFF

;MARK: Selección de capa

;Establecer Capa Actual

;Establece como actual la capa de los objetos seleccionados.

CW, *LAYMCUR

;Borrar Capa.

;Elimina la capa seleccionada.

CE, *LAYDEL

;Capa Actual

;Aplica la capa actual a los elementos seleccionados.

CQ, *LAYCUR

;Propiedades

Ç, *PROPIEDADES

;Trazar (CTRL + P)

;Abre el menú imprimir.

TR, *TRAZAR

;Opciones

;Abre el panel de configuración.

OP, *OPCIONES


## License

OptimizedCAD is licensed under the MIT license. (http://opensource.org/licenses/MIT)

## Me

I tweet at [@nonoesp](http://www.twitter.com/nonoesp) and blog at [nono.ma/says](http://nono.ma/says). I would love to hear about it if you use this library. Thanks!
