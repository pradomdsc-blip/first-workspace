# THEMES — modificadores que se SUMAN a las reglas del pack
# Formato: TEMATICA :: modificador_chicas | modificador_chicos | modificador_universal | notas

# ===== GRANJA / SAFARI / NATURALEZA =====
GRANJA :: - | pantalon_jeans_azul + botines_cafe + cinturon | - | botargas_vaca_gallo_caballo_gallina_cerdito
GRANJA_DE_ZENON :: = GRANJA | botargas_zenon_bartolito_vaca_lola
GRANJA_AGRICULTURA :: = GRANJA | colores_verde_amarillo_beige_cafe
GRANJERO :: = GRANJA
SAFARI :: - | pantalon_jeans + botines_cafe + cinturon | - | colores_verde_beige_tierra
SAFARI_LEON :: = SAFARI
MICKEY_SAFARI :: = SAFARI | botargas_mickey_minnie_safari
PLIM_PLIM_SAFARI :: = PLIM_PLIM + SAFARI
BOSQUE_ENCANTADO :: short_corto | botines + pantalon_neutro | - | hadas_duendes_flores_mariposas
JARDIN_ENCANTADO :: short_corto + calsa_corta | - | -
MARIPOSAS :: short_corto + calsa_corta | - | -
FLORES_Y_MARIPOSAS :: = MARIPOSAS
JARDIN_Y_MARIPOSAS :: = MARIPOSAS
HADAS :: short_corto + calsa_corta | - | -
DINOSAURIOS :: - | - | - | zanqueros_arbol + botarga_dino
CAPIBARA :: calsa_corta | - | zapatos_blancos
ANIMALES_DEL_FONDO_DEL_MAR :: calsa_blanca + molecas | pantalon_blanco + zapatos_blancos | -
BAMBI :: - | - | - | colores_verde_amarillo_beige_pastel
POLLITOS :: pantalon_vestir_blanco + tacos | pantalon_blanco + zapatos_blancos | -

# ===== PRINCESAS / DISNEY =====
PRINCESAS :: calsa_corta(princesas_roles) | pantalon_vestir_negro + cinturon(principes) | - | princesa_sin_calsa_corta_es_error
PRINCESAS_DISNEY :: = PRINCESAS
CUENTO_DE_PRINCIPE :: = PRINCESAS
CUENTO_DE_HADAS :: = HADAS
CENICIENTA :: = PRINCESAS
BLANCA_NIEVES :: = PRINCESAS
BLANCA_NIEVES_BEBE :: = PRINCESAS
RAPUNZEL :: = PRINCESAS
LA_SIRENITA :: = PRINCESAS | cola_provista
SIRENITA :: = PRINCESAS | cola_provista
SIRENITA_ARIEL :: = PRINCESAS
SIRENAS :: = PRINCESAS | cola_provista
MOANA :: = PRINCESAS
MOANA_BEBE :: = PRINCESAS
TINKERBELL :: = HADAS
AURORA :: = PRINCESAS
BELLA_Y_BESTIA :: = PRINCESAS
ALADINO_Y_JAZMIN :: = PRINCESAS
FROZEN :: - | pantalon_azul_marino(Maickel) + zapatos_blancos | - | colores_blanco_celeste_morado
EL_PRINCIPITO :: - | - | - | colores_pasteles
CUENTO_CAPERUCITA :: calsa_corta(caperucita) | botines_beige + pantalon_beige(Luis_lobo) | zapatos_blancos(Shirley_narradora)
GATITA_MARIE_ARISTOGATOS :: calsa_blanca + molecas | pantalon_blanco + zapatos_blancos | -

# ===== DISNEY OTROS =====
MICKEY_MOUSE :: - | - | - | botargas_mickey_minnie_goofy_donald_daisy_pluto
MICKEY_Y_SUS_AMIGOS :: = MICKEY_MOUSE
DISNEY :: = MICKEY_MOUSE + PRINCESAS
MICKEY_CARRERAS :: = MICKEY_MOUSE | colores_celeste_pastel
MICKEY_CARS :: = MICKEY_MOUSE
MICKEY_CLASICO :: = MICKEY_MOUSE
MICKEY_FERRARI :: = MICKEY_MOUSE | personalizado
MICKEY_100_ANOS :: = MICKEY_MOUSE | traje_100_anos
LILO_STICH :: calsa_corta | - | zapatos_blancos | botarga_stich_Luis
LILO_Y_STICH :: = LILO_STICH
STICH :: = LILO_STICH
TOY_STORY :: - | pantalon_jeans_chupin_azul_oscuro | - | botargas_jessie_woody_buzz
REY_LEON :: - | pantalon_blanco + zapatos_blancos | - | colores_verde_beige_amarillo_naranja
SIMBA :: = REY_LEON
ZOOTOPIA :: calsa_corta(botargas) + polera_morada_AM | polera_negra + botines_negros(bailarines_tigres) | - | botargas_zorro_conejo_shakira + bailarines_tigres_plateados
PEPPA_PIG :: - | - | - | botarga_peppa
PEPPA :: = PEPPA_PIG
BAMBI :: calsa_corta | - | - | colores_verde_amarillo_beige
MONSTERS_INC :: = MICKEY_MOUSE
TIGRE_DANIEL :: - | - | - | botarga_tigre

# ===== ANIMES / KPOP / MODERNOS =====
GUERRERAS_KPOP :: calsa_corta_blanca_o_negra + basica_negra | - | zapatos_parecidos_al_personaje
HUNTRIX :: = GUERRERAS_KPOP | colores_morado_plateado/dorado
KPOP :: = GUERRERAS_KPOP
SAYA_BOYS :: - | chulo_amarillo + pantalon_jeans + zapatos_blancos | - | rol_Franco
HELLO_KITTY :: calsa_corta | - | zapatos_blancos
MY_MELODY :: = HELLO_KITTY
KUROMI :: = HELLO_KITTY | colores_morado
SNOOPY :: respetar_provisto | respetar_provisto | - | vestuario_amarillo_rojo_apostoles_2023
BARBIE :: calsa_corta | zapatos_blancos_limpios | - | personajes_barbie + zanqueros_plateados
FRUTILLITA :: - | - | - | colores_rojo_rosa
COQUETTE :: calsa_corta | - | - | colores_rosa_blanco
PREPPY :: - | - | zapatos_blancos | colores_rosa_fucsia_amarillo_blanco
CEREZAS :: calsa_corta | - | - | colores_rojo_rosa_blanco

# ===== SUPERHÉROES / ACCIÓN =====
AVENGERS :: - | - | - | colores_rojo_azul_amarillo
SPIDERMAN :: - | - | - | traje_spiderman_provisto
HOMBRE_ARANA :: = SPIDERMAN
MARVEL_Y_SIRENITA :: = SPIDERMAN + SIRENITA
BATMAN :: - | - | - | traje_batman_provisto
HARLEY_QUINN :: - | - | - | colores_azul_rojo_blanco

# ===== AUTOS / VEHÍCULOS / DEPORTE =====
CARS :: - | pantalon_jeans | - | colores_rojo_azul
HOTWHEELS :: calsa_corta + basica | - | - | colores_naranja_azul_celeste_rojo_amarillo
RAYO_MCQUEEN :: = CARS
FERRARI :: calsa_corta + basica | solera | - | personalizado
FORMULA_1 :: basica_negra | - | - | personalizado
AVIONES_Y_AVIONETAS :: - | - | - | botargas_paw_patrol
PAW_PATROL :: - | polera_blanca_manga_larga + zapatos_blancos(Rider/Anderson) | - | 2_botargas + Raider
MOUNSTER_TRUCK :: - | - | - | -
CAMIONES :: - | - | zapatos_blancos | -
MOTOCROSS :: respetar_provisto | respetar_provisto | - | personalizado
COPA_MALTIN :: = VESTUARIO_SPORT | deporte
FUTBOL :: short_deportivo + medias + zapatillas(arbitro) | - | ponchillos_provistos
FUTBOL_BARCA :: = VESTUARIO_SPORT + zapatos_blancos(show_led)
NEYMAR_REAL_MADRID :: respetar_provisto | respetar_provisto | - | vestuario_real_madrid
CHAMPIONS_LEAGUE :: = VESTUARIO_SPORT + zapatos_blancos_arbitro
SPORT :: = VESTUARIO_SPORT

# ===== FIESTA / DISCO / ESPECIALES =====
DISCO :: - | - | ropa_negra_base | si_HRL_basica_con_cuello
FIESTA_DISCO :: = DISCO
NEON :: - | pantalon_negro + zapatos_blancos | ropa_negra_base | si_HRL_ropa_negra
FIESTA_DE_DISFRACES :: respetar_provisto | respetar_provisto | -
PLAY_STATION :: - | - | - | colores_blanco_negro_azul
MINECRAFT :: - | - | zapatos_blancos | -
MR_BEATS :: - | - | zapatos_blancos | -
POOL_PARTY :: = POOL_PARTY(pack)
PLAYA :: = POOL_PARTY(pack)
CAMUFLADO :: ropa_camuflada_si_tiene | ropa_camuflada_si_tiene + polera_negra_lisa | botines_negros | para_pesca
PESCA :: = CAMUFLADO
PAINTBALL :: pantalon_negro_chupin | pantalon_negro_chupin | - | mini_hrl
MILITARES :: respetar_provisto | respetar_provisto | - | 2_asistentes_militares

# ===== NAVIDAD =====
NAVIDAD :: calsa_corta + basica_negra(cascanueces) | pantalon_blanco + camisa_blanca(cascanueces) | - | rodete_peinado_chicas
SHOW_NAVIDENO :: = NAVIDAD
PAPA_NOEL :: respetar_provisto | respetar_provisto | - | rol_papa_noel_Rilver/Ricardo/Richi
SOLDADITOS_GREEN :: calsa_corta + basica_negra | respetar_provisto | -
CASCANUECES :: calsa_corta + basica_negra | pantalon_blanco + camisa_blanca | -
MAMANUELAS :: respetar_provisto | - | -
GRINCH :: ropa_para_sudar + polera_morada_AM | ropa_para_sudar + polera_morada_AM | -
RODOLFO :: ropa_para_sudar + polera_morada_AM | ropa_para_sudar + polera_morada_AM | -
REYES_MAGOS :: respetar_provisto | respetar_provisto | - | cascanueces

# ===== OTROS / VARIOS =====
VINOS_Y_UVAS :: pantalon_vestir_negro + zapatos_blancos | - | -
VENECIANA :: = HRL_VENECIANO
ARTE_Y_PINTURA :: pantalon_blanco + zapatos_blancos | pantalon_blanco + zapatos_blancos | -
DULCES :: - | - | - | colores_pasteles
HELADERIA :: - | - | - | colores_pasteles
TRADICIONES_CRUCENAS :: tipoy + calsa_corta + apargatas_beige | pantalon_blanco + camisa_blanca | -
SANTA_CRUZ :: = TRADICIONES_CRUCENAS
DANZA :: respetar_provisto | respetar_provisto | - | bailes_tipicos
CARNAVAL :: pantalon_blanco + camisa_blanca + calsa_blanca + molecas | pantalon_blanco + cinturon + camisa_blanca | -
CARRUSEL :: - | - | - | colores_rosa_beige
CIRCO_CARRUSEL :: = CARRUSEL | colores_pasteles
CASTILLO_REAL :: = PRINCESAS
COWGIRL :: pantalon_jeans_azul_chupin + botas_vaquero | pantalon_jeans_azul_chupin + botas_vaquero | -
VAQUERAS :: = COWGIRL
CABALLOS :: pantalon_jeans_azul_chupin | - | -
PIRATA :: respetar_provisto + pantalon_negro + camisa_blanca | respetar_provisto + pantalon_negro + camisa_blanca | -
DISNEY_100_ANOS :: traje_plateado_azul_disney100 | traje_plateado_azul_disney100 | -
JEFE_EN_PANALES :: - | - | - | colores_blanco_negro_celeste
OSOS_CARINOSOS :: calsa_blanca + molecas | pantalon_blanco + zapatos_blancos | -
OSITA :: = OSOS_CARINOSOS
BABY_KOALA :: = OSOS_CARINOSOS
BABY_SHARK :: - | - | - | colores_azul_celeste_amarillo
PERRITOS :: calsa_corta | - | - | colores_amarillo_beige
WINNIE_POOH :: - | - | - | colores_amarillo_celeste_verde_pastel
ABEJITA :: polera_morada_AM(botarga) + jogger_negro(botarga) | polera_morada_AM(botarga) + jogger_negro(botarga) | - | botarga_abejita
MASHA_Y_EL_OSO :: respetar_provisto | respetar_provisto | - | botarga_oso + masha
MAMANUELAS :: respetar_provisto | - | -
SONIC :: respetar_provisto | respetar_provisto | -
SHAKIRA :: respetar_provisto | - | -
MARIO_BROS :: respetar_provisto | respetar_provisto | - | botargas_mario_luigi_bowser
MARIO_BROS_SONIC :: = MARIO_BROS
DAVID_Y_GOLIAT :: sandalias + basica | short + solera | - | tunica_provista
JESUS :: = DAVID_Y_GOLIAT
PICNIC :: - | - | - | colores_beige_verde + minnie_roja
ELEGANTE :: tacos + vestido_elegante | traje_formal | -
ROSAS_GOLD :: = HRL_PLATEADOS
ECUADOR_BOLIVIA :: respetar_provisto | respetar_provisto | - | hrl_tematica
ARGENTINA :: - | zanqueras_blanco + polera_argentina(bailarines) + personaje_Messi | -
LORELAI :: calsa_blanca + molecas | - | -
PLEBE_HIJA_DE_PICAPIEDRAS :: - | - | - | colores_naranja_rosa_verde
BOSQUE :: = BOSQUE_ENCANTADO
VINTAGE :: = HRL_VINTAGE
ROCK :: - | - | ropa_negra_base | -
PISCINA_Y_TRAJES_TIPICOS :: = POOL_PARTY
EXPOBODA :: - | - | -
EXPOBEBE :: - | - | zapatos_blancos
PROMOCIONAL :: calsa_corta(princesas) + zapatos_blancos | pantalon_blanco + zapatos_blancos | zapatos_blancos
