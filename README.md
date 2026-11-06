# Chaco: law history in git

Part of [lexifina/global-law](https://github.com/lexifina/global-law), one git history for every country's law: this is the law of Chaco, Argentina, which global-law reads at `argentina/chaco/acts/`.

The law of the Province of Chaco (Provincia del Chaco, Argentina) as a git history: one file per article, one commit per norm on the day it took effect. `git log` lists the changes to an article; checking out a date gives the text the record holds for that day.

It follows the shared design of [lexifina/global-law](https://github.com/lexifina/global-law), which places it at `ar-h/`. Argentina's national law is in [lexifina/argentina-law](https://github.com/lexifina/argentina-law).

The text is in Spanish, exactly as the source prints it.

## What this repository holds

2990 norms so far: the constitution first, then the codes, then laws, newest first, added in parts. 2911 of them are shown as enacted; the rest are their current consolidated text only (see Dates).

| Folder | Norm | History |
| --- | --- | --- |
| `constitucion/` | Constitución de la Provincia del Chaco 1957-1994 | current text only, as of 21 June 2013 |
| `ley-2950-m/` | Ley 2950-M: CÓDIGO PROCESAL DE NIÑEZ. ADOLESCENCIA Y FAMILIA | current text only, as of 9 October 2026 |
| `ley-2559-m/` | Ley 2559-M: CÓDIGO PROCESAL CIVIL Y COMERCIAL | current text only, as of 1 March 2021 |
| `ley-965-n/` | Ley 965-N: CODIGO PROCESAL PENAL | current text only, as of 8 September 2026 |
| `ley-850-j/` | Ley 850-J: CODIGO DE FALTAS DE LA PROVINCIA DEL CHACO | current text only, as of 10 September 2026 |
| `ley-713-i/` | Ley 713-I: CODIGO RURAL DE LA PROVINCIA DEL CHACO | current text only, as of 7 March 2018 |
| `ley-135-a/` | Ley 135-A: CODIGO CONTENCIOSO ADMINISTRATIVO | current text only, as of 20 September 2024 |
| `ley-353-r/` | Ley 353-R: CODIGO URBANO-AMBIENTAL DE LA CIUDAD DE RESISTENCIA | current text only, as of 9 April 2018 |
| `ley-555-r/` | Ley 555-R: CODIGO DE AGUAS. CREA LA ADMINISTRACION PROVINCIAL DEL AGUA | current text only, as of 3 May 2018 |
| `ley-179-a/` | Ley 179-A: CODIGO DE PROCEDIMIENTO ADMINISTRATIVO | current text only, as of 23 September 2024 |
| `ley-4268-f/` | Ley 4268-F: REGIMEN INCENTIVO NUEVAS INVERSIONES (RINI) "CHACO INVIERTE". | as enacted, in force 18 October 2026 |
| `ley-4269-k/` | Ley 4269-K: REGIMEN DE LAS CONCESIONES DE OBRAS Y SERVICIOS PUBLICOS Y DE INICIATIVAS PRIVADAS EN LA PROVINCIA DEL CHACO. ABROGASE LEY Nº 1053-A. | as enacted, in force 18 October 2026 |
| `ley-4267-a/` | Ley 4267-A: DECLARA DE INTERES LEGISLATIVO Y PROVINCIAL EL 39° CONGRESO NACIONAL DE CONTADURIAS GENERALES. | as enacted, in force 18 October 2026 |
| `ley-4266-g/` | Ley 4266-G: ESTABLECE LA SEMANA PROVINCIAL PARA LA PREVENCION DEL SUICIDIO. | as enacted, in force 18 October 2026 |
| `ley-4265-m/` | Ley 4265-M: MODIFICA EL ARTICULO 3 DE LA LEY N° 2950-M. | as enacted, in force 18 October 2026 |
| `ley-4264-g/` | Ley 4264-G: DIA PROVINCIAL DE LA PREVENCION DE LAS ENFERMEDADES VENOSAS. | as enacted, in force 18 October 2026 |
| `ley-4263-r/` | Ley 4263-R: PROCEDIMIENTO ADMINISTRATIVO Y JUDICIAL EXCEPCIONAL DE INTERVENCIÓN URGENTE DURANTE EMERGENCIAS HIDROMETEOROLÓGICAS. | as enacted, in force 23 September 2026 |
| `ley-4262-q/` | Ley 4262-Q: SUSPENSIÓN DE LA LEY 2073-Q -SISTEMA DE ELECCIONES PASO-. | as enacted, in force 23 September 2026 |
| `ley-4256-g/` | Ley 4256-G: SELLO PROFESIONAL BIOQUIMICO. | as enacted, in force 7 October 2026 |
| `ley-4255-a/` | Ley 4255-A: MODIFICA LEY 1940-A DE LA FISCALIA DE ESTADO INCREMENTO EN EL PORCENTAJE DE LOS CARGOS. | as enacted, in force 4 October 2026 |
| `ley-4260-a/` | Ley 4260-A: EXPROPIA INMUEBLE EN LA LOCALIDAD DE CHARADAI. | as enacted, in force 18 September 2026 |
| `ley-4259-f/` | Ley 4259-F: RATIFICA DECRETO 2021/2025 - EMERGENCIA ECONOMICA Y FINANCIERA-. | as enacted, in force 16 September 2026 |
| `ley-4257-j/` | Ley 4257-J: MODIFICA LEY 850-J CODIGO DE FALTAS DE LA PROVINCIA DEL CHACO Y MODIFICA LEY 949-T REGIMEN DE TRANSITO Y SEGURIDAD VIAL DE LA PROVINCIA DEL CHACO. | as enacted, in force 18 September 2026 |
| `ley-4250-j/` | Ley 4250-J: INCORPORASE COMO TITULO XIII DEL LIBRO II DE LA LEY 850-J CODIGO DE FALTAS DE LA PROVINCIA DEL CHACO-. | as enacted, in force 4 September 2026 |
| `ley-4254-g/` | Ley 4254-G: MODIFICA EL ARTICULO 10 DE LA LEY 3036-G -REGIMEN DE APADRINAMIENTO DE ENTIDADES VINCULADAS A LA SALUD-. | as enacted, in force 7 August 2026 |
| `ley-4253-a/` | Ley 4253-A: EXPEDIENTE ELECTRONICO TRIBUNAL DE CUENTAS DE LA PROVINCIA DEL CHACO. | as enacted, in force 14 August 2026 |
| `ley-4251-v/` | Ley 4251-V: FIESTA PROVINCIAL DEL PACU ARROCERO. | as enacted, in force 7 August 2026 |
| `ley-4249-a/` | Ley 4249-A: PRORROGA LEY 2024-K. | as enacted, in force 7 August 2026 |
| `ley-4248-h/` | Ley 4248-H: MODIFICA LOS ARTICULOS 6°, 15, 68 Y 71 DE LA LEY 800-H (ANTES LEY 4044) - REGIMEN DE JUBILACIONES Y PENSIONES. | as enacted, in force 21 August 2026 |
| `ley-4247-s/` | Ley 4247-S: NEWCOM DEPORTE PROVINCIAL. | as enacted, in force 14 August 2026 |
| `ley-4246-g/` | Ley 4246-G: MODIFICACIONES A LA LEY 9-G, REGULACIONES SOBRE SEDACION. | as enacted, in force 7 August 2026 |
| `ley-4245-g/` | Ley 4245-G: REGISTRO DE PROFESIONALES DE SALUD MATRICULADOS EN LA PROVINCIA DEL CHACO. | as enacted, in force 31 July 2026 |
| `ley-4244-r/` | Ley 4244-R: REGIMEN DE FORTALECIMIENTO DE LA RESPUESTA SANCIONATORIA Y DE PROTECCION ANIMAL. MODIFICA LEY 850-J. | as enacted, in force 5 August 2026 |
| `ley-4243-a/` | Ley 4243-A: MODIFICA INCISO C) DEL ARTICULO 1 DE LA LEY 4132-A. | as enacted, in force 4 September 2026 |
| `ley-4242-e/` | Ley 4242-E: REGULA DISPOSITIVOS DIGITALES EN EL AMBITO EDUCATIVO PROVINCIAL. | as enacted, in force 2 August 2026 |
| `ley-4241-a/` | Ley 4241-A: DESAFECTACION Y TRANSFERENCIA DE INMUEBLES DEL ESTADO PROVINCIAL A FAVOR DE LA FUNDACION LOS DINOSAURIOS. | as enacted, in force 19 June 2026 |
| `ley-4240-e/` | Ley 4240-E: DESIGNACION UNICA Y EXCEPCIONAL DE CARGOS DE SUPERVISION DEL NIVEL SECUNDARIO. | as enacted, in force 1 July 2026 |
| `ley-4239-a/` | Ley 4239-A: EXPROPIACION DE INMUEBLES UBICADOS EN LA LOCALIDAD DE PAMPA DEL INDIO. | as enacted, in force 5 July 2026 |
| `ley-4238-t/` | Ley 4238-T: MODIFICA LEY 1115-T. | as enacted, in force 1 July 2026 |
| `ley-4237-e/` | Ley 4237-E: DÍA PROVINCIAL DE LA LUCHA CONTRA EL AVASALLAMIENTO DE LA AUTONOMÍA UNIVERSITARIA. | as enacted, in force 5 July 2026 |
| `ley-4236-a/` | Ley 4236-A: EXPROPIA INMUEBLE UBICADO EN LA CIUDAD DE RESISTENCIA DEPARTAMENTO SAN FERNANDO. | as enacted, in force 5 July 2026 |
| `ley-4234-v/` | Ley 4234-V: PROMOCIÓN SOBRE EL PEZ DORADO (SALMINUS BRASILIENSIS). | as enacted, in force 19 June 2026 |
| `ley-4232-a/` | Ley 4232-A: DIA DE DUELO PROVINCIAL. | as enacted, in force 5 July 2026 |
| `ley-4235-a/` | Ley 4235-A: REINSTAURA LA VIGENCIA DE LA LEY 3471-A. | as enacted, in force 19 June 2026 |
| `ley-4233-a/` | Ley 4233-A: REINSTAURA LA VIGENCIA DE LA LEY 2867-A. | as enacted, in force 10 June 2026 |
| `ley-4231-k/` | Ley 4231-K: INCORPORA EL ARTÍCULO 10 BIS A LA LEY 2024-K (antes Ley 7030). | as enacted, in force 10 June 2026 |
| `ley-4228-c/` | Ley 4228-C: LEY DE HONORARIOS DE PROFESIONALES DE LA ABOGACIA Y PRINCIPIOS GENERALES. ABROGA LA LEY 288-C. | as enacted, in force 29 April 2026 |
| `ley-4229-e/` | Ley 4229-E: OBSERVATORIO LEGISLATIVO MALVINAS. | as enacted, in force 24 April 2026 |
| `ley-4230-g/` | Ley 4230-G: MODIFICASE EL ARTICULO 5° DE LA LEY 4197-G -EXAMENES TOXICOLOGICOS. | as enacted, in force 24 April 2026 |
| `ley-4227-a/` | Ley 4227-A: LEYENDAS OFICIALES TRANSITORIAS. | as enacted, in force 29 March 2026 |
| `ley-4205-a/` | Ley 4205-A: DEROGA INCISO B) APARTADO C DEL ANEXO I A LA LEY 3731-A | as enacted, in force 30 January 2026 |
| `ley-4207-a/` | Ley 4207-A: PRORRÓGASE LA LEY 3994-A. | as enacted, in force 30 January 2026 |
| `ley-4208-s/` | Ley 4208-S: PROGRAMA PROVINCIAL DE PROMOCIÓN Y FORTALECIMIENTO DEL DEPORTE URBANO. | as enacted, in force 30 January 2026 |
| `ley-4209-e/` | Ley 4209-E: DÍA PROVINCIAL DE LAS ALTAS CAPACIDADES | as enacted, in force 30 January 2026 |
| `ley-4210-p/` | Ley 4210-P: ELEVA DE CATEGORÍA AL MUNICIPIO DE EL SAUZALITO | as enacted, in force 30 January 2026 |
| `ley-4211-a/` | Ley 4211-A: REINSTAURA LA VIGENCIA DE LA LEY 3081-A. | as enacted, in force 30 January 2026 |
| `ley-4212-e/` | Ley 4212-E: DIA PROVINCIAL DE LA CHARANDA. | as enacted, in force 30 January 2026 |
| `ley-4214-g/` | Ley 4214-G: REGULA LA ATENCIÓN PRIMARIA DE SALUD VISUAL. | as enacted, in force 30 January 2026 |
| `ley-4215-a/` | Ley 4215-A: EXPROPIACIÓN DE INMUEBLE UBICADO EN LA CIUDAD DE FONTANA. | as enacted, in force 30 January 2026 |
| `ley-4216-g/` | Ley 4216-G: SISTEMA DE POSICIONAMIENTO GLOBAL (GPS) PARA AMBULANCIAS PERTENECIENTES AL MINISTERIO DE SALUD. | as enacted, in force 30 January 2026 |
| `ley-4217-a/` | Ley 4217-A: RATIFICA RESOLUCIONES N° 15/24 Y 23/24 DE LA COMISION PLENARIA DEL CONVENIO MULTILATERAL DEL 18/8/77. | as enacted, in force 30 January 2026 |
| `ley-4218-v/` | Ley 4218-V: PLATAFORMA DIGITAL INTELIGENTE SOBRE TURISMO AMBIENTAL SUSTENTABLE Y DE AVENTURA. | as enacted, in force 30 January 2026 |
| `ley-4219-e/` | Ley 4219-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL DE LA PROVINCIA DEL CHACO A -EL CHALET- EN EL PARAJE PAMPA ARGENTINA, JURISDICCIÓN DE JUAN JOSÉ CASTILLI | as enacted, in force 30 January 2026 |
| `ley-4224-e/` | Ley 4224-E: DÍA PROVINCIAL DEL YOGA. | as enacted, in force 30 January 2026 |
| `ley-4220-r/` | Ley 4220-R: DECLARA "MONUMENTO NATURAL PROVINCIAL" Y DE INTERÉS PROVINCIAL A LAS ESPECIES ANIMALES: CARAYÁ (ALOUATTA CARAYA) Y MIRIKINÁ (AOTUS AZARAE) | as enacted, in force 30 January 2026 |
| `ley-4221-e/` | Ley 4221-E: DÍA PROVINCIAL DEL HUMORISTA. | as enacted, in force 30 January 2026 |
| `ley-4223-e/` | Ley 4223-E: CENTRO CULTURAL ALTERNATIVO HUGO OSVALDO BLOTTA. | as enacted, in force 30 January 2026 |
| `ley-4225-a/` | Ley 4225-A: RATIFICA EL DECRETO 1654/25. | as enacted, in force 30 January 2026 |
| `ley-4226-a/` | Ley 4226-A: EXPROPIA INMUEBLE. | current text only, as of 5 February 2026 |
| `ley-4199-a/` | Ley 4199-A: CREA UNA FISCALÍA DE INVESTIGACIÓN PENAL DEPENDIENTE DE LA SEXTA CIRCUNSCRIPCIÓN JUDICIAL | as enacted, in force 30 January 2026 |
| `ley-4204-r/` | Ley 4204-R: MANEJO DEL FUEGO, PREVENCIÓN Y LUCHA CONTRA INCENDIOS | as enacted, in force 30 January 2026 |
| `ley-4197-g/` | Ley 4197-G: "EXÁMENES TOXICOLÓGICOS OBLIGATORIOS PARA EL EJERCICIO DE LA FUNCIÓN PÚBLICA EN EL ÁMBITO DE LA PROVINCIA" | as enacted, in force 26 December 2025 |
| `ley-4213-f/` | Ley 4213-F: RESTABLECE VIGENCIA DE LA LEY 3898-F (RÉGIMEN DE REGULARIZACIÓN EXCEPCIONAL DE OBLIGACIONES TRIBUTARIAS). | as enacted, in force 2 January 2026 |
| `ley-4198-e/` | Ley 4198-E: PATRIMONIO HISTÓRICO Y CULTURAL DE LA PROVINCIA DEL CHACO AL SITIO MEMORIAL DE LA MASACRE DE NAPALPÍ | as enacted, in force 26 December 2025 |
| `ley-4203-c/` | Ley 4203-C: RECONOCER A LAS IGLESIAS, CONFESIONES, COMUNIDADES O ENTIDADES RELIGIOSAS NO CATÓLICAS COMO PERSONAS JURÍDICAS PRIVADAS. DEROGA LEY 1499-C. | as enacted, in force 2 January 2026 |
| `ley-4202-a/` | Ley 4202-A: DECLARASE EL AÑO 2026 COMO EL "100º ANIVERSARIO DE LA SANCION DE LA LEY DE DERECHOS CIVILES DE LA MUJER-LEY NACIONAL 11.357". | as enacted, in force 2 February 2026 |
| `ley-4200-h/` | Ley 4200-H: REGIMEN DE RETIRO VOLUNTARIO MOVIL | as enacted, in force 19 December 2025 |
| `ley-4201-h/` | Ley 4201-H: MODIFICA ARTICULO 37 DE LA LEY 800-H. | as enacted, in force 9 January 2026 |
| `ley-4184-j/` | Ley 4184-J: PREVENCIÓN Y PROTECCIÓN DE NIÑOS, NIÑAS y ADOLESCENTES FRENTE AL CONSUMO PROBLEMÁTICO DE JUEGOS VIRTUALES DE AZAR. | as enacted, in force 19 December 2025 |
| `ley-4190-a/` | Ley 4190-A: PROGRAMA PROVINCIAL TRANSITORIO AL RÉGIMEN DE REPARACIÓN ECONÓMICA PREVISTA EN LA LEY NACIONAL 27.452 | as enacted, in force 21 November 2025 |
| `ley-4189-p/` | Ley 4189-P: AREAS DE INFLUENCIA DE LOS MUNICIPIOS COLONIA ABORIGEN Y MACHAGAI. | as enacted, in force 21 November 2025 |
| `ley-4185-p/` | Ley 4185-P: RATIFICA DECRETO 1598/01. | as enacted, in force 21 November 2025 |
| `ley-4193-g/` | Ley 4193-G: ADHIERE LA PROVINCIA DEL CHACO A LA LEY NACIONAL 27.669-MARCO REGULATORIO PARA EL DESARROLLO DE LA INDUSTRIA DEL CANNABIS MEDICINAL Y EL CÁÑAMO INDU… | as enacted, in force 21 November 2025 |
| `ley-4192-g/` | Ley 4192-G: ADHESIÓN A LA LEY NACIONAL 27.678 -PROGRAMA NACIONAL DE CUIDADOS PALIATIVOS. | as enacted, in force 21 November 2025 |
| `ley-4191-l/` | Ley 4191-L: CREACIÓN DE JUZGADOS EN LA IV CIRCUNSCRIPCIÓN. | as enacted, in force 21 November 2025 |
| `ley-4188-a/` | Ley 4188-A: EXPROPIA INMUEBLES EN LA CIUDAD DE RESISTENCIA -VILLA LIBERTAD | as enacted, in force 21 November 2025 |
| `ley-4187-g/` | Ley 4187-G: DIA PROVINCIAL DE LA MENOPAUSIA. | as enacted, in force 21 November 2025 |
| `ley-4186-a/` | Ley 4186-A: EXPROPIACIÓN DE UN INMUEBLE EN RESISTENCIA PARA LA CONSTRUCCIÓN DE LA COMISARÍA 13°. | as enacted, in force 21 November 2025 |
| `ley-4178-a/` | Ley 4178-A: REINSTAURA LA VIGENCIA DE LA LEY 2337-A (ANTES LEY 7618). | as enacted, in force 28 September 2025 |
| `ley-4172-e/` | Ley 4172-E: DIA PROVINCIAL DE LA EDUCACION FINANCIERA. | as enacted, in force 28 September 2025 |
| `ley-4183-i/` | Ley 4183-I: CAPITAL PROVINCIAL DEL BUFALO. | as enacted, in force 28 September 2025 |
| `ley-4181-a/` | Ley 4181-A: EXPROPIA INMUEBLE EN LA CIUDAD DE RESISTENCIA-VILLA CRISTO REY. | as enacted, in force 28 September 2025 |
| `ley-4180-a/` | Ley 4180-A: REINSTAURA LEY 2064-A. | as enacted, in force 28 September 2025 |
| `ley-4179-a/` | Ley 4179-A: PRORROGA LA VIGENCIA DE LA LEY 3975-A. | as enacted, in force 28 September 2025 |
| `ley-4177-a/` | Ley 4177-A: REINSTAURA LEY 2540-A. | as enacted, in force 28 September 2025 |
| `ley-4174-a/` | Ley 4174-A: MODIFICA EL INCISO B) DEL ARTICULO 6, LOS INCISOS B) Y C) DEL ARTICULO 7 Y EL ARTICULO 36 DE LA LEY 1940-A (ANTES LEY 6808). | as enacted, in force 28 September 2025 |
| `ley-4173-t/` | Ley 4173-T: MODIFICA EL INCISO C) DEL ARTICULO 69 DEL ANEXO "A" DE LA LEY 949-T (ANTES LEY 4488) - REGIMEN DE TRANSITO Y SEGURIDAD VIAL DE LA PROVINCIA DEL CHAC… | as enacted, in force 28 September 2025 |
| `ley-4182-a/` | Ley 4182-A: EXPROPIA INMUEBLE EN LA CIUDAD DE BARRANQUERAS - BARRIO SAN CAYETANO. | as enacted, in force 28 September 2025 |
| `ley-4175-p/` | Ley 4175-P: EXCEPCION AL TRAMITE DE SUBDIVISION DE INMUEBLES PARA TIERRAS INCORPORADAS EL EJIDO URBANO. | as enacted, in force 28 September 2025 |
| `ley-4176-a/` | Ley 4176-A: TRANSFERENCIA INMUEBLE INSTITUTO PROVINCIAL DE DESARROLLO URBANO Y VIVIENDA A FUNDACIÓN ESPERANZA. | as enacted, in force 28 September 2025 |
| `ley-4171-k/` | Ley 4171-K: MODIFICA ARTICULOS DE LA LEY 3383-K. | as enacted, in force 28 September 2025 |
| `ley-4170-e/` | Ley 4170-E: PREMIO ANUAL "CECILIA BARONI" | as enacted, in force 28 September 2025 |
| `ley-4168-m/` | Ley 4168-M: CREA JUZGADO EN LA SEGUNDA CIRCUNSCRIPCION JUDICIAL. | as enacted, in force 27 June 2025 |
| `ley-4167-p/` | Ley 4167-P: LEY ORGANICA MUNICIPAL. | as enacted, in force 27 June 2025 |
| `ley-4160-a/` | Ley 4160-A: EXPROPIA INMUEBLE. | current text only, as of 3 February 2026 |
| `ley-4161-w/` | Ley 4161-W: 5 DE SEPTIEMBRE ASUETO LABORAL PARA LAS MUJERES PERTENECIENTES A LOS PUEBLOS ORIGINARIOS. | as enacted, in force 27 June 2025 |
| `ley-4162-a/` | Ley 4162-A: EXPROPIA INMUEBLE EN RESISTENCIA PARA RESERVA NATURAL. | as enacted, in force 28 September 2025 |
| `ley-4158-a/` | Ley 4158-A: CREACIÓN DE LA ASESORÍA DE NIÑAS, NIÑOS Y ADOLESCENTES N° 3 CON ASIENTO EN LA SEGUNDA CIRCUNSCRIPCIÓN JUDICIAL. | as enacted, in force 27 June 2025 |
| `ley-4159-a/` | Ley 4159-A: CREACIÓN DE LA ASESORÍA DE NIÑAS, NIÑOS Y ADOLESCENTES N° 7 CON ASIENTO EN LA PRIMERA CIRCUNSCRIPCIÓN JUDICIAL. | as enacted, in force 27 June 2025 |
| `ley-4163-a/` | Ley 4163-A: TRANSFERENCIA DE DOMINIO A FAVOR DE LA MUNICIPALIDAD DE RESISTENCIA. | as enacted, in force 22 June 2025 |
| `ley-4164-v/` | Ley 4164-V: CREACION DEL REGISTRO UNICO PROVINCIAL DE FIESTAS RELIGIOSAS Y PATRONALES. | as enacted, in force 27 June 2025 |
| `ley-4165-h/` | Ley 4165-H: PROGRAMAS DE AYUDA PROVINCIAL (PAPRO) Y MUNICIPAL (PAM) | as enacted, in force 27 June 2025 |
| `ley-4166-a/` | Ley 4166-A: RATIFICA DECRETO 203/25. PRORROGA HASTA EL 31/12/25 LA EMERGENCIA ECONÓMICA Y FINANCIERA DE LA PROVINCIA, DISPUESTA POR LEY 2425-F (ANTES LEY 7751). | as enacted, in force 27 June 2025 |
| `ley-4157-r/` | Ley 4157-R: MODIFICA LEY 2079-R: REGIMEN DE SANCIONES PARA LA ACTIVIDAD FORESTAL. | as enacted, in force 28 September 2025 |
| `ley-4156-f/` | Ley 4156-F: MEDIDAS FISCALES. LEY 299-F -TARIFARIA PROVINCIAL - MODIFICACIONES. | as enacted, in force 20 June 2025 |
| `ley-4155-f/` | Ley 4155-F: LEY 83-F - CODIGO TRIBUTARIO PROVINCIAL - MODIFICACIONES | as enacted, in force 20 June 2025 |
| `ley-4154-i/` | Ley 4154-I: PRORROGA POR EL TERMINO DE CUATRO (4) AÑOS A PARTIR DEL 9 DE ENERO DE 2025 LA VIGENCIA DE LA LEY 937-I (ANTES LEY 4453). | as enacted, in force 14 May 2025 |
| `ley-4149-a/` | Ley 4149-A: EXPROPIACIÓN DE INMUEBLES EN LA LOCALIDAD DE SAMUHÚ - ABROGASE LA LEY 3469-A. | as enacted, in force 23 May 2025 |
| `ley-4148-a/` | Ley 4148-A: REINSTAURA LA LEY 2057-A (ANTES LEY 7115) | as enacted, in force 17 January 2025 |
| `ley-4147-a/` | Ley 4147-A: DEROGA Y MODIFICA DATOS IDENTIFICATORIOS DE INMUEBLES DEL ANEXO I LEY 3731-A | as enacted, in force 12 February 2025 |
| `ley-4146-a/` | Ley 4146-A: MODIFICA EL ANEXO I A LA LEY 3790-A | as enacted, in force 12 February 2025 |
| `ley-4145-a/` | Ley 4145-A: MODIFICA EL ARTÍCULO 6° DE LA LEY 3434-R - DEROGA Y MODIFICA APARTADOS DEL ANEXO I DE LA LEY 3434-R | as enacted, in force 17 January 2025 |
| `ley-4144-a/` | Ley 4144-A: EXPROPIA INMUEBLE | as enacted, in force 17 January 2025 |
| `ley-4143-a/` | Ley 4143-A: DONACIÓN DE INMUEBLE A LA UNIÓN DE LA CONSTRUCCIÓN DE LA REPÚBLICA ARGENTINA (UOCRA) | as enacted, in force 17 January 2025 |
| `ley-4142-g/` | Ley 4142-G: DIA PROVINCIAL DE LA ENFERMEDAD DE FABRY | as enacted, in force 17 January 2025 |
| `ley-4139-g/` | Ley 4139-G: DIA PROVINCIAL DEL ENFERMERO Y ENFERMERA | as enacted, in force 17 January 2025 |
| `ley-4138-b/` | Ley 4138-B: DIGESTO JURIDICO DE LA PROVINCIA DEL CHACO | as enacted, in force 12 February 2025 |
| `ley-4153-b/` | Ley 4153-B: LEYENDA EN PAPELERÍA PARA EL AÑO 2025 " AÑO DEL 40º ANIVERSARIO DEL JUICIO A LA JUNTAS MILITARES" | as enacted, in force 29 December 2024 |
| `ley-4136-a/` | Ley 4136-A: REINSTAURA LEY 2340-A (ANTES LEY 7623) | as enacted, in force 17 January 2025 |
| `ley-4137-a/` | Ley 4137-A: REINSTAURA LEY 1040-A (ANTES LEY 4674) | as enacted, in force 17 January 2025 |
| `ley-4141-g/` | Ley 4141-G: DÍA PROVINCIAL DE LA CONCIENTIZACIÓN DE LA ENFERMEDAD CARDIOVASCULAR EN LA MUJER. | as enacted, in force 9 February 2025 |
| `ley-4140-a/` | Ley 4140-A: EXPROPIA INMUEBLE | as enacted, in force 12 February 2025 |
| `ley-4152-r/` | Ley 4152-R: MODIFICACION DE LA LEY 4005-R. | as enacted, in force 29 December 2024 |
| `ley-4150-f/` | Ley 4150-F: AUTORIZA OPERACIONES DE CREDITO PUBLICO PARA LA INFRAESTRUCTURA PROVINCIAL. | as enacted, in force 27 December 2024 |
| `ley-4151-f/` | Ley 4151-F: MODIFICACIONES AL FINANCIAMIENTO DEL CHACO SUBSIDIA. | as enacted, in force 27 December 2024 |
| `ley-4134-j/` | Ley 4134-J: INCORPORA EL ARTÍCULO 39 BIS A LA LEY 2855-J. | as enacted, in force 6 December 2024 |
| `ley-4133-e/` | Ley 4133-E: USO DE INTELIGENCIA ARTIFICIAL. | as enacted, in force 25 December 2024 |
| `ley-4132-a/` | Ley 4132-A: EXPROPIA INMUEBLES EN LA CIUDAD DE GENERAL JÓSE DE SAN MARTÍN. | as enacted, in force 25 December 2024 |
| `ley-4131-c/` | Ley 4131-C: MODIFICA ARTÍCULOS DE LA LEY 2955-C. | as enacted, in force 25 December 2024 |
| `ley-4129-e/` | Ley 4129-E: DECLARA PATRIMONIO HISTORICO Y CULTURAL AL SITIO MEMORIAL MASACRE DE EL ZAPALLAR. | as enacted, in force 25 December 2024 |
| `ley-4130-q/` | Ley 4130-Q: SUSPENDE POR EL TÉRMINO DE UN (1) AÑO LA VIGENCIA DE LA LEY 2073-Q. | as enacted, in force 6 December 2024 |
| `ley-4128-i/` | Ley 4128-I: INSTITUYE EL 15 DE NOVIEMBRE DE CADA AÑO COMO  "DÍA DEL TANINERO DE LA PROVINCIA DEL CHACO". | as enacted, in force 8 December 2024 |
| `ley-4118-a/` | Ley 4118-A: INCREMENTO SALARIAL EN EL TRIBUNAL DE CUENTAS, PODER JUDICIAL, TRIBUNAL ELECTORAL, CONSEJO DE LA MAGISTRATURA Y JURADO DE ENJUICIAMIENTO. | as enacted, in force 22 December 2024 |
| `ley-4115-a/` | Ley 4115-A: RATIFICA DECRETO 1588/22. | as enacted, in force 22 December 2024 |
| `ley-4111-a/` | Ley 4111-A: RATIFICA DECRETO 1068/21. | as enacted, in force 22 December 2024 |
| `ley-4110-a/` | Ley 4110-A: RATIFICA DECRETO 1067/21. | as enacted, in force 22 December 2024 |
| `ley-4109-a/` | Ley 4109-A: RATIFICA DECRETO 302/24. | as enacted, in force 20 December 2024 |
| `ley-4107-a/` | Ley 4107-A: RATIFICA DECRETO 1685/24. | as enacted, in force 22 December 2024 |
| `ley-4126-a/` | Ley 4126-A: RATIFICA DECRETO 2756/2023. | as enacted, in force 22 December 2024 |
| `ley-4125-a/` | Ley 4125-A: RATIFICA DECRETO 2887/2023. | as enacted, in force 22 December 2024 |
| `ley-4124-a/` | Ley 4124-A: RATIFICA DECRETO 1676/22. | as enacted, in force 22 December 2024 |
| `ley-4123-f/` | Ley 4123-F: MODIFICA PRESUPUESTO 2023. | as enacted, in force 12 January 2025 |
| `ley-4122-a/` | Ley 4122-A: RATIFICA DECRETO 1859/22. | as enacted, in force 22 December 2024 |
| `ley-4120-a/` | Ley 4120-A: RATIFICA DECRETO 1523/21. | as enacted, in force 22 December 2024 |
| `ley-4121-a/` | Ley 4121-A: RATIFICA DECRETO 978/2022. | as enacted, in force 26 December 2024 |
| `ley-4105-a/` | Ley 4105-A: RATIFICA DECRETO 1687/24 PARA LAS SIGUIENTES JUR.: 8-TRIBUNAL DE CUENTAS, 9-PODER JUDICIAL, 17- TRIBUNAL ELECTORAL, 40-CONSEJO DE LA MAGISTRATURA Y … | as enacted, in force 6 December 2024 |
| `ley-4104-e/` | Ley 4104-E: DECLARA PATRIMONIO HISTORICO Y CULTURAL A LA CAPILLA "SAN ANTONIO DE PADUA". | as enacted, in force 6 December 2024 |
| `ley-4112-a/` | Ley 4112-A: INCREMENTO EN LAS PRESTACIONES SOCIALES LEYES 1369-H - 1370-H - 1614-H RATIFICA DECRETO 2250/2021. | as enacted, in force 22 December 2024 |
| `ley-4113-a/` | Ley 4113-A: RATIFICA DECRETO 2675/2021. | as enacted, in force 6 December 2024 |
| `ley-4114-a/` | Ley 4114-A: RATIFICA DECRETOS 496/2022 Y 989/2022. | as enacted, in force 22 December 2024 |
| `ley-4116-a/` | Ley 4116-A: RATIFICA DECRETO 1749/2022. | as enacted, in force 6 December 2024 |
| `ley-4106-a/` | Ley 4106-A: RATIFICA DECRETO 1681/2024 PARA LAS SIGUIENTES JURIDICCIONES: 21 PERSONAL POLICIAL y 36 PERSONAS DEL SERVICIO PENITENCIARIO PROVINCIAL. | as enacted, in force 6 December 2024 |
| `ley-4117-a/` | Ley 4117-A: RATIFICA DECRETOS 2116/2022 Y 2483/2022. | as enacted, in force 6 December 2024 |
| `ley-4119-a/` | Ley 4119-A: RATIFICA DECRETO 1667/2020. | as enacted, in force 6 December 2024 |
| `ley-4127-a/` | Ley 4127-A: RATIFICA DECRETO 1263/2022. | as enacted, in force 25 December 2024 |
| `ley-4099-i/` | Ley 4099-I: PROGRAMA DISTINTIVO DE CALIDAD. | as enacted, in force 22 November 2024 |
| `ley-4100-g/` | Ley 4100-G: DIA PROVINCIAL DE LA DONACION DE LECHE HUMANA. | as enacted, in force 22 November 2024 |
| `ley-4098-e/` | Ley 4098-E: DIA PROVINCIAL DEL AJEDREZ ESCOLAR. | as enacted, in force 22 November 2024 |
| `ley-4095-e/` | Ley 4095-E: REGIMEN DE ESCUELAS PUBLICAS DE GESTION SOCIAL. | as enacted, in force 22 November 2024 |
| `ley-4096-a/` | Ley 4096-A: REINSTAURA  LEY 2024-K(ANTES LEY 7030). | as enacted, in force 6 December 2024 |
| `ley-4093-e/` | Ley 4093-E: EDUCACION FINANCIERA EN EL NIVEL SECUNDARIO. | as enacted, in force 18 October 2024 |
| `ley-4091-e/` | Ley 4091-E: MODIFICA LA LEY 2381-E. | as enacted, in force 3 November 2024 |
| `ley-4094-v/` | Ley 4094-V: SEMANA DEL TURISMO CHAQUEÑO. | as enacted, in force 24 November 2024 |
| `ley-4092-a/` | Ley 4092-A: REINSTAURA LA LEY 2615-A (ANTES LEY 8010). | as enacted, in force 9 February 2025 |
| `ley-4090-e/` | Ley 4090-E: MODIFICA  ARTICULO 354 DE LA LEY 647-E. | as enacted, in force 12 January 2025 |
| `ley-4089-a/` | Ley 4089-A: PRORROGA LA LEY 2828-A. | as enacted, in force 3 November 2024 |
| `ley-4088-a/` | Ley 4088-A: RÉGIMEN DE REGULARIZACIÓN  DE ACTIVOS - ADHESIÓN AL TÍTULO II DE LA LEY NACIONAL 27.743. | as enacted, in force 1 November 2024 |
| `ley-4087-a/` | Ley 4087-A: EXPROPIA INMUEBLE EN LA CIUDAD DE BARRANQUERAS. | as enacted, in force 24 November 2024 |
| `ley-4086-a/` | Ley 4086-A: ADHESIÓN AL RÉGIMEN DE INCENTIVO PARA GRANDES INVERSIONES (R.I.G.I). | as enacted, in force 9 October 2024 |
| `ley-4085-k/` | Ley 4085-K: PRÓRROGA DE LA EMERGENCIA HABITACIONAL Y DE INFRAESTRUCTURA SOCIAL BÁSICA. | as enacted, in force 9 October 2024 |
| `ley-4084-g/` | Ley 4084-G: DIA PROVINCIAL DEL SÍNDROME DE GUILLAIN-BARRÉ | as enacted, in force 9 February 2025 |
| `ley-4083-a/` | Ley 4083-A: EXPROPIA INMUEBLE EN LA CIUDAD DE RESISTENCIA. | current text only, as of 27 October 2024 |
| `ley-4082-a/` | Ley 4082-A: PRORROGA LEY 1919-A(ANTES LEY 6773). | as enacted, in force 9 February 2025 |
| `ley-4081-a/` | Ley 4081-A: PRORROGA LEY 3293-A. | as enacted, in force 9 February 2025 |
| `ley-4080-a/` | Ley 4080-A: REINSTAURA LEY 2756-A. | as enacted, in force 6 December 2024 |
| `ley-4072-g/` | Ley 4072-G: ACCESO INTEGRAL A LA PREVENCION, DETECCION, DIAGNOSTICO Y CONTROLES NECESARIOS PARA EL ABORDAJE DE LA ENDOMETRIOSIS. | as enacted, in force 20 November 2024 |
| `ley-4075-r/` | Ley 4075-R: MODIFICACION  DE LA LEY 1485-R. | as enacted, in force 18 September 2024 |
| `ley-4076-f/` | Ley 4076-F: REGULARIZACIÓN EXCEPCIONAL DE OBLIGACIONES TRIBUTARIAS. | as enacted, in force 9 October 2024 |
| `ley-4077-e/` | Ley 4077-E: DIA PROVINCIAL DE LAS AREAS NATURALES PROTEGIDAS. | as enacted, in force 18 September 2024 |
| `ley-4074-e/` | Ley 4074-E: CREA EL SECTOR "CHACO" EN EL SUBSISTEMA BIBLIOTECARIO DE LA PROVINCIA. | as enacted, in force 12 February 2025 |
| `ley-4073-j/` | Ley 4073-J: MODIFICA LOS ARTICULOS 42, INC. E) APARTADO 1 Y 45 INCISOS I) Y K) DE LA LEY 2011-J DE SEGURIDAD PUBLICA. | as enacted, in force 18 September 2024 |
| `ley-4071-c/` | Ley 4071-C: MODIFICA EL ARTICULO 3º DE LA LEY 4032-C (CREA COMISIÓN ESPECIAL TÉCNICO PARA ACTUALIZACIÓN Y MODIFICACIÓN DE LA LEY DE HONORARIOS PROFESIONALES DE … | as enacted, in force 18 September 2024 |
| `ley-4070-i/` | Ley 4070-I: INSTITUYE EL DIA DEL CULTIVO HIDROPÓNICO. | as enacted, in force 18 September 2024 |
| `ley-4078-e/` | Ley 4078-E: MODIFICA ARTICULOS 334 Y 343 DE LA LEY 647-E. | as enacted, in force 22 November 2024 |
| `ley-4079-g/` | Ley 4079-G: DIA PROVINCIAL DE LA ACTIVIDAD FISICA. | as enacted, in force 18 September 2024 |
| `ley-4069-a/` | Ley 4069-A: DIA PROVINCIAL CONMEMORATIVO DEL SAMURADIPEN U HOLOCAUSTO GITANO-ROMANI. | as enacted, in force 8 September 2024 |
| `ley-4068-a/` | Ley 4068-A: PROCESO DE ADOPCION DE CANES DE LA POLICIA DEL CHACO. | as enacted, in force 9 October 2024 |
| `ley-4067-a/` | Ley 4067-A: EXPROPIA INMUEBLE EN LA CIUDAD DE BARRANQUERAS. | as enacted, in force 8 September 2024 |
| `ley-4066-a/` | Ley 4066-A: CREACION DE DEFENSORIA OFICIAL CON ASIENTO EN LA PRIMERA CIRCUNSCRIPCION JUDICIAL DE LA CIUDAD DE RESISTENCIA. | as enacted, in force 8 September 2024 |
| `ley-4060-e/` | Ley 4060-E: RATIFICA DECRETO DEL PODER EJECUTIVO 1265/24 REFERIDO AL PROGRAMA DE FORMACIÓN DOCENTE CONTINUA “RED APRENDE 2024-2027”. | as enacted, in force 8 September 2024 |
| `ley-4061-s/` | Ley 4061-S: DECLARA DE INTERÉS PROVINCIAL EL PLAN DE ACCIÓN ANUAL DEL INSTITUTO DEL DEPORTE CHAQUEÑO. | as enacted, in force 18 August 2024 |
| `ley-4062-h/` | Ley 4062-H: PROGRAMAS DE AYUDA PROVINCIAL (PAPRO)  y MUNICIPAL (PAM). | as enacted, in force 8 September 2024 |
| `ley-4064-a/` | Ley 4064-A: CREACION DE DEFENSORIA OFICIAL Nº 6 CON ASIENTO EN LA SEGUNDA CIRCUNSCRIPCION JUDICIAL DE LA CIUDAD DE PRESIDENCIA ROQUE SAENZ PEÑA. | as enacted, in force 8 September 2024 |
| `ley-4065-a/` | Ley 4065-A: CREASE UNA DEFENSORIA OFICIAL EN LA TERCERA CIRCUNSCRIPCION JUDICIAL EN LA CIUDAD DE VILLA ANGELA. | as enacted, in force 8 September 2024 |
| `ley-4046-a/` | Ley 4046-A: RATIFICA DECRETO 717/24. INCREMENTO SALARIAL PARA LA JURISDICCION 21 - POLICIA PROVINCIAL Y 36 - SERVICIO PENITENCIARIO PROVINCIAL. | as enacted, in force 16 August 2024 |
| `ley-4056-g/` | Ley 4056-G: CAMPAÑA DE CONCIENTIZACION Y SENSIBILIZACION SOBRE LOS PELIGROS DE LA "AUTOMEDICACION" EN LA SALUD. | as enacted, in force 18 August 2024 |
| `ley-4055-e/` | Ley 4055-E: ADHESION A LA LEY NACIONAL 27.710 "LENGUA DE SEÑAS ARGENTINAS". | as enacted, in force 18 August 2024 |
| `ley-4054-u/` | Ley 4054-U: DIA DEL LOCUTOR Y LOCUTORA DEL CHACO. | as enacted, in force 18 August 2024 |
| `ley-4052-a/` | Ley 4052-A: RATIFICA DECRETO 730/24 INCREMENTO SALARIAL P-ESCALAFON DE P. LEGISL.-AUT. SUP.-CONTADURIA GRAL DE LA PROV DEL CHACO Y TESORERIA GRAL DE LA PROV DEL… | as enacted, in force 16 August 2024 |
| `ley-4051-a/` | Ley 4051-A: RATIFICA DECRETO 719/24 INCREMENTO SALARIAL EN EL ESCALAFON GENERAL - LEY 196-A. | as enacted, in force 16 August 2024 |
| `ley-4049-a/` | Ley 4049-A: RATIFICA DECRETO 718/24 INCREMENTO SALARIAL EN LOS ESCALAFONES DEL TRIBUNAL ELECTORAL-PODER JUDICIAL-TRIBUNAL DE CUENTAS-CONSEJO DE LA MAGISTRATURA … | as enacted, in force 16 August 2024 |
| `ley-4048-a/` | Ley 4048-A: RATIFICA DECRETO 640/24 INCREMENTO EN EL VALOR INDICE UNO DEL ESCALAFON DOCENTE. | as enacted, in force 16 August 2024 |
| `ley-4047-a/` | Ley 4047-A: RATIFICA DECRETO 339/24 INCREMENTO EN EL AJUSTE POR REVISION LEY 3424-A. | as enacted, in force 16 August 2024 |
| `ley-4059-f/` | Ley 4059-F: RATIFICA DECRETO 171/24 EMERGENCIA ECONOMICA Y FINANCIERA. PRORROGA HASTA EL 31/12/24, LA EMERGENCIA ECONÓMICA Y FINANCIERA DE LA PROVINCIA, DISPUES… | as enacted, in force 28 July 2024 |
| `ley-4058-a/` | Ley 4058-A: ABROGA LA LEY 3335-I INSTITUTO DE AGRICULTURA FAMILIAR Y ECONOMIA POPULAR. | current text only, as of 27 February 2025 |
| `ley-4057-e/` | Ley 4057-E: CREA EL CENTRO DE FORMACION Y CAPACITACION EN ADMINISTRACION PUBLICA DEL CHACO. ABROGA LAS LEYES 2036-A Y 2069-A. | as enacted, in force 16 August 2024 |
| `ley-4053-w/` | Ley 4053-W: CONVOCA A ELECCIONES AUTORIDADES DEL INSTITUTO ABORIGEN CHAQUEÑO. | as enacted, in force 18 August 2024 |
| `ley-4050-a/` | Ley 4050-A: AUTORIZACION AL INSTITUTO DE TIERRAS FISCALES A ADJUDICAR EN VENTA TIERRAS. | as enacted, in force 14 August 2024 |
| `ley-4042-i/` | Ley 4042-I: CREA REGISTRO ESPECIAL DE COMERCIALIZADORES DE ELEMENTOS Y MATERIALES USADOS. | as enacted, in force 11 September 2024 |
| `ley-4043-a/` | Ley 4043-A: EXPROPIA INMUEBLES  EN LA LOCALIDAD DE PUERTO VILELAS - BARRIO EX PLOMO. | as enacted, in force 23 May 2025 |
| `ley-4044-i/` | Ley 4044-I: DIA DEL PRODUCTOR DE ARROZ CHAQUEÑO. | as enacted, in force 28 July 2024 |
| `ley-4045-h/` | Ley 4045-H: MARCO LEGAL PARA LA ASIGNACION DE BENEFICIOS SOCIALES. | as enacted, in force 28 July 2024 |
| `ley-4035-f/` | Ley 4035-F: MODIFICA EL PRESUPUESTO GENERAL DE LA PROVINCIA DEL CHACO PARA EL EJERCICIO 2024. | as enacted, in force 28 July 2024 |
| `ley-4041-h/` | Ley 4041-H: MODIFICA LOS ARTS. 35 Y 136 DE LEY 800-H REGIMEN DE JUBILACIONES, RETIROS Y PENSIONES. | as enacted, in force 19 July 2024 |
| `ley-4040-p/` | Ley 4040-P: MODIFICA EL ART. 62 LEY 471-P. | as enacted, in force 23 June 2024 |
| `ley-4039-a/` | Ley 4039-A: CREA DEFENSORIA OFICIAL PENAL Nª 4 EN LA CIUDAD DE VILLA ANGELA. | as enacted, in force 8 September 2024 |
| `ley-4038-f/` | Ley 4038-F: DEJA SIN EFECTO ACTAS DE INFRACCIONES DE TRANSITO ORIGINADAS POR FOTOMULTAS-CINEMOMETROS EN LA PROVINCIA DEL CHACO. | as enacted, in force 21 June 2024 |
| `ley-4037-k/` | Ley 4037-K: RUTA DEL TRABAJO. | as enacted, in force 19 July 2024 |
| `ley-4036-g/` | Ley 4036-G: MODIFICA ARTICULOS DE LA LEY 1215-G (ANTES LEY 5086), REGIMEN DE FORMACION Y CAPACITACION DE LOS RECURSOS HUMANOS EN SALUD DE LA PROVINCIA DEL CHACO… | as enacted, in force 16 August 2024 |
| `ley-4034-m/` | Ley 4034-M: LEY DE EJERCICIO PROFESIONAL DE LOS GRADUADOS EN CIENCIAS ECONOMICAS Y ORGANICA DEL CONSEJO PROFESIONAL DE CIENCIAS ECONOMICAS DE LA PROVINCIA DEL C… | as enacted, in force 24 July 2024 |
| `ley-4012-a/` | Ley 4012-A: RATIFICA DECRETO 152/24. | as enacted, in force 21 June 2024 |
| `ley-4022-a/` | Ley 4022-A: NUEVOS MONTOS DEL FONDO ESTIMULO. DIRECCION PROVINCIAL DEL TRABAJO. | as enacted, in force 8 September 2024 |
| `ley-4020-a/` | Ley 4020-A: INCREMENTO DE LA BONIFICACION CREADA POR LA LEY 3532-A. BONIFICACION POR MAYORES FUNCIONES Y RESPONSABILIDADES PARA EL MINISTERIO DE PLANIFICACION, … | as enacted, in force 8 September 2024 |
| `ley-4021-a/` | Ley 4021-A: MODIFICACIÓN BASE DE CÁLCULO DE LA BONIFICACIÓN ESPECIAL PARA LA SECRETARÍA DE MUNICIPIOS Y CIUDADES. | as enacted, in force 25 April 2024 |
| `ley-4014-a/` | Ley 4014-A: BONIFICACIÓN ESPECIAL LEY 1846-H. NUEVA BASE DE CÁLCULO. | as enacted, in force 8 September 2024 |
| `ley-4023-a/` | Ley 4023-A: CREA BONIFICACIÓN ESPECIAL. PARA EL PERSONAL DEL MINISTERIO DE PRODUCCIÓN, INDUSTRIA Y EMPLEO. RATIFICA DECRETO 2166/22 | as enacted, in force 8 September 2024 |
| `ley-4019-a/` | Ley 4019-A: BONIFICACION PERMANENCIA EN EL CARGO PARA EL PERSONAL DE LA JURISDICCION 47 - INSTITUTO DEL DEFENSOR DEL PUEBLO. | as enacted, in force 8 September 2024 |
| `ley-4018-a/` | Ley 4018-A: RATIFICA DECRETO 1870/22. BONIFICACION ESPECIAL AL PERSONAL DE ARQUITECTURA HOSPITALARIA LEY 3645-A. | as enacted, in force 8 September 2024 |
| `ley-4017-a/` | Ley 4017-A: MODIFICA VALOR FONDO DE APOYO AL SISTEMA EDUCATIVO. LEY 2633-A. | as enacted, in force 1 September 2024 |
| `ley-4016-a/` | Ley 4016-A: INCREMENTO DEL ADICIONAL POR TAREA ESPECIFICA PARA AGENTES DEL MINISTERIO DE DESARROLLO SOCIAL | as enacted, in force 8 September 2024 |
| `ley-4015-h/` | Ley 4015-H: LEY 505-H INCREMENTOS. | as enacted, in force 23 June 2024 |
| `ley-4009-a/` | Ley 4009-A: RATIFICA DECRETO 154/24. | as enacted, in force 21 June 2024 |
| `ley-4008-a/` | Ley 4008-A: RATIFICA DECRETO 151/24. | as enacted, in force 21 June 2024 |
| `ley-4006-a/` | Ley 4006-A: RATIFICA DECRETO 153/24. | as enacted, in force 21 June 2024 |
| `ley-4031-e/` | Ley 4031-E: MODIFICA LEY 1692-E. | as enacted, in force 8 September 2024 |
| `ley-4030-e/` | Ley 4030-E: PROTECCIÓN Y ESTABILIDAD DEL PERSONAL EN EL CONTEXTO DE IMPLEMENTACIÓN DE LAS LEYES 3895-E Y 3896-E. | as enacted, in force 12 June 2024 |
| `ley-4007-a/` | Ley 4007-A: RATIFICA DECRETO 54/24. | as enacted, in force 21 June 2024 |
| `ley-4010-a/` | Ley 4010-A: RATIFICA DECRETO 222/24. | as enacted, in force 21 June 2024 |
| `ley-4011-a/` | Ley 4011-A: RATIFICA DECRETO 213/24. | as enacted, in force 21 June 2024 |
| `ley-4013-a/` | Ley 4013-A: RATIFICA DECRETO 175/24. | as enacted, in force 21 June 2024 |
| `ley-4024-a/` | Ley 4024-A: RATIFICA DECRETO 2443/23. | as enacted, in force 21 June 2024 |
| `ley-4026-a/` | Ley 4026-A: MODIFICA LA PAUTA SALARIAL INSTITUTO DEL DEFENSOR DEL PUEBLO RATIFICA DECRETO. | as enacted, in force 21 June 2024 |
| `ley-4029-a/` | Ley 4029-A: LEY ORGÁNICA DE LA ESCRIBANÍA GENERAL DE GOBIERNO. | as enacted, in force 27 October 2024 |
| `ley-4028-a/` | Ley 4028-A: MODIFICA LEY 3920-A. | as enacted, in force 12 June 2024 |
| `ley-4032-c/` | Ley 4032-C: CREA COMISIÓN ESPECIAL TÉCNICO PARA ACTUALIZACIÓN Y MODIFICACIÓN DE LA LEY DE HONORARIOS PROFESIONALES DE ABOGADOS Y PROCURADORES. | as enacted, in force 12 June 2024 |
| `ley-4033-j/` | Ley 4033-J: LIMITACIÓN DE TELEFONÍA CELULAR E INTERNET EN LOS ESTABLECIMIENTOS PENITENCIARIOS. | as enacted, in force 12 June 2024 |
| `ley-4005-r/` | Ley 4005-R: ACTUALIZACIÓN DEL ORDENAMIENTO TERRITORIAL DE LOS BOSQUES NATIVOS DE LA PROVINCIA DEL CHACO. | as enacted, in force 19 May 2024 |
| `ley-4004-a/` | Ley 4004-A: RATIFICA DECRETO 315/24. EMERGENCIA SANITARIA DEL SISTEMA PUBLICO PROVINCIAL DE SALUD. | as enacted, in force 19 May 2024 |
| `ley-4003-f/` | Ley 4003-F: MODIFICACIONES A LA LEY 3898-F. BENEFICIOS FISCALES. | as enacted, in force 17 May 2024 |
| `ley-3998-i/` | Ley 3998-I: "EMERGENCIA POR SEQUÍA" | as enacted, in force 12 June 2024 |
| `ley-4002-f/` | Ley 4002-F: REGULARIZACIÓN EXCEPCIONAL DE OBLIGACIONES TRIBUTARIAS. | as enacted, in force 12 June 2024 |
| `ley-4001-a/` | Ley 4001-A: LEYENDA "2024: AÑO DEL CENTENARIO DE LA MASACRE DE NAPALPÍ". | as enacted, in force 21 June 2024 |
| `ley-4000-h/` | Ley 4000-H: MODIFICA LA LEY 1084-H PROGRAMAS DE AYUDA PROVINCIAL (PAPRO) Y MUNICIPAL (PAM). | as enacted, in force 26 May 2024 |
| `ley-3999-m/` | Ley 3999-M: CREA DOS JUZGADOS DE NIÑEZ, ADOLESCENCIA Y FAMILIA. | as enacted, in force 12 June 2024 |
| `ley-3996-f/` | Ley 3996-F: MODIFICA LA LEY 840-F - TASA DE JUSTICIA. | as enacted, in force 12 May 2024 |
| `ley-3997-m/` | Ley 3997-M: RESTABLECER EL PLAZO DE VIGENCIA DE LA LEY 1388-M (ANTES LEY 5525). | as enacted, in force 12 May 2024 |
| `ley-3994-a/` | Ley 3994-A: EXPROPIA INMUEBLES. | as enacted, in force 26 April 2024 |
| `ley-3995-a/` | Ley 3995-A: REINSTAURA LEY 3471-A. | as enacted, in force 26 April 2024 |
| `ley-3993-i/` | Ley 3993-I: CARTAS DE MENÚ ADAPTADAS CON PICTOGRAMAS. | as enacted, in force 26 April 2024 |
| `ley-3992-g/` | Ley 3992-G: DIA PROVINCIAL DEL PACIENTE CON ARTRITIS REUMATOIDEA. | as enacted, in force 26 April 2024 |
| `ley-3991-a/` | Ley 3991-A: DIA PROVINCIAL DEL TRABAJADOR SOCIAL. . | as enacted, in force 26 April 2024 |
| `ley-3989-h/` | Ley 3989-H: MODIFICA LEY 786-H- SISTEMA PREVISIONAL Y SOCIAL PARA PROFESIONALES EN CIENCIAS ECONÓMICAS DE LA PROVINCIA DEL CHACO. | as enacted, in force 3 May 2024 |
| `ley-3990-a/` | Ley 3990-A: DIA DEL EMPLEADO DE LA ADMINISTRACION PROVINCIAL DEL AGUA. | as enacted, in force 29 March 2024 |
| `ley-3988-a/` | Ley 3988-A: DECLARA AL AÑO 2024 COMO “30° ANIVERSARIO DE LA REFORMA DE LA CONSTITUCIÓN NACIONAL Y PROVINCIAL. | as enacted, in force 12 June 2024 |
| `ley-3987-e/` | Ley 3987-E: DECLARA A LA LOCALIDAD DE PUERTO TIROL  “CAPITAL PROVINCIAL DE LA MURGA” | as enacted, in force 12 January 2024 |
| `ley-3986-e/` | Ley 3986-E: FONTANA, CAPITAL PROVINCIAL DEL  CARNAVAL DE ADULTOS MAYORES | as enacted, in force 12 January 2024 |
| `ley-3983-g/` | Ley 3983-G: PROGRAMA PROVINCIAL DE DETECCIÓN TEMPRANA  DE ALTERACIONES POSTURALES EN EDAD ESCOLAR | as enacted, in force 12 January 2024 |
| `ley-3984-g/` | Ley 3984-G: PROGRAMA "MARÍA BERNABITTI" SOBRE CAPACITACIÓN EN PERSPECTIVA DE GÉNERO Y DIVERSIDAD SEXUALES PARA GREMIOS, SINDICATOS ASOCIACIONES DE TRABAJADORES … | as enacted, in force 3 April 2024 |
| `ley-3972-e/` | Ley 3972-E: CAMPAÑA DE CONCIENTIZACIÓN Y PREVENCIÓN DE LA VIOLENCIA POR RAZONES DE`GÉNERO EN ADULTAS MAYORES. | as enacted, in force 5 January 2024 |
| `ley-3974-h/` | Ley 3974-H: BONIFICACION DE EQUIPARACION SALARIAL  PARA VETERANOS DE MALVINAS. | as enacted, in force 5 January 2024 |
| `ley-3969-a/` | Ley 3969-A: LEY DE MINISTERIOS. DEROGA LEY N° 3108-A. | as enacted, in force 12 January 2024 |
| `ley-3975-a/` | Ley 3975-A: EXPROPIA INMUEBLES EN LA CIUDAD DE RESISTENCIA. BARRIO DON SANTIAGO Y MAPIC. | as enacted, in force 5 January 2024 |
| `ley-3976-a/` | Ley 3976-A: EXPROPIA INMUEBLE EN LA CIUDAD DE FONTANA.PROPIETARIOS: ANTONIO, SCALE Y DICON S.R.L.. | as enacted, in force 5 January 2024 |
| `ley-3968-f/` | Ley 3968-F: PRESUPUESTO GENERAL DE LA PROVINCIA DEL CHACO PARA EL EJERCICIO 2024. | as enacted, in force 24 December 2023 |
| `ley-3967-g/` | Ley 3967-G: DÍA PROVINCIAL DE LA CONCIENTIZACIÓN Y PREVENCIÓN DE LOS AHOGAMIENTOS. | as enacted, in force 5 January 2024 |
| `ley-3966-g/` | Ley 3966-G: DÍA PROVINCIAL DE LA DIABETES. | as enacted, in force 5 January 2024 |
| `ley-3965-e/` | Ley 3965-E: CAPACITACIÓN EN ESTABLECIMIENTOS EDUCATIVOS SOBRE SENSIBILIZACIÓN, PREVENCIÓN Y ABORDAJE INTEGRAL DE LOS CONSUMOS PROBLEMÁTICOS. | as enacted, in force 5 January 2024 |
| `ley-3964-g/` | Ley 3964-G: ESPACIOS ACTIVOS- | as enacted, in force 5 January 2024 |
| `ley-3963-g/` | Ley 3963-G: DÍA PROVINCIAL DEL SÍNDROME DE ALFI. | as enacted, in force 5 January 2024 |
| `ley-3962-a/` | Ley 3962-A: BONIFICACIÓN POR INCOMPATIBILIDAD PARA EL PERSONAL DE LA ADMINISTRACIÓN TRIBUTARIA PROVINCIAL. | as enacted, in force 5 January 2024 |
| `ley-3960-a/` | Ley 3960-A: NUEVA BASE DE CÁLCULO PARA LA BONIFICACIÓN ESTABLECIDA EN LA LEY 1846-H DE LA JURISDICCIÓN 14 - INSTITUTO DE TIERRAS FISCALES. | as enacted, in force 5 January 2024 |
| `ley-3959-a/` | Ley 3959-A: BONIFICACIÓN ESPECIAL PARA EL PERSONAL QUE REVISTA Y PRESTA SERVICIOS EN EL REGISTRO DE LA PROPIEDAD INMUEBLE DEPENDIENTE DEL MINISTERIO DE GOBIERNO… | as enacted, in force 5 January 2024 |
| `ley-3958-a/` | Ley 3958-A: SUMA FIJA MENSUAL, REMUNERATIVA Y NO BONIFICABLE PARA EL PERSONAL DE PLANTA PERMANENTE Y ADSCRIPTO QUE PRESTA REAL Y EFECTIVO SERVICIO EN LA JURISDI… | as enacted, in force 29 December 2023 |
| `ley-3957-a/` | Ley 3957-A: SUPLEMENTO POR EXTENSIÓN, DE CARÁCTER REMUNERATIVO Y BONIFICABLE PARA EL PERSONAL DE LA JURISDICCIÓN 29 - MINISTERIO DE EDUCACIÓN, CULTURA, CIENCIA … | as enacted, in force 3 April 2024 |
| `ley-3956-a/` | Ley 3956-A: RATIFICA DECRETO 1770/23. | as enacted, in force 31 December 2023 |
| `ley-3954-a/` | Ley 3954-A: PERSONAL POLICIAL: CONCEPTO BONIFICACIÓN ESPECIAL PARA EL PERSONAL QUE PRESTA EL SERVICIO DE TORRISTA/ANTENISTA. | as enacted, in force 31 December 2023 |
| `ley-3952-a/` | Ley 3952-A: INCREMENTO SALARIAL PARA EL PERSONAL POLICIAL Y SERVICIO PENITENCIARIO PROVINCIAL, COMPRENDIDOS EN EL ESCALAFÓN DE SEGURIDAD. | as enacted, in force 29 December 2023 |
| `ley-3951-a/` | Ley 3951-A: BONIF. RIESGO VIDA PERS. DESEMPEÑE TAREAS INSPECCIÓN, RELEV, DCCIÓN Y EJECUCIÓN DE OBRAS CHOFER INSP, RELEV, DCCIÓN DE OBRAS DEP. DE LA JURISDICCIÓN… | as enacted, in force 29 December 2023 |
| `ley-3950-a/` | Ley 3950-A: RATIFICA DECRETO 2562/23. | as enacted, in force 29 December 2023 |
| `ley-3949-a/` | Ley 3949-A: MODIFICA LOS ARTÍCULOS 11 Y 17 DE LA LEY 2017-H Y RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 2533-23 | as enacted, in force 15 December 2023 |
| `ley-3935-a/` | Ley 3935-A: CARGOS TEMPORARIOS PARA LA JURISDICCIÓN 17 - TRIBUNAL ELECTORAL. | as enacted, in force 27 December 2023 |
| `ley-3946-a/` | Ley 3946-A: RATIFICA LOS DECRETOS 28/23, 1453/23, 2118/23 Y 2244/23. | as enacted, in force 22 November 2023 |
| `ley-3943-w/` | Ley 3943-W: CREA LA MESA INTERINSTITUCIONAL Y MULTICULTURAL DENOMINADA MESA ESTADO Y COMUNIDADES INDÍGENAS - MIRAFLORES. | as enacted, in force 7 January 2024 |
| `ley-3942-a/` | Ley 3942-A: TRANSFIERE INMUEBLE. | as enacted, in force 17 November 2023 |
| `ley-3948-h/` | Ley 3948-H: MODIFICA LEY 3792-H. | as enacted, in force 27 December 2023 |
| `ley-3947-a/` | Ley 3947-A: RATIFICA DECRETO 2656/23. | as enacted, in force 22 November 2023 |
| `ley-3944-a/` | Ley 3944-A: RECATEGORIZACIÓN DE INSPECTORES NOTARIALES. | as enacted, in force 20 December 2023 |
| `ley-3945-e/` | Ley 3945-E: 12 DE DICIEMBRE DÍA DE LA CUMBIA CHAQUEÑA. | as enacted, in force 27 December 2023 |
| `ley-3940-a/` | Ley 3940-A: ESTABLECE UNA CUOTA MENSUAL EN CONCEPTO DE PARTICIPACIÓN MUNICIPAL PARA EL MUNICIPIO DE COLONIA ABORÍGEN Y MODIFICA ARTÍCULO 2º DE LA LEY 738-P. | as enacted, in force 17 November 2023 |
| `ley-3939-a/` | Ley 3939-A: EXIMICIÓN DE PAGO POR CONSUMOS DE ENERGÍA ELÉCTRICA Y AGUA POTABLE PARA TODAS LAS FILIALES DE LA ASOCIACIÓN DE LUCHA CONTRA EL CÁNCER (A.L.C.E.C). | as enacted, in force 27 December 2023 |
| `ley-3937-a/` | Ley 3937-A: ASIGNA CON CARÁCTER DE LETRADO AL JUZGADO DE PAZ Y FALTAS DE LA LOCALIDAD DE SANTA SYLVINA. | as enacted, in force 6 December 2023 |
| `ley-3936-a/` | Ley 3936-A: MODIFICACIONES A LA LEY 2415-A . | as enacted, in force 27 December 2023 |
| `ley-3934-a/` | Ley 3934-A: ADICIONAL  REMUNERATIVO Y AJUSTE POR REVISIÓN PARA EL PODER JUDICIAL - CONSEJO DE LA MAGISTRATURA Y JURADO DE ENJUICIAMIENTO - TRIBUNAL ELECTORAL. | as enacted, in force 27 December 2023 |
| `ley-3933-a/` | Ley 3933-A: INCREMENTO EN LAS MULTAS PREVISTAS EN LA LEY 2079-R- INFRACCIONES DE BOSQUE NATIVOS. | as enacted, in force 22 December 2023 |
| `ley-3931-a/` | Ley 3931-A: SUMA FIJA PARA EL PERSONAL DE UNIDADES DEL MINISTERIO DE DESARROLLO SOCIAL. | as enacted, in force 22 December 2023 |
| `ley-3930-a/` | Ley 3930-A: INCREMENTO DE VARIOS ESCALAFONES. | as enacted, in force 15 December 2023 |
| `ley-3929-a/` | Ley 3929-A: INCREMENTOS SALARIALES PARA EL PODER LEGISLATIVO, AUTORIDADES SUPERIORES, CONTADURÍA Y TESORERÍA GRAL DE LA PCIA, DCIÓN DE AERONÁUTICA, ADM. PORTUAR… | as enacted, in force 15 December 2023 |
| `ley-3932-a/` | Ley 3932-A: INCREMENTO BONIFICACIÓN POR MAYORES FUNCIONES Y RESPONSABILIDADES PARA  MTRIO DE PLANIFICACIÓN, ECONOMÍA E INFRAEST - CONTADURÍA Y TESORERÍA GRAL DE… | as enacted, in force 22 December 2023 |
| `ley-3941-e/` | Ley 3941-E: RATIFICA DECRETOS DEL PODER EJECUTIVO 2027/2009 Y SU MODIFICATORIO 1797/2020. | as enacted, in force 27 December 2023 |
| `ley-3928-j/` | Ley 3928-J: INSTALA CÁMARA DE SEGURIDAD EN EL TRANSPORTE PÚBLICO DE PASAJEROS. | as enacted, in force 17 November 2023 |
| `ley-3926-a/` | Ley 3926-A: ASIGNA CON CARÁCTER DE LETRADO AL JUZGADO DE PAZ Y FALTAS DE LA CIUDAD DE FONTANA. | as enacted, in force 22 November 2023 |
| `ley-3925-e/` | Ley 3925-E: RATIFICA DECRETO DEL PODER EJECUTIVO 1336/20. | as enacted, in force 22 November 2023 |
| `ley-3915-a/` | Ley 3915-A: BONIFICACIÓN DE EQUIPARACIÓN SALARIAL PARA EMPLEADOS Y RETIRADOS BOCEP y EX BANCO DEL CHACO SEM. | as enacted, in force 15 December 2023 |
| `ley-3916-a/` | Ley 3916-A: INCREMENTO SALARIAL EN EL TRIBUNAL DE CUENTAS, PODER JUDICIAL, TRIBUNAL ELECTORAL, CONSEJO DE LA MAGISTRATURA  JURADO DE ENJUICIAMIENTO Y FISCALÍA D… | as enacted, in force 15 December 2023 |
| `ley-3917-a/` | Ley 3917-A: VALOR ÍNDICE UNO DEL ESCALAFÓN DOCENTE - LEY 647-E. | as enacted, in force 15 December 2023 |
| `ley-3918-a/` | Ley 3918-A: RATIFICA DECRETO 2348/23. | as enacted, in force 15 December 2023 |
| `ley-3919-a/` | Ley 3919-A: INCREMENTOS EN LAS ESCALAS SALARIALES VIGENTES DEL ESCALAFÓN GENERAL - LEY 196-A. | as enacted, in force 15 December 2023 |
| `ley-3921-a/` | Ley 3921-A: CREA CARGOS EN EL MINISTERIO PÚBLICO DE LA DEFENSA DEL PODER JUDICIAL. | as enacted, in force 15 December 2023 |
| `ley-3922-g/` | Ley 3922-G: EXÁMEN PSICODIAGNÓSTICO A TODA PERSONA QUE DESEMPEÑE CARGO, FUNCIÓN O ACTIVIDAD EN LA QUE SE ENCUENTRE EN CONTACTO CON NIÑOS, NIÑAS Y ADOLESCENTES. | as enacted, in force 1 December 2023 |
| `ley-3923-s/` | Ley 3923-S: DECLARA A LA CIUDAD DE BARRANQUERAS COMO CAPITAL PROVINCIAL DE LOS DEPORTES NÁUTICOS. | as enacted, in force 15 December 2023 |
| `ley-3914-a/` | Ley 3914-A: INCREMENTO EN LA BONIFICACIÓN POR MAYORES FUNCIONES Y RESPONSABILIDADES PARA EL MINISTERIO DE PLANIFICACIÓN, ECONOMÍA  E INFRAESTRUCTURA - CONTADURÍ… | as enacted, in force 15 December 2023 |
| `ley-3920-a/` | Ley 3920-A: DEROGA INCISO A) DEL ARTÍCULO 4º DE LA LEY 3784-A. | as enacted, in force 22 November 2023 |
| `ley-3908-a/` | Ley 3908-A: INCREMENTO SALARIAL EN EL TRIBUNAL DE CUENTAS, PODER JUDICIAL, TRIBUNAL ELECTORAL, CONSEJO DE LA MAGISTRATURA Y JURADO DE ENJUICIAMIENTO. | as enacted, in force 17 November 2023 |
| `ley-3902-a/` | Ley 3902-A: BONIFICACIÓN EQUIPARACIÓN SALARIAL. | as enacted, in force 29 December 2023 |
| `ley-3911-a/` | Ley 3911-A: RÉGIMEN ESPECIAL DE LICENCIA POR PATERNIDAD PARA LOS AGENTES NO COMPRENDIDOS EN LA LEY 645-A. | as enacted, in force 5 January 2024 |
| `ley-3913-d/` | Ley 3913-D: LEY DE FOMENTO DEL EMPRENDEDURISMO. | as enacted, in force 7 January 2024 |
| `ley-3901-a/` | Ley 3901-A: BONIFICACIÓN EQUIPARACIÓN SALARIAL PARA EL ESCALAFÓN GENERAL LEY 196-A. | as enacted, in force 29 December 2023 |
| `ley-3905-a/` | Ley 3905-A: INCREMENTA EL PORCENTAJE DEL ADICIONAL REMUNERATIVO ESPECIAL. | as enacted, in force 9 June 2024 |
| `ley-3910-a/` | Ley 3910-A: INCREMENTO SALARIALES P. LEGISLATIVO, AUTORIDADES SUPERIORES, CONTADURÍA Y TESORERÍA GENERAL DE LA  PROVINCIA, DCCIÓN DE AERONÁUTICA, ADM.PORTUARIA-… | as enacted, in force 17 November 2023 |
| `ley-3909-a/` | Ley 3909-A: INCREMENTO EN LA BONIFICACIÓN ESPECIAL PARA EL PERSONAL DEL MINISTERIO DE SEGURIDAD Y JUSTICIA, POLICÍA PROVINCIAL, SERVICIO PENITENCIARIO Y DE READ… | as enacted, in force 17 November 2023 |
| `ley-3907-a/` | Ley 3907-A: INCREMENTO DEL REFRIGERIO PARA LA POLICÍA PROVINCIAL Y SERVICIO PENITENCIARIO PROVINCIAL.. | as enacted, in force 17 November 2023 |
| `ley-3906-a/` | Ley 3906-A: PAUTA SALARIAL INSTITUTO DEL DEFENSOR DEL PUEBLO RATIFICA DECRETO 2370/23. | as enacted, in force 15 November 2023 |
| `ley-3904-a/` | Ley 3904-A: VALOR ÍNDICE UNO DEL ESCALAFÓN DOCENTE LEY 647-E. | as enacted, in force 17 November 2023 |
| `ley-3903-a/` | Ley 3903-A: MODIFICA TRAMOS DE LA BONIFICACIÓN EQUIPARACIÓN SALARIAL PARA EL ESCALAFÓN GENERAL LEY 196-A. . | as enacted, in force 17 November 2023 |
| `ley-3897-e/` | Ley 3897-E: PROGRAMA DE COOPERATIVISMO Y MUTUALISMO ESCOLAR. | as enacted, in force 9 June 2024 |
| `ley-3900-k/` | Ley 3900-K: CONSTRUCCIÓN  DE DOS MÁSTILES PARA EL IZAMIENTO DE LAS BANDERAS ARGENTINA Y DEL CHACO. | as enacted, in force 29 October 2023 |
| `ley-3899-e/` | Ley 3899-E: PATRIMONIO CULTURAL Y ARTÍSTICO DE LA PROVINCIA A LOS SABERES ARTESANALES Y A LAS ARTESANÍAS INDÍGENAS. | as enacted, in force 17 November 2023 |
| `ley-3898-f/` | Ley 3898-F: RÉGIMEN DE REGULARIZACIÓN EXCEPCIONAL DE OBLIGACIONES TRIBUTARIAS. | as enacted, in force 17 November 2023 |
| `ley-3891-i/` | Ley 3891-I: RÉGIMEN DE PROMOCIÓN AUDIOVISUAL. | as enacted, in force 20 October 2023 |
| `ley-3896-e/` | Ley 3896-E: PLAN DE ESTABILIDAD Y GARANTÍAS LABORALES PARA DOCENTES DEL NIVEL SUPERIOR. | as enacted, in force 27 October 2023 |
| `ley-3895-e/` | Ley 3895-E: PLAN DE ESTABILIDAD Y GARANTÍAS LABORALES PARA DOCENTES DE LOS NIVELES INICIAL, PRIMARIO Y SECUNDARIO. Y DEROGA ARTS 4º,  5º, 6º, 7º Y 8º DE LA LEY … | as enacted, in force 27 October 2023 |
| `ley-3894-e/` | Ley 3894-E: GUÍA DE ORIENTACIONES Y CRITERIOS DE INTERVENCIÓN ANTE SITUACIONES DE CONSUMO DE SUSTANCIAS EN ÁMBITOS ESCOLARES. | as enacted, in force 20 October 2023 |
| `ley-3893-g/` | Ley 3893-G: DÍA PROVINCIAL DE LA CONCIENTIZACIÓN SOBRE LA TARTAMUDEZ. | as enacted, in force 27 October 2023 |
| `ley-3892-i/` | Ley 3892-I: POLO TECNOLÓGICO TERMAL TECH. | as enacted, in force 27 October 2023 |
| `ley-3890-b/` | Ley 3890-B: COMPENDIO TEMÁTICO DE LA MEMORIA, LA VERDAD Y LA JUSTICIA. | as enacted, in force 27 October 2023 |
| `ley-3886-i/` | Ley 3886-I: CREA EL PROGRAMA PROVINCIAL PARA LA PROTECCIÓN DE LAS ABEJAS. | as enacted, in force 27 September 2023 |
| `ley-3889-a/` | Ley 3889-A: RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 2035/21 - LEY 2548-A IPRODICH BONIFICACIÓN POR FUNCIONES ESPECIALES - NUEVA BASE DE CÁLCULO. | as enacted, in force 27 September 2023 |
| `ley-3882-c/` | Ley 3882-C: ADHESIÓN A LA LEY NACIONAL 27.709 | as enacted, in force 27 September 2023 |
| `ley-3888-a/` | Ley 3888-A: NUEVA BASE DE CÁLCULO BONIFICACIÓN ESPECIAL LEY 1967-A-(ANTES LEYES 6865 - 7665). | as enacted, in force 27 October 2023 |
| `ley-3879-a/` | Ley 3879-A: RATIFICA EL  DECRETO DEL PODER EJECUTIVO PROVINCIAL 1065/23 | as enacted, in force 27 September 2023 |
| `ley-3885-d/` | Ley 3885-D: CARRITOS Y CANASTOS ADAPTADOS PARA EL USO DE PERSONAS CON MOVILIDAD REDUCIDA EN SUPERMERCADOS E HIPERMERCADOS. | as enacted, in force 27 September 2023 |
| `ley-3881-a/` | Ley 3881-A: REINSTAURA LEY 2265-A-(ANTES LEY 7511). | as enacted, in force 27 September 2023 |
| `ley-3877-g/` | Ley 3877-G: SERVICIO DE ATENCIÓN INTEGRAL EN SALUD A LOS VETERANOS DE GUERRA DE MALVINAS. | as enacted, in force 1 September 2023 |
| `ley-3874-a/` | Ley 3874-A: BONIFICACIÓN POR RESPONSABILIDAD FUNCIONAL. | as enacted, in force 8 September 2023 |
| `ley-3872-a/` | Ley 3872-A: FONDO FORTALECIMIENTO DE GESTIÓN INSTITUCIONAL PARA EL PERSONAL DEL MINISTERIO DE GOBIERNO Y TRABAJO. | as enacted, in force 1 September 2023 |
| `ley-3873-a/` | Ley 3873-A: BONIFICACIÓN PARA EL PERSONAL DE LA JURISDICCIÓN 23: MINISTERIO DE PLANIFICACIÓN, ECONOMÍA E INFRAESTRUCTURA. | as enacted, in force 1 September 2023 |
| `ley-3878-a/` | Ley 3878-A: CREA SUPLEMENTO REMUNERATIVO Y NO BONIFICABLE PARA SUPERVISORES DOCENTES. | as enacted, in force 1 September 2023 |
| `ley-3876-a/` | Ley 3876-A: BONIFICACIÓN ESPECIAL PARA DIRECCIÓN GENERAL DEL REGISTRO CIVIL Y CAPACIDAD DE LAS PERSONAS. | as enacted, in force 1 September 2023 |
| `ley-3875-a/` | Ley 3875-A: BONIFICACIÓN POR RIESGO. | as enacted, in force 1 September 2023 |
| `ley-3871-c/` | Ley 3871-C: CREA PLAN PROVINCIAL DE DIFUSION Y CAPACITACION. | as enacted, in force 11 August 2023 |
| `ley-3869-p/` | Ley 3869-P: ELEVA A PRIMERA CATEGORIA A LA MUNICIPALIDAD DE TRES ISLETAS. | as enacted, in force 11 August 2023 |
| `ley-3860-a/` | Ley 3860-A: LEY 1973-A. INCORPORACION DE BONIFICACIONES | as enacted, in force 18 August 2023 |
| `ley-3859-a/` | Ley 3859-A: RATIFICA DECRETO 2187/22-CONCEPTO AJUSTE POR REVISION EN EL PODER JUDICIAL. | as enacted, in force 18 August 2023 |
| `ley-3858-a/` | Ley 3858-A: INCREMENTOS REMUNERACIONES DOCENTE. | as enacted, in force 18 August 2023 |
| `ley-3857-a/` | Ley 3857-A: INCREMENTOS SALARIALES DE VARIOS ESCALAFONES. | as enacted, in force 13 August 2023 |
| `ley-3856-g/` | Ley 3856-G: DÍA PROVINCIAL DE LAS PERSONAS CON TALLA BAJA. | as enacted, in force 6 August 2023 |
| `ley-3855-e/` | Ley 3855-E: CAPACITACIÓN PARA PERSONAL DOCENTE Y ALUMNOS SOBRE TÉCNICAS DE PRIMEROS AUXILIOS, REANIMACIÓN CARDIOPULMONAR Y DESOBSTRUCCIÓN DE LAS VÍAS AÉREAS. | as enacted, in force 16 August 2023 |
| `ley-3853-e/` | Ley 3853-E: INSTITUYESE COMO DÍA DE LA LUCHA CONTRA EL ACOSO ESCOLAR O BULLYNG EL 2 DE MAYO DE CADA AÑO. | as enacted, in force 9 August 2023 |
| `ley-3852-g/` | Ley 3852-G: DÍA PROVINCIAL SOBRE LA CONCIENTIZACIÓN DE LA FIBROMIALGIA. | as enacted, in force 6 August 2023 |
| `ley-3851-g/` | Ley 3851-G: EXHIBICIÓN DE CARTELERÍA SOBRE LA "MANIOBRA DE HEIMLICH". | as enacted, in force 6 August 2023 |
| `ley-3849-g/` | Ley 3849-G: DÍA PROVINCIAL DEL SÍNDROME DE GOULD. | as enacted, in force 6 August 2023 |
| `ley-3848-a/` | Ley 3848-A: VALOR DEL JORNAL DIARIO EN LA ADMINISTRACIÓN PÚBLICA PROVINCIAL DESDE SEPTIEMBRE A DICIEMBRE DEL AÑO 2022. | as enacted, in force 2 August 2023 |
| `ley-3847-a/` | Ley 3847-A: SALUD PÚBLICA - NIVEL CENTRAL SUMA NO REMUNERATIVA Y NO BONIFICABLE PARA DIRECTOR Y/O JEFE DE DEPARTAMENTO CON BONIFICACIÓN POR DEDICACIÓN EXCLUSIVA… | as enacted, in force 2 August 2023 |
| `ley-3842-i/` | Ley 3842-I: ADHESIÓN A LA LEY NACIONAL 27.521 - "SISTEMA ÚNICO NORMALIZADO DE IDENTIFICACIÓN DE TALLES DE INDUMENTARIA" | as enacted, in force 2 August 2023 |
| `ley-3841-i/` | Ley 3841-I: PORTAL WEB MUJERES RURALES. | as enacted, in force 2 August 2023 |
| `ley-3840-e/` | Ley 3840-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL EDIFICIO EDUCATIVO DE LA VERDE. | as enacted, in force 2 August 2023 |
| `ley-3837-v/` | Ley 3837-V: CREA LA FIESTA PROVINCIAL DE COMIDAS TÍPICAS LOCALES. | as enacted, in force 9 July 2023 |
| `ley-3836-a/` | Ley 3836-A: EXIMICIÓN DE PAGO POR CONSUMOS DE ENERGÍA ELÉCTRICA Y AGUA POTABLE A LA PEÑA NATIVA MARTÍN FIERRO, BIBLIOTECA POPULAR Y MUSEO REGIONAL. | as enacted, in force 7 July 2023 |
| `ley-3835-g/` | Ley 3835-G: INCORPORA CLAÚSULA TRANSITORIA A LA LEY 3180-G. | as enacted, in force 13 August 2023 |
| `ley-3833-h/` | Ley 3833-H: INCREMENTOS EN LA ESCALA SALARIAL DE LA LEY 2017-H. | as enacted, in force 25 June 2023 |
| `ley-3832-e/` | Ley 3832-E: 23 DE SEPTIEMBRE OBLIGATORIEDAD DE JORNADAS ALUSIVAS A LA LEY NACIONAL 13.010.- | as enacted, in force 25 June 2023 |
| `ley-3831-v/` | Ley 3831-V: RUTA TURÍSTICA GASTRONÓMICA DEL PACU ARROCERO. | as enacted, in force 25 June 2023 |
| `ley-3830-a/` | Ley 3830-A: CREA PARQUE INDUSTRIAL EN LA LOCALIDAD DE COLONIA ELISA. | as enacted, in force 5 July 2023 |
| `ley-3829-p/` | Ley 3829-P: DÍA DEL DIRIGENTE VECINAL. | as enacted, in force 14 June 2023 |
| `ley-3828-e/` | Ley 3828-E: CONCURSO ABIERTO DE POESÍA CHAQUEÑA "ALEDO LUIS MELONI". | as enacted, in force 9 June 2023 |
| `ley-3826-e/` | Ley 3826-E: CREACIÓN DE LOS ESPACIOS INTERCULTURALES INDÍGENAS COLABORATIVOS CHAQUEÑOS. | as enacted, in force 14 June 2023 |
| `ley-3825-a/` | Ley 3825-A: CREA COLEGIO DE PROFESIONALES DE EDUCACIÓN FÍSICA. | as enacted, in force 5 July 2023 |
| `ley-3824-a/` | Ley 3824-A: CREA FISCALÍA DE INVESTIGACIONES EN LO PENAL EN LA TERCERA CIRCUNSCRIPCIÓN DEL PODER JUDICIAL EN VILLA ÁNGELA. | as enacted, in force 14 June 2023 |
| `ley-3822-a/` | Ley 3822-A: MARCO REGULATORIO DEL EJERCICIO PROFESIONAL DE LA PSICOPEDAGOGÍA. | as enacted, in force 25 June 2023 |
| `ley-3821-e/` | Ley 3821-E: PROMESA DE COMPROMISO AMBIENTAL. | as enacted, in force 14 June 2023 |
| `ley-3820-a/` | Ley 3820-A: RATIFICA DECRETO 675-23- INCREMENTO SALARIAL- INSTITUTO DEL DEFENSOR DEL PUEBLO-. | as enacted, in force 9 June 2023 |
| `ley-3819-e/` | Ley 3819-E: ABRIL: MES DE HOMENAJE A LOS EX-COMBATIENTES DE LA GUERRA DE MALVINAS. | as enacted, in force 9 June 2023 |
| `ley-3818-a/` | Ley 3818-A: RATIFICA DECRETO 658/23 - INCREMENTO CONCEPTO "AJUSTE POR REVISIÓN" PODER JUDICIAL. | as enacted, in force 9 June 2023 |
| `ley-3817-g/` | Ley 3817-G: DÍA Y SEMANA PROVINCIAL DE LA PREVENCIÓN DE CONSUMOS PROBLEMÁTICOS Y ADICCIONES. | as enacted, in force 9 June 2023 |
| `ley-3815-r/` | Ley 3815-R: CREA EL PROGRAMA DE "VOLUNTARIADO AMBIENTAL" | as enacted, in force 14 June 2023 |
| `ley-3813-e/` | Ley 3813-E: DÍA PROVINCIAL DE LA CONCIENCIA AMBIENTAL. | as enacted, in force 14 June 2023 |
| `ley-3778-e/` | Ley 3778-E: DÍA PROVINCIAL DE LAS MADRES DE MALVINAS. | as enacted, in force 30 April 2023 |
| `ley-3774-k/` | Ley 3774-K: DEROGA LEY 102-K (ANTES LEY 597) - CONTRIBUCIÓN DE MEJORAS SOBRE LA PROPIEDAD RURAL BENEFICIADA POR LA TRAZA DE CAMINOS E INCISO C )DEL ARTICULO 24 … | as enacted, in force 30 April 2023 |
| `ley-3771-g/` | Ley 3771-G: "MES DE LA CONCIENTIZACIÓN DEL SÍNDROME DE WILLIAMS". | as enacted, in force 30 April 2023 |
| `ley-3769-a/` | Ley 3769-A: PRORRÓGA LEY 2620-A. | as enacted, in force 30 April 2023 |
| `ley-3777-a/` | Ley 3777-A: RATIFICA DECRETO 137/23. MODIFICA ART. 1, INCORPORA INCISO LXXII -COLONIA ABORIGEN. LEY 43-P | as enacted, in force 23 April 2023 |
| `ley-3767-h/` | Ley 3767-H: RATIFICA DECRETO 338/23 - ASIGNACIONES FAMILIARES PARA LA ADMINISTRACIÓN PÚBLICA. | as enacted, in force 28 April 2023 |
| `ley-3766-h/` | Ley 3766-H: RATIFICA DECRETO 337/23 - NUEVO MONTO PARA LAS ASIGNACIONES FAMILIAR POR INICIACIÓN DEL CICLO LECTIVO (LEY 505-H). | as enacted, in force 30 April 2023 |
| `ley-3765-a/` | Ley 3765-A: RATIFICA DECRETO 400/23 - BONIFICACIÓN POR SERVICIOS COMUNICACIONALES. | as enacted, in force 30 April 2023 |
| `ley-3764-e/` | Ley 3764-E: DECLARA MONUMENTO Y PATRIMONIO HISTÓRICO, SOCIAL Y CULTURAL AL EDIFICIO DE LA ESCUELA Nº 562 DE LA LOCALIDAD DE MISIÓN NUEVA POMPEYA. | as enacted, in force 23 April 2023 |
| `ley-3763-g/` | Ley 3763-G: SEMANA PROVINCIAL DE CONCIENTIZACIÓN SOBRE LA MANIOBRA DE HEIMLICH. | as enacted, in force 23 April 2023 |
| `ley-3759-h/` | Ley 3759-H: NUEVO VALOR DEL BENEFICIO PARA EX-COMBATIENTES, CAPÍTULO I DE LA LEY 2017.H - DECRETO 317/23. ABROGA LEY N° 3660-H. | as enacted, in force 21 April 2023 |
| `ley-3758-a/` | Ley 3758-A: RATIFICA DECRETO 2485/22. | as enacted, in force 21 April 2023 |
| `ley-3757-a/` | Ley 3757-A: RATIFICA DECRETO 2264/22 - MODIFICA BONIFICACIONES ESPECIALES PARA INSTITUTO DE CULTURA, INSTITUTO DE TURISMO E INSTITUTO DEL DEPORTE. | as enacted, in force 14 April 2023 |
| `ley-3756-a/` | Ley 3756-A: RATIFICA DECRETO 2406/22 - MODIFICACIÓN BASE DE CÁLCULO BONIFICACIÓN PARA EL PERSONAL DE LA JURISDICCIÓN 46-SECRETARÍA DE DERECHOS HUMANOS Y GÉNEROS… | as enacted, in force 14 April 2023 |
| `ley-3755-a/` | Ley 3755-A: RATIFICA DECRETO 2481/22 - INCREMENTOS SALARIALES EN EL ESCALAFÓN GENERAL - LEY 196-A. | as enacted, in force 14 April 2023 |
| `ley-3754-a/` | Ley 3754-A: RATIFICA DECRETO 2165/22 - CONCEPTO REMUNERATIVO Y NO BONIFICABLE "AJUSTE POR REVISIÓN". | as enacted, in force 14 April 2023 |
| `ley-3753-a/` | Ley 3753-A: RATIFICA DECRETO 2263/22. | as enacted, in force 21 April 2023 |
| `ley-3752-r/` | Ley 3752-R: PROGRAMA CONECTIVIDAD VIAL Y AMBIENTAL. | as enacted, in force 21 April 2023 |
| `ley-3751-g/` | Ley 3751-G: DÍA PROVINCIAL DEL RIÑON. | as enacted, in force 21 April 2023 |
| `ley-3750-a/` | Ley 3750-A: NOMENCLATURA URBANA CON VISIÓN DE PERSPECTIVA DE GÉNERO. | as enacted, in force 21 April 2023 |
| `ley-3748-e/` | Ley 3748-E: CREA EL SECTOR ESPECÍFICO GÉNERO Y DIVERSIDAD EN LAS BIBLIOTECAS. | as enacted, in force 30 December 2022 |
| `ley-3747-e/` | Ley 3747-E: DECLARA PATRIMONIO HISTÓRICO CULTURAL LA PARROQUIA SAN JOSÉ DE PUERTO TIROL. | as enacted, in force 28 December 2022 |
| `ley-3708-a/` | Ley 3708-A: PERSONAL DOCENTE INCREMENTO DEL VALOR ÍNDICE UNO (1) DESDE JULIO DEL AÑO 2022. | as enacted, in force 6 November 2022 |
| `ley-3742-b/` | Ley 3742-B: DÍA DEL TESTIGO POR DELITOS DE LESA HUMANIDAD. | as enacted, in force 30 December 2022 |
| `ley-3743-e/` | Ley 3743-E: LEY DE EDUCACIÓN EMOCIONAL. | as enacted, in force 30 December 2022 |
| `ley-3740-i/` | Ley 3740-I: ADHESIÓN A LA LEY NACIONAL 27454-CREA PLAN NACIONAL DE REDUCCIÓN DE PÉRDIDAS Y DESPERDICIOS DE ALIMENTOS. | as enacted, in force 25 December 2022 |
| `ley-3739-a/` | Ley 3739-A: PERSONAL DE LA ESCUELA DE GOBIERNO DE LA PROVINCIA DEL CHACO, NOMBRAMIENTO Y NORMAS RELACIONADAS. | as enacted, in force 25 December 2022 |
| `ley-3737-e/` | Ley 3737-E: LEY DE PRÁCTICAS ACCESIBLES EN FESTIVALES Y EVENTOS CULTURALES. | as enacted, in force 28 December 2022 |
| `ley-3732-r/` | Ley 3732-R: PROGRAMA MAS ÁRBOLES PARA EL CHACO. | as enacted, in force 25 December 2022 |
| `ley-3734-e/` | Ley 3734-E: MES PROVINCIAL DE LA BIBLIA. | as enacted, in force 25 December 2022 |
| `ley-3733-a/` | Ley 3733-A: ASIGNA CARÁCTER DE LETRADO AL JUZGADO DE PAZ Y FALTAS DE LA LEONESA. | as enacted, in force 8 January 2023 |
| `ley-3736-c/` | Ley 3736-C: ADHESIÓN A LA LEY NACIONAL Nº 27576 (MODIFICACIÓN), POR LA CUAL INCORPORA LOS INCISOS T), U) Y V) AL ARTÍCULO 44  DE LA LEY 26061 - PROTECCIÓN INTEG… | as enacted, in force 25 December 2022 |
| `ley-3731-a/` | Ley 3731-A: TRANSFIERE INMUEBLES. | as enacted, in force 7 December 2022 |
| `ley-3730-a/` | Ley 3730-A: REINSTAURA LEY 1040-A (ANTES LEY 4674) | as enacted, in force 23 December 2022 |
| `ley-3729-a/` | Ley 3729-A: REINSTAURA LEY 2476-A (ANTES LEY 7834). | as enacted, in force 23 December 2022 |
| `ley-3728-a/` | Ley 3728-A: REINSTAURA LEY 2867-A. | as enacted, in force 23 December 2022 |
| `ley-3727-a/` | Ley 3727-A: DECRETO 2066/22, MODIFICA LEY 3547-A - INCREMENTA EL PORCENTAJE DEL CONCEPTO ADICIONAL REMUNERATIVO ESPECIAL. | as enacted, in force 20 November 2022 |
| `ley-3726-e/` | Ley 3726-E: TURISMO ESTUDIANTIL AMBIENTAL. | as enacted, in force 23 December 2022 |
| `ley-3725-l/` | Ley 3725-L: ADHESIÓN AL DECRETO NACIONAL 551/2022 - PROGRAMA "PUENTE AL EMPLEO". | as enacted, in force 23 December 2022 |
| `ley-3724-l/` | Ley 3724-L: ADHESIÓN A LA LEY NACIONAL 26.832 - DÍA DEL PERIODISTA DE EXTERIORES DE RADIO Y TELEVISIÓN -. | as enacted, in force 7 December 2022 |
| `ley-3723-g/` | Ley 3723-G: IMPONE EL NOMBRE DE "IRMA GAMARRA" AL NUEVO EDIFICIO DEL CENTRO DE ATENCIÓN PRIMARIA DE SALUD - PARAJE LA MATANZA DE LA CIUDAD DE QUITILIPI- PCIA. D… | as enacted, in force 16 November 2022 |
| `ley-3722-a/` | Ley 3722-A: REINSTAURA LA LEY 2611-A (ANTES LEY 8006) | as enacted, in force 20 November 2022 |
| `ley-3721-a/` | Ley 3721-A: REINSTAURA LA LEY 1919-A (ANTES LEY 6773) | as enacted, in force 20 November 2022 |
| `ley-3719-g/` | Ley 3719-G: DÍA PROVINCIAL DEL SÍNDROME DE DRAVET. | as enacted, in force 16 November 2022 |
| `ley-3716-p/` | Ley 3716-P: ELÉVASE A SEGUNDA CATEGORÍA AL MUNICIPIO DE COLONIA ELISA. | as enacted, in force 18 November 2022 |
| `ley-3715-a/` | Ley 3715-A: REINSTAURA LA LEY 2110-A (ANTES LEY 7212). | as enacted, in force 18 November 2022 |
| `ley-3707-a/` | Ley 3707-A: RATIFICA DECRETO 1911/22. | as enacted, in force 9 November 2022 |
| `ley-3703-g/` | Ley 3703-G: DÍA PROVINCIAL DEL PUERPERIO. | as enacted, in force 6 November 2022 |
| `ley-3704-s/` | Ley 3704-S: ADHESIÓN A LA LEY NACIONAL 27596 - DÍA DE LAS FUTBOLISTAS ARGENTINAS. | as enacted, in force 6 November 2022 |
| `ley-3705-e/` | Ley 3705-E: DÍA DEL SUPERVISOR. | as enacted, in force 6 November 2022 |
| `ley-3706-a/` | Ley 3706-A: PRORROGA LEY 3293-A. | as enacted, in force 6 November 2022 |
| `ley-3710-a/` | Ley 3710-A: INCREMENTA BASE DE CÁLCULO DE LA BONIFICACIÓN POR FUNCIONES ESPECIALES PARA EL PERSONAL DEL IPRODICH - LEY 2548-A. | as enacted, in force 6 November 2022 |
| `ley-3712-a/` | Ley 3712-A: RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 1025/22. | as enacted, in force 9 November 2022 |
| `ley-3709-a/` | Ley 3709-A: RATIFICA DECRETO 1580/22. | as enacted, in force 9 November 2022 |
| `ley-3700-r/` | Ley 3700-R: PROGRAMA DE REDUCCIÓN DE UTILIZACIÓN DE SORBETES Y VASOS DESCARTABLES PLÁSTICOS. | as enacted, in force 2 November 2022 |
| `ley-3698-e/` | Ley 3698-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL A LA ESCUELA DE EDUCACIÓN PRIMARIA Nº 534 "PRIMERA LUZ DE LA PATRIA". | as enacted, in force 2 November 2022 |
| `ley-3697-e/` | Ley 3697-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL A LA ESCUELA DE EDUCACIÓN PRIMARIA Nº 98 "HÉROES CHAQUEÑOS DE MALVINAS". | as enacted, in force 2 November 2022 |
| `ley-3695-c/` | Ley 3695-C: ASISTENCIA, ABORDAJE E INTERVENCIÓN DE FAMILIAS Y PERSONAS EN SITUACIÓN DE CALLE. | as enacted, in force 2 November 2022 |
| `ley-3702-e/` | Ley 3702-E: DÍA PROVINCIAL DE LA EDUCACIÓN DOMICILIARIA Y HOSPITALARIA. | as enacted, in force 2 November 2022 |
| `ley-3701-e/` | Ley 3701-E: DÍA DE LAS ARTES ESCÉNICAS. | as enacted, in force 21 October 2022 |
| `ley-3694-a/` | Ley 3694-A: EXTENSIÓN DEL SUPLEMENTO COMPLEMENTARIO ESTABLECIDO POR LEY 3651-A, PARA EL PERSONAL MÉDICO, A LOS PROFESIONALES BIOQUÍMICOS Y ODONTÓLOGOS. | as enacted, in force 25 December 2022 |
| `ley-3679-a/` | Ley 3679-A: REISTAURA LA LEY 2024-K ( ANTES LEY 7030). | as enacted, in force 21 October 2022 |
| `ley-3678-k/` | Ley 3678-K: REINSTAURA LEY 3201-K. | as enacted, in force 21 October 2022 |
| `ley-3688-a/` | Ley 3688-A: DEJA SIN EFECTO LAS RESTRICCIONES AL DOMINIO EN EL ARTÍCULO 4º DE LA LEY 7205. | as enacted, in force 21 October 2022 |
| `ley-3689-a/` | Ley 3689-A: INCREMENTO DE LA BONIFICACIÓN ESPECIAL DE LA JURISDICCIÓN 04: MINISTERIO DE PLANIFICACIÓN, ECONOMÍA E INFRAESTRUCTURA. | as enacted, in force 12 October 2022 |
| `ley-3690-a/` | Ley 3690-A: RATIFICA DECRETO 1436/22 - BONIFICACIÓN PARA EL PERSONAL DE LA JURISDICCIÓN 23:MINISTERIO DE PLANIFICACIÓN, ECONOMÍA E INFRAESTRUCTURA. | as enacted, in force 21 October 2022 |
| `ley-3691-e/` | Ley 3691-E: DÍA DEL HISTORIADOR INDÍGENA. | as enacted, in force 12 October 2022 |
| `ley-3692-a/` | Ley 3692-A: TRANSFIERE INMUEBLE. | as enacted, in force 21 October 2022 |
| `ley-3677-a/` | Ley 3677-A: ESTABLECE LINEAMIENTOS PARA EL DESARROLLO TERRITORIAL  UN HÁBITAT ADECUADO.E INCORPORA INC.H DEL ARTÍCULO 20 CAPÍTULO II- RECURSOS MUNICIPALES DE LA… | as enacted, in force 2 November 2022 |
| `ley-3693-g/` | Ley 3693-G: INCLUSIÓN DIGITAL GRATUITA PARA PERSONAS MAYORES DE SESENTA AÑOS. | as enacted, in force 21 October 2022 |
| `ley-3687-a/` | Ley 3687-A: PRESUPUESTO CON PERSPECTIVA AMBIENTAL. INCORPORA EL INCISO e) AL ARTICULO 34 DE LA LEY N° 1092-A | as enacted, in force 26 October 2022 |
| `ley-3685-g/` | Ley 3685-G: IMPONE EL NOMBRE "DOCTOR CARLOS POSSE" AL BANCO DE LECHE HUMANA DEL HOSPITAL "DR. JULIO C. PERRANDO". | as enacted, in force 21 October 2022 |
| `ley-3682-g/` | Ley 3682-G: PROGRAMA PROVINCIAL DE PROMOCIÓN DE LA DONACIÓN DE SANGRE Y CÉLULAS PROGENITORAS HEMATOPOYÉTICAS. | as enacted, in force 21 October 2022 |
| `ley-3681-g/` | Ley 3681-G: ADHESIÓN A LA LEY NACIONAL 27675 - DE RESPUESTA INTEGRAL AL VIH, HEPATITIS VIRALES, OTRAS INFECCIONES DE  TRANSMISIÓN SEXUAL - LTS- Y TUBERCULOSIS -… | as enacted, in force 21 October 2022 |
| `ley-3680-l/` | Ley 3680-L: DÍA DEL TRABAJADOR DE SEGURIDAD SOCIAL DE LA PROVINCIA DEL CHACO. | as enacted, in force 26 October 2022 |
| `ley-3675-a/` | Ley 3675-A: RATIFICACIÓN DEL DECRETO 1853/21 - ADICIONAL REMUNERATIVO, 09: PODER JUDICIAL, 17: TRIBUNAL ELECTORAL, 40: CONSEJO DE LA MAGISTRATURA Y JURADO DE EN… | as enacted, in force 12 October 2022 |
| `ley-3674-a/` | Ley 3674-A: RATIFICACIÓN DEL DECRETO 2009/21 - ADICIONAL REMUNERATIVO NO BONIFICABLE LEY 3262-A NUEVOS MONTOS EN ABRIL, JUNIO, AGOSTO Y OCTUBRE DEL AÑO 2021. | as enacted, in force 12 October 2022 |
| `ley-3673-a/` | Ley 3673-A: RATIFICACIÓN DEL DECRETO 2008/21 - ADICIONAL REMUNERATIVO JURISDICCIÓN 18: FISCALÍA DE ESTADO- | as enacted, in force 12 October 2022 |
| `ley-3672-g/` | Ley 3672-G: GUÍA DE ACOMPAÑAMIENTO PARA ATENCIÓN DE DUELOS PERINATALES Y NEONATALES. | as enacted, in force 2 October 2022 |
| `ley-3671-e/` | Ley 3671-E: EDUCACIÓN AMBIENTAL INTEGRAL. | as enacted, in force 12 October 2022 |
| `ley-3670-e/` | Ley 3670-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL PRIMER EDIFICIO DE LA ESCUELA Nº 111 "JUAN BAUTISTA TERÁN". | as enacted, in force 12 October 2022 |
| `ley-3669-e/` | Ley 3669-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL EDIFICIO DE LA "EX-COOPERATIVA LIMITADA IDEAL". | as enacted, in force 12 October 2022 |
| `ley-3668-e/` | Ley 3668-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL EDIFICIO MUNICIPAL DE LA LOCALIDAD DE PAMPA DEL INFIERNO. | as enacted, in force 12 October 2022 |
| `ley-3667-a/` | Ley 3667-A: IMPONE EL NOMBRE DE TATIANA KOLODZIEY AL TRAMO 3 DE LA RED CAMINERA. | as enacted, in force 30 September 2022 |
| `ley-3666-e/` | Ley 3666-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL EDIFICIO DE LA CONFEDERACIÓN GENERAL DEL TRABAJO SECCIONAL  CHACO. | as enacted, in force 30 September 2022 |
| `ley-3665-a/` | Ley 3665-A: EJERCICIO PROFESIONAL DE NIÑEZ, ADOLESCENCIA Y FAMILIA. | as enacted, in force 21 October 2022 |
| `ley-3663-a/` | Ley 3663-A: PRORROGA LEY 2828-A. | as enacted, in force 30 September 2022 |
| `ley-3661-a/` | Ley 3661-A: IMPONE EL NOMBRE DE CABALGATA DE LA FE A UN TRAMO DE LA RUTA PROVINCIAL Nº 4. | as enacted, in force 21 September 2022 |
| `ley-3659-e/` | Ley 3659-E: DÍA DE LA PREVENCIÓN DE LA VIOLENCIA EN EL NOVIAZGO. | as enacted, in force 23 September 2022 |
| `ley-3657-t/` | Ley 3657-T: PROGRAMA ALCOHOLEMIA CERO. | as enacted, in force 7 September 2022 |
| `ley-3656-i/` | Ley 3656-I: ADHESIÓN A LA LEY NACIONAL 27.076 - PROGRAMA FEDERAL PARA EL FOMENTO Y DESARROLLO DE LA PRODUCCIÓN BUBALINA - INCENTIVOS FISCALES PROVINCIALES. | as enacted, in force 23 September 2022 |
| `ley-3655-l/` | Ley 3655-L: PROGRAMA PROVINCIAL DE RECONVERSIÓN LABORAL PARA TRABAJADORES CANILLITAS. | as enacted, in force 21 September 2022 |
| `ley-3654-c/` | Ley 3654-C: EJERCICIO  PROFESIONAL DE LA INGENIERÍA FORESTAL Y LA CREACIÓN DEL CONSEJO PROFESIONAL DE CIENCIAS FORESTALES DEL CHACO. | as enacted, in force 23 September 2022 |
| `ley-3653-r/` | Ley 3653-R: FOMENTO A LA ARBORICULTURA - CREACIÓN DE VIVEROS. | as enacted, in force 21 September 2022 |
| `ley-3652-g/` | Ley 3652-G: CONTROL DEL TABACO- AMBIENTE LIBRE HUMO. ABROGA LEY Nº 642-R (ANTES LEY 3515) | as enacted, in force 23 September 2022 |
| `ley-3640-g/` | Ley 3640-G: "CREA  PROGRAMA PATU". ABROGA LEY Nº 2250-G. | as enacted, in force 16 September 2022 |
| `ley-3651-a/` | Ley 3651-A: SUPLEMENTO COMPLEMENTARIO PARA EL PERSONAL MÉDICO. | as enacted, in force 21 September 2022 |
| `ley-3650-a/` | Ley 3650-A: REMUNERACIONES DE LAS AUTORIDADES SUPERIORES (PRESIDENTE, VOCALES Y GERENTE GENERAL) DE LA JURISDICCIÓN 12 - LOTERÍA CHAQUEÑA. | as enacted, in force 21 September 2022 |
| `ley-3649-a/` | Ley 3649-A: INCREMENTOS SALARIALES PARA EL TRIBUNAL DE CUENTAS, PODER JUDICIAL, TRIBUNAL ELECTORAL, CONSEJO DE LA MAGISTRATURA Y JURADO DE ENJUICIAMIENTO Y FISC… | as enacted, in force 21 September 2022 |
| `ley-3648-a/` | Ley 3648-A: INCREMENTOS EN EL ESCALAFÓN GENERAL LEY 196-A (DECRETO 433/22). | as enacted, in force 16 September 2022 |
| `ley-3647-a/` | Ley 3647-A: PERSONAL DOCENTE, INCREMENTOS DEL VALOR ÍNDICE UNO (1) Y DEL CONCEPTO RECOMPOSICIÓN DOCENTE. | as enacted, in force 16 September 2022 |
| `ley-3646-a/` | Ley 3646-A: PERSONAL DOCENTE, INCRMENTOS DEL VALOR ÍNDICE UNO (1) DEL CONCEPTO RECOMPOSICIÓN DOCENTE. | as enacted, in force 16 September 2022 |
| `ley-3645-a/` | Ley 3645-A: BONIFICACIÓN ESPECIAL AL PERSONAL DE ARQUITECTURA HOSPITALARIA. | as enacted, in force 16 September 2022 |
| `ley-3644-a/` | Ley 3644-A: MODIFICACIONES EN LA BASE DE CÁLCULO DEL CONCEPTO ADICIONAL REMUNERATIVO ESPECIAL PARA LA SECRETARÍA GENERAL DE GOBERNACIÓN. | as enacted, in force 16 September 2022 |
| `ley-3643-a/` | Ley 3643-A: RATIFICA EL DECRETO DEL P.E. Nº 1258 DEL 19/06/2022. | as enacted, in force 9 September 2022 |
| `ley-3642-a/` | Ley 3642-A: BONIFICACIONES PARA LA DIRECCIÓN PROVINCIAL DE CATASTRO Y CARTOGRAFÍA. | as enacted, in force 9 September 2022 |
| `ley-3641-h/` | Ley 3641-H: MODIFICACIONES EN LA ESCALA SALARIAL DE LA LEY 2017-H (PENSIÓN GRACIABLE PARA EX SOLDADOS CONVOCADOS POR EL DISTRITO MILITAR CHACO). | as enacted, in force 9 September 2022 |
| `ley-3632-l/` | Ley 3632-L: ESTABLECE DÍA NO LABORABLE A LOS QUE PROFESEN EL CULTO CRISTIANO EVANGÉLICO. | as enacted, in force 28 August 2022 |
| `ley-3639-g/` | Ley 3639-G: PLAN INTEGRAL DE SALUD ODONTOLÓGICA INTERCULTURAL. | as enacted, in force 28 August 2022 |
| `ley-3638-g/` | Ley 3638-G: ADHESIÓN A LA LEY NACIONAL 27.628 - DÍA DEL ELECTRODEPENDIENTE POR CUESTIONES DE SALUD. | as enacted, in force 28 August 2022 |
| `ley-3634-a/` | Ley 3634-A: SUMA FIJA - PODER LEGISLATIVO. | as enacted, in force 28 August 2022 |
| `ley-3633-a/` | Ley 3633-A: INCREMENTOS SALARIALES MARZO 2022 PODER LEG., AUTORIDADES SUP. DEL P. E., CONTADURÍA GENERAL Y TESORERÍA GENERAL DE LA PROVINCIA, DIRECCIÓN DE AERON… | as enacted, in force 28 August 2022 |
| `ley-3631-l/` | Ley 3631-L: RATIFICA DECRETO 274/2017 | as enacted, in force 23 September 2022 |
| `ley-3630-a/` | Ley 3630-A: LEYENDA EN BOLETAS DE SERVICIO PÚBLICO DE AGUA. | as enacted, in force 28 August 2022 |
| `ley-3629-g/` | Ley 3629-G: PROGRAMA DE CONCIENTIZACIÓN SOBRE LOS EFECTOS DEL CONSUMO DE ALCOHOL DURANTE EL EMBARAZO. | as enacted, in force 28 August 2022 |
| `ley-3628-a/` | Ley 3628-A: PRORROGA LEY 2057-A (Antes Ley 7115). | as enacted, in force 28 August 2022 |
| `ley-3627-a/` | Ley 3627-A: PRORRÓGA LEY 2178-A (Antes Ley 7349). | as enacted, in force 28 August 2022 |
| `ley-3626-e/` | Ley 3626-E: DÍA DE LA CHACARERA DEL MONTE, EL DÍA 4 DE AGOSTO. | as enacted, in force 17 August 2022 |
| `ley-3622-a/` | Ley 3622-A: LEY 3424-A CONCEPTO "AJUSTE POR REVISIÓN" EXTENSIÓN AL TRIBUNAL DE CUENTAS, FISCALÍA DE ESTADO Y FISCALÍA DE INVESTIGACIONES ADMINISTRATIVAS. | as enacted, in force 17 August 2022 |
| `ley-3621-a/` | Ley 3621-A: INCREMENTOS SALARIALES PARA LA POLICÍA PROVINCIAL Y SERVICIO PENITENCIARIO PROVINCIAL. | as enacted, in force 17 August 2022 |
| `ley-3620-e/` | Ley 3620-E: DÍA DEL DOCENTE RURAL. | as enacted, in force 17 August 2022 |
| `ley-3619-e/` | Ley 3619-E: PUERTO TIROL CAPITAL PROVINCIAL DEL MURALISMO Y ARTE PÚBLICO. | as enacted, in force 17 August 2022 |
| `ley-3618-g/` | Ley 3618-G: PROGRAMA DE ESCLEROSIS MÚLTIPLE. | as enacted, in force 17 August 2022 |
| `ley-3617-a/` | Ley 3617-A: ADICIONAL COMPLEMENTARIO LEY 3369-A, CARÁCTER BONIFICABLE. | as enacted, in force 14 August 2022 |
| `ley-3616-a/` | Ley 3616-A: BONIFICACIÓN POR TÍTULO PARA LAS JURISDIICCIONES 21: POLICÍA PROVINCIAL Y 36: SERVICIO PENITENCIARIO PROVINCIAL. | as enacted, in force 14 August 2022 |
| `ley-3615-e/` | Ley 3615-E: PREMIO ANUAL PERMANENTE  A LOS JÓVENES DESTACADOS DE LA PROVINCIA DEL CHACO. | as enacted, in force 29 July 2022 |
| `ley-3614-g/` | Ley 3614-G: PLAZAS INCLUSIVAS. | as enacted, in force 29 July 2022 |
| `ley-3613-w/` | Ley 3613-W: ADHIÉRESE LA PROVINCIA DEL CHACO AL DECRETO DE NECESIDAD Y URGENCIA N. 805/21. | as enacted, in force 29 July 2022 |
| `ley-3612-s/` | Ley 3612-S: PROGRAMA DE PADRINAZGO PARA CLUBES DE BARRIOS Y MERENDEROS. | as enacted, in force 28 October 2022 |
| `ley-3611-g/` | Ley 3611-G: CREA PROGRAMA PROVINCIAL DE ATENCIÓN INTEGRAL DEL ALBINISMO. | as enacted, in force 31 August 2022 |
| `ley-3610-g/` | Ley 3610-G: DÍA PROVINCIAL DE LA SENSIBILIZACIÓN SOBRE EL ALBINISMO. | as enacted, in force 29 July 2022 |
| `ley-3609-e/` | Ley 3609-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL A LA CAPILLA VIRGEN DE ITATÍ. | as enacted, in force 29 July 2022 |
| `ley-3608-c/` | Ley 3608-C: DÍA PROVINCIAL DEL ADMINISTRADOR DE PROPIEDAD HORIZONTAL. | as enacted, in force 29 July 2022 |
| `ley-3607-g/` | Ley 3607-G: DÍA DE SOCIALIZACIÓN DEL SÍNDROME DE MÜNCHAUSEN POR PODERES (SMP) - MALTRATO INFANTIL DE ALTO RIESGO. | as enacted, in force 27 July 2022 |
| `ley-3606-g/` | Ley 3606-G: CAMPAÑA DE CONCIENTIZACIÓN SOBRE EL RUIDO. | as enacted, in force 27 July 2022 |
| `ley-3598-f/` | Ley 3598-F: RÉGIMEN DE INCENTIVO FISCAL PARA OBRAS PRIVADAS. | as enacted, in force 10 July 2022 |
| `ley-3599-w/` | Ley 3599-W: PREMIO PROFESOR JUAN CHICO. | as enacted, in force 10 July 2022 |
| `ley-3600-e/` | Ley 3600-E: CENTROS PSICOSOCIOEDUCATIVOS PARA PERSONAS AUTORAS DE VIOLENCIA DE GÉNERO. | as enacted, in force 31 August 2022 |
| `ley-3601-i/` | Ley 3601-I: DÍA DEL EMPRENDEDOR Y LA EMPRENDEDORA CHAQUEÑOS. | as enacted, in force 13 July 2022 |
| `ley-3602-g/` | Ley 3602-G: SALA DE TERAPIA INTENSIVA "DOCTOR MIGUEL DURÉ". | as enacted, in force 10 July 2022 |
| `ley-3603-r/` | Ley 3603-R: CREA PROGRAMA PROVINCIAL DE CONCIENTIZACIÓN Y PREVENCIÓN DE DAÑOS EN NUESTROS HUMEDALES Y RÍOS NAVEGABLES. | as enacted, in force 31 August 2022 |
| `ley-3604-a/` | Ley 3604-A: REINSTAURA LEY 2107-A (ANTES LEY 7206). | as enacted, in force 13 July 2022 |
| `ley-3587-a/` | Ley 3587-A: REINSTAURA LEY 2920-A. | as enacted, in force 10 July 2022 |
| `ley-3592-e/` | Ley 3592-E: DECLARA PATRIMONIO CULTURAL Y NATURAL LA PLAZOLETA EVITA. | as enacted, in force 10 July 2022 |
| `ley-3593-r/` | Ley 3593-R: PROGRAMA DE SEPARACIÓN DE RESIDUOS SÓLIDOS URBANOS EN ORIGEN EN EL ÁMBITO DE LOS ORGANISMOS PÚBLICOS DE LA PROVINCIA. | as enacted, in force 27 July 2022 |
| `ley-3594-e/` | Ley 3594-E: SEMANA DE LUCHA CONTRA EL ABUSO A LA INTEGRIDAD SEXUAL DE NIÑAS, NIÑOS Y ADOLESCENTES. | as enacted, in force 10 July 2022 |
| `ley-3595-e/` | Ley 3595-E: IMPLEMENTAR EL USO DE BORDADOS, INSIGNIAS O PRENDEDOR TIPO PIN DE LAS "ISLAS MALVINAS" EN GUARDAPOLLVOS Y UNIFORMES DE LOS ALUMNOS DE CUARTO GRADO D… | as enacted, in force 10 July 2022 |
| `ley-3596-w/` | Ley 3596-W: DIA PROVINCIAL DE LA NIÑEZ INDÍGENA. | as enacted, in force 10 July 2022 |
| `ley-3560-g/` | Ley 3560-G: CREA EL PROGRAMA HORA INCLUSIVA. | as enacted, in force 12 June 2022 |
| `ley-3584-e/` | Ley 3584-E: TALLERES DE TOMA DE CONCIENCIA DE ABUSO Y MALTRATO DE ADULTOS MAYORES EN LOS NIVELES PRIMARIOS Y SECUNDARIOS DE LAS ESCUELAS PÚBLICAS Y PRIVADAS | as enacted, in force 15 June 2022 |
| `ley-3585-g/` | Ley 3585-G: DÍA PROVINCIAL DE LAS PERSONAS ADULTAS MAYORES. | as enacted, in force 15 June 2022 |
| `ley-3583-j/` | Ley 3583-J: CAMPAÑA PROVINCIAL DE PREVENCIÓN DE ESTAFAS TELEFÓNICAS Y POR INTERNET. | as enacted, in force 15 June 2022 |
| `ley-3582-i/` | Ley 3582-I: PROGRAMA DE CAPACITACIÓN y FORMACIÓN DE LOS ESTABLECIMIENTOS GASTRONÓMICOS PARA BRINDAR UN MENÚ LIBRE DE GLUTEN . | as enacted, in force 17 June 2022 |
| `ley-3581-i/` | Ley 3581-I: PROMOCIÓN DE HUERTAS URBANAS. | as enacted, in force 17 June 2022 |
| `ley-3580-g/` | Ley 3580-G: REGULACIÓN DE LA ASISTENCIA PERSONAL PARA PERSONAS CON DISCAPACIDAD. | as enacted, in force 17 June 2022 |
| `ley-3579-j/` | Ley 3579-J: MAPA INTERACTIVO RURAL CHACO. | as enacted, in force 17 June 2022 |
| `ley-3578-e/` | Ley 3578-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL EDIFICIO MUNICIPAL DE QUITILIPI. | as enacted, in force 15 June 2022 |
| `ley-3575-w/` | Ley 3575-W: MONUMENTO CACIQUE LUIS GARCIA. | as enacted, in force 15 June 2022 |
| `ley-3569-a/` | Ley 3569-A: PERSONAL DOCENTE, INCREMENTOS DEL VALOR ÍNDICE UNO (1) Y EL CONCEPTO RECOMPOSICIÓN DOCENTE. | as enacted, in force 12 June 2022 |
| `ley-3570-e/` | Ley 3570-E: DECLARA PATRIMONIO CULTURAL AL FESTIVAL DEL GUARDAMONTE | as enacted, in force 12 June 2022 |
| `ley-3571-e/` | Ley 3571-E: ABRIL, MES DE LA LUCHA CONTRA EL MAL TRATO INFANTIL. | as enacted, in force 12 June 2022 |
| `ley-3573-g/` | Ley 3573-G: ADHESIÓN A LA LEY NACIONAL 27.642 PROMOCIÓN DE LA ALIMENTACIÓN SALUDABLE. | as enacted, in force 12 June 2022 |
| `ley-3574-g/` | Ley 3574-G: CAMPAÑA DE PREVENCIÓN Y CONCIENTIZACIÓN DE ENFERMEDADES CARDIOVASCULARES. | as enacted, in force 12 June 2022 |
| `ley-3576-t/` | Ley 3576-T: ADHESIÓN A LA LEY 27.510. | as enacted, in force 12 June 2022 |
| `ley-3567-e/` | Ley 3567-E: DECLARA PATRIMONIO HISTÓRICO, CULTURAL Y NATURAL AL EDIFICIO MUNICIPAL DE CHARATA. | as enacted, in force 12 June 2022 |
| `ley-3566-e/` | Ley 3566-E: DECLARA PATRIMONIO HISTÓRICO, CULTURAL Y NATURAL AL EDIFICIO DE LA ESTACIÓN DEL FERROCARRIL DE CHARATA. | as enacted, in force 12 June 2022 |
| `ley-3565-g/` | Ley 3565-G: ADHESION A LA LEY NACIONAL N° 27.611 - ATENCION Y CUIDADO INTEGRAL DE LA SALUD DURANTE EL EMBARAZO Y LA PRIMERA INFANCIA-. | as enacted, in force 12 June 2022 |
| `ley-3558-a/` | Ley 3558-A: PERSONAL DEL ESCALAFÓN GENERAL LEY 196-A INCREMENTOS SALARIALES DESDE JULIO, AGOSTO, SEPTIEMBRE Y NOVIEMBRE DEL AÑO 2021. | as enacted, in force 12 June 2022 |
| `ley-3559-r/` | Ley 3559-R: PREMIO A LA ACCIÓN AMBIENTAL EN LA PROVINCIA DEL CHACO. | as enacted, in force 12 June 2022 |
| `ley-3553-a/` | Ley 3553-A: MODIFICA BONIFICACIONES ESPECIALES PARA  INSTITUTO DE CULTURA, DE TURISMO Y DE DEPORTE. | as enacted, in force 1 June 2022 |
| `ley-3563-e/` | Ley 3563-E: DÍA DEL ESCULTOR CHAQUEÑO. | as enacted, in force 12 June 2022 |
| `ley-3564-e/` | Ley 3564-E: PROMESA DE LEALTAD A LA BANDERA ARGENTINA TOMADA POR UN EX-COMBATIENTE DE MALVINAS.- | as enacted, in force 12 June 2022 |
| `ley-3552-a/` | Ley 3552-A: RATIFICA LOS DECRETOS DEL PODER EJECUTIVO 2101/18, 2237/18, 3244/18, 2636/19 Y 4060/19.- | as enacted, in force 29 May 2022 |
| `ley-3562-e/` | Ley 3562-E: ADHESIÓN A LA LEY NACIONAL 26.691.- | as enacted, in force 12 June 2022 |
| `ley-3561-a/` | Ley 3561-A: IMPONE NOMBRE DE EX-COMBATIENTES Y VETERANOS DE GUERRA DE LAS ISLAS MAL VINAS A VEHÍCULOS DEL ESTADO PROVINCIAL. | as enacted, in force 12 June 2022 |
| `ley-3546-a/` | Ley 3546-A: MODIFICA VALOR FONDO DE APOYO AL SISTEMA EDUCATIVO LEY 2633-A | as enacted, in force 31 August 2022 |
| `ley-3547-a/` | Ley 3547-A: CREACIÓN ADICIONAL REMUNERATIVO ESPECIAL EN EL ÁMBITO DE LA JURISDICCIÓN 02 -SECRETARÍA GENERAL DE GOBERNACIÓNESCALAFÓN 21- ASESORÍA GENERAL DE GOBI… | as enacted, in force 31 August 2022 |
| `ley-3549-f/` | Ley 3549-F: INCREMENTO SALARIAL JURISDICCIÓN 19 -CONTADURÍA GENERAL DE LA PROVINCIA- y JURISDICCIÓN 26 -TESORERÍA GENERAL DE LA PROVINCIA | as enacted, in force 31 August 2022 |
| `ley-3548-a/` | Ley 3548-A: TRIBUNAL DE CUENTAS - INCREMENTO SALARIAL.- | as enacted, in force 31 August 2022 |
| `ley-3545-a/` | Ley 3545-A: INCREMENTO DE LA BONIFICACIÓN ESPECIAL DEL MINISTERIO DE PLANIFICACIÓN, ECONOMÍA E INFRAESTRUCTURA EN JUNIO Y SEPTIEMBRE DEL AÑO 2021 | as enacted, in force 22 May 2022 |
| `ley-3551-f/` | Ley 3551-F: INCREMENTO BASE CALCULO BONIFICACIONES SALUD PÚBLICA Y RESTO BONIFICACIONES | as enacted, in force 22 May 2022 |
| `ley-3542-a/` | Ley 3542-A: POLICÍA PROVINCIAL, INCREMENTOS SALARIALES DESDE JULIO Y SEPTIEMBRE DEL AÑO 2021. | as enacted, in force 22 May 2022 |
| `ley-3550-a/` | Ley 3550-A: ESCALAFÓN DE LA DIRECCIÓN DE AERONÁUTICA (LEY 1973-A) INCREMENTO SALARIAL | as enacted, in force 31 August 2022 |
| `ley-3543-a/` | Ley 3543-A: MINISTERIO DE GOBIERNO Y TRABAJO - NUEVAS BASES DE CÁLCULOS PARA FONDOS ESTÍMULOS DESDE MAYO Y AGOSTO DEL AÑO 2021. | as enacted, in force 22 May 2022 |
| `ley-3544-a/` | Ley 3544-A: INCREMENTOS SALARIALES DESDE JULIO Y SEPTIEMBRE DEL AÑO 2021 PARA CONTADURÍA GENERAL Y TESORERÍA GENERAL DE LA PROVINCIA, DIRECCIÓN DE AERONÁUTICA. … | as enacted, in force 22 May 2022 |
| `ley-3554-a/` | Ley 3554-A: TRIBUNAL DE CUENTAS, PODER JUDICIAL, TRIBUNAL ELECTORAL, CONSEJO DE LA MAGISTRATURA Y JURADO DE ENJUICIAMIENTO, FISCALÍA DE ESTADO - INCREMENTOS SAL… | as enacted, in force 1 June 2022 |
| `ley-3555-a/` | Ley 3555-A: SERVICIO PENITENCIARIO PROVINCIAL, INCREMENTOS SALARIALES EN JULIO Y SEPTIEMBRE DEL AÑO 2021. | as enacted, in force 12 June 2022 |
| `ley-3556-a/` | Ley 3556-A: INCREMENTOS EN LAS PRESTACIONES SOCIALES LEYES 1369-H, 1370-H Y 1614-H EN JULIO Y SEPTIEMBRE DEL AÑO 2021. | as enacted, in force 12 June 2022 |
| `ley-3557-a/` | Ley 3557-A: INCREMENTO SALARIAL PARA EL PERSONAL DOCENTE EN JULIO DEL AÑO 2021 RATIFICA DECRETO 1553/21. | as enacted, in force 12 June 2022 |
| `ley-3541-a/` | Ley 3541-A: ADMINISTRACIÓN TRIBUTARIA PROVINCIAL. BONIFICACIÓN ESPECIAL POR MA YOR RESPONSABILIDAD. | as enacted, in force 14 September 2022 |
| `ley-3538-e/` | Ley 3538-E: DECLARA COMO PATRIMONIO CULTURAL INMATERIAL LA VIGILIA POR MAL VINAS QUE SE REALIZA EL 2 DE ABRIL DE CADA AÑO. | as enacted, in force 27 April 2022 |
| `ley-3537-g/` | Ley 3537-G: DÍA PROVINCIAL DE LA MUJER Y LA NIÑA EN LA CIENCIA. | as enacted, in force 12 June 2022 |
| `ley-3532-a/` | Ley 3532-A: CREA BONIF. POR MAYORES FUNCIONES Y RESPONSABILIDADES PARA EL MINIST DE PLANIFICACIÓN, ECONOMÍA E INFRAESTRUCTURA -CONTADURÍA Y TESORERÍA GRAL DE LA… | as enacted, in force 14 September 2022 |
| `ley-3536-e/` | Ley 3536-E: CREA EL CONCURSO Y PREMIO PROVINCIAL LITERARIO “ISLAS MAL VINAS”. | as enacted, in force 27 April 2022 |
| `ley-3534-f/` | Ley 3534-F: APRUEBA  EL ACUERDO DENOMINADO CONSENSO FISCAL AÑO 2021.- | as enacted, in force 31 August 2022 |
| `ley-3533-a/` | Ley 3533-A: MODIFICACIÓN BASE DE CÁLCULO DE LA BONIFICACIÓN ESPECIAL PARA LA SECRETARÍA DE MUNICIPIOS Y CIUDADES. | as enacted, in force 14 September 2022 |
| `ley-3512-g/` | Ley 3512-G: PROTECCIÓN INTEGRAL DE LOS DERECHOS DE LA MUJER EMBARAZADA EN ESTADO DE VULNERABILIDAD. | as enacted, in force 22 April 2022 |
| `ley-3510-e/` | Ley 3510-E: ARCHIVO ORAL DE LAS MEMORIAS DE MALVINAS. | as enacted, in force 20 April 2022 |
| `ley-3513-h/` | Ley 3513-H: MES PROVINCIAL DE LA CONSTRUCCIÓN COLECTIVA DE CONCIENCIA CIUDADANA. | as enacted, in force 3 April 2022 |
| `ley-3511-r/` | Ley 3511-R: PROGRAMA DE REUTILIZACIÓN Y RECICLADO DE APARATOS ELECTRÓNICOS Y ELÉCTRICOS, EN EL ÁMBITO DEL SECTOR PÚBLICO. | as enacted, in force 3 April 2022 |
| `ley-3509-e/` | Ley 3509-E: DECLARA DUELO PROVINCIAL POR FALLECIMIENTO DE UN VETERANO DE LA GUERRA DE MALVINAS E ISLAS DEL ATLANTICO SUR, RADICADO EN LA PROVINCIA. | as enacted, in force 3 April 2022 |
| `ley-3526-g/` | Ley 3526-G: DIA DEL DONANTE VOLUNTARIO DE PLASMA. | as enacted, in force 22 April 2022 |
| `ley-3525-i/` | Ley 3525-I: APLICACIÓN PARA CELIACOS “CHACO SIN TACC”. | as enacted, in force 20 April 2022 |
| `ley-3524-e/` | Ley 3524-E: DÍA PROVINCIAL DE LOS HUMEDALES CHAQUEÑOS. | as enacted, in force 14 September 2022 |
| `ley-3523-p/` | Ley 3523-P: ELEVA A SEGUNDA CATEGORÍA A LA MUNICIPALIDAD DE  VILLA RIO BERMEJITO. | as enacted, in force 22 April 2022 |
| `ley-3530-g/` | Ley 3530-G: ADHESION A LA LEY NACIONAL 26.945 DÍA NACIONAL POR UNA ARGENTINA SIN CHAGAS. | as enacted, in force 20 April 2022 |
| `ley-3529-e/` | Ley 3529-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL SENTENCIAS, EXP. DE INSTRUCCIÓN, MATERIALES FÍLMICOS DE LAS AUDIENCIAS DE JUICIOS ORALES DE LOS PROCESOS JUD… | as enacted, in force 20 April 2022 |
| `ley-3528-e/` | Ley 3528-E: CAPACITACIÓN OBLIGATORIA EN ÉTICA PÚBLICA. | as enacted, in force 10 July 2022 |
| `ley-3527-s/` | Ley 3527-S: PROGRAMA DE INSERCIÓN SOCIAL Y PROMOCIÓN DEPORTIVA “MI PLAZA, MI BARRIO”. | as enacted, in force 20 April 2022 |
| `ley-3522-f/` | Ley 3522-F: EMERGENCIA ECONÓMICA Y FINANCIERA.(HASTA 31/12/2023). | as enacted, in force 22 April 2022 |
| `ley-3516-a/` | Ley 3516-A: EXPROPIA INMUEBLE EN LA LOCALIDAD DE CHARADAI. | as enacted, in force 22 April 2022 |
| `ley-3515-s/` | Ley 3515-S: PROGRAMA DE PROMOCIÓN Y DIFUSIÓN DE LOS DEPORTES ELECTRÓNICOS. | as enacted, in force 25 May 2022 |
| `ley-3514-n/` | Ley 3514-N: ETAPA INVESTIGATIVA DEL PROCESO PENAL -PROTOCOLOS Y MANUALES DE ACTUACIÓN. | as enacted, in force 20 April 2022 |
| `ley-3517-a/` | Ley 3517-A: FORMACIÓN TRANSVERSAL EN DERECHOS HUMANOS PARA LA  PREVENCIÓN DE LA VIOLENCIA INSTITUCIONAL, EL ODIO, EL RACISMO, LA DISCRIMINACIÓN Y LA XENOFOBIA." | as enacted, in force 20 April 2022 |
| `ley-3518-a/` | Ley 3518-A: DONACIÓN DE BIENES MUEBLES PÚBLICOS EN DESUSO A ENTIDADES CON TEMÁTICA EN VIOLENCIA DE GÉNERO Y/O FAMILIAR. | as enacted, in force 22 April 2022 |
| `ley-3519-e/` | Ley 3519-E: EJE EDUCATIVO VINCULADO A LA PROTECCION DE LOS DERECHOS DE  LOS ANIMALES. | as enacted, in force 14 September 2022 |
| `ley-3520-g/` | Ley 3520-G: DÍA DE LA PERSONA DONANTE DE ÓRGANOS. | as enacted, in force 20 April 2022 |
| `ley-3521-l/` | Ley 3521-L: DIRECCIÓN PROVINCIAL DEL TRABAJO FUNCIONAMIENTO ESPECIAL TEMPORAL POR EMERGENCIA SANITARIA. | as enacted, in force 22 April 2022 |
| `ley-3506-j/` | Ley 3506-J: PROGRAMA PROVINCIAL DE PROMOCION DE POLITICAS CONTRA EL NEGACIONISMO DEL TERRORISMO DE ESTADO. | as enacted, in force 21 January 2022 |
| `ley-3505-g/` | Ley 3505-G: LEY DE ESTIMULACION TEMPRANA UNIVERSAL. | as enacted, in force 21 January 2022 |
| `ley-3504-e/` | Ley 3504-E: DECLARAR PATRIMONIO HISTORICO Y CULTURAL DE LA PROVINCIA DEL CHACO, AL PRIMER INMUEBLE, SEDE CENTRAL DEL INSTITUTO DEL ABORIGEN CHAQUEÑO, UBICADO EN… | as enacted, in force 21 January 2022 |
| `ley-3503-h/` | Ley 3503-H: PROGRAMA PROVINCIAL PUENTES HACIA LA AUTONOMIA DE ADOLESCENTES Y JOVENES SIN CUIDADOS PARENTALES. | as enacted, in force 21 January 2022 |
| `ley-3501-e/` | Ley 3501-E: DECLARAR PATRIMONIO HISTORICO Y CULTURAL DE LA PROVINCIA DEL CHACO, AL EDIFICIO DONDE FUNCIONARA EL HOTEL DE LA LOCALIDAD DE SAMUHU. | as enacted, in force 21 January 2022 |
| `ley-3499-r/` | Ley 3499-R: ADHESION A LA LEY NACIONAL 27.520 -LEY DE PRESUPUESTOS MINIMOS DE ADAPTACION Y MITIGACION AL CAMBIO CLIMATICO GLOBAL. | as enacted, in force 6 March 2022 |
| `ley-3498-g/` | Ley 3498-G: LEY DE CAPACITACION OBLIGATORIA EN DISCAPACIDAD, INCLUSION Y DIVERSIDAD PARA TODAS LAS PERSONAS QUE INTEGRAN LOS TRES PODERES DEL ESTADO. | as enacted, in force 21 January 2022 |
| `ley-3497-h/` | Ley 3497-H: OBSERVATORIO PROVINCIAL CONTRA LAS VIOLENCIAS EN RAZON DE GENERO. | as enacted, in force 21 January 2022 |
| `ley-3496-e/` | Ley 3496-E: DIA DE LA BOMBERA Y DEL BOMBERO VOLUNTARIO CHAQUEÑO. | as enacted, in force 21 January 2022 |
| `ley-3495-a/` | Ley 3495-A: POLICIA PROVINCIAL Y SERVICIO PENITENCIARIO PROVINCIAL. INCREMENTO SALARIAL DESDE OCTUBRE DEL AÑO 2021. | as enacted, in force 9 January 2022 |
| `ley-3494-a/` | Ley 3494-A: INCREMENTO SALARIAL DESDE OCTUBRE DEL AÑO 2021 PARA EL PODER LEGISLATIVO, PODER JUDICIAL, TRIBUNAL DE CUENTAS, TRIBUNAL ELECTORAL, FISCALIA DE ESTAD… | as enacted, in force 9 January 2022 |
| `ley-3493-a/` | Ley 3493-A: PERSONAL JORNALIZADO DE LA ADMINISTRACION PUBLICA PROVINCIAL. VALOR DEL DIA DESDE OCTUBRE DEL AÑO 2021. | as enacted, in force 9 January 2022 |
| `ley-3492-a/` | Ley 3492-A: PERSONAL DOCENTE. INCREMENTO DEL VALOR INDICE UNO (1) DESDE OCTUBRE DEL AÑO 2021. | as enacted, in force 9 January 2022 |
| `ley-3491-a/` | Ley 3491-A: INCREMENTO SALARIAL DESDE OCTUBRE DEL AÑO 2021 PARA AUTORIDADES SUP. DEL PODER EJECUTIVO - CONTADURIA GENERAL Y TESORERIA GENERAL DE LA PROVINCIA - … | as enacted, in force 9 January 2022 |
| `ley-3490-a/` | Ley 3490-A: PERSONAL DEL ESCALAFON GENERAL -LEY 196-A. INCREMENTOS SALARIALES DESDE OCTUBRE DEL AÑO 2021 PARA EL ESCALAFON GENERAL. | as enacted, in force 9 January 2022 |
| `ley-3489-a/` | Ley 3489-A: BENEFICIO REMUNERATIVO NO BONIFICABLE DESDE JUNIO DEL AÑO 2021 PARA LOS ORGANISMOS DEPENDIENTES DEL MINISTERIO DE GOBIERNO Y TRABAJO. | as enacted, in force 4 March 2022 |
| `ley-3488-a/` | Ley 3488-A: CREA BONIFICACION ESPECIAL PARA EL PERSONAL DEL MINISTERIO DE SEGURIDAD Y JUSTICIA, POLICIA PROVINCIAL, SERVICIO PENITENCIARIO Y DE READAPTACION SOC… | as enacted, in force 9 January 2022 |
| `ley-3487-a/` | Ley 3487-A: RATIFICACION DEL DECRETO 2004/21. LEY 1967-A. | as enacted, in force 9 January 2022 |
| `ley-3474-f/` | Ley 3474-F: CONDONACIÓN DE DEUDAS DE FIDEICOMISOS PÚBLICOS ADMlNISTRADOS POR FIDUCIARIA DEL NORTE S.A. | as enacted, in force 9 January 2022 |
| `ley-3464-a/` | Ley 3464-A: INSTITUTO CHAQUEÑO DE CIENCIA, TECNOLOGÍA E INNOVACIÓN (IChCTI) . ABRÓGASE LA LEY 1637-I -LEY DE CIENCIA, TECNOLOGÍA E INNOVACIÓN. ADHIERE A LEYES  … | current text only, as of 23 February 2022 |
| `ley-3465-r/` | Ley 3465-R: SISTEMAS PRODUCTIVOS AGROPECUARIOS Y AGROFORESTALES AGROECOLÓGICOS . | as enacted, in force 9 January 2022 |
| `ley-3466-a/` | Ley 3466-A: TRANSFIERE INMUEBLE.-PARQUE DE LA DEMOCRACIA-. | as enacted, in force 9 January 2022 |
| `ley-3467-k/` | Ley 3467-K: ACCESO A VIVIENDAS Y TIERRA PARA LA POBLACIÓN LGBTIQNB+. | as enacted, in force 9 January 2022 |
| `ley-3468-e/` | Ley 3468-E: RÉGIMEN ESPECIAL DE INASISTENCIAS JUSTIFICADAS PARA ESTUDIANTES. | as enacted, in force 9 January 2022 |
| `ley-3469-a/` | Ley 3469-A: EXPROPIACIÓN DE INMUEBLES EN LA LOCALIDAD DE SAMUHÚ  PROPIETARIO: SAMUHI SOCIEDAD ANÓNIMA COMERCIAL, INDUSTRIAL E INMOBILIARIA. | current text only, as of 23 February 2022 |
| `ley-3471-a/` | Ley 3471-A: EXPROPIACIÓN DE INMUEBLES EN LA CIUDAD DE RESISTENCIA. PROPIETARIO : BERGER , RAÚL JUAN. | as enacted, in force 9 January 2022 |
| `ley-3486-g/` | Ley 3486-G: PROGRAMA PROVINCIAL FEBRERO SE VISTE DE DORADO. | as enacted, in force 9 January 2022 |
| `ley-3481-g/` | Ley 3481-G: PROGRAMA DE PREVENCIÓN DE ENFERMEDADES CARDIOVASCULARES Y CONTROL DE PACIENTES DE RIESGO CORONARIO. | as enacted, in force 9 January 2022 |
| `ley-3482-a/` | Ley 3482-A: TRANSFIERE INMUEBLE. ABROGA LEY Nº 3042-A | current text only, as of 2 March 2022 |
| `ley-3480-d/` | Ley 3480-D: PROHIBICIÓN DE EMPLEO Y COMERCIALIZACIÓN DE PLÁSTICOS DE UN SOLO USO. | as enacted, in force 31 August 2022 |
| `ley-3479-w/` | Ley 3479-W: DÍA DEL ARTESANO Y ARTESANA INDÍGENA. | as enacted, in force 9 January 2022 |
| `ley-3477-l/` | Ley 3477-L: DÍA PROVINCIAL DE LA DELEGADA Y DEL DELEGADO GREMIAL DE BASE. | as enacted, in force 9 January 2022 |
| `ley-3476-a/` | Ley 3476-A: PROGRAMA DE PUERTOS CON PERSPECTIVA DE GÉNERO. | as enacted, in force 9 January 2022 |
| `ley-3475-l/` | Ley 3475-L: PROMOCIÓN LABORAL PARA VÍCTIMAS DEL DELITO DE TRATA Y EXPLOTACIÓN DE PERSONAS. | as enacted, in force 9 January 2022 |
| `ley-3470-e/` | Ley 3470-E: DECLARA PATRlMONIO CULTURAL INMATERlAL A LAS SILUETAS DE MARGARlTA BELEN. | as enacted, in force 22 May 2022 |
| `ley-3461-e/` | Ley 3461-E: INSTITUYE DIA 27 DE NOVIEMBRE DE CADA AÑO COMO DIA PROVINCIAL DE LA EDUCACIÓN DE JOVENES Y ADULTOS. | as enacted, in force 9 January 2022 |
| `ley-3463-f/` | Ley 3463-F: PRESUPUESTO GENERAL DE LA PROVINCIA PARA EL EJERCICIO 2022. | as enacted, in force 14 December 2021 |
| `ley-3460-e/` | Ley 3460-E: PATRIMONIO HISTÓRICO CULTURAL DE LA PROVINCIA DEL CHACO A LA SOCIEDAD ARGENTINA DE ESCRITORES -S.A.D.E.-FILIAL CHACO. | as enacted, in force 9 January 2022 |
| `ley-3459-g/` | Ley 3459-G: PROGRAMA DE APOYO AL PACIENTE ONCOLÓGICO. | as enacted, in force 9 January 2022 |
| `ley-3458-r/` | Ley 3458-R: TRANSFIERE JURISDICCION PROVINCIAL AL ESTADO NACIONAL. | as enacted, in force 3 December 2021 |
| `ley-3452-e/` | Ley 3452-E: ADHESIÓN A LA LEY NACIONAL 27.539 -CUPO FEMENINO Y ACCESO DE ARTISTAS MUJERES A EVENTOS MUSICALES. | as enacted, in force 28 November 2021 |
| `ley-3453-g/` | Ley 3453-G: ADHESIÓN ALA RESOLUCIÓN NACIONAL 1551 SEMANA POR LA PROMOCIÓN DE LOS DERECHOS DE LAS PERSONAS CON DISCAPACIDAD. | as enacted, in force 9 January 2022 |
| `ley-3454-r/` | Ley 3454-R: COMPENDIO DE NORMATIVA AMBIENTAL | as enacted, in force 9 January 2022 |
| `ley-3451-g/` | Ley 3451-G: PROGRAMA PROVINCIAL DE PROMOCIÓN DE LA SALUD MENSTRUAL. INCORPORA EL INCISO X) AL ART. 135 LEY 83-F. | as enacted, in force 9 January 2022 |
| `ley-3447-e/` | Ley 3447-E: DÍA DEL MAESTRO INDÍGENA | as enacted, in force 9 January 2022 |
| `ley-3446-a/` | Ley 3446-A: ADICIONAL REMUNERATIVO POR TÍTULO UNIVERSITARIO- PODER JUDICIAL, TRIBUNAL ELECTORAL Y CONSEJO DE LA MAGISTRATURA. | as enacted, in force 19 November 2021 |
| `ley-3448-e/` | Ley 3448-E: IMPLEMENTACIÓN DE LA SEMANA “HISTORIA DE MUJERES” EN EL CALENDARIO ESCOLAR. | as enacted, in force 9 January 2022 |
| `ley-3442-a/` | Ley 3442-A: BENEFICIO TARIFARIO PARA EL FOMENTO DE SALAS DE TEATRO Y CENTROS CULTURALES. | as enacted, in force 19 November 2021 |
| `ley-3439-w/` | Ley 3439-W: BANDERA OFICIAL DE LA ETNIA MOQOIT. | as enacted, in force 19 November 2021 |
| `ley-3434-r/` | Ley 3434-R: TRANSFIERE DOMINIO PROVINCIAL A LA MUNICIPALIDAD DE RESISTENCIA:  LAGUNA ARGUELLO.PARQUE AUTÓDROMO.PARQUE CARAGUATÁ.PARQUE PASEO SUR.CANAL SOBERANÍA… | as enacted, in force 19 November 2021 |
| `ley-3432-m/` | Ley 3432-M: PRORROGA LEY 1388-M -SUSPENSIÓN DE EJECUCIONES HIPOTECARlAS-. | as enacted, in force 19 November 2021 |
| `ley-3441-c/` | Ley 3441-C: LEY DE PROTECCION INTEGRAL PARA PREVENIR, SANCIONAR Y ERRADICAR LA DISCRIMINACION EN RAZON DE LA EDAD EN TODOS LOS AMBITOS SOCIALES DE LA PROVINCIA. | as enacted, in force 19 November 2021 |
| `ley-3445-a/` | Ley 3445-A: CREACIÓN DE CARGOS EN EL PODER JUDICIAL. | as enacted, in force 19 November 2021 |
| `ley-3427-a/` | Ley 3427-A: INCREMENTOS SALARIALES PARA LA ADMINISTRACIÓN PUERTO DE BARRANQUERAS  EN JULIO Y SEPTIEMBRE 2021 | as enacted, in force 24 October 2021 |
| `ley-1068-a/` | Ley 1068-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 20 October 2000 |
| `ley-3424-a/` | Ley 3424-A: CREA ADICIONAL REMUNERATIVO Y AJUSTE POR REVISIÓN PARA EL PODER JUDICIAL -CONSEJO DE LA MAGISTRATURA Y JURADO DE  ENJUCIAMIENTO -TRIBUNAL ELECTORAL. | as enacted, in force 24 October 2021 |
| `ley-3425-a/` | Ley 3425-A: FISCALÍA DE ESTADO, CREA ADICIONAL REMUNERATIVO. | as enacted, in force 24 October 2021 |
| `ley-3417-h/` | Ley 3417-H: OBSERVATORIO CHAQUEÑO SOBRE ABUSO SEXUAL INFANTIL Y ADOLESCENTE. | as enacted, in force 20 August 2021 |
| `ley-3415-e/` | Ley 3415-E: ADHESIÓN A LA LEY NACIONAL 27.523 - DÍA NACIONAL DE LA REFORMA UNIVERSITARIA. | as enacted, in force 20 August 2021 |
| `ley-3413-j/` | Ley 3413-J: DERECHOS Y GARANTÍAS DE LAS PERSONAS VÍCTIMAS DE DELITOS. | as enacted, in force 20 August 2021 |
| `ley-3411-a/` | Ley 3411-A: REINSTAURA LA LEY 2556-A (ANTES LEY 7945). | as enacted, in force 20 August 2021 |
| `ley-3409-a/` | Ley 3409-A: REINSTAURA LA LEY 2265-A-(antes ley 7511). | as enacted, in force 20 August 2021 |
| `ley-3418-n/` | Ley 3418-N: MARCO REGULATORIO PARA PROMOVER LA INCLUSIÓN Y REPARACIÓN INTEGRAL DE NIÑAS, NIÑOS, ADOLESCENTES Y JÓVENES BENEFICIARIOS DE LA LEY NACIONAL 27.452 -… | as enacted, in force 20 August 2021 |
| `ley-3419-e/` | Ley 3419-E: DIA PROVINCIAL DE LA EDUCACION EN CONTEXTO DE ENCIERRO Y DE SUS TRABAJADORES Y TRABAJADORAS DOCENTES. | as enacted, in force 20 August 2021 |
| `ley-3420-e/` | Ley 3420-E: CENTRO DE INTERPRETACION INDIGENA DE LA PROVINCIA DEL CHACO. | as enacted, in force 20 August 2021 |
| `ley-3405-e/` | Ley 3405-E: LEY DE EDUCACIÓN DIGITAL. DEROGA ARTÍCULO 115 DE LEY 1887-E. MODIFICA ARTÍCULOS LEY 647-E. | as enacted, in force 20 August 2021 |
| `ley-3371-a/` | Ley 3371-A: SECRETARIA GENERAL DE GOBERNACIÓN. MODIFICACIÓN DE LAS BONIFICACIONES ESPECIALES LEYES 2418-A Y 2423-A. | as enacted, in force 16 June 2021 |
| `ley-3403-h/` | Ley 3403-H: COMBATIENTES CHAQUEÑOS FALLECIDOS EN LA GUERRA DE MALVINAS. DECLARACIÓN DE HÉROES PROVINCIALES. | as enacted, in force 14 July 2021 |
| `ley-3401-a/` | Ley 3401-A: INCORPORA PERSPECTIVA DE GÉNERO Y DIVERSIDAD EN TODA LA INFORMACIÓN Y ESTADÍSTICAS PÚBLICAS DE LA PROVINCIA DEL CHACO | as enacted, in force 14 July 2021 |
| `ley-3400-h/` | Ley 3400-H: CAMPAÑA DE CONCIENTIZACIÓN SOBRE LA PREVENCIÓN DEL MALTRATO EN LA NIÑEZ Y ADOLESCENCIA. | as enacted, in force 14 July 2021 |
| `ley-3398-f/` | Ley 3398-F: ADHIERE A LA LEY NACIONAL 27.487. | as enacted, in force 16 July 2021 |
| `ley-3397-l/` | Ley 3397-L: INCOMPATIBILIDAD PARA LICENCIADO, TÉCNICO Y/O PROFESIONALES DE CARRERAS AFINES EN HIGIENE Y SEGURIDAD DEL TRABAJO BONIFICACIONES. | as enacted, in force 14 July 2021 |
| `ley-3396-e/` | Ley 3396-E: CAPACITACIÓN OBLIGATORIA EN LA TEMATICA DE MALVINAS PARA TODAS LAS PERSONAS QUE DESEMPEÑAN FUNCIONES EN LA ADMINISTRACIÓN PÚBLICA. | as enacted, in force 1 September 2021 |
| `ley-3395-u/` | Ley 3395-U: LEY DE SENSIBILIDAD DE GÉNERO EN LOS MEDIOS DE COMUNICACIÓN. | as enacted, in force 14 July 2021 |
| `ley-3394-i/` | Ley 3394-I: ADHESION A LA LEY NACIONAL 27231 - DESARROLLO SUSTENTABLE DEL SECTOR ACUICOLA. | as enacted, in force 1 September 2021 |
| `ley-3393-a/` | Ley 3393-A: PRORROGA POR EL TERMINO DE DOS (2) AÑOS LEY Nº 2620-A. | as enacted, in force 14 July 2021 |
| `ley-3391-a/` | Ley 3391-A: BONIFICACIONES DEDICACION EXCLUSIVA, AUXILIARES DE ENFERMERIA, ESTABLECIMIENTOS SANITARIOS Y RESTO DE BONIFICACIONES INCREMENTOS DESDE ABRIL/21, AGO… | as enacted, in force 16 July 2021 |
| `ley-3390-a/` | Ley 3390-A: INCREMENTO DE LA BONIFICACION POR RIESGO DE SALUD. | as enacted, in force 14 July 2021 |
| `ley-3383-k/` | Ley 3383-K: PROCEDIMIENTO Y RÉGIMEN DE SANCIONES POR IRREGULARIDADES COMETIDAS SOBRE VIVIENDAS ADJUDICADAS POR EL IPDUV. ABROGASE LA LEY 810-A (Antes Ley 4083). | as enacted, in force 11 June 2021 |
| `ley-3381-g/` | Ley 3381-G: PROTOCOLO DE INTERVENCION PARA LOS AGENTES DE LAS FUERZAS  DE SEGURIDAD Y DE EFECTORES DE SALUD EN SITUACION DE  INTOXICACION POR CONSUMO DE SUSTANC… | as enacted, in force 11 June 2021 |
| `ley-3377-r/` | Ley 3377-R: ADHESIÓN A LA LEY 27.566- APRUEBA ACUERDO CELEBRADO EN ESCAZÚ- | as enacted, in force 11 June 2021 |
| `ley-3389-a/` | Ley 3389-A: FACULTA AL PODER EJECUTIVO A SUSCRIBIR CONTRATOS  PARA LA ADQUISICIÓN EN FORMA DIRECTA DE VACUNAS CONTRA EL COVID-19. | as enacted, in force 11 June 2021 |
| `ley-3369-a/` | Ley 3369-A: LEY 1964-F BONIFICACIÓN “ADICIONAL COMPLEMENTARIO”  EXTENSIÓN AL MINISTERIO DE PLANIFICACIÓN, ECONOMÍA E INFRAESTRUCTURA. | as enacted, in force 13 June 2021 |
| `ley-3368-a/` | Ley 3368-A: PERSONAL SUBSECRETARÍA DE INFRAESTRUCTURA ESCOLAR EXTENSIÓN BONIFICACIONES LEYES 1588-A Y 1967-A. RATIFICA DECRETO 663/21 | as enacted, in force 13 June 2021 |
| `ley-3367-a/` | Ley 3367-A: INCREMENTO EN LAS PRESTACIONES SOCIALES LEYES 1369-H – 1370-H – 1614-H. RATIFICA DECRETO 596/21 | as enacted, in force 13 June 2021 |
| `ley-3373-a/` | Ley 3373-A: MODIFICACIONES A LAS ASIGNACIONES ESPECIALES Y/O FONDO ESTÍMULO OTORGADOS POR LEYES 1118-P, 2323-A, 2394-A Y 2415-A | as enacted, in force 16 June 2021 |
| `ley-3372-a/` | Ley 3372-A: CREACIÓN DE BONIFICACIÓN ESPECIAL PARA LA SECRETARÍA DE MUNICIPIOS Y CIUDADES | as enacted, in force 16 June 2021 |
| `ley-3370-a/` | Ley 3370-A: SUMA FIJA PARA EL PERSONAL DE UNIDADES DEL MINISTERIO DE DESARROLLO SOCIAL | as enacted, in force 16 June 2021 |
| `ley-3366-a/` | Ley 3366-A: INCREMENTO EN LAS PRESTACIONES SOCIALES LEYES 1369-H - 1370-H - 1614- H  RATIFICA DECRETO 597/21 | as enacted, in force 6 June 2021 |
| `ley-3384-a/` | Ley 3384-A: ACUERDO DE REFINANCIACIÓN ANSES - PROVINCIA DEL CHACO | as enacted, in force 6 June 2021 |
| `ley-3348-g/` | Ley 3348-G: LEY EMMITA | as enacted, in force 26 May 2021 |
| `ley-3361-a/` | Ley 3361-A: INCREMENTO SALARIAL PARA EL PERSONAL DOCENTE. RATIFICA DECRETO 662/21. | as enacted, in force 23 May 2021 |
| `ley-3360-a/` | Ley 3360-A: INCREMENTO SALARIAL PARA EL PERSONAL DEL PUERTO DE BARRANQUERAS. RATIFICA DECRETO PROVINCIAL 651/21. | as enacted, in force 23 May 2021 |
| `ley-3359-j/` | Ley 3359-J: POLICÍA PROVINCIAL INCREMENTOS SALARIALES DESDE  MARZO 2021. | as enacted, in force 14 May 2021 |
| `ley-3358-a/` | Ley 3358-A: INCREMENTO SALARIAL DESDE MARZO 2021 PARA CONTADURIA GENERAL Y TESORERIA GENERAL DE LA PROVINCIA - AUTORIDADES SUPERIORES DEL PODER EJECUTIVO - PODE… | as enacted, in force 23 May 2021 |
| `ley-3357-a/` | Ley 3357-A: INCREMENTO SALARIAL DESDE MARZO 2021 PARA PODER JUDICIAL-TRIBUNAL ELECTORAL-CONSEJO DE LA MAGISTRATURA Y JURADO DE ENJUICIAMIENTO. | as enacted, in force 23 May 2021 |
| `ley-3356-a/` | Ley 3356-A: SERVICIO PENITENCIARIO PROVINCIAL. INCREMENTOS SALARIALES DESDE MARZO 2021- | as enacted, in force 23 May 2021 |
| `ley-3355-a/` | Ley 3355-A: PERSONAL DEL ESCALAFON GENERAL - LEY 196-A. INCREMENTOS SALARIALES DESDE 2020. | as enacted, in force 14 May 2021 |
| `ley-3352-a/` | Ley 3352-A: POLICIA DEL CHACO - SERVICIO PENITENCIARIO PROVINCIAL. INCREMENTOS SALARIALES DESDE MARZO 2020. | as enacted, in force 23 May 2021 |
| `ley-3353-a/` | Ley 3353-A: INCREMENTO SALARIAL JURISDICCIÓN 9-PODERJUDICIAL Y JURISDICCIÓN 17-TRIBUNAL ELECTORAL DE LA PROVINCIA DEL CHACO, 40-CONSEJO DE LA MAGISTRATURA Y JUR… | as enacted, in force 5 May 2021 |
| `ley-3350-e/` | Ley 3350-E: PERSONAL DOCENTE. INCREMENTOS DEL VALOR INDICE UNO (1). | as enacted, in force 5 May 2021 |
| `ley-3345-g/` | Ley 3345-G: DÍA PROVINCIAL DE LA CONCIENTIZACIÓN SOBRE CARDIOPATÍAS CONGÉNITAS. | as enacted, in force 5 May 2021 |
| `ley-3344-q/` | Ley 3344-Q: INCORPORA ARTICULOS A LA LEY 834-Q. | as enacted, in force 5 May 2021 |
| `ley-3341-h/` | Ley 3341-H: DIA DEL AGENCIERO Y SUBAGENCIERO | as enacted, in force 5 May 2021 |
| `ley-3340-a/` | Ley 3340-A: ADMINISTRACION PORTUARIA PUERTO BARRANQUERAS. INCREMENTO SALARIAL ADICIONAL DESDE SEPTIEMBRE 2020. | as enacted, in force 4 April 2021 |
| `ley-3339-s/` | Ley 3339-S: INSTITUCIONES DEPORTIVAS. PROTOCOLO INSTITUCIONAL PARA LA PREVENCIÓN DE VIOLENCIA, ACOSO, DISCRIMINACIÓN, GENERO Y DIVERSIDAD. | as enacted, in force 4 April 2021 |
| `ley-3338-r/` | Ley 3338-R: ADHESION A LA LEY NACIONAL Nº 27592 " LEY YOLANDA". | as enacted, in force 26 March 2021 |
| `ley-3290-g/` | Ley 3290-G: EJERCICIO DE LA OBSTETRICIA. CREA COLEGIO PUBLICO DE OBSTETRICIA. | as enacted, in force 7 February 2021 |
| `ley-3325-b/` | Ley 3325-B: JUICIOS CIVILES Y COMERCIALES POR JURADOS DEL PUEBLO DE LA PROVINCIA DEL CHACO. | as enacted, in force 12 February 2021 |
| `ley-3330-r/` | Ley 3330-R: ESTABLECE CAPACITACION OBLIGATORIA EN LOS 17 OBJETIVOS DE DESARROLLO SOSTENIBLE (ODS). | as enacted, in force 10 March 2021 |
| `ley-3331-a/` | Ley 3331-A: CREA BANCO PROVINCIAL DE TIERRAS URBANAS. | as enacted, in force 7 March 2021 |
| `ley-3334-a/` | Ley 3334-A: ACUERDO COMPROMISO ENTRE PROVINCIA DEL CHACO Y ANSES CONVENIO BILATERAL DE FINANCIAMIENTO. | as enacted, in force 22 August 2021 |
| `ley-3327-g/` | Ley 3327-G: DÌA DE LA CONCIENTIZACIÒN SOBRE LA MUERTE GESTACIONAL Y PERINATAL. | as enacted, in force 5 February 2021 |
| `ley-3313-c/` | Ley 3313-C: CAPACITACIÓN PERMANENTE EN TEMÁTICA DE LOS DERECHOS DE LAS NIÑAS, NIÑOS Y ADOLESCENTES | as enacted, in force 24 January 2021 |
| `ley-3305-f/` | Ley 3305-F: RÉGIMEN DE PROMOCIÓN DE LA ECONOMÍA DEL CONOCIMIENTO | as enacted, in force 24 January 2021 |
| `ley-3291-g/` | Ley 3291-G: VIOLENCIA OBSTETRICA | as enacted, in force 24 January 2021 |
| `ley-3328-g/` | Ley 3328-G: RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 1668 | as enacted, in force 24 January 2021 |
| `ley-3329-a/` | Ley 3329-A: ESTABLECE EN PAPELERÍA OFICIAL PARA EL AÑO 2021 LA LEYENDA "2021 -AÑO DE EL IMPENETRABLE CHAQUEÑO, DEPARTAMENTO GENERAL GÜEMES”. | as enacted, in force 22 January 2021 |
| `ley-3321-a/` | Ley 3321-A: PODER JUDICIAL: RECATEGORIZACION DEL CARGO AGENTE FISCAL. | as enacted, in force 22 January 2021 |
| `ley-3314-g/` | Ley 3314-G: PROGRAMA PROVINCIAL "NOVIEMBRE MORADO". | as enacted, in force 22 January 2021 |
| `ley-3311-r/` | Ley 3311-R: MODIFICA LA LEY 2026-R (ANTES LEY 7032) LEY DE BIOCIDAS. | as enacted, in force 22 January 2021 |
| `ley-3309-g/` | Ley 3309-G: CAMPAÑA DE INFORMACION, CONCIENTIZACION Y PREVENCION DE LA TRASMISION DEL CORONAVIRUS-COVID-19, DESTINADA A NIÑOS, NIÑAS Y ADOLESCENTES. | as enacted, in force 22 January 2021 |
| `ley-3308-g/` | Ley 3308-G: ADHIERE A LA LEY NACIONAL 27197 LUCHA CONTRA EL SEDENTARISMO. | as enacted, in force 22 January 2021 |
| `ley-3304-n/` | Ley 3304-N: REGLAMENTA LA ACTIVIDAD RENTADA DE PERSONAS CONDENADAS PRIVADAS DE SU LIBERTAD. | as enacted, in force 22 January 2021 |
| `ley-3302-a/` | Ley 3302-A: COMISION INVESTIGADORA "VERDAD Y JUSTICIA PARA MARTIRES LOPEZ". | as enacted, in force 22 January 2021 |
| `ley-3322-g/` | Ley 3322-G: REGISTROS DE EVENTOS SEGUROS EN TU GOBIERNO DIGITAL PROTOCOLO PARA EVENTOS CULTURALES y AFINES | as enacted, in force 15 January 2021 |
| `ley-3315-l/` | Ley 3315-L: RATIFICA DECRETO DEL PODER EJECUTIVO PROVINCIAL 1113/20. | as enacted, in force 15 January 2021 |
| `ley-3318-a/` | Ley 3318-A: DIRECCIÓN DE AERONÁUTICA INCREMENTO SALARIAL DESDE SEPTIEMBRE 2020 | as enacted, in force 15 January 2021 |
| `ley-3319-a/` | Ley 3319-A: ADMINISTRACIÓN PORTUARIA PUERTO DE BARRANQUERAS INCREMENTO SALARIAL DESDE SEPTIEMBRE 2020 | as enacted, in force 15 January 2021 |
| `ley-3317-a/` | Ley 3317-A: ASESORÍA GENERAL DE GOBIERNO INCREMENTO SALARIAL DESDE SEPTIEMBRE 2020 | as enacted, in force 15 January 2021 |
| `ley-3323-c/` | Ley 3323-C: LEY INTEGRAL DE MEDIACIÓN | as enacted, in force 7 April 2021 |
| `ley-3324-a/` | Ley 3324-A: ESCUELA JUDICIAL DEL CONSEJO DE LA MAGISTRATURA DE LA PROVINCIA DEL CHACO. | as enacted, in force 24 January 2021 |
| `ley-3284-f/` | Ley 3284-F: LEY DE PRESUPUESTO EJERCICIO 2021. | as enacted, in force 24 January 2021 |
| `ley-3280-a/` | Ley 3280-A: TRANSFIERE INMUEBLE A FAVOR DE LA ASOCIACION CIVIL LA FABRICA CULTURAL PARA LA CONSTRUCCION DE UN CENTRO CULTURAL. | as enacted, in force 13 January 2021 |
| `ley-3283-e/` | Ley 3283-E: PATRIMONIO HISTORICO Y CULTURAL DE LA PROVINCIA DEL CHACO A LA ESCUELA DE EDUCACION SECUNDARIA Nº 5 "DOMINGO FAUSTINO SARMIENTO" | as enacted, in force 22 February 2021 |
| `ley-3286-m/` | Ley 3286-M: EXPEDIENTE ELECTRONICO EN LA PROVINCIA DEL CHACO. | as enacted, in force 15 January 2021 |
| `ley-3289-v/` | Ley 3289-V: ADHESIÓN A LA LEY NACIONAL 27.563 DE SOSTENIMIENTO Y REACTIVACIÓN PRODUCTIVA DE LA ACTIVIDAD TURÍSTICA NACIONAL. | as enacted, in force 15 January 2021 |
| `ley-3277-a/` | Ley 3277-A: RECONOCIMIENTO DINERARIO POR REFRIGERIO POLICÍA PROVINCIAL Y SERVICIO PENITENCIARIO PROVINCIAL. | as enacted, in force 15 January 2021 |
| `ley-3281-a/` | Ley 3281-A: CONTADURIA GENERAL Y TESORERIA GENERAL DE LA PROVINCIA DEL CHACO. INCREMENTO SALARIAL DESDE SEPTIEMBRE DE 2020. | as enacted, in force 8 January 2021 |
| `ley-3278-a/` | Ley 3278-A: POLICÍA PROVINCIAL Y SERVICIO PENITENCIARIO PROVINCIAL INCREMENTO SALARIAL | as enacted, in force 13 January 2021 |
| `ley-3288-s/` | Ley 3288-S: COMPENDIO TEMATICO DE LA LEGISLACION DEL DEPORTE. | as enacted, in force 15 January 2021 |
| `ley-3292-e/` | Ley 3292-E: PROGRAMA YO JURADO. | as enacted, in force 17 January 2021 |
| `ley-3293-a/` | Ley 3293-A: EXPROPIA INMUEBLE | as enacted, in force 15 January 2021 |
| `ley-3294-r/` | Ley 3294-R: EMERGENCIA AMBIENTAL DEL ECOSISTEMA DEL RÍO PARANÁ. | as enacted, in force 17 January 2021 |
| `ley-3297-h/` | Ley 3297-H: MODIFICA ARTÍCULO 84 LEY 800-H. | as enacted, in force 13 January 2021 |
| `ley-3298-g/` | Ley 3298-G: SEMANA DE CONCIENTIZACIÓN DE LA NO VIOLENCIA CONTRA LA MUJER | as enacted, in force 15 January 2021 |
| `ley-3300-i/` | Ley 3300-I: PRORROGA LA LEY 937-I (ANTES LEY 4453) | as enacted, in force 15 January 2021 |
| `ley-3301-g/` | Ley 3301-G: CAMPAÑA DE CONCIENTIZACIÓN Y DIFUSIÓN DE LA LEY DE RESPETO A LOS TIEMPOS DE LA VÍCTIMA DE LOS DELITOS CONTRA  LA INTEGRIDAD SEXUAL DE MENORES | as enacted, in force 15 January 2021 |
| `ley-3303-x/` | Ley 3303-X: APRUEBA  EL ACUERDO DENOMINADO CONSENSO FISCAL AÑO 2020 | as enacted, in force 8 January 2021 |
| `ley-3265-i/` | Ley 3265-I: CULTIVOS HIDROPÓNICOS. | as enacted, in force 8 January 2021 |
| `ley-3257-a/` | Ley 3257-A: PRORROGA LA LEY 2557-A (ANTES LEY 7948). | as enacted, in force 8 January 2021 |
| `ley-3264-b/` | Ley 3264-B: SISTEMA PROVINCIAL PARA LA PREVENCION DE LA TORTURA Y OTROS TRATOS O PENAS CRUELES, INHUMANOS O DEGRADANTES. | as enacted, in force 17 January 2021 |
| `ley-3255-a/` | Ley 3255-A: REINSTAURA LA VIGENCIA DE LA  LEY 2470-A. | as enacted, in force 8 January 2021 |
| `ley-3251-a/` | Ley 3251-A: POLICÍA PROVINCIAL Y SERVICIO PENITENCIARIO PROVINCIAL ELIMINACIÓN SUPLEMENTO POR RECARGO DE SERVICIO ESCALA SALARIAL ESCALAFÓN SEGURIDAD DESDE SEPT… | as enacted, in force 8 January 2021 |
| `ley-3268-k/` | Ley 3268-K: ETIQUETADO DE EFICIENCIA  ENERGÉTICA DE INMUEBLES DESTINADOS A VIVIENDA. | as enacted, in force 22 August 2021 |
| `ley-3273-a/` | Ley 3273-A: INSTITUYE EL DÍA DE LA MUJER POLICÍA CHAQUEÑA. | as enacted, in force 5 February 2021 |
| `ley-3271-g/` | Ley 3271-G: CONTENCIÓN Y ACOMPAÑAMIENTO EMOCIONAL MEDIANTE ASISTENCIA  TELEFÓNICA O VIRTUAL. | as enacted, in force 8 January 2021 |
| `ley-3270-e/` | Ley 3270-E: PROMOCIÓN Y PARTICIPACIÓN DE ARTISTAS MUSICALES LOCALES. | as enacted, in force 8 January 2021 |
| `ley-3269-g/` | Ley 3269-G: DÍA DEL VACUNADOR  Y LA VACUNADORA CHAQUEÑOS. | as enacted, in force 8 January 2021 |
| `ley-3266-i/` | Ley 3266-I: ADHESIÓN AL DECRETO NACIONAL 756/2020. | as enacted, in force 8 January 2021 |
| `ley-3254-a/` | Ley 3254-A: PERSONAL DEL ESCALAFÓN GENERAL - LEY 196-A (ANTES LEY 1276) INCREMENTO SALARIAL DESDE SEPTIEMBRE 2020. | as enacted, in force 20 August 2021 |
| `ley-3250-a/` | Ley 3250-A: TRIBUNAL DE CUENTAS INCREMENTO SALARIAL DESDE SEPTIEMBRE 2020. | as enacted, in force 20 August 2021 |
| `ley-3249-a/` | Ley 3249-A: INSTITUTO DEL DEFENSOR DEL PUEBLO. INCREMENTO SALARIAL VIGENTE DESDE SEPTIEMBRE DE 2020. | as enacted, in force 20 August 2021 |
| `ley-3259-a/` | Ley 3259-A: RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 1466. | as enacted, in force 22 August 2021 |
| `ley-3262-a/` | Ley 3262-A: TRIBUNAL DE CUENTAS. ADICIONAL REMUNERATIVO Y NO BONIFICABLE DESDE AGOSTO 2019. | as enacted, in force 22 August 2021 |
| `ley-3261-h/` | Ley 3261-H: PRESTACIONES SOCIALES LEYES 1369-H Y 1370-H. INCREMENTO. | as enacted, in force 22 August 2021 |
| `ley-3248-a/` | Ley 3248-A: FISCALÍA DE INVESTIGACIONES ADMINISTRATIVAS INCREMENTO SALARIAL DESDE SEPTIEMBRE DE 2020. | as enacted, in force 20 August 2021 |
| `ley-3258-a/` | Ley 3258-A: RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 1520. | as enacted, in force 22 August 2021 |
| `ley-3245-a/` | Ley 3245-A: PANDEMIA COVID-19 RATIFICA EL DECRETO 1314/20 DISTANCIAMIENTO SOCIAL, PREVENTIVO Y OBLIGATORIO  OTRAS MEDIDAS. | as enacted, in force 20 August 2021 |
| `ley-3246-a/` | Ley 3246-A: AUTORIDADES SUPERIORES DEL PODER EJECUTIVO Y DE ORGANISMOS AUTARQUICOS Y DESCENTRALIZADOS. INCREMENTO SALARIAL DESDE SEPTIEMBRE DE 2020. | as enacted, in force 20 August 2021 |
| `ley-3260-f/` | Ley 3260-F: ESCALAFÓN GENERAL INCREMENTO SALARIAL DESDE MARZO 2020 | as enacted, in force 22 August 2021 |
| `ley-3256-f/` | Ley 3256-F: EMERGENCIA SANITARIA POR PANDEMIA COVID-19 CONTRATO DE LOCACIÓN DE SERVICIO EN SALUD PÚBLICA - . | as enacted, in force 20 August 2021 |
| `ley-3252-a/` | Ley 3252-A: AUTORIDADES SUPERIORES ASESORIA GENERAL DE GOBIERNO. INCREMENTO SALARIAL MARZO 2020. | as enacted, in force 20 August 2021 |
| `ley-3247-a/` | Ley 3247-A: ÓRGANO RECTOR DEL SISTEMA PRESUPUESTARIO. INCREMENTO SALARIAL DESDE SEPTIEMBRE DE 2020. | as enacted, in force 20 August 2021 |
| `ley-3232-e/` | Ley 3232-E: DEPOSITO LEGAL BIBLIOGRAFICO PROVINCIAL | as enacted, in force 8 January 2021 |
| `ley-3235-a/` | Ley 3235-A: DESESCALDA DEL AISLAMIENTO SOCIAL PREVENTIVO Y OBLIGATORIO POR LA PANDEMIA COVID-19 FUNCIONAMIENTO DE GUARDERÍAS INFANTILES Y JARDINES MATERNALES. | as enacted, in force 8 January 2021 |
| `ley-3231-a/` | Ley 3231-A: PERSONAL DOCENTE-INCREMENTO DEL VALOR INDICE UNO (1). | as enacted, in force 8 January 2021 |
| `ley-3233-a/` | Ley 3233-A: RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 1068/20. | as enacted, in force 8 January 2021 |
| `ley-3234-a/` | Ley 3234-A: RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 1207/2020. | as enacted, in force 8 January 2021 |
| `ley-3236-a/` | Ley 3236-A: RATIFICA EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 1429/2020. | as enacted, in force 8 January 2021 |
| `ley-3237-a/` | Ley 3237-A: CONDONACIÓN DE DEUDA DE PRODUCTORES AGROPECUARIOS. | as enacted, in force 8 January 2021 |
| `ley-3238-a/` | Ley 3238-A: REINSTAURA LEY 3136-A. | as enacted, in force 8 January 2021 |
| `ley-3242-g/` | Ley 3242-G: USO DE MASCARILLA, BARBIJOS TRANSPARENTES EN OFICINAS PÚBLICAS . | as enacted, in force 8 January 2021 |
| `ley-3244-w/` | Ley 3244-W: CAPACITACION SOBRE DERECHOS INDIGENAS PARA EMPLEADOS DE LA ADMINISTRACION PUBLICA PROVINCIAL. | as enacted, in force 8 January 2021 |
| `ley-3243-g/` | Ley 3243-G: UNIDADES DE ATENCIÓN GERIÁTRICA. | as enacted, in force 8 January 2021 |
| `ley-3229-a/` | Ley 3229-A: REINSTAURA LA LEY 2828-A. | as enacted, in force 8 January 2021 |
| `ley-3228-a/` | Ley 3228-A: AUTORIZA AL INSTITUTO DE TIERRAS FISCALES A ESCRITURAR INMUEBLE FISCAL A FAVOR DE LA UNIVERSIDAD NACIONAL DEL NORDESTE. | as enacted, in force 8 January 2021 |
| `ley-3226-i/` | Ley 3226-I: OBSERVATORIO PARA LAS PEQUEÑAS Y MEDIANAS EMPRESAS -OPyME-. | as enacted, in force 8 January 2021 |
| `ley-3225-r/` | Ley 3225-R: PROGRAMA PARA REFORESTAR “UNA VIDA, DIEZ ÁRBOLES”. | as enacted, in force 8 January 2021 |
| `ley-3224-f/` | Ley 3224-F: CÓDIGO TRIBUTARIO PROVINCIAL - MODIFICACIONES. | current text only, as of 28 April 2021 |
| `ley-3223-a/` | Ley 3223-A: ADHESIÓN A L.N. 27.553 RECETAS ELECTRÓNICAS O DIGITALES. | as enacted, in force 13 January 2021 |
| `ley-3220-g/` | Ley 3220-G: ADHIERE A LA LEY NACIONAL 27.552 -LUCHA CONTRA LA ENFERMEDAD DE FIDROSIS QUÍSTICA DE PÁNCREAS O MUCOVISCIDOSIS. | as enacted, in force 8 January 2021 |
| `ley-3219-a/` | Ley 3219-A: RATIFICA CONVENIOS ENTRE LAS PROVINCIAS DE CHACO, SANTA FE Y SANTIAGO DEL ESTERO. | as enacted, in force 13 January 2021 |
| `ley-3204-f/` | Ley 3204-F: CONTABILIDAD GUBERNAMENTAL. PRESENTACION DE ESTADOS CONTABLES DEL SECTOR PUBLICO. | as enacted, in force 12 March 2021 |
| `ley-3217-a/` | Ley 3217-A: REINSTAURA LA LEY 2045-A (ANTES LEY 7082). | as enacted, in force 17 January 2021 |
| `ley-3216-a/` | Ley 3216-A: REINSTAURA LA LEY 2351-A (ANTES LEY 7639). | as enacted, in force 17 January 2021 |
| `ley-3215-a/` | Ley 3215-A: REINSTAURA LA LEY 1492-A (ANTES LEY 5796). | as enacted, in force 17 January 2021 |
| `ley-3214-a/` | Ley 3214-A: REINSTAURA LA LEY Nº 2619-A. | as enacted, in force 17 January 2021 |
| `ley-3212-c/` | Ley 3212-C: CONCIENTIZACION, PREVENCION Y PROMOCION DE GROOMING. ADHIERE LA PROVINCIA DEL CHACO A LA LEY NACIONAL Nº 27458. | as enacted, in force 17 January 2021 |
| `ley-3210-f/` | Ley 3210-F: REGIMEN UNICO DE REPARACION ECONOMICA - COVID 19. | as enacted, in force 17 January 2021 |
| `ley-3209-g/` | Ley 3209-G: PROGRAMA DE FORMACION DE PROMOTORAS Y PROMOTORES TERRITORIALES EN GENERO Y DIVERSIDADES CONTRA LA VIOLENCIA SEXISTA - "PRO.TE.GEN." | as enacted, in force 17 January 2021 |
| `ley-3203-a/` | Ley 3203-A: SIMPLIFICACION Y MODERNIZACION DE LA ADMINISTRACION. ADHIERESE LA PROVINCIA AL CAPITULO II DE LA LEY NACIONAL Nº 27.466. | as enacted, in force 17 January 2021 |
| `ley-3201-k/` | Ley 3201-K: EMERGENCIA HABITACIONAL Y DE INFRAESTRUCTURA SOCIAL BASICA. | as enacted, in force 17 January 2021 |
| `ley-3177-i/` | Ley 3177-I: MODIFICASE EL ARTÍCULO 1° DE LA LEY 737-I. | as enacted, in force 16 October 2020 |
| `ley-3189-a/` | Ley 3189-A: AISLAMIENTO SOCIAL, PREVENTIVO Y OBLIGATORIO ADHESIÒN  AL DECRETO DEL PODER  EJECUTIVO NACIONAL 641/20. | as enacted, in force 28 October 2020 |
| `ley-3199-a/` | Ley 3199-A: PRORROGA LEY Nº 2476-A (ANTES LEY 7834). | as enacted, in force 28 October 2020 |
| `ley-3198-p/` | Ley 3198-P: AMPLIA EJIDO MUNICIPAL DE LA CIUDAD DE LAS BREÑAS. | as enacted, in force 28 October 2020 |
| `ley-3197-r/` | Ley 3197-R: CARTELERIA INFORMATIVA Y EXPLICATIVA RESPECTO DEL PLAZO DE DEGRADACION DE LOS MATERIALES. | as enacted, in force 1 November 2020 |
| `ley-3196-g/` | Ley 3196-G: PROTOCOLO DE CONTENCION PSICOAFECTIVA ANTE PANDEMIA POR CORONAVIRUS COVID-19. | as enacted, in force 30 October 2020 |
| `ley-3195-g/` | Ley 3195-G: ADHESION A LA LEY NACIONAL 27.554. CAMPAÑA NACIONAL PARA LA DONACION DE PLASMA SANGUINEO DE PACIENTES RECUPERADOS DE COVID-19 | as enacted, in force 30 October 2020 |
| `ley-3200-f/` | Ley 3200-F: CONDICIONES PARA EL INGRESO DE NIÑAS, NIÑOS y ADOLESCENTES A ESTABLECIMIENTOS QUE PRESTEN SERVICIOS DE ALOJAMIENTO | as enacted, in force 17 January 2021 |
| `ley-3190-j/` | Ley 3190-J: POLICIA DE LA PROVINCIA DEL CHACO. NUEVAS DIRECCIONES GENERALES | as enacted, in force 23 October 2020 |
| `ley-3180-g/` | Ley 3180-G: REGULACION DEL EJERCICO PROFESIONAL DE ACOMPAÑANTES TERAPÉUTICOS | as enacted, in force 4 April 2021 |
| `ley-3181-e/` | Ley 3181-E: LEY DE PROMOCION DE ENTORNO ESCOLAR SALUDABLE. | as enacted, in force 16 October 2020 |
| `ley-3174-c/` | Ley 3174-C: DEL VOLUNTARIADO SOCIAL. | as enacted, in force 30 September 2020 |
| `ley-3182-g/` | Ley 3182-G: DECLARAR LA EMERGENCIA SOCIAL POR LA PANDEMIA DEL COVID-19. | as enacted, in force 30 September 2020 |
| `ley-3183-j/` | Ley 3183-J: MODIFICA CODIGO DE FALTAS - QUEMA DE VEGETACION. | as enacted, in force 16 October 2020 |
| `ley-3184-e/` | Ley 3184-E: DEFINICION DE ANTISEMITISMO | as enacted, in force 16 October 2020 |
| `ley-3185-a/` | Ley 3185-A: PRORROGA POR EL TERMINO DE DOS (2) AÑOS LO PREVISTO EN EL ARTICULO 1 DE LA LEY 2024-K (ANTES LEY 7030) | as enacted, in force 16 October 2020 |
| `ley-3188-a/` | Ley 3188-A: REINSTÁURASE POR EL TERMINO DE DOS (2) AÑOS LA LEY 2848-A. | as enacted, in force 30 September 2020 |
| `ley-3186-a/` | Ley 3186-A: PRORROGA POR EL TERMINO DE DOS (2) AÑOS LA LEY 2057-A (ANTES LEY 7115). | as enacted, in force 30 September 2020 |
| `ley-3179-a/` | Ley 3179-A: DERECHO A ACCESO PARA CONOCER LA IDENTIDAD  BIOLOGICA O DE ORIGEN. | as enacted, in force 30 September 2020 |
| `ley-3176-l/` | Ley 3176-L: LEY 2335-L - READECUACIÓN DE HORAS CÁTEDRAS OCUPADAS- AFECTACIÓN A NUEVAS ESTRUCTURAS CURRICULARES. | as enacted, in force 16 October 2020 |
| `ley-3175-g/` | Ley 3175-G: LEY 3155-G - PROTOCOLO PARA LA UTILIZACIÓN DE ESTABLECIMIENTOS NO HOSPITALARIOS COMO DISPOSITIVOS DE ATENCIÓN DOMICILIARIA DE PACIENTES COVID-19 CON… | as enacted, in force 30 September 2020 |
| `ley-3168-f/` | Ley 3168-F: NOMENCLADOR DE ACTIVIADES ECONOMICAS. MODIFICACIONES A LEY Nº 299-F (ANTE LEY 2071). | as enacted, in force 15 November 2020 |
| `ley-3164-a/` | Ley 3164-A: PLAN DE DESESCALADA EN EL MARCO DEL AISLAMIENTO SOCIAL PREVENTIVO Y OBLIGATORIO POR LA PANDEMINA COVID-19. | as enacted, in force 2 September 2020 |
| `ley-3171-g/` | Ley 3171-G: IMPLEMENTA EN FORMA OBLIGATORIA LA INSTALACION DE LAVAMANOS Y DISPENSADORES DE ALCOHOL EN GEL O GEL ANTIBACTERIAL EN TODOS LOS LOCALES CON ATENCION … | as enacted, in force 17 January 2021 |
| `ley-3165-f/` | Ley 3165-F: TRANSFERENCIA  O AFECTACION DE BIENES INMUEBLES. | as enacted, in force 18 October 2020 |
| `ley-3161-w/` | Ley 3161-W: PAUTAS PARA LA ATENCION DE PUEBLOS Y COMUNIDADES INDIGENAS ANTE LA EMERGENCIA SANITARIA GENERADA POR LA PANDEMIA DEL COVID-19. | as enacted, in force 22 August 2021 |
| `ley-3166-f/` | Ley 3166-F: EMERGENCIA ECONOMICA Y FINANCIERA. | as enacted, in force 30 August 2020 |
| `ley-3160-g/` | Ley 3160-G: USO OBLIGATORIO DE BARBIJOS O MASCARILLAS DE PROTECCION FACIL. | as enacted, in force 2 September 2020 |
| `ley-3153-a/` | Ley 3153-A: RATIFICACIÓN DECRETO PROVINCIAL 702/20-SUSPENDE MEDIDAS APRUEBA DISPOSICIONES EN EL MARCO LA PANDEMIA COVID-19. | as enacted, in force 30 August 2020 |
| `ley-3152-g/` | Ley 3152-G: PROGRAMA DE PROMOCIÓN Y CONCIENTIZACIÓN SOBRE LA IMPORTANCIA SANITARIA DE LA DONACIÓN DE PLASMA DE PACIENTES RECUPERADOS DE COVID-19. | as enacted, in force 21 August 2020 |
| `ley-3151-d/` | Ley 3151-D: ADHESIÓN A LA LEY NACIONAL DE GÓNDOLA 27545. | as enacted, in force 21 August 2020 |
| `ley-3150-a/` | Ley 3150-A: INSTITUTO PROVINCIAL DE INFORMACIÓN ESTADÍSTICA Y TERRITORIAL. DEROGA  LA  LEY 1775-E.. | as enacted, in force 23 August 2020 |
| `ley-3149-r/` | Ley 3149-R: DESIGNACION VIA REGLAMENTARIA DE LA AUTORIDAD DE APLICACION DE LA LEY 2877-R -REGIMEN DE REGULACION DE PROMOCION PARA LA PRODUCCION Y USO SUSTENTABL… | as enacted, in force 21 August 2020 |
| `ley-3158-g/` | Ley 3158-G: FONDO DE RECUPERO DE GASTOS. DEROGA LEY 644.H (ANTES LEYES 3517-3842). | as enacted, in force 4 September 2020 |
| `ley-3148-g/` | Ley 3148-G: ADHESION A LA LEY NACIONAL 27548 -PROGRAMA DE PROTECCION AL PERSONAL DE LA SALUD ANTE LA PANDEMIA DE CORONAVIRUS COVID-19. | as enacted, in force 21 August 2020 |
| `ley-3147-f/` | Ley 3147-F: RATÍFICASE EL DECRETO 677/20. | as enacted, in force 21 August 2020 |
| `ley-3138-a/` | Ley 3138-A: FLEXIBILIZACION DE PAGOS DE ALQUILERES EN EL MARCO DE LA EMERGENCIA SANITARIA POR LA PANDEMIA COVID-19. | as enacted, in force 21 August 2020 |
| `ley-3115-a/` | Ley 3115-A: REINSTAURA LA LEY 2110-A (ANTES LEY 7212) | as enacted, in force 23 August 2020 |
| `ley-3144-i/` | Ley 3144-I: FONDO PARA LA PROMOCIÓN Y RADICACIÓN DE EMPRENDIMIENTOS INDUSTRIALES Y LA GENERACIÓN Y SOSTENIMIENTO DEL EMPLEO. | as enacted, in force 23 August 2020 |
| `ley-3143-i/` | Ley 3143-I: INCORPORA ACTIVIDAD PRODUCTIVA INDUSTRIAL. | as enacted, in force 23 August 2020 |
| `ley-3142-f/` | Ley 3142-F: CREACIÓN DE UN RÉGIMEN DE INCENTIVOS FISCALES . | as enacted, in force 23 August 2020 |
| `ley-3141-t/` | Ley 3141-T: EMERGENCIA DEL SECTOR DEL TRANSPORTE AUTOMOTOR DE PASAJEROS, EN LA MODALIDAD DE REMIS, TAXIS Y/O RADIO TAXIS. | as enacted, in force 23 August 2020 |
| `ley-3140-f/` | Ley 3140-F: MODIFICA LEY 83-F (ANTES DECRETO-LEY 2444/62) CÓDIGO TRIBUTARIO PROVINCIAL Y MODIFICA LEY 299-F. | as enacted, in force 23 August 2020 |
| `ley-3124-e/` | Ley 3124-E: REPARACION HISTORICA SIMBOLICA PARA LA SEÑORA ROSA GRILO | as enacted, in force 27 May 2020 |
| `ley-3139-s/` | Ley 3139-S: EMERGENCIA SOCIOECONOMICA  DE CLUBES DEPORTIVOS DE LA PROVINCIA DEL CHACO. | as enacted, in force 30 August 2020 |
| `ley-3134-i/` | Ley 3134-I: RATIFICA DECRETO DEL PODER EJECUTIVO PROVINCIAL 469/2020 | as enacted, in force 29 May 2020 |
| `ley-3137-f/` | Ley 3137-F: BANCARIZACIÓN ADMINISTRACIÓN DE INMUEBLES. | as enacted, in force 21 August 2020 |
| `ley-3133-g/` | Ley 3133-G: RATIFICA EL DECRETO 540/2020 -PROTOCOLOS DE ACTUACIÓN SOBRE MEDIDAS GENERALES, CLASIFICACIÓN DE LOCALIDADES, LOCALIDADES CRÍTICAS Y LOCALIDADES NO C… | as enacted, in force 29 May 2020 |
| `ley-3126-a/` | Ley 3126-A: LEY 3126 - A  EMERGENCIA SANITARIA POR CORONAVIRUS - COVID 19 | as enacted, in force 29 May 2020 |
| `ley-3125-a/` | Ley 3125-A: EMERGENCIA SANITARIA POR CORONA VIRUS -COVID 19 - PROTOCOLO UNIFICADO DE ACTUACIÓN | as enacted, in force 7 June 2020 |
| `ley-3131-f/` | Ley 3131-F: RATIFÍCASE EL DECRETO DEL PODER EJECUTIVO PROVINCIAL 495 DE FECHA 13 DE ABRIL DE 2020. | as enacted, in force 17 May 2020 |
| `ley-3127-f/` | Ley 3127-F: BONIFICACIÓN DEL IMPUESTO SOBRE LOS INGRESOS BRUTOS. MODIFICA ARTICULOS LEY 3118-F. | as enacted, in force 17 May 2020 |
| `ley-3123-a/` | Ley 3123-A: LICENCIA EXCEPCIONAL POR CORONAVIRUS PARA EL SECTOR PÚBLICO. | as enacted, in force 29 March 2020 |
| `ley-3117-n/` | Ley 3117-N: ADHIERE L.N. 27452 - REPARACIÓN ECONÓMICA P/ NIÑAS, NIÑOS Y ADOLESC. VICTIMAS DE FEMICIDIO. | as enacted, in force 23 August 2020 |
| `ley-3122-a/` | Ley 3122-A: REINSTAURA POR EL TÉRMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2477-A (ANTES LEY 7835) | as enacted, in force 23 August 2020 |
| `ley-3116-g/` | Ley 3116-G: ADHESIÓN L.N. 27.517 - DÍA NACIONAL DEL SÍNDROME DE ASPERGER | as enacted, in force 23 August 2020 |
| `ley-3118-f/` | Ley 3118-F: REGIMEN DE REGULARIZACION EXCEPCIONAL DE OBLIGACIONES TRIBUTARIAS. | as enacted, in force 22 March 2020 |
| `ley-3113-e/` | Ley 3113-E: CREACION Y CONVOCATORIA AL CONGRESO PEDAGOGICO PROVINCIAL "LA EDUCACIÒN DEL S. XXI" | as enacted, in force 12 January 2020 |
| `ley-3112-x/` | Ley 3112-X: APRUEBA  EL ACUERDO DENOMINADO CONSENSO FISCAL AÑO 2019.- | as enacted, in force 12 January 2020 |
| `ley-3109-a/` | Ley 3109-A: CREA LA "COMISIÓN PARLAMENTARIA DE CONDONACIÓN Y/O REFINANCIACIÓN DE DEUDA DE PRODUCTORES AGROPECUARIOS". | as enacted, in force 9 October 2020 |
| `ley-3110-a/` | Ley 3110-A: PRORROGA HASTA EL 30 DE JUNIO  DE 2020 LA VIGENCIA DE LA LEY 2425-F(ANTES LEY 7751) | as enacted, in force 23 February 2020 |
| `ley-3102-d/` | Ley 3102-D: CLASIFICACIÓN, CATEGORIZACIÓN, INSCRIPCIÓN Y CONTROL DE LA INDUSTRIA HOTELERA - GASTRONÓMICA | as enacted, in force 8 January 2020 |
| `ley-3105-t/` | Ley 3105-T: ENTE REGULADOR DE TRANSPORTE (ENRETRA). | current text only, as of 19 February 2020 |
| `ley-3103-h/` | Ley 3103-H: ASIGNACIÓN ESPECIAL COMPLEMENTARIA LEY 2017-H. | as enacted, in force 25 December 2019 |
| `ley-3100-w/` | Ley 3100-W: CENSO PROVINCIAL DE PUEBLOS ORIGINARIOS | as enacted, in force 29 December 2019 |
| `ley-3092-b/` | Ley 3092-B: DIGESTO JURIDICO. CONSOLIDAR DESDE EL 01/01/2018 HASTA EL 31/12/2018. | current text only, as of 23 September 2024 |
| `ley-3084-a/` | Ley 3084-A: BONIFICACIÓN ESPECIAL EXCLUSIVA PARA EL PERSONAL DEL IPDUV. | as enacted, in force 25 December 2019 |
| `ley-3083-a/` | Ley 3083-A: ASIGNACIÓN MENSUAL ESPECIAL "ESTÍMULO" PERSONAL IPDUV. | as enacted, in force 25 December 2019 |
| `ley-3076-m/` | Ley 3076-M: HABILITACIÓN PUBLICACIÓN EDICTOS, CONVOCATORIAS, CONCURSOS Y LICITACIONES. | as enacted, in force 18 December 2019 |
| `ley-3074-g/` | Ley 3074-G: INFORMACIÓN DE SERVICIOS DE INTERNACIÓN DOMICILIARIA O CUIDADO DOMICILIARIO EN LA PCIA. | as enacted, in force 30 September 2020 |
| `ley-3082-e/` | Ley 3082-E: COMEDORES ESCOLARES PROGRAMA ALIMENTARIO FONDO ESPECIAL. | as enacted, in force 18 December 2019 |
| `ley-3081-a/` | Ley 3081-A: EXPROPIACION Y TRANSFERENCIA INMUEBLE P/SANTUARIO ANIMAL "OSVALDO Y LILIANA VIGNAU". | as enacted, in force 18 December 2019 |
| `ley-3079-g/` | Ley 3079-G: INSTALACIÓN DEL DESFIBRILADOR EXTERNO AUTOMÁTICO (DEA) EN ESTABLECIMIENTOS PÚBLICOS. | as enacted, in force 18 December 2020 |
| `ley-3078-g/` | Ley 3078-G: ADHESIÓN L.N.27.159 - MUERTE SÚBITA - SISTEMA DE PREVENCIÓN INTEGRAL. | as enacted, in force 18 December 2019 |
| `ley-3077-g/` | Ley 3077-G: SERVICIO DE ASISTENCIA A PERSONAS CON DISCAPACIDAD EN LOCALES COMERCIALES. | as enacted, in force 18 December 2019 |
| `ley-3073-g/` | Ley 3073-G: PROGRAMA DE REPARACIÓN ESTÉTICA PARA PACIENTES CON TRATAMIENTO ONCOLÓGICOS. | as enacted, in force 8 December 2019 |
| `ley-3071-e/` | Ley 3071-E: ENSEÑANZA EN FOLCLORE EN LOS NIVELES Y MODALIDADES DEL SISTEMA EDUCATIVO PROVINCIAL. | as enacted, in force 8 December 2019 |
| `ley-3067-g/` | Ley 3067-G: ADHESIÓN L.N.25.989 - RÉGIMEN ESPECIAL PARA LA DONACIONES DE ALIMENTOS. | as enacted, in force 13 November 2019 |
| `ley-3066-a/` | Ley 3066-A: REINSTAURA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2272-A (ANTES LEY 7521). | as enacted, in force 13 November 2019 |
| `ley-3063-a/` | Ley 3063-A: DEROGA LA LEY 2259-K (ANTES LEY 7504). | as enacted, in force 3 November 2019 |
| `ley-3062-g/` | Ley 3062-G: PROGRAMA DE PROFESIONALIZACIÓN DE AUXILIARES DE ENFERMERÍA. | as enacted, in force 21 August 2020 |
| `ley-3061-a/` | Ley 3061-A: CREA  DEFENSORAS OFICIALES 8 Y 9. EN PRIMERA CIRCUNSCRIPCIÓN JUDICIAL. | as enacted, in force 3 November 2019 |
| `ley-3060-v/` | Ley 3060-V: ESTABLECE EL RÉGIMEN DE FOMENTO Y TUTORÍA DEL TURISMO. | as enacted, in force 3 November 2019 |
| `ley-3056-g/` | Ley 3056-G: EJERCICIO PROFESIONAL DE LOS TÉCNICO DE LABORATORIO. | as enacted, in force 3 November 2019 |
| `ley-3055-a/` | Ley 3055-A: ADICIONAL POR TAREA ESPECIFICA E INCOMPATIBILIDAD PERSONAL TRIBUNAL DE CUENTAS. | as enacted, in force 1 November 2019 |
| `ley-3053-a/` | Ley 3053-A: DÉBITO AUTOMÁTICO DE CUOTAS DEL IPDUV. | as enacted, in force 27 October 2019 |
| `ley-3043-e/` | Ley 3043-E: ADHESIÓN L.N. Nº 27.131 - DÍA NACIONAL POLITÓLOGO/A. | as enacted, in force 9 October 2019 |
| `ley-3041-e/` | Ley 3041-E: ADHESIÓN L.N 26801 - CREACIÓN DEL INSTITUTO NACIONAL DE LA MÚSICA. | as enacted, in force 11 October 2019 |
| `ley-3040-h/` | Ley 3040-H: MODIFICA EL ARTICULO 17 DE LA LEY 1084 -H  (ANTES LEY 4768). | as enacted, in force 9 October 2019 |
| `ley-3038-k/` | Ley 3038-K: INSTITUYE EN LA PROVINCIA DEL CHACO EL BANCO ROJO. | as enacted, in force 9 October 2019 |
| `ley-3037-g/` | Ley 3037-G: CREA CONSEJO ASESOR DE POLÍTICAS RELACIONADAS AL CANNABIS MEDICINAL | as enacted, in force 24 January 2021 |
| `ley-3036-g/` | Ley 3036-G: RÉGIMEN DE APADRINAMIENTO DE ENTIDADES VINCULADAS A LA SALUD. | as enacted, in force 6 October 2019 |
| `ley-3035-t/` | Ley 3035-T: RESTABLECE VIGENCIA DE EMERGENCIA DEL SISTEMA PCIAL- DE TRANSPORTE PÚBLICO DE PASAJEROS-. | as enacted, in force 6 October 2019 |
| `ley-3032-a/` | Ley 3032-A: INCREMENTA REMUNERACIONES DEL PERSONAL LEGISLATIVO- | as enacted, in force 4 October 2019 |
| `ley-3031-a/` | Ley 3031-A: INCREMENTA BONIFICACIÓN POR TITULO PERSONAL LEGISLATIVO. | as enacted, in force 4 October 2019 |
| `ley-3025-g/` | Ley 3025-G: EMERGENCIA SOCIAL POR VIOLENCIA DE GÉNERO. | as enacted, in force 2 August 2019 |
| `ley-3024-e/` | Ley 3024-E: DECLARA PATRIMONIO CULTURAL VIVIENTE A ROSA GRILO. | as enacted, in force 2 August 2019 |
| `ley-3023-g/` | Ley 3023-G: DECLARA EMERGENCIA DE ABUSO SEXUAL Y EMBARAZOS FORZADOS DE NIÑAS, NIÑOS Y ADOLESCENTES. | as enacted, in force 25 December 2019 |
| `ley-3021-w/` | Ley 3021-W: REGISTRO DE ARTESANOS INDIGENAS. | as enacted, in force 2 August 2019 |
| `ley-3022-a/` | Ley 3022-A: MODIFICA EL ARTÍCULO 1º DE LA LEY 2846-A. | as enacted, in force 31 July 2019 |
| `ley-3015-s/` | Ley 3015-S: DECLARA "CAPITAL PCIAL. DEL VOLEY ADAPTADO P/ ADULTOS MAYORES (NEWCOM)"  A LA LEONESA. | as enacted, in force 31 July 2019 |
| `ley-3020-p/` | Ley 3020-P: HOMENAJE POST MORTEM A LOS VETERANOS DE GUERRA DE MALVINAS - ABROGUESE LEY 1441-P (ANTES 5686). | as enacted, in force 31 July 2019 |
| `ley-3014-a/` | Ley 3014-A: PRORROGA POR EL TÉRMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2620-A. | as enacted, in force 31 July 2019 |
| `ley-3013-e/` | Ley 3013-E: INSTITÚYESE EL DIA 3 DE JUNIO DÍA PCIAL. DE LA NO VIOLENCIA CONTRA LA MUJER. | as enacted, in force 14 July 2019 |
| `ley-3012-i/` | Ley 3012-I: ENLACE WEB A SUBSECRETARÍA DE DEFENSA AL CONSUMIDOR. | as enacted, in force 14 July 2019 |
| `ley-3011-f/` | Ley 3011-F: ADHESIÓN L.N. 27.467 - PRESUPUESTO NACIONAL AÑO 2019. | as enacted, in force 3 July 2019 |
| `ley-3010-t/` | Ley 3010-T: ADHESIÓN L.N. 27445 Y MODIFICA ANEXO A DE LA LEY 949 -T (ANTES LEY 4488). | as enacted, in force 14 July 2019 |
| `ley-3009-t/` | Ley 3009-T: ADHESIÓN L.N. 27.445  - MODIFICA ANEXO A LEY 1684-T (ANTES LEY 6241). | as enacted, in force 14 July 2019 |
| `ley-3006-f/` | Ley 3006-F: LEY DE CRÉDITO PÚBLICO | as enacted, in force 19 June 2019 |
| `ley-2998-g/` | Ley 2998-G: REGIMEN DE SPONSORIZACIÓN  Y TUTORÍA PARA PERSONAS CON DISCAPACIDAD. | as enacted, in force 16 June 2019 |
| `ley-3004-f/` | Ley 3004-F: MODIFICA LOS ARTÍCULOS 1º, 5º Y 9º DE LA LEY 2924-F Y RESTABLECE LA VIGENCIA. | as enacted, in force 7 June 2019 |
| `ley-3003-r/` | Ley 3003-R: SUSPENSIÓN DE RECLAMOS FISCALES Y MANDAMIENTOS EN JUICIOS DE EJECUCIÓN DE SENTENCIAS POR EMERGENCIA AGROPECUARIA | as enacted, in force 16 June 2019 |
| `ley-3002-f/` | Ley 3002-F: PROGRAMA PCIAL. DE FINANC. DE PROYECTOS PROD. P/EL DESARROLLO DE LA MUJER EMPRENDEDORA CHAQUEÑA. | as enacted, in force 2 October 2019 |
| `ley-2997-g/` | Ley 2997-G: ADHESIÓN L.N.27499 - LEY PCIAL. NATALIA SAMANIEGO. (LEY MICAELA) | as enacted, in force 16 June 2019 |
| `ley-3001-r/` | Ley 3001-R: ADHESIÓN L.N. 27.424 - RÉGIMEN DE FOMENTO GENERACIÓN DE ENERGÍA RENOVABLE | as enacted, in force 29 September 2019 |
| `ley-2993-f/` | Ley 2993-F: CONVENIO PCIA. DEL CHACO CON FONDO FIDUCIARIO DE DESARROLLO PCIAL (CAMMESA). | as enacted, in force 21 April 2019 |
| `ley-2990-a/` | Ley 2990-A: CREA COMISIÓN ESPECIAL DE SEGUIMIENTO EMPRESA SECHEEP PLAN ENERGÉTICOI  PCIAL. 2013-2033 | as enacted, in force 12 May 2019 |
| `ley-2988-a/` | Ley 2988-A: COLOCACIÓN SEÑALES DE CARÁCTER INFORMATIVOS REFERIDA A LAS ISLAS MALVINAS. | as enacted, in force 5 May 2019 |
| `ley-2986-p/` | Ley 2986-P: ELEVA A SEGUNDA CATEGORÍA AL MUNICIPIO DE LOS FRENTONES | as enacted, in force 21 April 2019 |
| `ley-2985-a/` | Ley 2985-A: PRORROGA POR EL TÉRMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2265 - A (ANTES LEY 7511) | as enacted, in force 21 April 2019 |
| `ley-2983-s/` | Ley 2983-S: INTEGRACIÓN DE MUJERES EN CARGOS ELECTIVOS Y REPRESENTATIVOS DE LAS INSTITUCIONES DEPORTIVAS | as enacted, in force 21 April 2019 |
| `ley-2979-f/` | Ley 2979-F: PROGRAMA CHACO SUBSIDIA. | as enacted, in force 17 March 2019 |
| `ley-2978-f/` | Ley 2978-F: AUTORIZA AL P.E. SUSCRIBIR PRÉSTAMOS SUBSIDIARIOS PARA PROGRAMA DE INVERSIONES MUNICIPALES | as enacted, in force 13 February 2019 |
| `ley-2977-a/` | Ley 2977-A: PRORROGA POR EL TÉRMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2556-A (ANTES LEY 7945) | as enacted, in force 13 February 2019 |
| `ley-2975-g/` | Ley 2975-G: EJERCICIO DE LA PROFESIÓN DE LICENCIADO EN NUTRICIÓN, PROFESIONALES UNIVERSITARIOS DIETISTA. | as enacted, in force 10 February 2019 |
| `ley-2968-f/` | Ley 2968-F: MODIFICACIONES SOBRE TASA RETRIBUTIVAS POR SERVICIOS ADMIN. EN LA DCCIÓN. PCIAL DEL TRABAJO S/LEY 299-F (ANTES LEY 2071). | as enacted, in force 18 January 2019 |
| `ley-2971-a/` | Ley 2971-A: ESTABLECE EN PAPELERÍA OFICIAL PARA EL AÑO 2019 LA LEYENDA “AÑO 2019, CENTENARIO DEL NACIMIENTO DE EVA DUARTE DE PERÓN”. | as enacted, in force 18 January 2019 |
| `ley-2972-a/` | Ley 2972-A: RÉGIMEN LEGAL DEL EJERCICIO DE LA PROFESIÓN DISEÑO GRÁFICO | as enacted, in force 8 February 2019 |
| `ley-2969-a/` | Ley 2969-A: NUEVA ESCALA DE REMUNERACIONES DEL PERSONAL LEGISLATIVO SEGÚN LEY 469-A (ANTES LEY 2898) | as enacted, in force 6 February 2019 |
| `ley-2970-b/` | Ley 2970-B: CREACIÓN DE CARGOS Y REORDENAMENTO EN EL CONSEJO DE LA MAGISTRATURA | as enacted, in force 8 February 2019 |
| `ley-2967-f/` | Ley 2967-F: MODIFICA ARTÍCULO 3º DE LA LEY 2078-F (ANTES LEY 7149) | as enacted, in force 18 January 2019 |
| `ley-2966-f/` | Ley 2966-F: MODIFICA ARTÍCULO 1º E INCORPORA TÍTULO A LA LEY 1704-I (ANTES LEY 6286) | as enacted, in force 18 January 2019 |
| `ley-2965-f/` | Ley 2965-F: MODIFICA ARTS..12 Y 16 ITEM C) DEL INC.33) DE LA LEY 299-F (ANTES LEY 2071) | as enacted, in force 18 January 2019 |
| `ley-2964-f/` | Ley 2964-F: MODIFICA VARIOS ARTÍCULOS E INCORPORA INCISOS, Y DEROGA VARIOS INCISOS DE LA LEY 83-F (ANTES D.L.2444/62) | as enacted, in force 18 January 2019 |
| `ley-2962-f/` | Ley 2962-F: PRESUPUESTO PROVINCIAL PERIODO 2019. | as enacted, in force 6 January 2019 |
| `ley-2963-a/` | Ley 2963-A: PRORROGA HASTA EL 31/12/2019 LA VIGENCIA DE LA LEY 2425-F (ANTES LEY 7751) | as enacted, in force 18 January 2019 |
| `ley-2961-a/` | Ley 2961-A: INCORPORA COMO ARTÍCULO 4º DE LA LEY 2908-A | as enacted, in force 6 February 2019 |
| `ley-2956-c/` | Ley 2956-C: CREA EL COLEGIO DE PROFESIONALES DE LA HIGIENE Y SEGURIDAD EN EL TRABAJO | as enacted, in force 3 February 2019 |
| `ley-2954-c/` | Ley 2954-C: CREA CONSEJO PROFESIONAL DE AGRIMENSURA DE LA PROVINCIA DEL CHACO | as enacted, in force 1 February 2019 |
| `ley-2953-c/` | Ley 2953-C: CREA COLEGIO PROFESIONAL DE ARQUITECTURA Y URBANISMO | as enacted, in force 25 January 2019 |
| `ley-2952-c/` | Ley 2952-C: CREA COLEGIO PROFESIONAL DE TÉCNICOS DEL CHACO | as enacted, in force 23 January 2019 |
| `ley-2951-n/` | Ley 2951-N: PROCESO PENAL APLICABLE A LOS ADOLESCENTES. | as enacted, in force 20 January 2019 |
| `ley-2955-c/` | Ley 2955-C: EJERCICIO PROFESIONAL DE LA INGENIERÍA Y CREA CONSEJO PROFESIONAL | as enacted, in force 1 February 2019 |
| `ley-2957-e/` | Ley 2957-E: DECLARA PATRIMONIO CULTURAL INMATERIAL A LA ACTIVIDAD TEATRAL | as enacted, in force 6 February 2019 |
| `ley-2959-a/` | Ley 2959-A: CARTEL QUE CONTENGA INFORMACIÓN DE CONTACTO CON CENTROS DE TRATAMIENTO DE ADICCIONES AL JUEGO - LUDOPATÍA. | as enacted, in force 6 February 2019 |
| `ley-2946-e/` | Ley 2946-E: ADHESIÓN A LA LEY NACIONAL 27.306 - DECLARA DE INTERÉS NACIONAL EL ABORDAJE INTEGRAL E INTERDISCIPLINARIO DE LOS SUJETOS QUE PRESENTAN DIFICULTADES … | as enacted, in force 13 January 2019 |
| `ley-2949-g/` | Ley 2949-G: MODIFICA LOS ARTÍCULOS 1º, 6º Y 9º, Y DEROGA EL ARTÍCULO 8º DE LA LEY 2402-G (ANTES LEY 7715) | as enacted, in force 13 January 2019 |
| `ley-2948-r/` | Ley 2948-R: PLAN PROVINCIAL DE SUSTENTABILIDAD DE LOS EDIFICIOSY OFICINAS PÚBLICAS | as enacted, in force 13 January 2019 |
| `ley-2947-g/` | Ley 2947-G: PROGRAMA DE PREVENCIÓN Y ATENCIÓN INTEGRAL DE LA OSTEOPOROSIS. | as enacted, in force 26 May 2019 |
| `ley-2945-v/` | Ley 2945-V: CREA PROGRAMA PROVINCIAL DE RUTAS ESCÉNICAS | as enacted, in force 13 January 2019 |
| `ley-2944-e/` | Ley 2944-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL EDIFICIO TEMPLO IGLESIA COMUNIDAD CRISTIANA EVANGÉLICA DE LA LOCALIDAD DE COLONIA PAMPA SOMMER. | as enacted, in force 26 May 2019 |
| `ley-2943-e/` | Ley 2943-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL INMUEBLE DE LA UNIÓN CULTURAL ARGENTINO GERMANA DE LA CIUDAD DE CHARATA. | as enacted, in force 26 May 2019 |
| `ley-2942-e/` | Ley 2942-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL  AL MUSEO MUNICIPAL DE LA CIUDAD DE CHARATA. | as enacted, in force 26 May 2019 |
| `ley-2938-a/` | Ley 2938-A: MODIFICA LEY 1238-A | as enacted, in force 13 January 2019 |
| `ley-2941-a/` | Ley 2941-A: MODIFICA EL  ARTÍCULO 5º E INCORPORA COMO ARTÍCULO 6º A LA LEY 2372-A (ANTES LEY 7672) | as enacted, in force 13 December 2018 |
| `ley-2940-e/` | Ley 2940-E: MODIFICA EL ART.2º INC.C) Y 4º DE LA LEY 1643-E (ANTES LEY 6157) | as enacted, in force 13 January 2019 |
| `ley-2939-h/` | Ley 2939-H: CREA REGISTRO PCIAL. DE EMPRENDEDORES Y OFICIOS | as enacted, in force 13 January 2019 |
| `ley-2937-a/` | Ley 2937-A: INCORPORA EL ARTÍCULO 4º BIS A LA LEY 1973-A (ANTES LEY 6879). | as enacted, in force 26 December 2018 |
| `ley-2936-p/` | Ley 2936-P: MODIFICA EL INC.XLI DEL ART. 1º DE LA LEY 43 - P (ANTES LEY 257) - PUEBLO: LAGUNA BLANCA | as enacted, in force 13 January 2019 |
| `ley-2935-k/` | Ley 2935-K: DEROGA EL PÁRRAFO SEGUNDO DEL ART.6º DE LA LEY 2024-K (ANTES LEY 7030) | as enacted, in force 13 January 2019 |
| `ley-2934-l/` | Ley 2934-L: PROMOCIÓN DE LA INSERCIÓN Y PARTICIPACIÓN DE PERSONAS TRAVESTÍS, TRANSEXUALES Y TRANSGÉNERO. | as enacted, in force 20 January 2019 |
| `ley-2933-p/` | Ley 2933-P: MODIFICA LA LEY 738-P (ANTES LEY 3798).-CREA EL FONDO SOLIDARIO MUNICIPAL-. | as enacted, in force 25 November 2018 |
| `ley-2931-a/` | Ley 2931-A: PRORROGA POR EL TÉRMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2476-A (ANTES LEY 7834) . | as enacted, in force 23 December 2018 |
| `ley-2930-e/` | Ley 2930-E: MODIFICA LOS ARTS. 1º, 3º INCISOS B) Y C), 4º Y 7º INCISOS A), B), C) Y D) LEY 2039-E (ANTES LEY 7068). | as enacted, in force 26 December 2018 |
| `ley-2929-p/` | Ley 2929-P: MODIFICA EL ARTÍCULO 1º DE LA LEY 2891-P - AMPLIACIÓN EJIDO MUNICIPAL HERMOSO CAMPO . | as enacted, in force 23 December 2018 |
| `ley-2928-c/` | Ley 2928-C: MODIFICA 2º PÁRRAFO DEL ARTÍCULO 5º DE LA LEY 288-C (ANTES LEY 2011) | as enacted, in force 23 December 2018 |
| `ley-2927-j/` | Ley 2927-J: INCORPORA INCISO C) DEL ARTÍCULO 69 DE LA LEY 850-J (ANTES LEY 4209) | as enacted, in force 23 December 2018 |
| `ley-2926-a/` | Ley 2926-A: RECATEGORIZACIÓN DEL CARGO DE SECRETARIO TÉCNICO DEL SUPERIOR TRIBUNAL DE JUSTICIA | as enacted, in force 23 December 2018 |
| `ley-2925-j/` | Ley 2925-J: EXHIBICIÓN OBLIGATORIA EN DEPENDENCIAS JUDICIALES PARRAFOS 5º Y 6º ART.21 CONST. PCIAL. 1957-1994. | as enacted, in force 23 December 2018 |
| `ley-2922-w/` | Ley 2922-W: SALUDO EN LENGUA NATIVA. | as enacted, in force 25 November 2018 |
| `ley-2923-q/` | Ley 2923-Q: MODIFICA EL ART.55 L.834-Q, , ART.10, INC.A) Y 23 L.2073-Q, ABROGASE  LA LEY 752-Q Y SE ADHIERE A LA L.N.27.412.- PARIDAD DE GÉNERO RÉGIMEN ELECTORA… | as enacted, in force 16 November 2018 |
| `ley-2924-f/` | Ley 2924-F: RÉGIMEN DE REGULARIZACIÓN EXCEPCIONAL DE OBLIGACIONES TRIBUTARIAS PROVINCIALES. | as enacted, in force 25 November 2018 |
| `ley-2921-d/` | Ley 2921-D: AGUA POTABLE PARA CONSUMO EN ESTABLECIMIENTOS GASTRONÓMICOS Y DE ESPECTACULOS. | as enacted, in force 26 May 2019 |
| `ley-2915-i/` | Ley 2915-I: PROGRAMA DE PROMOCIÓN DE ELABORACIÓN DE ALIMENTOS LIBRES DE GLUTEN. | as enacted, in force 25 November 2018 |
| `ley-2919-j/` | Ley 2919-J: SUPLEMENTO MENSUAL  PARA EL PERSONAL DE SEGURIDAD,  POLICÍA Y SERVICIO PENITENCIARIO SEGÚN LEY 2456-A (ANTES LEY 7796) | as enacted, in force 30 November 2018 |
| `ley-2918-f/` | Ley 2918-F: BONIFICACION  MENSUAL SUPLEMENTO POR VESTUARIO ESTABLECIDO POR LEY 1889 -F (ANTES LEY 6697) | as enacted, in force 30 November 2018 |
| `ley-2917-j/` | Ley 2917-J: BONIFICACIÓN MENSUAL SUPLEMENTO POR VESTUARIO SEGÚN LEY 1880-A(ANTES LEY 6677) | as enacted, in force 30 November 2018 |
| `ley-2916-f/` | Ley 2916-F: DECLARA CUMPLIDO PROGRAMA DE DESARROLLO INSTITUCIONAL E INVERSIONES PRODIISM) - SEGÚN L.842-X. | as enacted, in force 25 November 2018 |
| `ley-2914-g/` | Ley 2914-G: ADHESIÓN L.N.27.447 - TRASPLANTE DE ÓRGANOS. TEJIDOS Y CÉLULAS - DEROGA L.820-G. | as enacted, in force 25 November 2018 |
| `ley-2913-e/` | Ley 2913-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL AL EX-INGENIO AZUCARERO LAS PALMAS DEL CHACO AUSTRAL | as enacted, in force 20 January 2019 |
| `ley-2912-a/` | Ley 2912-A: TRANSFERENCIA INMUEBLE AL MUNICIPIO DE SAENZ PEÑA. | as enacted, in force 7 November 2018 |
| `ley-2910-a/` | Ley 2910-A: CREA JUZGADO DEL MENOR DE EDAD Y LA FAMILIA Nº 2 EN S.PEÑA, VILLA ANGELA, CHARATA Y J.J.CASTELLI. | as enacted, in force 7 November 2018 |
| `ley-2911-a/` | Ley 2911-A: ADHESIÓN AL TITULO  I DE LA LEY NACIONAL 27.440 - FINANCIAMIENTO PRODUCTIVO. | as enacted, in force 7 November 2018 |
| `ley-2908-a/` | Ley 2908-A: BONIFICACION POR ASISTENCIA EXCLUSIVA AL LEGISLADOR. | as enacted, in force 2 November 2018 |
| `ley-2905-r/` | Ley 2905-R: DECLARA DE INTERÉS PCIAL. EL MUITÚ (CRAX FASCIOLATA) | as enacted, in force 30 November 2018 |
| `ley-2904-j/` | Ley 2904-J: INCORPORA INC.C) AL ART. 5º , SUSTITUYE ARTS.6º, 7º, 8º Y 9º E INCORPORA ARTS. 10 Y 11 DE LA LEY 1096-J (ANTES LEY 4796) | as enacted, in force 7 November 2018 |
| `ley-2903-a/` | Ley 2903-A: ASIGNA CARÁCTER DE LETRADO AL JUZGADO DE PAZ Y FALTAS DE LA LOCALIDAD DE PUERTO TIROL. | as enacted, in force 7 November 2018 |
| `ley-2902-c/` | Ley 2902-C: MODIFICA LOS ARTÍCULOS 2º Y 3º DE LA LEY 1864-C (ANTES LEY 6640) | as enacted, in force 28 September 2018 |
| `ley-2901-a/` | Ley 2901-A: MODIFICA EL INCISO B) DEL ARTÍCULO 1º DE LA LEY 2860-A | as enacted, in force 25 November 2018 |
| `ley-2900-k/` | Ley 2900-K: ESTABLECE CUPO HABITACIONAL JOVEN PARA PERSONAS ENTRE 18 Y 35 AÑOS DE EDAD. CREA REGISTRO DE ADJUDICATARIOS JOVENES. | as enacted, in force 7 November 2018 |
| `ley-2899-a/` | Ley 2899-A: MODIFICA LOS ARTÍCULOS 1º A 4º DE LA LEY 2864 - A. | as enacted, in force 30 November 2018 |
| `ley-2891-p/` | Ley 2891-P: AMPLÍA EL EJIDO MUNICIPAL DE HERMOSO CAMPO.. | as enacted, in force 7 October 2018 |
| `ley-2892-g/` | Ley 2892-G: LA EQUINOTERAPIA COMO ACTIVIDAD TERAPÉUTICA. | as enacted, in force 16 September 2018 |
| `ley-2893-g/` | Ley 2893-G: PROGRAMA DE CIRUGÍA RECONSTRUCTIVA ESTÉTICA PARA PERSONAS VÍCTIMAS DE VIOLENCIA DE GÉNERO. | as enacted, in force 7 October 2018 |
| `ley-2894-c/` | Ley 2894-C: REESTABLECE POR EL TÉRMINO DE CINCO AÑOS, LA VIGENCIA DE LA LEY  1452-C (ANTES LEY 5703). | as enacted, in force 7 October 2018 |
| `ley-2895-a/` | Ley 2895-A: PRORROGA POR EL TÉRMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2057 A (ANTES LEY 7115) | as enacted, in force 7 October 2018 |
| `ley-2897-a/` | Ley 2897-A: MODIFICA EL ARTÍCULO 1º DE LA LEY 2837-A | current text only, as of 17 October 2018 |
| `ley-2889-b/` | Ley 2889-B: DECLARA LA INTERVENCIÓN DEL PODER EJECUTIVO Y CONCEJO DELIBERANTE DE VILLA RIO BERMEJITO, DE ACUERDO A LOS  TÉRMINOS DEL ART.  203 DE LA CONSTITUCIÓ… | as enacted, in force 7 September 2018 |
| `ley-2884-i/` | Ley 2884-I: REINSTAURA LA VIGENCIA DE LA LEY 1394-I (ANTES LEY 554O) HASTA EL 30 DE JUNIO DE 2021. | as enacted, in force 19 September 2018 |
| `ley-2877-r/` | Ley 2877-R: ADHESIÓN L.N.26.093 - RÉGIMEN DE REGULACIÓN Y PROMOCIÓN PARA LA PRODUCCIÓN Y USO SUSTENTABLE DE BIOCOMBUSTIBLES. | as enacted, in force 19 September 2018 |
| `ley-2875-d/` | Ley 2875-D: DIFERENCIA EN MONTO A PAGAR -DEROGA LA LEY 1403-D (ANTES LEY 5561) | as enacted, in force 7 November 2018 |
| `ley-2885-a/` | Ley 2885-A: REINSTAURA POR EL TÉRMINO DE DOS (2) AÑOS, LA VIGENCIA DE LA LEY 1556-A (ANTES LEY 5943). | as enacted, in force 19 September 2018 |
| `ley-2879-j/` | Ley 2879-J: DEROGA LOS ARTÍCULOS 52,53,54 Y 55 DE LA LEY 2854-J. | as enacted, in force 12 September 2018 |
| `ley-2876-e/` | Ley 2876-E: INSTITUYE COMO DÍA DEL DIÁLOGO INTERRELIGIOSO EL 9 DE AGOSTO DE CADA AÑO. | as enacted, in force 19 September 2018 |
| `ley-2874-a/` | Ley 2874-A: PRORROGA POR EL TÉRMINO DE DOS (2) AÑOS, VIGENCIA LEY Nº 2024-K (ANTES LEY 7030) . | as enacted, in force 12 September 2018 |
| `ley-2873-k/` | Ley 2873-K: ADHESIÓN LEY NACIONAL Nº 27.397 - DETERMINA PRECIOS EN CONTRATOS DE OBRAS PÚBLICAS -VIVIENDAS-. | as enacted, in force 7 September 2018 |
| `ley-2870-a/` | Ley 2870-A: CREA EL INSTITUTO PCIAL. DE ADMINISTRACIÓN PÚBLICA DEL CHACO -IPAP- BONIFICACIÓN ESPECIAL. | as enacted, in force 7 September 2018 |
| `ley-2856-l/` | Ley 2856-L: ADHESIÓN LEY NACIONAL  Nº 27348 -RIESGO DEL TRABAJO. | as enacted, in force 17 August 2018 |
| `ley-2871-h/` | Ley 2871-H: RETIRO VOLUNTARIO MÓVIL PARA PERSONAL DEL PODER EJECUTIVO. | as enacted, in force 19 August 2018 |
| `ley-2869-f/` | Ley 2869-F: CRÉDITO PÚBLICO - OBRAS ACCESOS A LOS PUERTOS LAS PALMAS Y BARRANQUERAS. | as enacted, in force 19 August 2018 |
| `ley-2858-f/` | Ley 2858-F: OBLIGACIONES IMPOSITIVAS PROVINCIALES - RÉGIMEN DE FINANCIACIÓN PARA MUNICIPIOS. | as enacted, in force 19 August 2018 |
| `ley-2868-c/` | Ley 2868-C: MODIFICA EL INCISO D) DEL ARTÍCULO 5º DE LA LEY 1495-C (ANTES LEY 5799) | as enacted, in force 19 August 2018 |
| `ley-2867-a/` | Ley 2867-A: EXPROPIA INMUEBLE EN LA LOCALIDAD DE LAGUNA LIMPIA PARA ADJUDICAREN VENTA A ACTUALES OCUPANTES | as enacted, in force 2 December 2018 |
| `ley-2866-a/` | Ley 2866-A: EXPROPIA INMUEBLES EN RCIA.-VILLA DON ANDRÉS- P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES. | as enacted, in force 19 September 2018 |
| `ley-2865-a/` | Ley 2865-A: INCREMENTOS SALARIALES AUTORIDADES SUPERIORES DEL PODER EJECUTIVO Y ENTES DESCENTRALIZ. Y AUTÁRQUICOS | as enacted, in force 19 August 2018 |
| `ley-2864-a/` | Ley 2864-A: INCREMENTOS SALARIALES PERSONAL PODER EJECUTIVO, TRIBUNAL DE CUENTAS, FISCALIA DE ESTADO, POLICIA, SERV. PENITENCIARIO Y DCCION. DE AERONAUTICA. | as enacted, in force 19 August 2018 |
| `ley-2863-a/` | Ley 2863-A: INCREMENTOS  SALARIALES PODER JUDICIAL-TRIBUNAL ELECTORAL Y CONS. DE LA MAGISTR. Y JUR. DE ENJUICIAMIENTO. | as enacted, in force 19 August 2018 |
| `ley-2862-a/` | Ley 2862-A: DISPONE EL PAGO DE UNA SUMA FIJA PARA EL PERSONAL PASIVO COMPRENDIDO EN LA LEY 196-A (ANTES LEY 1276) | as enacted, in force 19 August 2018 |
| `ley-2859-h/` | Ley 2859-H: INCREMENTO PRESTACIONES SOCIALES PARA EX-EMPLEADOS DEL BCO. DEL CHACO S.E.M Y RETIRADOS BOCEP | as enacted, in force 19 August 2018 |
| `ley-2860-a/` | Ley 2860-A: PERSONAL DOCENTE.INCREMENTOS DEL VALOR ÍNDICE UNO (1) Y BONIFICACIÓN POR TÍTULO. | as enacted, in force 19 August 2018 |
| `ley-2855-j/` | Ley 2855-J: ORDENAMIENTO NORMATIVO PARA LA ACTIVIDAD DEL PERSONAL DEL SERVICIO PENITENCIARIO - REGIMEN | as enacted, in force 21 December 2018 |
| `ley-2854-j/` | Ley 2854-J: LEY ORGÁNICA DEL SERVICIO PENITENCIARIO Y READAPTACIÓN SOCIAL DE LA PCIA. DEL CHACO - DEROGA LEY 1628 - J (ANTES LEY 6117) | as enacted, in force 17 August 2018 |
| `ley-2853-f/` | Ley 2853-F: MODIFICA LOS ARTÍCULOS 5º Y 6º DE LA LEY 2688-F. | as enacted, in force 17 August 2018 |
| `ley-2852-a/` | Ley 2852-A: ADJUDICACIÓN DE INMUEBLES A ENARSA S.A. PARA LA CONSTRUCCIÓN DEL GASODUCTO DEL NORDESTE ARGENTINO. | current text only, as of 29 April 2025 |
| `ley-2851-g/` | Ley 2851-G: ADHESIÓN L.N. 27232 - ESTABLECE EL NOMENCLADOR BIOQUÍMICO ÚNICO. | as enacted, in force 10 August 2018 |
| `ley-2850-a/` | Ley 2850-A: EXPROPIA INMUEBLE EN LAGUNA BLANCA CON DESTINO DE OBRAS PÚBLICAS. | current text only, as of 23 October 2018 |
| `ley-2845-s/` | Ley 2845-S: ADHESIÓN L.N. 27.211 - DERECHO DE FORMACIÓN DEPORTIVA. | as enacted, in force 8 August 2018 |
| `ley-2848-a/` | Ley 2848-A: EXPROPIA INMUEBLES EN BQUERAS. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 8 August 2018 |
| `ley-2847-a/` | Ley 2847-A: LA DCCIÓN DE VIALIDAD PCIAL. TRANSFIERE INMUEBLE EN COLONIA BENITEZ PARA EL CLUB "YAPÚ GUAZÚ" | as enacted, in force 23 December 2018 |
| `ley-2844-e/` | Ley 2844-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL A LA PARROQUIA "INMACULADA CONCEPCIÓN DE MARÍA DE BARRANQUERAS. | as enacted, in force 1 August 2018 |
| `ley-2843-e/` | Ley 2843-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL A LA ESCUELA DE EDUCACIÓN PRIMARO Nº 30 " SAN MARTÍN" | as enacted, in force 1 August 2018 |
| `ley-2841-a/` | Ley 2841-A: PRORROGA HASTA EL 31 DE DICIEMBRE DE 2018 VIGENCIA LEY 2425-F (ANTES LEY 7751). | as enacted, in force 8 July 2018 |
| `ley-2842-a/` | Ley 2842-A: BONIFICACIÓN POR PERMANENCIA EN LA ESTRUCTURA PERSONAL LEGISLATIVO. | as enacted, in force 15 July 2018 |
| `ley-2840-a/` | Ley 2840-A: EXPROPIA INMUEBLES EN RESISTENCIA PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 15 July 2018 |
| `ley-2835-a/` | Ley 2835-A: TRANSFIERE INMUEBLE DEL IPDUV A LA MUNICIPALIDAD DE QUITILIPI | current text only, as of 23 October 2018 |
| `ley-2838-a/` | Ley 2838-A: EXPROPIA INMUEBLES EN PRESIDENCIA ROCA PARA  TRANSFERIR AL MUNICIPIO LOCAL | current text only, as of 23 October 2018 |
| `ley-2836-j/` | Ley 2836-J: PUBLICACIÓN OBLIGATORIA EN PORTAL PCIAL. SOBRE VIOLENCIA CONTRA LA MUJER. | as enacted, in force 15 July 2018 |
| `ley-2833-j/` | Ley 2833-J: CREA EL REGISTRO ÚNICO DE CASOS DE VIOLENCIA DE GÉNERO. | as enacted, in force 8 July 2018 |
| `ley-2831-t/` | Ley 2831-T: ADHESIÓN L.N.26.958 - DIA MUNDIAL RECUERDO VICTIMAS DE ACCIDENTES DE TRÁNSITO | as enacted, in force 6 July 2018 |
| `ley-2830-d/` | Ley 2830-D: ADHESIÓN LEY NACIONAL 27.266 - SUSTITUYE ART.38 L.N.24.240 - DEFENSA DEL CONSUMIDOR | as enacted, in force 6 July 2018 |
| `ley-2829-a/` | Ley 2829-A: LIQUIDACIÓN DE HABERES PERSONAL DE FISCALÍA DE ESTADO. | as enacted, in force 15 June 2018 |
| `ley-2828-a/` | Ley 2828-A: EXPROPIA INMUEBLES EN LAGUNA BLANCA  P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES. | as enacted, in force 6 July 2018 |
| `ley-2825-f/` | Ley 2825-F: RATIFICA RESOLUCIÓN Nº 28/17 DE LA COMISIÓN PLENARIA (CONVENIO MULTILATERAL DEL 18/8/77) | as enacted, in force 15 June 2018 |
| `ley-2824-k/` | Ley 2824-K: USO RACIONAL Y EFICIENCIA ENERGÉTICA EN EDIFICIOS PÚBLICO (PUREEEP). | as enacted, in force 22 June 2018 |
| `ley-2827-e/` | Ley 2827-E: MODIFICA ARTÍCULO 3º DE LA LEY 2211 - E (ANTES LEY 7407). | as enacted, in force 22 June 2018 |
| `ley-2823-a/` | Ley 2823-A: MODIFICA ARTÍCULO 6 DE LA LEY 2024-K (ANTES LEY 7030) | as enacted, in force 22 June 2018 |
| `ley-2822-a/` | Ley 2822-A: FONDO DE APOYO AL SISTEMA EDUCATIVO. MODIFICACION DE VALOR. | as enacted, in force 8 July 2018 |
| `ley-2821-k/` | Ley 2821-K: TITULO EJECUTIVO PARA EL COBRO DE ACREENCIA DEL IPDUV. | as enacted, in force 22 June 2018 |
| `ley-2820-e/` | Ley 2820-E: IMPOSICIÓN NOMBRE "GOBERNADOR DEOLINDO FELIPE BITTEL", SALÓN INGRESO CENTRAL CASA DE GOBIERNO . | as enacted, in force 15 June 2018 |
| `ley-2819-g/` | Ley 2819-G: DENUNCIAS POR MENSAJERÍA DE TEXTO P/PERSONAS CON DISCAPACIDAD COMUNICATIVA | as enacted, in force 22 June 2018 |
| `ley-2818-a/` | Ley 2818-A: INCORPORA COMO ÚLTIMO PÁRRAFO DEL ARTÍCULO 3º DE LA LEY 616-A (ANTES LEY 3468). | as enacted, in force 1 June 2018 |
| `ley-2817-t/` | Ley 2817-T: ADHESIÓN A LA LEY 27.425. MODIFICA ARTS.30, 31, 32 Y 47 DEL ANEXO A DE LA LEY 949-T (ANTES LEY 4488). | as enacted, in force 15 July 2018 |
| `ley-2816-w/` | Ley 2816-W: MODIFICA EL ARTÍCULO 2º DE LA LEY 1821-W (ANTES LEY 6542). | as enacted, in force 15 June 2018 |
| `ley-2815-g/` | Ley 2815-G: USO OBLIGATORIO DE LAS NORMAS DE SEGURIDAD EN LAS PRÁCTICAS ODONTOLÓGICAS | as enacted, in force 6 July 2018 |
| `ley-2814-g/` | Ley 2814-G: CALENDARIO SOBRE DISCAPACIDADES | as enacted, in force 6 July 2018 |
| `ley-2813-b/` | Ley 2813-B: ADHESION L.N.27.275 - DERECHO DE ACCESO A LA INFORMACIÓN PÚBLICA | as enacted, in force 6 June 2018 |
| `ley-2812-f/` | Ley 2812-F: MODIFICA EL ARTÍCULO 6º DE LA LEY 2688- F | as enacted, in force 6 July 2018 |
| `ley-2809-j/` | Ley 2809-J: REGISTRO ÚNICO DE PERSONAS VIOLENTAS (RUPV) | as enacted, in force 26 October 2018 |
| `ley-2811-h/` | Ley 2811-H: NUEVO MONTO PARA LAS ASIGNACIONES FAMILIAR POR INICIACIÓN DEL CICLO LECTIVO. | as enacted, in force 6 June 2018 |
| `ley-2810-g/` | Ley 2810-G: INSTITUYE EL DÍA 21 DE NOVIEMBRE DE CADA AÑO COMO EL "DÍA PCIAL. DE PREVENCIÓN DEL DENGUE, ZIKA Y CHIKUNGUNYA" | as enacted, in force 15 June 2018 |
| `ley-2803-e/` | Ley 2803-E: INSTITUYESE COMO "DIA DEL ESCRITOR BREÑENSE" AL 21 DE AGOSTO DE CADA AÑO, EN HOMENAJE AL ESCRITOR Y POETA MARIO NESTOROFF. | as enacted, in force 15 June 2018 |
| `ley-2808-g/` | Ley 2808-G: EXAMEN GINECOLÓGICO PAPANICOLAU (PAP) PARA TODA LA POBLACIÓN | as enacted, in force 15 June 2018 |
| `ley-2807-i/` | Ley 2807-I: REINSTAURA LA VIGENCIA DE LA LEY 1394-I (ANTES LEY 5540) HASTA EL 30 DE JUNIO DE 2018 | as enacted, in force 15 June 2018 |
| `ley-2806-c/` | Ley 2806-C: ADHESIÓN L.N. 27.364 - PROGRAMA DE ACOMPAÑAMIENTO PARA EL EGRESO DE JÓVENES SIN CUIDADO PARENTALES. | as enacted, in force 15 June 2018 |
| `ley-2805-a/` | Ley 2805-A: INCORPORA EN LA PAGINA WEB DEL PODER LEGISLATIVO INCLUSIÓN DE NOMINA E IMAGEN  DE NIÑOS/AS PERDIDOS. | as enacted, in force 15 June 2018 |
| `ley-2804-g/` | Ley 2804-G: DECLARA LA OBLIGATORIEDAD DE INSTALAR PLACA IDENTIFICATORIA EN SISTEMA BRAILE EN TODOS LOS EDIFICIO SPÚBLICOS DEL GOBIERNO PCIAL. | as enacted, in force 15 June 2018 |
| `ley-2802-j/` | Ley 2802-J: IMPLEMENTA LA OBLIGATORIEDAD DE INSTALAR BOTÓN ANTI PÁNICO EN EL TRANSPORTE DE PASAJEROS. | as enacted, in force 15 June 2018 |
| `ley-2801-e/` | Ley 2801-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL DE LA PCIA. EDIFICIO EXCOMISARÍA  DE LAS BREÑAS | as enacted, in force 15 June 2018 |
| `ley-2800-e/` | Ley 2800-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL DE LA PCIA. DEL CHACO, EDIFICIO COOPERATIVA AGROPECUARIA DE LAS BREÑAS. | as enacted, in force 15 June 2018 |
| `ley-2799-e/` | Ley 2799-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL DEL CHACO, EDIFICIO IGLESIA ORTODOXA UCRANIANA DE LAS BREÑAS. | as enacted, in force 15 June 2018 |
| `ley-2793-a/` | Ley 2793-A: EXPROPIA INMUEBLE EN PRESIDENCIA ROCA PARA OBRA PLANTA POTABILIZADORA Y ACUEDUCTO. | current text only, as of 16 October 2018 |
| `ley-2795-f/` | Ley 2795-F: MODIFICA EL ARTÍCULO 14 DE LA LEY 2734- F | as enacted, in force 4 May 2018 |
| `ley-2797-a/` | Ley 2797-A: MODIFICA ARTÍCULO 1º DE LA LEY 2551 - A (ANTES LEY 7939) | as enacted, in force 6 June 2018 |
| `ley-2798-b/` | Ley 2798-B: MODIFICA ARTÍCULOS 1º Y 3º DE LA LEY 678-P (Antes ley 3604) | as enacted, in force 22 June 2018 |
| `ley-2792-a/` | Ley 2792-A: DECLARA AL MES DE JUNIO DE 2018 COMO "MES DEL CENTENARIO DE LA REFORMA UNIVERSITARIA". | as enacted, in force 13 May 2018 |
| `ley-2791-k/` | Ley 2791-K: MODIFICA EL ARTÍCULO 6º DE LA LEY 2042- K (ANTES LEY 7071). | as enacted, in force 13 May 2018 |
| `ley-2790-g/` | Ley 2790-G: ADHESIÓN L.N. 25.855 - VOLUNTARIADO SOCIAL | as enacted, in force 13 May 2018 |
| `ley-2789-j/` | Ley 2789-J: IMPLEMENTACIÓN DE SISTEMA DE PROTECCIÓN TECNOLÓGICO PARA VICTIMAS DE VIOLENCIA DE GÉNERO Y MODIFICA EL ART.6º A LA LEY Nº 1886-M (ANTES LEY 6689) | as enacted, in force 6 June 2018 |
| `ley-2788-m/` | Ley 2788-M: MODIFICA EL ARTíCULO 18 DE LA LEY 2198-M (ANTES LEY 7388) | as enacted, in force 6 June 2018 |
| `ley-2787-e/` | Ley 2787-E: DECLARA PATRIMONIO CULTURAL AL INSTRUMENTO MUSICAL "EL BOMBO GRINGO". | as enacted, in force 6 June 2018 |
| `ley-2786-e/` | Ley 2786-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL DE LA PROVINCIA DEL CHACO, A LA ESCUELA DE EDUCACIÓN SECUNDARIA Nª 184 "GENERAL MARTÍN MIGUEL DE GUEMES" DE … | as enacted, in force 6 June 2018 |
| `ley-2785-e/` | Ley 2785-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL A LA EGB. Nº 255 "FELIPE BOERO. | as enacted, in force 6 June 2018 |
| `ley-2784-g/` | Ley 2784-G: ADHESIÓN  L.N.. 27.410 - INSTITUYE EL MES DE NOVIEMBRE DE CADA AÑO COMO "MES NACIONAL DE CONCIENTIZACIÓN SOBRE LA VIOLENCIA DE GÉNERO". | as enacted, in force 6 June 2018 |
| `ley-2783-g/` | Ley 2783-G: ADHESIÓN L.N. 27.420 - USO DEL BASTÓN ROJO Y BLANCO | as enacted, in force 29 April 2018 |
| `ley-2782-a/` | Ley 2782-A: EXPROPIA INMUEBLES EN ROQUE SAENZ PEÑA PARA SER ADJUDICADO EN VENTA A SUS OCUPANTES. | as enacted, in force 29 April 2018 |
| `ley-2781-e/` | Ley 2781-E: INSTITUYE EL DÍA 31 DE OCTUBRE DE CADA AÑO COMO EL "DIA DE LAS IGLESIAS EVANGÉLICAS" | as enacted, in force 29 April 2018 |
| `ley-2780-a/` | Ley 2780-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 29 April 2018 |
| `ley-2776-p/` | Ley 2776-P: INCORPORA EL INCISO Ñ) AL ARTICULO 10 DE LA LEY 854-P (ANTES LEY 4233) | as enacted, in force 29 April 2018 |
| `ley-2775-r/` | Ley 2775-R: MODIFICA EL ARTICULO 4º DE LA LEY 2026-R (ANTES LEY 7032) | as enacted, in force 29 April 2018 |
| `ley-2774-a/` | Ley 2774-A: MODIFICA EL ARTÍCULO 4º DE LA LEY 397-A (ANTES LEY 2543) | as enacted, in force 29 April 2018 |
| `ley-2773-g/` | Ley 2773-G: INSTITUYE EL DÍA 7 DE MARZO DE CADA AÑO EL "DÍA PCIAL. DEL MÉDICO SANITARISTA" | as enacted, in force 29 April 2018 |
| `ley-2772-l/` | Ley 2772-L: PROTOCOLO DE PREVENCIÓN ANTE SITUACIONES DE VIOLENCIA LABORAL EN LA ADMINISTRACIÓN PÚBLICA | as enacted, in force 29 April 2018 |
| `ley-2769-g/` | Ley 2769-G: PREVENCIÓN DEL CÁNCER DE PROSTATA | as enacted, in force 2 May 2018 |
| `ley-2770-g/` | Ley 2770-G: ADHESIÓN LEY NACIONAL 25.682 - PERSONAS CON BAJA VISIÓN | as enacted, in force 2 May 2018 |
| `ley-2768-f/` | Ley 2768-F: ADHIERE A LEY NACIONAL Nº 27.428 (REGIMEN FEDERAL DE RESPONSABILIDAD FISCAL Y BUENAS PRACTICAS DE GOBIERNO) | as enacted, in force 18 February 2018 |
| `ley-2767-f/` | Ley 2767-F: ACUERDO DE FINANCIAMIENTO Y COLABORACIÓN ENTRE LA  PROVINCIA DEL CHACO, EL ESTADO NACIONAL Y LA ADMINISTRACIÓN  FEDERAL DE INGRESOS PÚBLICOS. | as enacted, in force 19 January 2018 |
| `ley-2766-a/` | Ley 2766-A: PRORROGA HASTA EL 30/06/2018 LA LEY Nº 2425-F (ANTES LEY 7751). | as enacted, in force 17 January 2018 |
| `ley-2749-a/` | Ley 2749-A: CREA CARGO TEMPORARIO PERSONAL DE GABINETE JURISDICCIÓN 08: TRIBUNAL DE CUENTAS | as enacted, in force 24 January 2018 |
| `ley-2752-e/` | Ley 2752-E: PROGRAMA DE EDUCACIÓN TRIBUTARIA | as enacted, in force 26 January 2018 |
| `ley-2759-a/` | Ley 2759-A: EXPROPIA INMUEBLE EN LA CIUDAD DE VILLA ANGELA DEPARTAMENTO MAYOR LUIS FONTANA | as enacted, in force 28 January 2018 |
| `ley-2764-l/` | Ley 2764-L: INSTITUYE EL DÍA 20 DE DICIEMBRE DE CADA AÑO COMO EL "DIA DEL MENSAJERO" | as enacted, in force 31 January 2018 |
| `ley-2763-i/` | Ley 2763-I: SISTEMA DE RESERVAS DE PASAJES "ONLINE". PARA DISCAPACITADOS | as enacted, in force 31 January 2018 |
| `ley-2765-j/` | Ley 2765-J: LEY DE ANIMALES SUELTOS.- DEROGA LE LEY 2138-J | as enacted, in force 2 February 2018 |
| `ley-2756-a/` | Ley 2756-A: EXPROPIA INMUEBLES EN DPTO. SAN FERNANDO PARA OBRA  AMPLIACIÓN CANAL 16 | current text only, as of 19 June 2018 |
| `ley-2760-e/` | Ley 2760-E: DÍA DEL PASTOR EVANGÉLICO. | as enacted, in force 28 January 2018 |
| `ley-2761-g/` | Ley 2761-G: ADHESION L.N. 27.360 - PROTECCIÓN DE LOS DERECHOS HUMANOS DE LAS PERSONAS MAYORES | as enacted, in force 28 January 2018 |
| `ley-2762-e/` | Ley 2762-E: INSTITUYE COMO CAPITAL PCIAL. DE LA FIESTA DEL CHAMAMÉ A LA CIUDAD DE PUERTO TIROL | as enacted, in force 31 January 2018 |
| `ley-2753-a/` | Ley 2753-A: RECATEGORIZACIÓN CARGO DE SECRETARIO LETRADO DE CÁMARA DEL PODER JUDICIAL | as enacted, in force 26 January 2018 |
| `ley-2751-g/` | Ley 2751-G: ADHESIÓN L.N.27.350 - USO MEDICINAL DE LA PLANTA DE CANNABIS Y SUS DERIVADOS | as enacted, in force 26 January 2018 |
| `ley-2750-a/` | Ley 2750-A: ESTABLECE EN PAPELERÍA OFICIAL PARA EL AÑO 2018 LA LEYENDA "2018 AÑO DE LA CONCIENTIZACIÓN SOBRE LA VIOLENCIA DE GÉNERO #NIUNAMENOS" | as enacted, in force 5 January 2018 |
| `ley-2747-f/` | Ley 2747-F: RATIFICA CONVENIO CON EL GOBIERNO NACIONAL. | as enacted, in force 31 December 2017 |
| `ley-2745-b/` | Ley 2745-B: APRUEBA  EL ACUERDO DENOMINADO CONSENSO FISCAL AÑO 2017. | as enacted, in force 31 December 2017 |
| `ley-2737-f/` | Ley 2737-F: CRÉIDTO PÚBLICO PAVIMENTACIÓN DE LA RUTA PROVINCIAL Nº 6 | as enacted, in force 24 December 2017 |
| `ley-2734-f/` | Ley 2734-F: PRESUPUESTO PROVINCIAL EJERCICIO 2018. | as enacted, in force 24 December 2017 |
| `ley-2736-f/` | Ley 2736-F: CRÉDITO PÚBLICO PARA OBRAS BÁSICAS Y PAVIMENTO DE LA RUTA PROVINCIAL Nº 13 . | as enacted, in force 24 December 2017 |
| `ley-2735-f/` | Ley 2735-F: CRÉDITO PÚBLICO PAVIMENTACIÓN RUTA PROVINCIAL Nº 9 | as enacted, in force 24 December 2017 |
| `ley-2743-e/` | Ley 2743-E: EL DIA 8 DE SEPTIEMBRE SE RECUERDA A LOS  ARTISTAS POPULARES CHAQUEÑOS FALLECIDOS EN BELLA VISTA CORRIENTES. | as enacted, in force 24 January 2018 |
| `ley-2742-s/` | Ley 2742-S: ADHESIÓN DE LA LEY NACIONAL 27.155 - EJERCICIO PROFESIONAL DE LOS GUARDAVIDAS -. | as enacted, in force 21 January 2018 |
| `ley-2741-g/` | Ley 2741-G: PROGRAMA DE TÉCNICAS DE REANIMACIÓN CARDIOPULMONAR. | as enacted, in force 21 January 2018 |
| `ley-2738-a/` | Ley 2738-A: AUTORIZA AL P.E. TRANSFERIR EN VENTA UN INMUEBLE EN RCIA. A FAVOR DE LA  FUN DACIÓN IGLESIA  DE JESUCRISTO PROPIEDAD DEL GOBIERNO DE LA PCIA. | current text only, as of 18 June 2018 |
| `ley-2733-f/` | Ley 2733-F: AUTORIZA AL P.E. A EFECTUAR OPERACIONES DE CRÉDITO PÚBLICO POR HASTA UN MONTO DE $4.198.492.000,00 | as enacted, in force 24 December 2017 |
| `ley-2730-e/` | Ley 2730-E: CREA PROGRAMA EN EL AMBITO DE EDUCACIÓN "PLAN COMUNITARIO PARA LA PREVENCIÓN DE CONSUMOS PROBLEMÁTICOS". | as enacted, in force 5 January 2018 |
| `ley-2729-i/` | Ley 2729-I: INCREMENTO DEL CONSUMO Y VALOR AGREGADO DE MIELES CHAQUEÑAS | as enacted, in force 5 January 2018 |
| `ley-2727-j/` | Ley 2727-J: ADHESIÓN L.N.27.287 - SISTEMA NACIONAL PARA LA GESTIÓN INTEGRAL DEL RIESGO Y LA PROTECCIÓN CIVIL. | as enacted, in force 29 December 2017 |
| `ley-2728-b/` | Ley 2728-B: PUBLICACIÓN ELECTRÓNICA DEL BOLETÍN OFICIAL. DEROGA LA LEY 3-B (ANTES LEY 11). | as enacted, in force 22 December 2017 |
| `ley-2719-e/` | Ley 2719-E: SECCIÓN DE EQUIPOS DE APOYO Y ORIENTACIÓN ESCOLAR - ABRÓGASE LA LEY 2052 (ANTES L.7093) | as enacted, in force 5 January 2018 |
| `ley-2721-a/` | Ley 2721-A: RECATEGORIZACIÓN JUZGADO DE PAZ Y FALTAS DE PAMPA DEL INFIERNO. | as enacted, in force 5 January 2018 |
| `ley-2725-a/` | Ley 2725-A: PERSONAL DOCENTE INCREMENTO DEL VALOR ÍNDICE UNO (1), A PARTIR DEL 01/08/2017. | as enacted, in force 17 January 2018 |
| `ley-2726-e/` | Ley 2726-E: PROGRAMA PROVINCIAL DE EDUCACIÓN PARA EL CONSUMO. | as enacted, in force 29 December 2017 |
| `ley-2723-p/` | Ley 2723-P: PRESERVACIÓN, PROTECCIÓN Y TUTELA DE LOS CEMENTERIOS RURALES. | as enacted, in force 29 December 2017 |
| `ley-2718-p/` | Ley 2718-P: DÍA DE LOS MUNICIPIOS CHAQUEÑOS. | as enacted, in force 29 December 2017 |
| `ley-2717-l/` | Ley 2717-L: CARACTERÍSTICAS, AUTORIDAD DE APLICACIÓN Y FOMENTO DEL TELETRABAJO. | as enacted, in force 27 December 2017 |
| `ley-2716-g/` | Ley 2716-G: PROTECCIÓN A LA FAMILIA VULNERABLE. | as enacted, in force 29 December 2017 |
| `ley-2715-a/` | Ley 2715-A: EXPROPIA INMUEBLE EN SAENZ PEÑA PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 27 December 2017 |
| `ley-2712-e/` | Ley 2712-E: PROGRAMA PCIAL. DE EDUCACIÓN P/ ALUMNOS C/ TALENTOS ESPECIALES O ALTAS CAPACIDADES | as enacted, in force 7 January 2018 |
| `ley-2711-f/` | Ley 2711-F: ADHESIÓN L.N. 27.349 - APOYO AL CAPITAL EMPRENDEDOR | as enacted, in force 7 January 2018 |
| `ley-2703-a/` | Ley 2703-A: PRORROGA POR EL TÉRMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2244-A (ANTES LEY 7475) | as enacted, in force 7 January 2018 |
| `ley-467-a/` | Ley 467-A: EXPROPIA INMUEBLES EN RCIA. P/REUBICACION DE FAMILIAS | as enacted, in force 4 December 1983 |
| `ley-172-c/` | Ley 172-C: CREA DIRECCION DE PROMOCION Y DESARROLLO DE SOCIEDADES COOPERATIVAS | as enacted, in force 9 January 1972 |
| `ley-2700-e/` | Ley 2700-E: ESTABLECE RÉGIMEN DE DISTINCIONES OTORGADOS POR LA CÁMARA DE DIPUTADOS. | as enacted, in force 22 November 2017 |
| `ley-2698-a/` | Ley 2698-A: INCREMENTO SALARIAL PARA EL PERSONAL DEL PODER EJECUTIVO. | as enacted, in force 22 November 2017 |
| `ley-2697-j/` | Ley 2697-J: INCREMENTO SALARIAL PARA EL PERSONAL POLICIAL Y  SERVICIO PENITENCIARIO | as enacted, in force 22 November 2017 |
| `ley-2694-a/` | Ley 2694-A: INCREMENTO SALARIAL PARA EL PERSONAL DEL PODER EJECUTIVO, A PARTIR DE AGOSTO 2016. | as enacted, in force 22 November 2017 |
| `ley-2693-a/` | Ley 2693-A: EXPROPIA INMUEBLES EN BQUERAS. PARA SER ADJUDICADOS EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 22 November 2017 |
| `ley-2689-g/` | Ley 2689-G: EJERCICIO PROFESIONAL DE LOS LICENCIADOS, TÉCNICOS EN RADIOLOGÍA Y PROFESIONALES EQUIVALENTES | as enacted, in force 27 December 2017 |
| `ley-2690-a/` | Ley 2690-A: EL IPDUV TRANSFIERE AL MUNICIPIO DE GRAL. JOSÉ DE SAN MARTÍN UN INMUEBLE DE SU PROPIEDAD | current text only, as of 12 June 2018 |
| `ley-2687-l/` | Ley 2687-L: "DIA PROVINCIAL DE LA LUCHA CONTRA LA VIOLENCIA LABORAL" | as enacted, in force 29 October 2017 |
| `ley-2688-f/` | Ley 2688-F: CONDONACIÓN Y REFINANCIACIÓN DE DEUDAS A PRODUCTORES AGROPECUARIOS | as enacted, in force 11 October 2017 |
| `ley-2685-a/` | Ley 2685-A: EXPROPIA INMUEBLE EN CAMPO LARGO PARA EL FUNCIONAMIENTO DEL PARQUE INDUSTRIAL | current text only, as of 11 June 2018 |
| `ley-2683-p/` | Ley 2683-P: CONSTRUCCIÓN DE BAÑOS PÚBLICOS EN LAS PLAZAS CENTRALES DE LA PROVINCIA | as enacted, in force 15 October 2017 |
| `ley-2681-a/` | Ley 2681-A: PRORROGA POR EL TÉRMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 1919-A (ANTES LEY 6773) | as enacted, in force 15 October 2017 |
| `ley-2680-a/` | Ley 2680-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/ FUNCIONAMIENTO DEL CONSEJO DE LA MAGISTRATURA | current text only, as of 8 June 2018 |
| `ley-2679-a/` | Ley 2679-A: ESTABLECE  QUE LAS VACANTES EN EL MINISTERIO DE EDUCACIÓN PERSONAL DE SERVICIOS SERÁN CUBIERTAS POR DECRETO DEL PODER EJECUTIVO. | as enacted, in force 5 November 2017 |
| `ley-2677-v/` | Ley 2677-V: ADHESION LEY NACIONAL Nº 27.324 - RÉGIMEN DE PROMOCIÓN DE PUEBLOS RURALES TURÍSTICOS | as enacted, in force 29 October 2017 |
| `ley-2675-p/` | Ley 2675-P: RÉGIMEN LEGAL DE LOS CINERARIOS O COLUMBARIOS. | as enacted, in force 29 October 2017 |
| `ley-2671-k/` | Ley 2671-K: CREA PROGRAMA PROVINCIAL DE INCENTIVOS PARA LA GENERACIÓN Y USO DE ENERGÍA RENOVABLES, ALTERNATIVAS O BLANDAS . | as enacted, in force 29 October 2017 |
| `ley-2673-v/` | Ley 2673-V: DECLARA A LA CIUDAD DE PRESIDENCIA ROQUE SAENZ PEÑA CAPITAL PCIAL.. DEL TURISMO TERMAL. | as enacted, in force 6 October 2017 |
| `ley-2665-f/` | Ley 2665-F: ADHESION A LEY NACIONAL Nº 27.328 (SISTEMA DE PARTICIPACIÓN PUBLICO-PRIVADA). | as enacted, in force 22 September 2017 |
| `ley-2669-a/` | Ley 2669-A: CREA COMISIÓN PROVINCIAL DE EX LEGISLADORES Y LEGISLADORAS* | as enacted, in force 6 October 2017 |
| `ley-2663-a/` | Ley 2663-A: EL IPDUV TRANSFIERE UN INMUEBLE EN DPTO. SAN FERNANDO PARA LA FUNDACION CONIN | current text only, as of 7 June 2018 |
| `ley-2661-e/` | Ley 2661-E: CEREMONIA ESCOLAR "COMPROMISO DE PROTECCION Y PRESERVACION DE LA MADRE TIERRA Y DE SUS DERECHOS" | as enacted, in force 6 September 2017 |
| `ley-2658-a/` | Ley 2658-A: POLICIA DEL CHACO - SERVICIO PENITENCIARIO PROVINCIAL INCREMENTO SALARIAL. | as enacted, in force 3 September 2017 |
| `ley-2660-a/` | Ley 2660-A: NUEVAS ESCALAS  SALARIALES P/ EL PERSONAL DEL PODER EJECUTIVO COMPRENDIDO EN LA LEY 196-A | as enacted, in force 3 September 2017 |
| `ley-2662-l/` | Ley 2662-L: ADHESIÓN PROVINCIAL , LEY NACIONAL Nº 27.299, POR LA QUE SE INSTITUYE EL DÍA DEL LADRILLERO ARTESANAL, EL 21 DE AGOSTO DE CADA AÑO. | as enacted, in force 6 September 2017 |
| `ley-766-p/` | Ley 766-P: INDICES DE DISTRIBUCION DEL FONDO DE PARTICIPACION MUNICIPAL | current text only, as of 14 November 2017 |
| `ley-2648-a/` | Ley 2648-A: REINSTAURA LA VIGENCIA DE LAS LEYES 1996-A (ANTES LEY 6928), 1578-A (ANTES LEY 5994) POR EL TERMINO DE DOS (2) AÑOS | as enacted, in force 6 August 2017 |
| `ley-2652-e/` | Ley 2652-E: DECLARAR PATRIMONIO HISTÓRICO Y CULTURAL DE LA PROVINCIA DEL CHACO AL EDIFICIO DE LA PARROQUIA NUESTRA SEÑORA DE ITATI, DE MACHAGAI. | as enacted, in force 6 August 2017 |
| `ley-2650-e/` | Ley 2650-E: DECLARA COMO CAPITAL PROVINCIAL DEL MUEBLE DE ALGARROBO A LA CIUDAD DE MACHAGAI . | as enacted, in force 6 August 2017 |
| `ley-2649-a/` | Ley 2649-A: REINSTAURA LA VIGENCIA DE LA LEY Nº 1918-A (ANTES LEY Nº 6772) POR EL TERMINO DE DOS (/2) AÑOS . | as enacted, in force 6 August 2017 |
| `ley-2645-s/` | Ley 2645-S: RÉGIMEN PROVINCIAL DE VALORACIÓN Y RECONOCIMIENTO AL MERITO DEPORTIVO. | as enacted, in force 29 October 2017 |
| `ley-2647-a/` | Ley 2647-A: EXPROPIA INMUEBLE EN COLONIA UNIDAS  PARA SER TRANSFERIDO AL MUNICIPIO LOCAL . | current text only, as of 6 June 2018 |
| `ley-2642-a/` | Ley 2642-A: CREA PARA EL PERSONAL POLICIAL EL CONCEPTO SEGURIDAD BONIFICACIÓN ESPECIAL | as enacted, in force 6 August 2017 |
| `ley-2641-a/` | Ley 2641-A: RECATEGORIZACIÓN DE CARGO DELEGADO PENITENCIARIO PODER JUDICIAL | as enacted, in force 6 August 2017 |
| `ley-2638-e/` | Ley 2638-E: EL MINISTERIO DE EDUCACIÓN IMPLEMENTARÁ PARA NIVEL PRIMARIO Y SECUNDARIO "EL MES DE LAS NIÑAS, NIÑOS Y ADOLESCENTES, A LLEVARSE A CABO DURANTE EL ME… | as enacted, in force 30 July 2017 |
| `ley-2637-e/` | Ley 2637-E: DECLARA PATRIMONIO HISTÓRICO Y CULTURAL DE LA PCIA. AL MURAL "ARGENTINA. DOLOR Y ESPERANZA" | as enacted, in force 16 August 2017 |
| `ley-2636-e/` | Ley 2636-E: DECLARA PATRIMONIO HISTÓRICO CULTURAL DE LA PCIA. AL "MONUMENTO A LOS CAÍDOS EN MARGARITA BELÉN" | as enacted, in force 30 July 2017 |
| `ley-2633-a/` | Ley 2633-A: FONDO DE APOYO AL SISTEMA EDUCATIVO. | as enacted, in force 26 July 2017 |
| `ley-2634-e/` | Ley 2634-E: PROGRAMA DE CONTENIDOS Y ESTRATEGIAS SOBRE EL USO SEGURO Y RESPONSABLE DE LAS TECNOLOGÍAS DE LA INFORMACIÓN Y COMUNICACIÓN (TIC).PARA NIÑOS, NIÑAS Y… | as enacted, in force 26 July 2017 |
| `ley-2635-e/` | Ley 2635-E: BANCO SOLIDARIO DE INSTRUMENTOS MUSICALES. | as enacted, in force 26 July 2017 |
| `ley-2629-a/` | Ley 2629-A: PRORROGA HASTA EL 31 DE DICIEMBRE DE 2017 LA EMERGENCIA ECONÓMICA Y FINANC. SEGÚN LEY 2425-F. (ANTES LEY 7751) | as enacted, in force 30 July 2017 |
| `ley-2621-a/` | Ley 2621-A: EXPROPIA INMUEBLES EN RESISTENCIA PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 30 July 2017 |
| `ley-2622-w/` | Ley 2622-W: CREA EL COMPENDIO PROVINCIAL DE LEGISLACIÓN Y JURISPRUDENCIA INDÍGENA. | as enacted, in force 30 July 2017 |
| `ley-1599-a/` | Ley 1599-A: REUBICACION CARGOS PERSONAL DIRECCION GENERAL DE FINANZAS Y PROGRAMACION PRESUPUESTARIA | as enacted, in force 30 December 2007 |
| `ley-2626-a/` | Ley 2626-A: EXPROPIA INMUEBLE EN GRAL. SAN MARTIN PARA SER TRANSFERIDO AL MUNICIPIO LOCAL | as enacted, in force 30 July 2017 |
| `ley-2620-a/` | Ley 2620-A: EXPROPIA INMUEBLE EN RESISTENCIA PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 3 September 2017 |
| `ley-2627-a/` | Ley 2627-A: EXPROPIA INMUEBLE EN BARRANQUERAS PARA  ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. . | as enacted, in force 30 July 2017 |
| `ley-2625-a/` | Ley 2625-A: EXPROPIA INMUEBLE EN RESISTENCIA POR ENCONTRARSE AFECTADO POR TRAZA DE LA DEFENSA PERMANENTE SOBRE EL RÍO NEGRO EN EL SECTOR DE LA AVENIDA SARMIENTO… | current text only, as of 4 June 2018 |
| `ley-2617-j/` | Ley 2617-J: CONTROL OBLIGATORIO DE EXAMEN TOXICOLÓGICO A LAS FUERZAS DE SEGURIDAD | as enacted, in force 23 June 2017 |
| `ley-2612-j/` | Ley 2612-J: PREVENCIÓN DEL DELITO DE CIBERACOSO | as enacted, in force 23 June 2017 |
| `ley-2613-c/` | Ley 2613-C: ACCESO GRATUITO A ESPECTÁCULOS PÚBLICOS DE MENORES ALOJADOS EN INSTITUCIONES PUBLICAS. | as enacted, in force 3 September 2017 |
| `ley-2608-l/` | Ley 2608-L: REGULACION DE LA ACTIVIDAD DE CADETERIA, MENSAJERIA, MOTOMANDADOS, DELIVERY Y AFINES. CREA REGISTRO. | as enacted, in force 23 June 2017 |
| `ley-2607-v/` | Ley 2607-V: CREA PROGRAMA PROVINCIAL DE TURISMO RELIGIOSO | as enacted, in force 16 June 2017 |
| `ley-2605-f/` | Ley 2605-F: PRESUPUESTO PROVINCIAL EJERCICIO 2017 | as enacted, in force 14 May 2017 |
| `ley-2604-f/` | Ley 2604-F: AUTORIZA AL P.E. ACCEDER A UN CREDITO PUBLICO POR $4.900.000.000,- CRÉA  EN EL ÁMBITO DEL PODER LEGISLATIVO LA COMISIÓN ESPECIAL DE SEGUIMIENTO Y CO… | as enacted, in force 14 May 2017 |
| `ley-2599-a/` | Ley 2599-A: TRIBUNAL ELECTORAL - REVALUACIÓN DE CARGO. | as enacted, in force 16 June 2017 |
| `ley-2598-f/` | Ley 2598-F: EXCEPCION TARIFAS ALUMBRADO PÚBLICO S/ ARTÍCUL0 1º DE LA LEY Nº 506-K | as enacted, in force 16 June 2017 |
| `ley-2596-i/` | Ley 2596-I: ADHESION L.N. 27.263 = DESARROLLO Y FORTALECIMIENTO DEL AUTOPARTISMO ARGENTINO | as enacted, in force 31 May 2017 |
| `ley-2595-a/` | Ley 2595-A: PRORROGA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY Nº 2107-A (ANTES LEY 7206) | as enacted, in force 31 May 2017 |
| `ley-2593-j/` | Ley 2593-J: CREA EL COMPENDIO TEMÁTICO DE LAS VIOLENCIAS | as enacted, in force 31 May 2017 |
| `ley-2592-g/` | Ley 2592-G: ADHESION L.N. 27.305 - LECHE MEDICAMENTOSA | as enacted, in force 12 May 2017 |
| `ley-2591-b/` | Ley 2591-B: DIGESTO JURIDICO. CONSOLIDAR HASTA EL 31 DE DICIEMBRE DEL AÑO 2016. | as enacted, in force 12 May 2017 |
| `ley-2590-p/` | Ley 2590-P: IMPLEMENTAR COMO SIMBOLOS Y EMBLEMAS DE LOS MUNICIPIOS EL USO DE BANDERAS, ESCUDOS ETC. | as enacted, in force 12 May 2017 |
| `ley-2580-a/` | Ley 2580-A: INCREMENTOS SALARIALES PERSONAL DE LA ADMINISTRACION PUBLICA PROVINCIAL | as enacted, in force 12 May 2017 |
| `ley-2574-j/` | Ley 2574-J: ADHESION LEY NACIONAL Nº 27.283 - CREA CONSEJO FEDERAL DE PRECURSORES QUIMICOS | as enacted, in force 21 April 2017 |
| `ley-2573-e/` | Ley 2573-E: ESTUDIO Y APLICACIÓN DE LAS PROSPECTIVAS | as enacted, in force 9 April 2017 |
| `ley-2572-q/` | Ley 2572-Q: ADHESION L.N. 27.278 - 4 DE JULIO "DIA NACIONAL DE LA CONVIVENCIA Y PLURALIDAD EXPRESIONES POLITICAS | as enacted, in force 21 April 2017 |
| `ley-2558-f/` | Ley 2558-F: PRORROGA HASTA EL 30 DE JUNIO DE 2017 LA VIGENCIA DE LA LEY 2425-F (ANTES LEY 7751) | as enacted, in force 15 January 2017 |
| `ley-2570-a/` | Ley 2570-A: PRORROGA POR EL TERMINO DE DOS (2) AÑOS LO PREVISTO EN EL ARTICULO 1º  LEY 2024-K (ANTES LEY 7030) | as enacted, in force 27 January 2017 |
| `ley-2565-a/` | Ley 2565-A: REINSTAURA POR EL TERMINO DE DOS AÑOS, DESDE SU VENCIMIENTO, LEY Nº 1876-A (ANTES LEY 6664) | as enacted, in force 27 January 2017 |
| `ley-2563-a/` | Ley 2563-A: REINSTAURA POR EL TERMINO DE DOS AÑOS, DESDE SU VENCIMIENTO, LEY Nº 1802-A (ANTES 6501) | as enacted, in force 27 January 2017 |
| `ley-2561-a/` | Ley 2561-A: TRANSFIERE INMUEBLES PARA LAS 262 VIVIENDAS DEL BARRIO INSSSEP. | current text only, as of 4 July 2018 |
| `ley-2562-a/` | Ley 2562-A: REINSTAURA POR EL TERMINO DE DOS AÑOS, DESDE SU VENCIMIENTO, LEY Nº 1563-A (ANTES LEY 5956) | as enacted, in force 27 January 2017 |
| `ley-2571-e/` | Ley 2571-E: CENTRO PEDAGÓGICO DE PRODUCC. Y DISTRIB. TIFLOTECNODIGITAL - EDITORIAL BRAILLE ROBERTO E. TOULLIEUX | as enacted, in force 27 January 2017 |
| `ley-2556-a/` | Ley 2556-A: EXPROPIA INMUEBLE EN LA LOCALIDAD DE CAPITÁN SOLARI MP/ADJUDICAR EN VENTA ACT. OCUP. | as enacted, in force 25 January 2017 |
| `ley-2557-a/` | Ley 2557-A: EXPROPIA INMUEBLE EN RCIA. PARA TRANSFERIR A LA COOPERATIVA DE TRABAJO Y CONSUMO INIMBO | current text only, as of 30 May 2023 |
| `ley-2555-g/` | Ley 2555-G: PROGRAMA DE DETECCIÓN TEMPRANA DE LA ENFERMEDAD RENAL CRÓNICA EN PEDIATRÍA | as enacted, in force 22 January 2017 |
| `ley-2554-g/` | Ley 2554-G: CREA LA FIGURA DE "PROMOTOR DE SALÚD COMUNITARIO" Y PROGRAMA DE FORMACION | as enacted, in force 22 January 2017 |
| `ley-2553-b/` | Ley 2553-B: PROMOCION Y PROTECCION INTEGRAL DE LAS PERSONAS ADULTAS MAYORES. | as enacted, in force 20 January 2017 |
| `ley-2551-a/` | Ley 2551-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 20 January 2017 |
| `ley-2549-a/` | Ley 2549-A: FISCALIA DE ESTADO  - CREA "PERMANENCIA EN EL CARGO"  FUNCIONARIOS Y EMPLEADOS | as enacted, in force 1 January 2017 |
| `ley-2547-e/` | Ley 2547-E: BONIFICACION POR TITULO PARA PERSONAL DOCENTE COMPRENDIDO EN LEY 647-E (ANTES  3529) | as enacted, in force 1 January 2017 |
| `ley-2548-a/` | Ley 2548-A: BONIFICACION POR FUNCIONES ESPECIALES PARA INSTITUTO PCIAL. P/LA INCLUSION P/PERSONAS C/DISCAPACIDAD (IProDiCh) | as enacted, in force 1 January 2017 |
| `ley-2552-a/` | Ley 2552-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 20 January 2017 |
| `ley-2546-a/` | Ley 2546-A: MODERNIZ. DCCION. GRAL. DE ARCHIVO PODER JUDICIAL-INCORPORA INC. H) ART.4º L.840-F | as enacted, in force 22 January 2017 |
| `ley-2544-a/` | Ley 2544-A: CAMBIO UBICACION INMUEBLE EDIFICIO "SEDE DEL PODER LEGISLATIVO" | as enacted, in force 25 December 2016 |
| `ley-2542-a/` | Ley 2542-A: REINSTAURA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 1894-A (ANTES LEY 6710) | as enacted, in force 1 January 2017 |
| `ley-2543-e/` | Ley 2543-E: MONUMENTO ESCULTÓRICO PCIAL. A LA MEMORIA DE LAS VICTIMAS DE LA "MASACRE DE NAPALPI" | as enacted, in force 19 February 2017 |
| `ley-2539-i/` | Ley 2539-I: OBSERVATORIO P/EL FORTALECIMIENTO DEL CONSUMO SUSTENTABLE EN LA PCIA. DEL CHACO | as enacted, in force 8 January 2017 |
| `ley-2538-e/` | Ley 2538-E: DECLARA PATRIMONIO HISTORICO Y CULTURAL ESCUELA DE ENSEÑANZA PRIM. Nº 8 EN PTO. BASTIANI | as enacted, in force 1 January 2017 |
| `ley-2540-a/` | Ley 2540-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 1 January 2017 |
| `ley-2537-p/` | Ley 2537-P: CREA FOROS MUNICIPALES DE CONSUMO PROBLEMATICO | as enacted, in force 1 January 2017 |
| `ley-2536-g/` | Ley 2536-G: ADHESION L.N. 26.934 -PLAN INTEGRAL P/EL ABORDAJE DE LOS CONSUMOS PROBLEMATICOS | as enacted, in force 8 January 2017 |
| `ley-2541-a/` | Ley 2541-A: PRORROGA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2265-A (ANTES LEY 7511) | as enacted, in force 1 January 2017 |
| `ley-2535-e/` | Ley 2535-E: INSTITUYE EL DIA 19 DE DICIEMBRE DE CADA AÑO COMO DIA DEL NARRADOR ORAL CHAQUEÑO | as enacted, in force 21 December 2016 |
| `ley-2533-j/` | Ley 2533-J: VISU MEDICO Y REQUISA DE PERSONAS TRANS EN SERV. PENITENCIAROS Y POLICIA DE LA PCIA. | as enacted, in force 21 December 2016 |
| `ley-2534-e/` | Ley 2534-E: CREA UNA PAGINA WEB "AGENDA CULTURAL CHACO" | as enacted, in force 25 December 2016 |
| `ley-2531-t/` | Ley 2531-T: ESTABLECE OBLIGATORIEDAD DE COLOCAR CARTEL CON LA LEYENDA "SI VA A CONDUCIR, NO CONSUMA BEBIDAS ALCOHOLICAS", EN RESTAURANTES,  CONFITERIAS, ETC. | as enacted, in force 25 December 2016 |
| `ley-2532-j/` | Ley 2532-J: ESTABLECE OBLIGATORIA P/ASPIRANTES DE LA POLICIA LA VISITA A LA CASA DE LA MEMORIA | as enacted, in force 21 December 2016 |
| `ley-2530-g/` | Ley 2530-G: PROGRAMA DE PREVENCIÓN DE LA VIOLENC. Y SEGUR. EN EL AMBITO DEL SISTEMA DE SALUD | as enacted, in force 25 December 2016 |
| `ley-2528-a/` | Ley 2528-A: INSTITUYE EL DÍA 19 DE SEPTIEMBRE DE CADA AÑO COMO EL "DIA DEL EMPLEADO DE LA ADM. TRIBUTARIA" | as enacted, in force 25 December 2016 |
| `ley-2529-e/` | Ley 2529-E: FINALIZACION TRANSFORMAC. ESCUELAS EDUCAC. TECNICO-PROFESIONAL NIVEL SECUND. E INST. DE EDUCAC. TECNICO PROFES. NIVEL SUPERIOR | as enacted, in force 25 December 2016 |
| `ley-2522-a/` | Ley 2522-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 14 December 2016 |
| `ley-2523-c/` | Ley 2523-C: DERECHO DE IDENTIDAD DE GÉNERO DE LAS PERSONAS | as enacted, in force 14 December 2016 |
| `ley-2519-f/` | Ley 2519-F: SINCERAMIENTO FISCAL-REGULARIZACIÓN DE OBLIGACIONES TRIBUTARIAS PROVINCIALES | as enacted, in force 4 December 2016 |
| `ley-2516-m/` | Ley 2516-M: MODIFICA COMPETENCIA JUZGADO CIVIL Y COMERCIAL Nº 8 PRIMERA CIRCUNSCR. JUDICIAL | as enacted, in force 14 December 2016 |
| `ley-2517-p/` | Ley 2517-P: CONVIERTENSE EN SUBSIDIOS NO REINTEGRABLES ANTICIPOS TRANSITORIOS A MUNICIPIOS | as enacted, in force 14 December 2016 |
| `ley-2526-i/` | Ley 2526-I: PRORROGA POR CUATRO (4) AÑOS, A PARTIR DEL 09/01/2017, LA VIGENCIA DE LA LEY 937-I (ANTES LEY 4453) | as enacted, in force 30 November 2016 |
| `ley-2520-i/` | Ley 2520-I: ADHESION L.N. 27.264 - PROGRAMA DE RECUPERACIÓN PRODUCTIVA | as enacted, in force 14 December 2016 |
| `ley-2518-q/` | Ley 2518-Q: INSTITUYE EL DIA 14 DE NOVIEMBRE DE C.A. COMO EL "DIA DEL MILITANTE SOCIALISTA" | as enacted, in force 14 December 2016 |
| `ley-2525-g/` | Ley 2525-G: JORNADA ESTUDIANTIL DE CONCIENTIZACIÓN Y PREVENCIÓN SOBRE ADICCIONES | as enacted, in force 14 December 2016 |
| `ley-2524-g/` | Ley 2524-G: INSTITUYE EL DIA 5 DE NOVIEMBRE DE CADA AÑO COMO "DIA DEL PAYAMEDICO" | as enacted, in force 14 December 2016 |
| `ley-2515-a/` | Ley 2515-A: EXPROPIA INMUEBLE EN VILLA ANGELA A FAVOR DEL INSTITUTO DE CULTURA DE LA PCIA. | current text only, as of 30 November 2016 |
| `ley-2513-e/` | Ley 2513-E: DECLARA PATRIM. HISTÓRICO Y CULTURAL DE LA PCIA. EDIFICIO PARROQUIA SAGR. CORAZON DE JESÚS DE VILLA ANGELA | as enacted, in force 30 November 2016 |
| `ley-2514-a/` | Ley 2514-A: EXPROPIA INMUEBLE EN VILLA ANGELA P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 30 November 2016 |
| `ley-2511-a/` | Ley 2511-A: INSTITUYE EL 2 DE DICIEMBRE DE CADA AÑO COMO "DIA DEL EMPLEADO DEL IPDUV" | as enacted, in force 2 December 2016 |
| `ley-2512-i/` | Ley 2512-I: PROHIBE SALIDA DE LA PCIA. DEL CHACO MADERA AUTÓCTONA SIN PROCESO DE INDUSTRIALIZACIÓN. MODIFICA LEY  2079-R (ANTES LEY 7153) | as enacted, in force 9 November 2016 |
| `ley-2509-l/` | Ley 2509-L: ADHIERE LA PROVINCIA DEL CHACO A LA LEY NACIONAL Nº 26.816 REGIMEN FEDERAL DE EMPLEO PROTEGIDO PARA LAS PERSONAS CON DISCAPACIDAD Y SU DECRETO REGLA… | as enacted, in force 9 November 2016 |
| `ley-2510-v/` | Ley 2510-V: INSTITUYE EL DIA 22 DE OCTUBRE DE CADA AÑO COMO "DIA DEL ECOTURISMO CHAQUEÑO" | as enacted, in force 9 November 2016 |
| `ley-2508-a/` | Ley 2508-A: EXPROPIA INMUEBLE EN BQUERAS. P/ TALLER DE DANZAS FOLCLORICAS "LUCERO DEL ALBA" | current text only, as of 9 November 2016 |
| `ley-2507-a/` | Ley 2507-A: REINSTAURA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2045-A (ANTES LEY 7082) | as enacted, in force 9 November 2016 |
| `ley-2506-a/` | Ley 2506-A: EL PODER EJECUTIVO TRANSFIERE UN INMUEBLE AL MUNICIPIO DE COLONIAS UNIDAS | as enacted, in force 9 November 2016 |
| `ley-2505-q/` | Ley 2505-Q: CREA MESA DE CONCERTACIÓN POLITICA Y SOCIAL EN LA PROVINCIA. | as enacted, in force 2 December 2016 |
| `ley-2502-i/` | Ley 2502-I: ADHESION L.N. 27.262 - GRANOS PLAGUICIDAS FUMIGANTES - PROHIBICION | as enacted, in force 26 October 2016 |
| `ley-2503-a/` | Ley 2503-A: EXPROPIA INMUEBLE EN J.J. CASTELLI P/ TRANSFERIR AL MUNICIPIO DESTINADO A ESPACIOS VERDES Y RECREACIÓN | current text only, as of 26 October 2016 |
| `ley-2500-a/` | Ley 2500-A: REINSTAURA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 1950-A (ANTES LEY 6826) | as enacted, in force 21 October 2016 |
| `ley-2499-a/` | Ley 2499-A: REINSTAURA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 1918-A (ANTES LEY 6772) | as enacted, in force 21 October 2016 |
| `ley-2498-a/` | Ley 2498-A: EXPROPIA INMUEBLE EN RCIA. PARA PÀRQUE URBANO AMBIENTAL Y PRESERV. SIST. LACUSTRE LAGUNA COLUSSI . | current text only, as of 21 October 2016 |
| `ley-2497-a/` | Ley 2497-A: CREACIÓN OFICINA DE OBJETOS ENCONTRADOS . | as enacted, in force 21 October 2016 |
| `ley-2494-e/` | Ley 2494-E: DECLARA PATRIMONIO HISTORICO Y CULTURAL DE LA PCIA. ESCUELA PRIMARIA Nº 5 "RUY DIAZ DE GUZMAN" | as enacted, in force 16 October 2016 |
| `ley-2493-e/` | Ley 2493-E: DECLARA CANCION POPULAR DEL CHACO LETRA Y MUSICA "CHACO TAMBIEN" DE ZITTO SEGOVIA | as enacted, in force 30 September 2016 |
| `ley-2490-g/` | Ley 2490-G: REGIMEN DE CUIDADOR DOMICILIARIO Y/O POLIVALENTE | as enacted, in force 16 October 2016 |
| `ley-2491-a/` | Ley 2491-A: TRANSFERENCIA INMUEBLE EN DPTO. LIBERTAD A LA UNION INDUSTRIAL DEL CHACO . | current text only, as of 16 September 2016 |
| `ley-2492-s/` | Ley 2492-S: ADHESION L.N.27.202 - LEY DE DEPORTE. | as enacted, in force 16 October 2016 |
| `ley-2486-a/` | Ley 2486-A: CREA LA OFICINA DE TRANSPARENCIA Y ACCESO A LA INFORMACION PÚBLICA | as enacted, in force 21 September 2016 |
| `ley-2484-a/` | Ley 2484-A: EL IPDUV TRANSFIERE INMUEBLE PARA FUNCIONAMIENTO DE LA "CASA DE MEDIO CAMINO" | current text only, as of 21 September 2016 |
| `ley-2482-e/` | Ley 2482-E: DECLARA PATRIMONIO HISTORICO Y CULTURAL DE LA PCIA. ESCUELA PRIMARIA Nº 9 LAGUNA BLANCA | as enacted, in force 2 October 2016 |
| `ley-2485-a/` | Ley 2485-A: REINSTAURA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2057-A (ANTES LEY 7115) | as enacted, in force 2 October 2016 |
| `ley-2483-r/` | Ley 2483-R: ADHESION L.N. 27.191 - DECLARA DE INTERES PCIAL. UTILIZACION FUENTES RENOVABLES DE ENERGIA | current text only, as of 16 May 2018 |
| `ley-2481-w/` | Ley 2481-W: PRESERVACION Y MEMORIA DE LA ONOMÁSTICA GEOGRAFICA PROVINCIAL | as enacted, in force 14 September 2016 |
| `ley-2479-a/` | Ley 2479-A: PRORROGA POR DOS (2) AÑOS LA VIGENCIA DE LA LEY 1876-A (ANTES LEY 6664) | as enacted, in force 11 September 2016 |
| `ley-2478-w/` | Ley 2478-W: INSTITUYE COMO DIA DE LA DIVERSIDAD LINGUISTICA EL 14 DE JULIO DE CADA AÑO, EN CONMEMORACION LEY Nº 1848-W | as enacted, in force 14 August 2016 |
| `ley-2476-a/` | Ley 2476-A: EXPROPIA INMUEBLE EN RCIA. PARA TRANSFERIR A LA FUNDACION GASTON | current text only, as of 6 December 2018 |
| `ley-2473-a/` | Ley 2473-A: REINSTAURASE POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 1931-A (ANTES LEY 6790) | as enacted, in force 5 August 2016 |
| `ley-2470-a/` | Ley 2470-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 5 August 2016 |
| `ley-2469-x/` | Ley 2469-X: ACUERDO NACION-PROVINCIAS SUSCRIPTO EL 18/05/2016 EN  LAS CIUDAD DE CORDOBA . | as enacted, in force 15 July 2016 |
| `ley-2466-i/` | Ley 2466-I: CREASE EL REGISTRO PCIAL. DE ELABORACIÓN DE ALIMENTOS ARTESANALES | as enacted, in force 5 August 2016 |
| `ley-2467-e/` | Ley 2467-E: PREMIO ANUAL DEL PODER LEGISLATIVO AL ESFUERZO EDUCATIVO | as enacted, in force 5 August 2016 |
| `ley-2463-w/` | Ley 2463-W: TITULARIZACION DOCENTES INDIGENAS DE LA PROVINCIA | as enacted, in force 20 July 2016 |
| `ley-2459-a/` | Ley 2459-A: ESTABLECE CON ALCANCES ACLARATORIOS, REFERENTE AL ARTÍCULO 1º DE LA LEY 6028 | as enacted, in force 24 June 2016 |
| `ley-2458-e/` | Ley 2458-E: DECLARA PATRIMONIO HISTORICO CULTURAL EDIFICIO EX SINDICATO UNICO DE AGRIC. DEL CHACO. | as enacted, in force 24 June 2016 |
| `ley-2448-j/` | Ley 2448-J: ESTABLECE LA OBLIGATORIEDAD DE REALIZAR AVISOS PUBLICITARIOS DESTINADOS A BRINDAR INFORMACION S/LA PREVENCION DE LA VIOLENCIA DE GENERO, ANTE LOS TR… | as enacted, in force 19 June 2016 |
| `ley-2456-a/` | Ley 2456-A: NUEVA ESCALA DE REMUNERACIONES A PARTIR DEL 1º/03/2016  Y 1º/07/2016, PERSONAL DE SEGURIDAD. L.1134 Y L.6117 | as enacted, in force 12 June 2016 |
| `ley-2453-a/` | Ley 2453-A: NUEVA ESCALA SALARIAL PARA EL PERSONAL DE LA ADM. PUBLICA A PARTIR DEL 1º/03/2016 y 1º/07/2016, L.196-A (Antes L.1276) | as enacted, in force 12 June 2016 |
| `ley-2444-f/` | Ley 2444-F: AUTORIZA AL PODER EJECUTIVO A CONTRAER EMPRESTITOS POR HASTA LA SUMA DE $ 4.000.000.000 | as enacted, in force 11 May 2016 |
| `ley-2440-e/` | Ley 2440-E: ADHESIÓN L.N. 27.234 = EDUCAR EN IGUALDAD: PREVENCIÓN Y ERRADIC. VIOL. DE GENERO | as enacted, in force 6 May 2016 |
| `ley-2438-a/` | Ley 2438-A: CREÁNSE CIENTO VEINTESEIS  (126) CARGOS EN LA JURISDICCION 21: POLICIA PROVINCIAL, EN EL ESCALAFON PERSONAL DE SEGURIDAD. | as enacted, in force 27 April 2016 |
| `ley-2429-j/` | Ley 2429-J: CREASE EL "SISTEMA PROVINCIAL DE PREVENCION Y PROTECCION C/DESCARGAS ELECTRICAS ATMOSFERICAS" | as enacted, in force 22 May 2016 |
| `ley-2427-j/` | Ley 2427-J: ADHESION L.N. 27.176 - "DIA NACIONAL DE LA LUCHA CONTRA LA VIOLENCIA  DE GENERO" | as enacted, in force 17 April 2016 |
| `ley-2426-x/` | Ley 2426-X: APRUEBA CONVENIO EN EL MARCO DEL PROGRAMA FEDERAL DE DESENDEUDAMIENTO DE LAS PCIAS. ARGENTINAS | as enacted, in force 27 March 2016 |
| `ley-2425-f/` | Ley 2425-F: DECLARA EMERGENCIA ECONOMICA Y FINANCIERA A LA PROVINCIA DEL CHACO HASTA 30/06/2016 (SEPARATA B.O.:9879) | as enacted, in force 6 January 2016 |
| `ley-2423-a/` | Ley 2423-A: MODIFICA LOS ARTÍCULOS 4, 12 Y 15 DE LA LEY 196-A Y ARTÍCULO 7º DE LA LEY 1583-A  (ANTES LEY 6009). | as enacted, in force 14 September 2016 |
| `ley-2421-a/` | Ley 2421-A: PRESUPUESTO PROVINCIAL EJERCICIO 2016 (SEPARATA B.O. Nº 9880) | as enacted, in force 8 January 2016 |
| `ley-2418-a/` | Ley 2418-A: BONIFICACION ESPECIAL PARA PERSONAL DE LA JURISDICCION 02: SECRETARIA GENERAL DE LA GOBERNACIÓN | as enacted, in force 20 January 2016 |
| `ley-2410-a/` | Ley 2410-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | current text only, as of 22 June 2018 |
| `ley-2420-a/` | Ley 2420-A: LEY DE MINISTERIOS. DEROGA LEY Nº 6906 | as enacted, in force 25 December 2015 |
| `ley-2419-d/` | Ley 2419-D: ESTABLECE "CLAUSULA INEFICAZ" A LA PUBLICACION EN PLAYAS DE ESTACIONAMIENTO VEHICULAR | as enacted, in force 20 January 2016 |
| `ley-2417-a/` | Ley 2417-A: ADICIONAL POR TAREA ESPECIFICA PERSONAL DEL MRIO. DE DESARROLLO SOCIAL | as enacted, in force 20 January 2016 |
| `ley-2411-a/` | Ley 2411-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 20 January 2016 |
| `ley-2415-a/` | Ley 2415-A: CREA EL FONDO DE FORTALECIMIENTO DE GESTION INSTITUCIONAL P/PERSONAL P.E. | as enacted, in force 20 January 2016 |
| `ley-2412-a/` | Ley 2412-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 20 January 2016 |
| `ley-2409-a/` | Ley 2409-A: CREACION DEL INSTITUTO DE LA MUJER Y LA FAMILIA (I.M.FA.) | as enacted, in force 4 March 2016 |
| `ley-2416-a/` | Ley 2416-A: MODIFICA PARCIALMENTE EL DECRETO 2320/77 | as enacted, in force 20 January 2016 |
| `ley-2413-a/` | Ley 2413-A: EXPROPIA INMUEBLE EN RCIA. PARA FUNCIONAMIENTO CLUB SOCIAL, CULT. Y DEP. "VILLA LIBERTAD" | current text only, as of 22 June 2018 |
| `ley-2408-a/` | Ley 2408-A: EL PODER EJECUTIVO TRANSFIERE INMUEBLE A FAVOR DE ASOCIACION  ARGENTINA PADRES DE AUTISTAS (APADEA) | as enacted, in force 27 December 2015 |
| `ley-2414-a/` | Ley 2414-A: CREA EL BASTON DE GOBERNADOR | as enacted, in force 25 December 2015 |
| `ley-2407-a/` | Ley 2407-A: CREA EN TODAS LAS BIBLIOTECAS DEL SUBSISTEMA BIBLIOTECARIO DE LA PCIA. LA TEMATICA "CHACO" | as enacted, in force 8 January 2016 |
| `ley-2401-a/` | Ley 2401-A: EXPROPIA INMUEBLES EN MACHAGAI PARA CONSTRUCCION COMPLEJO EDUCATIVO, ETC. | as enacted, in force 8 January 2016 |
| `ley-2396-b/` | Ley 2396-B: DIGESTO JURIDICO. CONSOLIDAR HASTA EL 31 DE DICIEMBRE DEL AÑO 2014. | as enacted, in force 18 December 2015 |
| `ley-2400-t/` | Ley 2400-T: BOLETO ESTUDIANTIL GRATUITO | as enacted, in force 18 December 2015 |
| `ley-2398-i/` | Ley 2398-I: ESTABLECE A PARTIR DEL 1º/06/15 ASIGNACION ESPECIAL PERSONAL MINISTERIO DE PRODUCCIÓN | as enacted, in force 20 January 2016 |
| `ley-2397-a/` | Ley 2397-A: INGRESO A PLANTA PERMANENTE PERSONAL DEL ENTE EX- FIESTA NACIONAL DEL ALGODON | as enacted, in force 4 December 2015 |
| `ley-2399-j/` | Ley 2399-J: CRITERIOS MINIMOS SOBRE LA ACTUACION DE LOS CUERPOS POLICIALES Y FUERZAS DE SEGURIDAD EN MANIFESTACIONES PUBLICAS | as enacted, in force 18 December 2015 |
| `ley-2394-a/` | Ley 2394-A: MODIFICA ARTÍCULO 41 DE LA LEY 1903-C (ANTES LEY 6723) | as enacted, in force 2 December 2015 |
| `ley-2395-w/` | Ley 2395-W: INSTITUYESE EL DIA 13 DE NOVIEMBRE DE CADA AÑO COMO "DIA PROVINCIAL DE LA MUJER INDÍGENA" | as enacted, in force 18 December 2015 |
| `ley-2391-a/` | Ley 2391-A: EL PODER EJECUTIVO TRANSFIERE AL ESTADO NACIONAL INMUEBLE EN PUERTO TIROL PARA COMPLEJO PENITENCIARIO FEDERAL | as enacted, in force 2 December 2015 |
| `ley-2392-a/` | Ley 2392-A: REINSTAURASE POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2046-A (ANTES LEY 7083) | as enacted, in force 18 December 2015 |
| `ley-2390-a/` | Ley 2390-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 17 April 2016 |
| `ley-2383-a/` | Ley 2383-A: MODIFICA LOS ARTÍCULOS 1º Y 2º DE LA LEY 7589. FIJASE EL ESTADO DOCENTE EN 800 PUNTOS A PARTIR DEL 01/10/15. | as enacted, in force 18 December 2015 |
| `ley-2387-a/` | Ley 2387-A: CRÉASE EL "FIDEICOMISO DE FORTALECIMIENTO INSTITUCIONAL DEL PODER LEGISLATIVO" | as enacted, in force 18 December 2015 |
| `ley-2389-a/` | Ley 2389-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 2 December 2015 |
| `ley-2385-a/` | Ley 2385-A: ADHESION L.N. 26.968 = PROHIBICION VENTA DE ADHESIVOS PEGAMENTOS, ETC. A MENORES | as enacted, in force 2 December 2015 |
| `ley-2380-d/` | Ley 2380-D: PROHIBE EFECTUAR DIFERENCIAS DE PRECIO DE CONTADO O CON TARJETAS DE CRÉDITO-DÉBITO | as enacted, in force 18 November 2015 |
| `ley-2377-p/` | Ley 2377-P: CREA EL FONDO COMPENSADOR MUNICIPAL PARA MUNICIPIOS DE FONTANA, MACHAGAI Y JUAN JOSE CASTELLI | as enacted, in force 4 November 2015 |
| `ley-2370-a/` | Ley 2370-A: PRORROGA POR EL TERMINO DE DOS AÑOS, A PARTIR DE SU SANCION, LEY Nº  2085-A (ANTES LEY 7161) | as enacted, in force 4 November 2015 |
| `ley-2369-a/` | Ley 2369-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 1 November 2015 |
| `ley-2372-a/` | Ley 2372-A: INSTITUYE EL "PREMIO PROVINCIAL DE LUCHA CONTRA LA VIOLENCIA INSTITUCIONAL, DR. MARIO FEDERICO BOSCH" | as enacted, in force 4 November 2015 |
| `ley-2368-a/` | Ley 2368-A: DESAFECTACION INMUEBLES PROPIEDAD DEL ESTADO PCIAL. EN DPTO SAN FERNANDO | as enacted, in force 1 November 2015 |
| `ley-2366-a/` | Ley 2366-A: PRORROGA POR DOS (2) AÑOS LA VIGENCIA DE LA LEY 2110-A (ANTES LEY 7212) | as enacted, in force 25 October 2015 |
| `ley-2365-b/` | Ley 2365-B: LEY PROVINCIAL DE JUVENTUD | as enacted, in force 11 October 2015 |
| `ley-2363-e/` | Ley 2363-E: INCORPORA PERSONAL DEL MRIO. DE EDUCACION A PLANTA PERMANENTE | as enacted, in force 18 September 2015 |
| `ley-2364-n/` | Ley 2364-N: JUICIO PENAL POR JURADOS.INCORPORA INC D) AL ART.1º Y MODIFICA ART. 103 DE LA LEY Nº 1-B (ANTES LEY 3) | as enacted, in force 25 September 2015 |
| `ley-2362-p/` | Ley 2362-P: CREA EL MUNICIPIO DE TERCERA CATEGORIA DE COLONIA ABORIGEN. | as enacted, in force 11 September 2015 |
| `ley-2357-a/` | Ley 2357-A: PRORROGA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 1919-A | as enacted, in force 11 September 2015 |
| `ley-2358-a/` | Ley 2358-A: OTORGA A PARTIR DEL 1º/03/15 BONIFICACION ESPECIAL P/ PERSONAL ADM. PUBLICA | as enacted, in force 11 September 2015 |
| `ley-2353-a/` | Ley 2353-A: INSTITUYE EL 19 DE NOVIEMBRE DE CADA AÑO COMO EL "DIA PCIAL. DE LAS FERIAS FRANCAS" | as enacted, in force 16 August 2015 |
| `ley-2354-x/` | Ley 2354-X: APRUEBA CONVENIO SUSCRIPTO PCIA.-NACION PROGRAMA FEDERAL DE DESENDEUDAMIENTO DE LAS PCIAS. ARGENTINAS | as enacted, in force 7 August 2015 |
| `ley-2352-j/` | Ley 2352-J: PROHIBESE EN LA PCIA. LA VENTA A MENORES DE 18 AÑOS PURPURINA Y/O BRILLANTINA | as enacted, in force 16 August 2015 |
| `ley-2350-k/` | Ley 2350-K: EL IPDUV TRANSFIERE AL MRIO. DE EDUCACION INMUEBLE EN GRAL. SAN MARTIN P/ESCUELA SECUNDARIA Nº 139 | current text only, as of 11 June 2019 |
| `ley-2348-a/` | Ley 2348-A: EL P.E ADJUDICARA EN VENTA UN INMUEBLE  EN DPTO. S.FER. P/RADICACION Y PROM. INDUSTRIAL | as enacted, in force 14 August 2015 |
| `ley-2347-x/` | Ley 2347-X: PROGRAMA DE FOMENTO E INCENTIVO A LA ACTIVIDAD AERONAUTICA | as enacted, in force 14 August 2015 |
| `ley-2346-a/` | Ley 2346-A: EXPROPIA INMUEBLE EN RCIA. P/ JARDIN DE INFANTES Nº 184 "ZITO SEGOVIA" EX E.G.B. 404 | current text only, as of 15 June 2018 |
| `ley-2340-a/` | Ley 2340-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 14 August 2015 |
| `ley-2345-a/` | Ley 2345-A: ESTABLECE LAS BASES PARA EL FUNCIONAMIENTO DE  LA CIUDAD ADMINISTRATIVA | as enacted, in force 7 August 2015 |
| `ley-2344-a/` | Ley 2344-A: REGIMEN DE ORGANIZ. Y FUNCIONAM. DEL INST. PCIAL. P/LA INCLUSION PERSONAS C/DISCAPACIDAD | as enacted, in force 14 August 2015 |
| `ley-2341-a/` | Ley 2341-A: REINSTAURA POR EL TERMINO DE DOS AÑOS, A PARTIR DE SU SANCION, LEY Nº 1898-A (ANTES LEY 6717) | as enacted, in force 14 August 2015 |
| `ley-2336-e/` | Ley 2336-E: EL CONSEJO DE EDUCACION TRANFIERE INMUEBLE AL MRIO. DE DES. URBANO Y TERRITORIAL | as enacted, in force 7 August 2015 |
| `ley-2337-a/` | Ley 2337-A: EXPROPIA INMUEBLE EN RCIA. PARA LA ASOCIACION CIVIL CLUB DEPORTIVO LUJAN | as enacted, in force 7 August 2015 |
| `ley-2335-l/` | Ley 2335-L: MECANISMOS QUE RESGUARDAN LOS DERECHOS Y ESTABILIDAD LABORAL DE LOS DOCENTES | as enacted, in force 7 August 2015 |
| `ley-2338-a/` | Ley 2338-A: REINSTAURA POR EL TERMINO DE DOS AÑOS (24/06/2017), A PARTIR DE SU SANCION, LEY Nº 2125-A (ANTES LEY N° 7244) | as enacted, in force 7 August 2015 |
| `ley-2332-a/` | Ley 2332-A: REINSTAURASE POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 7161 | as enacted, in force 5 August 2015 |
| `ley-2329-a/` | Ley 2329-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 5 August 2015 |
| `ley-2333-h/` | Ley 2333-H: FIJA A PARTIR DEL 1º/03/15 NUEVOS MONTOS DE ASIGNACIONES FAMILIARES S/LEY 3049 | as enacted, in force 22 July 2015 |
| `ley-2331-a/` | Ley 2331-A: REINSTAURASE POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 1872-A (ANTES LEY 6653) | as enacted, in force 5 August 2015 |
| `ley-2325-a/` | Ley 2325-A: JUICIO DE RESIDENCIA | as enacted, in force 2 August 2015 |
| `ley-2323-a/` | Ley 2323-A: CREA LA UNIDAD DE TASA DIFERENCIAL O SOBRETASA APLICABLE POR LA DCCION. GRAL. DEL REGISTRO CIVIL | as enacted, in force 17 July 2015 |
| `ley-2322-a/` | Ley 2322-A: CREA LA UNIDAD DE TASA DIFERENCIAL O SOBRETASA APLICABLE POR DCCION. DEL REG. DE LA PROPIEDAD INMUEBLE | as enacted, in force 17 July 2015 |
| `ley-2324-a/` | Ley 2324-A: RETRIBUCION  REMUNERATIVA  NO BONIFICABLE PERSONAL TRIBUNAL ELECTORAL | as enacted, in force 17 July 2015 |
| `ley-2320-i/` | Ley 2320-I: ESTABLECE RESTRICCIONES P/ASENTAMIENTOS Y EMPRENDIMIENTOS AGRIC.-GAN. SAN MARTIN | as enacted, in force 5 July 2015 |
| `ley-2318-p/` | Ley 2318-P: EL P.E. TRANSFIERE AL MUNICIPIO DE RCIA. INMUEBLE P/INSTALACION CEMENTERIO MUNICIPAL | as enacted, in force 1 July 2015 |
| `ley-2316-e/` | Ley 2316-E: ADHESION L.N.27.064 - REGULACION Y SUPERV. DE INSTIT. DE EDUCACION NO INCLUIDAS EN LA ENSEÑANZA OFICIAL | as enacted, in force 2 July 2015 |
| `ley-2315-a/` | Ley 2315-A: EXPROPIA INMUEBLES EN LAGUNA BLANCA P/ LA CONSTRUCCION PROGRAMAS HABITACIONALES | current text only, as of 11 August 2015 |
| `ley-2312-w/` | Ley 2312-W: DECLARA DE CARACTER OBLIGATORIO, UN ASISTENTE BILINGÜE P/PACIENTE INDIGENA QUE NO HABLEN ESPAÑOL | as enacted, in force 1 July 2015 |
| `ley-2310-a/` | Ley 2310-A: EL P.E. TRANSFIERE  INMUEBLE EN DPTO. S. FERNANDO A LA ASOC.BARRIO PARQUE INDEPENDENCIA | as enacted, in force 2 August 2015 |
| `ley-2313-w/` | Ley 2313-W: INSTITUYE EL 13 DE MAYO DE CADA AÑO "DIA DE LA REAFIRMACIÓN DE LOS DERECHOS DE LOS PUEBLOS INDIGENAS EN LA PCIA. DEL CHACO" | as enacted, in force 21 June 2015 |
| `ley-2309-a/` | Ley 2309-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 7 June 2015 |
| `ley-2304-n/` | Ley 2304-N: ADHIERE A LA LEY NACIONAL Nº 23.737  - REGIMEN PENAL DE ESTUPEFACIENTES | as enacted, in force 29 May 2015 |
| `ley-2307-a/` | Ley 2307-A: DISPONE LA INSCRIPCION DE "AUSENTE POR DESAPARICION FORZADA" LEGAJOS AGENTES ADM. PCA. PCIAL. | as enacted, in force 12 June 2015 |
| `ley-2306-a/` | Ley 2306-A: PERMISO POR NATALICIO PARA PERSONAL DEPENDIENTE DEL PODER JUDICIAL, TRIBUNAL ELECTORAL, CONSEJO DE LA MAGISTRATURA Y JURADO DE ENJUICIAMIENTO | as enacted, in force 12 June 2015 |
| `ley-2301-t/` | Ley 2301-T: USO OBLIGATORIO DE CHALECOS REFLECTANTES P/CONDUCTORES Y ACOMPAÑANTES DE MOTOCICLETAS, CICLOMOTORES Y BICICLETAS. | as enacted, in force 7 June 2015 |
| `ley-2308-a/` | Ley 2308-A: IMPLEMENTA ESPACIO AMIGO DE LA LACTANCIA DENTRO DEL AMBITO DE LA ADM. PUBLICA | as enacted, in force 12 June 2015 |
| `ley-2302-a/` | Ley 2302-A: CREA A PARTIR DEL 01/01/15, CARGOS Y HORAS CATEDRA EN LA JUR. 29. PLANILLA COMPLEMENTARIA AL PRESUPUESTO GENERAL PERIODO 2015 | as enacted, in force 29 May 2015 |
| `ley-2300-k/` | Ley 2300-K: DECLARA DE INTERES PUBLICO PCIAL. EL PLAN ELECTRICO PCIAL. 2013-2033 | as enacted, in force 7 June 2015 |
| `ley-2295-f/` | Ley 2295-F: ADHESION L.N. 26.530 - PRORROGA REGIMEN FEDERAL DE RESPONSABILIDAD FISCAL | as enacted, in force 20 May 2015 |
| `ley-2298-x/` | Ley 2298-X: DECLARA DE INTERES GENERAL CONVENIO DE ENTENDIMIENTO MRIO. DE ECON. NAC. Y PCIA. | as enacted, in force 20 May 2015 |
| `ley-2297-a/` | Ley 2297-A: RESTITUYE LA VIGENCIA DE LA LEY 1760-A POR EL TERMINO DE DOS AÑOS | as enacted, in force 29 May 2015 |
| `ley-2294-e/` | Ley 2294-E: INSTITUYE EL 19 DE FEBRERO DE CADA AÑO EL "DIA PROVINCIAL DE LOS PERROS GUIAS" | as enacted, in force 29 May 2015 |
| `ley-2291-g/` | Ley 2291-G: PROGRAMA DE LUCHA CONTRA EL ALZHEIMER | as enacted, in force 20 May 2015 |
| `ley-2292-a/` | Ley 2292-A: PRORROGA POR DOS (2) AÑOS, A PARTIR DE SU SANCION, LA VIGENCIA DE LA LEY Nº 2107-A (ANTES LEY 7206) | as enacted, in force 20 May 2015 |
| `ley-2286-a/` | Ley 2286-A: INSTITUYE EN LA PCIA. COMO "DIA DE LOS SERVICIOS PUBLICOS ESTATALES" EL 10/04 DE CADA AÑO | as enacted, in force 6 May 2015 |
| `ley-2285-t/` | Ley 2285-T: ADHESION L.N. 27.023 = OBLIGAT. EN TRANSPORTE DE PASAJEROS LEYENDA "LAS ISLAS MALVINAS SON ARGENTINAS" | as enacted, in force 26 April 2015 |
| `ley-2283-a/` | Ley 2283-A: CREA FISCALIA DE INVESTIGACIONES EN LO PENAL , CIRCUNSCRIPCION II DEPART. 25 DE MAYO | as enacted, in force 19 April 2015 |
| `ley-2282-s/` | Ley 2282-S: ADHESION L.N. 26.990 = DIA NACIONAL DE LA MEMORIA EN EL DEPORTE | as enacted, in force 15 April 2015 |
| `ley-2280-f/` | Ley 2280-F: AUTORIZA AL P.E., A ENDEUDARSE POR LA SUMA DE TRESCIENTOS SESENTA Y CUATRO MILLONES  PARA FINANCIAR CONSTRUCCION PAVIMENTO MUNICIPIOS. | as enacted, in force 25 January 2015 |
| `ley-2278-a/` | Ley 2278-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 23 January 2015 |
| `ley-2275-b/` | Ley 2275-B: REGLAMENTA EL EJERCICIO DE LA PROFESION DE ABOGADOS Y PROCURADORES - DEROGA L. 25 | current text only, as of 10 July 2018 |
| `ley-2277-a/` | Ley 2277-A: BONIFICACION POR TITULO P/PERSONAL DE LA ADMINISTRACION PUBLICA. | as enacted, in force 26 April 2015 |
| `ley-2272-a/` | Ley 2272-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 21 January 2015 |
| `ley-2273-w/` | Ley 2273-W: INSTITUYE EL PRIMER DOMINGO DE DICIEMBRE DE C. A. COMO "DIA PCIAL. DEL ARTE INDIGENA" | as enacted, in force 11 January 2015 |
| `ley-2269-w/` | Ley 2269-W: CREACION CARRERA DE TRADUCTOR-INTERPRETE DE LENGUAS INDIGENAS | as enacted, in force 11 January 2015 |
| `ley-2264-f/` | Ley 2264-F: REGIMEN DE FINANCIACION  PARA OBLIGACIONES IMPOSITIVAS PROVINCIALES | as enacted, in force 2 January 2015 |
| `ley-2267-e/` | Ley 2267-E: INSTITUYE EL 20 DE SEPTIEMBRE DE CADA AÑO COMO "DIA PCIAL. DEL NUNCA MAS" | as enacted, in force 7 January 2015 |
| `ley-2268-e/` | Ley 2268-E: INSTITUYE EL 13 DE MARZO DE CADA AÑO COMO EL "DIA PCIAL. DEL PERSONAL DE CASAS PARTICULARES | as enacted, in force 7 January 2015 |
| `ley-2260-i/` | Ley 2260-I: REGULACION DE LAS FERIAS FRANCAS EN LA PROVINCIA | as enacted, in force 31 December 2014 |
| `ley-2257-a/` | Ley 2257-A: EL MINISTERIO DE DESARROLLO SOCIAL CELEBRA CONTRATO DE LOCACION P/PERSONAL | as enacted, in force 19 April 2015 |
| `ley-2263-e/` | Ley 2263-E: INSTITUYE EL 7 DE OCTUBRE DE CADA AÑO COMO EL "DIA DE LOS VALORES VILLEROS" | as enacted, in force 31 December 2014 |
| `ley-2258-a/` | Ley 2258-A: NUEVA ESCALA SALARIAL PERSONAL DE SEGURIDAD POLICIAS Y SERVICIO PENITENCIARIO | as enacted, in force 21 December 2014 |
| `ley-2261-e/` | Ley 2261-E: INSTITUYE EL 22 DE NOVIEMBRE COMO "DIA DEL DEFENSOR OFICIAL" | as enacted, in force 31 December 2014 |
| `ley-2259-k/` | Ley 2259-K: LOTERIA CHAQUEÑA TRANSFIERE AL IPDUV INMUEBLE EN RCIA. P/CONSTRUCC. VIVIENDAS | as enacted, in force 31 December 2014 |
| `ley-2256-a/` | Ley 2256-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 26 December 2014 |
| `ley-2254-x/` | Ley 2254-X: CONVENIO PROVINCIA - NACION PROGRAMA FEDERAL DE DESENDEUDAMIENTO DE LAS PCIAS. ARGENTINAS | as enacted, in force 10 December 2014 |
| `ley-2252-d/` | Ley 2252-D: SISTEMA O REGIMEN DE DEDUCCIONES DIRECTAS CON CODIGO DE DESCUENTO. DEROGA LEY Nº 6676 | current text only, as of 10 November 2017 |
| `ley-2253-s/` | Ley 2253-S: DECLARA CAPITAL DE LA FIESTA PROVINCIAL DEL CANOTAJE DE TRAVESIA A PRESID. ROCA | as enacted, in force 12 December 2014 |
| `ley-2247-d/` | Ley 2247-D: FIJA PLAZO DE 30 MINUTOS DE ESPERA PARA ATENCION DE CLIENTES EN CAJAS DE HIPERMERCADOS Y/O SUPERMERCADOS | as enacted, in force 14 November 2014 |
| `ley-2244-a/` | Ley 2244-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 14 November 2014 |
| `ley-2248-e/` | Ley 2248-E: INSTITUYE EL 8 DE OCTUBRE DE CADA AÑO COMO "DIA PROVINCIAL DEL ESTUDIANTE SOLIDARIO" | as enacted, in force 14 November 2014 |
| `ley-2245-e/` | Ley 2245-E: INSTITÚYESE EN LA PROVINCIA EL DIA 3 DE DICIEMBRE DE CADA AÑO, EL DÍA PCIAL. DEL MÉDICO | as enacted, in force 14 November 2014 |
| `ley-2241-e/` | Ley 2241-E: ADHESION L.N. 26.917 - "SISTEMA NACIONAL DE BIBLIOTECAS ESCOLARES Y UNID. DE INF.EDUCATIVA" | as enacted, in force 7 November 2014 |
| `ley-2237-f/` | Ley 2237-F: DISPONE BONIFICACION  COMPLEMENTARIA NO ACUMULATIVA A LA BONIF. DISPUESTA POR LEY 2115-F | as enacted, in force 17 October 2014 |
| `ley-2236-a/` | Ley 2236-A: EXPROPIA INMUEBLE PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 12 June 2015 |
| `ley-2234-a/` | Ley 2234-A: CRÉASE CON CARACTER PERMANENTE EL PODER LEGISLATIVO JUVENIL | as enacted, in force 10 October 2014 |
| `ley-2233-x/` | Ley 2233-X: APRUEBA CONVENIO SUSCRIPTO EL 31/07/14 PROGRAMA FEDERAL DE DESEND. DE LAS PCIAS. ARGENTINAS | as enacted, in force 3 October 2014 |
| `ley-2230-e/` | Ley 2230-E: "DIA PROVINCIAL DEL LIBRO PARA NIÑOS" EL DIA 16 DE AGOSTO DE CADA AÑO | as enacted, in force 21 September 2014 |
| `ley-2231-i/` | Ley 2231-I: INSTITUYE LA "SEMANA DE LA INDUSTRIA Y EL COMPRE CHAQUEÑO" LA PRIMER SEMANA DE SEPTIEMBRE | as enacted, in force 21 September 2014 |
| `ley-2232-w/` | Ley 2232-W: LEY DE EDUCACION PÚBLICA DE GESTION COMUNITARIA BILINGÜE INTERCULTURAL INDIGENA | as enacted, in force 21 September 2014 |
| `ley-2227-d/` | Ley 2227-D: ESTABLECE OBLIGATORIEDAD DE INSTALAR LECTORES DE CODIGO DE BARRAS EN COMERCIOS | as enacted, in force 12 September 2014 |
| `ley-2228-q/` | Ley 2228-Q: REMOCIÓN DE PROPAGANDA ELECTORAL | as enacted, in force 5 October 2014 |
| `ley-2226-d/` | Ley 2226-D: TODA EMPRESA PRESTATARIA DE SERVICIOS EN LA PCIA. DEBERAN CONTAR CON OFICINA DE ATENCION AL PUBLICO | as enacted, in force 12 September 2014 |
| `ley-2222-e/` | Ley 2222-E: DECLARA A LA CIUDAD DE LA LEONESA "CAPITAL PCIAL. DEL PACÚ ARROCERO" | as enacted, in force 10 August 2014 |
| `ley-2221-f/` | Ley 2221-F: AUTORIZA AL P.E. A ENDEUDARSE HASTA U$S 48.000.000,- P/FINANC. PROYECTOS PROSAP | as enacted, in force 10 August 2014 |
| `ley-2219-f/` | Ley 2219-F: ESTABLECE QUE LOS CAJEROS AUTOM. DEBERAN EXHIBIR EN PANTALLA EL COSTO DE LA OPERACION BANCARIA A REALIZARSE. | as enacted, in force 8 August 2014 |
| `ley-2218-a/` | Ley 2218-A: IMPONE EL NOMBRE DE "JOSE FROILAN GONZALEZ" A LA RUTA PROVINCIAL Nº 13. | as enacted, in force 23 July 2014 |
| `ley-2217-a/` | Ley 2217-A: NUEVA ESCALA SALARIAL PARA AUTORIDADES SUPERIORES DEL PODER EJECUTIVO Y ORGANISMOS DESCENTRALIZADOS | as enacted, in force 13 August 2014 |
| `ley-2213-x/` | Ley 2213-X: CONVENIO PROGRAMA FEDERAL DE DESENDEUDAMIENTO DE LA PROVINCIAS ARGENTINAS | as enacted, in force 13 August 2014 |
| `ley-2212-a/` | Ley 2212-A: EXPROPIA INMUEBLE EN ROQUE SAENZ PEÑA / ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 13 August 2014 |
| `ley-2211-e/` | Ley 2211-E: INSTITUYE EL 17 DE MAYO DE CADA AÑO COMO "DIA CONTRA LA DISCRIMINACION POR ORIENTACION SEXUAL, IDENTIDAD O EXPRESION DE GENERO" | as enacted, in force 13 August 2014 |
| `ley-2209-a/` | Ley 2209-A: INSTITUYE EL DIA 9 DE SEPTIEMBRE DE CADA AÑO DIA DE DUELO PROVINCIAL POR MASACRE DEL ZAPALLAR | as enacted, in force 13 August 2014 |
| `ley-2208-a/` | Ley 2208-A: CREA ASESORIA DEL MENOR DE EDAD EN EL JUZGADO MULTIFUEROS DE NUEVA POMPEYA | as enacted, in force 13 August 2014 |
| `ley-2206-a/` | Ley 2206-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 24 August 2014 |
| `ley-2204-a/` | Ley 2204-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 11 June 2014 |
| `ley-2203-a/` | Ley 2203-A: EXPROPIA INMUEBLE EN RCIA. PARA SER ADJUDICADO EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 11 June 2014 |
| `ley-2201-e/` | Ley 2201-E: FIJA EL VALOR INDICE UNO (1) PARA DETERMINAR LAS REMUNERACIONES DEL PERSONAL DOCENTE - LEY 647-E | as enacted, in force 1 June 2014 |
| `ley-2202-e/` | Ley 2202-E: ESTABLECE PARA ALUMNOS DEL ULTIMO GRADO DE LA EDUCACION PRIMARIA Y EL ULTIMO AÑO DE LA EDUCACION SECUNDARIA PROMETER LEALTAD A LA CONSTITUCION PROVI… | as enacted, in force 11 June 2014 |
| `ley-2199-u/` | Ley 2199-U: ADHESION L.N. 26.923 - COMERCIALIZACION DE EQUIPOS COMPATIBLES CON ORTESIS Y PRÓTESIS AUDITIVAS PARA PERSONAS HIPOACUSTICAS | as enacted, in force 1 June 2014 |
| `ley-2198-m/` | Ley 2198-M: REGULA PROCEDIMIENTO DE ADOPCIÓN. | as enacted, in force 1 June 2014 |
| `ley-2195-r/` | Ley 2195-R: USO RESPONSABLE DEL AGUA POTABLE EN BAÑOS Y TOILETTES EN ESTABLECIMIENTOS PUBLICOS  Y PRIVADOS. | as enacted, in force 13 August 2014 |
| `ley-2194-r/` | Ley 2194-R: CREA "PROGRAMA PARA EL USO RESPONSABLE DEL AGUA" EN EL AMBITO DEL MINISTERIO DE EDUCACION | as enacted, in force 15 February 2015 |
| `ley-2196-e/` | Ley 2196-E: ADHESION LEY NACIONAL 26.876 - SE INSTITUYE EL 27 DE JUNIO DE CADA AÑO "DIA DEL TRABAJADOR DEL ESTADO NACIONAL" | as enacted, in force 28 May 2014 |
| `ley-2190-a/` | Ley 2190-A: TRANSFIERE INMUEBLES ESCRITURADOS A NOMBRE DEL IPDUV A FAVOR DEL MRIO. DESARR. URBANO TERRITORIAL | as enacted, in force 7 May 2014 |
| `ley-2192-a/` | Ley 2192-A: LENGUAJE INCLUSIVO Y GENERICO EN TODO PROTOCOLO EN PAPELERIA DEL ESTADO PROVINCIAL | as enacted, in force 28 May 2014 |
| `ley-2188-l/` | Ley 2188-L: ADHESION L.N.26.844 - REGIMEN ESPECIAL DE CONTRATO DE TRABAJO PERSONAL DE CASA PART. | as enacted, in force 28 May 2014 |
| `ley-2189-a/` | Ley 2189-A: PRACTICA ABUSIVA POR COBRO DE ADICIONALES POR RECIBIR SERVICIO CREDITO VIRTUAL EN TELEFONOS CELULARES. | as enacted, in force 28 May 2014 |
| `ley-2186-e/` | Ley 2186-E: INSTITUYE EL 3 DE DICIEMBRE DE CADA AÑO "DIA PROVINCIAL DE LAS PERSONAS CON DISCAPACIDAD" | as enacted, in force 25 April 2014 |
| `ley-2187-e/` | Ley 2187-E: INSTITUYE EL 4 DE ABRIL DE CADA AÑO "DIA PROVINCIAL CONTRA LA PROSTITUCION INFANTIL" | as enacted, in force 25 April 2014 |
| `ley-2184-a/` | Ley 2184-A: NUEVAS ESCALAS SALARIALES TRIBUNAL DE CUENTAS,  INCORPORA INCS.F) Y G)  ART.2º L.6784 | as enacted, in force 25 April 2014 |
| `ley-2183-s/` | Ley 2183-S: CREA PROGRAMA PCIAL. DE ASISTENCIA INTEGRAL PARA DEPORTISTAS CALIFICADOS AMATEURS | as enacted, in force 25 April 2014 |
| `ley-2181-x/` | Ley 2181-X: CONVENIO CON LA NACION PROGRAMA DE DESENDEUDAMIENTO DE LAS PCIAS. ARGENTINAS | as enacted, in force 13 April 2014 |
| `ley-2165-i/` | Ley 2165-I: CREA EL PARQUE INDUSTRIAL DE LA LOCALIDAD DE BARRANQUERAS | as enacted, in force 29 January 2014 |
| `ley-2177-f/` | Ley 2177-F: PRESUPUESTO PROVINCIAL PERIODO 2014 | as enacted, in force 26 January 2014 |
| `ley-2171-a/` | Ley 2171-A: LEY ORGANICA DE LA JUSTICIA DE PAZ Y FALTAS - DEROGA EL D.L. 2247/62 | as enacted, in force 22 January 2014 |
| `ley-2173-e/` | Ley 2173-E: ADHESION L.N.26.878 - "DIA NACIONAL DEL JOVEN EMPRESARIO" | as enacted, in force 12 January 2014 |
| `ley-2168-c/` | Ley 2168-C: INSTITUYE EL DIA 12 DE DICIEMBRE DE CADA AÑO "DIA PROVINCIAL DE LA ADOPCION" | as enacted, in force 12 January 2014 |
| `ley-2169-u/` | Ley 2169-U: INSTITUYE EL DIA 24 DE MAYO COMO DIA PROVINCIAL DEL OPERADOR DE RADIO | as enacted, in force 12 January 2014 |
| `ley-2172-a/` | Ley 2172-A: DECLARA EN ESTADO DE DISOLUCION  Y LIQUIDACION  ENTE AUTAR. FIESTA NAC. DEL ALGODON | as enacted, in force 15 January 2014 |
| `ley-2170-f/` | Ley 2170-F: ADICIONAL COMPLEMENTARIO P/ AGENTES DE CONTADURIA GRAL. TESOR. GRAL. Y DCCION. GRAL. DE FINANZAS Y PROGR. PRESUP. | as enacted, in force 5 January 2014 |
| `ley-2161-e/` | Ley 2161-E: ESTABLECE EL "PREMIO ANUAL A LA POESIA CHAQUEÑA, MARIO NESTOROFF" DE LA CAMARA DE DIPUTADOS | as enacted, in force 27 December 2013 |
| `ley-2160-e/` | Ley 2160-E: DECLARA PATRIMONIO HISTORICO CULTURAL ESCUELAS CONSTRUIDAS POR "PLAN QUINQUENAL" | as enacted, in force 27 December 2013 |
| `ley-2158-d/` | Ley 2158-D: CRÉASE UNA PAGINA WEB PARA RECIBIR RECLAMOS O CONSULTAS ONLINE | as enacted, in force 15 December 2013 |
| `ley-2156-e/` | Ley 2156-E: FONDO PCIAL. PARA MANTENIMIENTO Y MEJORA DE LOS EDIFICIOS EDUCATIVOS | as enacted, in force 7 March 2014 |
| `ley-2155-e/` | Ley 2155-E: PROGRAMA DE JUEGOTECAS BARRIALES | as enacted, in force 20 November 2013 |
| `ley-2154-r/` | Ley 2154-R: ADHESION L.N. 26.815 - SISTEMA FEDERAL DE MANEJO DE FUEGO | as enacted, in force 7 March 2014 |
| `ley-2152-a/` | Ley 2152-A: ESTABLECE OBLIGACION DE COMPAÑIAS. TELEFONICAS, MEDICINA PREPAGA, ETC. POR RESCICION DEL SERVICIOS | as enacted, in force 22 December 2013 |
| `ley-2151-a/` | Ley 2151-A: TODO ACTOS OFICIALES DEBERA CONTAR CON LAS TRADUCCIONES A LA LENGUA DE SEÑAS ARGENTINA (LSA) | as enacted, in force 8 November 2013 |
| `ley-2150-a/` | Ley 2150-A: EXPROPIA INMUEBLES EN LAGUNA BLANCA P/CONSTRUCC. ESCUELA SECUND. , VIVIEN. ETC. | as enacted, in force 1 November 2013 |
| `ley-2148-l/` | Ley 2148-L: CREA EN LA PCIA. DEL CHACO EL REGIMEN DE CONSORCIOS DE LADRILLEROS | as enacted, in force 18 October 2013 |
| `ley-2147-d/` | Ley 2147-D: IMPLEMENTA DERECHOS DE LOS USUARIOS CREAR MECANISMOS DE PROTECCION S/L.2068-D | as enacted, in force 9 October 2013 |
| `ley-2145-a/` | Ley 2145-A: EXPROPIA INMUEBLES EN DPTO. GRAL. GUEMES, LOCALIDAD EL SAUZALITO | current text only, as of 28 August 2018 |
| `ley-2146-j/` | Ley 2146-J: REGLAMENTO DEL SERVICIO ADICIONAL PARA LA  POLICIA  DE LA PCIA. DEL CHACO | as enacted, in force 6 October 2013 |
| `ley-2143-e/` | Ley 2143-E: DERECHO AL LIBRE ACCESO Y PERMANENCIA CON PERROS GUÍAS. CREA REGISTRO | as enacted, in force 25 September 2013 |
| `ley-2142-w/` | Ley 2142-W: INSTITUYE  EL"DIA DEL VETERANO Y DE LOS CAIDOS INDIGENAS  GUERRA DE MALVINAS" | as enacted, in force 25 September 2013 |
| `ley-2140-d/` | Ley 2140-D: NORMATIVA PARA LOCALES QUE COMERCIALICEN INDUMENTARIA DE VESTIR | as enacted, in force 20 September 2013 |
| `ley-2139-t/` | Ley 2139-T: PROGRAMA DE CONCIENTIZACION VIAL"SIN CASCO NO HAY COMBUSTIBLE" | as enacted, in force 20 September 2013 |
| `ley-2141-j/` | Ley 2141-J: RESTRICCION DE PORTACION  DEL ARMA EFECTIVO POLICIAL DENUNCIADOS VIOLENCIA FAMILIAR | as enacted, in force 15 September 2013 |
| `ley-2136-a/` | Ley 2136-A: EXPROPIA INMUEBLE EN PTO. TIROL P/SER ADJUDICADO EN VENTA A SUS OCUPANTES | as enacted, in force 9 August 2013 |
| `ley-2137-e/` | Ley 2137-E: DETERMINASE PARA LA VALORACION DE ANTECEDENTES DEL PERSONAL DOCENTE | as enacted, in force 9 August 2013 |
| `ley-2135-w/` | Ley 2135-W: PRESERVACION, PROTECCION Y TUTELA DE LOS RESTOS MORTALES PUEBLOS ORIGINARIOS | as enacted, in force 7 August 2013 |
| `ley-2134-e/` | Ley 2134-E: CREA EN LA PCIA. EL MUSEO DE CIENCIA Y TECNOLOGÍA | as enacted, in force 4 August 2013 |
| `ley-2132-j/` | Ley 2132-J: IDENTIFICACION ORGANISMOS DE ATENCION A LA VICTIMA DE VIOLENCIA FAMILIAR Y DE GENERO | as enacted, in force 11 August 2013 |
| `ley-2133-a/` | Ley 2133-A: CREA JUZGADOS DEL MENOR DE EDAD Y LA FAMILIA EN SAENZ PEÑA, V.ANGELA, CHARATA Y J.J.CASTELLI | as enacted, in force 7 August 2013 |
| `ley-2131-e/` | Ley 2131-E: ADHESION L.N.26.811 - "DIA PROVINCIAL DE LA LUCHA CONTRA LA VIOLENCIA INSTITUCIONAL" | as enacted, in force 7 August 2013 |
| `ley-2127-j/` | Ley 2127-J: CAMPAÑAS DE CONCIENCIACION  DEL USO RACIONAL DE LOS  SERVICIOS DE EMERGENC. 911 | as enacted, in force 2 August 2013 |
| `ley-2128-e/` | Ley 2128-E: ADHESION L.N. 26.064 - INSTITUYE EL 12 DE JUNIO DE C/A. "DIA NACIONAL C/EL TRABAJO INFANTIL" | as enacted, in force 14 July 2013 |
| `ley-2126-a/` | Ley 2126-A: EXPROPIA INMUEBLES EN VILLA ANGELA P/TRANSFERIR AL MUNICIPIO | as enacted, in force 26 July 2013 |
| `ley-2129-a/` | Ley 2129-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 14 July 2013 |
| `ley-2124-e/` | Ley 2124-E: INSTITUYESE EL DIA 13 DE MARZO DE CADA AÑO "DIA PCIAL. DE LUCHA CONTRA LA POBREZA" | as enacted, in force 14 July 2013 |
| `ley-2123-j/` | Ley 2123-J: IMPLEMENTACION DEL BOTON ANTIPÁNICO | as enacted, in force 14 July 2013 |
| `ley-2125-a/` | Ley 2125-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 14 July 2013 |
| `ley-2121-i/` | Ley 2121-I: ADHESION L.N.26.838 - FOMENTO DE LA ACTIVIDAD CINEMATOGRAFICA NACIONAL | as enacted, in force 19 June 2013 |
| `ley-2120-a/` | Ley 2120-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 2 October 2013 |
| `ley-2108-a/` | Ley 2108-A: LEY ORGANICA DE LA ASESORIA GENERAL DE GOBIERNO | as enacted, in force 15 May 2013 |
| `ley-2110-a/` | Ley 2110-A: EXPROPIA INMUEBLES EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 15 May 2013 |
| `ley-2107-a/` | Ley 2107-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 8 May 2013 |
| `ley-2106-a/` | Ley 2106-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 8 May 2013 |
| `ley-2105-g/` | Ley 2105-G: ADHESION L.N. 26.803 -   "DIA NACIONAL PARA LA LUCHA CONTRA EL CANCER INFANTIL" | as enacted, in force 8 May 2013 |
| `ley-2102-a/` | Ley 2102-A: EXPROPIA INMUEBLES EN BARRANQUERAS PARA SER ADJUDICADOS EN VENTA A SUS OCUPANTES | as enacted, in force 19 April 2013 |
| `ley-2101-a/` | Ley 2101-A: EXPROPIA INMUEBLES EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 19 April 2013 |
| `ley-2100-p/` | Ley 2100-P: CREA COMISION DE PROPUESTAS PARA LA REFORMA MUNICIPAL | as enacted, in force 3 April 2013 |
| `ley-2097-e/` | Ley 2097-E: EL 3 DE ABRIL DE CADA AÑO "DIA PCIAL. DE CONCIENCIACION Y SENSIBILIZ. S/TRATA DE PERSONAS" | as enacted, in force 8 March 2013 |
| `ley-2083-a/` | Ley 2083-A: EXPROPIA INMUEBLES EN DPTO. S. FERNANDO P/ADJUDICAR EN VENTA A SUS ACTCUALES OCUPANTES | as enacted, in force 15 February 2013 |
| `ley-2084-a/` | Ley 2084-A: EXPROPIA INMUEBLE EN DPTO. S. FERNANDO P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 15 February 2013 |
| `ley-2098-a/` | Ley 2098-A: APRUEBA NUEVA ESCALA DE REMUNERACIONES PARA LA FISCALIA DE ESTADO | as enacted, in force 19 April 2013 |
| `ley-2082-b/` | Ley 2082-B: REGLAMENTA EL SISTEMA DE SELECCION P/LA DESIGNACION DE JUECES Y PROC. GENERAL | as enacted, in force 27 January 2013 |
| `ley-2081-b/` | Ley 2081-B: REGLAMENTA 2DO. PARRAFO DEL ART.154 DE LA CONSTITUCION PROVINCIAL 1957-1994- ACCESO A LA JUBILACION DE MAGISTRADOS Y DEL MINISTERIO PUBLICO | as enacted, in force 16 January 2013 |
| `ley-2078-f/` | Ley 2078-F: MODIFICA VARIOS ARTICULOS DE LA LEYES 299-F (ANTES LEY 2071) Y 1903-C (ANTES LEY 6723) | as enacted, in force 28 December 2012 |
| `ley-2075-a/` | Ley 2075-A: EL PODER EJECUTIVO TRANSFIERE EN DONACION INMUEBLES PROPIEDAD DEL GOB. PCIAL. | as enacted, in force 23 December 2012 |
| `ley-2073-q/` | Ley 2073-Q: SISTEMA DE ELECCIONES PRIMARIAS. ADHESION A LA LEY NACIONAL 26.571- (PASO) | as enacted, in force 21 December 2012 |
| `ley-2067-a/` | Ley 2067-A: EXPROPIA INMUEBLE EN RESISTENCIA PARA VENTA  ACTUALES OCUPANTES | as enacted, in force 19 December 2012 |
| `ley-2070-d/` | Ley 2070-D: ESTABLECE MODALIDAD PARA  CAMBIO EN LA COMPRA-VENTA DE PRODUCTOS O BIENES | as enacted, in force 21 December 2012 |
| `ley-2062-d/` | Ley 2062-D: ESTABLECE FORMA DE EXHIBIR PRECIOS DE LAS COSAS MUEBLES EN LOS COMERCIOS | as enacted, in force 25 November 2012 |
| `ley-2058-a/` | Ley 2058-A: EXPROPIA INMUEBLES EN RESISTENCIA P/VENTA  A ACTUALES OCUPANTES | as enacted, in force 25 November 2012 |
| `ley-2071-c/` | Ley 2071-C: AUTORIZA EN TODA LA PROVINCIA DEL CHACO EL JUEGO DE "TABA" | as enacted, in force 23 December 2012 |
| `ley-2065-a/` | Ley 2065-A: EXPROPIA INMUEBLE EN RCIA. PROPIEDAD DE ENCINA RUBEN Y ORCOLA GASTON | as enacted, in force 19 December 2012 |
| `ley-2061-a/` | Ley 2061-A: EXPROPIA INMUEBLE EN EL DPTO. O'HIGGINS P/ LA OBRA "DEFENSA SUR DE LA CLOTILDE" | as enacted, in force 25 November 2012 |
| `ley-2057-a/` | Ley 2057-A: EXPROPIA INMUEBLES E RESISTENCIA P/VENTA A ACTUALES OCUPANTES | as enacted, in force 25 November 2012 |
| `ley-2064-a/` | Ley 2064-A: EXPROPIA INMUEBLE EN RCIA. PROPIEDAD DE OSCAR ORLANDO BAEZ | as enacted, in force 23 December 2012 |
| `ley-2060-h/` | Ley 2060-H: SISTEMA DE PROTECCION INTEGRAL PARA PERSONAS TRASPLANTADAS | as enacted, in force 25 November 2012 |
| `ley-2055-c/` | Ley 2055-C: PROGRAMA "SOY PEQUEÑO CON GRANDES DERECHOS" | as enacted, in force 25 November 2012 |
| `ley-2054-t/` | Ley 2054-T: SEMAFOROS INSTALADOS EN LA PROVINCIA DEBERAN CONTAR CON SEÑAL SONORA PARA NO VIDENTES | as enacted, in force 25 November 2012 |
| `ley-2051-a/` | Ley 2051-A: ESTABLECESE EL "DERECHO DE ADMISION" | as enacted, in force 16 November 2012 |
| `ley-2048-a/` | Ley 2048-A: ESCALA SALARIAL PARA AUTORIDADES DEL PODER EJECUTIVO Y ORGANISMOS DESCENTRALIZADOS Y AUTÁRQUICOS | as enacted, in force 24 October 2012 |
| `ley-2046-a/` | Ley 2046-A: EXPROPIA INMUEBLES EN RCIA. PARA FUNCIONAMIENTO DEL CEP Nº 109 | as enacted, in force 24 October 2012 |
| `ley-2053-w/` | Ley 2053-W: REGISTRO DE NATALIDAD Y MORTALIDAD DE LOS PUEBLOS INDIGENAS | as enacted, in force 9 November 2012 |
| `ley-2050-a/` | Ley 2050-A: EXPROPIA INMUEBLE EN RCIA. PARA VENTA A ACTUALES OCUPANTES | as enacted, in force 28 October 2012 |
| `ley-2044-a/` | Ley 2044-A: DISPOSICIÓN SELECTIVA DE RESIDUOS EN ORGANISMOS PÚBLICOS | as enacted, in force 24 October 2012 |
| `ley-2047-e/` | Ley 2047-E: DECLÁRASE PATRIMONIO NATURAL DE LA PROVINCIA DEL CHACO, AL ÁRBOL CONOCIDO COMO “EL GIGANTE DEL IMPENETRABLE” | as enacted, in force 24 October 2012 |
| `ley-2043-e/` | Ley 2043-E: FOMENTO DE LA EDUCACIÓN Y LA CULTURA DE LA PAZ Y LA NO VIOLENCIA | as enacted, in force 14 October 2012 |
| `ley-2040-a/` | Ley 2040-A: RUTA PROVINCIAL N° 7 SE DENOMINARÁ “RUTA N° 7  PRESIDENTE NÉSTOR CARLOS KIRCHNER” | as enacted, in force 10 October 2012 |
| `ley-2049-e/` | Ley 2049-E: TRANSFIERE UNIDAD EDUCATIVA PRIVADA Nº 30 “AIDA ZOLEZZI DE FLORITO" A LA PROVINCIA | as enacted, in force 26 October 2012 |
| `ley-2041-a/` | Ley 2041-A: FACTURAS DE SERVICIOS PUBLICOS DEBERAN  LLEVAR N° TELEFONICO PARA DENUNCIAS DE MALTRATO INFANTIL, VIOLENCIA  DE GENERO Y NIÑOS DESAPARECIDOS DE | as enacted, in force 7 October 2012 |
| `ley-2042-k/` | Ley 2042-K: ADHESIÓN PROVINCIAL AL PROGRAMA DE CRÉDITO ARGENTINO DEL BICENTENARIO PARA LA VIVIENDA ÚNICA FAMILIAR (PRO.CRE.AR.), | as enacted, in force 2 December 2012 |
| `ley-2037-e/` | Ley 2037-E: PROGRAMA EDUCATIVO PROVINCIAL “30 AÑOS DE LA GESTA DE MALVINAS” | as enacted, in force 10 October 2012 |
| `ley-2036-a/` | Ley 2036-A: CRÉASE LA ESCUELA DE GOBIERNO DE LA PROVINCIA DEL CHACO | as enacted, in force 7 October 2012 |
| `ley-2034-v/` | Ley 2034-V: ACTIVIDADES TURISTICAS "DESTINO CHACO" | as enacted, in force 7 October 2012 |
| `ley-2033-a/` | Ley 2033-A: CREA EL CENTRO DE LIBERADOS DEL CHACO | as enacted, in force 2 November 2012 |
| `ley-2032-a/` | Ley 2032-A: EXPROPIA INMUEBLE EN RCIA. PARA SER ADJUDICADO A SUS ACTUALES OCUPANTES | as enacted, in force 7 October 2012 |
| `ley-2031-a/` | Ley 2031-A: EXPROPIA INMUEBLES EN SAENZ PEÑA PARA CONSTRUCCION DE VIVIENDAS SOCIALES | as enacted, in force 14 September 2012 |
| `ley-2030-a/` | Ley 2030-A: CRÉASE LA COMISIÓN MIXTA DEL INTERFLUVIO TEUCO-BERMEJITO. | as enacted, in force 23 September 2012 |
| `ley-2029-a/` | Ley 2029-A: EXPROPIA INMUEBLE EN RESISTENCIA PARA VENTA A ACTUALES OCUPANTES | as enacted, in force 7 October 2012 |
| `ley-2028-r/` | Ley 2028-R: PROCEDIMIENTOS DE GESTION INTEGRAL DE RESIDUOS SOLIDOS URBANOS | as enacted, in force 14 September 2012 |
| `ley-2023-a/` | Ley 2023-A: PREVENCIÓN Y ERRADICACIÓN DE LA VIOLENCIA LABORAL EN LA ADMINIST. PBLICA. PCIAL. | as enacted, in force 12 August 2012 |
| `ley-2017-h/` | Ley 2017-H: PENSION GRACIABLE PARA EX SOLDADOS CONVOCADOS POR EL DISTRITO MILITAR CHACO | as enacted, in force 14 September 2012 |
| `ley-2025-a/` | Ley 2025-A: RATIFICA RESOLUCION DE PRESIDENCIA DE LA CAMARA DE DIPUTADOS Nº 713/12 | as enacted, in force 5 August 2012 |
| `ley-2024-k/` | Ley 2024-K: DECLARA POR EL TERMINO DE 24 MESES LA "EMERGENCIA HABITACIONAL" | as enacted, in force 5 August 2012 |
| `ley-2021-b/` | Ley 2021-B: RECURSOS DE INCONSTITUCIONALIDAD Y DE  INAPLICABILIDAD DE LEY O DOCTRINA LEGAL | as enacted, in force 3 August 2012 |
| `ley-2019-i/` | Ley 2019-I: ADHESION L.N.26020 -COMERCIALIZACION DEL GAS LICUADO DE PETROLEO- | as enacted, in force 13 July 2012 |
| `ley-2018-h/` | Ley 2018-H: PROGRAMA SOCIAL PCIAL. P/FABRICACION DE ATAUDES P/PERSONAS INDIGENTES O DE EXTREMA POBREZA | as enacted, in force 13 July 2012 |
| `ley-2015-j/` | Ley 2015-J: OBLIGATORIEDAD DE DIFUNDIR  NORMAS DE TRANSITO VIGENTES EN EVENTOS DEPORTIVOS | as enacted, in force 17 June 2012 |
| `ley-2013-f/` | Ley 2013-F: SISTEMA DE COMPENSACION DE CREDITOS Y DEUDAS | as enacted, in force 13 July 2012 |
| `ley-2014-e/` | Ley 2014-E: REGULA PROCESO INTERRELACION  DE LAS ESCUELAS TECNICAS AGROPECUARIAS DE LA PCIA. | as enacted, in force 13 July 2012 |
| `ley-2011-j/` | Ley 2011-J: LEY DE SEGURIDAD PUBLICA DE LA PROVINCIA DEL CHACO - DEROGA LAS LEYES 4681 Y 4503 | as enacted, in force 27 May 2012 |
| `ley-2009-f/` | Ley 2009-F: CREA PROGRAMA FIDEICOMISOS FINANCIEROS MUNICIPIOS DEL CHACO | as enacted, in force 1 June 2012 |
| `ley-1914-f/` | Ley 1914-F: MODIFICA EL ARTICULO 4º DE LA LEY 468-F Y EL ARTICULO 5º DE LA LEY 378-A (ANTES LEY 2471) | as enacted, in force 8 May 2011 |
| `ley-2004-t/` | Ley 2004-T: PROHIBE TRANSPORTE NOCTURNO DE PRODUCTOS FORESTALES EN RUTAS Y CAMINOS VECINALES | as enacted, in force 30 May 2012 |
| `ley-2003-t/` | Ley 2003-T: ESTABLECE TRANSPORTE AUTOMOTOR DE CARGAS DE PRODUCTOS PRIMARIOS COMO SERVICIO PUBLICO | as enacted, in force 6 June 2012 |
| `ley-2002-p/` | Ley 2002-P: FIJA PARA EL MUNICIPIO DE EL ESPINILLO LA PARTICIPACION MENSUAL | as enacted, in force 4 May 2012 |
| `ley-2000-e/` | Ley 2000-E: DECLARA PATRIMONIO HISTORICO CULTURAL ESCUELA PRIMARIA Nº 7 "MANUEL BELGRANO" | as enacted, in force 20 April 2012 |
| `ley-1999-x/` | Ley 1999-X: CONVENIO BILATERAL "PROGRAMA FEDERAL DE DESENDEUDAMIENTO DE LAS PCIAS. ARGENT." | as enacted, in force 1 April 2012 |
| `ley-1996-a/` | Ley 1996-A: EXPROPIA LA RESERVA DE RECURSOS "LA FIDELIDAD" CREADA POR LEY 1953-R | as enacted, in force 15 January 2012 |
| `ley-1997-a/` | Ley 1997-A: EL PODER EJECUTIVO CONSTITUIRÁ EL "FIDEICOMISO LA FIDELIDAD" | as enacted, in force 15 January 2012 |
| `ley-1992-c/` | Ley 1992-C: ADHESION L.N.26.581 - INCLUIR EN PAGINA WEB ESPACIO NÑOS/AS PERDIDOS | as enacted, in force 22 January 2012 |
| `ley-1989-g/` | Ley 1989-G: CREA EL PROGRAMA DERECHO ALIMENTARIO SALUDABLE | as enacted, in force 11 January 2012 |
| `ley-1988-a/` | Ley 1988-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/ADJUDICAR EN VENTA A SUS OCUPANTES | as enacted, in force 15 January 2012 |
| `ley-1975-b/` | Ley 1975-B: INSTITUYE EL DIGESTO JURIDICO DE LA PROVINCIA DEL CHACO - ABROGASE  LA LEY 5432 | as enacted, in force 1 January 2012 |
| `ley-1974-a/` | Ley 1974-A: AMPLIA COMPETENCIA, ATRIBUCIONES, Y FUNCIONES DE LA ESCRIBANIA GRAL. DE GOBIERNO | as enacted, in force 23 December 2011 |
| `ley-1973-a/` | Ley 1973-A: ESCALAFON P/PERSONAL ESPECIALIZADO DE LA DIRECCION DE AERONAUTICA | as enacted, in force 1 January 2012 |
| `ley-1972-e/` | Ley 1972-E: INSTITUYESE EL 27 DE OCTUBRE COMO EL DIA DE LA REIVINDICACION  LABORAL | as enacted, in force 2 December 2011 |
| `ley-1971-a/` | Ley 1971-A: DIRECCION PROVINCIAL PARA LA PREVENCION Y ERRADICACION DEL TRABAJO INFANTIL Y PROTECCION DEL TRABAJO ADOLESCENTE -DIPROPETI-. | as enacted, in force 13 November 2011 |
| `ley-1960-e/` | Ley 1960-E: IMPRESION DE FOLLETOS - ACCESO GRATUITO A DISCAPACITADOS | as enacted, in force 28 September 2011 |
| `ley-1959-a/` | Ley 1959-A: ASIGNACION P/INCOMPATIBILIDAD P/CONTADOR GRAL., SUBCONTADOR, TESORERO Y SUBTESORERO DE LA CONTADURIA GRAL. DE LA PCIA. | as enacted, in force 16 September 2011 |
| `ley-1958-a/` | Ley 1958-A: OTORGA A PARTIR DEL 01/04/2011 COMPENSACION MENSUAL DEL 25% PERSONAL POLICIAL | as enacted, in force 10 August 2011 |
| `ley-1955-a/` | Ley 1955-A: ADHESION L.N. 26.047 - REGISTROS NACIONALES DE SOC. POR ACC., DE SOC. EXTRANJ. ETC. | as enacted, in force 10 August 2011 |
| `ley-1957-h/` | Ley 1957-H: SISTEMA DE PRESTACIONES SOCIALES LEYES 1369-H Y 1370-H - ASIGNACION COMPENSATORIA | as enacted, in force 5 August 2011 |
| `ley-1954-e/` | Ley 1954-E: DECLARA PATRIMONIO HISTORICO, CULTURAL Y NATURAL DE LA PCIA. AL BARRIO "SAN PEDRO PESCADOR" | as enacted, in force 19 August 2011 |
| `ley-1952-a/` | Ley 1952-A: CREA REGISTRO UNICO DE FIESTAS PROVINCIALES | as enacted, in force 10 August 2011 |
| `ley-1949-e/` | Ley 1949-E: DECLARA PATRIMONIO HISTORICO CULTURAL DE LA PCIA. ESCUELA "PEDRO ANDRES PRADIER" DE TRES ISLETAS. | as enacted, in force 31 July 2011 |
| `ley-1948-p/` | Ley 1948-P: CREA MUNICIPIO DE 3RA. CATEGORIA EN CHOROTIS E INCORPORA INC.LVIII) ART. 1º L.257 | as enacted, in force 20 July 2011 |
| `ley-1943-c/` | Ley 1943-C: ADHESION L.N.25.854 | as enacted, in force 10 July 2011 |
| `ley-1941-e/` | Ley 1941-E: ENSEÑANZA OBLIGATORIA DEL IDIOMA PORTUGUES EN LAS ESCUELAS SECUNDARIAS | as enacted, in force 10 July 2011 |
| `ley-1942-e/` | Ley 1942-E: APRUEBA MECANISMOS QUE RESGUARDEN LOS DERECHO Y ESTABILIDAD LABORAL DOCENTES | as enacted, in force 13 July 2011 |
| `ley-1936-e/` | Ley 1936-E: DECLARA PATRIMONIO CULTURAL PROVINCIAL AL CASCO HISTORICO DE PUERTO BERMEJO | as enacted, in force 24 June 2011 |
| `ley-1937-e/` | Ley 1937-E: DECLARA PATRIMONIO CULTURAL PCIAL. A LAS RUINAS  "LA CANGAYE" Y "SAN BERNARDO EL VERTIZ" | as enacted, in force 20 July 2011 |
| `ley-1935-j/` | Ley 1935-J: CREA PROGRAMA "CONDUCTOR RESPONSABLE DESIGNADO" | as enacted, in force 24 June 2011 |
| `ley-1934-a/` | Ley 1934-A: ESTABLECE NORMATIVA POR TENENCIA DE CANES O PERROS PELIGROSOS | as enacted, in force 24 June 2011 |
| `ley-1929-e/` | Ley 1929-E: DECLARA PATRIMONIO HISTORICO CULTURAL DE LA PCIA. EX-EDIFICIO "VILLA MARTI" DE GRAL. SAN MARTIN | as enacted, in force 5 June 2011 |
| `ley-1927-a/` | Ley 1927-A: NUEVAS ESCALAS SALARIALES P/ FUNC. Y EMPLEADOS TRIB. DE CUENTAS Y MOD. ART.1º L. 1608 -A (Antes L. 6061) | as enacted, in force 5 June 2011 |
| `ley-1925-w/` | Ley 1925-W: RECONOCE A LA BANDERA INDIGENA "WIPHALA" COMO EMBLEMA DE LOS PUEBLOS ORIGINARIOS | as enacted, in force 1 June 2011 |
| `ley-1924-w/` | Ley 1924-W: RECONOCIMIENTO Y PROTECCION A LOS DERECHOS DE LOS PUEBLOS ORIGINARIOS DEL CHACO | as enacted, in force 5 June 2011 |
| `ley-1923-e/` | Ley 1923-E: ESTABLECE EL 23 DE FEBRERO DE CADA AÑO  "DIA PROVINCIAL DEL ROTARY INTERNACIONAL" | as enacted, in force 20 May 2011 |
| `ley-1920-e/` | Ley 1920-E: ADHESION L.N. 26.653 - ACCESIBIL. DE LA INFORMACION PAGINAS WEB (PERSONAS C/DISCAPACIDAD) | as enacted, in force 20 May 2011 |
| `ley-1922-e/` | Ley 1922-E: DECLARA PATRIMONIO HISTORICO CULTURAL A LA "CASA CRUZ" DE SAENZ PEÑA | as enacted, in force 20 May 2011 |
| `ley-1921-d/` | Ley 1921-D: OBLIGACION ENTREGA MODELO CONTRATO A SUSCRIBIR POR SERVICIOS A CONSUMIDORES | as enacted, in force 20 May 2011 |
| `ley-1915-e/` | Ley 1915-E: DECLARA PATRIMONIO HISTORICO , CULTURAL A LAS "RUINAS DEL KILOMETRO 75" | as enacted, in force 15 May 2011 |
| `ley-1917-j/` | Ley 1917-J: PROGRAMA DE ATENCION, ASESORAMIENTO, CONTENCION Y ACOMPAÑAMIENTO CONTRA LAS VIOLENCIAS DE GENERO | as enacted, in force 9 October 2011 |
| `ley-1913-a/` | Ley 1913-A: DESIGNACION DE FUNCIONARIOS POR ACUERDO LEGISLATIVO - DEROGA LEY 3412 | as enacted, in force 20 April 2011 |
| `ley-1912-p/` | Ley 1912-P: CREA EN EL DPTO. GRAL. GUEMES MUNICIPIO DE 3RA. CATEGORIA -DE EL ESPINILLO | as enacted, in force 8 April 2011 |
| `ley-1906-e/` | Ley 1906-E: CREA PROGRAMA "ESPACIOS VERDES ESCOLARES" A IMPLEMENTAR EN ESTABL. EDUCATIVOS | as enacted, in force 26 January 2011 |
| `ley-1905-e/` | Ley 1905-E: PLAZAS PUBLICAS SE DEBEN ADECUAR CON JUEGOS P/NIÑOS CON DISCAPACIDAD | as enacted, in force 24 July 2011 |
| `ley-1909-i/` | Ley 1909-I: PROTOCOLO PCIAL. PARA EL CONTRALOR DE EXPENDIO DE COMBUSTIBLES EN LA PROVINCIA | as enacted, in force 26 January 2011 |
| `ley-1908-l/` | Ley 1908-L: CREA EN LA PROVINCIA EL "REGIMEN DE CONTROLADORES LABORALES" | as enacted, in force 19 January 2011 |
| `ley-1889-f/` | Ley 1889-F: ESTABLECE A PARTIR DEL 1º DE AGOSTO DE 2010 BONIFICACION DE $150 , SUPLEMENTO POR VESTUARIO AL  PERSONAL SERVICIO PENITENCIARIO | as enacted, in force 26 December 2010 |
| `ley-1891-s/` | Ley 1891-S: CREA EL INSTITUTO DEL DEPORTE CHAQUEÑO | as enacted, in force 30 March 2011 |
| `ley-1886-m/` | Ley 1886-M: PROTECCION INTEGRAL A LAS MUJERES - ADHIERE LN. 26.485 | as enacted, in force 19 December 2010 |
| `ley-1885-f/` | Ley 1885-F: CREDITO DEL BANCO NACIONAL DO DESENVOLVIMIENTO (BNADES) DE BRASIL P/ ACUEDUCTO INTERIOR DEL CHACO | as enacted, in force 5 December 2010 |
| `ley-1881-h/` | Ley 1881-H: MODIFICA VARIOS ARTICULOS E INCISOS DE LA LEY 800-H (ANTES LEY 4044) | as enacted, in force 14 January 2011 |
| `ley-1883-g/` | Ley 1883-G: CREA REGISTRO UNICO DE DONANTES VOLUNTARIOS DE SANGRE Y HEMOCOMPONENTES | as enacted, in force 24 December 2010 |
| `ley-1876-a/` | Ley 1876-A: EXPROPIA INMUEBLES EN LA LOCALIDAD DE TRES ISLETAS P/ TRANSFERIR AL MUNICIPIO | as enacted, in force 24 December 2010 |
| `ley-1880-a/` | Ley 1880-A: ESTABLECE A PARTIR DEL 1º/08/10, BONIFICACION DE $ 150" SUPLEMENTO POR VESTUARIO" PARA PERSONAL POLICIAL . | as enacted, in force 19 December 2010 |
| `ley-1877-e/` | Ley 1877-E: CREA FONDO PCIAL. ESPECIAL P/AYUDA ECONOMICA ESTUDIANTES UNIVERSITARIOS EN CUBA | as enacted, in force 19 December 2010 |
| `ley-1875-j/` | Ley 1875-J: CREA DIRECCIONES DE JUZGAMIENTO ADMIN. DE INFRACCIONES DE TRANSITO POLICIA DEL CHACO | as enacted, in force 28 November 2010 |
| `ley-1874-h/` | Ley 1874-H: CREA PROGRAMA SEGURO DE EMPLEO Y CAPACITACIÓN | as enacted, in force 19 November 2010 |
| `ley-1862-v/` | Ley 1862-V: PLAN CHACO EXPLORA 2015 - PLAN ESTRATEGICO DE TURISMO SUSTENTABLE 2015 | as enacted, in force 7 November 2010 |
| `ley-1872-a/` | Ley 1872-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO OCUPADO CON ASENTAMIENTOS ESPONTANEOS | as enacted, in force 3 November 2010 |
| `ley-1871-h/` | Ley 1871-H: REGIMEN DE RETIRO VOLUNTARIO MOVIL PARA PERSONAL DEL PODER LEGISLATIVO | as enacted, in force 7 November 2010 |
| `ley-1870-g/` | Ley 1870-G: RATIFICA DECRETO 1190/10 - PROYECTO ARG/09/R37 - FORTALEC. A LA GESTION DE INSUMOS MEDICOS | as enacted, in force 15 June 2010 |
| `ley-1866-e/` | Ley 1866-E: INSTITUYESE EL "DIA DE LA PRIMERA CONSTITUCION DE LA PROVINCIA DEL CHACO" | as enacted, in force 29 October 2010 |
| `ley-1867-a/` | Ley 1867-A: CREA UNA DEFENSORIA BARRIAL EN EL BARRIO GUIRALDE DE RESISTENCIA | as enacted, in force 29 October 2010 |
| `ley-1864-c/` | Ley 1864-C: CESION GRATUITO DERECHOS Y OBLIG. CONTRATO CONCESION USO ELEVADOR TERMINAL EX JUNTA NAC. DE GRANOS | as enacted, in force 22 October 2010 |
| `ley-1860-a/` | Ley 1860-A: EXPROPIA INMUEBLE EN BARRANQUERAS PARA CONSTR. HOSPITAL DE NIVEL COMPLEJIDAD III | as enacted, in force 3 November 2010 |
| `ley-1863-a/` | Ley 1863-A: CREA A PARTIR DEL 1º DE ENERO DE 2011 DOS CARGOS EN LA FISCALIA DE INVESTIGACIONES ADMINISTRATIVAS. | as enacted, in force 29 October 2010 |
| `ley-1859-a/` | Ley 1859-A: EXPROPIA INMUEBLE EN FONTANA  PARA LA CONSTRUCCION DEL HOSPITAL DE COMPL. III | as enacted, in force 29 October 2010 |
| `ley-1858-a/` | Ley 1858-A: PAGO DEL 100% DEL BASICO DEL AGENTE DE POLICIA P/CADETES A PARTIR DEL 2011-L.1746- | as enacted, in force 17 October 2010 |
| `ley-1856-e/` | Ley 1856-E: CREA EL COMITE DE LA CIUDAD DE RESISTENCIA "CAPITAL NACIONAL DE LAS ESCULTURAS" | as enacted, in force 17 October 2010 |
| `ley-1854-a/` | Ley 1854-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/ ADJUDICAR EN VENTA A SUS OCUPANTES | as enacted, in force 26 September 2010 |
| `ley-1852-e/` | Ley 1852-E: DECLARA PATRIMONIO HISTORICO Y CULTURAL EDIFICIO COMERCIAL "ARCA & SANTOS" DE GRAL. SAN MARTIN | as enacted, in force 26 September 2010 |
| `ley-1853-e/` | Ley 1853-E: INSTITÚYESE  EL "DIA DEL TRABAJADOR EN PSICOLOGÍA SOCIAL" 25 DE JUNIO DE CADA AÑO | as enacted, in force 22 September 2010 |
| `ley-1851-e/` | Ley 1851-E: INSTITUYE EL DIA 26 DE AGOSTO DE CADA AÑO FECHA ANIVERSARIO FUNDACION SELVA DEL RIO DE ORO | as enacted, in force 22 September 2010 |
| `ley-1850-f/` | Ley 1850-F: LEY DE AUTARQUIA DE LA ADMINISTRACION TRIBUTARIA PROVINCIAL | as enacted, in force 19 September 2010 |
| `ley-1849-a/` | Ley 1849-A: PROCEDIMIENTO P/DESIGNACION FUNCIONARIOS DE CONTADURIA Y TESORERIA DE LA PCIA. | as enacted, in force 13 August 2010 |
| `ley-1848-w/` | Ley 1848-W: DECLARA LENGUAS OFICIALES DE LA PCIA. A LAS DE LOS PUEBLOS QOM, MOQOIT Y WICHI | as enacted, in force 6 August 2010 |
| `ley-1846-h/` | Ley 1846-H: BONIFICACIÓN ESPECIAL MENSUAL, REMUNERATIVA Y PERMANENTE PERSONAL INSTITUTO DE TIERRAS FISCALES | as enacted, in force 13 August 2010 |
| `ley-1845-a/` | Ley 1845-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 13 August 2010 |
| `ley-1847-j/` | Ley 1847-J: CREA EN LA POLICIA DEL CHACO CON CARACTER DE DIRECCION GENERAL, LA POLICIA CAMINERA | as enacted, in force 13 August 2010 |
| `ley-1844-e/` | Ley 1844-E: DECLARA PATRIMONIO HISTORICO CULTURAL DE LA PCIA. AL CORO POLIFONICO DE RCIA. | as enacted, in force 13 August 2010 |
| `ley-1843-r/` | Ley 1843-R: AUTORIZA LA EXTRACCION Y TRASLADO DE MADERAS MUERTA P/ LEÑA CONSUMO PROPIO Y/O SU COMERCIALIZACION | as enacted, in force 27 August 2010 |
| `ley-1841-e/` | Ley 1841-E: PROCEDIMEINTO PARA LA IMPOSICION DE NOMBRE A LOS ESTABLECIMIENTOS ESCOLARES | as enacted, in force 13 August 2010 |
| `ley-1842-e/` | Ley 1842-E: DECLARA PATRIMONIO CULTURAL DE LA PROVINCIA, AL ACERVO MUSEOLOGICO DE LOS MUSEOS DEPENDIENTES DEL INST. DE CULTURA DEL CHACO | as enacted, in force 13 August 2010 |
| `ley-1840-c/` | Ley 1840-C: DERECHO DE "ADICION DEL APELLIDO MATERNO" P/RECIEN NACIDOS Y PERSONAS MAYORES | as enacted, in force 6 August 2010 |
| `ley-1838-x/` | Ley 1838-X: RATIFICA CONVENIO BILATERAL PROGRAMA FEDERAL DE DESCENDEUDAMIENTO DE LAS PCIAS. ARGENTINAS | as enacted, in force 16 July 2010 |
| `ley-1834-g/` | Ley 1834-G: REGIMEN PARA EL EJERCICIO  DE LA PROFESION DE LOS ODONTOLOGOS EN LA PROVINCIA | as enacted, in force 1 August 2010 |
| `ley-1835-r/` | Ley 1835-R: CREA LA COMISION DE INVESTIGACION DE CONTAMINANTES DEL AGUA | as enacted, in force 22 October 2010 |
| `ley-1833-e/` | Ley 1833-E: DESIGNACION P/EL CARGO DE SUPERVISOR DE MODALIDAD TECNICO AGROPECUARIA Y FORMACION PROFESIONAL | as enacted, in force 17 September 2010 |
| `ley-1832-r/` | Ley 1832-R: ADHESION L.N.26.438 - PRINCIPIOS RECTORES DE POLITICAS HIDRICAS DE LA REP. ARGENTINA | as enacted, in force 21 July 2010 |
| `ley-1829-d/` | Ley 1829-D: CREA EN LA PCIA. EL "REGISTRO DE PROTECCION AL USUARIO-CONSUMIDOR DE TELEFONO" | as enacted, in force 21 July 2010 |
| `ley-1827-g/` | Ley 1827-G: RECUPERO GASTOS EN CASO DE ACCIDENTES ATENDIDOS EN EST. DEL MINISTERIO DE SALUD PUBLICA | as enacted, in force 23 July 2010 |
| `ley-1830-d/` | Ley 1830-D: DISPONE IMPRESION EN FACTURAS  TELEFONO DE LA DCCION. DE COMERCIO INT. DE LA PCIA. | as enacted, in force 14 July 2010 |
| `ley-1826-j/` | Ley 1826-J: PROTOCOLO DE ACTUACION POLICIAL ANTE SITUACIONES DE VIOLENCIA CONTRA LAS MUJERES | as enacted, in force 2 July 2010 |
| `ley-1825-i/` | Ley 1825-I: REGIMEN DE CONSORCIOS PRODUCTIVOS DE SERVICIOS RURALES | as enacted, in force 25 June 2010 |
| `ley-1824-a/` | Ley 1824-A: EXPROPIACION TEMPORANEA NORMAL INMUEBLES Y MAQUINARIAS FRIGORIFICO "LAS TERMAS S.R.L." | as enacted, in force 6 June 2010 |
| `ley-1823-i/` | Ley 1823-I: CREA EL SISTEMA PCIAL. DE CERTIFICACION DE ORIGEN DE PRODUCTOS CHAQUEÑOS | as enacted, in force 27 June 2010 |
| `ley-1822-i/` | Ley 1822-I: CREA EL"PROGRAMA DE INCENTIVOS PARA EL DESARROLLO DE PROVEEDORES LOCALES" | as enacted, in force 27 June 2010 |
| `ley-1820-e/` | Ley 1820-E: DECLARA PATRIMONIO HISTORICO CULTURAL EDIFICIO IGLESIA ORTODOXA DE MACHAGAI | as enacted, in force 2 July 2010 |
| `ley-1819-e/` | Ley 1819-E: CREA EL MUSEO PCIAL. DE NIVEL INICIAL "MERCEDITAS DE SAN MARTIN" | as enacted, in force 20 June 2010 |
| `ley-1821-w/` | Ley 1821-W: INSTITUYE EL 14 DE MAYO DE CADA AÑO, COMO "DIA DE LAS COMUNIDADES INDIGENAS EN EL CHACO" | as enacted, in force 20 June 2010 |
| `ley-1818-a/` | Ley 1818-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 20 June 2010 |
| `ley-1816-e/` | Ley 1816-E: INSTITUYESE EL 23 DE MAYO COMO "DIA DE LOS CONSORCIOS CAMINEROS DE LA PROVINCIA DEL CHACO" | as enacted, in force 15 August 2010 |
| `ley-1817-a/` | Ley 1817-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 13 June 2010 |
| `ley-1815-d/` | Ley 1815-D: ESTABLECE PARA HIPERMERCADOS, SUPERMERCADOS, ETC. EXHIBIR EN GONDOLAS PRODUCTOS QUE SE ELABOREN Y COMERCIALICEN  DENTRO DE LA PCIA. | as enacted, in force 13 June 2010 |
| `ley-1814-e/` | Ley 1814-E: DECLARA PATRIMONIO HISTRICO CULTURAL DE LA PCIA. EDIFICIO EX-FABRICA LA CHAQUEÑA | as enacted, in force 6 June 2010 |
| `ley-1600-f/` | Ley 1600-F: ADHIERE L.N. 24.977 E INCORPORA INCS. T) Y U) ART.128, CAPITULO V D.L.2444/62 | as enacted, in force 21 December 2007 |
| `ley-1811-j/` | Ley 1811-J: PROTOCOLO DE DETECCION SISTEMATICA DE SITUACIONES DE VIOLENCIA CONTRA LA MUJER EN LA CONSULTA MEDICA | as enacted, in force 9 June 2010 |
| `ley-1812-w/` | Ley 1812-W: ADHESION L.N. 26.160 - EMERGENCIA POSESION Y PROPIEDAD DE TIERRAS COMUN. INDIGENAS ORIGINARIAS DEL PAIS | as enacted, in force 23 May 2010 |
| `ley-1810-e/` | Ley 1810-E: DECLARA COMO INTEGRANTE PATRIM. CULTURAL DEL CHACO VARIAS COMPOSIC. MUSICALES | as enacted, in force 21 May 2010 |
| `ley-1809-e/` | Ley 1809-E: ADHESION L.N.26.582 - CONMEM. DE LA OBRA REALIZADA POR MONS. ENRIQUE ANGELELLI | as enacted, in force 16 May 2010 |
| `ley-1804-e/` | Ley 1804-E: PATRIMONIO CULTURAL DE LA PCIA. AL CONJUNTO DE CONSTRUCC. EDILICIAS EN BQUERAS. | as enacted, in force 17 September 2010 |
| `ley-1805-g/` | Ley 1805-G: ADHESION L.N. 26.588 - DECLARA DE INT. NAC. DETECC. TEMPRANA ENFERMEDAD CELIACA | as enacted, in force 16 May 2010 |
| `ley-1807-e/` | Ley 1807-E: ADHESION L.N. 26.586 - PROGRAMA NAC. DE EDUC. Y PREVENC. S/ADICC. Y CONS. DROGAS | as enacted, in force 16 May 2010 |
| `ley-1806-g/` | Ley 1806-G: ADHESION L.N. 25.501 - PRIORIDAD SANITARIA CONTROL Y PREVENC. ENFERM. CARDIOVASC. | as enacted, in force 16 May 2010 |
| `ley-1802-a/` | Ley 1802-A: EXPROPIA INMUEBLES PARA SER ADJUDICADOS EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 16 May 2010 |
| `ley-1801-a/` | Ley 1801-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 9 May 2010 |
| `ley-1800-k/` | Ley 1800-K: SUSTITUYE REDACCION DE LOS ARTICULOS 1º Y 3º DE LA LEY 6287 | as enacted, in force 12 March 2010 |
| `ley-1794-b/` | Ley 1794-B: REGIMEN INTEGRAL PARA LA INCLUSION DE LAS PERSONAS CON DISCAPACIDAD | as enacted, in force 5 February 2010 |
| `ley-1793-g/` | Ley 1793-G: CREA EL "FONDO PROVINCIAL PARA EL FINANCIAMIENTO DE LA SALUD PUBLICA" | as enacted, in force 27 January 2010 |
| `ley-1791-k/` | Ley 1791-K: ADHESION L.N. 26.360 - PROMOC. DE INVERC. BIENES DE CAPITAL Y OBRAS DE INFRAESTRUCT. | as enacted, in force 24 January 2010 |
| `ley-1796-e/` | Ley 1796-E: CREASE EL FONDO EDUCATIVO PROVINCIAL - DEROGA LA LEY 3591 | as enacted, in force 7 February 2010 |
| `ley-1789-k/` | Ley 1789-K: ADHESION L.N. 26.095 - OBRAS DE INFRAESTRUCTURA ENERGETICA | as enacted, in force 20 January 2010 |
| `ley-1797-f/` | Ley 1797-F: ADHESION L.N. 26.530 - EXCEPCIONES L.N. 25.917 - CREACION REG. FEDERAL DE RESP. FISCAL | as enacted, in force 24 January 2010 |
| `ley-1786-a/` | Ley 1786-A: RECOMPOSICION SALARIAL DEL 5% A PARTIR DEL 1º DE JUNIO DE 2010 PERSONAL ADM. PCA. | as enacted, in force 6 January 2010 |
| `ley-1788-x/` | Ley 1788-X: CREA EL CONSEJO FEDERAL LEGISLATIVO DE SALUD (COFELESA) | as enacted, in force 20 January 2010 |
| `ley-1787-h/` | Ley 1787-H: EXIME DE TASAS JUDICIALES Y OTROS P/ ACCEDER TRAMITE ASIGNACION UNIVERSAL P/ HIJO | as enacted, in force 17 January 2010 |
| `ley-1785-e/` | Ley 1785-E: CREA EL REGIMEN DE PASANTIAS PARA ALUMNOS/AS CON DISCAPACIDADES TEMP. O PERMAN. | as enacted, in force 17 January 2010 |
| `ley-1784-g/` | Ley 1784-G: INSTALACION Y UTILIZACION EQUIPOS GENERADORES DE RADIACION ULTRAVIOLETA (RUV) | as enacted, in force 21 January 2010 |
| `ley-1782-c/` | Ley 1782-C: LEY DE MEDIACION FAMILIAR OBLIGATORIA | as enacted, in force 9 May 2010 |
| `ley-1783-f/` | Ley 1783-F: "FIDEICOMISO DE CUSTODIA, ADMINISTR., INVERSION Y PAGOS P/ CONSTR. EDIF. P. LEGISL." | as enacted, in force 6 January 2010 |
| `ley-1781-a/` | Ley 1781-A: EXPROPIA INMUEBLE Y MAQUINAS EX DIARIO "TRIBUNA CHAQUEÑA" EN SAENZ PEÑA | as enacted, in force 6 January 2010 |
| `ley-1780-e/` | Ley 1780-E: DECLARA PATRIMONIO CULTURAL VIVIENTE AL ESCRITOR Y POETA ALEDO LUIS MELONI | as enacted, in force 18 December 2009 |
| `ley-1777-x/` | Ley 1777-X: AUTORIZA SUSCRIBIR ADDENDA MODIF. DEL CONVENIO C/BCO. NACION RATIF. POR LEY 6141 | as enacted, in force 18 December 2009 |
| `ley-1778-e/` | Ley 1778-E: SISTEMA PROVINCIAL DE BECAS DE INCLUSION EDUCATIVA | as enacted, in force 16 May 2010 |
| `ley-1775-e/` | Ley 1775-E: LEY DE ESTADISTICAS Y CENSOS -  DEROGA LA LEY 2146 | as enacted, in force 10 September 2010 |
| `ley-1776-g/` | Ley 1776-G: REGIMEN EJERCICIO PROFESIONAL DE OPTICA OFTALMICA E INSTRUMENTAL | as enacted, in force 18 December 2009 |
| `ley-1773-g/` | Ley 1773-G: PROGRAMA "EDUCACION COMUNITARIA PARA LA OBTENCION DE SANGRE SEGURA" | as enacted, in force 6 December 2009 |
| `ley-1774-b/` | Ley 1774-B: ACCESO A LA INFORMACION - DERECHO A LA INFORMACION | as enacted, in force 13 December 2009 |
| `ley-1770-h/` | Ley 1770-H: CREA PROGRAMA PCIAL. DE APOYO P/ ACCEDER A LA JUBILACION - L.N. 24.476 | as enacted, in force 4 December 2009 |
| `ley-1769-a/` | Ley 1769-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 4 December 2009 |
| `ley-1767-l/` | Ley 1767-L: REGIMEN DE NEGOCIACIONES COLECTIVAS (PARITARIAS) | as enacted, in force 15 January 2010 |
| `ley-1766-c/` | Ley 1766-C: ADHESION PROVINCIAL L.N. 26.493 - MODIFICACION DE LA LEY S/REGULARIZ. DOMINIAL | as enacted, in force 22 November 2009 |
| `ley-1768-e/` | Ley 1768-E: DECLARA PATRIMONIO CULTURAL A LA EX FABRICA "FABRIL FINANCIERA" | as enacted, in force 22 November 2009 |
| `ley-1765-e/` | Ley 1765-E: DECLARA PATRIMONIO CULTURAL CHIMENEA EX-COMPLEJO INDUSTRIAL "CODUTTI" | as enacted, in force 22 March 2010 |
| `ley-1764-e/` | Ley 1764-E: DECLARA PATRIMONIO HISTORICO CULTURAL EDIFICIO ESCUELA Nº 16 DE LAS PALMAS | as enacted, in force 21 March 2010 |
| `ley-1760-a/` | Ley 1760-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/ ADJUDICAR EN VENTA  ACTUAL. OCUPANTES | as enacted, in force 18 October 2009 |
| `ley-1759-e/` | Ley 1759-E: DECLARA PATRIMONIO CULTURAL VIVIENTE AL ARTISTA MENOLDO DIAZ | as enacted, in force 18 October 2009 |
| `ley-1757-a/` | Ley 1757-A: BANDERA OFICIAL DE LA PROVINCIA DEL CHACO | as enacted, in force 18 October 2009 |
| `ley-1755-g/` | Ley 1755-G: IMPLEMENTA CAMPAÑA DE INFORMACION NUTRICIONALES PARA CONSUMIDOR ADULTO | as enacted, in force 4 October 2009 |
| `ley-1756-e/` | Ley 1756-E: INSTITUYE COMO EL "DIA DE LA DANZA DEL CHACO" EL 27 DE AGOSTO DE CADA AÑO | as enacted, in force 4 October 2009 |
| `ley-1752-a/` | Ley 1752-A: EL P.E. DONA INMUEBLE EN SAN BERNARDO P/ASOC. CIVIL CASA DEL NIÑO S. C. DE JESUS | as enacted, in force 4 October 2009 |
| `ley-1750-g/` | Ley 1750-G: FONDO PARA INVESTIGACION CIENTIFICA Y ESTUDIOS CITOGENETICOS, MALFORM. ETC. | as enacted, in force 4 October 2009 |
| `ley-1749-a/` | Ley 1749-A: CREA EL CONSEJO ASESOR CONSULTIVO P/ LAS POLITICAS CULTURALES CHAQUEÑAS | as enacted, in force 4 October 2009 |
| `ley-1745-e/` | Ley 1745-E: INSTITUYE EL "DIA DEL CANTO CORAL DEL CHACO" EL 19 DE AGOSTO DE CADA AÑO | as enacted, in force 13 September 2009 |
| `ley-1744-e/` | Ley 1744-E: CREASE EN LA PCIA. DEL CHACO EL ESPACIO CULTURAL "MALVINAS ARGENTINAS" | as enacted, in force 18 September 2009 |
| `ley-1743-a/` | Ley 1743-A: CREA LA AGENCIA PROVINCIAL DE SEGURIDAD VIAL (APSV) | as enacted, in force 13 September 2009 |
| `ley-1741-h/` | Ley 1741-H: RECONOCE COMO AÑO DE SERVICIO EL SERVICIO MILITAR A LOS DOCENTES | as enacted, in force 5 August 2009 |
| `ley-1739-e/` | Ley 1739-E: INSTITUYE EL 31 DE MARZO COMO "DIA DE LA ETICA REPUBLICANA Y DEMOCRATICA" | as enacted, in force 22 July 2009 |
| `ley-1738-j/` | Ley 1738-J: ADHESION L.N.26.290 - FUERZA DE SEGURIDAD. CAPACITACION | as enacted, in force 26 July 2009 |
| `ley-1747-a/` | Ley 1747-A: EXPROPIA INMUEBLE EN RCIA. P/INSTITUTO DEL PROFESORADO DE ENSEÑANZAS ARTISTICAS | as enacted, in force 23 September 2009 |
| `ley-1737-a/` | Ley 1737-A: CREA JUZGADO MULTIFUEROS Y FISCALIA DE INVESTIGACIONES EN NUEVA POMPEYA | as enacted, in force 22 July 2009 |
| `ley-1736-j/` | Ley 1736-J: PROHIBE EN LA PCIA. LA VENTA DE BEBIDAS ENERGIZANTES A MENORES DE 18 AÑOS | as enacted, in force 15 July 2009 |
| `ley-1735-a/` | Ley 1735-A: EXPROPIA INMUEBLES EN GRAL. SAN MARTIN P/CENTRO DE ESTUDIOS UNIVERSITARIOS | as enacted, in force 15 July 2009 |
| `ley-1734-l/` | Ley 1734-L: ESTABLECE EL EJERCICIO DE LA PROFESION DE OPERADOR EN PSICOLOGIA SOCIAL. | as enacted, in force 15 July 2009 |
| `ley-1742-a/` | Ley 1742-A: RECONOCIMIENTO DE SERVICIOS A AGENTES EXONERADOS SIN SUMARIO ADMINISTRATIVO | as enacted, in force 2 September 2009 |
| `ley-1733-e/` | Ley 1733-E: EL MINISTERIO DE EDUCACION OTORGARA COMPETENCIA DE TITULO A PROFESORES | as enacted, in force 3 July 2009 |
| `ley-1732-a/` | Ley 1732-A: LAS  COLONIAS DE VACACIONES SERA ORGANIZADO  Y CONTROLADO POR EL P. EJECUT. | as enacted, in force 3 July 2009 |
| `ley-1731-g/` | Ley 1731-G: ADHESION L.N.26.369 - CONTROL Y PREVENC. EXAMEN DETECC. ESTREPTOCOCO GR."B" | as enacted, in force 8 July 2009 |
| `ley-1730-f/` | Ley 1730-F: ADHESION ACUERDO PRECIO GAS LICUADO DE PETROLEO (GLP) MOD. D.L. 2444/62 | as enacted, in force 17 June 2009 |
| `ley-1729-e/` | Ley 1729-E: ADHESION L.N.26.316 - DIA NAC. P/LA PREVENC. DEL ABUSO C/NIÑOS, NIÑAS Y ADOL. | as enacted, in force 5 July 2009 |
| `ley-1724-e/` | Ley 1724-E: LEY PROVINCIAL SOBRE EDUCACION INCLUSIVA | as enacted, in force 3 July 2009 |
| `ley-1727-n/` | Ley 1727-N: CREA REGISTRO DE CONDENADOS POR DELITOS CONTRA LA INTEGRIDAD SEXUAL | as enacted, in force 5 July 2009 |
| `ley-1726-n/` | Ley 1726-N: CREA BANCO PCIAL. DE HUELLAS GENETICAS DIGITALIZADAS MOD. ART.405 L.4538 | as enacted, in force 5 July 2009 |
| `ley-1728-x/` | Ley 1728-X: CONVENIO MARCO EJECUTOR-PROVINCIA PROGRAMA AGUA POTABLE Y SANEAMIENTO | as enacted, in force 5 June 2009 |
| `ley-1725-a/` | Ley 1725-A: EXPROPIA INMUEBLES EN DEPARTAMENTO LIBERTADOR GENERAL SAN MARTIN PARA ADJUDICAR A PRODUCTORES | as enacted, in force 17 June 2009 |
| `ley-1723-e/` | Ley 1723-E: CREA EN  EST. ESCOLARES SERVICIOS PEDAGOGICOS P/ HIJOS MENORES DE ALUMNOS | as enacted, in force 5 June 2009 |
| `ley-1722-k/` | Ley 1722-K: CONDONA SALDOS IMPAGOS Y DEUDAS PENDIENTES POR VIVIENDAS EX COMBATIENTES | as enacted, in force 22 May 2009 |
| `ley-1719-e/` | Ley 1719-E: DECLARA PATRIMONIO CULTURAL DE LA PCIA. EDIFICIO EX ESCUELA 69 PTO. VILELAS | as enacted, in force 13 September 2009 |
| `ley-1721-u/` | Ley 1721-U: ADHIERE L.N.24.204 - SERVICIO DE TELEFONIA PUBLICA PARA DISCAPACITADOS | as enacted, in force 22 May 2009 |
| `ley-1718-s/` | Ley 1718-S: ADHESION L.N.26.462 - PROGRAMA SOCIAL Y DEPORTIVO "JUEGOS NACIONALES EVITA" | as enacted, in force 22 May 2009 |
| `ley-1717-q/` | Ley 1717-Q: CREA REGISTRO PUBLICO DE POSTULANTES DE AUTOR. DE MESA. MOD. ART.102 LEY 834-Q. | as enacted, in force 22 May 2009 |
| `ley-1716-x/` | Ley 1716-X: CONVENIO P/CONCURSO DE ANTEPROYECTOS EDIFICIO CAMARA DE DIPUTADOS | as enacted, in force 3 May 2009 |
| `ley-1715-f/` | Ley 1715-F: EXIME DEL IMPUESTO DE SELLOS A LOS CONTRATOS FORMALIZADOS POR L.6141 | as enacted, in force 3 May 2009 |
| `ley-1714-e/` | Ley 1714-E: CREA LA CAMPAÑA  DE INFORMACION, CONCIENTIZACION Y PREVENCION DEL DENGUE | as enacted, in force 24 April 2009 |
| `ley-1713-a/` | Ley 1713-A: EL P.E. TRANSFIERE INMUEBLE EN RCIA. AL CENTRO DE EX SOLDADOS COMB. DE MALV. | as enacted, in force 22 April 2009 |
| `ley-1711-e/` | Ley 1711-E: INSTITUYESE EL 21 DE JUNIO DE C. AÑO EL "DIA DE LA CONFRATERNIDAD ANTARTICA" | as enacted, in force 22 April 2009 |
| `ley-1710-e/` | Ley 1710-E: DECLARA PATRIMONIO CULTURAL PCIAL. AL RITMO MUSICAL "CHACARERA DEL MONTE" | as enacted, in force 22 April 2009 |
| `ley-1709-g/` | Ley 1709-G: PROGRAMA  "JOVENES LIDERES P/ LA PREVENCION DEL VIH SIDA Y ENFERM. SEXUAL" | as enacted, in force 8 February 2009 |
| `ley-1708-e/` | Ley 1708-E: DECLARA PATRIMONIO CULTURAL DE LA PCIA. AL CIRCULO ITALIANO "DANTE ALIGHIERI" | as enacted, in force 8 February 2009 |
| `ley-1707-e/` | Ley 1707-E: DECLARA PATRIMONIO CULTURAL DE LA PCIA. ESTACIONES DEL FERROCARRIL. | as enacted, in force 8 February 2009 |
| `ley-1706-c/` | Ley 1706-C: PROGRAMA DE INFORMACION Y CONCIENTIZ. SOBRE  EL DERECHO A LA IDENTIDAD | as enacted, in force 8 February 2009 |
| `ley-1705-f/` | Ley 1705-F: EL IPDUV CONTRAERA EMPRESTITOS CON EL ANSSES POR $ 420.000.000 | as enacted, in force 8 February 2009 |
| `ley-1704-i/` | Ley 1704-I: FONDO PROVINCIAL DEL DESARROLLO DE LA INDUSTRIA CÁRNICA | as enacted, in force 8 February 2009 |
| `ley-1703-j/` | Ley 1703-J: PROTOCOLO DE ACTUACION POLICIAL EN MATERIA DE DESAPARICION DE PERSONAS | as enacted, in force 8 February 2009 |
| `ley-1702-a/` | Ley 1702-A: LOS ACT0S ADMINISTRAT. DEL  PODER EJECUTIVO SERAN PUBLICADOS EN SITIO WEB | as enacted, in force 8 February 2009 |
| `ley-1701-i/` | Ley 1701-I: ADHESION L.N. 17.319 - LEY DE HIDROCARBUROS | current text only, as of 26 March 2018 |
| `ley-1700-a/` | Ley 1700-A: APRUEBA LA "ADDENDA AL CONVENIO DE PARTICIPACION EN EL PERMER" | as enacted, in force 1 February 2009 |
| `ley-1699-a/` | Ley 1699-A: MODIFICA LOS ARTS. 1º, 3º Y 10 Y DEROGA LOS ARTS. 14 Y 15 DE LA LEY 200-A (ANTES LEY 1307) | as enacted, in force 1 February 2009 |
| `ley-1698-a/` | Ley 1698-A: EXPROPIA INMUEBLE  DPTO. 25 DE MAYO  A FAVOR DEL INST. DEL ABORIGEN CHAQ. | as enacted, in force 25 January 2009 |
| `ley-1697-e/` | Ley 1697-E: DECLARA PATRIMONIO CULTURAL AL ACERVO DEL MUSEO DE TITERE "TIBI" | as enacted, in force 25 January 2009 |
| `ley-1696-e/` | Ley 1696-E: DECLARA PATRIMONIO HISTORICO CULTURAL EDIFICIO UNIVERSIDAD POPULAR | as enacted, in force 25 January 2009 |
| `ley-1695-e/` | Ley 1695-E: DECLARA PATRIM. HISTORICO CULTURAL AL EDIFICIO DEL BANCO DE LA NACION | as enacted, in force 25 January 2009 |
| `ley-1694-e/` | Ley 1694-E: DECLARA PATRIMONIO HISTORICO CULTURAL AL EDIFICIO EX LT5 "RADIO CHACO" | as enacted, in force 25 January 2009 |
| `ley-1693-e/` | Ley 1693-E: DECLARA PATRIMONIO HISTORICO CULTURAL EDIFICIO EX-DIARIO EL TERRITORIO | as enacted, in force 25 January 2009 |
| `ley-1692-e/` | Ley 1692-E: DECLARA PATRIM. HISTORICO CULT. EDIFICIO INSTIT. CHAQU. DE CULT. INGLESA | as enacted, in force 25 January 2009 |
| `ley-1691-e/` | Ley 1691-E: DECLARA PATRIM. HISTORICO CULTURAL DE LA PCIA. SEDE PARTIDO SOCIALISTA | as enacted, in force 25 January 2009 |
| `ley-1689-h/` | Ley 1689-H: LOS DOCENTES JUBILADOS PODRAN OPTAR POR LO ESTABLECIDO EN LA LEY 6124 | as enacted, in force 5 June 2009 |
| `ley-1686-e/` | Ley 1686-E: INSTITUYE EL DIA 16 DE AGOSTO COMO "DIA DEL EMPRESARIO CHAQUEÑO" | as enacted, in force 14 December 2008 |
| `ley-1688-a/` | Ley 1688-A: EXPROPIA INMUEBLE EN BQUERAS P/ ADJUDICAR AL MUNICIPIO PARA RESERVORIO | as enacted, in force 7 December 2008 |
| `ley-1687-j/` | Ley 1687-J: IMPLEMENTA EJERCICIOS DE EVACUACION EN EDIFICIOS PUBLICOS Y ESCUELAS | as enacted, in force 7 December 2008 |
| `ley-1684-t/` | Ley 1684-T: ADHESION L.N. 26.363 - TRANSITO Y SEG. VIAL- CREACION AGENCIA NAC. DE SEG. VIAL | as enacted, in force 7 December 2008 |
| `ley-1685-e/` | Ley 1685-E: DECLARA PATRIMONIO HISTORICO  CULTURAL LA CHIMENEA DE EX-FABRICA DE VILELAS | as enacted, in force 7 December 2008 |
| `ley-1681-g/` | Ley 1681-G: CREA EL SISTEMA DE TRAUMA Y EMERGENCIA SANITARIA EN LA PCIA. DEL CHACO | as enacted, in force 23 November 2008 |
| `ley-1682-e/` | Ley 1682-E: CREA EL SISTEMA PROVINCIAL DE PASANTIAS | as enacted, in force 23 November 2008 |
| `ley-1679-e/` | Ley 1679-E: DECLARA PATRIM. HISTORICO CULTURAL DE LA PCIA. EDIFICIO COMITE U. C. RADICAL | as enacted, in force 16 November 2008 |
| `ley-1680-e/` | Ley 1680-E: DECLARA PATRIM. HISTORICO CULTURAL DE LA PCIA. EDIFICIO SEDE PART.JUSICIALISTA | as enacted, in force 16 November 2008 |
| `ley-1678-e/` | Ley 1678-E: DECLARA A LA LOCALIDAD DE LAS PALMAS COMO "PRIMERA LUZ DE LA PATRIA" | as enacted, in force 16 November 2008 |
| `ley-1676-a/` | Ley 1676-A: CREASE EL MUSEO PROVINCIAL DEL ALGODON "INGENIERO EUGENIO IMFELD" | as enacted, in force 31 October 2008 |
| `ley-1671-a/` | Ley 1671-A: CREA ALBERGUE PROVINCIAL. PARA FAMILIARES DE PACIENTES HOSPITAL 4 DE JUNIO EN PRESIDENCIA  ROQUE SAENZ  .PEÑA | as enacted, in force 31 October 2008 |
| `ley-1672-a/` | Ley 1672-A: EXPROPIA INMUEBLES EN DPTO. SAN FERNANDO P/ ADJUDICAR EN VENTA A ACT. OCUP. | as enacted, in force 31 October 2008 |
| `ley-1673-a/` | Ley 1673-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/ ADJUDICAR EN VENTA ACT. OCUPANTES. | as enacted, in force 31 October 2008 |
| `ley-1670-h/` | Ley 1670-H: IN.S.S.SE.P CUBRIRA TRATAMIENTO DEL LINFEDEMA POST MASTECTOMIAS | as enacted, in force 12 October 2008 |
| `ley-1668-h/` | Ley 1668-H: COBERTURA OBRA SOCIAL FAMILIARES DESAPARECIDOS O PRIVADOS DE LIBERTAD | as enacted, in force 17 October 2008 |
| `ley-1667-a/` | Ley 1667-A: EXPROPIA MAQUINARIAS P/ COOPERATIVA DE TRABAJO "HILANDEREIA V. ANGELA LTDA." | as enacted, in force 31 October 2008 |
| `ley-1664-e/` | Ley 1664-E: LEY DE MUSEOS DE LA PROVINCIA DEL CHACO | as enacted, in force 16 November 2008 |
| `ley-1665-a/` | Ley 1665-A: CREA  COMISIÓN DE CONMEMORACIÓN . DE LA DECLARACIÓN UNIVERSAL. DE LOS DERECHOS HUMANOS | as enacted, in force 28 September 2008 |
| `ley-1666-e/` | Ley 1666-E: INSTITUYA EL "DÍA DEL CANTO Y DE LA MÚSICA POPULAR" EL 8 DE SETIEMBRE | as enacted, in force 26 September 2008 |
| `ley-1663-a/` | Ley 1663-A: EXPROPIA INMUEBLES EN RCIA. P/ CONSTRUCCION EDIFICIO DEL PODER LEGISLATIVO Y DEL PARQUE DE LA DEMOCRACIA Y LA JUVENTUD | as enacted, in force 21 September 2008 |
| `ley-1662-f/` | Ley 1662-F: AUTORIZA A S.A.M.E.E.P. A CONTRAER CREDITO HASTA LA SUMA DE $ 25.000.000,- | as enacted, in force 14 September 2008 |
| `ley-1661-g/` | Ley 1661-G: CREA EL BANCO DE CELULAS "MADRE" | as enacted, in force 26 September 2008 |
| `ley-1660-e/` | Ley 1660-E: INSTITUYESE  EL "DIA DE LA POESIA EN EL CHACO" EL 30 DE OCTUBRE DE CADA AÑO | as enacted, in force 12 September 2008 |
| `ley-1658-n/` | Ley 1658-N: MEDIDAS DE PREVENCION Y PROTECCION VICTIMAS DE LA TRATA DE PERSONAS | as enacted, in force 8 February 2009 |
| `ley-1657-l/` | Ley 1657-L: EQUIPARA REMUNERACIONES P/TRABAJADORES COMPRENDIDOS EN ESCALAFON LEY 196-A (ANTES LEY 1276) | as enacted, in force 8 October 2008 |
| `ley-1656-g/` | Ley 1656-G: NORMAS PARA LOCALES QUE PROVEAN  EL SERVICIO CAMAS SOLARES | as enacted, in force 5 September 2008 |
| `ley-1655-e/` | Ley 1655-E: INSTITUYE LA CRUZ ROJA ESCOLAR EN ESTABLECIMIENTOS EDUCATIVOS DE LA PCIA. | as enacted, in force 29 August 2008 |
| `ley-1653-d/` | Ley 1653-D: ADHESION L.N.26.005 - CONSORCIOS DE COOPERACION | as enacted, in force 29 August 2008 |
| `ley-1652-e/` | Ley 1652-E: INSTITÚYESE "MES DE LA JUVENTUD EN LA PCIA. DEL CHACO" AL MES DE SEPTIEMBRE | as enacted, in force 5 September 2008 |
| `ley-1651-g/` | Ley 1651-G: CREA LA RED DE BANCOS DE LECHE HUMANA | as enacted, in force 26 September 2008 |
| `ley-1650-a/` | Ley 1650-A: REGULARIZACION DOMINIAL DE INMUEBLES URBANOS S/L.N. 24.374 | current text only, as of 22 October 2018 |
| `ley-1649-w/` | Ley 1649-W: INSTITUYE EL 19 DE JULIO "DIA DE LOS DERECHOS  DE LOS PUEBLOS ORIGINARIOS DEL CHACO" | as enacted, in force 14 December 2008 |
| `ley-1648-e/` | Ley 1648-E: INSTITUYE EL "DIA DE LOS ARCHIVOS DEL CHACO" EL 17 DE AGOSTO DE CADA AÑO | as enacted, in force 17 August 2008 |
| `ley-1647-c/` | Ley 1647-C: OBLIGATORIEDAD EN LOCALES DE JUEGOS  CARTEL ADVIRTIENDO DAÑOS P/ LA SALUD | as enacted, in force 14 December 2008 |
| `ley-1646-a/` | Ley 1646-A: BONIFICAC. POR TITULO UNIVERSIT. FISCAL DE ESTADO A PARTIR  1º DE ABRIL 2008 | as enacted, in force 20 July 2008 |
| `ley-1643-e/` | Ley 1643-E: CREA "PREMIO DERECHOS HUMANOS AMANDA M. DE PIEROLA DE LA LEGISLATURA DE LA PCIA. DEL CHACO" | as enacted, in force 20 July 2008 |
| `ley-1645-a/` | Ley 1645-A: CREA FISCALIA EN LO CORRECC. Y CIVIL DE LA CUARTA CIRCUNSCR. JUDIC. EN CHRATA | as enacted, in force 20 July 2008 |
| `ley-1644-e/` | Ley 1644-E: CONTROL Y USO DE DE CELULARES EN ESTABLECIMIENTOS EDUCATIVOS | as enacted, in force 20 July 2008 |
| `ley-1642-x/` | Ley 1642-X: CONVENIO DE ASISTENCIA FINANCIERA - REGIMEN FEDERAL DE RESPONSABIL. FISCAL | as enacted, in force 16 July 2008 |
| `ley-1640-e/` | Ley 1640-E: INSTITUYESE EL 24 DE ABRIL EL "DIA DE LA MUSICA EN EL CHACO" | as enacted, in force 20 July 2008 |
| `ley-1639-x/` | Ley 1639-X: CONVENIO P/ASISTIR A PRODUCTORES AGROPECUARIOS Y NO AGROPECUARIOS | current text only, as of 25 June 2018 |
| `ley-1638-b/` | Ley 1638-B: CREA LA OFICINA CONTRA LA DISCRIMINACION , LA XENOFOBIA Y EL RACISMO | as enacted, in force 18 June 2008 |
| `ley-1636-e/` | Ley 1636-E: INSTITÚYESE LA "SEMANA DE LA CULTURA DE LA PAZ" | as enacted, in force 13 June 2008 |
| `ley-1635-e/` | Ley 1635-E: IMPONESE EL NOMBRE DE "RAUL DELFINO BERNERI" AL MUSEO DE MEDIOS DE COMUNICACIONES. | as enacted, in force 13 June 2008 |
| `ley-1633-b/` | Ley 1633-B: ADHESION L.N.26.298 - CONVEN. INTERN. PROTECC. PERSONAS C/ DESAP.FORZADAS | as enacted, in force 13 June 2008 |
| `ley-1632-e/` | Ley 1632-E: ADHESION L.N.25.743 - PROTECCION DEL PATRIMONIO ARQUEOLOGICO Y PALEONTOL. | as enacted, in force 13 June 2008 |
| `ley-1629-e/` | Ley 1629-E: INSTITUYESE EL 07 DE JULIO "DIA DE LOS MUSEOS DEL CHACO" | as enacted, in force 8 June 2008 |
| `ley-1630-x/` | Ley 1630-X: CONVENIO DE TRANSFERENCIA DE RUTAS ENTRE VIALIDAD PCIAL. Y VIALIDAD NACIONAL | as enacted, in force 8 June 2008 |
| `ley-1631-x/` | Ley 1631-X: CONVENIO DE TRANSFERFENCIA DE RUTAS VIALIDAD PCIAL. Y VIALIDAD NACIONAL | as enacted, in force 8 June 2008 |
| `ley-1628-j/` | Ley 1628-J: CREA SERVICIO PENITENCIARIO PROVINCIAL | as enacted, in force 20 August 2008 |
| `ley-1627-e/` | Ley 1627-E: "PREMIO MOJON" DEL PODER LEGISLATIVO BIENAL INTERN. DE ESCULTURA 2008" | as enacted, in force 25 May 2008 |
| `ley-1626-e/` | Ley 1626-E: CONCURSO PCIAL. ANUAL DE ENSAYOS "LEGISLAD. AURORA EDITH SILVA DE FRESCHI " | as enacted, in force 13 July 2008 |
| `ley-1625-e/` | Ley 1625-E: ADHESION L.N.26.320 - "DIA NACIONAL DE LA GRATUIDAD DE LA ENSEÑANZA UNIVERS." | as enacted, in force 25 May 2008 |
| `ley-1624-e/` | Ley 1624-E: CONCURSO ANUAL LITERARIO DE POESIA Y NARRATIVA "CORINA SILVA DE PITAU" | as enacted, in force 25 May 2008 |
| `ley-1623-b/` | Ley 1623-B: DERECHO A LA IDENTIDAD DE LOS VETERANOS DE GUERRA SEPULTADOS EN MALVINAS | as enacted, in force 25 May 2008 |
| `ley-1622-a/` | Ley 1622-A: ADHESION L.N. 25.783 - SE INSTITUYE EL 26 DE MARZO COMO DIA DEL MERCOSUR | as enacted, in force 9 May 2008 |
| `ley-1621-g/` | Ley 1621-G: ADHESION L.N.26.281 - PREVENCION Y CONTROL TRANSMIS. ENFERMEDAD DE CHAGAS | as enacted, in force 2 May 2008 |
| `ley-1620-k/` | Ley 1620-K: PROCEDIMIENTO PARA LA CONSTRUCCION EDIFICIO CAMARA DE DIPUTADOS. DEROGA LEY 5690 | as enacted, in force 23 April 2008 |
| `ley-1619-e/` | Ley 1619-E: DECLARA DE INTERES PCIAL. A PROMOVER LA INTERCULTURALIDAD DESDE EL AÑO 2008 | as enacted, in force 20 February 2008 |
| `ley-1618-a/` | Ley 1618-A: MODIFICA ARTICULO 5º DE LA LEY 913-B (ANTES LEY 4396) (FISCALES DE INVESTIG. RURAL Y AMBIENTAL) | as enacted, in force 3 February 2008 |
| `ley-1617-e/` | Ley 1617-E: INICIATIVA LATINOAMERICANA PARA LA IDENTIFICACION DE DESAPARECIDOS 1974-1983 | as enacted, in force 3 February 2008 |
| `ley-1616-a/` | Ley 1616-A: EXPROPIA INMUEBLE EN PTO. VILELAS DESTINADO AL PARQUE INDUSTRIAL | as enacted, in force 3 February 2008 |
| `ley-1615-e/` | Ley 1615-E: ADHESION L.N.20.770 - DECLARA EL 20 DE NOVIEMBRE DIA DE LA SOBERANIA NACION. | as enacted, in force 25 January 2008 |
| `ley-1614-h/` | Ley 1614-H: BONIFICACIONES Y ADICIONALES PARA BENEFICIARIOS DE LAS LEYES 1369-H y 1370-H | as enacted, in force 4 December 2009 |
| `ley-1612-a/` | Ley 1612-A: SERVICIO DE ATENCION EN LA LENGUA DE SEÑAS ARGENTINAS P/ PERSONAS MUDAS | as enacted, in force 18 January 2008 |
| `ley-1611-a/` | Ley 1611-A: ADICIONAL 25% P/ SUBTESORERO GRAL. POR  "RESPONSABILIDAD FUNCIONAL" | as enacted, in force 16 January 2008 |
| `ley-1610-a/` | Ley 1610-A: EXPROPIA INMUEBLE EN DPTO. BERMEJO "FABRICA DE ALMIDON DE MANDIOCA" | current text only, as of 21 June 2018 |
| `ley-1609-a/` | Ley 1609-A: NUEVA ESCALA SALARIAL AUTORIDADES SUPERIORES DEL PODER EJECUTIVO | as enacted, in force 21 December 2007 |
| `ley-1608-a/` | Ley 1608-A: BONIFICACION POR TITULO  UNIVERSITARIO 25% PERSONAL TRIBUNAL DE CUENTAS | as enacted, in force 21 December 2007 |
| `ley-1598-f/` | Ley 1598-F: CONVENIO DE PRESTAMO SUBSIDIARIO CON LA NACION POR U$S 50.000.000,- | as enacted, in force 21 December 2007 |
| `ley-1602-g/` | Ley 1602-G: CREA DEPARTAMENTO DE ESTERILIZACIONES CANINAS Y FELINAS | as enacted, in force 4 January 2008 |
| `ley-1605-a/` | Ley 1605-A: EXPROPIA INMUEBLE EN RESISTENCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 4 January 2008 |
| `ley-1604-a/` | Ley 1604-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | current text only, as of 19 June 2018 |
| `ley-1603-a/` | Ley 1603-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 4 January 2008 |
| `ley-1607-a/` | Ley 1607-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | current text only, as of 21 June 2018 |
| `ley-1597-a/` | Ley 1597-A: FONDO PCIAL. SUBSIDIARIO DE TARIFAS DE ELECTRIFICACION RURAL (FoProSTER) | as enacted, in force 21 December 2007 |
| `ley-1601-m/` | Ley 1601-M: NORMAS APLICABLES EN MEDIACION EN LA PCIA. DEL CHACO. DEROGA L.4498 | as enacted, in force 8 June 2008 |
| `ley-1606-a/` | Ley 1606-A: EXPROPIA INMUEBLES EN S.PEÑA PARA ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 4 January 2008 |
| `ley-1596-h/` | Ley 1596-H: COMPUTO DE APORTES Y CONTRIBUC. PREVISION. NO APORTADO PERS. CONTRATADO | as enacted, in force 21 December 2007 |
| `ley-1592-g/` | Ley 1592-G: PROGRAMA DE PREVENCION Y CONTROL DE TRASTORNOS ALIMENTARIOS | as enacted, in force 2 December 2007 |
| `ley-1591-g/` | Ley 1591-G: ADHESION L.N.26.279 - DETECCION Y TRATAMIENTO PATOLOGIAS EN EL RECIEN NACIDO | as enacted, in force 2 December 2007 |
| `ley-1589-g/` | Ley 1589-G: CREA EL PROGRAMA DE ZOOTERAPIA P/ PERSONAS CON CAPACIDAD DIFERENTE | as enacted, in force 2 December 2007 |
| `ley-1593-g/` | Ley 1593-G: CIRUGIA REPARADORA P/ MUJERES PRATICADO MASTECTOMIA PATOLOG. ONCOLOGICA | as enacted, in force 2 December 2007 |
| `ley-1590-e/` | Ley 1590-E: ESTABLECE NORMAS PARA EL USO DE JUEGOS INFANTILES MANUALES | as enacted, in force 9 December 2007 |
| `ley-1594-g/` | Ley 1594-G: PROGRAMA INTEGRAL PCIAL. PARA LA ASISTENCIA A LA OBESIDAD | as enacted, in force 2 December 2007 |
| `ley-1588-a/` | Ley 1588-A: BONIFICACION POR INCOMPATIBILIDAD PARCIAL DE TITULOS  PROFESION. Y TECNICOS | as enacted, in force 2 December 2007 |
| `ley-1587-a/` | Ley 1587-A: ESCALA SALARIAL P/ FUNCIONARIOS Y EMPLEADOS CONTADURIA GRAL. Y TESORERIA | as enacted, in force 7 December 2007 |
| `ley-1586-a/` | Ley 1586-A: ASIGNACIÓN REMUNERATIVA POR "INCOMPATIBILIDAD TOTAL" P/ ESCRIBANO GRAL.GOB | as enacted, in force 2 December 2007 |
| `ley-1585-h/` | Ley 1585-H: LAS CONTRIBUCIONES PATRONALES POR LAS LEYES 1369-H Y 1370-H  ABONARA EL P. EJEC. | as enacted, in force 2 December 2007 |
| `ley-1583-a/` | Ley 1583-A: REESTRUCTURACION DE CARGOS ESCALAFON GENERAL - LEY 196-A | as enacted, in force 2 December 2007 |
| `ley-1582-a/` | Ley 1582-A: SUPLEMENTO POR FUNCION DIRECTORES Y JEFES DPTO. ESCALAFON LEY 196-A | as enacted, in force 25 November 2007 |
| `ley-1579-h/` | Ley 1579-H: DOCENTES PODRAN OPTAR POR INCORPORARSE AL REGIMEN PREVISIONAL PCIAL. | as enacted, in force 25 November 2007 |
| `ley-1578-a/` | Ley 1578-A: EXPROPIA INMUEBLE COLONIA PASTORIL TEUCO PARA POBLADORES NO ABORIGENES (HERMANOS ROSEO) | as enacted, in force 28 November 2007 |
| `ley-1577-a/` | Ley 1577-A: CÓMPUTO JUBILATORIO EX-AGENTES DE PLANTA PERMANENTE ALCANCES DE LA LEY 1218-A. | as enacted, in force 7 October 2007 |
| `ley-1576-a/` | Ley 1576-A: CREA DENTRO DE LA ESTRUCTURA DE LOTERIA CHAQUEÑA, REGISTRO NOTARIAL ESPECIAL | as enacted, in force 5 September 2008 |
| `ley-1575-e/` | Ley 1575-E: PROGRAMA PCIAL. DE PREVENC. Y DISMINUCIÓN DE LA VIOLENCIA C/ NIÑOS, ADOLESC. Y JÓVENES | as enacted, in force 5 October 2007 |
| `ley-1574-f/` | Ley 1574-F: DECLARA EXENTA DE PAGO IMPUESTOS INGRESOS BRUTOS,  SELLOS, ETC. EN EL MARCO LEY 1521-F | as enacted, in force 5 October 2007 |
| `ley-1573-j/` | Ley 1573-J: ADHESIÓN L.N. 26.216 - ARMAS Y EXPLOSIVOS. | as enacted, in force 20 September 2007 |
| `ley-1572-a/` | Ley 1572-A: CREA REGISTRO PROVINCIAL DE RECUPERO DE BIENES EXTRAVIADOS. | as enacted, in force 28 September 2007 |
| `ley-1570-h/` | Ley 1570-H: RÉGIMEN PREVISIONAL ESPECIAL P/ SOLDADOS EX-COMBATIENTES DE LA ADMINIST. PÚBLICA. | as enacted, in force 5 October 2007 |
| `ley-1569-e/` | Ley 1569-E: ADHESIÓN L.N. 25.787 - INSTITUYE EL 29 DE JULIO COMO EL "DÍA DE LOS VALORES HUMANOS" | as enacted, in force 22 August 2007 |
| `ley-1568-e/` | Ley 1568-E: ADHESIÓN L.N. 26.125 -DECLARACIÓN DE HÉROE NACIONAL A DON MARTÍN MIGUEL DE GÜEMES. | as enacted, in force 15 August 2007 |
| `ley-1567-e/` | Ley 1567-E: ADHESIÓN L.N. 25.448 - DECLARA EL 4 DE JULIO "DÍA DEL MÉDICO RURAL" | as enacted, in force 3 August 2007 |
| `ley-1566-e/` | Ley 1566-E: PROGRAMA DE ACOMPAÑAMIENTO PERSONALIZADO P/EDUCANDOS c/DIFICULTAD DE APRENDIZAJE | as enacted, in force 25 May 2008 |
| `ley-1564-a/` | Ley 1564-A: EXPROPIA INMUEBLE EN RCIA. P/SER ADJUDICADA EN VENTA A ACTUALES OCUPANTES- | as enacted, in force 1 August 2007 |
| `ley-1563-a/` | Ley 1563-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES. | as enacted, in force 1 August 2007 |
| `ley-1565-b/` | Ley 1565-B: ADHESIÓN L.N. 25.932 - APRUEBA  PROTOCOLO CONVENC.C/LA  TORTURA O PENAS CRUELES, INHUM. | as enacted, in force 1 August 2007 |
| `ley-1559-x/` | Ley 1559-X: RATIFICA ACTA COMPLEMENTARIA DE RECONOCIMIENTO DE DEUDA. | as enacted, in force 11 July 2007 |
| `ley-1562-a/` | Ley 1562-A: EXPROPIA INMUEBLE EN RCIA. PARA VENTA A ACTUALES OCUPANTES | current text only, as of 25 October 2019 |
| `ley-1561-a/` | Ley 1561-A: EXPROPIA INMUEBLES EN RESISTENCIA P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 1 August 2007 |
| `ley-1560-a/` | Ley 1560-A: EXPROPIA INMUEBLES EN LA LOCALIDAD DE FONTANA P/ ADJUDICAR EN VENTA A SUS OCUPANTES | as enacted, in force 1 August 2007 |
| `ley-1558-j/` | Ley 1558-J: ADHIERESE LA PCIA. DEL CHACO AL DECRETO LEY NACIONAL 17160/43. | as enacted, in force 25 July 2007 |
| `ley-1557-j/` | Ley 1557-J: ADHESIÓN L.N. 25.367 - SISTEMA DE EMERGENCIAS CORDINADAS T.E. *911 - | as enacted, in force 25 July 2007 |
| `ley-1554-a/` | Ley 1554-A: RATIFICA DECRETO Nº 696/07. | as enacted, in force 4 July 2007 |
| `ley-1552-c/` | Ley 1552-C: PROHÍBE EN LA PCIA. LA INSTALACIÓN DE CAJEROS AUTOMÁTICOS EN CASINOS, SALAS DE BINGO, ETC. | as enacted, in force 4 July 2007 |
| `ley-1551-e/` | Ley 1551-E: INSTITÚYE EL 25 DE NOVIEMBRE EL "DÍA DE LA LIBERTAD DE RELIGIÓN Y CONVICCIÓN" | as enacted, in force 4 July 2007 |
| `ley-1553-a/` | Ley 1553-A: ASÍGNASE EL CARÁCTER DE LETRADO AL JUZGADO DE PAZ DE PRES. ROQUE SAENZ PEÑA. | as enacted, in force 4 July 2007 |
| `ley-1549-a/` | Ley 1549-A: EXPROPIA INMUEBLE EN FONTANA PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 11 July 2007 |
| `ley-1548-a/` | Ley 1548-A: INCREMENTO DE 25% S/ASIGNACION ESPECIAL "INCOMPATIBILIDAD PARCIAL" s/Ley 5660 | as enacted, in force 13 June 2007 |
| `ley-1547-a/` | Ley 1547-A: EXPROPIA INMUEBLE EN QUITILIPI P/ LA CONSTRUCCIÓN COMPLEJO EDUCATIVO, CULTURAL Y DEPORTIVO | as enacted, in force 20 June 2007 |
| `ley-1545-k/` | Ley 1545-K: El IPDUV INCLUIRÁ EN TODOS LOS PLANES HABITACIONALES, EL ARBOLADO TOTAL DE LOS MISMOS. | as enacted, in force 20 June 2007 |
| `ley-1546-d/` | Ley 1546-D: CONSTITUYE UNA SOCIEDAD ANON. QUE SE DENOMINARÁ LABORATORIOS CHAQUEÑOS S.A. | as enacted, in force 20 June 2007 |
| `ley-1543-e/` | Ley 1543-E: ADHESIÓN L.N. 26.157 - DECLARA A RESISTENCIA "CAPITAL NACIONAL DE LAS ESCULTURAS" | as enacted, in force 13 June 2007 |
| `ley-1542-m/` | Ley 1542-M: CREA JUZGADOS EN LA CIUDAD DE RESISTENCIA | as enacted, in force 13 June 2007 |
| `ley-1538-r/` | Ley 1538-R: DECLARA MONUMENTO NATURAL PCIAL. AL TAPIR (TAPIRUS TERRESTRIS) ESPECIE EN EXTINCIÓN. | as enacted, in force 6 June 2007 |
| `ley-1541-a/` | Ley 1541-A: ENCOMIENDA CREAR UNIDAD ADMINISTRATIVA P/INFORMACION BIOMEDICA | as enacted, in force 26 October 2007 |
| `ley-1540-e/` | Ley 1540-E: OBLIGATORIEDAD DE INSTALACION SISTEMA DE ARO MAGNETICO P/HIPOACÚSICOS | as enacted, in force 3 August 2007 |
| `ley-1539-e/` | Ley 1539-E: ADHESIÓN L.N. 25.431  - DÍA INTERNACIONAL DE LA MUJER RURAL. | as enacted, in force 6 June 2007 |
| `ley-1537-x/` | Ley 1537-X: RATIFICA CONVENIO DE ASISTENCIA FINANCIERA | as enacted, in force 16 May 2007 |
| `ley-1536-e/` | Ley 1536-E: ADHESIÓN L. N.  26.199 - CONMEMORACIONES- GENOCIDIO - ARMENIA. | as enacted, in force 23 May 2007 |
| `ley-1535-e/` | Ley 1535-E: ESTABLECE OBLIGATORIEDAD ENSEÑANZA EDUCACIÓN VIAL EN TODOS LOS NIVELES EDUCATIVOS. | as enacted, in force 13 May 2007 |
| `ley-1534-b/` | Ley 1534-B: PROGRAMA INTEGRAL P/ LA PREVENC. Y DETECCIÓN TEMPRANA DEL ABUSO SEXUAL Y MALTR.INFAN. | as enacted, in force 11 May 2007 |
| `ley-1533-e/` | Ley 1533-E: DECLARA PARIMONIO CULTURAL Y NATURAL DE LA PCIA. AL INMUEBLE DENOMINADO "DURMITOR" | as enacted, in force 11 May 2007 |
| `ley-1532-i/` | Ley 1532-I: ADHESIÓN L.N. 26.141 - RECUPERACIÓN, FOMENTO Y DESARROLLO DE LA ACTIVIDAD CAPRINA. | as enacted, in force 11 May 2007 |
| `ley-1519-a/` | Ley 1519-A: CREA CÁMARA DE APELACIONES EN LO CIVIL, COMERCIAL Y DEL TRABAJO CON ASIENTO EN CHARATA. | as enacted, in force 23 February 2007 |
| `ley-1518-a/` | Ley 1518-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 18 February 2007 |
| `ley-1517-a/` | Ley 1517-A: EXPROPIA INMUEBLES EN BQUERAS. P/"CORRIMIENTO DEFENSA AV. SAN MARTÍN- I Etapa" | as enacted, in force 18 February 2007 |
| `ley-1523-a/` | Ley 1523-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES. | as enacted, in force 25 February 2007 |
| `ley-1525-e/` | Ley 1525-E: CREA EL PROGRAMA "CHACO PARA LATINOAMERICA" | as enacted, in force 28 February 2007 |
| `ley-1526-a/` | Ley 1526-A: CREA JUZGADO DE PAZ EN LA LOCALIDAD DE COLONIA POPULAR. | as enacted, in force 28 February 2007 |
| `ley-1527-a/` | Ley 1527-A: CREA JUZGADO DE PAZ EN LA LOCALIDAD DE PUERTO EVA PERÓN. | as enacted, in force 28 February 2007 |
| `ley-1522-a/` | Ley 1522-A: EXPROPIA INMUEBLE EN CHARATA PARA FUNCIONAMIENTO PODER JUDICIAL. | as enacted, in force 9 February 2007 |
| `ley-1521-f/` | Ley 1521-F: ADHESIÓN L.N. 26.117 - PROMOCIÓN DE MICROCRÉDITO P/EL DESARROLLO DE LA ECONOMÍA SOCIAL | as enacted, in force 9 February 2007 |
| `ley-1520-e/` | Ley 1520-E: INSTÁURASE EL 15 DE OCTUBRE COMO EL "DÍA PROVINCIAL DE LAS COOPERATIVAS ESCOLARES" | as enacted, in force 9 February 2007 |
| `ley-1515-v/` | Ley 1515-V: INSTITÚYESE EL "PREMIO A LA ACTIVIDAD TURÍSTICA" EN LA PROVINCIA DEL CHACO. | as enacted, in force 4 February 2007 |
| `ley-1512-e/` | Ley 1512-E: ADHESIÓN L.N.Nº 25.346 - 3 DE DICIEMBRE DÍA NACIONAL DE LAS PERS. C/DISCAPACIDAD. | as enacted, in force 31 December 2006 |
| `ley-1510-a/` | Ley 1510-A: EXPROPIA INMUEBLE EN QUITILIPI PARA TRANSFERIR AL MUNICIPIO LOCAL PARA CENTRO CULTURAL. | as enacted, in force 31 December 2006 |
| `ley-1509-a/` | Ley 1509-A: ASÍGNASE CARÁCTER DE LETRADO JUZG. DE PAZ Y FALTAS MACHAGAY,QUITILIPI,PINEDO Y L.BREÑAS | as enacted, in force 31 December 2006 |
| `ley-1508-x/` | Ley 1508-X: RATIFICA CONVENIO DE COORDIN. Y COOPER. TECNICA, RED FED. DE CONTR. PUB. Y T.CUENTAS | as enacted, in force 24 December 2006 |
| `ley-1507-g/` | Ley 1507-G: ADHIERE L.N.24.151 - OBLIGATORIEDAD VACUNACIÓN HEPATITIS "B" TRABAJADORES DE LA SALÚD. | as enacted, in force 16 May 2007 |
| `ley-1506-a/` | Ley 1506-A: CREA EL JUZGADO DEL MENOR Y LA FAMILIA EN JUÁN JOSÉ CASTELLI. | as enacted, in force 10 December 2006 |
| `ley-1505-f/` | Ley 1505-F: RATIFICASE EL "ACTA DE RECONOCIMIENTO DE CREDITO A FAVOR DE LA PROVINCIA" | as enacted, in force 10 December 2006 |
| `ley-1504-a/` | Ley 1504-A: CREA JUZGADOS DE FALTAS EN CHARATA, JUÁN JOSÉ CASTELLI Y BARRANQUERAS. | as enacted, in force 10 December 2006 |
| `ley-1503-a/` | Ley 1503-A: CREA EL REGISTRO PROVINCIAL DE INFORMACIÓN DE PERSONAS MENORES EXTRAVIADAS. | as enacted, in force 10 December 2006 |
| `ley-1501-e/` | Ley 1501-E: ADHESIÓN L.N. 24.806 - NORMAS PARA LA PUBLICIDAD DE LA ENSEÑANZA PRIVADA. | as enacted, in force 10 December 2006 |
| `ley-1500-a/` | Ley 1500-A: CREA DENTRO DE LA POLICIA UNA DIVISION QUE FUNCIONARÁ COMO"ATENCIÓN DE LA MUJER" | as enacted, in force 13 December 2006 |
| `ley-1499-c/` | Ley 1499-C: DECLARA INEMBARGABLE E INEJECUTABLE INMUEBLE DONDE FUNCIONE TEMPLO NO CATOLICO. | as enacted, in force 10 December 2006 |
| `ley-1498-a/` | Ley 1498-A: EXPROPIA INMUEBLES EN RCIA., PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 13 December 2006 |
| `ley-1497-a/` | Ley 1497-A: EXPROPIA INMUEBLES EN RCIA.,  PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 10 December 2006 |
| `ley-1495-c/` | Ley 1495-C: ESTABLECE REGIMEN PARA EL EJERCICIO DE CORREDOR INMOBILIARIO | as enacted, in force 13 December 2006 |
| `ley-1494-a/` | Ley 1494-A: CREANSE DELEGACIONES DEL CENTRO PUBLICO DE MEDIACION EN CIUDADES CABECERAS CIRC. JUD. | as enacted, in force 29 November 2006 |
| `ley-1490-a/` | Ley 1490-A: CREA CAMARA DE APELACIONES EN LO CIVIL, COMERCIAL Y DEL TRABAJO EN VILLA ANGELA | as enacted, in force 29 November 2006 |
| `ley-1491-a/` | Ley 1491-A: CREA LA CAMARA DE APELACIONES C/COMPETENCIA UNIVERSAL CON ASIENTO EN J.J. CASTELLI. | as enacted, in force 29 November 2006 |
| `ley-2022-k/` | Ley 2022-K: REGISTRO ÚNICO DE BENEFICIARIOS DEL HABITAT (RUBH) | as enacted, in force 3 August 2012 |
| `ley-1487-g/` | Ley 1487-G: ADHIERE LA PROVINCIA DEL CHACO A LA LEY Nº 25.404 | as enacted, in force 27 October 2006 |
| `ley-1484-w/` | Ley 1484-W: DECLARA PATRIMONIO CULTURAL VIVIENTE AL CONJUNTO CORAL TOBA "CHELAALAPI" DEROGA L.3322 | as enacted, in force 15 October 2006 |
| `ley-1483-e/` | Ley 1483-E: EMPLAZAMIENTO MURAL EN RCIA., QUE SE DENOMINARA "MURAL DE LA CULTURA" | as enacted, in force 6 October 2006 |
| `ley-1482-a/` | Ley 1482-A: EXPROPIA INMUEBLE EN RCIA. A FAVOR DE LA MUNICIPALIDAD DE RCIA. | as enacted, in force 27 September 2006 |
| `ley-1480-a/` | Ley 1480-A: EXPROPIA INMUEBLES EN BQUERAS. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 22 September 2006 |
| `ley-1479-a/` | Ley 1479-A: EXPROPIA INMUEBLE EN FONTANA PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 22 September 2006 |
| `ley-1481-l/` | Ley 1481-L: DIA NO LABORABLE P/CADA LOCALIDAD EN FECHA DE CONMEMORAR SU ANIVERSARIO | as enacted, in force 22 September 2006 |
| `ley-1478-a/` | Ley 1478-A: EXPROPIA DERECHOS ADQUIRIDOS HERMANOS GUALTIERI SOBRE INMUEBLES EN DEPARTAMENTO ALMIRANTE BROWN | as enacted, in force 1 September 2006 |
| `ley-1477-x/` | Ley 1477-X: CONVENIO PARTICIPACION PROGRAMA FORTALECIMIENTO INSTITUCIONAL PRODUCT. Y DE GEST. FISCAL | as enacted, in force 13 September 2006 |
| `ley-1475-x/` | Ley 1475-X: RATIFICA CONVENIO DE REFINANCIACION DE INTERESES CON EL ESTADO PROVINCIAL | as enacted, in force 1 September 2006 |
| `ley-1476-a/` | Ley 1476-A: LICENCIA POR MATERNIDAD PARA EL AGENTE VARON POR FALLECIMIENTO DE CONYUGE | as enacted, in force 8 September 2006 |
| `ley-1473-e/` | Ley 1473-E: INSTITUYE EL 6 DE JULIO DE CADA AÑO "DIA DEL TRABAJADOR LEGISLATIVO" | as enacted, in force 20 August 2006 |
| `ley-1472-j/` | Ley 1472-J: CREA PROGRAMA DE BRIGADAS MUNICIPALES DE EDUCACION Y SEGURIDAD VIAL | as enacted, in force 20 August 2006 |
| `ley-1466-e/` | Ley 1466-E: DECLARA EL 20 DE SEPTIEMBRE DE CADA AÑO. "DÍA DEL DIÁLOGO ECUMÉNICO E INTERRELIGIOSO" EN EL MARCO DEL DÍA INTERNACIONAL DE LA PAZ | as enacted, in force 4 August 2006 |
| `ley-1465-x/` | Ley 1465-X: CONVENIO DE ASISTENCIA FINANCIERA. MODIFICA ART.3 DEL ANEXO LEY 1416-X (ANTES LEY 5594). | as enacted, in force 26 July 2006 |
| `ley-1463-a/` | Ley 1463-A: CREA JUZGADO DE PAZ DE 3RA. CATEGORIA EN LA LOCALIDAD DE LAPACHITO | as enacted, in force 26 July 2006 |
| `ley-1460-f/` | Ley 1460-F: RATIFICA DTO. 678/06 P.E. - ADHIERE D.N.1382/05 | as enacted, in force 25 June 2006 |
| `ley-1457-h/` | Ley 1457-H: GRATUIDAD P/TRAMITAC.PROCED.JUDICIALES P/RECLAMOS LABORALES O PREVIS. | as enacted, in force 25 June 2006 |
| `ley-1456-a/` | Ley 1456-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 11 June 2006 |
| `ley-1452-c/` | Ley 1452-C: DECLARA DE INTERES SOCIAL Y LA INEMBARGABILIDAD  E INEJECUT. BIENES CLUBES DEPORT. | as enacted, in force 28 May 2006 |
| `ley-1448-e/` | Ley 1448-E: ADHESION L.N.26.001 -DIA NACIONAL DEL DERECHO A LA IDENTIDAD- | as enacted, in force 11 June 2006 |
| `ley-1447-i/` | Ley 1447-I: ADHESION L.N. Nº 26.060 -PLAN DE DESARROLLO SUST.Y FOM.PRODUCC.ALGOD.- | as enacted, in force 24 May 2006 |
| `ley-1446-f/` | Ley 1446-F: CREA EL "FIDEICOMISO PARA LA CONSTRUCCION DEL EDIFICIO LEGISLATIVO" | as enacted, in force 7 May 2006 |
| `ley-1441-p/` | Ley 1441-P: ADQUISICION BANDERAS Y COFRES P/FAMILIARES EX-COMBATIENTES FALLECIDOS | as enacted, in force 17 May 2006 |
| `ley-1443-x/` | Ley 1443-X: CONVENIO COMPL. AL CONVENIO DEL PROGRAMA DE FINANC.ORDENADO Y RATIFIC. | as enacted, in force 28 April 2006 |
| `ley-1442-x/` | Ley 1442-X: CONVENIO DE CONVERSION DE DEUDA PUBLICA EN BONOS GARANTIZADOS | as enacted, in force 28 April 2006 |
| `ley-1439-b/` | Ley 1439-B: PLAN DE IGUALDAD REAL DE OPORTUNIDADES Y TRATO ENTRE MUJERES Y VARONES | as enacted, in force 28 April 2006 |
| `ley-1432-a/` | Ley 1432-A: EXPROPIA INMUEBLE EN RCIA. P/ SER DESTINADO A LA ESCUELA ESPEC. N.2 | as enacted, in force 26 February 2006 |
| `ley-1433-i/` | Ley 1433-I: FACULTA A LOS MUNICIPIOS A DISPONER DEL GANADO ASNAL OREJANO | as enacted, in force 19 February 2006 |
| `ley-1438-a/` | Ley 1438-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 26 February 2006 |
| `ley-1437-a/` | Ley 1437-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A SUS OCUPANTES | as enacted, in force 19 February 2006 |
| `ley-1435-a/` | Ley 1435-A: ASIGNACION REMUN.ESPECIAL P/PERSONAL DE ASESORIA GRAL. DE GOBIERNO | as enacted, in force 26 February 2006 |
| `ley-1434-a/` | Ley 1434-A: CREA CINCO (5) JUZGADOS DE EJECUCIÓN PENAL EN LA PRIMERA, TERCERA, CUARTA, QUINTA Y SEXTA CIRCUNSCRIPCIÓN Y UN (1) JUZGADO DE GARANTÍA EN LA SEXTA C… | as enacted, in force 19 February 2006 |
| `ley-1430-h/` | Ley 1430-H: RATIFICA DTO.2574/05 -AGENTES REINCORP. COBERTURA POR ACCIDENTE DE TRABAJO. | as enacted, in force 28 December 2005 |
| `ley-1428-r/` | Ley 1428-R: MANEJO DE LOS RECURSOS ACUICOLAS Y PESCA - DEROGA L.635 | as enacted, in force 3 March 2006 |
| `ley-1427-v/` | Ley 1427-V: INCORPORA CIRCUITO TURISTICO, RUINAS PRIMERA CIUDAD ESPAÑOLA EN CHACO | as enacted, in force 6 January 2006 |
| `ley-1425-e/` | Ley 1425-E: DECLARA EL 1 DE AGOSTO "DIA DE LA POESIA CHAQUEÑA" | as enacted, in force 28 December 2005 |
| `ley-1424-f/` | Ley 1424-F: RATIFICA ACTA DE RECONOCIMIENTO CREDITO A FAVOR DE LA PROVINCIA | current text only, as of 13 July 2018 |
| `ley-1436-e/` | Ley 1436-E: INSTITUIR EL 15 DE DICIEMBRE COMO "DIA DEL RETIRADO CON BOCEP" | as enacted, in force 19 February 2006 |
| `ley-1423-e/` | Ley 1423-E: INCORPORA AL CALENDARIO ESCOLAR COMO "DIA DE LA MASACRE DE NAPALPI" | as enacted, in force 6 November 2005 |
| `ley-1422-g/` | Ley 1422-G: NORMAS SOBRE TATUAJES EN LA PIEL, PERFORACIONES, INCISIONES, ETC. | as enacted, in force 27 November 2005 |
| `ley-1420-a/` | Ley 1420-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 14 October 2005 |
| `ley-1419-c/` | Ley 1419-C: IMPLEMENTA SISTEMA DE COBRO CUOTAS ALIMENTARIAS C/ TARJETAS MAGNETICAS | as enacted, in force 14 October 2005 |
| `ley-1418-e/` | Ley 1418-E: INSTITUYE EL 19 DE SEPTIEMBRE COMO DIA PROVINCIAL DE LA PERSONA SORDA | as enacted, in force 9 October 2005 |
| `ley-1417-f/` | Ley 1417-F: MODIFICA ARTS. 67 Y 68 LEY 1118- (PANTES LEY 4851) - DEROGA ART.22 CAPITULO III LEY 299-F (ANTES LEY 2071) | as enacted, in force 9 October 2005 |
| `ley-1416-x/` | Ley 1416-X: RATIFICA CONVENIO DE ASISTENCIA FINANCIERA | as enacted, in force 14 September 2005 |
| `ley-1415-f/` | Ley 1415-F: ADHIERE L.N.25.973 - REGIMEN DE INEMBARGABILIDAD | as enacted, in force 14 September 2005 |
| `ley-1414-c/` | Ley 1414-C: CREA REGISTRO PUBLICO DE ADMINISTR. DE CONSOR. DE PROPIEDAD HORIZONTAL | as enacted, in force 2 September 2005 |
| `ley-1413-i/` | Ley 1413-I: DECLARA DE INTERES SOCIAL, ECONOMICO, AMBIENTAL Y ESTRAT. AL ALGARROBO | as enacted, in force 26 August 2005 |
| `ley-1412-a/` | Ley 1412-A: CREA COMISION PCIAL. POR LA MEMORIA Y REGISTRO UNICO DE LA VERDAD | as enacted, in force 26 August 2005 |
| `ley-1410-a/` | Ley 1410-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 7 August 2005 |
| `ley-1409-l/` | Ley 1409-L: ADHESION L.N.25.255 - PROHIBICION PEORES FORMA DE TRABAJO INFANTIL. | as enacted, in force 3 August 2005 |
| `ley-1408-e/` | Ley 1408-E: INSTITUYE EL 8 DE SEPT.COMO DIA DE LA FUNDACION DE LA ISLA DEL CERRITO | as enacted, in force 17 July 2005 |
| `ley-1407-w/` | Ley 1407-W: ADHESION L.N.25.607 - DERECHOS DE LOS PUEBLOS INDIGENAS | as enacted, in force 17 July 2005 |
| `ley-1405-i/` | Ley 1405-I: ADHESION L.N.25.922 -PROMOCION DE LA INDUSTRIA DEL SOFTWARE | as enacted, in force 15 July 2005 |
| `ley-1406-d/` | Ley 1406-D: AGENCIA DE PROM. DE INVERS. E INTERCAMBIO CHACO S.A. (APIICHACO S.A.) | as enacted, in force 15 July 2005 |
| `ley-1403-d/` | Ley 1403-D: ADHESION L.N.25.954 -DEVOLUC. AL CONSUMIDOR DIFERENCIAS MENORES 5 CTVS | as enacted, in force 8 July 2005 |
| `ley-1402-e/` | Ley 1402-E: INSTITUYE EL 30 DE AGOSTO COMO "DIA DE LA CULTURA CHAQUEÑA" | as enacted, in force 8 July 2005 |
| `ley-1400-e/` | Ley 1400-E: PATRIMONIO HISTORICO CULTURAL Y NATURAL | as enacted, in force 26 June 2005 |
| `ley-1399-a/` | Ley 1399-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 22 June 2005 |
| `ley-1397-a/` | Ley 1397-A: EXPROPIA MUEBLES P/COOPERATIVA DE TRABAJO Y CONSUMO LA PRENSA LTDA. | as enacted, in force 15 June 2005 |
| `ley-1398-f/` | Ley 1398-F: PERS. FISICAS O JURID.,QUE ALMACENEN DATOS DEBEN INSCRIBIRSE EN RENTAS | as enacted, in force 15 June 2005 |
| `ley-1395-v/` | Ley 1395-V: IMPLEMENTA EN LA PCIA. CENTROS DE INFORMACION TURISTICA (C.I.T.) | as enacted, in force 18 May 2005 |
| `ley-1394-i/` | Ley 1394-I: ESTABLECE POR 365 DIAS EMERGENCIA AGROPECUARIA S/DTOS.450 Y 569/05 PE. | as enacted, in force 15 June 2005 |
| `ley-1393-a/` | Ley 1393-A: CREA JUZGADO DE PAZ DE TERCERA CATEGORIA EN LAGUNA BLANCA | as enacted, in force 15 May 2005 |
| `ley-1392-e/` | Ley 1392-E: ADHESION AL D.N.. 1406/98 -DIA DEL NIÑO POR NACER- | as enacted, in force 15 May 2005 |
| `ley-1390-a/` | Ley 1390-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 15 May 2005 |
| `ley-1389-k/` | Ley 1389-K: REGISTRO DE CONSTRUCTORES DE OBRAS Y PREST. DE SERV. PUBL. DE LA PCIA. | as enacted, in force 15 May 2005 |
| `ley-1388-m/` | Ley 1388-M: SUSPENDE HASTA 31/12/05 TRAMITE PROCESOS DE EJECUCIONES HIPOTECARIAS | as enacted, in force 1 May 2005 |
| `ley-1387-e/` | Ley 1387-E: DECLARA PATRIMONIO CULTURAL DE LA PCIA. A LA PEÑA NATIVA MARTIN FIERRO | as enacted, in force 15 April 2005 |
| `ley-1386-a/` | Ley 1386-A: CREA JUZGADO DE PAZ DE 3RA. CATEGORIA EN NAPENAY | as enacted, in force 1 May 2005 |
| `ley-1385-e/` | Ley 1385-E: DECLARA "FLOR PROVINCIAL DEL CHACO" A LA FLOR ROSADA DEL "PALO BORRACHO" | as enacted, in force 1 May 2005 |
| `ley-1383-j/` | Ley 1383-J: ADHESION PCIAL. ARTS.1, 2 Y 3 L.N.25.938 -REG. NAC. DE ARMAS DE FUEGO- | as enacted, in force 24 April 2005 |
| `ley-1382-v/` | Ley 1382-V: ADHIERE LA PCIA. L.N.25.997 -LEY NACIONAL DE TURISMO- | as enacted, in force 24 April 2005 |
| `ley-1381-g/` | Ley 1381-G: ESTABLECE EL DERECHO DE LA MUJER A ESTAR ACOMPAÑADA DURANTE EL PARTO | as enacted, in force 13 April 2005 |
| `ley-1380-e/` | Ley 1380-E: ESTABLECE EL 21 DE MARZO COMO DIA DEL CRONISTA DE EXTERIORES | as enacted, in force 15 April 2005 |
| `ley-1379-e/` | Ley 1379-E: INSTITUYE EL 18 DE MARZO COMO EL DIA DE LA FUNDACION DE TACO POZO | as enacted, in force 15 April 2005 |
| `ley-1372-i/` | Ley 1372-I: REGULA ACTIVIDAD CUNICOLA EN LA PCIA.- ADHESION L.N.23.634 - | as enacted, in force 16 January 2005 |
| `ley-1375-a/` | Ley 1375-A: CREA REGISTRO UNICO PERSONAL DE ASISTENCIA Y CUIDADO DE MENORES | as enacted, in force 16 January 2005 |
| `ley-1373-d/` | Ley 1373-D: PROHIBE FABRICACION DE JUGUETES QUE SEAN REPLICAS DE ARMAS DE FUEGO | as enacted, in force 16 January 2005 |
| `ley-1371-g/` | Ley 1371-G: 6 DE ABRIL DIA DE LAS ACCIONES RELACIONADAS AL FACTOR RH NEGATIVO | as enacted, in force 16 January 2005 |
| `ley-1366-a/` | Ley 1366-A: RATIFICA DECRETO PROVINCIAL N.1956/2000 | as enacted, in force 14 January 2005 |
| `ley-1360-a/` | Ley 1360-A: CREA REGISTRO UNICO PCIAL. DE INHABILITACION PARA CONDUCIR | as enacted, in force 9 January 2005 |
| `ley-1358-i/` | Ley 1358-I: ADHESION L.N.25.761 - DESARMADERO AUTOMOTORES Y VENTAS AUTOPARTES- | as enacted, in force 29 December 2004 |
| `ley-1357-r/` | Ley 1357-R: DECLARA PARQUE NATURAL PCIAL. LORO HABLADOR DEPTO. GRAL. GUEMES | as enacted, in force 22 December 2004 |
| `ley-1355-e/` | Ley 1355-E: INSTITUYE EL 4/12 COMO DIA DE LA FUNDACION LOCALIDAD DE CAP. SOLARI | as enacted, in force 22 December 2004 |
| `ley-1354-a/` | Ley 1354-A: APRUEBA ESTRUCTURA DE CARGOS JURISDICCION 08 -TRIBUNAL DE CUENTAS- | as enacted, in force 22 December 2004 |
| `ley-1353-e/` | Ley 1353-E: FOMENTO ACTIVIDAD PRIVADA EN ACTIVIDADES CULTURALES (MECENAZGO) | as enacted, in force 22 December 2004 |
| `ley-1350-a/` | Ley 1350-A: ESTABLECE DERECHOS APLICACION REINCORPORAC. AGENTES PRESCIND. ADM.PCA. | current text only, as of 4 October 2019 |
| `ley-1348-i/` | Ley 1348-I: INCORPORA COMO ACTIVIDAD PRODUCTIVA INDUSTR. DISEÑO Y ELAB. DE SOFTWARE | as enacted, in force 7 November 2004 |
| `ley-1346-f/` | Ley 1346-F: EL RECURSO HIDRICO SISTEMA ACUIFERO GUARANI(S.A.G.) PERTENECE AL CHACO | as enacted, in force 14 November 2004 |
| `ley-1340-g/` | Ley 1340-G: REGLAMENTA EL EJERCICIO DE LAS CIENCIAS VETERINARIAS - DEROGA L.576 | as enacted, in force 18 May 2005 |
| `ley-1341-a/` | Ley 1341-A: LEY DE ETICA Y TRANSPARENCIA EN LA FUNCION PUBLICA. | as enacted, in force 14 January 2005 |
| `ley-1336-a/` | Ley 1336-A: IMPONE NOMBRE "ESTEBAN VELEFF" A LA RUTA PCIAL. N.9 | as enacted, in force 6 August 2004 |
| `ley-1335-e/` | Ley 1335-E: INSTITUYE EL DIA 23 DE AGOSTO COMO "DIA DEL MEDIADOR" | as enacted, in force 30 July 2004 |
| `ley-1329-a/` | Ley 1329-A: CREA JUZGADO DEL MENOR DE EDAD Y LA FAMILIA EN GRAL.JOSE DE SAN MARTIN | as enacted, in force 4 July 2004 |
| `ley-1327-c/` | Ley 1327-C: EL SUP.TRIB. DE JUST.TOMARA A SU CARGO EL COSTO DE ESTUDIOS HLA.Y ADN. | as enacted, in force 16 June 2004 |
| `ley-1326-a/` | Ley 1326-A: CREA REGISTRO DE LEYES PCIALES. QUE PREVEAN ADHESION MUNICIPAL | as enacted, in force 16 June 2004 |
| `ley-1322-t/` | Ley 1322-T: ADHESION  L.N.25.857 - MOD.ART.55 (TRANSPORTE ESCOLAR) L.N.24.449 | as enacted, in force 21 May 2004 |
| `ley-1321-a/` | Ley 1321-A: CREA CAMARA EN LO CRIMINAL 2DA. CIRCUNCRIPC. JUDICIAL EN SAENZ PEÑA | as enacted, in force 21 May 2004 |
| `ley-1317-i/` | Ley 1317-I: ADHESION L.N.25.856 - INCORPORA PARRAFO INC.P) ART.128 D.L.2444/62 | as enacted, in force 14 May 2004 |
| `ley-1316-r/` | Ley 1316-R: ADHESION L.N.23.919 -PRESERVA HUMEDALES S/CONVENCION DE RAMSAR- | as enacted, in force 9 May 2004 |
| `ley-1310-g/` | Ley 1310-G: REGIMEN PARA AGENTES DE PROPAGANDA MEDICA | as enacted, in force 11 June 2004 |
| `ley-1311-a/` | Ley 1311-A: PROHIBE EN LA ADM. PCA. ACCESO POR INTERNET PAGINAS PORNOGRAF.Y JUEGOS | as enacted, in force 21 May 2004 |
| `ley-1307-a/` | Ley 1307-A: EXPROPIA INMUEBLES EN RCIA. PARA ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 18 January 2004 |
| `ley-1284-v/` | Ley 1284-V: CREA REGIMEN DE PROMOCION Y DESARROLLO DEL TURISMO SALUD | as enacted, in force 2 January 2004 |
| `ley-1289-a/` | Ley 1289-A: CREA ADMINISTRACION TRIBUTARIA DE LA PROVINCIA -ART.59 C.P. 1957-1994- | as enacted, in force 28 January 2004 |
| `ley-1283-x/` | Ley 1283-X: 2DO. CONVENIO DEUDA PUBLICA EN BONOS GARANTIZADOS C/FONDO FIDUCIARIO | as enacted, in force 5 December 2003 |
| `ley-1281-g/` | Ley 1281-G: INSTITUYE EL 9 DE NOVIEMBRE COMO "DIA DEL DONANTE SOLIDARIO DE SANGRE" | as enacted, in force 10 December 2003 |
| `ley-1280-i/` | Ley 1280-I: INSTITUYE EL FONDO DE DESARROLLO REGIONAL (FDR) | as enacted, in force 2 November 2003 |
| `ley-1278-f/` | Ley 1278-F: EXIME A LA ASOCIACION R.E.M.A.R. CHACO, DE TODOS GRAVAMENES PCIALES. | as enacted, in force 24 October 2003 |
| `ley-1279-e/` | Ley 1279-E: INSTITUYE COMO "DIA DEL CHAMAME" EL 19 DE SEPTIEMBRE DE CADA AÑO | as enacted, in force 19 October 2003 |
| `ley-1277-e/` | Ley 1277-E: DECLARA A LAS BREÑAS SEDE PERMANENTE "FIESTA PCIAL.DE CARROZAS ESTUD." | as enacted, in force 19 October 2003 |
| `ley-1276-e/` | Ley 1276-E: DECLARA A SAENZ PEÑA SEDE CENTRAL DE LA FIESTA PCIAL. DEL ESTUDIANTE | as enacted, in force 19 October 2003 |
| `ley-1272-h/` | Ley 1272-H: EXCEPTUA APORTES Y RETENCIONES S/ASIGNACION ESPECIAL NO REMUNERATIVA | as enacted, in force 17 September 2003 |
| `ley-1271-n/` | Ley 1271-N: CREA CAMARA EN LO CRIMINAL CUARTA CIRCUNSCRIPC. JUDICIAL EN CHARATA | as enacted, in force 17 September 2003 |
| `ley-1268-b/` | Ley 1268-B: FUNCIONARIOS Y JUECES NO OBLIGADOS DE VINDICARSE -ART.74 C.P.1957-1994 | as enacted, in force 12 September 2003 |
| `ley-1269-x/` | Ley 1269-X: CONVENIO CONVERSION DEUDA PUBLICA EN BONOS GARANTIZADOS C/FONDO FIDUC. | as enacted, in force 12 September 2003 |
| `ley-1270-l/` | Ley 1270-L: ADHESION L.N.12.908 -ESTATUTO DEL PERIODISTA PROFESIONAL- | as enacted, in force 12 September 2003 |
| `ley-1267-a/` | Ley 1267-A: EXPROPIA INMUEBLE EN RCIA. P/ APERTURA PASAJE PADRE LUIS STANDO | as enacted, in force 22 August 2003 |
| `ley-1265-u/` | Ley 1265-U: ANUNCIOS S/LICITACION, REMATES  Y CONCURSOS DE PRECIOS POR INTERNET | as enacted, in force 20 August 2003 |
| `ley-1264-a/` | Ley 1264-A: ESTABLECE SITIO OFICIAL INTERNET GOBIERNO DE LA PCIA. PAGINA WEB | as enacted, in force 20 August 2003 |
| `ley-1266-x/` | Ley 1266-X: APRUEBA ADDENDA AL PROGRAMA DE UNIFICACION MONETARIA.(ART.2 L.5211) | as enacted, in force 27 July 2003 |
| `ley-1263-a/` | Ley 1263-A: CREA CAMARA EN LO CRIMINAL SEXTA CIRCUNSC. JUDICIAL EN J. J. CASTELLI | as enacted, in force 8 August 2003 |
| `ley-1262-x/` | Ley 1262-X: RATIFICA ACUERDO AMPLIATORIO CONV. PRESTAMO P/TRANSF. SECT. PUBLICOS | as enacted, in force 6 July 2003 |
| `ley-1261-e/` | Ley 1261-E: CREA MARCO NORMATIVO PARA ACUERDOS DE CONVIVENCIA EN ESTABLECIMIENTOS EDUCATIVOS | as enacted, in force 20 July 2003 |
| `ley-1259-v/` | Ley 1259-V: ADHESION  L.N.25.643 -TURISMO ACCESIBLE P/PERS. C/MOV. Y COMUN. REDUCIDA | as enacted, in force 15 June 2003 |
| `ley-1258-f/` | Ley 1258-F: ADHESION PROGRAMA DE UNIFICACION MONETARIA (RESCATE BONOS "QUEBRACHO") | as enacted, in force 21 May 2003 |
| `ley-1255-a/` | Ley 1255-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/VENTA ACTUALES OCUPANTES | as enacted, in force 23 May 2003 |
| `ley-1253-g/` | Ley 1253-G: ADHIERE L.N.25.392 - REG. NAC. DONANTES CELULAS PROGENITORAS HEMATOP.- | as enacted, in force 23 May 2003 |
| `ley-1252-a/` | Ley 1252-A: CREA JUZGADO DEL MENOR DE EDAD Y LA FAMILIA EN CHARATA | as enacted, in force 23 May 2003 |
| `ley-1250-a/` | Ley 1250-A: EXPROPIA INMUEBLES EN DPTO. COM.FERNANDEZ P/DEFENSAS CALLES 68 Y 78 | as enacted, in force 11 May 2003 |
| `ley-1249-a/` | Ley 1249-A: LAS ADJUDICACIONES POR EXPROPIACION NO PODRAN SER TRANSF. POR 10 AÑOS | as enacted, in force 11 May 2003 |
| `ley-1248-a/` | Ley 1248-A: CREA LA COMISION PROVINCIAL MULTISECTORIAL DE LA MUJER. DEROGA L.3416 | as enacted, in force 16 April 2003 |
| `ley-1247-f/` | Ley 1247-F: EL PODER EJECUTIVO.SE ABSTENDRÁ DE ABONAR SALARIOS Y PARTICIPACIÓN . MUNICIPALES. CON /BONOS | as enacted, in force 30 March 2003 |
| `ley-1246-x/` | Ley 1246-X: RATIFICA CONVENIO PRESTAMO FONDO TRANSFORM. SECTORES PUBLIC. PCIALES. | as enacted, in force 30 March 2003 |
| `ley-1245-x/` | Ley 1245-X: CONVENIO DE FINANCIAMIENTO PCIA. DEL CHACO Y ESTADO NACIONAL | as enacted, in force 30 March 2003 |
| `ley-1244-p/` | Ley 1244-P: SISTEMA PLANIFICACION Y EVALUACION DE RESULTADOS-REGIONES MUNICIPALES | as enacted, in force 22 January 2003 |
| `ley-1243-f/` | Ley 1243-F: AUTORIZA AL P.E. A OBTENER PRESTAMO POR U$S 250.000, P/MEDICAMENTOS | as enacted, in force 26 January 2003 |
| `ley-1241-a/` | Ley 1241-A: MARCO REGULATORIO DEL SISTEMA ELECTRICO PROVINCIAL | as enacted, in force 26 October 2003 |
| `ley-1239-e/` | Ley 1239-E: ESTABLECE EL FUNCIONAMIENTO DE LA "ASOCIACION COOPERADORA" EN LA PCIA. | as enacted, in force 26 January 2003 |
| `ley-1238-a/` | Ley 1238-A: EL PODER JUDICIAL CREA REGISTRO DE BIENES SECUESTRADOS Y DECOMISADOS. | as enacted, in force 26 January 2003 |
| `ley-1242-e/` | Ley 1242-E: RECONOCE LENGUA DE SEÑAS DE LAS PERSONAS SORDAS E HIPOACUSICAS | as enacted, in force 19 January 2003 |
| `ley-1240-e/` | Ley 1240-E: ADHESION  L.N.25.359 -CONVENIO DE COOPER. EDUCAT. ENTRE ARGENTINA Y CUBA | as enacted, in force 24 January 2003 |
| `ley-1235-v/` | Ley 1235-V: ESTABLECE "LA SEMANA DEL TURISMO" | as enacted, in force 19 January 2003 |
| `ley-1234-f/` | Ley 1234-F: EXCEPTUA DEL PAGO DE IMPUESTOS PROVINCIALES. A LA EMPRESA SE.FE.CHA. S .A. | as enacted, in force 8 January 2003 |
| `ley-1233-x/` | Ley 1233-X: RATIFICA COMPROMISO DE ASISTENCIA Y RECIPROCIDAD SUSCRIPTO EN SANTA FE | as enacted, in force 20 December 2002 |
| `ley-1232-a/` | Ley 1232-A: PRIORIDAD A LA U.N.N.E. Y U.T.N. P/CAPACITACIÓN DE RECURSOS HUMANOS | as enacted, in force 22 December 2002 |
| `ley-1231-e/` | Ley 1231-E: CREA CENTROS DE ESTUDIANTES EN ESTABLECIMIENTOS ESCOLARES | as enacted, in force 22 December 2002 |
| `ley-1230-c/` | Ley 1230-C: CREA EN LA PCIA. VOLUNTARIADO SOCIAL EN ENTIDADES SIN FINES DE LUCRO | as enacted, in force 22 December 2002 |
| `ley-1228-i/` | Ley 1228-I: DECLARA DE PRIORIDAD PRODUCTIVA LA PRODUCCION DE SEMILLAS DE ALGODON | as enacted, in force 8 December 2002 |
| `ley-1225-e/` | Ley 1225-E: DECLARA DE INTERES PCIAL. ACTIVIDADES CULTURALES SUBSECRET. DE CULTURA | as enacted, in force 22 November 2002 |
| `ley-1224-a/` | Ley 1224-A: ASIGNA CARACTER DE LETRADO AL JUZGADO DE FALTAS DE PRES. R. SAENZ PEÑA | as enacted, in force 10 November 2002 |
| `ley-1221-f/` | Ley 1221-F: EXIME PAGO DE IMPUESTO PCIAL. A LAS ASOCIAC. DE TALLERES PROTEGIDOS | as enacted, in force 30 October 2002 |
| `ley-1222-l/` | Ley 1222-L: REGIMEN PARA EL DESARROLLO EMPRESARIAL A TRAVES DE ORGANIZACIONES GREMIALES | as enacted, in force 30 October 2002 |
| `ley-1219-e/` | Ley 1219-E: INCORPORA PAGINA WEB DEDICADA AL CALENDARIO HISTORICO DEL CHACO | as enacted, in force 25 October 2002 |
| `ley-1218-a/` | Ley 1218-A: ADHESION L.N.24736 -RESTABLECE VIGENCIA L.N.23278- | as enacted, in force 25 October 2002 |
| `ley-1217-e/` | Ley 1217-E: CREA CENTROS DE ESTUDIOS LOCALES (C.E.L.) | as enacted, in force 25 October 2002 |
| `ley-1214-x/` | Ley 1214-X: ESTABLECE PRIORIDAD ESTRATEGICA TRATADO INTERPR. REGION NORTE GRANDE | as enacted, in force 27 September 2002 |
| `ley-1213-f/` | Ley 1213-F: CREA EL CONSEJO ECONOMICO Y SOCIAL (CONES) - ART.45 C.P.1957-1994 | as enacted, in force 25 September 2002 |
| `ley-1210-x/` | Ley 1210-X: ACUERDO NACION-PROVINCIAS SOBRE RELACION FINANCIERA Y COPARTICIPACION FEDERAL | as enacted, in force 11 August 2002 |
| `ley-1209-a/` | Ley 1209-A: CREA REGISTRO PUBLICO UNIFICADO DE CREDITOS PCIALES. (RE.CRE.PRO.) | as enacted, in force 11 August 2002 |
| `ley-1208-e/` | Ley 1208-E: FUNCIONAMIENTO ALBERGUES ESCOLARES EN EL SISTEMA EDUCATIVO PROVINCIAL | as enacted, in force 11 August 2002 |
| `ley-1207-c/` | Ley 1207-C: INSCRIPCION  EN JUZGADOS DE PAZ INMUEBLE COMO BIEN DE FAMILIA | as enacted, in force 7 August 2002 |
| `ley-1204-g/` | Ley 1204-G: ADHESION L.N.25.598 -DIA NACIONAL DE LA MEDICINA SOCIAL- | as enacted, in force 7 August 2002 |
| `ley-1202-k/` | Ley 1202-K: INEMBARGABILIDAD INMUEBLE QUE CONSTITUYA VIVIENDA UNICA HOGAR FAMILIAR | as enacted, in force 28 July 2002 |
| `ley-1203-f/` | Ley 1203-F: EMERG. PUBLICA - ADHIERE ARTS.8, 9 Y 10 L.N.25.561.- EMERG. PUBLICA | as enacted, in force 30 June 2002 |
| `ley-1201-f/` | Ley 1201-F: LOS MUNICIPIOS ABONARAN CON "QUEBRACHO" O "LECOP", TASAS SEGUN L.840-F | as enacted, in force 19 July 2002 |
| `ley-1200-g/` | Ley 1200-G: ESTABLECE LA PRESCRIPCION DE MEDICAMENTOS EN SU DENOMINACION GENERICA | as enacted, in force 7 July 2002 |
| `ley-1199-x/` | Ley 1199-X: ACUERDO MRIO. DE S. PUBLICA CHACO Y PROGRAMA DE NAC. UNIDAS P/EL DES. | as enacted, in force 29 May 2002 |
| `ley-1198-f/` | Ley 1198-F: EXCEPTUA EL PAGO DE TASAS PARA ACCEDER A PLANES SOCIALES, ALIMENTARIOS O DE EMPLEO | as enacted, in force 29 May 2002 |
| `ley-1197-a/` | Ley 1197-A: EXPROPIA INMUEBLE EN LAS BREÑAS P/ CASA DE LA CULTURA Y TEATRO MUNIC. | as enacted, in force 19 May 2002 |
| `ley-1196-i/` | Ley 1196-I: CREA LA UNIDAD EJECUTORA PROVINCIAL DEL "PROINTAL" (UEPPR) | as enacted, in force 19 May 2002 |
| `ley-1195-a/` | Ley 1195-A: NO SERAN ADMITIDOS COMO PROVEEDORES, PREST. O CONTR. DEUDORES EN MORA | as enacted, in force 3 May 2002 |
| `ley-1194-a/` | Ley 1194-A: ESTABLECE EN LOS PODERES DEL ESTADO, DATOS, INFORM. SEAN DESAGREGADOS | as enacted, in force 28 April 2002 |
| `ley-1193-g/` | Ley 1193-G: CREA REGISTRO UNICO PCIAL. DE ENTIDADES PUBLICAS Y PRIVADAS EN LA PCIA | as enacted, in force 28 April 2002 |
| `ley-1191-a/` | Ley 1191-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 24 April 2002 |
| `ley-1190-l/` | Ley 1190-L: CREA PROGRAMA DE EMPLEO PRODUCTIVO CHAQUEÑO (P.E.PRO.CHA.) | as enacted, in force 17 April 2002 |
| `ley-1188-a/` | Ley 1188-A: EXPROPIA INMUEBLES EN S.PEÑA P/CONSTRUIR VIVIENDAS | as enacted, in force 20 January 2002 |
| `ley-1185-a/` | Ley 1185-A: EXPROPIA INMUEBLE EN MARGARITA BELEN PARA SER ADJUDICADO EN VENTA A LOS ACTUALES OCUPANTES | as enacted, in force 9 January 2002 |
| `ley-1182-k/` | Ley 1182-K: LEY DE OBRAS PUBLICAS | as enacted, in force 27 January 2002 |
| `ley-1179-j/` | Ley 1179-J: LEY ORGANICA POLICIAL | as enacted, in force 20 January 2002 |
| `ley-1189-f/` | Ley 1189-F: TASA USO VIA NAVEGABLE, PAGO DRAGADO MANTENIMIENTO RIACHO BARRANQUERAS | as enacted, in force 30 December 2001 |
| `ley-1187-x/` | Ley 1187-X: RATIFICA ACUERDO MARCO ADHESION SISTEMA IDENTIFICACION NACIONAL TRIBUTARIO Y SOCIAL ( (SINTyS) | as enacted, in force 30 December 2001 |
| `ley-1183-r/` | Ley 1183-R: CREA LA RESERVA NATURAL CULTURAL "PRES. ROQUE SAENZ PEÑA" COMPL. ECOL. | as enacted, in force 11 January 2002 |
| `ley-1181-n/` | Ley 1181-N: ESTABLECE LA MEDIACION PENAL EN LA PROVINCIA DEL CHACO | as enacted, in force 23 January 2002 |
| `ley-1184-a/` | Ley 1184-A: EXPROPIA INMUEBLE EN SAENZ PEÑA P/ADJUDICAR EN VENTA ACTUALES OCUPANT. | as enacted, in force 4 January 2002 |
| `ley-1178-e/` | Ley 1178-E: PLAN PROVINCIAL DE PREVENCION DE VIOLENCIA EN LAS ESCUELAS | as enacted, in force 2 January 2002 |
| `ley-1176-f/` | Ley 1176-F: RATIFICA "COMPROMISO POR LA INDEPENDENCIA". SEGUNDA ADDENDA COMPR.FED. | as enacted, in force 5 December 2001 |
| `ley-1175-c/` | Ley 1175-C: PRESTACION VOLUNTARIA DE SERV. EN ORGANIZ. CIVILES SIN FINES DE LUCRO | as enacted, in force 14 December 2001 |
| `ley-1174-g/` | Ley 1174-G: GARANTIZA A TODA PERSONA LA ENTREGA DE COPIA DE SU HISTORIA CLINICA | as enacted, in force 14 December 2001 |
| `ley-1173-e/` | Ley 1173-E: "DIA PROVINCIAL DEL VECINO". ADHESION "PRINCIPIOS S/LA TOLERANCIA" | as enacted, in force 14 December 2001 |
| `ley-1171-i/` | Ley 1171-I: PROGRAMA OCUPACIONAL Y PRODUCTIVO PROVINCIAL (PROPP) | as enacted, in force 14 December 2001 |
| `ley-1170-x/` | Ley 1170-X: ACTA COMPLEM. CONVENIO PRESTAMO FONDO P/ LA TRANSFORM. SECT. PUBLICOS | as enacted, in force 30 November 2001 |
| `ley-1169-x/` | Ley 1169-X: CONVENIO SUSCRIPCION LETRAS DE CANCEL. DE OBLIGAC. PCIALES. (LECOP) | as enacted, in force 16 November 2001 |
| `ley-1168-k/` | Ley 1168-K: CREA UNIDAD EJECUTORA DEL SERVICIO ELECTRICO RURAL.MODIF. L.1065-K. | as enacted, in force 21 November 2001 |
| `ley-1161-a/` | Ley 1161-A: EXPROPIA INMUEBLES EN PRES. ROQUE SAENZ PEÑA P/ ADJUDICAR EN VENTA | as enacted, in force 21 October 2001 |
| `ley-1154-f/` | Ley 1154-F: APORTE DEL 5% DE PREMIOS DE LOTERIA CHAQUEÑA PARA DEPORTE AMATEUR | as enacted, in force 21 September 2001 |
| `ley-1155-c/` | Ley 1155-C: NORMAS PARA EL JUEGO DE AZAR | as enacted, in force 23 September 2001 |
| `ley-1152-c/` | Ley 1152-C: CREA REGISTRO DE ADOPCIONES A CARGO DEL REGISTRO CIVIL DE LA PCIA. | as enacted, in force 23 September 2001 |
| `ley-1146-a/` | Ley 1146-A: CONSEJO P/LA PROMOCION, FORTALECIM. Y DEFENSA DE LOS DERECHOS HUMANOS | as enacted, in force 24 August 2001 |
| `ley-1145-i/` | Ley 1145-I: CONSTRUCCION DE PARQUES Y AREAS INDUSTRIALES | as enacted, in force 12 October 2001 |
| `ley-1138-g/` | Ley 1138-G: SALUD PUBLICA Y EL IN.S.S.SE.P. PROVEERA MEDICACION P/MIASTENIA GRAVIS | as enacted, in force 5 August 2001 |
| `ley-1133-b/` | Ley 1133-B: REGLAMENTA DESIGNACION DE JUECES Y REPRESENTANTES DEL MRIO. PUBLICO | as enacted, in force 13 June 2001 |
| `ley-1128-a/` | Ley 1128-A: REGIMEN DE INCOMPATIBILIDADES | as enacted, in force 2 September 2001 |
| `ley-1116-a/` | Ley 1116-A: EXPROPIA INMUEBLES EN BQUERAS. P/CONSTRUCC.DEFENSA CONTRA INUNDACIONES | as enacted, in force 19 January 2001 |
| `ley-1111-f/` | Ley 1111-F: AUTORIZA AL P.E. CONTRAER UN PRESTAMO DE HASTA $29.400.000,- | as enacted, in force 24 December 2000 |
| `ley-1108-a/` | Ley 1108-A: EXPROPIA INMUEBLES EN RCIA.P/CENTROS COMUNITARIO, DE SALUD Y DEPORTIVO | as enacted, in force 5 January 2001 |
| `ley-1110-a/` | Ley 1110-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 29 December 2000 |
| `ley-1109-a/` | Ley 1109-A: EXPROPIA TERRENOS EN RCIA. P/ ENSANCHAMIENTO AV. ESPAÑA | as enacted, in force 29 December 2000 |
| `ley-1106-a/` | Ley 1106-A: EXPROPIA INMUEBLE EN RCIA. P/OBISPADO DE LA ARQUIDIOCESIS DE RCIA. | as enacted, in force 20 December 2000 |
| `ley-1100-t/` | Ley 1100-T: CREA EL FONDO PROVINCIAL DEL TRANSPORTE | as enacted, in force 20 December 2000 |
| `ley-1083-a/` | Ley 1083-A: CREA EN LA PCIA. REGISTRO DE DEUDORES ALIMENTARIOS MOROSOS (RE.D.A.M.) | as enacted, in force 17 September 2000 |
| `ley-1080-s/` | Ley 1080-S: CREA REGISTRO PCIAL. DE GIMNASIOS, INSTITUTOS, ETC. DE DEPORTES | as enacted, in force 13 September 2000 |
| `ley-714-f/` | Ley 714-F: CONSOLIDACION DE DEUDAS DEL ESTADO PROVINCIAL. CREA BONO -BOSAFI- | as enacted, in force 11 January 1992 |
| `ley-1061-x/` | Ley 1061-X: APRUEBA CONVENIO DE ASISTENCIA FINANCIERA CON EL GOBIERNO NACIONAL | as enacted, in force 31 May 2000 |
| `ley-1060-x/` | Ley 1060-X: APRUEBA COMPROMISO FEDERAL CON LA NACION Y GOB. PCIALES. S/L.N. 25.235 | as enacted, in force 31 May 2000 |
| `ley-1058-a/` | Ley 1058-A: REGIMEN DE COMPRAS Y CONTRATACION PROVINCIAL (COMPRE).DEROGA L.3146 | as enacted, in force 31 May 2000 |
| `ley-1056-j/` | Ley 1056-J: CREA PROGRAMA INTEGRADO DE SEGURIDAD Y PROTECCION A LA COMUNIDAD RURAL | as enacted, in force 21 May 2000 |
| `ley-1054-a/` | Ley 1054-A: EXPROPIA INMUEBLE EN QUITILIPI P/ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 23 January 2000 |
| `ley-1046-a/` | Ley 1046-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 12 January 2000 |
| `ley-1042-a/` | Ley 1042-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 29 December 1999 |
| `ley-1041-a/` | Ley 1041-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 26 May 2000 |
| `ley-1040-a/` | Ley 1040-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 26 May 2000 |
| `ley-1038-a/` | Ley 1038-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 23 June 2000 |
| `ley-1037-a/` | Ley 1037-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 29 December 1999 |
| `ley-1036-a/` | Ley 1036-A: EXPROPIA INMUEBLE EN DPTO. 1 DE MAYO P/FAMILIAS DE AGRICULTORES | as enacted, in force 19 December 1999 |
| `ley-1032-a/` | Ley 1032-A: EXPROPIA INMUEBLES DPTO. SAN FERNANDO P/ADJUDICAR EN VENTA ACT. OCUP. | as enacted, in force 19 November 1999 |
| `ley-1030-a/` | Ley 1030-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 12 November 1999 |
| `ley-1029-a/` | Ley 1029-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 12 April 2000 |
| `ley-1028-b/` | Ley 1028-B: DESAFUERO DE UN DIPUTADO E INCORPORACION DEL SUPLENTE | as enacted, in force 31 October 1999 |
| `ley-1024-b/` | Ley 1024-B: PROMULGACION DE LEYES. VETO. (REGLAMENTA ART.118 C.P.1957-1994) | as enacted, in force 15 September 1999 |
| `ley-1023-s/` | Ley 1023-S: LEY DE ORDENAMIENTO, PROMOCION Y FISCALIZACION DEL DEPORTE | as enacted, in force 24 September 1999 |
| `ley-1016-c/` | Ley 1016-C: BASES PROGRAMATICAS PARA LA PREVENCIÓN Y ASISTENCIA A LAS MADRES NIÑAS Y PADRES NIÑOS | as enacted, in force 27 August 1999 |
| `ley-1017-a/` | Ley 1017-A: EXPROPIA INMUEBLE EN LAGUNA BLANCA PARA MUNICIPIO LOCAL | as enacted, in force 29 August 1999 |
| `ley-1009-a/` | Ley 1009-A: EXPROPIA INMUEBLES EN DEPTO. SAN FERNANDO P/ADJUDICAR ACT. OCUPANTES | current text only, as of 21 August 2018 |
| `ley-1012-a/` | Ley 1012-A: EXPROPIA INMUEBLE EN GRAL. VEDIA P/CONSTRUCC. EDIFICIO S.E.CH.E.E.P. | as enacted, in force 15 August 1999 |
| `ley-1010-a/` | Ley 1010-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 22 August 1999 |
| `ley-1008-a/` | Ley 1008-A: EXPROPIA INMUEBLE EN V.ANGELA, P/ADJUDICAR EN VENTA COMUNIDAD ABORIGEN | as enacted, in force 22 August 1999 |
| `ley-1007-a/` | Ley 1007-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 22 August 1999 |
| `ley-1005-a/` | Ley 1005-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 1 August 1999 |
| `ley-1004-a/` | Ley 1004-A: EXPROPIA INMUEBLES EN RCIA. P/ CONSTRUCCION ESCUELA SECUNDARIA | as enacted, in force 23 July 1999 |
| `ley-994-a/` | Ley 994-A: EXPROPIA INMUEBLE DPTO. SAN FERNANDO P/ADJUDICAR A ACTUALES OCUPANTES | as enacted, in force 27 January 1999 |
| `ley-993-a/` | Ley 993-A: EXPROPIA INMUEBLE DPTO. SAN FERNANDO P/ADJUDICAR A ACTUALES OCUPANTES | as enacted, in force 27 January 1999 |
| `ley-992-a/` | Ley 992-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 27 January 1999 |
| `ley-990-a/` | Ley 990-A: EXPROPIA INMUEBLE EN COLONIA BENITEZ P/MUSEO CASA Y JARDIN SCHULZ | as enacted, in force 15 January 1999 |
| `ley-991-a/` | Ley 991-A: EXPROPIA INMUEBLE DPTO. SAN FERNANDO P/ADJUDICAR A ACTUALES OCUPANTES | as enacted, in force 27 January 1999 |
| `ley-997-a/` | Ley 997-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 27 January 1999 |
| `ley-996-a/` | Ley 996-A: EXPROPIA INMUEBLE DPTO. SAN FERNANDO P/ADJUDICAR ACTUALES OCUPANTES | as enacted, in force 27 January 1999 |
| `ley-995-a/` | Ley 995-A: EXPROPIA INMUEBLE DPTO. SAN FERNANDO P/ADJUDICAR ACTUALES OCUPANTES | as enacted, in force 27 January 1999 |
| `ley-984-a/` | Ley 984-A: EXPROPIA INMUEBLE EN RCIA. P/VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 27 January 1999 |
| `ley-982-a/` | Ley 982-A: EXPROPIA INMUEBLES EN RCIA. P/CONSTRUCC. VIVIENDAS ACTUALES OCUPANTES | as enacted, in force 15 January 1999 |
| `ley-978-a/` | Ley 978-A: EXPROPIA INMUEBLES EN LAGUNA BLANCA P/PLANES DE VIVIENDAS, ETC. | as enacted, in force 15 January 1999 |
| `ley-973-a/` | Ley 973-A: EXPROPIA INMUEBLES P/CONSTRUC. "ACUEDUCTO CENTRO-OESTE CHAQUEÑO" | as enacted, in force 27 December 1998 |
| `ley-967-j/` | Ley 967-J: PROHIBE VENTA BEBIDAS ALCOHOLICAS A PARTIR DE LAS 23:00 HASTA 08:30 HS | as enacted, in force 25 December 1998 |
| `ley-959-a/` | Ley 959-A: EXPROPIA INMUEBLES EN RCIA. P/CONSTRUCCION ESCUELA PRIMARIA | as enacted, in force 18 October 1998 |
| `ley-956-j/` | Ley 956-J: CREA EN LA PCIA. CENTRO UNICO DE RECEPCION Y EXPEDICION DE INFORMACION | as enacted, in force 27 September 1998 |
| `ley-955-a/` | Ley 955-A: EXPROPIA INMUEBLE EN RCIA. P/REGULARIZAR SITUACION FAMILIAS OCUPANTES. | as enacted, in force 20 September 1998 |
| `ley-954-x/` | Ley 954-X: CONVENIO S/EXPLOTACION SERV.INTERURBANO F.C.GRAL. BELGRANO S.A. | as enacted, in force 4 September 1998 |
| `ley-953-e/` | Ley 953-E: CREA REGIMEN DE PASANTIAS EN EL PODER JUDICIAL DEL CHACO | as enacted, in force 23 August 1998 |
| `ley-951-x/` | Ley 951-X: APRUEBA TRATADO PARCIAL INTERPROVINCIAL (CREA REGION ECONOMICO-SOCIAL) | as enacted, in force 19 July 1998 |
| `ley-952-a/` | Ley 952-A: EL INSTITUTO DE TIERRAS FISCALES TRANSFERIRA INMUEBLES DE LA PROVINCIA AL IPDUV. | as enacted, in force 7 August 1998 |
| `ley-950-n/` | Ley 950-N: PROHIBE EN LA PCIA. DISTR., COM.,VENTA ETC. JUEGO ELECTR."CARMAGGEDON" | as enacted, in force 24 July 1998 |
| `ley-949-t/` | Ley 949-T: REGIMEN DE TRANSITO Y SEGURIDAD VIAL DE LA PCIA. DEL CHACO | current text only, as of 10 September 2026 |
| `ley-948-e/` | Ley 948-E: DETERMINA DISEÑO ARQUITECTONICO ESCUELAS, P/UTILIZAC. EN EMERGENCIAS | as enacted, in force 25 November 1998 |
| `ley-946-f/` | Ley 946-F: PRESTAMO SUBSIDIARIO P/"PROGRAMA MEJORAMIENTO DE BARRIOS" | as enacted, in force 10 June 1998 |
| `ley-945-c/` | Ley 945-C: SENTENCIAS JUDIC. QUE CONDENEN AL ESTADO TENDRAN EFECTO DECLARATIVO. | as enacted, in force 26 April 1998 |
| `ley-944-f/` | Ley 944-F: ADHESION L.N.24855 -DE CREACION DEL FONDO FIDUCIARIO FEDERAL DE INFRAESTRUCTURA REGIONAL-. | as enacted, in force 26 April 1998 |
| `ley-943-x/` | Ley 943-X: CONVENIO NACION-PCIA. P/CANCELAR ACREENCIAS POR VENTA GAS DEL ESTADO | as enacted, in force 5 April 1998 |
| `ley-942-a/` | Ley 942-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/ESCUELA AGROPECUARIA N.13 | current text only, as of 21 August 2018 |
| `ley-940-a/` | Ley 940-A: EXPROPIA INMUEBLE EN DPTO. GRAL. SAN MARTIN P/ESCUELA AGROPECUARIA | as enacted, in force 18 January 1998 |
| `ley-939-e/` | Ley 939-E: CREA LA "JUNTA DE ESTUDIOS HISTORICOS DEL CHACO" | as enacted, in force 21 January 1998 |
| `ley-938-a/` | Ley 938-A: EXPROPIA INMUEBLE EN DPTO. 12 DE OCTUBRE P/AREA DE RESERVA NATURAL | as enacted, in force 18 January 1998 |
| `ley-937-i/` | Ley 937-I: RÉGIMEN DE RADICACIÓN Y PROMOCIÓN INDUSTRIAL | as enacted, in force 25 January 1998 |
| `ley-936-m/` | Ley 936-M: ARANCELAMIENTO DE CIERTAS DILIGENCIAS JUDICIALES (GASTOS DOCUMENTADOS) | as enacted, in force 21 January 1998 |
| `ley-934-a/` | Ley 934-A: EXPROPIA INMUEBLES EN DPTO. 12 DE OCTUBRE P/VVDAS. FAMILIARES | as enacted, in force 16 November 1997 |
| `ley-933-a/` | Ley 933-A: EXPROPIA INMUEBLE EN RCIA. PARA APERTURA DE CALLE PUBLICA | as enacted, in force 16 November 1997 |
| `ley-932-i/` | Ley 932-I: REGIMEN DE DENOMINACIONES DE ORIGEN CONTROLADAS | as enacted, in force 16 November 1997 |
| `ley-931-a/` | Ley 931-A: EXPROPIA INMUEBLE EN RCIA. P/VENTA A ACTUALES OCUPANTES | as enacted, in force 8 October 1997 |
| `ley-930-a/` | Ley 930-A: EXPROPIA INMUEBLE EN RCIA. P/VENTA A ACTUALES OCUPANTES | as enacted, in force 8 October 1997 |
| `ley-929-a/` | Ley 929-A: EXPROPIA INMUEBLE EN RCIA. P/VENTA A ACTUALES OCUPANTES | as enacted, in force 8 October 1997 |
| `ley-928-e/` | Ley 928-E: OTORGA AL CORO CHELA-LAA-PI INVESTIDURA DE "CORO OFICIAL AUTOCTONO   / | as enacted, in force 19 September 1997 |
| `ley-927-e/` | Ley 927-E: 27 DE AGOSTO DE CADA AÑO "DIA DEL INMIGRANTE UCRANIANO EN EL CHACO" | as enacted, in force 5 September 1997 |
| `ley-926-a/` | Ley 926-A: CREA JUZGADO DE EJECUCIÓN PENAL CON ASIENTO EN RESISTENCIA CON COMPETENCIA EN TODA LA PROVINCIA | as enacted, in force 8 August 1997 |
| `ley-925-e/` | Ley 925-E: ESTABLECE EN DOCUMENT. OFIC. INSCRIPC."DONAR ORGANOS ES SALVAR VIDAS" | as enacted, in force 1 August 1997 |
| `ley-924-a/` | Ley 924-A: EXPROPIA INMUEBLE UBICADO EN RCIA. P/SU VENTA A ACTUALES OCUPANTES | as enacted, in force 26 September 1997 |
| `ley-923-a/` | Ley 923-A: EXPROPIA INMUEBLE EN RCIA. P/VENTAS A SUS ACTUALES OCUPANTES | as enacted, in force 26 September 1997 |
| `ley-922-a/` | Ley 922-A: EXPROPIA INMUEBLE EN RCIA. P/VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 26 September 1997 |
| `ley-921-a/` | Ley 921-A: EXPROPIA INMUEBLE EN DPTO. S. FERNANDO P/VENDER A ACTUALES OCUPANTES | as enacted, in force 26 September 1997 |
| `ley-920-a/` | Ley 920-A: EXPROPIA INMUEBLE EN RCIA. CON DESTINO A CALLE PUBLICA. | as enacted, in force 16 July 1997 |
| `ley-919-a/` | Ley 919-A: EXPROPIA INMUEBLES EN GRAL. SAN MARTIN P/OFICINAS PODER JUDICIAL | as enacted, in force 13 June 1997 |
| `ley-918-e/` | Ley 918-E: ADHESION L.N.24784 Y L.N.24785 -DERECHOS POLITICOS DE LA MUJER- | as enacted, in force 8 June 1997 |
| `ley-917-x/` | Ley 917-X: CONVENIO DE CESION DEL AEROPUERTO DE RESISTENCIA | as enacted, in force 1 June 1997 |
| `ley-916-g/` | Ley 916-G: ARANCELA SERVICIOS DE LA DIRECCION DE FISCALIZACION SANITARIA | as enacted, in force 7 May 1997 |
| `ley-915-a/` | Ley 915-A: CREA CONSEJO CONSULTIVO P/PROGRAMA DE PROTECCION CONTRA INUNDACIONES | as enacted, in force 7 May 1997 |
| `ley-914-l/` | Ley 914-L: REGISTRO UNICO DE ASPIRANTES A PUESTOS DE TRABAJO P/EX-COMBATIENTES | as enacted, in force 7 May 1997 |
| `ley-912-a/` | Ley 912-A: EXPROPIA INMUEBLES EN GENERAL SAN MARTIN PARA DESTINARLO A LA ESCUELA TÉCNICA AGROPECUARIA N.º 8 | as enacted, in force 30 April 1997 |
| `ley-913-b/` | Ley 913-B: LEY ORGANICA DEL MINISTERIO PUBLICO (ART.156 CONST. PCIAL. 1957-1994) | as enacted, in force 30 April 1997 |
| `ley-911-e/` | Ley 911-E: DECLARA PATRIMONIO CULTURAL AL CLUB SOCIAL DE RESISTENCIA | as enacted, in force 20 April 1997 |
| `ley-909-f/` | Ley 909-F: BONOS CHAQUEÑOS DE CONSOLIDACION II. MODIFICA LEYES 3958 Y 4230 | as enacted, in force 2 February 1997 |
| `ley-906-j/` | Ley 906-J: PROGRAMA PROVINCIAL DE PREVENCIÓN A LAS VÍCTIMAS DE LA VIOLENCIA FAMILIAR | as enacted, in force 31 January 1997 |
| `ley-903-c/` | Ley 903-C: ESTATUTO JURIDICO DEL MENOR DE EDAD Y LA FAMILIA. | current text only, as of 11 April 2025 |
| `ley-910-f/` | Ley 910-F: BONOS PARA CANCELACIÓN DE LA DEUDA PÚBLICA PROVINCIAL | as enacted, in force 15 January 1997 |
| `ley-908-a/` | Ley 908-A: ASIGNA CARACTER DE LETRADO A JUZGADOS DE PAZ N.1 Y 2 DE RESISTENCIA | as enacted, in force 26 January 1997 |
| `ley-907-i/` | Ley 907-I: PROGRAMA DE MICROEMPRENDIMIENTOS PRODUCTIVOS (CREDITOS SUPERVISADOS) | as enacted, in force 26 January 1997 |
| `ley-905-a/` | Ley 905-A: CREA DEFENSORIA N.2 Y FISCALIA N.2 CON ASIENTO EN J. J. CASTELLI | as enacted, in force 24 January 1997 |
| `ley-902-k/` | Ley 902-K: CREA SISTEMA PROVINCIAL DE LA VIVIENDA | as enacted, in force 24 January 1997 |
| `ley-900-e/` | Ley 900-E: ESTABLECE "DIA DEL TEATRO CHAQUEÑO" EL 8 DE DICIEMBRE DE CADA AÑO | as enacted, in force 17 January 1997 |
| `ley-899-a/` | Ley 899-A: CREA EN EL PODER LEGISLATIVO LA "EDITORIAL PARLAMENTARIA" | as enacted, in force 1 June 1997 |
| `ley-896-r/` | Ley 896-R: SISTEMA PCIAL. AREAS NATURALES PROTEGIDAS (ART.38 INC.4 CONST. PCIAL.) | as enacted, in force 29 December 1996 |
| `ley-895-r/` | Ley 895-R: DECLARA DE INTERES PCIAL. REVISTA "NUESTRO AMBIENTE" | as enacted, in force 18 December 1996 |
| `ley-894-j/` | Ley 894-J: CREA LA TARJETA DE PROTECCION AL CIUDADANO | as enacted, in force 13 April 1997 |
| `ley-893-r/` | Ley 893-R: CREDITO DE U$S 50.000.000 P/EJECUTAR PROGARMAS -PROSAP- Y -PRODERNEA- | as enacted, in force 18 December 1996 |
| `ley-892-t/` | Ley 892-T: ESTATUTO SOCIAL DE "SE.FE.CHA. S.A." | as enacted, in force 24 November 1996 |
| `ley-890-a/` | Ley 890-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A SUS OCUPANTES | as enacted, in force 4 December 1996 |
| `ley-889-e/` | Ley 889-E: "METAS PARA CUMPLIMIENTO CONVENCION INTERNACIONAL S/ DERECHOS DEL NIÑO" | as enacted, in force 18 October 1996 |
| `ley-884-b/` | Ley 884-B: INICIATIVA POPULAR, CONSULTA POPULAR Y REVOCATORIA (ART.2 C.P.) | as enacted, in force 18 August 1996 |
| `ley-883-m/` | Ley 883-M: COMPETENCIA JUZGADOS EN CUESTIONES RELATIVAS A ABLACION E IMPLANTES | as enacted, in force 4 August 1996 |
| `ley-880-r/` | Ley 880-R: PROTECCION DEL SUELO, AGUA Y RECURSOS ENERGETICOS | as enacted, in force 14 July 1996 |
| `ley-879-c/` | Ley 879-C: REGLAMENTA ACTIVIDAD DE LOS MANDATARIOS DEL AUTOMOTOR | as enacted, in force 25 August 1996 |
| `ley-878-f/` | Ley 878-F: RATIFICA CONVENIO DE ADHESION L.N.24331 -ZONAS FRANCAS- | as enacted, in force 16 June 1996 |
| `ley-876-e/` | Ley 876-E: ADHESION L.N.24561 -DIA DEL INMIGRANTE ITALIANO- | as enacted, in force 5 July 1996 |
| `ley-874-d/` | Ley 874-D: PRODUCTOS ELABORADOS EN EL CHACO, SERAN "MANUFACTURA CHAQUEÑA" | as enacted, in force 23 October 1996 |
| `ley-873-i/` | Ley 873-I: CREA PROGRAMA DE INTEGRACION AGROINDUSTRIAL DE LA PCIA. (PIACH) | as enacted, in force 6 October 1996 |
| `ley-872-a/` | Ley 872-A: SISTEMA INTEGRADO Y PUBLICO DE ESTADISTICAS JUDICIALES (ART.154 C.P.) | as enacted, in force 23 June 1996 |
| `ley-871-a/` | Ley 871-A: EXPROPIA INMUEBLE EN DPTO. 1 DE MAYO P/ FAMILIA DE AGRICULTORES | as enacted, in force 23 October 1996 |
| `ley-870-t/` | Ley 870-T: CREA "SERVICIOS FERROVIARIOS DEL CHACO S.A." (SEFECHA) | as enacted, in force 12 May 1996 |
| `ley-868-g/` | Ley 868-G: PROGRAMA DE SALUD REPRODUCTIVA Y PROCREACION HUMANA RESPONSABLE | as enacted, in force 6 October 1996 |
| `ley-867-k/` | Ley 867-K: CUOTA MENSUAL DEL 15% PARA EX-COMBATIENTES EN PLANES DE VIVIENDAS | as enacted, in force 28 April 1996 |
| `ley-866-f/` | Ley 866-F: AUTORIZA P.E. TRAMITAR Y OBTENER PRESTAMO HASTA $ 60.000.000 | as enacted, in force 9 February 1996 |
| `ley-863-a/` | Ley 863-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/ESCUELA NIVEL SECUNDARIO | as enacted, in force 24 May 1996 |
| `ley-862-a/` | Ley 862-A: EXPROPIA INMUEBLE EN EL BARRIO FACUNDO P/VENTA ACTUALES OCUPANTES | as enacted, in force 24 May 1996 |
| `ley-861-a/` | Ley 861-A: EXPROPIA INMUEBLES EN DPTO. SAN FERNANDO P/VENTA ACTUALES OCUPANTES | as enacted, in force 24 May 1996 |
| `ley-858-a/` | Ley 858-A: FACULTA AL P.E. COMPRAR PARCELAS DEL EX-INGENIO LAS PALMAS | as enacted, in force 9 February 1996 |
| `ley-860-a/` | Ley 860-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/VENTA A ACTUALES OCUPANTES | as enacted, in force 24 May 1996 |
| `ley-857-f/` | Ley 857-F: EL GOBIERNO PCIAL. SE HARA CARGO DE LA DEUDA DEL BCO. DEL CHACO S.E.M. | as enacted, in force 21 January 1996 |
| `ley-856-f/` | Ley 856-F: FACULTA AL P.E. REPROGRAMAR DEUDAS PCIALES. DE CARACTER FINANCIERO | as enacted, in force 24 January 1996 |
| `ley-855-f/` | Ley 855-F: FACULTA AL P.E. CONVENIR CON EL BCO. CENTRAL CANCELACION DE CREDITOS | as enacted, in force 24 January 1996 |
| `ley-854-p/` | Ley 854-P: LEY ORGANICA MUNICIPAL | as enacted, in force 20 December 1995 |
| `ley-853-a/` | Ley 853-A: INGRESO AL S.T.J., HASTA TANTO SE INSTRUMENTE CARRERA ADMINISTRATIVA | as enacted, in force 24 January 1996 |
| `ley-852-a/` | Ley 852-A: ASIGNAN CARACTER DE LETRADO AL JUZGADO DE FALTAS DE RESISTENCIA | as enacted, in force 24 January 1996 |
| `ley-851-c/` | Ley 851-C: ADHESION L.N.24540 -IDENTIFICACION RECIEN NACIDOS- | as enacted, in force 6 December 1995 |
| `ley-849-k/` | Ley 849-K: ADHESION L.N.24464 -SISTEMA FEDERAL DE VIVIENDA- | as enacted, in force 20 October 1995 |
| `ley-847-i/` | Ley 847-I: ADHESION AL TITULO I "DISPOSICIONES GRALES." L.N.24467 -PYMES- | as enacted, in force 12 April 1996 |
| `ley-844-i/` | Ley 844-I: CREA APORTE ESPECIAL DE $2 POR TONELADA DE ALGODON EN BRUTO | as enacted, in force 20 September 1995 |
| `ley-843-a/` | Ley 843-A: CREA EL INSTITUTO DEL DEFENSOR DEL PUEBLO | as enacted, in force 8 September 1995 |
| `ley-838-a/` | Ley 838-A: CREA EL CONSEJO ADJUDICADOR DE LA TIERRA PUBLICA | as enacted, in force 26 November 1995 |
| `ley-841-t/` | Ley 841-T: ADHESION D.N.2284/91 Y 1494/92 -DESREGULA TRANSPORTE AUTOMOTOR- | as enacted, in force 2 August 1995 |
| `ley-835-r/` | Ley 835-R: CREA PROGRAMA DE RELEVAMIENTO E INVENTARIO DE REC. NATURALES PCIALES. | as enacted, in force 30 July 1995 |
| `ley-834-q/` | Ley 834-Q: NUEVO REGIMEN ELECTORAL PROVINCIAL | current text only, as of 12 September 2024 |
| `ley-833-m/` | Ley 833-M: CREA LOS TRIBUNALES DE CONCILIACION, ARBITRAMENTO Y ARBITRAJE | as enacted, in force 7 July 1995 |
| `ley-831-a/` | Ley 831-A: NUEVO REGIMEN DEL TRIBUNAL DE CUENTAS | as enacted, in force 11 August 1995 |
| `ley-830-i/` | Ley 830-I: DECLARA DE INTERES PCIAL. EL PROGRAMA -PROMEX- | as enacted, in force 28 May 1995 |
| `ley-822-g/` | Ley 822-G: PROTESICO DENTAL, MECANICO DENTAL, LABORATOR. DENTAL O TECNICO DENTAL | as enacted, in force 18 January 1995 |
| `ley-821-g/` | Ley 821-G: LA BONIFICACION POR PRESTACIONES PROFESIONALES COMPLEJAS, INTEGRARA LA | as enacted, in force 28 April 1995 |
| `ley-817-p/` | Ley 817-P: CONVENIOS CON MUNICIP. P/AFECTACION DE LA CUOTA PARTE DE LA COOPARTIC. | as enacted, in force 6 January 1995 |
| `ley-813-p/` | Ley 813-P: FIJA AREAS DE INFLUENCIA DE LOS MUNICIPIOS DE LA PROVINCIA. | as enacted, in force 25 November 1994 |
| `ley-811-g/` | Ley 811-G: ELABORACION DE MEDICAMENTOS PARA ABASTECER A HOSPITALES PUBLICOS | as enacted, in force 9 June 1995 |
| `ley-814-c/` | Ley 814-C: ADHESION L.N.24283 (LEY RAIMONDA) Y D.N.794/94 - | as enacted, in force 9 November 1994 |
| `ley-812-i/` | Ley 812-I: DECLARA LA RESERVA DE 10.000 HAS. PARA HIJOS DE PRODUCTORES DE CAPRINOS | as enacted, in force 9 November 1994 |
| `ley-806-i/` | Ley 806-I: PROHIBE USO DE ANABOLICOS Y HORMONALES EN ANIMALES P/CONSUMO HUMANO | as enacted, in force 22 February 1995 |
| `ley-805-a/` | Ley 805-A: EMCOMENDAR AL P.E. ENVIO DE EPECIALISTAS SEGUN L.3563 | as enacted, in force 2 October 1994 |
| `ley-804-t/` | Ley 804-T: ADHESION AL ART.67 D.N.692/92 -SEGURO OBLIGATORIO AUTOMOTOR- | as enacted, in force 25 June 1994 |
| `ley-800-h/` | Ley 800-H: REGIMEN DE JUBILACIONES, RETIROS Y PENSIONES. MODIFICA LS. 544-P (ANTES LEY 3188) Y 647-H (ANTES LEY 3529) | as enacted, in force 16 September 1994 |
| `ley-797-g/` | Ley 797-G: DECLARA DE INTERES PCIAL. APLICACION VACUNA CUBANA "VA-MENGOC-BC" | as enacted, in force 17 June 1994 |
| `ley-794-b/` | Ley 794-B: ADHESION L.N.22431 Y L.N.24314 -DISCAPACITADOS- | as enacted, in force 17 June 1994 |
| `ley-788-c/` | Ley 788-C: INSTITUCIONES DE TURF CONCESION DE ACTIVIDADES A TERCEROS | as enacted, in force 20 May 1994 |
| `ley-784-c/` | Ley 784-C: ACTIVIDADES PROFESIONALES. ADHESION DN.2293/92 -MATRICULA UNICA- | as enacted, in force 16 January 1994 |
| `ley-782-i/` | Ley 782-I: ADHESION L.N.24196 -ACTIVIDAD MINERA- | as enacted, in force 16 January 1994 |
| `ley-779-a/` | Ley 779-A: REMUNERACIONES PARA EL PODER EJECUTIVO Y ORGANISMOS DESCENTRALIZADOS | as enacted, in force 12 January 1994 |
| `ley-778-a/` | Ley 778-A: PROGRAMA DESCENTRALIZACION DE FUNCIONES, OBRAS Y SERV. PCIALES. | as enacted, in force 11 September 1994 |
| `ley-776-c/` | Ley 776-C: DECLARA INEMBARGABLES BIENES INMUEBLES DONADOS A ENTIDADES INTERMEDIAS | as enacted, in force 10 December 1993 |
| `ley-775-e/` | Ley 775-E: DECLARA MONUMENTO HISTORICO EDIFICIO DEL MUSEO Y BIBLIOTECA POLICIAL | as enacted, in force 7 November 1993 |
| `ley-768-a/` | Ley 768-A: EL P.E. DICTARA NORMAS P/EMPRESAS DEDICADAS EXPLOTACION HIDROCARBUROS | as enacted, in force 10 September 1993 |
| `ley-764-p/` | Ley 764-P: REGIMEN ADJUDICACION TIERRAS DEL DEPARTAMENTOS ALMIRANTE BROWN Y GENERAL GUEMES | as enacted, in force 10 October 1993 |
| `ley-4261-n/` | Ley 4261-N: MODIFICA LEY 965-N (ANTES LEY 4538). | as enacted, in force 16 September 2026 |
| `ley-4252-a/` | Ley 4252-A: EXPROPIA INMUEBLE UBICADO EN LA CIUDAD DE RESISTENCIA-VILLA MARIN. | as enacted, in force 16 September 2026 |
| `ley-4194-f/` | Ley 4194-F: PRESUPUESTO GENERAL DE LA PROVINCIA DEL CHACO PARA EL EJERCICIO 2026. | as enacted, in force 10 December 2025 |
| `ley-4101-a/` | Ley 4101-A: CREA EL OBSERVATORIO DE CONFLICTOS DE TIERRAS Y TERRITORIOS. | as enacted, in force 21 November 2025 |
| `ley-4102-a/` | Ley 4102-A: RATIFICA DECRETO 3013/23 Y 1062/24 CREA ESTRUCTURA ORGÁNICA DE LA JURISDICCIÓN 59 -DIRECCIÓN PROVINCIAL DE INFORMACIÓN ESTADÍSTICA Y TERRITORIAL. | as enacted, in force 25 December 2024 |
| `ley-4108-a/` | Ley 4108-A: RATIFICA DECRETO 1684/24. | as enacted, in force 22 December 2024 |
| `ley-4135-f/` | Ley 4135-F: PRESUPUESTO GENERAL DE LA PROVINCIA DEL CHACO PARA EL EJERCICIO 2025. | as enacted, in force 1 January 2025 |
| `ley-4097-a/` | Ley 4097-A: EXPROPIA INMUEBLE - DESTINO DEPOSITO DE RESIDUOS URBANOS. | as enacted, in force 22 November 2024 |
| `ley-4063-e/` | Ley 4063-E: PREMIO TRIENAL DE RECONOCIMIENTO AL MÉRITO CIENTÍFICO DE LA MUJER CIENTÍFICA. | as enacted, in force 8 September 2024 |
| `ley-4027-a/` | Ley 4027-A: INCREMENTOS EN LAS ESCALAS SALARIALES VIGENTES DEL ESCALAFÓN GENERAL - LEY 196-A . | as enacted, in force 21 June 2024 |
| `ley-3827-g/` | Ley 3827-G: PREVENCIÓN, CONCIENTIZACIÓN Y TRATAMIENTO DEL JUEGO PATOLÓGICO. | current text only, as of 15 December 2023 |
| `ley-3807-h/` | Ley 3807-H: RETIRO VOLUNTARIO MÓVIL POR FAMILIAR CON DISCAPACIDAD. | as enacted, in force 14 July 2023 |
| `ley-3797-g/` | Ley 3797-G: REINSTAURA Y MODIFICA ART.5º de  LA LEY 3025-G. | as enacted, in force 5 July 2023 |
| `ley-3801-a/` | Ley 3801-A: REINSTAURA LEY 2556-A (ANTES LEY 7945) | as enacted, in force 2 June 2023 |
| `ley-3808-g/` | Ley 3808-G: DECLARACIÓN DE EMERGENCIA POR CONSUMOS PROBLEMÁTICOS. | as enacted, in force 31 May 2023 |
| `ley-3812-a/` | Ley 3812-A: RATIFICA DECRETO 2664/22. | as enacted, in force 28 May 2023 |
| `ley-3810-a/` | Ley 3810-A: EXPROPIA INMUEBLE. | as enacted, in force 28 May 2023 |
| `ley-3806-c/` | Ley 3806-C: RÉGIMEN ESPECIAL PARA PERSONAS HUMANAS DE TALLA BAJA POR ADEE. | as enacted, in force 28 May 2023 |
| `ley-3800-a/` | Ley 3800-A: RATIFICA DECRETO 135/23 - VALOR ÍNDICE DOCENTE -. | as enacted, in force 28 May 2023 |
| `ley-3798-a/` | Ley 3798-A: PROGRAMA DE CAPACITACIÓN, ROTATIVA, ANUAL Y OBLIGATORIA PARA PREVENIR CONFLICTOS LABORALES. | as enacted, in force 28 May 2023 |
| `ley-3796-a/` | Ley 3796-A: CREA SERVICIO DE ACCESO DE LA CIUDADANÍA A NORMAS EN LENGUAJE CLARO. | as enacted, in force 28 May 2023 |
| `ley-3795-a/` | Ley 3795-A: CREA FISCALÍAS DE INVESTIGACIÓN PENAL. | as enacted, in force 28 May 2023 |
| `ley-3791-c/` | Ley 3791-C: DÍA DEL AGENTE DE FISCALÍA DE ESTADO DE LA PROVINCIA DEL CHACO. | as enacted, in force 28 May 2023 |
| `ley-3781-a/` | Ley 3781-A: RESOLUCIÓN 5529/22 DEL DIRECTORIO DEL IN.S.S.SE.P. - BONIFICACIÓN TRABAJADORES DE LA SEGURIDAD SOCIAL - RATIFICA DECRETO 3258/22. | as enacted, in force 28 May 2023 |
| `ley-3780-a/` | Ley 3780-A: RATIFICA DECRETO 468/23 - INCREMENTOS EN LAS ESCALAS SALARIALES VIGENTES DEL ESCALAFÓN GENERAL - LEY 196-A (ANTES LEY 1276)-. | as enacted, in force 28 May 2023 |
| `ley-3783-a/` | Ley 3783-A: INCREMENTO SALARIAL SOBRE LOS HABERES BÁSICOS DEL PERSONAL COMPRENDIDO EN LA LEY 178-J (ANTES LEY 1134)-, POLICÍA PROVINCIAL Y LA LEY 2855-J-, SERVI… | as enacted, in force 19 May 2023 |
| `ley-3782-a/` | Ley 3782-A: PERSONAL DOCENTE INCREMENTOS ESCALONADOS DEL VALOR ÍNDICE UNO (1) - RATIFICA DECRETO 460/23. | as enacted, in force 19 May 2023 |
| `ley-3793-g/` | Ley 3793-G: ADHIERE AL DÍA NACIONAL DE LA PUERICULTURA. | as enacted, in force 12 May 2023 |
| `ley-3790-a/` | Ley 3790-A: TRANSFIERE INMUEBLE. | as enacted, in force 3 May 2023 |
| `ley-3784-a/` | Ley 3784-A: INCREMENTOS SALARIALES P LEG., AUT. SUP., CONTADURÍA Y TESORERÍA GRAL. DE LA PROVINCIA, DCCIÓN DE AERONÁUTICA , ADM.PORTUARIA- PUERTO DE BARRANQUERA… | as enacted, in force 3 May 2023 |
| `ley-3761-g/` | Ley 3761-G: DÍA PROVINCIAL DEL SÍNDROME DE CORNELIA DE LANGE. | as enacted, in force 23 April 2023 |
| `ley-3744-f/` | Ley 3744-F: PRESUPUESTO GENERAL DE LA PROVINCIA PARA EL EJERCICIO 2023. | as enacted, in force 1 January 2023 |
| `ley-3735-g/` | Ley 3735-G: DÍA PROVINCIAL DEL DONANTE DE MÉDULA ÓSEA. | as enacted, in force 25 December 2022 |
| `ley-3711-a/` | Ley 3711-A: MODIFICA LA LEY 3633-A. | as enacted, in force 9 November 2022 |
| `ley-3605-g/` | Ley 3605-G: ADHIERE LA PROVINCIA DEL CHACO A LA LEY NACIONAL 27.071. | as enacted, in force 10 July 2022 |
| `ley-3456-s/` | Ley 3456-S: PROGRAMA DE EMPODERAMIENTO FEMENINO EN EL ÁMBITO DEPORTIVO | as enacted, in force 9 January 2022 |
| `ley-3450-a/` | Ley 3450-A: RÉGIMEN DE REGULARIZACIÓN EXCEPCIONAL DE OBLIGACIONES TRIBUTARIAS. | as enacted, in force 19 November 2021 |
| `ley-3187-a/` | Ley 3187-A: REINSTAURA POR EL TERMINO DE DOS (2) AÑOS LA LEY 2102-A (ANTES LEY 7188). | as enacted, in force 30 September 2020 |
| `ley-3159-t/` | Ley 3159-T: SISTEMA INTEGRADO DE SEGUROS AGROPECUARIOS (SISA). | as enacted, in force 4 September 2020 |
| `ley-3111-f/` | Ley 3111-F: PRESUPUESTO PROVINCIAL PERIODO 2020 | as enacted, in force 17 January 2020 |
| `ley-2909-h/` | Ley 2909-H: MODIFICA EL HABER MENSUAL DEL RETIRO VOLUNTARIO Y MÓVIL S/ LEY 4923. | as enacted, in force 2 November 2018 |
| `ley-2861-a/` | Ley 2861-A: DISPONE UN IMPORTE FIJO PARA EL PERSONAL ACTIVO COMPRENDIDO EN LA LEY 196-A (ANTES LEY 1276) | as enacted, in force 19 August 2018 |
| `ley-2724-a/` | Ley 2724-A: ESTABLECE INCREMENTOS ACUMULATIVOS A LAS ESCALAS SALARIALES MESES DE JULIO, AGOSTO Y SETIEMBRE 2017 PARA DIRECCIÓN DE AERONÁUTICA | as enacted, in force 17 January 2018 |
| `ley-2702-g/` | Ley 2702-G: DIA PROVINCIAL DEL BASTÓN BLANCO | as enacted, in force 7 January 2018 |
| `ley-2706-a/` | Ley 2706-A: PRORROGA POR EL TERMINO DE DOS (2) AÑOS LA VIGENCIA DE LA LEY 2110-A (ANTES LEY 7211) | as enacted, in force 10 December 2017 |
| `ley-2684-j/` | Ley 2684-J: INSTITUYE COMO "DIA PROVINCIAL DE LA LUCHA CONTRA EL NARCOTRAFICO" EL 21 DE AGOSTO DE CADA AÑO | as enacted, in force 29 October 2017 |
| `ley-2668-a/` | Ley 2668-A: INCREMENTO SALARIAL A PARTIR DEL 1º DE MARZO DE 2017 P/ PERSONAL PODER JUDICIAL | as enacted, in force 6 October 2017 |
| `ley-2659-a/` | Ley 2659-A: FÍJASE EL VALOR ÍNDICE UNO (1) P/ DETERMINAR LAS REMUNERACIONES DEL PERSONAL DOCENTE COMPRENDIDO EN LA LEY 647-E | as enacted, in force 3 September 2017 |
| `ley-2615-a/` | Ley 2615-A: EXPROPIA INMUEBLE EN LA LOCALIDAD DE PUERTO TIROL P/ SER ADJUDICADOS A SUS OCUPANTES | as enacted, in force 30 July 2017 |
| `ley-2461-t/` | Ley 2461-T: ADHESION L.N. 27.214 - LEY DE PROMOCION DE LA SEGURIDAD VIAL | as enacted, in force 14 December 2016 |
| `ley-2475-g/` | Ley 2475-G: ADHESION L.N. 26.946 =  EL DIA 23 DE JULIO DE CADA AÑO "DIA DEL DIRECTOR/A AUDIOVISUAL" | as enacted, in force 14 August 2016 |
| `ley-2474-j/` | Ley 2474-J: CREA EL CENTRO DE ATENCION Y ASESORAMIENTO A MUJERES VICTIMAS DE VIOLENCIA | as enacted, in force 12 August 2016 |
| `ley-2472-a/` | Ley 2472-A: PREMIO PROVINCIAL A LA CALIDAD PARA EL SECTOR PUBLICO Y PRIVADO | as enacted, in force 5 August 2016 |
| `ley-2468-g/` | Ley 2468-G: IMPLEMENTA JORNADAS DE VACUNACIÓN GRATUITA Y VOLUNTARIA EN LA ADMIN. PÚBLICA | as enacted, in force 5 August 2016 |
| `ley-2465-g/` | Ley 2465-G: DONACIÓN CELULAS PROGENITORAS HEMATOPOYÉTICAS DE SANGRE CORDÓN UMBI. Y PLACENTA | as enacted, in force 5 August 2016 |
| `ley-2471-f/` | Ley 2471-F: PRORROGA HASTA EL 31/12/2016, A PARTIR DE SU VENCIMIENTO, LEY Nº 2425-F (ANTES LEY 7751) | as enacted, in force 15 July 2016 |
| `ley-2460-g/` | Ley 2460-G: CONTROL OFTALMOLÓGICO EN LA PRIMERA INFANCIA | as enacted, in force 8 July 2016 |
| `ley-2454-a/` | Ley 2454-A: INCREMENTO SALARIAL PERSONAL PODER JUDICIAL, TRIB. ELECTORAL Y CONS. DE LA MAGISTRATURA Y JURADO DE ENJUICIAMIENTO | as enacted, in force 12 June 2016 |
| `ley-2451-a/` | Ley 2451-A: FIJA VALOR INDICE UNO (1) P/ DETERMINAR REMUNERACIONES PERSONAL DOCENTE L. 647- E (Antes L.3529) | as enacted, in force 12 June 2016 |
| `ley-2452-a/` | Ley 2452-A: INCREMENTO SALARIAL TRIBUNAL DE CUENTAS, A PARTIR DEL 01/03/16 Y 01/07/16 | as enacted, in force 12 June 2016 |
| `ley-2450-a/` | Ley 2450-A: INCREMENTO ESCALA SALARIAL ESCALAFON PERSONAL ESPEC. DCCION. DE AERONAUTICA -LEY 1973-A (Antes Ley 6879)-, A PARTIR DEL 01/03/16 Y 01/07/16 | as enacted, in force 12 June 2016 |
| `ley-2449-a/` | Ley 2449-A: INCREMENTO SALARIAL FISCALIA DE ESTADO, A PARTIR DEL 01/03/16 Y 01/07/16 | as enacted, in force 12 June 2016 |
| `ley-2447-d/` | Ley 2447-D: CAMPAÑAS SOLIDARIAS PARA DONAR SU VUELTO EN COMERCIOS DE LA PROVINCIA | as enacted, in force 10 June 2016 |
| `ley-2445-s/` | Ley 2445-S: INSTITÚYESE COMPETENCIA ATLÉTICA ANUAL "MARATON DE LA PROVINCIA DEL CHACO" | as enacted, in force 10 June 2016 |
| `ley-2443-a/` | Ley 2443-A: CREA EL FORO PERMANENTE EN DEFENSA DEL USUARIO VIAL (PEAJE EN CORREDORES VIALES). | as enacted, in force 20 May 2016 |
| `ley-2442-d/` | Ley 2442-D: NORMAS PARA ATENCION USUARIOS EN EST. COMERCIALES, BANCOS, ETC. LAPSO 30 MINUTOS | as enacted, in force 20 May 2016 |
| `ley-2376-l/` | Ley 2376-L: REGIMEN DE LAS AGENCIAS DE MODELAJE E IMAGEN PUBLICIT., PROMOCIÓN Y DEGUSTACION PUBLICITARIA. | as enacted, in force 13 January 2016 |
| `ley-2405-j/` | Ley 2405-J: PROTOCOLO DE REQUISA DE PERSONAS EN LA VIA PÚBLICA EN LA COMISION DE DELITOS O FALTAS | as enacted, in force 8 January 2016 |
| `ley-2406-p/` | Ley 2406-P: CREANSE LOS CONGLOMERADOS PRODUCTIVOS EN LOS MUNICIPIOS DE 2a Y 3a CATEGORIA | as enacted, in force 8 January 2016 |
| `ley-2404-j/` | Ley 2404-J: PROTOCOLO DE REQUISA A FAMILIARES Y/O VISITAS  A PERSONAS  PRIVADAS DE SU LIBERTAD | as enacted, in force 8 January 2016 |
| `ley-2402-g/` | Ley 2402-G: TARIFA ESPECIAL PARA USUARIOS DENOMINADOS "ELECTRODEPENDIENTES POR CUESTIONES DE SALUD" | as enacted, in force 8 January 2016 |
| `ley-2422-a/` | Ley 2422-A: LICENCIA A DIPUTADO PARA OCUPAR CARGO O FUNCIÓN PÚBLICA | as enacted, in force 25 December 2015 |
| `ley-2386-j/` | Ley 2386-J: OBLIGACION DE INSTALAR SANITARIOS EN ENTIDADES ESTATAL, CORREOS, TELEFONIA, ETC. | as enacted, in force 18 December 2015 |
| `ley-2388-e/` | Ley 2388-E: DECLARA PATRIMONIO HISTORICO CULTURAL ESCUELA Nº 536 "MANUEL BELGRANO" EN LA LEONESA | as enacted, in force 2 December 2015 |
| `ley-2381-e/` | Ley 2381-E: INSTITUYE EL DIA 6 DE ENERO DE CADA AÑO COMO "DIA DEL AFRODESCENDIENTE CHAQUEÑO Y DE LA CULTURA AFROLITORALEÑA" | as enacted, in force 2 December 2015 |
| `ley-2393-x/` | Ley 2393-X: CONVENIO SUSCRIPTO EN EL MARCO DEL PROGRAMA FEDERAL DE DESENDEUDAMIENTO DE LAS PCIAS. ARGENTINAS. | as enacted, in force 29 November 2015 |
| `ley-2379-i/` | Ley 2379-I: ADHESION L.N. 27.118 = AGRICULTURA FAMILIAR, CAMPESINA E INDÍGENA | as enacted, in force 18 November 2015 |
| `ley-2378-g/` | Ley 2378-G: SISTEMA PROVINCIAL DE SALUD PUBLICA | as enacted, in force 6 November 2015 |
| `ley-2373-e/` | Ley 2373-E: INSTITUYE EN LA PCIA. EL 9 DE DICIEMBRE DE CADA AÑO "DIA DE LA REIVINDICACION  DE LOS DERECHOS HUMANOS EN DEMOCRACIA" | as enacted, in force 4 November 2015 |
| `ley-2371-g/` | Ley 2371-G: CREA EL PROGRAMA DE CANCER DE COLON Y RECTO. | as enacted, in force 4 November 2015 |
| `ley-2367-g/` | Ley 2367-G: CARRERA SANITARIA PROVINCIAL | current text only, as of 27 September 2018 |
| `ley-2361-g/` | Ley 2361-G: INSTITUYESE EL DIA 29 DE OCTUBRE DE CADA AÑO COMO "DIA PCIAL. DEL ACCIDENTE CEREBRO VASCULAR (A.C.V.) | as enacted, in force 25 September 2015 |
| `ley-2359-g/` | Ley 2359-G: ADHESION L.N. 27.113 - DECLARA DE INT.NAC. Y ESTRATEG. LA ACTIVID. DE LOS LABORATORIOS | as enacted, in force 20 September 2015 |
| `ley-2360-g/` | Ley 2360-G: SEGURO PÚBLICO PROVINCIAL DE SALUD | as enacted, in force 11 September 2015 |
| `ley-2355-g/` | Ley 2355-G: ADHESION L.N. 26.862 - REPRODUCCION MEDICAMENTE ASISTIDA | as enacted, in force 2 September 2015 |
| `ley-2339-g/` | Ley 2339-G: ADHESION L.N. 26.657 - LEY NACIONAL DE SALUD MENTAL | as enacted, in force 14 August 2015 |
| `ley-2342-f/` | Ley 2342-F: REGIMEN DE REGULARIZACION TRIBUTARIA PARA COOPERATIVAS AGROPECUARIAS | as enacted, in force 7 August 2015 |
| `ley-2343-p/` | Ley 2343-P: EXCEPTÚA DEL PAGO DEL IMPUESTO S/INGRESOS BRUTOS Y ADIC. SECHEEP Y SAMEEP | as enacted, in force 7 August 2015 |
| `ley-2334-g/` | Ley 2334-G: CAMPAÑA DE DONACIÓN DE MÉDULA ÓSEA O CÉLULAS PROGENITORAS HEMATOPOYÉTICAS | as enacted, in force 5 August 2015 |
| `ley-2319-s/` | Ley 2319-S: ADHESION L.N. 27.098 = REGIMEN DE PROMOCION DE LOS CLUBES DE BARRIO Y PUEBLO | as enacted, in force 12 July 2015 |
| `ley-2317-e/` | Ley 2317-E: ADHESION L.N. 27.116 = DECLARA HEROE NACIONAL POST MORTEN ANDRÉS GUACURARÍ | as enacted, in force 1 July 2015 |
| `ley-2242-r/` | Ley 2242-R: PROTECCION  Y BIENESTAR DE ANIMALES | as enacted, in force 24 June 2015 |
| `ley-2311-a/` | Ley 2311-A: INSTITUYE EN LA PCIA. EL DIA 15 DE ABRIL DE CADA AÑO COMO EL "DIA DE LA PROTECCION RADIOLÓGICA" | as enacted, in force 21 June 2015 |
| `ley-2305-g/` | Ley 2305-G: ADHESION L.N. 27.130 | as enacted, in force 12 June 2015 |
| `ley-2303-g/` | Ley 2303-G: ADHESION L.N.26.872 - PATOLOGIA MAMARIA- CIRUGIA RECONSTRUCTIVA-COBERTURA | as enacted, in force 7 June 2015 |
| `ley-2299-e/` | Ley 2299-E: CREA PROGRAMA DE PRIMEROS AUXILIOS EN ESTABLECIMIENTOS EDUCATIVOS DE LA PCIA. | as enacted, in force 31 May 2015 |
| `ley-2290-g/` | Ley 2290-G: ADHESION A LA LEY NACIONAL 25.929 -  PARTO HUMANIZADO | as enacted, in force 20 May 2015 |
| `ley-2293-e/` | Ley 2293-E: ORGANIZACION TALLERES ANUALES EN EST. EDUCACIONALES S/ SITUACIONES LIMITES | as enacted, in force 20 May 2015 |
| `ley-2289-g/` | Ley 2289-G: PROGRAMA DE PREVENCIÓN DE LA CEGUERA DEL PREMATURO | as enacted, in force 20 May 2015 |
| `ley-2288-e/` | Ley 2288-E: CREA MUESTRA PCIAL. ITINERANTE "HEROES DE MALVINAS" | as enacted, in force 6 May 2015 |
| `ley-2287-e/` | Ley 2287-E: CREA PROGRAMA PCIAL. "MALVINAS ARGENTINAS" EN TODOS LOS ESTABLEC. EDUCATIVOS | as enacted, in force 6 May 2015 |
| `ley-2284-f/` | Ley 2284-F: APRUEBA CONVENIO SUSCRIPTO 30/03/15, PROGRAMA FEDERAL DE DESENDEUDAMIENTO DE LAS PROVINCIAS ARGENTINAS | as enacted, in force 15 April 2015 |
| `ley-2281-a/` | Ley 2281-A: CREA CARGOS DE DEFENSOR GENERAL Y DEFENSOR GENERAL ADJUNTO PODER JUDICIAL | as enacted, in force 15 April 2015 |
| `ley-2279-e/` | Ley 2279-E: CREA EL MUSEO DE LA EDUCACION EN LA PROVINCIA | as enacted, in force 25 January 2015 |
| `ley-2274-e/` | Ley 2274-E: ADHESION L.N. 27.002 - DIA NACIONAL DE LA JUVENTUD | as enacted, in force 21 January 2015 |
| `ley-2265-a/` | Ley 2265-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 2 January 2015 |
| `ley-2262-e/` | Ley 2262-E: ADHESION L.N.26.985 - "RED MUNDIAL DE ESCUELAS SCHOLAS OCURRENTES" | as enacted, in force 31 December 2014 |
| `ley-2251-g/` | Ley 2251-G: ADHESION L.N. 26.905 - CONSUMO DE SODIO. VALORES MAXIMOS. | as enacted, in force 28 November 2014 |
| `ley-2249-f/` | Ley 2249-F: CREA SISTEMA DE PROMOCION Y DESARROLLO DE LA ECONOMIA SOCIAL Y SOLIDARIA DE LA PROVINCIA | as enacted, in force 26 November 2014 |
| `ley-2246-g/` | Ley 2246-G: ADHESION L.N.26.956 - DIA NACIONAL DE LA SALUD MENTAL | as enacted, in force 14 November 2014 |
| `ley-2240-g/` | Ley 2240-G: PREMIO PROVINCIAL ANUAL AL MEDICO DESTACADO DEL AÑO | as enacted, in force 31 October 2014 |
| `ley-2239-g/` | Ley 2239-G: INSTITUYE EL 21 DE SEPTIEMBRE DE CADA AÑO "DIA PCIAL. DE CONCIENTIZACION  Y LUCHA CONTRA EL ALZHEIMER" | as enacted, in force 17 October 2014 |
| `ley-2238-g/` | Ley 2238-G: ADHESION L.N. 26.928 -  SISTEMA DE PROTECCION INTEGRAL PARA PERSONAS TRASPLANTADAS | as enacted, in force 17 October 2014 |
| `ley-2235-g/` | Ley 2235-G: ADHESION L.N. 26.906 - REGIMEN DE TRAZABILIDAD Y VERIFICACION DE APTITUD TECNICA DE LOS PRODUCTOS MEDICOS ACTIVOS DE SALUD EN USO | as enacted, in force 10 October 2014 |
| `ley-2225-o/` | Ley 2225-O: CODIGO PROCESAL LABORAL DE LA PROVINCIA DEL CHACO - DEROGA LEYES 2383 Y 4063 | as enacted, in force 21 September 2014 |
| `ley-2229-g/` | Ley 2229-G: INSTITUYE LA PRIMER SEMANA DE MARZO DE CADA AÑO COMO LA "SEMANA DE LA CONCIENCIACION DE LA ENDOMETRIOSIS" | as enacted, in force 12 September 2014 |
| `ley-2224-g/` | Ley 2224-G: PROGRAMA PCIAL. DE PRODUCCION PUBLICA DE MEDICAMENTOS | as enacted, in force 24 August 2014 |
| `ley-2223-a/` | Ley 2223-A: ADHESION L.N. 26.874 - CREACION DEL CONSEJO FEDERAL DE LEGISLADORES COMUNALES | as enacted, in force 24 August 2014 |
| `ley-2215-a/` | Ley 2215-A: NUEVA ESCALA SALARIAL TRIBUNAL ELECTORAL Y CONSEJO DE LA MAGISTRATURA Y JUR. DE ENJ. | as enacted, in force 13 August 2014 |
| `ley-2210-g/` | Ley 2210-G: TODO SUPERMERCADOS O HIPERMERCADOS DEBERAN POSEER GÓNDOLAS C/PROD. P/CELIACO | as enacted, in force 13 August 2014 |
| `ley-2207-g/` | Ley 2207-G: CELEBRAR CONTRATO DE LOCACION DE SERVICIOS PROFESIONALES DE LA SALUD | as enacted, in force 13 August 2014 |
| `ley-2175-g/` | Ley 2175-G: EJERCICIO DE LA ENFERMERIA - DEROGA LEY Nº 3520 | as enacted, in force 13 August 2014 |
| `ley-2176-g/` | Ley 2176-G: CREACION DEL COLEGIO DE ENFERMERIA DEL CHACO | as enacted, in force 13 August 2014 |
| `ley-2220-g/` | Ley 2220-G: ADHESION L.N. 26.873 - LACTANCIA MATERNA, PROMOCION Y CONCIENTIZACION PUBLICA | as enacted, in force 10 August 2014 |
| `ley-2216-g/` | Ley 2216-G: INSTITUYESE EN LA PROVINCIA AL 2 DE ABRIL COMO "DIA PROVINCIAL DE LA CONCIENTIZACION SOBRE EL AUTISMO" | as enacted, in force 8 August 2014 |
| `ley-2205-g/` | Ley 2205-G: ADHESION L.N. 26.926 -DIA NACIONAL DE LA LUCHA CONTRA EL SINDROME UREMICO HEMOLÍTICO | as enacted, in force 11 June 2014 |
| `ley-2200-g/` | Ley 2200-G: INSTITUYE EL DIA 5 DE MAYO DE CADA AÑO COMO "DIA PROVINCIAL DE LA ENFERMEDAD CELIACA" | as enacted, in force 1 June 2014 |
| `ley-2197-g/` | Ley 2197-G: OBLIGATORIEDAD EN LA PROVINCIA DE LA LIBRETA DEPORTIVA DE PREVENCION Y SALUD. | as enacted, in force 1 June 2014 |
| `ley-2191-g/` | Ley 2191-G: ADHESION L.N. 26.914 MODIFIC. DE LA L.N. 23.753 | as enacted, in force 28 May 2014 |
| `ley-2164-r/` | Ley 2164-R: SISTEMA DE INFORMACION AMBIENTAL DE LA PROVINCIA DEL CHACO | as enacted, in force 16 April 2014 |
| `ley-2167-g/` | Ley 2167-G: PROGRAMA DE PREVENC. PERSONAS EN SIT. DE CRISIS Y RIESGO SUICIDA Y DE APOYO FAMILIAR | as enacted, in force 7 March 2014 |
| `ley-2163-g/` | Ley 2163-G: EJERCICIO DE LA PROFESIÓN DE LA INSTRUMENTACION QUIRURGICA | as enacted, in force 31 January 2014 |
| `ley-2174-r/` | Ley 2174-R: GESTION  Y TRATAMIENTO DE LOS RESIDUOS DE APARATOS ELECTRICOS Y ELECTRONICOS (RAEE) | as enacted, in force 29 January 2014 |
| `ley-2166-r/` | Ley 2166-R: SISTEMA DE RECOLECCION DE AGUAS DE LLUVIA - AGUAS RECUPERADAS P/USO DOMICILIARIO | as enacted, in force 19 January 2014 |
| `ley-2179-f/` | Ley 2179-F: AUTORIZA AL P.E. CONTRAER PRESTAMOS POR HASTA U$S 50.000.000,- P/PROYECTOS PROSAP | as enacted, in force 17 January 2014 |
| `ley-2162-g/` | Ley 2162-G: CREA EL  "REGISTRO PROVINCIAL DE MADRES DONANTES DE LECHE" | as enacted, in force 27 December 2013 |
| `ley-2157-a/` | Ley 2157-A: REGIMEN SANCIONATORIO ESPECIAL DEL INST. PCIAL. P/LA INCLUSION DE PERSONAS CON DISCAPACIDAD | as enacted, in force 15 December 2013 |
| `ley-2159-r/` | Ley 2159-R: TRANSFIERE AL ESTADO NACIONAL LA RESERVA NATURAL DE RECURSOS "LA FIDELIDAD" | as enacted, in force 1 December 2013 |
| `ley-2116-r/` | Ley 2116-R: INSTITUYE DEL 1º AL 7 DE JUNIO DE CADA AÑO "LA SEMANA DEL AMBIENTE" | as enacted, in force 1 December 2013 |
| `ley-2122-e/` | Ley 2122-E: CREA EN EL SISTEMA EDUCATIVO PCIAL. EL PROGRAMA TRAYECTORIAS ESCOLARES | as enacted, in force 20 November 2013 |
| `ley-2149-g/` | Ley 2149-G: OBLIGATORIEDAD DEL ESTUDIO DE TAMIZAJE DE CARDIOPATIAS EN RECIEN NACIDO | as enacted, in force 8 November 2013 |
| `ley-2153-r/` | Ley 2153-R: LEY DE AGRICULTURA FAMILIAR | as enacted, in force 3 November 2013 |
| `ley-2144-g/` | Ley 2144-G: ASISTENCIA SANITARIA DE EQUINOS, CANES Y FELINOS DOMESTICOS Y DOMESTICOS CALLEJEROS | as enacted, in force 27 September 2013 |
| `ley-2130-r/` | Ley 2130-R: CONVENIO C/AGENCIA NACIONAL DE PROMOCION CIENTIFICA Y TECNOLOGICA S/CONTRATO DE CREDITO | as enacted, in force 2 August 2013 |
| `ley-2052-e/` | Ley 2052-E: CREA LA SECCION DE GABINETE INTERDISCIPLINARIO EN C/U DE LAS REGIONES EDUCATIVAS | as enacted, in force 14 July 2013 |
| `ley-2119-e/` | Ley 2119-E: DECLARA EL DIA 4 DE JULIO DE CADA AÑO EL "DIA DEL ARTESANO CHAQUEÑO" | as enacted, in force 21 June 2013 |
| `ley-2118-a/` | Ley 2118-A: CREA EN LA PROVINCIA LA CEDULA ADMINISTRATIVA ELECTRONICA | as enacted, in force 19 June 2013 |
| `ley-2113-q/` | Ley 2113-Q: OBLIGATORIEDAD DE DEBATES PREELECTORALES PUBLICOS ENTRE CANDIDATOS | as enacted, in force 7 June 2013 |
| `ley-2117-e/` | Ley 2117-E: ADHESION L.N.26.819 - DECLARA "DIA INTERNACIONAL DE LA PAZ" | as enacted, in force 29 May 2013 |
| `ley-2115-f/` | Ley 2115-F: REGIMEN DE BONIFICACION IMPUESTO INMOBILIARIO RURAL AÑOS 2013 Y 2014 | as enacted, in force 29 May 2013 |
| `ley-2112-e/` | Ley 2112-E: EL 23 DE SEPTIEMBRE DE C/ AÑO "DIA PCIAL. C/LA  EXPLOTACION SEXUAL Y TRATA DE MUJERES, NIÑAS Y NIÑOS" | as enacted, in force 17 May 2013 |
| `ley-2111-g/` | Ley 2111-G: ADHESION L.N. 26.835 - PROMOCION Y CAPACIT. TECN. DE REANIMACION CARDIOPULMONAR | as enacted, in force 17 May 2013 |
| `ley-2109-e/` | Ley 2109-E: ADHESION  L.N.26.754 - "DIA DEL LECTOR" | as enacted, in force 12 May 2013 |
| `ley-2027-g/` | Ley 2027-G: REGIMEN DEL EJERCICIO PROFESIONAL DE LA TERAPIA  OCUPACIONAL | as enacted, in force 8 May 2013 |
| `ley-2104-e/` | Ley 2104-E: INSTITUYESE EL 28 DE DICIEMBRE DE CADA AÑO "DIA DEL INSPECTOR DE TRANSITO MUNICIPAL" | as enacted, in force 26 April 2013 |
| `ley-2103-a/` | Ley 2103-A: NUEVAS ESCALAS SALARIALES PERSONAL PODER JUDICIAL, TRIBUNAL ELECTORAL, CONSEJO DE LA MAGISTRATURA Y RETIRO | as enacted, in force 19 April 2013 |
| `ley-2096-g/` | Ley 2096-G: CREA EN LA PCIA. EL REGISTRO UNICO DE CARDIOPATIA CONGENITA | as enacted, in force 8 March 2013 |
| `ley-2095-d/` | Ley 2095-D: OBLIGATORIEDAD EXHIBIR CARTEL CON LA INSCRIPCION "0800-444-3346" SUBS. COMER. | as enacted, in force 8 March 2013 |
| `ley-2094-g/` | Ley 2094-G: ECOGRAFIAS FETALES CON EVALUCIÓN CARDIACA | as enacted, in force 8 March 2013 |
| `ley-2092-a/` | Ley 2092-A: CREA CAMARA DE APELACIONES DEL TRABAJO EN SAENZ PEÑA | as enacted, in force 6 March 2013 |
| `ley-2093-r/` | Ley 2093-R: PROGRAMA DE ARBOLADO PUBLICO DE LA PROVINCIA DEL CHACO | as enacted, in force 6 March 2013 |
| `ley-2091-g/` | Ley 2091-G: PROGRAMA PCIAL. DE PREVENCION Y ASISTENCIA SANITARIA INTEGRAL DE LAS ADICCIONES | as enacted, in force 27 February 2013 |
| `ley-2088-c/` | Ley 2088-C: ASOCIACIONES CIVILES DE BOMBEROS VOLUNTARIOS - DEROGA LA LEY 5110 | as enacted, in force 22 February 2013 |
| `ley-2090-f/` | Ley 2090-F: MODIFICA ARTICULO 1º E INCORPORA COMO ARTICUL0 2º DE LA LEY 102-K (ANTES LEY 597) | as enacted, in force 22 February 2013 |
| `ley-2086-c/` | Ley 2086-C: PROTECCION INTEGRAL DE DERECHOS DE NIÑAS, NIÑOS Y ADOLESCENTES - MODIF. L.4369 Y 5681 | as enacted, in force 17 February 2013 |
| `ley-2099-r/` | Ley 2099-R: DECLARA RESERVA NATURAL CULTURAL "PIGÜEN N'ONAXA" TERRENOS LOCALIDAD GANCEDO | as enacted, in force 25 January 2013 |
| `ley-2080-r/` | Ley 2080-R: CREA EL REGISTRO PCIAL. DE PRODUCTORES AGRICOLAS (REPPA) | as enacted, in force 25 January 2013 |
| `ley-2079-r/` | Ley 2079-R: REGIMEN DE SANCIONES PARA LA ACTIVIDAD FORESTAL SEGUN LAS LEYES 350-R  (Antes Ley 2386) y 1762-R (Antes Ley 6409). | as enacted, in force 23 January 2013 |
| `ley-2076-e/` | Ley 2076-E: INSTITUYESE EL "PREMIO A LA MEJOR INICIATIVA DE FOMENTO DE LA LECTURA Y ESCRITURA" | as enacted, in force 4 January 2013 |
| `ley-2074-a/` | Ley 2074-A: CREA TRES FISCALIAS DE INVESTIGACION PRIMERA CIRCUNSCRIPCION JUDICIAL EN RCIA. | as enacted, in force 4 January 2013 |
| `ley-2077-f/` | Ley 2077-F: MODIFICA VARIOS ARTÍCULOS DE LA LEY 83-F. RÉGIMEN DE INCENTIVO AL CUMPLIMIENTO FISCAL -PEQUEÑAS Y Y MEDIANAS EMPRESAS. SUSPÉNDASE, A PARTIR DEL 1º/… | as enacted, in force 26 December 2012 |
| `ley-2072-j/` | Ley 2072-J: CREA EN EL PORTAL-WWW.CHACO.GOV.AR- LINK CON LINEAS GRATUITAS DE ATENCION A LAS VICTIMAS DE VIOLENCIA DE GENERO | as enacted, in force 21 December 2012 |
| `ley-2068-d/` | Ley 2068-D: PROCEDIMIENTO PARA LA EFECTIVA IMPLEMENTACION DE LOS DERECHOS DEL CONSUMIDOR | as enacted, in force 10 December 2012 |
| `ley-2069-a/` | Ley 2069-A: INSTITUTO PROVINCIAL DE ADMINISTRACIÓN PÚBLICA DEL CHACO | as enacted, in force 19 December 2012 |
| `ley-2066-g/` | Ley 2066-G: SISTEMA PROVINCIAL DE CUIDADOS PALIATIVOS | as enacted, in force 16 December 2012 |
| `ley-2059-g/` | Ley 2059-G: OBLIGATORIEDAD DE CONTAR CON SILLAS ADECUADAS PARA OBESOS | as enacted, in force 25 November 2012 |
| `ley-2056-g/` | Ley 2056-G: INSTITUYE EL 2 DE JUNIO DE CADA AÑO "DIA DE LA PERSONA CON MIASTENIA GRAVIS" Y LA 1RA. SEMANA DE JUNIO COMO "LA SEMANA DE LUCHA CONTRA LA MIASTENIA … | as enacted, in force 25 November 2012 |
| `ley-2038-g/` | Ley 2038-G: GUIA TECNICA P/ATENCION INTEGRAL DE LOS ABORTOS NO PUNIBLES | as enacted, in force 14 October 2012 |
| `ley-2039-e/` | Ley 2039-E: PREMIO ANUAL DE RECONOCIMIENTO A LA LABOR MÁS DESTACADA EN  LA ERRADICACIÓN DE LA VIOLENCIA DE GÉNERO DE LA CÁMARA DE DIPUTADOS DE LA PROVINCIA DEL … | as enacted, in force 10 October 2012 |
| `ley-2035-g/` | Ley 2035-G: PROHIBICION DEL COBRO DEL "PLUS". INCORPORA INC.F) AL ART.15 DEL D.L. Nº527/55 | as enacted, in force 7 October 2012 |
| `ley-2026-r/` | Ley 2026-R: LEY DE BIOCIDAS - DEROGA LEY 3378 | as enacted, in force 24 August 2012 |
| `ley-2020-i/` | Ley 2020-I: PROMOCIÓN Y RADICACIÓN  DE LAS INDUSTRIAS CULTURALES | as enacted, in force 1 August 2012 |
| `ley-2008-r/` | Ley 2008-R: REGLAMENTO PARA LA PROTECCIÓN AMBIENTAL, EXPLORACION, PERFORAC. Y PROD. PETROLERA | as enacted, in force 1 June 2012 |
| `ley-2010-f/` | Ley 2010-F: EL PODER EJECUTIVO CONTRAERA EMPRÉSTITOS POR HASTA LA SUMA DE $250.000.000,- | as enacted, in force 25 May 2012 |
| `ley-2006-a/` | Ley 2006-A: MODIFICA INC.A) ART.4º, INCORP. INC.J) APART.II ART.7º LEY 1092 (ANTES LEY 4787) Y MOD. ART.6º 843-A( ANTES LEY 4190). DEFENSOR DEL PUEBLO. ESTRUCTU… | as enacted, in force 25 May 2012 |
| `ley-2007-f/` | Ley 2007-F: CRÉDITO PÚBLICO PARA EXPLORACIÓN DE HIDROCARBUROS | as enacted, in force 13 May 2012 |
| `ley-2001-a/` | Ley 2001-A: CREA CARGO DE ASESOR DE MENORES SEXTA CIRCUNSCRIPCION JUDIC. EN J.J.CASTELLI | as enacted, in force 29 April 2012 |
| `ley-1984-a/` | Ley 1984-A: CREA PROGRAMA DE ASISTENCIA INTEGRAL P/PERSONAS PRIVADAS DE LA LIBERTAD | as enacted, in force 10 February 2012 |
| `ley-1998-a/` | Ley 1998-A: CREA CARGOS TEMPORARIOS DE GESTION CULTURAL - ARTISTICA. INST. DE CULTURA | as enacted, in force 25 January 2012 |
| `ley-1995-f/` | Ley 1995-F: RENDICION FONDOS ANTICIPADOS AUTORIDADES DE LA CAMARA DE DIPUTADOS | as enacted, in force 25 January 2012 |
| `ley-1994-g/` | Ley 1994-G: ADHESION L.N. 26.529 - DERECHOS DEL PACIENTE, HISTORIA CLINICA Y CONSENT. INFORM. | as enacted, in force 25 January 2012 |
| `ley-1991-g/` | Ley 1991-G: ADHIERE L.N. 26.688 - PRODUCCION PUBLICA DE MEDICAMENTOS | as enacted, in force 25 January 2012 |
| `ley-1993-f/` | Ley 1993-F: ADHESION L.N. 26.355 - MARCAS COLECTIVAS. MODIFICA E INCORPORA INCS. DL. 2444/62 | as enacted, in force 22 January 2012 |
| `ley-1985-k/` | Ley 1985-K: CREA LA COMISION DE SEGUIMIENTO Y CONTROL OBRA SEGUNDO ACUEDUCTO | as enacted, in force 15 January 2012 |
| `ley-1990-g/` | Ley 1990-G: PLAN DE ENSEÑANZA DE REANIMACION CARDIOPULMONAR BASICA | as enacted, in force 11 January 2012 |
| `ley-1987-e/` | Ley 1987-E: DECLARA PATRIMONIO CULTURAL VIVIENTE AL EXPEDICIONARIO RAMON ORESTE "MONCHO" OTAZO | as enacted, in force 11 January 2012 |
| `ley-1986-e/` | Ley 1986-E: DECLARA PATRIMONIO HISTORICO CULTURAL  DE LA PCIA. OBRAS DE EDDIE JULIO TORRE | as enacted, in force 11 January 2012 |
| `ley-1983-a/` | Ley 1983-A: EXPROPIA INMUEBLE EN VILLA ANGELA P/ DONAR A LA ASOC. CIVIL "CIRCULO DE AMIGOS DEL TANGO" | as enacted, in force 11 January 2012 |
| `ley-1982-p/` | Ley 1982-P: CREA EL MUSEO LEGISLATIVO DE LA PROVINCIA DEL CHACO | as enacted, in force 11 January 2012 |
| `ley-1981-g/` | Ley 1981-G: ADHESION L.N.26.689 - CUIDADO INT. DE LA SALUD PERSONAS C/ENFERM.POCO FRECUENTES | as enacted, in force 8 January 2012 |
| `ley-1979-e/` | Ley 1979-E: DECLARA A LA CIUDAD DE GRAL. SAN MARTIN "CAPITAL PCIAL. DEL MOTOVIAJERO" | as enacted, in force 8 January 2012 |
| `ley-1980-g/` | Ley 1980-G: FARMACIAS Y/O COMERCIOS DEBERAN IMPLEMENTAR LISTADO DE MEDICAMENTOS QUE SE RETIRAN DE CIRCULACION | as enacted, in force 8 January 2012 |
| `ley-1978-e/` | Ley 1978-E: PROGRAMA PCIAL. DE DETECCION, PREVENCION Y TRATAM. DEL ACOSO ESCOLAR O BULLYING | as enacted, in force 1 January 2012 |
| `ley-1977-g/` | Ley 1977-G: ESTABLECE EN FORMA OBLIGATORIA, EL SUMINISTRO DE ACIDO FOLICO | as enacted, in force 1 January 2012 |
| `ley-1944-g/` | Ley 1944-G: CREA PROGRAMA DE PREVENCION, DIAGNOSTICO Y ATENCION DE ENFERMEDADES HUERFANAS | as enacted, in force 23 December 2011 |
| `ley-1969-a/` | Ley 1969-A: EXPROPIA INMUEBLES EN FONTANA P/TRANSFERIR AL MUNICIPIO CONSTR. COMPLEJO SOCIO CULTURAL | as enacted, in force 18 November 2011 |
| `ley-1970-g/` | Ley 1970-G: CREA EL "PROGRAMA MADRE CANGURO" CON TECNOLOGIA ANAF | as enacted, in force 13 November 2011 |
| `ley-1967-a/` | Ley 1967-A: BONIFICACION ESPECIAL PARA PERSONAL DEL MINISTERIO DE INFRAESTR. Y SERV. PUBLICOS | as enacted, in force 23 October 2011 |
| `ley-1968-i/` | Ley 1968-I: DECLARA DE INTERES GRAL. PROYECTO DE RADICACION INDUSTRIA AGROALIMENT. GRANJA TRES ARROYOS S.A. | as enacted, in force 9 October 2011 |
| `ley-1966-b/` | Ley 1966-B: REGLAMENTA LA ACCION DE INCONSTITUCIONAD ARTS. 9º Y 163 INC.1) APART.A) CONST.PCIAL 1957-1994 | as enacted, in force 9 October 2011 |
| `ley-1962-j/` | Ley 1962-J: ESTABLECE LA OBLIGATORIEDAD DE UTILIZAR COLCHONES IGNIFUGOS EN COMISARIAS, ETC. | as enacted, in force 25 September 2011 |
| `ley-1961-a/` | Ley 1961-A: EXPROPIA INMUEBLE EN DPTO. SAN FERNANDO P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES. | as enacted, in force 25 September 2011 |
| `ley-1964-f/` | Ley 1964-F: FIJA A PARTIR DEL 1º/08/11 ADICIONAL COMPLEMENT. PERSONAL CONTADURIA, TESOR. ETC. | as enacted, in force 25 September 2011 |
| `ley-1963-e/` | Ley 1963-E: ESPACIO PARA PERSONAS CON DISCAPACIDAD - "ARTE SIN BARRERAS" | as enacted, in force 23 September 2011 |
| `ley-1965-e/` | Ley 1965-E: ADICIONAL REMUNERATIVO Y BONIFICABLE P/DOCENTES ESTATAL Y PRIVADA | as enacted, in force 18 September 2011 |
| `ley-1956-g/` | Ley 1956-G: CREA COMISION PROVINCIAL DE SANIDAD VEGETAL (COPROSAVE) | as enacted, in force 19 August 2011 |
| `ley-1953-r/` | Ley 1953-R: CREA LA RESERVA DE RECURSOS "LA FIDELIDAD"  EN EL DEPARTAMENTO GENERAL GUEMES | as enacted, in force 19 August 2011 |
| `ley-1951-g/` | Ley 1951-G: TRATAMIENTO Y PREVENCION DE LA ENFERMEDAD CELIACA - DEROGA LA LEY 3278 | as enacted, in force 5 August 2011 |
| `ley-1892-c/` | Ley 1892-C: REGIMEN FORMACION Y EJERCICIO DE LA COSMETOLOGIA | as enacted, in force 5 August 2011 |
| `ley-1950-a/` | Ley 1950-A: EXPROPIA INMUEBLES EN PUERTO TIROL CON DESTINO AL PARQUE INDUSTRIAL | as enacted, in force 31 July 2011 |
| `ley-1947-a/` | Ley 1947-A: EXPROPIA INMUEBLES EN GRAL. VEDIA P/ CONSTRUCC. VIVIENDAS, OCUPADOS C/ASENTAMIENTOS | as enacted, in force 24 July 2011 |
| `ley-1940-a/` | Ley 1940-A: LEY ORGANICA DE LA FISCALIA DE ESTADO | as enacted, in force 13 July 2011 |
| `ley-1946-a/` | Ley 1946-A: EXPROPIA INMUEBLES EN FONTANA PARA CONSTRUCCION DE VIVIENDAS FAMILIARES | as enacted, in force 10 July 2011 |
| `ley-1945-g/` | Ley 1945-G: REGISTRO DE ENFERMEDADES HUERFANAS | as enacted, in force 10 July 2011 |
| `ley-1939-e/` | Ley 1939-E: DECLARA PATRIMONIO CULTURAL PCIAL. A LA EX  "ESTACION DEL FERROCARRIL SANTA FE" | as enacted, in force 24 June 2011 |
| `ley-1938-e/` | Ley 1938-E: DECLARA PATRIMONIO CULTURAL PCIAL. AL EDIFICIO "CASA MISIONAL" EX "MISION NUEVA POMPEYA" | as enacted, in force 24 June 2011 |
| `ley-1933-r/` | Ley 1933-R: PROGRAMA DE RECOLECCION Y ALMACENAJE FINAL DE PILAS USADAS | as enacted, in force 15 June 2011 |
| `ley-1932-a/` | Ley 1932-A: EXPROPIA INMUEBLE EN DPTO. S. FERNANDO P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 15 June 2011 |
| `ley-1928-g/` | Ley 1928-G: CREA PROGRAMA PCIAL. DE CONTROL DE LA ATENCION A LA PRIMERA INFANCIA | as enacted, in force 5 June 2011 |
| `ley-1930-e/` | Ley 1930-E: DECLARA PATRIMONIO CULTURAL DE LA PCIA. A LA BIBLIOTECA "BERNARDINO RIVADAVIA" | as enacted, in force 5 June 2011 |
| `ley-1919-a/` | Ley 1919-A: EXPROPIA INMUEBLE EN DPTO. S. FERNANDO P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 20 May 2011 |
| `ley-1918-a/` | Ley 1918-A: EXPROPIA INMUEBLES EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 20 May 2011 |
| `ley-1916-a/` | Ley 1916-A: EXPROPIA TERRENO P/CANAL DE DESAGUE LADO NORTE EN PRESIDENCIA DE LA PLAZA | as enacted, in force 8 May 2011 |
| `ley-1890-g/` | Ley 1890-G: REGULACION POR PRESTACION  Y HABILITACION  DEL SERVICIO DE AMBULANCIAS | as enacted, in force 8 May 2011 |
| `ley-1878-e/` | Ley 1878-E: DECLARA PATRIMONIO HISTORICO CULTURAL EDIFICIO "CAPILLA MARIA AUXILIADORA" | as enacted, in force 8 May 2011 |
| `ley-1901-a/` | Ley 1901-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 30 January 2011 |
| `ley-1898-a/` | Ley 1898-A: EXPROPIA INMUEBLES EN SAENZ PEÑA P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 30 January 2011 |
| `ley-1894-a/` | Ley 1894-A: EXPROPIA INMUEBLE Y BIENES FRIGORIFICO "LAS TERMAS S.R.L." DE SAENZ PEÑA | as enacted, in force 30 January 2011 |
| `ley-1907-a/` | Ley 1907-A: EXPROPIA INMUEBLE EN RESISTENCIA PARA VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 30 January 2011 |
| `ley-1910-a/` | Ley 1910-A: EXPROPIA INMUEBLE EN RESISTENCIA P/ SEDE  CLUB JUVENTUD DE VILLA CENTENARIO | as enacted, in force 30 January 2011 |
| `ley-1911-a/` | Ley 1911-A: EXPROPIA INMUEBLE EN RESISTENCIA PARA SEDE DEL CLUB LOS CANALLAS DE SUR | as enacted, in force 30 January 2011 |
| `ley-1903-c/` | Ley 1903-C: CREA LA INSPECCION GRAL. DE PERSONAS JURIDICAS (IGPJ) Y REGISTRO PUBLICO DE COMERCIO (RPC) | as enacted, in force 23 January 2011 |
| `ley-1904-a/` | Ley 1904-A: ARCHIVO DIGITAL SITIO WEB DE LA PCIA. REGISTRO DENUNCIAS  DE PERSONAS PERDIDAS | as enacted, in force 23 January 2011 |
| `ley-1897-e/` | Ley 1897-E: ADHESION L.N. 19.524 - REGIMEN DE ESCUELAS DE ZONAS Y AREAS DE FRONTERA | as enacted, in force 21 January 2011 |
| `ley-1902-a/` | Ley 1902-A: INCORPORA EL ARTICULO 13 BIS A LA LEY 2017 (BENEFICIO A EX-COMBATIENTES MALVINAS) | as enacted, in force 21 January 2011 |
| `ley-1893-j/` | Ley 1893-J: ADHESION LN.26.370 - CONTROL DE ADMISION Y PERMANENCIA - MOD. ART.29  L.1134 | as enacted, in force 21 January 2011 |
| `ley-1900-g/` | Ley 1900-G: DECLARA LA EMERGENCIA SANITARIA DE LOS RECURSOS HUMANOS DE ENFERMERIA | as enacted, in force 21 January 2011 |
| `ley-1895-a/` | Ley 1895-A: ADHESION L.N. 25.506 - LEY DE FIRMA DIGITAL | as enacted, in force 19 January 2011 |
| `ley-1888-d/` | Ley 1888-D: SISTEMA DE INFORMACION P/ EL FORTALECIMIENTO DE LA ACTIVIDAD COMERCIAL Y DE SERVICIOS | as enacted, in force 16 January 2011 |
| `ley-1887-e/` | Ley 1887-E: LEY DE EDUCACION PROVINCIAL. | as enacted, in force 24 December 2010 |
| `ley-1884-r/` | Ley 1884-R: "SISTEMA DE INFORMACION PARA EL FORTALECIMIENTO DEL ABASTECIMIENTO  Y COMERCIALIZACION DE HIDROCARBUROS (SIFACHACO)" | as enacted, in force 24 December 2010 |
| `ley-1879-g/` | Ley 1879-G: REGULA EL EJERCICIO DE LA ACTIVIDAD FARMACEUTICA EN LA PROVINCIA DEL CHACO | as enacted, in force 24 December 2010 |
| `ley-1882-a/` | Ley 1882-A: EXPROPIA INMUEBLES EN COLONIA PAMPA CHICA, DPTO. LIBERTADOR GRAL. SAN MARTIN | as enacted, in force 22 December 2010 |
| `ley-1803-e/` | Ley 1803-E: INSTITUYESE EL 30 DE MARZO DE CADA AÑO  EL "DIA DE LA CULTURA DEMOCRATICA" | as enacted, in force 19 December 2010 |
| `ley-1873-a/` | Ley 1873-A: PASE A PLANTA PERSONAL DEL SECTOR PUBLICO PROVINCIAL | as enacted, in force 12 November 2010 |
| `ley-1861-v/` | Ley 1861-V: DECLARA DE INTERES PCIAL. AL TURISMO EN LA  PROVINCIA DEL CHACO - REGIMEN. CREA EL INSTITUTO DE TURISMO DEL CHACO. | as enacted, in force 7 November 2010 |
| `ley-1868-g/` | Ley 1868-G: DECLARACION DE LOS DERECHOS DEL PACIENTE | as enacted, in force 29 October 2010 |
| `ley-1865-g/` | Ley 1865-G: ADHESION L.N. 26.606 - "MES NACIONAL DE CONCIENTIZACION  SOBRE EL CANCER DE MAMA" | as enacted, in force 29 October 2010 |
| `ley-1869-e/` | Ley 1869-E: FIJA A PARTIR DEL 1/07/2010 EL VALOR INDICE, Y ASIGNACIONES VARIAS P/ DOCENTES | as enacted, in force 22 October 2010 |
| `ley-1857-e/` | Ley 1857-E: INSTITUYESE EL "DIA PROVINCIAL DE LAS LENGUAS MATERNAS" EL 14 DE JULIO DE CADA AÑO | as enacted, in force 10 October 2010 |
| `ley-1855-i/` | Ley 1855-I: CONSTITUYESE UN FONDO FIDUCIARIO  "FONDO PARA EL DESARROLLO DEL EMPLEO INDUSTRIAL" | as enacted, in force 17 September 2010 |
| `ley-1839-e/` | Ley 1839-E: CREA EL COMPLEJO CULTURAL  DEL IMPENETRABLE, JURISDICCION MUNICIPIO J.J. CASTELLI | as enacted, in force 6 August 2010 |
| `ley-1836-a/` | Ley 1836-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 6 August 2010 |
| `ley-1828-a/` | Ley 1828-A: CREA EN P. R. SAENZ PEÑA UN JUZGADO PENAL DE FALTAS Y TUTELAR DEL MENOR DE EDAD Nº 2 Y UNA ASESORIA DEL MENOR DE EDAD Nº 2. | as enacted, in force 9 July 2010 |
| `ley-1831-a/` | Ley 1831-A: EXPROPIA INMUEBLES EN RCIA. P/ SER ADJUDICADOS EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 25 June 2010 |
| `ley-1808-a/` | Ley 1808-A: PROHIBE EL USO DE ANIMALES DE CUALQUIER ESPECIES EN ESPECTACULOS CIRCENSES | as enacted, in force 21 May 2010 |
| `ley-1799-r/` | Ley 1799-R: NORMAS SOBRE RESIDUOS PATOGENICOS EN EST. SANITARIOS PUBLICOS Y PRIVADOS | as enacted, in force 27 January 2010 |
| `ley-1792-i/` | Ley 1792-I: ADHESION PROVINCIAL A LA LEY NACIONAL Nº 26.509 | as enacted, in force 24 January 2010 |
| `ley-1795-r/` | Ley 1795-R: ADHESION L.N. 26.190 = REGIMEN DE FOMENTO NACIONAL P/ USO FUENTES RENOVABLES DE ENERGIA. | as enacted, in force 22 January 2010 |
| `ley-1779-b/` | Ley 1779-B: EL MAGISTRADO O FUNCIONARIO SUSPENDIDO  PERCIBIRA EL 70% DE SUS HABERES | as enacted, in force 27 December 2009 |
| `ley-1762-r/` | Ley 1762-R: ORDENAMIENTO TERRITORIAL DE LOS BOSQUES NATIVOS DE LA PCIA. DEL CHACO | as enacted, in force 13 December 2009 |
| `ley-1772-s/` | Ley 1772-S: REGIMEN DE SPONSORIZACION Y TUTORIA DEL DEPORTE | as enacted, in force 4 December 2009 |
| `ley-1771-a/` | Ley 1771-A: LA LEGISLATURA PCIAL. TRADUCIRA AL SISTEMA BRAILLE LEYES, RERSOLUC. Y DECLARAC. | as enacted, in force 22 November 2009 |
| `ley-1763-a/` | Ley 1763-A: ADHESION L.N. 26.233 - PROMOCION Y REGULACION CENTRO DE DESARROLLO INFANTIL | as enacted, in force 6 November 2009 |
| `ley-1761-e/` | Ley 1761-E: ALUMNOS DE LA CARRERA DE FORMACION DOCENTE CERRADA PODRAN RENDIR ASIGNATURAS  PENDIENTES | as enacted, in force 6 November 2009 |
| `ley-1758-e/` | Ley 1758-E: PROGRAMA "CAMPAÑA PCIAL. DE CONCIENCIACION Y PROMOCION DE KIOSCOS SALUDABLES" | as enacted, in force 18 October 2009 |
| `ley-1754-a/` | Ley 1754-A: BOLETAS IMPOSITIVAS Y DE SERVICIOS DEBERAN IMPRIMIR EN SISTEMA BRAILE | as enacted, in force 4 October 2009 |
| `ley-1748-f/` | Ley 1748-F: EXIME DE IMPUESTOS, TASAS Y TRIBUTOS PCIALES. P/ ENTES SANITARIOS DE VACUNACIÓN | as enacted, in force 4 October 2009 |
| `ley-1746-r/` | Ley 1746-R: DECLARA COMO DAÑINA Y PERJUDICIAL A LA PALOMA - ADHIERE L.N. 22.421 - FAUNA | as enacted, in force 23 September 2009 |
| `ley-1751-r/` | Ley 1751-R: ESTABLECE NORMAS Y PROCEDIMIENTOS DE MANEJO DEL FUEGO EN AREAS RURALES | as enacted, in force 13 September 2009 |
| `ley-1753-s/` | Ley 1753-S: IMPLEMENTA SISTEMA DE BECAS POR PARTE DE INSTITUCIONES DEPORTIVAS | as enacted, in force 11 September 2009 |
| `ley-1712-s/` | Ley 1712-S: CREA REGISTRO PCIAL. DE PASES INTERFED. E INTERASOC. P/ JUGADORES MENORES | as enacted, in force 22 April 2009 |
| `ley-1690-e/` | Ley 1690-E: LEY PROVINCIAL DE CULTURA. CREA INSTITUTO DE CULTURA DEL CHACO. | as enacted, in force 28 December 2008 |
| `ley-1677-e/` | Ley 1677-E: CREA EL FONDO BIBLIOTECARIO CHAQUEÑO | as enacted, in force 16 November 2008 |
| `ley-1674-a/` | Ley 1674-A: CREA JUZGADOS EN LA PRIMERA, SEGUNDA Y TERCERA CIRCUNSCRIPCION JUDICIAL | as enacted, in force 31 October 2008 |
| `ley-1675-e/` | Ley 1675-E: TÍTULOS DE TÉCNICO SUPERIOR AUXILIAR DOCENTE Y AUXILIAR DOCENTE SON EQUIVALENTES | as enacted, in force 19 October 2008 |
| `ley-1669-f/` | Ley 1669-F: LEY DE PROMOCION  DE LOS CALL CENTER, CONTACT CENTER Y ALOJAMIENTO WEB | as enacted, in force 17 October 2008 |
| `ley-1659-a/` | Ley 1659-A: MODIFICA COMPETENCIA JUZGADO LABORAL CHARATA CREADO POR LEY 3480 | as enacted, in force 12 September 2008 |
| `ley-1654-r/` | Ley 1654-R: APLICACION LEY NACIONAL 26.331 - PRES. MINIMOS DE PROTECC. AMB. BOSQUES NAT. | as enacted, in force 29 August 2008 |
| `ley-1634-r/` | Ley 1634-R: FORO CONSULTIVO PERMANENTE "AGUA RESPONSABLE CHACO" SEGÚN LEY 3230 | as enacted, in force 23 July 2008 |
| `ley-1641-r/` | Ley 1641-R: CREA CAMPO DE INVESTIG.,  EXPERIMENTAC. Y DESARROLLO DEL CULTIVO DEL ARROZ | as enacted, in force 16 July 2008 |
| `ley-1613-a/` | Ley 1613-A: REQUISITOS P/PUBLICAC. EN DIARIOS, REVISTAS, ETC. S/CUMPLIM.DISP. LABORALES | as enacted, in force 18 January 2008 |
| `ley-1595-g/` | Ley 1595-G: PROHIBE EN TODA LA PCIA. EL SACRIFICIO DE PERROS Y GATOS SIN DUEÑO | as enacted, in force 30 December 2007 |
| `ley-1584-a/` | Ley 1584-A: MODIFICA ART.4º LEY 196-A  (ANTES LEY 1276) Y  REESTRUC. ADICIONAL Y BONIFICACICAC. PERSONAL | as enacted, in force 25 November 2007 |
| `ley-1581-e/` | Ley 1581-E: REGISTRO PARA LA INSCRIPCION DE INTERPRETES DE LENGUA DE SEÑAS | as enacted, in force 25 November 2007 |
| `ley-1556-a/` | Ley 1556-A: EXPROPIA INMUEBLE EN RESISTENCIA P/ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 15 July 2007 |
| `ley-1544-e/` | Ley 1544-E: CREA PROGRAMA DE EDUCACIÓN PLURILINGÜE | as enacted, in force 20 June 2007 |
| `ley-1531-e/` | Ley 1531-E: DECLARA DE INTERÉS EDUCATIVO PCIAL. DIFUSIÓN "INFORME FINAL COM. DE DERECHOS HUMANOS." | as enacted, in force 2 May 2007 |
| `ley-1530-e/` | Ley 1530-E: ADHESIÓN L.N. 26.205 -DÍA NACIONAL DE LOS DERECHOS DE CONSUMIDORES Y USUARIOS-. | as enacted, in force 25 April 2007 |
| `ley-1529-b/` | Ley 1529-B: ADHESIÓN L.N. 26.097 - APRUEBA CONVENCIÓN DE LAS NAC.UNIDAS CONTRA LA CORRUPCIÓN. | as enacted, in force 25 April 2007 |
| `ley-1528-i/` | Ley 1528-I: REGIMEN DE RECONOCIMIENTO Y PROMOCIÓN A DISEÑADORES DE MODA. | as enacted, in force 28 February 2007 |
| `ley-1524-e/` | Ley 1524-E: CONCURSO VIAJE DE ESTUDIOS "CONOCIENDO MI PROVINCIA" | as enacted, in force 25 February 2007 |
| `ley-1516-f/` | Ley 1516-F: ADHIÉRESE  LA  PROVINCIA  DEL  CHACO  AL  ART. 76  DE  LA  LEY  NACIONAL  26.078  – PRESUPUESTO GENERAL DE LA ADMINISTRACIÓN NACIONAL– Y AL ART. 17 … | as enacted, in force 11 February 2007 |
| `ley-1514-a/` | Ley 1514-A: EXPROPIA INMUEBLES RURALES EN DPTO. S. CABRAL S/TRAZA ACTUAL CAMINO, A FAVOR D.VIALIDAD. | as enacted, in force 4 February 2007 |
| `ley-1513-a/` | Ley 1513-A: EXPROPIA INMUEBLE EN RCIA., PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 4 February 2007 |
| `ley-1511-a/` | Ley 1511-A: EXPROPIA INMUEBLES EN DPTO. 12 DE OCTCUBRE A FAVOR DEL GOBIERNO DE LA PCIA DEL CHACO | as enacted, in force 31 December 2006 |
| `ley-1496-b/` | Ley 1496-B: ADHESION D.N. Nº 1086/2005 -HACIA UN PLAN NACIONAL CONTRA LA DISCRIMINACION. | as enacted, in force 13 December 2006 |
| `ley-1502-e/` | Ley 1502-E: INCLÚYE EN LOS ESTABLEC. EDUCATIVOS PÚBLICOS Y PRIVADOS LA "EDUCACIÓN SEXUAL  INTEGRAL" | as enacted, in force 10 December 2006 |
| `ley-1493-a/` | Ley 1493-A: EXPROPIA INMUEBLE EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES. | as enacted, in force 29 November 2006 |
| `ley-1464-r/` | Ley 1464-R: HABILITACION Y FUNCIONAMIENTO ESTABLEC. PECUARIOS DE ENGORDE A CORRAL | as enacted, in force 29 November 2006 |
| `ley-1489-j/` | Ley 1489-J: HOSPITALES , SANATORIOS, POLICIA DEBERAN EXHIBIR NUMEROS TELEFONICOS P/VIOL. FAMILIAR | as enacted, in force 4 November 2006 |
| `ley-1488-e/` | Ley 1488-E: ADHESION A LA LEY NACIONAL Nº 24.605 | as enacted, in force 27 October 2006 |
| `ley-1486-a/` | Ley 1486-A: EXPROPIA INMUEBLES EN RCIA. PARA ADJUDICAR EN VENTA A SUS ACTUALES OCUPANTES | as enacted, in force 15 October 2006 |
| `ley-1485-r/` | Ley 1485-R: AUTORIZA A LA DIRECCION DE BOSQUES A PERCIBIR ADICIONAL DEL 3% POR TODA LA MADERA | as enacted, in force 15 October 2006 |
| `ley-1474-f/` | Ley 1474-F: ASISTENCIA NO REINTEGRABLE A PRODUCTORES CRIOLLOS Y ABORIGENES | as enacted, in force 1 September 2006 |
| `ley-1471-e/` | Ley 1471-E: ADHESION D.N. 1574/63 - DIA NACIONAL DE LA CONSERVACIOON DEL SUELO - | as enacted, in force 11 August 2006 |
| `ley-1469-a/` | Ley 1469-A: EXPROPIA INMUEBLE EN RCIA. -CASA PERRANDO-, PARA CENTRO CULTURAL | as enacted, in force 11 August 2006 |
| `ley-1468-a/` | Ley 1468-A: EXPROPIA INMUEBLE EN BQUERAS. P/ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 11 August 2006 |
| `ley-1470-a/` | Ley 1470-A: EXPROPIA INMUEBLE EN PTO. VILELAS P/CONSTRUCCION CEMENTERIO | as enacted, in force 4 August 2006 |
| `ley-1462-a/` | Ley 1462-A: EXPROPIA INMUEBLE EN TRES ISLETAS P/COOP.DE TRABAJO SOJALIN LIMITADA | as enacted, in force 16 July 2006 |
| `ley-1461-n/` | Ley 1461-N: CREA CAMARA DE APELACIONES EN LO CRIMINAL Y CORRECC. EN RESISTENCIA | as enacted, in force 16 July 2006 |
| `ley-1458-e/` | Ley 1458-E: ADHESION D.N.754/98 -DIA NACIONAL DEL CRUCERO A.R.A. GRAL. BELGRANO- | as enacted, in force 25 June 2006 |
| `ley-1459-a/` | Ley 1459-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 18 June 2006 |
| `ley-1455-a/` | Ley 1455-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 11 June 2006 |
| `ley-1454-a/` | Ley 1454-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 11 June 2006 |
| `ley-1445-p/` | Ley 1445-P: PRESERVACION DOCUMENTAC. VINCULADOS A LA REPRESION Y AL TERR.DE ESTADO | as enacted, in force 11 June 2006 |
| `ley-1451-a/` | Ley 1451-A: EXPROPIA INMUEBLE EN RCIA. P/AMPLIACION JARDIN MATERN. Y DE INF. Nº 34 | as enacted, in force 28 May 2006 |
| `ley-1450-a/` | Ley 1450-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 28 May 2006 |
| `ley-1449-a/` | Ley 1449-A: EXPROPIA INMUEBLE EN BQUERAS. P/ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 28 May 2006 |
| `ley-1444-g/` | Ley 1444-G: ADHESION L.N.25.649 -PROMOCION UTILIZACION DE MEDICAMENTOS GENERICOS- | as enacted, in force 17 May 2006 |
| `ley-1440-a/` | Ley 1440-A: RATIFICA DTO. 2790/05 - PISO SALARIAL $700,- P/ESCALAFON DOCENTE | as enacted, in force 19 April 2006 |
| `ley-1429-r/` | Ley 1429-R: MANEJO DE LOS RECURSOS DE LA FAUNA SILVESTRE Y LA CAZA | current text only, as of 11 October 2018 |
| `ley-1426-e/` | Ley 1426-E: CREA REGISTRO DE ARBOLES HISTORICOS Y NOTABLES DE LA PCIA. DEL CHACO | as enacted, in force 6 January 2006 |
| `ley-1431-g/` | Ley 1431-G: ADHESION L.N.22.990 - LEY DE SANGRE HUMANA | as enacted, in force 28 December 2005 |
| `ley-1421-e/` | Ley 1421-E: ADHESION L.N.26.058 - LEY DE EDUCACION TECNICO PROFESIONAL | as enacted, in force 26 October 2005 |
| `ley-1411-g/` | Ley 1411-G: ADHESION L.N.25.415 -PROGR.NACIONAL DETEC.TEMPRANA Y ATENC. HIPOACUSIA | as enacted, in force 7 August 2005 |
| `ley-1367-a/` | Ley 1367-A: AUTORIZA AL IN.S.S.SE.P. A VENDER DEPARTAMENTOS DE SU PROPIEDAD | as enacted, in force 22 July 2005 |
| `ley-1404-r/` | Ley 1404-R: PROGRAMA DE EVALUACION AMBIENTAL ESTRATEGICA DE PLANES Y PROGRAMAS | as enacted, in force 15 July 2005 |
| `ley-1401-s/` | Ley 1401-S: CREA EN LA PCIA. LA FEDERACION PARA EL DEPORTE ADAPTADO | as enacted, in force 26 June 2005 |
| `ley-1396-e/` | Ley 1396-E: INSTITUYE "DIA PROVINCIAL DE LA MEMORIA POR LA VERDAD Y LA JUSTICIA" | as enacted, in force 27 May 2005 |
| `ley-1384-e/` | Ley 1384-E: ADHIERE LA PCIA. D.N.1531/72 -DIA DE LAS ESCUELAS DE FRONTERA- | as enacted, in force 24 April 2005 |
| `ley-1378-r/` | Ley 1378-R: ADHIERE LA PCIA. CELEBRACION DEL "DIA MUNDIAL DEL AGUA" | as enacted, in force 1 April 2005 |
| `ley-1356-n/` | Ley 1356-N: CREA DEFENSORIAS OFICIALES PENALES Y FISCALIAS DE INVESTIGACION PENAL | as enacted, in force 23 January 2005 |
| `ley-1377-a/` | Ley 1377-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 16 January 2005 |
| `ley-1376-a/` | Ley 1376-A: EL P.E. TRANSFIERE INMUEBLES EN PTO. EVA PERON | as enacted, in force 16 January 2005 |
| `ley-1374-g/` | Ley 1374-G: INSTITUYE CON EL NOMBRE DE "DRA LEONOR SORIA" AL HOSP. ODONTOLOGICO | as enacted, in force 16 January 2005 |
| `ley-1370-h/` | Ley 1370-H: SISTEMA DE PRESTACIONES SOCIALES EX EMPLEADOS RETIRADOS BOCEP. L.3900 | as enacted, in force 14 January 2005 |
| `ley-1369-h/` | Ley 1369-H: SISTEMA DE PRESTACIONES SOCIALES EX EMPLEADOS DEL BANCO DEL CHACO SEM. | as enacted, in force 14 January 2005 |
| `ley-1368-j/` | Ley 1368-J: ADHESION L.N.24.632 -CONVENCION DE BELEM DO PARA-VIOLENCIA C/ LA MUJER | as enacted, in force 9 January 2005 |
| `ley-1365-a/` | Ley 1365-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR A ACTUALES OCUPANTES | as enacted, in force 9 January 2005 |
| `ley-1363-a/` | Ley 1363-A: EXPROPIA INMUEBLES EN VILLA ANGELA PARA RESERVA ESPACIO VERDE | as enacted, in force 9 January 2005 |
| `ley-1362-a/` | Ley 1362-A: EXPROPIA INMUEBLES EN VILLA ANGELA P/CREACION PARQUE INDUSTRIAL | as enacted, in force 9 January 2005 |
| `ley-1361-a/` | Ley 1361-A: EXPROPIA INMUEBLE EN COLONIA CRUCE VIEJO P/AMPLIACION E.E.G.B. N.392 | as enacted, in force 9 January 2005 |
| `ley-1364-f/` | Ley 1364-F: ADHESION L.N.25.917 - REGIMEN DE RESPONSABILIDAD FISCAL - | as enacted, in force 2 January 2005 |
| `ley-1359-e/` | Ley 1359-E: DIA DEL JUBILADO PROVINCIAL, EL 24 DE NOVIEMBRE DE CADA AÑO | as enacted, in force 2 January 2005 |
| `ley-1351-x/` | Ley 1351-X: CONVENIO MARCO NACION-PCIA. SIST. PCIAL. DE INVERS. PUBLICAS (SPIP) | as enacted, in force 12 December 2004 |
| `ley-1352-i/` | Ley 1352-I: ADHESION L.N.25.422 -RECUPERACION GANADERIA OVINA- | as enacted, in force 12 December 2004 |
| `ley-1349-w/` | Ley 1349-W: ADHESION  L.N.25.517 - RESTOS MORTALES DE ABORIGENES DE MUSEOS Y/O COLECCION PUBLICAS | as enacted, in force 26 November 2004 |
| `ley-1347-b/` | Ley 1347-B: ADHESION L.N.25.914 - INDEMNIZACION PARA HIJOS NACIDOS EN CAUTIVERIO | as enacted, in force 14 November 2004 |
| `ley-1345-e/` | Ley 1345-E: DECLARA SEDE FIESTA PCIAL. DEL NIÑO EN COMPL.ECOLOG. MUNIC. DE S. PEÑA | as enacted, in force 14 November 2004 |
| `ley-1343-e/` | Ley 1343-E: ESTABLECE EL 16/09 COMO DIA DE LOS DERECHOS DE LOS ESTUDIANTES SECUND. | as enacted, in force 15 October 2004 |
| `ley-1344-f/` | Ley 1344-F: RENEGOCIACION DEUDA PUBLICA FINANCIERA MUNICIPIO DE RESISTENCIA | as enacted, in force 8 October 2004 |
| `ley-1342-p/` | Ley 1342-P: INSTITUYE EL SISTEMA DE INFORMACION MUNICIPAL -S.I.M.- | as enacted, in force 15 September 2004 |
| `ley-1339-a/` | Ley 1339-A: EXPROPIA INMUEBLE EN RCIA. P/VENTA A OCUPANTES | as enacted, in force 22 August 2004 |
| `ley-1338-a/` | Ley 1338-A: EXPROPIA INMUEBLES EN RCIA. P/VENTA ACTUALES OCUPANTES | as enacted, in force 22 August 2004 |
| `ley-1337-g/` | Ley 1337-G: PROGRAMA SOBRE CARENCIA ACIDO FOLICO- ADHESION L.N.25.630 | as enacted, in force 11 August 2004 |
| `ley-1333-e/` | Ley 1333-E: INSTITUYE EL 7 DE MAYO "DIA DE LA DIGNIDAD" NATALICIO EVA D. DE PERON | as enacted, in force 16 July 2004 |
| `ley-1334-e/` | Ley 1334-E: PROGRAMA "LA SOLIDARIDAD HACE ESCUELA" PARA ALUMNOS DISTINTOS NIVELES | as enacted, in force 16 July 2004 |
| `ley-1332-a/` | Ley 1332-A: ADHESION L.N.25.551 -REGIMEN DE PREFERENCIA DE LA PRODUCCION NACIONAL- | as enacted, in force 14 July 2004 |
| `ley-1331-e/` | Ley 1331-E: DECLARA DE INT. PCIAL. BUSQUEDA RESTOS DESAPARECIDOS AÑOS 1976-1983 | as enacted, in force 14 July 2004 |
| `ley-1330-e/` | Ley 1330-E: INCORPORA A LA EDUCACION DE PERSONAS SORDAS LENGUA DE SEÑAS ARGENTINAS | as enacted, in force 14 July 2004 |
| `ley-1328-e/` | Ley 1328-E: ESPACIOS PEDAGOGICOS P/ ANALISIS CRITICO VERSION ORIGINAL HIMNO NAC. | as enacted, in force 2 July 2004 |
| `ley-1325-e/` | Ley 1325-E: ADHESION  D.N.982/98 - DECLARA 26 DE AGOSTO "DIA DE LA SOLIDARIDAD" | as enacted, in force 13 June 2004 |
| `ley-1324-a/` | Ley 1324-A: EXPROPIA INMUEBLES DEP.S. FERNANDO P/ADJUDICAR EN VENTA ACTUALES OCUP. | as enacted, in force 11 June 2004 |
| `ley-1323-e/` | Ley 1323-E: ESTABLECE LAS "JORNADAS TURISTICAS ESCOLARES" MES DE JULIO DE CADA AÑO | as enacted, in force 11 June 2004 |
| `ley-1319-x/` | Ley 1319-X: CONVENIO DEL PROGRAMA DE FINANCIAMIENTO ORDENADO | as enacted, in force 23 May 2004 |
| `ley-1320-e/` | Ley 1320-E: ADHESION  L.N.25.863 -DECLARA EL 1º DE MAYO COMO "DIA DE LA CONSTITUCION  NACIONAL" | as enacted, in force 21 May 2004 |
| `ley-1318-e/` | Ley 1318-E: ADHESION L.N.25.844 -INSTITUYE 13 DE NOV."DIA DEL PENSAMIENTO NACIONAL" | as enacted, in force 14 May 2004 |
| `ley-1314-l/` | Ley 1314-L: ADHESION L.N.25.872 - PROGRAMA NACIONAL DE APOYO AL EMPRESARIADO JOVEN | as enacted, in force 5 May 2004 |
| `ley-1313-f/` | Ley 1313-F: ADHESION L.N.25.798 - SISTEMA DE REFINANCIACION HIPOTECARIA | as enacted, in force 5 May 2004 |
| `ley-1315-e/` | Ley 1315-E: DESIGNA A PARTIR DEL 1/3/04 A LOS DOCENTES DE MATERIAS ESPECIALES | as enacted, in force 2 May 2004 |
| `ley-1300-e/` | Ley 1300-E: IMPLEMENTA PLAN DE FORMACION EN SERVICIO CONTINUO PARA DOCENTES | as enacted, in force 19 March 2004 |
| `ley-1292-a/` | Ley 1292-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 28 January 2004 |
| `ley-1312-h/` | Ley 1312-H: CREA LA CAJA FORENSE DEL CHACO | as enacted, in force 21 January 2004 |
| `ley-1309-e/` | Ley 1309-E: PROGRAMA DE EDUCACION ALIMENTARIA Y NUTRICIONAL | as enacted, in force 21 January 2004 |
| `ley-1308-a/` | Ley 1308-A: EXPROPIA INMUEBLES BQUERAS. CANALIZ. CH.286 Y AMPL. RESERVORIO CH.297 | as enacted, in force 21 January 2004 |
| `ley-1301-a/` | Ley 1301-A: EXPROPIA INMUEBLES EN VARIOS DPTOS. OBRA HIDRICA CUENCA RIO TAPENAGA | as enacted, in force 21 January 2004 |
| `ley-1302-e/` | Ley 1302-E: APRUEBA FUCIONAMIENTO DE LA ESCUELA DE EDUCACION TECNOLOGICA | as enacted, in force 18 January 2004 |
| `ley-1306-a/` | Ley 1306-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 18 January 2004 |
| `ley-1305-a/` | Ley 1305-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 18 January 2004 |
| `ley-1303-e/` | Ley 1303-E: DECLARA A LA CIUDAD DE VILLA ANGELA "CAPITAL PROVINCIAL DEL TANGO" | as enacted, in force 18 January 2004 |
| `ley-1299-i/` | Ley 1299-I: FERIA PROVINCIAL DE COMERCIALIZACIÓN COMUNITARIA PARA PEQUEÑOS PRODUCTORES | as enacted, in force 16 January 2004 |
| `ley-1296-a/` | Ley 1296-A: EXPROPIA INMUEBLES EN SAENZ PEÑA P/ PARQUE INDUSTRIAL | as enacted, in force 16 January 2004 |
| `ley-1295-e/` | Ley 1295-E: CREA EL CONSEJO PROVINCIAL DE EDUCACION Y TRABAJO -COPET- | as enacted, in force 14 January 2004 |
| `ley-1298-a/` | Ley 1298-A: PROHIBE ACCESO A INTERNET MENORES DE 18 AÑOS PAGINAS PORNOGRAFICAS | as enacted, in force 14 January 2004 |
| `ley-1297-p/` | Ley 1297-P: ESTABLECE REGIMEN JURIDICO ESPECIAL Y TRANSITORIO SOBRE TIERRAS FISCALES Y PRIVADAS EN COMODATO | as enacted, in force 14 January 2004 |
| `ley-1291-a/` | Ley 1291-A: EXPROPIA INMUEBLE EN FONTANA P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 4 January 2004 |
| `ley-1288-s/` | Ley 1288-S: UTILIZACION INSTALACIONES DEPORTIVAS P/ USO ALUMNOS DE INST.EDUCATIVAS | as enacted, in force 4 January 2004 |
| `ley-1287-n/` | Ley 1287-N: CREA TRES FISCALIAS DE INVESTIGACIONES DEL FUERO PENAL EN RESISTENCIA | as enacted, in force 4 January 2004 |
| `ley-1293-a/` | Ley 1293-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 4 January 2004 |
| `ley-1294-a/` | Ley 1294-A: EXPROPIA INMUEBLES EN FONTANA P/ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 2 January 2004 |
| `ley-1285-a/` | Ley 1285-A: INSTITUYE EL 27 DE NOVIEMBRE COMO EL "DIA DE LOTERIA CHAQUEÑA" | as enacted, in force 2 January 2004 |
| `ley-1290-x/` | Ley 1290-X: CONVENIO PROYECTO CENTRO DE DESARROLLO TECNOLOGICO DE LA IND. MADERERA | as enacted, in force 31 December 2003 |
| `ley-1286-x/` | Ley 1286-X: CONVENIO DE PARTICIPACION PROYECTO PERMER. C/SECR.DE ENERGIA Y MINERIA | as enacted, in force 14 December 2003 |
| `ley-1282-e/` | Ley 1282-E: CONSIDERASE FRENTE A ALUMNOS EN LA CATEDRA "PRACTICA DE LA ENSEÑANZA" | as enacted, in force 10 December 2003 |
| `ley-1254-g/` | Ley 1254-G: LA PCIA. GARANTIZA Y RESGUARDA ACCESO A PRODUCTOS ALIMENTICIOS SEGUROS | as enacted, in force 5 December 2003 |
| `ley-1274-a/` | Ley 1274-A: EXPROPIA INMUEBLES EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 10 October 2003 |
| `ley-1275-a/` | Ley 1275-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 3 October 2003 |
| `ley-1273-v/` | Ley 1273-V: ADHESION LEYES NACIONAL NROS.18.829 Y 25.599 | as enacted, in force 3 October 2003 |
| `ley-1260-h/` | Ley 1260-H: Facúltase al Directorio del Instituto de Seguridad Social, Seguros y Prestamos a  compensar las partidas de los distintos fondos establecidos en el … | as enacted, in force 15 June 2003 |
| `ley-1256-h/` | Ley 1256-H: SISTEMA PCIAL. DE INFORMAC., EVALUAC.Y MONIT. DE PROGR. SOC. (SIPIEM) | as enacted, in force 11 June 2003 |
| `ley-1257-e/` | Ley 1257-E: ESTABLECE  DIA PCIAL. DE LAS ORG. NO GUBERN. (ONGS) EL 31 DE AGOSTO | as enacted, in force 6 June 2003 |
| `ley-1251-g/` | Ley 1251-G: ESTABLECE OBLIGATORIEDAD DE CONTROL PESO Y TALLA NIÑOS DE 0 A 6 AÑOS | as enacted, in force 23 May 2003 |
| `ley-1237-e/` | Ley 1237-E: ESTABLECE MARCO REGULATORIO DEL PLAN PROVINCIAL DE ALFABETIZACION | as enacted, in force 24 January 2003 |
| `ley-1236-x/` | Ley 1236-X: MODIFICA EL ART.2 DE LA LEY 987-X (ANTES LEY 4573) -RATIFICA ACUERDO CON TRENTO- | as enacted, in force 8 January 2003 |
| `ley-1229-h/` | Ley 1229-H: ADHESION  L.N.25.629 - ACUERDOS COMPUTO RECIPR. BENEF. PREVIS.- | as enacted, in force 15 December 2002 |
| `ley-1226-a/` | Ley 1226-A: EXPROPIA INMUEBLE EN RCIA. P/ ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 24 November 2002 |
| `ley-1227-a/` | Ley 1227-A: DONA INMUEBLE AL MUNICIPIO DE BASAIL  EN DEPARTAMENTO SAN  FERNANDO | as enacted, in force 20 November 2002 |
| `ley-1223-f/` | Ley 1223-F: EXIME DE IMPUESTOS Y TASAS, TRAMITES BENEFICIO ESTABLEC. POR L.24.411 | as enacted, in force 30 October 2002 |
| `ley-1220-e/` | Ley 1220-E: ADHESION L.N.25.575 - PROGRAMA VOCACIONAR - | as enacted, in force 25 October 2002 |
| `ley-1216-a/` | Ley 1216-A: EXPROPIA INMUEBLES EN BQUERAS. P/CONSTRUCC. TRAMO III DEFENSA C/INUND. | as enacted, in force 11 October 2002 |
| `ley-1215-g/` | Ley 1215-G: REGIMEN DE FORMACION Y CAPACITACION DE LOS RECURSOS HUMANOS EN SALUD | as enacted, in force 6 October 2002 |
| `ley-1212-s/` | Ley 1212-S: CREA LA BANDERA DEL DEPORTE DE LA PROVINCIA DEL CHACO | as enacted, in force 4 September 2002 |
| `ley-1211-f/` | Ley 1211-F: ORDENAMIENTO DE LAS FINANZAS PUBLICAS DE LA PROVINCIA (L.5071) | as enacted, in force 9 August 2002 |
| `ley-1206-e/` | Ley 1206-E: ADHESION  L.N.25.583 -PROGR. SOC. P/ASISTIR NIÑOS CARENCIADOS- | as enacted, in force 7 August 2002 |
| `ley-1205-e/` | Ley 1205-E: ADHESION  L.N.25.584 - CICLO ESCOLAR A ALUMNAS EMBARAZADAS - | as enacted, in force 7 August 2002 |
| `ley-1192-f/` | Ley 1192-F: RENEGOCIACION DEUDAS DE MUNICIPIOS CON ORG. DE CREDITOS NAC. E INTERN. | as enacted, in force 28 April 2002 |
| `ley-1180-s/` | Ley 1180-S: ESTABLECE EL 24 DE SEPTIEMBRE DE CADA AÑO "DIA DEL DEPORTE CHAQUEÑO" | as enacted, in force 17 March 2002 |
| `ley-1172-a/` | Ley 1172-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES -VISTA LINDA- | as enacted, in force 27 January 2002 |
| `ley-1186-d/` | Ley 1186-D: ESTABLECE LA CONSTITUCION DE LA SOCIEDAD "FIDUCIARIA DEL NORTE S.A." | as enacted, in force 2 January 2002 |
| `ley-1164-a/` | Ley 1164-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 23 December 2001 |
| `ley-1177-a/` | Ley 1177-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 21 December 2001 |
| `ley-1166-a/` | Ley 1166-A: EXPROPIA INMUEBLE EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 21 December 2001 |
| `ley-1167-a/` | Ley 1167-A: EXPROPIA INMUEBLE EN S. PEÑA P/ ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 21 November 2001 |
| `ley-1165-i/` | Ley 1165-I: REGULA EXPLOTACION DE HIPERMERCADOS Y GRANDES CADENA COMERCIALES | as enacted, in force 21 November 2001 |
| `ley-1162-a/` | Ley 1162-A: ESTABLECE TRANSFERENCIA DE JURISDICCIONES PERSONAL PODER LEGISLATIVO | as enacted, in force 21 October 2001 |
| `ley-1160-a/` | Ley 1160-A: EXPROPIA INMUEBLE EN SAENZ PEÑA PARA MUNICIPIO LOCAL | as enacted, in force 21 October 2001 |
| `ley-1159-a/` | Ley 1159-A: EXPROPIA INMUEBLE EN PRES. ROQUE SAENZ PEÑA P/ADJUDICAR EN VENTA | as enacted, in force 21 October 2001 |
| `ley-1158-a/` | Ley 1158-A: EXPROPIA INMUEBLES EN S. PEÑA P/ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 21 October 2001 |
| `ley-1157-a/` | Ley 1157-A: IMPONE EL NOMBRE DE "PTO. DE BARRANQUERAS DON ORIONE" AL ACTUAL PUERTO | as enacted, in force 21 October 2001 |
| `ley-1163-f/` | Ley 1163-F: BONOS "QUEBRACHO". ADHESION L.N.25344 - EMERGENCIA ECONOMICA FINANC. | as enacted, in force 14 October 2001 |
| `ley-1156-a/` | Ley 1156-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 12 October 2001 |
| `ley-1153-c/` | Ley 1153-C: EL REGISTRO CIVIL PODRA CELEBRAR MATRIMONIOS FUERA DEL EDIFICIO | as enacted, in force 23 September 2001 |
| `ley-1151-r/` | Ley 1151-R: PROHIBE UTILIZACION DE ACEITES QUE CONTENGAN BIFENILOS POLICLORADOS | as enacted, in force 9 September 2001 |
| `ley-1150-a/` | Ley 1150-A: EXPROPIA INMUEBLE EN LAPACHITO PROPIEDAD DE VICTORIANO BENITEZ | as enacted, in force 9 September 2001 |
| `ley-1149-a/` | Ley 1149-A: EXPROPIA INMUEBLE EN LAPACHITO PROPIEDAD DE DORA Y EDITH PALACIO | as enacted, in force 9 September 2001 |
| `ley-1148-a/` | Ley 1148-A: EXPROPIA INMUEBLE EN LAGUNA BLANCA A FAVOR DEL MUNICIPIO LOCAL | as enacted, in force 5 September 2001 |
| `ley-1147-a/` | Ley 1147-A: EXPROPIA INMUEBLE EN COTE LAI A FAVOR DEL MUNICIPIO LOCAL | as enacted, in force 22 August 2001 |
| `ley-1144-e/` | Ley 1144-E: CREA PLAN DE EDUCACION AMBIENTAL | as enacted, in force 22 August 2001 |
| `ley-1129-a/` | Ley 1129-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA ACTUALES OCUPANTES | as enacted, in force 22 August 2001 |
| `ley-1143-a/` | Ley 1143-A: TRANSFIERE INMUEBLE A LA SOCIEDAD RURAL DE QUITILIPI | as enacted, in force 12 August 2001 |
| `ley-1142-r/` | Ley 1142-R: ADHESION PCIAL. D.N.206/2001 | as enacted, in force 12 August 2001 |
| `ley-1140-e/` | Ley 1140-E: ORGANIZACION DE ACTIVIDADES S/HIMNO, ESCARAPELA, ESCUDO, Y BANDERA | as enacted, in force 5 August 2001 |
| `ley-1137-a/` | Ley 1137-A: EXPROPIA INMUEBLES EN DPTOS. M.LUIS J. FONTANA Y F.J.STA. MARIA DE ORO | as enacted, in force 3 August 2001 |
| `ley-1141-r/` | Ley 1141-R: ESTABLECE PAGO DE REGALIAS PARA EXTRACCION DE SUSTANCIAS MINERAS | as enacted, in force 3 August 2001 |
| `ley-1139-a/` | Ley 1139-A: EXPROPIA INMUEBLE EN COLONIA J.J.PASO PARA ADJUDICAR A SUS OCUPANTES | as enacted, in force 27 July 2001 |
| `ley-1118-p/` | Ley 1118-P: CREA DIRECCION PROVINCIAL DE CATASTRO Y CARTOGRAFIA | as enacted, in force 27 July 2001 |
| `ley-1136-p/` | Ley 1136-P: CREA LA BANDERA OFICIAL DE LA PCIA. DEL CHACO | as enacted, in force 11 July 2001 |
| `ley-1135-m/` | Ley 1135-M: CODIGO DE PROCEDIMIENTOS MINEROS | as enacted, in force 6 July 2001 |
| `ley-1134-i/` | Ley 1134-I: MAPA INTEGRAL DE INVERSIONES, PROYECTOS Y APTITUDES PRODUCTIVAS CHACO | as enacted, in force 24 June 2001 |
| `ley-1114-r/` | Ley 1114-R: DECLARA PARQUE PCIAL. FUERTE ESPERANZA, EN DEPARTAMENTO GRAL. GUEMES | as enacted, in force 24 June 2001 |
| `ley-1132-d/` | Ley 1132-D: ADHESION L.N.25156 -DEFENSA DE LA COMPETENCIA- | as enacted, in force 13 June 2001 |
| `ley-1130-c/` | Ley 1130-C: ADHESION L.N.23728 | as enacted, in force 20 May 2001 |
| `ley-1120-c/` | Ley 1120-C: CREA DIRECCION GRAL. DEL REGISTRO DE LA PROPIEDAD INMUEBLE PCIA. CHACO | as enacted, in force 20 May 2001 |
| `ley-1131-x/` | Ley 1131-X: CONVENIO PCIAS. CHACO-SANTA FE POR EXTENSION SERVICIOS SEFECHA S.A. | as enacted, in force 11 May 2001 |
| `ley-1127-e/` | Ley 1127-E: PREMIO PROVINCIAL A LA MUJER DESTACADA | as enacted, in force 20 April 2001 |
| `ley-1126-a/` | Ley 1126-A: BENEFICIOS DE JUBILACION P/EX- AGENTES  RETIRADOS A TRAVES DEL BOCEP | as enacted, in force 1 April 2001 |
| `ley-1125-f/` | Ley 1125-F: ADHESION D.N.1299/00 | current text only, as of 19 June 2018 |
| `ley-1124-x/` | Ley 1124-X: APRUEBA CONVENIO DE ASISTENCIA FINANCIERA CON EL FONDO FIDUCIARIO | as enacted, in force 25 February 2001 |
| `ley-1123-j/` | Ley 1123-J: PROHIBE VENTA A MENORES DE 18 AÑOS PEGAMENTOS QUE CONTENGAN TOLUENO | as enacted, in force 28 January 2001 |
| `ley-1122-h/` | Ley 1122-H: GARANTIZA DOCUMENTACION DEL DOCENTE PARA ACOGERSE A LA JUBILACION | as enacted, in force 28 January 2001 |
| `ley-1121-a/` | Ley 1121-A: ESTABLECE TARJETA DE IDENTIFICACION P/EMPLEADOS PUBLICOS | as enacted, in force 26 January 2001 |
| `ley-1119-r/` | Ley 1119-R: DECLARA AREA DE PESCA DE SUBSISTENCIA LOS RIOS BERMEJITO Y TEUCO | as enacted, in force 26 January 2001 |
| `ley-1117-a/` | Ley 1117-A: CREA VARIOS JUZGADOS EN RESISTENCIA, VILLA ANGELA Y SAENZ PEÑA. | as enacted, in force 26 January 2001 |
| `ley-1115-t/` | Ley 1115-T: REGIMEN DE PUERTOS ESTATALES Y PARTICULARES | as enacted, in force 19 January 2001 |
| `ley-1112-a/` | Ley 1112-A: OBLIGATORIEDAD DE HACER CONSTAR EL NRO. DE CUIL EN RECIBO DE SUELDO | as enacted, in force 14 January 2001 |
| `ley-1113-x/` | Ley 1113-X: APRUEBA COMPROMISO FEDERAL CON LA NACION Y GOB. PCIALES. Y LA ADDENDA | as enacted, in force 5 January 2001 |
| `ley-1107-i/` | Ley 1107-I: APRUEBA PLAN ESTRATEGICO PARA AREAS Y PARQUES INDUSTRIALES DEL CHACO | as enacted, in force 24 December 2000 |
| `ley-1101-e/` | Ley 1101-E: "PROMESA DE LEALTAD A LA BANDERA" PARA PERSONAS ADULTAS DIA 20-06 C/A. | as enacted, in force 24 December 2000 |
| `ley-1105-k/` | Ley 1105-K: CREA PROGRAMA PCIAL. DE PREMIOS E INCENTIVOS DEL IPDUV. | as enacted, in force 20 December 2000 |
| `ley-1104-r/` | Ley 1104-R: CREA COMISION PROVINCIAL DE EMERGENCIA AGROPECUARIA. DEROGA L.1254 | as enacted, in force 20 December 2000 |
| `ley-1103-r/` | Ley 1103-R: ESTABLECE CUPO HASTA 15% P/ HIJOS DE PEQUEÑOS Y MEDIANOS PRODUCTORES | as enacted, in force 20 December 2000 |
| `ley-1102-e/` | Ley 1102-E: CREA EL PROGRAMA MOVILIZADOR "TODOS LOS NIÑOS A LA ESCUELA" | as enacted, in force 20 December 2000 |
| `ley-1099-w/` | Ley 1099-W: CREA REGISTRO ESPECIAL DE COMUNIDADES Y ORGANIZACIONES INDIGENAS | as enacted, in force 6 December 2000 |
| `ley-1098-c/` | Ley 1098-C: CREA PROGRAMA DE LUCHA Y PREVENCION CONTRA EL JUEGO CLANDESTINO | as enacted, in force 6 December 2000 |
| `ley-1097-x/` | Ley 1097-X: CONVENIO P/CONSTR. ACUEDUCTO CENTRO OESTE CHAQUEÑO PROV. AGUA POTABLE | as enacted, in force 15 November 2000 |
| `ley-1096-j/` | Ley 1096-J: CREA PROGRAMA "PROVINCIAL DE ASISTENCIA A LAS VICTIMAS DEL DELITO" | as enacted, in force 12 November 2000 |
| `ley-1095-e/` | Ley 1095-E: ADHESION L.N.25273 -INASISTENCIAS JUSTIFIC. POR GRAVIDEZ P/ALUMNAS- | as enacted, in force 5 November 2000 |
| `ley-1094-g/` | Ley 1094-G: ADHESION L.N.24455 -OBLIGACION OBRAS SOCIALES CUBRIR GASTOS DE SIDA- | as enacted, in force 5 November 2000 |
| `ley-1093-w/` | Ley 1093-W: CREA REGISTRO DE NOMBRES INDIGENAS DE LA PROVINCIA | as enacted, in force 5 November 2000 |
| `ley-1092-a/` | Ley 1092-A: ORGANIZ. Y FUNCIONAM. ADMINISTR. FINANCIERA SECTOR PUBLICO PROVINCIAL | current text only, as of 23 February 2026 |
| `ley-1091-a/` | Ley 1091-A: CONFORMASE LA "COMISION DE SEGUIMIENTO LEGISLATIVO" CREADO POR L.951-X (ANTES LEY 4492) | as enacted, in force 29 October 2000 |
| `ley-1090-u/` | Ley 1090-U: ADHESION "DIA INTERNACIONAL DE RADIO Y TELEV. EN FAVOR DE LOS NIÑOS" | as enacted, in force 29 October 2000 |
| `ley-1088-g/` | Ley 1088-G: CREA EL CONSEJO PROVINCIAL DE BIOETICA | as enacted, in force 22 October 2000 |
| `ley-1089-e/` | Ley 1089-E: DECLARA "MES DE LOS EDUCADORES Y EDUCANDOS" AL MES DE SEPTIEMBRE DE CADA AÑO | as enacted, in force 20 October 2000 |
| `ley-1087-g/` | Ley 1087-G: CREA "COMISION PROVINCIAL DE CUIDADOS PALIATIVOS" | as enacted, in force 20 October 2000 |
| `ley-1086-f/` | Ley 1086-F: EXIME IMPUESTO DE SELLOS P/COMPRA DE VIVIENDA PROPIA | as enacted, in force 20 October 2000 |
| `ley-1067-a/` | Ley 1067-A: EXPROPIA INMUEBLES EN RCIA. P/ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 20 October 2000 |
| `ley-1085-a/` | Ley 1085-A: ADHESION L.N.24146 -TRANSFERENCIA DE INMUEBLES INNECESARIOS- | as enacted, in force 24 September 2000 |
| `ley-1084-h/` | Ley 1084-H: CREA PROGRAMA DE AYUDA PCIAL (P.A.PRO.) Y MUNICIPAL (P.A.M.) | as enacted, in force 17 September 2000 |
| `ley-1082-r/` | Ley 1082-R: CREA PARQUE CHAQUEÑO ARTICULADO -AREAS DE METEORITOS- | as enacted, in force 8 September 2000 |
| `ley-1081-a/` | Ley 1081-A: AUTORIZA AL IN.S.S.SE.P. TRANSFERIR INMUEBLE AL MUNICIPIO DE S. MARTIN | as enacted, in force 8 September 2000 |
| `ley-1079-r/` | Ley 1079-R: CREA GUIA DE APROVECHAMIENTO DE RESIDUOS O SUBPRODUCTOS RECICLABLES | as enacted, in force 8 September 2000 |
| `ley-1078-g/` | Ley 1078-G: HABILITACION DE MESAS DESTINADA A INFORMAR SOBRE DONACION DE ORGANOS | as enacted, in force 13 August 2000 |
| `ley-1077-e/` | Ley 1077-E: LEY DE COOPERACIÓN ACADÉMICA Y ASISTENCIA TÉCNICA | as enacted, in force 13 August 2000 |
| `ley-1076-p/` | Ley 1076-P: FIJA LIMITE DIVISORIO MUNICIPIOS DE BARRANQUERAS Y RESISTENCIA | as enacted, in force 4 August 2000 |
| `ley-1075-b/` | Ley 1075-B: REGLAMENTA ART.103 CONSTITUCION PROVINCIAL 1957-1994 (DESAFUERO) | as enacted, in force 23 July 2000 |
| `ley-1074-j/` | Ley 1074-J: CREA REGISTRO DE ACTIVIDADES COMERCIALES NOCTURNAS DE ACCESO PUBLICO | as enacted, in force 23 July 2000 |
| `ley-1070-f/` | Ley 1070-F: CREA FONDO DE GARANTÍA PROVINCIAL PARA LA MICRO, PEQUEÑA Y MEDIANA EMPRESA | as enacted, in force 14 July 2000 |
| `ley-1069-f/` | Ley 1069-F: FONDO PCIAL. P/EL DESARROLLO DE LA MICRO, PEQUEÑA Y MEDIANA EMPRESA | as enacted, in force 14 July 2000 |
| `ley-1072-e/` | Ley 1072-E: ADHESION L.N.25197 -REGISTRO DE BIENES CULTURALES- | as enacted, in force 14 July 2000 |
| `ley-1071-d/` | Ley 1071-D: MARCO NORMATIVO P/PROMOVER FUNCIONAMIENTO DE MERCADOS ELECTR. DE PROD. | as enacted, in force 14 July 2000 |
| `ley-1057-e/` | Ley 1057-E: CREA EL PLAN PROVINCIAL DE MEDIACION ESCOLAR | as enacted, in force 14 July 2000 |
| `ley-1073-e/` | Ley 1073-E: ADHESION L.N.20561 -DIA DE LOS DERECHOS ARGENTINOS SOBRE MALVINAS- | as enacted, in force 12 July 2000 |
| `ley-1066-a/` | Ley 1066-A: ADHESION D.N.229/00 -CARTA COMPROMISO CON EL CIUDADANO- | as enacted, in force 5 July 2000 |
| `ley-1065-k/` | Ley 1065-K: SISTEMA DE CONCESION DEL SERVICIO ELECTRICO PCIAL. EN EL AREA RURAL | as enacted, in force 5 July 2000 |
| `ley-1064-r/` | Ley 1064-R: GESTION P/PRESERVACION Y MEJORAMIENTO PAISAJES URBANO, RURAL E INDUS. | as enacted, in force 30 June 2000 |
| `ley-1059-b/` | Ley 1059-B: ADHESION AL "AÑO INTERNACIONAL DE LA CULTURA DE LA PAZ" | as enacted, in force 14 June 2000 |
| `ley-1063-f/` | Ley 1063-F: LEY DE AJUSTE - SOLVENCIA FISCAL, CONTENCION Y REDUC.DEL GASTO PUBLICO | as enacted, in force 31 May 2000 |
| `ley-1062-f/` | Ley 1062-F: CONVENIO CON EL FONDO FIDUCIARIO P/EL DESARROLLO PROVINCIAL | as enacted, in force 31 May 2000 |
| `ley-1039-a/` | Ley 1039-A: EXPROPIA INMUEBLES EN RESISTENCIA PARA ADJUDICAR EN VENTA A ACTUALES OCUPANTES | as enacted, in force 26 May 2000 |
| `ley-1055-g/` | Ley 1055-G: ADHESION L.N.23753 -DIABETES- | as enacted, in force 14 April 2000 |
| `ley-1050-x/` | Ley 1050-X: CONVENIOS PARA LA CAPACITACIÓN, MANEJO Y CONSERVACIÓN DE SUELOS Y AGUA ZONAS RURALES | as enacted, in force 23 January 2000 |
| `ley-1049-e/` | Ley 1049-E: CREA "PLAN EDUCAT. Y DE COMUNIC. SOCIAL P/LA PREVENCION DE ADICCIONES" | as enacted, in force 23 January 2000 |
| `ley-1033-g/` | Ley 1033-G: REGIMEN P/EL EJERCICIO DE LA PROFESION DE LICENCIADO EN FONOAUDILOGIA | as enacted, in force 16 January 2000 |
| `ley-1052-f/` | Ley 1052-F: DETERMINA PORCENTAJE DEL CRÉDITO PÚBLICO (ART. 63 CONSTITUCIÓN PROVINCIAL 1957-1994) | as enacted, in force 12 January 2000 |
| `ley-1053-a/` | Ley 1053-A: LEY DE INICIATIVAS PRIVADAS | as enacted, in force 12 January 2000 |
| `ley-1051-a/` | Ley 1051-A: AMPLIA FACULTADES OTORGADAS AL PODER EJECUTIVO PROVINCIAL POR LEY Nº 1019 -F (ANTES L. 4638) | as enacted, in force 12 January 2000 |
| `ley-1044-g/` | Ley 1044-G: INSTITUYE EL DIA PROVINCIAL DE LA DONACION DE ORGANOS | as enacted, in force 9 January 2000 |
| `ley-1048-f/` | Ley 1048-F: EL PODER EJECUTIVO SUSCRIBIRÁ Y APORTARA AL FONDO DE RIESGO DE GARANTIZAR S.G.R. -SOCIEDAD DE GARANTÍA RECÍPROCA- | as enacted, in force 5 January 2000 |
| `ley-1045-e/` | Ley 1045-E: DETERMINA INSCRIPCION PROVISORIA A ALUMNOS MENOR DE 18 AÑOS SIN D.N.I. | as enacted, in force 5 January 2000 |
| `ley-1047-x/` | Ley 1047-X: APRUEBA CONVENIO DE ASISTENCIA FINANCIERA CON EL FONDO FIDUCIARIO | as enacted, in force 29 December 1999 |
| `ley-1043-c/` | Ley 1043-C: PROHIBE JUEGOS MECANICOS, ELECTRICOS, ELECTRONICOS, ELECTROMEC. ETC. | as enacted, in force 26 December 1999 |
| `ley-1034-r/` | Ley 1034-R: CREA EL FONDO P/EL DESARROLLO Y CRECIMIENTO DE LA FRUTIHORTICULTURA | as enacted, in force 22 December 1999 |
| `ley-1035-a/` | Ley 1035-A: EXPROPIA TERRENO EN COLONIA ELISA P/ LA APERTURA DE UNA CALLE PUBLICA | as enacted, in force 19 December 1999 |
| `ley-1031-e/` | Ley 1031-E: CREA CONSEJO PCIAL. DE MOVILIZACION PRODUCTIVA DE LOS RECUR. UNIVERS. | as enacted, in force 24 November 1999 |
| `ley-1027-a/` | Ley 1027-A: CREA EN LA PROVINCIA DEL CHACO EL SISTEMA DE AUDIENCIAS PUBLICAS | as enacted, in force 22 October 1999 |
| `ley-1026-x/` | Ley 1026-X: APRUEBA CONVENIO POR EXTENSION SERVICIOS FERROVIARIOS SEFECHA S.A. | as enacted, in force 10 October 1999 |
| `ley-1025-h/` | Ley 1025-H: CREA SISTEMA DE PREVISION PARA KINESIOLOGOS. DEROGA L.3985 | as enacted, in force 1 October 1999 |
| `ley-1018-x/` | Ley 1018-X: CREA LA REGION NORTE GRANDE ARGENTINO -NOA-NEA- | as enacted, in force 27 August 1999 |
| `ley-1022-e/` | Ley 1022-E: ADHESION L.N.25053 -INCENTIVO DOCENTE- | as enacted, in force 22 August 1999 |
| `ley-1021-f/` | Ley 1021-F: FACULTA AL P.E. A CONTRAER PRESTAMO POR HASTA U$S5.000.000 | as enacted, in force 22 August 1999 |
| `ley-1015-a/` | Ley 1015-A: EL P.E. TRANSFIERE INMUEBLE EN BQUERAS. A LA ASOC. DE AYUDA AL MENOR | as enacted, in force 22 August 1999 |
| `ley-1014-a/` | Ley 1014-A: EL I.N.S.S.SE.P. TRANSFIERE INMUEBLE EN GENERAL JOSE DE SAN MARTIN | as enacted, in force 22 August 1999 |
| `ley-1013-h/` | Ley 1013-H: CREA LA CAJA DE PREVISION SOCIAL PARA EX-AGENTES DEL BCO. CHACO S.E.M. | as enacted, in force 22 August 1999 |
| `ley-1011-n/` | Ley 1011-N: EXAMEN FISICO PARA DETENIDOS POR PERSONAL POLICIAL | as enacted, in force 22 August 1999 |
| `ley-1020-f/` | Ley 1020-F: FACULTA AL P.E. A TRAMITAR PRESTAMO POR HASTA U$S2.000.000 | as enacted, in force 15 August 1999 |
| `ley-1019-f/` | Ley 1019-F: REPROGRAMACION DE LA DEUDA PUBLICA | as enacted, in force 15 August 1999 |
| `ley-1006-x/` | Ley 1006-X: FACULTA AL PODER EJECUTIVO A SUSCRIBIR CONVENIOS CON POBLADORES NO ABORIGENES | as enacted, in force 6 August 1999 |
| `ley-1003-g/` | Ley 1003-G: CREA EN LA PCIA. "ENTIDADES DE MEDICINA PREPAGA" (EMP) | as enacted, in force 23 July 1999 |
| `ley-1002-r/` | Ley 1002-R: DECLARA RESERVA DE RECURSOS, FRACCION DE TIERRA EN DPTO. GRAL.GUEMES | as enacted, in force 2 July 1999 |
| `ley-1001-r/` | Ley 1001-R: ADHESION L.N.25080 -INVERSIONES P/BOSQUES CULTIVADOS- | as enacted, in force 2 July 1999 |
| `ley-1000-u/` | Ley 1000-U: SERVICIOS DE RADIODIFUSION QUEDAN SUJETOS A JURISDICCION DE LA PCIA. | as enacted, in force 2 July 1999 |
| `ley-998-l/` | Ley 998-L: RATIFICA "PACTO FEDERAL DEL TRABAJO" MODIFICA Y DEROGA ARTS. L.481-L (ANTES L. 2956) | as enacted, in force 16 June 1999 |
| `ley-980-x/` | Ley 980-X: CONVENIO DE COOP.DE ELECTRICIDAD RURAL CON S.E.CH.E.E.P. P/SUMINISTRO | as enacted, in force 10 June 1999 |
| `ley-974-j/` | Ley 974-J: CREA COMISION ASESORA DE SEGURIDAD DE EDIFICIOS PUBLICOS  PCIALES. | as enacted, in force 9 June 1999 |
| `ley-958-v/` | Ley 958-V: INCORPORA CALENDARIO TURISTICO PCIAL. DESFILE CARROZAS ESTUDIANTES | as enacted, in force 18 April 1999 |
| `ley-977-e/` | Ley 977-E: CREA REGIMEN DE RESIDENCIAS EN EL AMBITO DE LOS PODERES EL ESTADO | as enacted, in force 27 January 1999 |
| `ley-988-k/` | Ley 988-K: NORMA P/LOS INMUEBLES DONADOS POR MUNICIPIOS AL I.P.D.U.V. P/VIVIENDAS | as enacted, in force 27 January 1999 |
| `ley-986-h/` | Ley 986-H: EL IN.S.S.SE.P. GESTIONARA RECUPERO DE APORTES JUB.PERSONAL BANCARIO | as enacted, in force 27 January 1999 |
| `ley-989-f/` | Ley 989-F: AUTORIZA AL P.E. CONTRAER UN PRESTAMO DE HASTA $10.000.000,- | as enacted, in force 15 January 1999 |
| `ley-987-x/` | Ley 987-X: EL P.E. APORTARA $400.000, S/ACUERDOS CON LA PCIA. AUTONOMA DE TRENTO | as enacted, in force 15 January 1999 |
| `ley-979-e/` | Ley 979-E: ADHESION L.N.24800 -TEATRO- | current text only, as of 21 June 2018 |
| `ley-981-e/` | Ley 981-E: DECLARA A RCIA. "CIUDAD DE LAS ESCULTURAS - PATRIMONIO CULT.DEL CHACO" | as enacted, in force 15 January 1999 |
| `ley-976-a/` | Ley 976-A: EXPROPIA INMUEBLE EN RCIA. P/CONSTR.ESTACION DE BOMBEO S.A.M.E.E.P. | as enacted, in force 15 January 1999 |
| `ley-983-x/` | Ley 983-X: PRESTAMO P/"PROYECTO DE EMERGENCIA DE INUNDACIONES EL NIÑO" | as enacted, in force 13 January 1999 |
| `ley-972-a/` | Ley 972-A: CREA EN LA PROVINCIA DEL CHACO EL SISTEMA DE INICIATIVA CIUDADANA | as enacted, in force 13 January 1999 |
| `ley-960-k/` | Ley 960-K: USO MADERAS Y LADRILLOS PRODUCIDOS EN LA PROVINCIA. DEROGA L.4242 Y 4451 | as enacted, in force 6 January 1999 |
| `ley-971-f/` | Ley 971-F: MODIFICA VARIOS ARTICULOS E INCISOS  L. 83-F (Antes D.L.2444/62) y L.299-F (Antes L.2071). | as enacted, in force 27 December 1998 |
| `ley-975-k/` | Ley 975-K: AUTORIZA AL P.E., A CONTRAER PRESTAMOS DE $ 5.000.000 EN EL MARCO DE LA LEY Nº 24855 | as enacted, in force 27 December 1998 |
| `ley-969-e/` | Ley 969-E: ADHESION L.N.14613 -ENTIDAD DE BIEN PUBLICO COOPERADORAS ESCOLARES- | as enacted, in force 25 December 1998 |
| `ley-970-x/` | Ley 970-X: ADHESION L.N.25048 -CONSERVACION RECURSOS ICTICOS- | as enacted, in force 23 December 1998 |
| `ley-968-g/` | Ley 968-G: CREA REGISTRO PROVINCIAL DE TUMORES CON BASE POBLACIONAL | as enacted, in force 20 December 1998 |
| `ley-966-i/` | Ley 966-I: DECLARA DE INTERES PCIAL. LA ACTIVIDAD APICOLA - DEROGA L.2977 | as enacted, in force 6 December 1998 |
| `ley-964-a/` | Ley 964-A: CREA JUZGADO DE FALTAS CATEGORIA PRIMERA ESPECIAL EN SAN MARTIN | as enacted, in force 27 November 1998 |
| `ley-962-a/` | Ley 962-A: CREA CAMARA CONTENCIOSO ADMINISTRATIVO DE UNICA INSTANCIA EN RCIA. | as enacted, in force 15 November 1998 |
| `ley-963-d/` | Ley 963-D: CREA SISTEMA PROVINCIAL DE ARBITRAJE DE CONSUMO | as enacted, in force 11 November 1998 |
| `ley-961-a/` | Ley 961-A: CREA JUZGADO DE PAZ DE 3RA. CATEGORIA EN MIRAFLORES | as enacted, in force 28 October 1998 |
| `ley-957-g/` | Ley 957-G: REGIMEN PARA EL EJERCICIO DE LA PROFESION DE LICENCIADO EN NUTRICION | as enacted, in force 7 October 1998 |
| `ley-947-g/` | Ley 947-G: REGIMEN PARA EL EJERCICIO DE LA PROFESION DE MUSICOTERAPIA EN LA PCIA. | as enacted, in force 19 June 1998 |
| `ley-941-a/` | Ley 941-A: EXPROPIA INMUEBLE  P/ARCHIVO HISTORICO Y MUSEO (EX DIARIO EL TERRITORIO) | as enacted, in force 16 January 1998 |
| `ley-935-a/` | Ley 935-A: EXPROPIA 150 HAS. EN COLONIA PASTORIL PARA ADJUDICAR A SUS OCUPANTES | as enacted, in force 16 January 1998 |
| `ley-904-g/` | Ley 904-G: SERVICIOS PRESTADOS A TERCEROS POR SALUD PUBLICA SERAN ARANCELADOS | as enacted, in force 24 January 1997 |
| `ley-901-e/` | Ley 901-E: CREA "FONDO EDITORIAL P/DIFUSION Y PROMOCION LITERATURA CHAQUEÑA" | as enacted, in force 17 January 1997 |
| `ley-898-b/` | Ley 898-B: ACCION DE HABEAS DATA (ART.19 CONSTITUCION PCIAL. 1957-1994) | as enacted, in force 29 December 1996 |
| `ley-887-b/` | Ley 887-B: NORMA P/CASOS DE ACEFALIA, INTERVENCION Y ELECCIONES DE MUNICIPIOS | as enacted, in force 27 December 1996 |
| `ley-897-g/` | Ley 897-G: CONVENIO DE ADHESION AL PROGRAMA MATERNO-INFANTIL Y NUTRICION | current text only, as of 15 November 2018 |
| `ley-891-n/` | Ley 891-N: NUEVO REGIMEN DE INDULTO Y CONMUTACION DE PENAS | as enacted, in force 22 November 1996 |
| `ley-888-c/` | Ley 888-C: ADHESION "PROGRAMA DE COOPER. TECNICA EN PCIAS. Y MUNICIPIOS" | as enacted, in force 25 October 1996 |
| `ley-886-b/` | Ley 886-B: REGLAMENTA ACCION DE HABEAS CORPUS (ART.19 C.P. 1957.1994) | as enacted, in force 25 September 1996 |
| `ley-877-b/` | Ley 877-B: REGLAMENTA ACCION DE AMPARO (ART.19 C.P.1957-1994) | current text only, as of 9 March 2018 |
| `ley-885-e/` | Ley 885-E: CONSEJO DE EDUCACION | current text only, as of 22 March 2019 |
| `ley-881-a/` | Ley 881-A: CREA DIRECCION Y DEPARTAMENTO DE BROMATOLOGIA EN M.S.P. MODIF.L.1276 | as enacted, in force 1 September 1996 |
| `ley-882-r/` | Ley 882-R: DECLARA "MONUMENTO NATURAL PROVINCIAL" A ESPECIES DE NUESTRA FAUNA | as enacted, in force 14 July 1996 |
| `ley-875-c/` | Ley 875-C: I.P.D.U.V. PODRA CONDONAR Y REFINANCIAR DEUDAS PLANES HABITACIONALES | as enacted, in force 7 July 1996 |
| `ley-864-r/` | Ley 864-R: DIRECCION DE SANEAMIENTO AMBIENTAL ARANCELARA SERVICIOS A TERCEROS | as enacted, in force 4 February 1996 |
| `ley-846-k/` | Ley 846-K: DECLARA LA FUNCION SOCIAL Y PRODUCTIVA DE LOS SERVICIOS DE AGUA Y LUZ | as enacted, in force 31 December 1995 |
| `ley-848-h/` | Ley 848-H: DEBERA DETALLARSE EN RECIBOS DE HABERES DESCUENTOS INSSSEP | as enacted, in force 24 September 1995 |
| `ley-845-f/` | Ley 845-F: AUTORIZA AL P.E. GARANTIZAR CREDITOS POR COMBUSTIBLE A PRODUCTORES | as enacted, in force 20 September 1995 |
| `ley-842-x/` | Ley 842-X: PROGRAMA DE INVERSIONES SOCIALES MUNICIPALES (PRODIISM) | as enacted, in force 8 September 1995 |
| `ley-807-i/` | Ley 807-I: PROGRAMA DE PROMOCION PARA EL DESARROLLO PRODUCTIVO PROVINCIAL | as enacted, in force 8 September 1995 |
| `ley-837-e/` | Ley 837-E: DECLARA EL 07 DE JUNIO "DIA DEL PUERTO DE BARRANQUERAS" | as enacted, in force 13 August 1995 |
| `ley-840-f/` | Ley 840-F: NUEVAS TASAS PARA ACTUACIONES JUDICIALES ANTE TRIBUNALES PROVINCIALES | as enacted, in force 6 August 1995 |
| `ley-839-a/` | Ley 839-A: AUTARQUIA DEL PODER JUDICIAL | as enacted, in force 6 August 1995 |
| `ley-823-g/` | Ley 823-G: REGLAMENTA EL EJERCICIO DE LA OBSTETRICIA | as enacted, in force 26 July 1995 |
| `ley-832-e/` | Ley 832-E: DECLARA DE INTERES PCIAL. OBRAS COMPLETAS DEL ESCRITOR GUIDO MIRANDA | as enacted, in force 23 June 1995 |
| `ley-829-f/` | Ley 829-F: CREA FONDO "UNICO DE RECURSOS POLICIALES PROPIOS" MODIF. LS.299-F Y 850-P | as enacted, in force 28 May 1995 |
| `ley-826-d/` | Ley 826-D: ADHESION L.N.24240 -DEFENSA DEL CONSUMIDOR- | as enacted, in force 21 May 1995 |
| `ley-828-r/` | Ley 828-R: MODIFICA ARTS.68, 75 Y 79 LEY Nº 486-C (ANTES LEY 2972). CREA EL FONDO LEY DE MARCAS Y SEÑALES. | as enacted, in force 30 April 1995 |
| `ley-827-x/` | Ley 827-X: RATIFICA ACUERDO RESPECTO DE DISTRIBUCION DE REGALIAS HIDROELECTRICAS | current text only, as of 31 August 2018 |
| `ley-824-a/` | Ley 824-A: EXPROPIA INMUEBLE EN RCIA. P/ENTREGAR EN VENTA A SUS OCUPANTES | as enacted, in force 19 April 1995 |
| `ley-825-f/` | Ley 825-F: ADHESION D.N.1499/94.-REFORMA DE ESTADOS PCIALES.- MONTO MAXIMO BOCEP | as enacted, in force 14 April 1995 |
| `ley-809-r/` | Ley 809-R: DECLARA DE INTERES PCIAL. DESARROLLO DEL SISTEMA DE RIEGO ARTIFICIAL | as enacted, in force 22 February 1995 |
| `ley-819-e/` | Ley 819-E: DECLARA INTERES PCIAL. FORMACION DE PROFESIONALES Y TECNICOS DE SALUD | as enacted, in force 18 January 1995 |
| `ley-818-b/` | Ley 818-B: EL PODER LEGISLATIVO HARA ORDENAMIENTO DE LAS LEYES (TEXTO ORDENADO) | as enacted, in force 6 January 1995 |
| `ley-816-b/` | Ley 816-B: CREA REGISTRO DE SUGERENCIAS PARA REGLAMENTAR LA NUEVA CONSTITUCION | as enacted, in force 23 December 1994 |
| `ley-808-d/` | Ley 808-D: EL P.E. PROMOVERA CREACION DE MERCADOS DE CONCENTRACION DE ALIMENTOS | as enacted, in force 16 December 1994 |
| `ley-815-f/` | Ley 815-F: LOS BO.SA.FI TENDRAN MISMA AFECTACION QUE L.3872. PRESTAMO ROTATIVO | as enacted, in force 9 November 1994 |
| `ley-802-a/` | Ley 802-A: EXPROPIA INMUEBLE EN SAENZ PEÑA P/OFICINAS DEL PODER JUDICIAL | as enacted, in force 25 September 1994 |
| `ley-803-a/` | Ley 803-A: EXPROPIA INMUEBLE EN RCIA. P/FUNCIONAMIENTO COMISARIA SEC. DECIMA | as enacted, in force 18 September 1994 |
| `ley-801-a/` | Ley 801-A: MODIFICA PLANILLA ANEXA "B" DEL ART. 5 LEY 196-A (ANTES LEY1276) | as enacted, in force 11 September 1994 |
| `ley-799-f/` | Ley 799-F: MODIFICA ARTS.62, 63 Y 64 D.L.2444/62 | as enacted, in force 12 August 1994 |
| `ley-783-r/` | Ley 783-R: REGIMEN DE PRESERVACION Y RECUPERACION DEL MEDIO AMBIENTE | as enacted, in force 12 August 1994 |
| `ley-798-a/` | Ley 798-A: EXPROPIA INMUEBLE EN RCIA. P/ORGANISMOS DEL PODER JUDICIAL | as enacted, in force 24 July 1994 |
| `ley-795-e/` | Ley 795-E: APRUEBA PLAN DE ESTUDIOS DE TECNICO EN DESARROLLO AMBIENTAL | as enacted, in force 26 June 1994 |
| `ley-793-e/` | Ley 793-E: DECLARA "CAPITAL PROVINCIAL DEL METEORITO" A LA LOCALIDAD DE GANCEDO | as enacted, in force 17 June 1994 |
| `ley-796-a/` | Ley 796-A: APRUEBA PROCESO LICITATORIO Y ADJUDICACION DEL BCO. DEL CHACO S.E.M. | as enacted, in force 25 May 1994 |
| `ley-792-e/` | Ley 792-E: DECLARA DE INTERES PROVINCIAL EL TEXTO "MALVINAS" | as enacted, in force 25 May 1994 |
| `ley-791-r/` | Ley 791-R: ADHESION L.N.24305 -FIEBRE AFTOSA- | as enacted, in force 22 May 1994 |
| `ley-790-j/` | Ley 790-J: CREA "FONDO DE SERVICIOS DE ALARMA A DISTANCIA" | as enacted, in force 15 May 1994 |
| `ley-789-f/` | Ley 789-F: AUTORIZA AL P.E. LA LIBRE DISPONIBILIDAD DE LOS "BOCON" | as enacted, in force 20 April 1994 |
| `ley-787-h/` | Ley 787-H: REGIMEN PREVISIONAL PARA BIOQUIMICOS | as enacted, in force 30 March 1994 |
| `ley-786-h/` | Ley 786-H: CREA SISTEMA PREVISIONAL P/PROFESIONALES EN CIENCIAS ECONOMICAS | as enacted, in force 18 February 1994 |
| `ley-785-h/` | Ley 785-H: CREA SISTEMA PREVISIONAL PARA ODONTOLOGOS | as enacted, in force 16 February 1994 |
| `ley-781-r/` | Ley 781-R: ADHESION CAPITULO I L.N.24224 - CARTEO GEOLOGICO TERRIT. CONTINENTAL- | as enacted, in force 12 January 1994 |
| `ley-780-f/` | Ley 780-F: BONOS CHAQUEÑOS DE CONSOLIDACION | as enacted, in force 12 January 1994 |
| `ley-777-r/` | Ley 777-R: REGIMEN DE RESIDUOS PELIGROSOS | as enacted, in force 31 December 1993 |
| `ley-770-r/` | Ley 770-R: DECLARA LA PROTECCION DE LOS INTERESES DIFUSOS Y COLECTIVOS | as enacted, in force 22 December 1993 |
| `ley-774-r/` | Ley 774-R: DECLARA DE INTERES PCIAL. ACTIVIDAD FRUTIHORTICOLA | as enacted, in force 12 November 1993 |
| `ley-773-f/` | Ley 773-F: EXIME DE IMPUESTOS A ACTOS RELACIONADOS CON CREACION NUEVO BCO. CHACO | as enacted, in force 29 October 1993 |
| `ley-772-x/` | Ley 772-X: APRUEBA EL PACTO FEDERAL P/EL EMPLEO, LA PRODUCCION Y EL CRECIMIENTO | as enacted, in force 6 October 1993 |
| `ley-771-x/` | Ley 771-X: RATIFICA EL PACTO FEDERAL AMBIENTAL ENTRE LA NACION Y LAS PCIAS. | as enacted, in force 24 September 1993 |
| `ley-769-g/` | Ley 769-G: ADHESION L.N.23798 -BIOSEGURIDAD (SIDA)- | current text only, as of 5 November 2018 |
| `ley-767-r/` | Ley 767-R: DECLARA A LA PROVINCIA DEL CHACO "ZONA NO NUCLEAR" | as enacted, in force 27 August 1993 |
| `ley-765-b/` | Ley 765-B: PROHIBE EN LA PROVINCIA PERSECUCION IDEOLOGICA | as enacted, in force 18 August 1993 |
| `ley-762-e/` | Ley 762-E: APRUEBA PLAN DE ESTUDIOS DE TÉCNICO MADERERO PARA ESCUELA DE EDUCACIÓN TÉCNICA | as enacted, in force 11 August 1993 |
| `ley-763-i/` | Ley 763-I: DECLARA DE INTERES PCIAL. EXPERIMENTACION GARBANZO Y EL POROTO | as enacted, in force 6 August 1993 |
| `ley-761-e/` | Ley 761-E: APRUEBA PLAN DE ESTUDIO P/NIVEL MEDIO MODALIDAD COMERCIAL DIURNO | as enacted, in force 1 August 1993 |
| `ley-759-n/` | Ley 759-N: ADHIÉRESE LA PROVINCIA DEL CHACO AL CAPÍTULO I DE LA LEY NACIONAL 24.192, REFERENTE AL RÉGIMEN PENAL Y CONTRAVENCIONAL PARA LA PREVENCIÓN Y REPRESIÓN… | as enacted, in force 14 July 1993 |
| `ley-760-f/` | Ley 760-F: EXIME IMPUESTO SOBRE INGRESOS BRUTOS AL FONDO DE PROV. DE COMBUSTIBLE | as enacted, in force 11 July 1993 |
| `ley-755-e/` | Ley 755-E: DECLARA PATRIMONIO HISTORICO ANTIGUO ASENTAMIENTO DE PUERTO BERMEJO | as enacted, in force 7 July 1993 |
| `ley-758-a/` | Ley 758-A: AUTORIZA AL P.E CREAR UNA S.A. BAJO DENOMINACION NUEVO BCO. DEL CHACO | current text only, as of 18 March 2019 |
| `ley-757-x/` | Ley 757-X: APRUEBA CONVENIO QUE SIRVE DE ANEXO A L.3871. CREA NUEVO BCO. CHACO | as enacted, in force 25 June 1993 |
| `ley-756-x/` | Ley 756-X: APRUEBA ACUERDO DE SANEAMIENTO FINANCIERO ENTRE LA PCIA. Y LA NACION | as enacted, in force 25 June 1993 |

## Source

Digesto Jurídico del Poder Legislativo de la Provincia del Chaco (digesto.legislaturachaco.gob.ar), Dirección de Información Parlamentaria, Cámara de Diputados del Chaco, <https://digesto.legislaturachaco.gob.ar/>. For each law: its record (digest number, sanción, promulgation and publication dates, Boletín Oficial number) and its text as a PDF with a text layer ("copia digital" of the Dirección de Información Parlamentaria). The constitution is the Editorial Parlamentaria PDF of the Constitución de la Provincia del Chaco 1957-1994 with its later enmiendas (Leyes 6436 and 7232) worked in.

## Dates

- Each commit is dated at **noon, America/Argentina/Cordoba, on the day the norm took effect**: the day its own vigencia clause names, or otherwise the ninth day after its publication in the Boletín Oficial de la Provincia del Chaco (Código Civil y Comercial de la Nación, arts. 5 and 6).
- The constitution is the 1994 text with the enmiendas of Ley 6436 (2009, art. 75) and Ley 7232 (2013, art. 90 inc. 2) worked in, shown as its current text only, dated the day Ley 7232 took effect (21 June 2013: published 12 June 2013, Boletín Oficial 9509, in force on the ninth day). Codes are the digest's consolidated texts, current text only, dated by the day the digest verified their record. Laws are their PDF texts from the digest; a law whose record or text notes a later change is its current text only, dated by the day the digest verified its record; every other law is as enacted, dated the day it took effect.
- Versions that take effect after the retrieval day are on the `futuro` branch, never merged into `main`.

## Files

`<norm>/art-005.md` is Artículo 5, `art-005-bis.md` Artículo 5 bis; `encabezado.md` holds the number, the enacting formula and anything printed before Artículo 1. Section headings, signatures and the source's amendment notes stay in the file of the article they follow. One paragraph per line.

## How it is checked

- Every version of every norm is read back from git on the day it took effect and on the day before (`tools/check_repo.py`); both must match `corpus.json`.
- The letters and digits of every version equal those of the source document it was read from (read again with an independent HTML reader), so no word is lost or added.
- Health checks: no merge commits, commit dates never go backwards, nothing dated in the future, and every commit's trailers parse.

## Limits

This is not an official publication. The binding text is the one published in the Boletín Oficial de la Provincia del Chaco. Only the norms listed above are included, and most show only their current text.
