# OpenMRS-SQL-DATASET-SCRIPTS
These are SQL datasets created based on my experience implementing OpenMRS

This Git containt the followers SQL Script:

### `SQL - List of VALUE_TEXT by Age range`
 This return a list with fields: 
 
 * VALUE_TEXT from Concept ID called "Diagnostico" 
 * Encounter Date "Fecha de Encuentro
 * OpenMRS ID "ID"
 * Birthdate "Edad
 * Age Range "RangoEdad"

### `SQL - List of  VALUE_CODED by age range`
 This return a list with fields: 
 
 * VALUE_CODED "Codigo PF" 
 * Name of VALUE_CODED "Nombre Metodo"
 * Encounter Date "Fecha de Encuentro
 * OpenMRS ID "ID"
 * Birthdate "Edad
 * Age Range "RangoEdad"

### `SQL - Count of VALUE_CODED by patient QTY`
This return a count report with fields: 
 
 * VALUE_CODED "Codigo PF" 
 * Name of VALUE_CODED "Nombre Metodo"
 * Count of PersonID "Cantidad de Pacientes"
