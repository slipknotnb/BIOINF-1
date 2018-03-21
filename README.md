# BIOINF-1
Nicolas Bonta Barros

# Trabajo Bioinformática 
#### Parte 1: Enfermedades genéticas y genes
 La enfermedad celíaca : es una enfermedad autoinmune caracterizada por la inflamación de las paredes intestinales debido a la presencia de gluten el cual el sistema inmune ataca, está asociada a los genes HLA-DQ1B y __HLA-DQA1__ principales genes de el complejo HLA  Sistema del antígeno leucocitario humano
 
  ##### Preguntas
 1. ##### _¿Tiene nombres alternativos el gen?_Sí, son 4 incluyendo el nombre original: __HLA-DQA1__, CELIAC1, DQ-A1, HLA-DQA
 2. ##### _¿En qué cromosoma está? ¿Cuántos exones tiene? ¿Cuántas isoformas de transcritos?_Se encuentra en el cromosoma 6 en la posición 6p21.32, posee 6 exones y 7 isoformas de transcritos
 3. ##### _¿Qué tipo de proteína es codificada por este gen? ¿Cuál es su número EC?_La proteína se llama antígeno de histocompatibilidad clase II, cadena DQ alfa 1, no posee número EC ya que no es una enzima 
 4. ##### _¿Qué genes están inmediatamente río arriba/abajo?_El gen que se encuentra río arriba con respecto a HLA-DQA1 es HLA-DQB1 y rio abajo el HLA-DRB1
 5. ##### _¿Cuál es la longitud de tu gen?_1591  pares de bases es la longitud del gen HLA-DQA1.
 6. ##### _¿Cuántas variantes de tu gen hay descritas y en qué posiciones?_ Son 7 las variantes descritas de este gen, todas se encuentran en el cromosoma 6
 7. ##### _¿Las sustituciones corresponden a cambios sinónimos o no sinónimos?_ Son 2 los cambios sinónimos, 3 no sinónimos Y existen 2 que no se conoce su significancia.
 8. ##### _¿Existen ortólogos de tu gen en otras especies? ¿Cuántos?_ si, existen 10 ortólogos de otras especies.
 9. ##### _¿Y parálogos? ¿Hay pseudogenes? ¿Cuántos?_ Sí, existen 25 parálogos en distintas zonas del cromosoma, de esos 25 hay 6 pertenecen al complejo HLA.

#### Parte 2: Rutas y procesos metabólicos 


 1. ##### _Anteriormente encontraste nombres alternativos de tu gen ¿Existen otros reportados por Kegg? ¿Cuáles?_Son los mismos en ambas paginas web, HLA-DQA1, CELIAC1, DQ-A1, HLA-DQA
 2. ##### _ ¿En qué rutas metabólicas participa la proteína codificada por tu gen?_ Participa en el linaje de células hematopoyéticas y rechazo de aloinjerto.
 3. ##### _¿Cuál es el número de identificación de tu gen (entry number)?_ 4942 
 4. ##### _¿En qué otras bases de datos está tu gen presente y cuáles son sus números de acceso?_En ncbi es 4942, Ensembl:ENSG00000196735, MIM:146880, Vega:OTTHUMG00000031106

![hsa05330.png](http://www.kegg.jp/tmp/mark_pathway152165093168084/hsa05330.png)
Imagen de la ruta matabolica asociada a rechazo de aloinjerto, en rojo se muestran en los lugares donde participa el gen.

5. ##### _¿En qué otras rutas metabólicas está involucrado tu gen?_Linaje de células hematopoyéticas, rechazo de aloinjerto, enfermedad autoinmune tiroidea, Procesamiento y presentación de antígenos, fagosoma, adhesión celular, red inmune intestinal para produccion de IgA y asma.
 6. ##### _¿Qué significan los cuadros verdes en el diagrama?_En la imagen los cuasros verdes que muestran MHC son factores de histocompatibilidad, los CD son cúmulos de diferenciación generalmente son marcadores que son reconocidos por las células, las IL son interleucinas funcionan como mensajeros químicos.	
 7. ##### _¿Con qué rutas se cruza la ruta metabólica?_Se cruza con la diabetes tipo 1, enfermedad de injerto contra el huesped, enfermedad tiraoidal autoinmune y asma.
 8. ##### _¿Cuántos "dominios" forman la anotación GO?_participa en el .
 9. ##### _	¿A qué corresponde este término y qué información te entrega la página?_el termino buscado corresponde a la glicolisis, la pagina muestra informacion y la relacion que existe desde un gen hasta una proteina y como esta se relaciona con los distintos procesos metabolicos y celulares, la funcionalidad principal de la pagina es que se puede buscar informacion detallada del origen de lo buscado y en que procesos participan indicando si participan de forma positiva u negativa en un proceso, como una especie de red que engolba todo.
 10. ##### _Anota 10 sub-categorías GO a la cual GO:0006096 pertenece_proceso glicolitico atravez de la fructosa 6 fosfato, regulacion negativa del proceso glicolitico, regulacion del proceso glicolitico por la transcripcion del promotor de la RNA pol II, regulacion positiva del proceso glicolitico, regulacion del proceso glicolitico atravez de la ruta de Entner-Doudoroff, proceso glicolitico atravez de  fructosa-1-fosfato, proceso glicolitco atravez del glicerol, actividad piruvato kinasa, proceso glicolitico de la sucrosa,regulación del proceso glucolítico de forma negativa en la transcripción del promotor de la ARN polimerasa II, regulación del proceso glucolítico de forma positiva en la transcripción del promotor de la ARN polimerasa II.

#### Parte 3: Descargando secuencias, convirtiendo formatos.
 
 1. ##### ¿Cuántos items fueron encontrados? ¿cuántos en animales?fueron encontrados 70748 articulos relacionoados cone el GAPDH.
 2. ##### _¿Cuál es la longitud del gen?_el geb del GAPDH basado en el paper tiene 1288bp 
 3. ##### _¿Cuál es la referencia bibliográfica más reciente?_ AUTHORS   Ren X, Zhang L, Gao Y, Gao H, Wang Y, Liu C, Cui H, Zhang Y, Jiang L, Qi X and Wang X.TITLE     Binding chicken Anx2 is beneficial for infection with infectiousbursal disease virusJOURNAL   Virus Res. 210, 232-240 (2015)
 4. ##### _¿Cuál es el número de acceso?_ NM_204305
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
