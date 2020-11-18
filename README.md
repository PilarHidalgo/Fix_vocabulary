# Find_span: mini-programa multilingue para encontrar y extraer términos y spans-terminos (hechos en casa :blush:)
Esta herramienta permite englobar un conjunto de palabras (patterns) asignadas a un SPAN o categoría. El uso de esta herramienta es multiple, desde identificar sinónimos,  corrector de ortografía, hasta etiquetado de palabras en categorías como Persona, Organización, Lugar, lo único que necesitas es un diccionario donde generar los SPAN.

# Find_span: mini-program to find span (made by yourself) into a multilingual text.

### Usage:
    find_span(input_data, diccionary,format_file,output_format=('tuple','just_terms','just_label')):
    
       IN: find_SPAN('i love Dog’s tooth in pants',file_dictionary.xlsx,'excel','tuple')
       OUTPUT: ('checkered patterns', 'dog’s tooth')

Given a text (input_data) and a dictionary created especially to identify SPAN's, related terms or words, this little program can extract terms in three formats: tuple (e.g ('label','term/list of terms')),just the term/terms or just the  label of the SPAN. 

Further details are in the comments within the code.
