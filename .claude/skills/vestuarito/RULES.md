# RULES — extras por tipo de pack
# Formato: PACK :: chicas | chicos | universal | roles_especiales

POOL_PARTY :: calsa_corta | short_negro_piscina | zapatos_blancos + ropa_interior_extra + chinelas
SHOW_EN_PISCINA :: = POOL_PARTY

CORPORATIVO :: - | - | polera_morada_AM + jogger_negro + zapatos_blancos
CORPORATIVO_CBN :: calsa_corta + basica_negra(si_tipoy) | pantalon_negro + camisa_blanca/negra | polera_morada_AM + jogger_negro + zapatos_blancos
DIA_DE_LA_FAMILIA :: = CORPORATIVO
TEAM_BUILDING :: = CORPORATIVO
SHOW_CORP :: = CORPORATIVO

BABY_SHOWER :: pantalon_vestir_blanco + tacos_coordinados | pantalon_blanco + zapatos_blancos | -
REVELACION_DE_SEXO :: pantalon_vestir_blanco + tacos_bajitos | pantalon_blanco + zapatos_blancos | -

BASICO :: calsa_blanca + molecas | pantalon_blanco + zapatos_blancos | -
BASICO_ESPECIAL :: = BASICO
MEDIUM :: = BASICO
PREMIUM :: = BASICO
EXCLUSIVO :: = BASICO
MEGA_SHOW :: = BASICO
MIXTO :: = BASICO

SHOW_LED :: calsa_blanca + molecas + ropa_negra_show_led | pantalon_blanco + zapatos_blancos + ropa_negra_show_led | ropa_negra_show_led
MASTER_LED :: = SHOW_LED
TEENS_LED :: ropa_interior_extra + ropa_negra_show_led | short_negro_piscina(si_aplica) + ropa_negra_show_led | zapatos_blancos + ropa_negra_show_led
SHOW_LED_TEENS :: = TEENS_LED

TEENS_BASICO :: - | - | zapatos_blancos
TEENS_ESPECIAL :: = TEENS_BASICO
TEENS_SPORT :: calsa_corta + zapatos_blancos | short_deportivo + medias_deportivas + zapatillas(arbitro) | zapatos_blancos
TEENS_TIKTOK :: - | - | zapatos_blancos
TEENS_TIKTOK_KARAOKE :: = TEENS_TIKTOK

HRL_PLATEADOS :: basica_con_cuello + calsa_corta | pantalon_vestir_negro + camisa_negra + botines_vestir_negros + cinturon + polera_negra | -
HRL_FOREVER :: = HRL_PLATEADOS
HRL_GEMELAS :: = HRL_PLATEADOS
HRL_LENTEJUELAS :: basica_con_cuello + calsa_corta/larga (el_traje_pica) | pantalon_vestir_negro + polera_negra + botines_vestir | -
HRL_URBANO_PLATEADOS :: = HRL_PLATEADOS
HRL_ENTERIZOS_LENTEJUELAS :: basica_con_cuello + calsa | polera_negra + pantalon_negro | -

HRL_VENECIANO :: calsa_corta_blanca_o_beige | pantalon_negro_vestir + camisa_negra + botines_vestir + cinturon | parejas_coordinar_negro_blanco
HRL_NEGROS_CON_COLA :: calsa_corta | pantalon_vestir_negro + camisa_negra + botines_vestir_negros + cinturon | -
HRL_BLANCO_ELEGANTE :: calsa_corta + tacos | pantalon_blanco + zapatos_blancos | vestuario_blanco_provisto
HRL_BODA_GENERICO :: ropa_elegante_gala + tacos + vestido_comodo_bailar | pantalon_vestir + camisa + chaleco + corbata | -
HRL_DISCO :: = HRL_PLATEADOS
HRL_VINTAGE :: = HRL_PLATEADOS
HRL_ADULTOS :: = HRL_PLATEADOS

SHOW_NAVIDENO :: calsa_corta + basica_negra(cascanueces) | pantalon_blanco + camisa_blanca | -
PAPA_NOEL_VISITA :: - | - | -
VISITA_PERSONAJE :: depende_personaje(ver_ROLES)
PERSONAJE :: depende_personaje(ver_ROLES)

ANIMACION :: depende_vestuario_declarado
MAESTRO_CEREMONIA :: - | traje_formal_negro | -
SONIDO :: - | - | -
SONIDO_Y_LUCES :: - | - | -
PACK_BODA :: coordinar_negro/segun_indicacion | coordinar_negro | -
PACK_VIP_BODA :: = PACK_BODA
PACK_VIP_15 :: todo_negro_coordinar | todo_negro_coordinar | -
PACK_PARTY :: depende_evento | depende_evento | -
PACK_CARNAVALERO :: calsa_corta + basica | - | -
SHOW_TEATRO :: depende_personaje | depende_personaje | -
SHOW_HADAS :: short_corto + calsa_corta | botines_o_zapatos_personaje | -
SHOW_DISNEY :: calsa_corta + polera_morada_AM(botargas) | polera_morada_AM + jogger_negro(botargas) + zapatos_de_vestir_negros + cinturon(principes) | ropa_para_sudar(botargas)
SHOW_BARBIE :: calsa_corta | zapatos_blancos_limpios | -
SHOW_BULO_BULO :: = CORPORATIVO
SHOW_PROMOCIONAL :: - | - | zapatos_blancos
EXPOBEBE :: - | - | zapatos_blancos
VENTURA_KIDS :: pantalon_jeans + zapatos_blancos | pantalon_jeans + zapatos_blancos | -
VENTURA_NAVIDENOS :: calsa_blanca + calsa_corta(cascanueces) | pantalon_blanco + camisa_blanca | -
KINDER_JARDIN :: calsa_corta | - | -
DIA_DEL_NINO :: polera_blanca_o_basica + zapatos_blancos | polera_blanca_o_basica + zapatos_blancos | -
EVENTO_SOLIDARIO :: polera_morada_AM + jogger_negro + zapatos_blancos | = chicas | -

DESPEDIDA_SOLTERA :: pantalon_vestir_negro + zapatos_blancos | - | -
ATRILES :: - | - | -
LATAS :: - | - | -
EFECTOS :: - | - | -
ZANCOS_PRECARNAVAL :: calsa_larga + basica + globos | - | -
ROBOT_LED :: calsa_larga + basica | - | -

# OVERRIDES POR VESTUARIO DECLARADO (cuando convocatoria dice VESTUARIO: X)
VESTUARIO_SPORT :: - | - | polera_morada_AM + jogger_negro + zapatos_blancos
VESTUARIO_PERSONALIZADO :: respetar_provisto + calsa_corta(chicas_default) | respetar_provisto | -
VESTUARIO_LIBRE :: - | - | consultar_antes
VESTUARIO_SEMI_FORMAL :: - | pantalon_negro + camisa + zapatos_vestir | -
VESTUARIO_NAVIDENOS :: - | - | cascanueces_default
VESTUARIO_NAVIDAD :: = VESTUARIO_NAVIDENOS
VESTUARIO_MILITARES :: respetar_provisto | respetar_provisto | -
VESTUARIO_TEMATICO :: respetar_provisto | respetar_provisto | -
VESTUARIO_DISNEY :: = SHOW_DISNEY
VESTUARIO_TEENS :: - | - | zapatos_blancos
VESTUARIO_PLATEADO_FOREVER :: = HRL_PLATEADOS
VESTUARIO_PLATEADOS_GEMELAS :: = HRL_PLATEADOS
VESTUARIO_LENTEJUELAS :: = HRL_LENTEJUELAS
VESTUARIO_BLANCO_Y_NEGRO :: coordinar_blanco_negro | coordinar_blanco_negro | -
VESTUARIO_ARCOR_FLUOR :: respetar_provisto + calsa_corta | respetar_provisto | -
VESTUARIO_JOOGER_PLATEADOS :: = HRL_PLATEADOS
VESTUARIO_LED_CLASICO :: ropa_negra_show_led + calsa_blanca + molecas | ropa_negra_show_led + pantalon_blanco + zapatos_blancos | -
VESTUARIO_REAL_MADRID :: respetar_provisto | respetar_provisto | -
