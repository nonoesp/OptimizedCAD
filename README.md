OptimizedCAD
============

My AutoCAD commands ported for both English & Spanish versions.

## References
* [Command Translator](http://www.cadforum.cz/cadforum_en/command.asp?ini=M&lan=ES)

## English acad.pgpg

A, *PLINE
;POL 

AA, *LINE
;LINEA 

F, *MATCHPROP
;*IGUALARPROP

FF, *OFFSET
;DESFASE 

V, *JOIN
;UNIR	

SC, *SPLINE	

D, *MOVE
;DESPLAZA 


ES, *SCALE
;ESCALA	

R, *TRIM
;RECORTA 

TT, *STRETCH
;ESTIRA	

S, *MIRROR
;SIMETRIA 

W, *ALIGN
;ALINEAR 

G, *ROTATE
;GIRA
 
X, *EXPLODE
;DESCOMP	

CC, *BOUNDARY
;CONTORNO	

ED, *PEDIT

C, *COPY
;COPIA 

E, *ERASE
;BORRA 

DD, *DIST 

Q, *CHAMFER
;CHAFLAN 

B, *DRAWORDER
;ORDENAOBJETOS

T, *MTEXT
;TEXTOM 

SS, *HATCH
;SOMBREA 

CA, *LAYON	
CD, *LAYISO	
CS, *LAYOFF 

CW, *LAYMCUR	
CE, *LAYDEL 
CQ, *LAYCUR 
CF, *LAYMRG
Ç, *PROPERTIES
;PROPIEDADES	
TR, *PLOT
;TRAZAR	

OP, *OPTIONS
;OPCIONES 

;2012-10-20
RE, *PREVIEW
;previsualizar

;2012-10-25
SCS, *UCS
;SCP


## Spanish acad.pgp

A,  *POL                       	;Polilínea;Dibuja una polilínea.

AA,  *LINEA                 	 ;Línea

F,  *IGUALARPROP     	 ;Igualar propiedades

FF,  *DESFASE           	;Desfase 

V, *UNIR		;Unir polilínea

SC,   *SPLINE		;Spline

D,     *DESPLAZA 	;Desplazar 

EE,   *EQDIST		;Equidistancia

ES, *ESCALA		;Escalar

R,     *RECORTA 		;Recortar

Q,    *CHAFLAN 		;Chaflán

TT,   *ESTIRA		;Estirar

S,    *SIMETRIA 		;Simetría

W,   *ALINEAR 		;Alinear

G,    *GIRA 		;Gira

X,     *DESCOMP		;Descomponer

CC,   *CONTORNO	;Contorno

ED,   *EDITPOL		;Editar polilínea;Utilizada para convertir líneas en polilíneas.

C,     *COPIA 		;Copiar

E,     *BORRA 		;Borrar

B,    *OB 		;Ordenar Objetos

DD,   *DIST 		;Distancia

T,     *TEXTOM 		;Texto:

SS,  *SOMBREA 	;Sombrear

;Estados de capa

CA,  *LAYON		;Encender Capa

CD,  *LAYISO		;Aislar Capa

CS,  *LAYOFF              ;Apagar Capa

;Selección de capa

CW,  *LAYMCUR	;Establecer Capa Actual;Establece como actual la capa de los objetos seleccionados.

CE,  *LAYDEL 		;Borrar Capa.;Elimina la capa seleccionada.

CQ,  *LAYCUR 		;Capa Actual;Aplica la capa actual a los elementos seleccionados.

Ç,     *PROPIEDADES	;Propiedades

TR,   *TRAZAR		;Trazar;Abre el menú imprimir.

;New proposed commands

OP, *OPCIONES ;Opciones;Abre el panel de configuración.

