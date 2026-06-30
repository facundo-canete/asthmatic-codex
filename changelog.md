# Changelog
Este changelog pretende, de manera muy simple, explicar los cambios exclusivamente referidos a la arquitectura del Codex. El punto de partida va a ser, sin embargo, el primer registro que se tenga del mismo: el Asthmatic Dictionary.


## v2.5.0.x (30/06/2026): Asthmatic Codex [current]

### Added
- Archivo [*Idioms*](./english/idioms.md) dentro de [*English*](./english).


## v2.4.3.x (25/06/2026): Asthmatic Codex [b08cb78]

### Fixed
- Archivo [*README*](./README.md), error ortográfico.


## v2.4.2.x (25/06/2026): Asthmatic Codex [ccefcc6]

### Fixed
- Archivo [*Entries Changelog*](./entries-changelog.md), error ortográfico.


## v2.4.1.x (25/06/2026): Asthmatic Codex [5c47aba]

### Fixed
- Archivo [*Entries Changelog*](./entries-changelog.md) renombrado.


## v2.4.0.x (25/06/2026): Asthmatic Codex [ea4cbf7]

### Added
- Archivo [*Entries Changelog*](./entries-changelog.md).

### Changed
- Archivo *Eras* renombrado a [*Períodos*](./historia/periodos.md).
- Archivo *Frases* renombrado a [*Expresiones*](./español/expresiones.md).
- Archivo *Phrases* renombrado a [*Expressions*](./english/expressions.md).

### Deprecated
- Archivo *Propiedades* para ser absorbido por [*Operadores*](./yeites-matematicos/operadores.md).


## v2.3.0.x (18/06/2026): Asthmatic Codex [09986fd]

### Added
- Archivo [*README*](./README.md).


## v2.2.0.x (13/06/2026): Asthmatic Codex [0d10b36]

### Added
- Archivo [*Literatura y Obras*](./historia/literatura-y-obras.md) dentro de [*Historia*](./historia).
- Archivo [*Operadores*](./yeites-matematicos/operadores.md) dentro de [*Yeites Matemáticos*](./yeites-matematicos).
- Archivo *Git Ignore*.


## v2.1.0.x (11/06/2026): Asthmatic Codex [6e0155d]

### Added
- Archivo *Phrases* dentro de [*English*](./english).
- Carpeta [*Historia*](./historia).
- Archivo *Eras* dentro de [*Historia*](./historia).

### Changed
- Carpeta *Conceptos* renombrada a [*Abstracciones*](./abstracciones).


## v2.0.0.x (07/06/2026): Asthmatic Codex [0017e3f]

### Added
- Archivo [*Corrientes Filosóficas*](./abstracciones/corrientes-filosoficas.md) dentro de la carpeta *Conceptos*.
- Archivo [*Cultura Digital y Expresiones*](./abstracciones/cultura-digital-y-expresiones.md) dentro de la carpeta *Conceptos*.
- Archivo [*Educación*](./abstracciones/educacion.md) dentro de la carpeta *Conceptos*.
- Archivo [*Falacias*](./abstracciones/falacias.md) dentro de la carpeta *Conceptos*.
- Archivo [*Filosofía Fundamental*](./abstracciones/filosofia-fundamental.md) dentro de la carpeta *Conceptos*.
- Archivo [*Filosofía Medieval y Cristiana*](./abstracciones/filosofia-medieval-y-cristiana.md) dentro de la carpeta *Conceptos*.
- Archivo [*Hedonismo*](./abstracciones/hedonismo.md) dentro de la carpeta *Conceptos*.
- Archivo [*Lingüística y Filología*](./abstracciones/linguistica-y-filologia.md) dentro de la carpeta *Conceptos*.
- Archivo [*Método Socrático*](./abstracciones/metodo-socratico.md) dentro de la carpeta *Conceptos*.
- Archivo [*Paradojas y Experimentos Mentales*](./abstracciones/paradojas-y-experimentos-mentales.md) dentro de la carpeta *Conceptos*.
- Archivo [*Psicología*](./abstracciones/psicologia.md) dentro de la carpeta *Conceptos*.
- Archivo [*Sesgos Cognitivos*](./abstracciones/sesgos-cognitivos.md) dentro de la carpeta *Conceptos*.
- Archivo [*Sociología y Ciencias Sociales*](./abstracciones/sociologia-y-ciencias-sociales.md) dentro de la carpeta *Conceptos*.
- Archivo [*Lunfardo*](./español/lunfardo.md) dentro de la carpeta [*Español*](./español).
- Carpeta [*Yeites Matemáticos*](./yeites-matematicos).
- Archivo [*Diagramas*](./yeites-matematicos/diagramas.md) dentro de la carpeta [*Yeites Matemáticos*](./yeites-matematicos).
- Archivo [*Fórmulas*](./yeites-matematicos/formulas.md) dentro de la carpeta [*Yeites Matemáticos*](./yeites-matematicos).
- Archivo [*Fractales*](./yeites-matematicos/fractales.md) dentro de la carpeta [*Yeites Matemáticos*](./yeites-matematicos).
- Archivo [*Funciones*](./yeites-matematicos/funciones.md) dentro de la carpeta [*Yeites Matemáticos*](./yeites-matematicos).
- Archivo *Propiedades* dentro de la carpeta [*Yeites Matemáticos*](./yeites-matematicos).
- Archivo [*Símbolos*](./yeites-matematicos/simbolos.md) dentro de la carpeta [*Yeites Matemáticos*](./yeites-matematicos).
- Archivo [*Teoría*](./yeites-matematicos/teoria.md) dentro de la carpeta [*Yeites Matemáticos*](./yeites-matematicos).


## v1.0: Asthmatic Dictionary

A lo largo de toda esta primera versión se mantuvo un formato de tablas de doble entrada en Google Docs, en las que se introducía el concepto a definir en la primera columna y su respectiva definición en la columna consiguiente. Una de las principales diferencias, además de la más evidente que es el formato, es que dentro de la carpeta *Conceptos* se encontraban todas las entradas en una misma tabla, a diferencia de todas las demás carpetas que tenían una tabla específica para cada sección (los que ahora son archivos). La decisión de migrar del formato tabla en Google Docs a archivos Markdown se dio principalmente (aunque no exclusivamente) por considerarse insuficiente, poco escalable e ineficiente ante expansiones inminentes en el volumen y complejidad de entradas. El segundo gran motivo fue el objetivo de mantener consistente el formato tanto en desktop como en mobile sin necesidad de redimensionar tablas.