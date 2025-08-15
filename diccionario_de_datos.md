## Diccionario de Datos - Clasificación de Riesgo en Pacientes

### Variables de Entrada

1. **11\_CodEtnia\_Indigena** – Variable binaria (0/1). Indica si el paciente pertenece a la etnia indígena.
2. **11\_CodEtnia\_Negro** – Variable binaria (0/1). Indica si el paciente pertenece a la comunidad negra.
3. **11\_CodEtnia\_Otro** – Variable binaria (0/1). Indica si el paciente pertenece a otra etnia.
4. **11\_CodEtnia\_Palenquero de San Basilio** – Variable binaria (0/1). Indica si el paciente pertenece a la comunidad palenquera de San Basilio.
5. **11\_CodEtnia\_ROM (Gitano)** – Variable binaria (0/1). Indica si el paciente pertenece a la comunidad ROM.
6. **11\_CodEtnia\_Raizal** – Variable binaria (0/1). Indica si el paciente pertenece a la comunidad Raizal.
7. **ENDOSALUD\_SI** – Variable binaria (0/1). Indica si el paciente pertenece al programa Endosalud.
8. **Indice Masa Corporal** – Valor numérico. Calculado como peso/talla².
9. **24\_Talla** – Altura del paciente en centímetros.
10. **23\_Peso** – Peso del paciente en kilogramos.
11. **25\_TenArtSis** – Presión arterial sistólica en mmHg.
12. **26\_TenArtDitlica** – Presión arterial diastólica en mmHg.
13. **36\_RcbeIECA\_SI** – Variable binaria (0/1). Uso de inhibidores de la enzima convertidora de angiotensina.
14. **37\_RcbeARA2\_SI** – Variable binaria (0/1). Uso de antagonistas de los receptores de angiotensina II.
15. **22\_EtiologiaERC\_HTA-DM** – Variable binaria (0/1). Etiología de enfermedad renal crónica por hipertensión y diabetes.
16. **EDAD (Años cumplidos)** – Edad del paciente en años.
17. **8\_Sexo\_F** – Variable binaria (0/1). 1 si el paciente es de sexo femenino.
18. **9\_Regimen\_CONTRIBUTIVO** – Variable binaria (0/1). Pertenencia al régimen contributivo.
19. **9\_Regimen\_NO ASEGURADO** – Variable binaria (0/1). Pertenencia a la población no asegurada.
20. **9\_Regimen\_SUBSIDIADO** – Variable binaria (0/1). Pertenencia al régimen subsidiado.
21. **18\_DxHTA\_SI** – Variable binaria (0/1). Diagnóstico de hipertensión arterial.
22. **18\_DxHTA\_NO** – Variable binaria (0/1). Ausencia de diagnóstico de hipertensión arterial.
23. **22\_EtiologiaERC\_HTA** – Variable binaria (0/1). Etiología de enfermedad renal crónica por hipertensión.
24. **22\_EtiologiaERC\_DM** – Variable binaria (0/1). Etiología de enfermedad renal crónica por diabetes mellitus.
25. **20\_DxDM\_SI** – Variable binaria (0/1). Diagnóstico de diabetes mellitus.

### Variables Objetivo (Clasificación Final del Riesgo)

* **CLASIFICACION FINAL DEL RIESGO\_ALTO** – 1 si el paciente está clasificado como alto riesgo.
* **CLASIFICACION FINAL DEL RIESGO\_BAJO** – 1 si el paciente está clasificado como bajo riesgo.
* **CLASIFICACION FINAL DEL RIESGO\_MODERADO** – 1 si el paciente está clasificado como riesgo moderado.
* **CLASIFICACION FINAL DEL RIESGO\_MUY ALTO** – 1 si el paciente está clasificado como muy alto riesgo.
