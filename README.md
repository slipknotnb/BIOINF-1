# BIOINF-1
Nicolas Bonta Barros

# Trabajo Bioinformática 
#### Parte 1: Enfermedades genéticas y genes
 La enfermedad celíaca : es una enfermedad autoinmune caracterizada por la inflamación de las paredes intestinales debido a la presencia de gluten el cual el sistema inmune ataca, está asociada a los genes HLA-DQ1B y __HLA-DQA1__ principales genes del complejo HLA  Sistema del antígeno leucocitario humano
 
  ##### Preguntas
 1. ##### ¿Tiene nombres alternativos el gen? Sí, son 4 incluyendo el nombre original: __HLA-DQA1__, CELIAC1, DQ-A1, HLA-DQA
 2. ##### ¿En qué cromosoma está? ¿Cuántos exones tiene? ¿Cuántas isoformas de transcritos? Se encuentra en el cromosoma 6 en la posición 6p21.32, posee 6 exones y 7 isoformas de transcritos
 3. ##### ¿Qué tipo de proteína es codificada por este gen? ¿Cuál es su número EC? La proteína se llama antígeno de histocompatibilidad clase II, cadena DQ alfa 1, no posee número EC ya que no es una enzima 
 4. ##### ¿Qué genes están inmediatamente río arriba/abajo? El gen que se encuentra río arriba con respecto a HLA-DQA1 es HLA-DQB1 y rio abajo el HLA-DRB1
 5. ##### ¿Cuál es la longitud de tu gen? 1591  pares de bases es la longitud del gen HLA-DQA1.
 6. ##### ¿Cuántas variantes de tu gen hay descritas y en qué posiciones? Son 7 las variantes descritas de este gen, todas se encuentran en el cromosoma 6
 7. ##### ¿Las sustituciones corresponden a cambios sinónimos o no sinónimos? Son 2 los cambios sinónimos, 3 no sinónimos Y existen 2 que no se conoce su significancia.
 8. ##### ¿Existen ortólogos de tu gen en otras especies? ¿Cuántos? si, existen 10 ortólogos de otras especies.
 9. ##### ¿Y parálogos? ¿Hay pseudogenes? ¿Cuántos? Sí, existen 25 parálogos en distintas zonas del cromosoma, de esos 25 hay 6 pertenecen al complejo HLA.

#### Parte 2: Rutas y procesos metabólicos 


 1. ##### Anteriormente encontraste nombres alternativos de tu gen ¿Existen otros reportados por Kegg? ¿Cuáles? Son los mismos en ambas páginas web, HLA-DQA1, CELIAC1, DQ-A1, HLA-DQA
 2. #####  ¿En qué rutas metabólicas participa la proteína codificada por tu gen? Participa en el linaje de células hematopoyéticas y rechazo de aloinjerto.
 3. ##### ¿Cuál es el número de identificación de tu gen (entry number)? 4942 
 4. ##### ¿En qué otras bases de datos está tu gen presente y cuáles son sus números de acceso? En ncbi es 4942, Ensembl:ENSG00000196735, MIM:146880, Vega:OTTHUMG00000031106

![hsa05330.png](http://www.kegg.jp/tmp/mark_pathway152165093168084/hsa05330.png)
Imagen de la ruta metabólica asociada a rechazo de aloinjerto, en rojo se muestran en los lugares donde participa el gen.

5. ##### ¿En qué otras rutas metabólicas está involucrado tu gen? Linaje de células hematopoyéticas, rechazo de aloinjerto, enfermedad autoinmune tiroidea, Procesamiento y presentación de antígenos, fagosoma, adhesión celular, red inmune intestinal para producción de IgA y asma.
 6. ##### ¿Qué significan los cuadros verdes en el diagrama? En la imagen los cuadros verdes que muestran MHC son factores de histocompatibilidad, los CD son cúmulos de diferenciación generalmente son marcadores que son reconocidos por las células, las IL son interleucinas funcionan como mensajeros químicos.	
 7. ##### ¿Con qué rutas se cruza la ruta metabólica? Se cruza con la diabetes tipo 1, enfermedad de injerto contra el huésped, enfermedad tiroidea autoinmune y asma.
 8. ##### ¿Cuántos "dominios" forman la anotación GO? participa en 2 de los 3 principales dominios
 9. ##### ¿A qué corresponde este término y qué información te entrega la página? el termino buscado corresponde a la glicolisis, la página muestra información y la relación que existe desde un gen hasta una proteína y como esta se relaciona con los distintos procesos metabólicos y celulares, la funcionalidad principal de la página es que se puede buscar información detallada del origen de lo buscado y en que procesos participan indicando si participan de forma positiva o negativa en un proceso, como una especie de red que engloba todo.
 10. ##### Anota 10 sub-categorías GO a la cual GO:0006096 pertenece proceso glicolitico a través de la fructosa 6 fosfato, regulación negativa del proceso glicolitico, regulación del proceso glicolitico por la transcripción del promotor de la RNA Pol II, regulación positiva del proceso glicolitico, regulación del proceso glicolitico atreves de la ruta de Entner-Doudoroff, proceso glicolitico a través de  fructosa-1-fosfato, proceso glicolitico a través del glicerol, actividad piruvato quinasa, proceso glicolitico de la sucrosa, regulación del proceso glicolitico de forma negativa en la transcripción del promotor de la ARN polimerasa II, regulación del proceso glicolitico de forma positiva en la transcripción del promotor de la ARN polimerasa II.

#### Parte 3: Descargando secuencias, convirtiendo formatos.
 
 1. ##### ¿Cuántos ítems fueron encontrados? ¿Cuántos en animales? Fueron encontrados 70748 artículos relacionados con el GAPDH.
 2. ##### ¿Cuál es la longitud del gen? el gen del GAPDH basado en el paper tiene 1288bp 
 3. ##### ¿Cuál es la referencia bibliográfica más reciente? AUTHORS   Ren X, Zhang L, Gao Y, Gao H, Wang Y, Liu C, Cui H, Zhang Y, Jiang L, Qi X and Wang X.TITLE     Binding chicken Anx2 is beneficial for infection with infectiousbursal disease virusJOURNAL   Virus Res. 210, 232-240 (2015)
 4. ##### ¿Cuál es el número de acceso? NM_204305
 5. ##### Secuencia

 >NM_204305.1 Gallus gallus glyceraldehyde-3-phosphate dehydrogenase (GAPDH), mRNA
ACCTTCTCACTGCGCGCTGGGGCCGTTGACGTGCAGCAGGAACACTATAAAGGCGAGATGGTGAAAGTCG
GAGTCAACGGATTTGGCCGTATTGGCCGCCTGGTCACCAGGGCTGCCGTCCTCTCTGGCAAAGTCCAAGT
GGTGGCCATCAATGATCCCTTCATCGATCTGAACTACATGGTTTACATGTTCAAATATGATTCTACACAC
GGACACTTCAAGGGCACTGTCAAGGCTGAGAACGGGAAACTTGTGATCAATGGGCACGCCATCACTATCT
TCCAGGAGCGTGACCCCAGCAACATCAAATGGGCAGATGCAGGTGCTGAGTATGTTGTGGAGTCCACTGG
TGTCTTCACCACCATGGAGAAGGCTGGGGCTCATCTGAAGGGTGGTGCTAAGCGTGTTATCATCTCAGCT
CCCTCAGCTGATGCCCCCATGTTTGTGATGGGTGTCAACCATGAGAAATATGACAAGTCCCTGAAAATTG
TCAGCAATGCATCGTGCACCACCAACTGCCTGGCACCCTTGGCCAAGGTCATCCATGACAACTTTGGCAT
TGTGGAGGGTCTTATGACCACTGTCCATGCCATCACAGCCACACAGAAGACGGTGGATGGCCCCTCTGGG
AAGCTGTGGAGAGATGGCAGAGGTGCTGCCCAGAACATCATCCCAGCGTCCACTGGGGCTGCTAAGGCTG
TGGGGAAAGTCATCCCTGAGCTGAATGGGAAGCTTACTGGAATGGCTTTCCGTGTGCCAACCCCCAATGT
CTCTGTTGTTGACCTGACCTGCCGTCTGGAGAAACCAGCCAAGTATGATGATATCAAGAGGGTAGTGAAG
GCTGCTGCTGATGGGCCCCTGAAGGGCATCCTAGGATACACAGAGGACCAGGTTGTCTCCTGTGACTTCA
ATGGTGACAGCCATTCCTCCACCTTTGATGCGGGTGCTGGCATTGCACTGAATGACCATTTCGTCAAGCT
TGTTTCCTGGTATGACAATGAGTTTGGATACAGCAACCGTGTTGTGGACTTGATGGTCCACATGGCATCC
AAGGAGTGAGCCAGGCACACAGCCCCCCTGCTGCCTAGGGAAGCAGGACCCTTTGTTGGAGCCCCTGCTC
TTCACCACCGCTCAGTTCTGCATCCTGCAGTGAGAGGCCAGTTCTGTTCCCTTCTGTCTCCCCCACTCCT
CCAATTTCTTCCTCCACCTGGGGGAGGTGGGAGAGGCTGATAGAAACTGATCTGTTTGTGTACCACCTTA
CATCAATAAAAGTGTTCACCATCTGAAG

6. ##### Formato convertido a nexus
#NEXUS
[TITLE: Written by EMBOSS 21/03/18]

begin data;
dimensions ntax=1 nchar=1288;
format interleave datatype=DNA missing=N gap=-;

matrix
NM_204305.1          ACCTTCTCACTGCGCGCTGGGGCCGTTGACGTGCAGCAGGAACACTATAA

NM_204305.1          AGGCGAGATGGTGAAAGTCGGAGTCAACGGATTTGGCCGTATTGGCCGCC

NM_204305.1          TGGTCACCAGGGCTGCCGTCCTCTCTGGCAAAGTCCAAGTGGTGGCCATC

NM_204305.1          AATGATCCCTTCATCGATCTGAACTACATGGTTTACATGTTCAAATATGA

NM_204305.1          TTCTACACACGGACACTTCAAGGGCACTGTCAAGGCTGAGAACGGGAAAC

NM_204305.1          TTGTGATCAATGGGCACGCCATCACTATCTTCCAGGAGCGTGACCCCAGC

NM_204305.1          AACATCAAATGGGCAGATGCAGGTGCTGAGTATGTTGTGGAGTCCACTGG

NM_204305.1          TGTCTTCACCACCATGGAGAAGGCTGGGGCTCATCTGAAGGGTGGTGCTA

NM_204305.1          AGCGTGTTATCATCTCAGCTCCCTCAGCTGATGCCCCCATGTTTGTGATG

NM_204305.1          GGTGTCAACCATGAGAAATATGACAAGTCCCTGAAAATTGTCAGCAATGC

NM_204305.1          ATCGTGCACCACCAACTGCCTGGCACCCTTGGCCAAGGTCATCCATGACA

NM_204305.1          ACTTTGGCATTGTGGAGGGTCTTATGACCACTGTCCATGCCATCACAGCC

NM_204305.1          ACACAGAAGACGGTGGATGGCCCCTCTGGGAAGCTGTGGAGAGATGGCAG

NM_204305.1          AGGTGCTGCCCAGAACATCATCCCAGCGTCCACTGGGGCTGCTAAGGCTG

NM_204305.1          TGGGGAAAGTCATCCCTGAGCTGAATGGGAAGCTTACTGGAATGGCTTTC

NM_204305.1          CGTGTGCCAACCCCCAATGTCTCTGTTGTTGACCTGACCTGCCGTCTGGA

NM_204305.1          GAAACCAGCCAAGTATGATGATATCAAGAGGGTAGTGAAGGCTGCTGCTG

NM_204305.1          ATGGGCCCCTGAAGGGCATCCTAGGATACACAGAGGACCAGGTTGTCTCC

NM_204305.1          TGTGACTTCAATGGTGACAGCCATTCCTCCACCTTTGATGCGGGTGCTGG

NM_204305.1          CATTGCACTGAATGACCATTTCGTCAAGCTTGTTTCCTGGTATGACAATG

NM_204305.1          AGTTTGGATACAGCAACCGTGTTGTGGACTTGATGGTCCACATGGCATCC

NM_204305.1          AAGGAGTGAGCCAGGCACACAGCCCCCCTGCTGCCTAGGGAAGCAGGACC

NM_204305.1          CTTTGTTGGAGCCCCTGCTCTTCACCACCGCTCAGTTCTGCATCCTGCAG

NM_204305.1          TGAGAGGCCAGTTCTGTTCCCTTCTGTCTCCCCCACTCCTCCAATTTCTT

NM_204305.1          CCTCCACCTGGGGGAGGTGGGAGAGGCTGATAGAAACTGATCTGTTTGTG

NM_204305.1          TACCACCTTACATCAATAAAAGTGTTCACCATCTGAAG
;

end;
begin assumptions;
options deftype=unord;
end;

