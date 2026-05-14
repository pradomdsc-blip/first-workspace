# ROLES — overrides por rol asignado o persona recurrente
# Tienen PRIORIDAD sobre PACK y TEMÁTICA
# Formato: ROL :: extras

# ===== ROLES GENÉRICOS =====
ARBITRO :: short_deportivo_negro + medias_deportivas + zapatillas
ARBITRO_FUTBOL :: = ARBITRO
NARRADOR :: pantalon_blanco + zapatos_blancos
NARRADORA :: pantalon_blanco + zapatos_blancos
COORDINADORA :: ropa_neutra
MAESTRO_CEREMONIA :: traje_formal_negro
OPERADOR :: ropa_neutra
OPERADOR_SONIDO :: ropa_neutra
SOPORTE :: ropa_neutra
ANIMADOR :: segun_vestuario_declarado
ANIMADORA :: segun_vestuario_declarado

# ===== ZANQUEROS =====
ZANQUERO :: calsa_larga + basica(no_corta_nunca)
ZANQUERA :: = ZANQUERO
ZANQUERO_PLATEADO :: calsa_larga + basica_lisa
ZANQUERO_DISCO :: calsa_larga + basica_lisa + bola_disco
ZANQUERO_BLANCO_CON_ALAS :: calsa_larga + basica_blanca
ZANQUERO_ROBOT :: calsa_larga + basica
ZANQUERO_ARLEQUIN :: calsa_larga + basica
ZANQUERO_ARBOL :: calsa_larga + basica_verde
ZANQUERO_SOMBRERO_ESPEJADO :: calsa_larga + basica
# NOTA: convocatoria usa sufijo Z en nombre (ej: BrendaZ) = zanquera
# NOTA: convocatoria usa "Zanqueros:" explícito → aplicar regla

# ===== BOTARGAS (botargaman/cabezón) =====
BOTARGA :: polera_morada_AM + jogger_negro_o_calsa_negra_por_dentro + ropa_para_sudar
BOTARGA_MICKEY :: = BOTARGA
BOTARGA_MINNIE :: = BOTARGA
BOTARGA_GOOFY :: = BOTARGA
BOTARGA_DONALD :: = BOTARGA
BOTARGA_DAISY :: = BOTARGA
BOTARGA_PLUTO :: = BOTARGA
BOTARGA_STICH :: = BOTARGA
BOTARGA_ABEJITA :: = BOTARGA
BOTARGA_PEPPA :: = BOTARGA
BOTARGA_PLIM_PLIM :: = BOTARGA
BOTARGA_ZENON :: = BOTARGA
BOTARGA_BARTOLITO :: = BOTARGA
BOTARGA_VACA_LOLA :: = BOTARGA
BOTARGA_LOBO :: = BOTARGA
BOTARGA_BAM :: = BOTARGA
BOTARGA_HOGUIE :: = BOTARGA
BOTARGA_ACUARELA :: = BOTARGA
BOTARGA_OSO :: = BOTARGA
BOTARGA_MASHA :: = BOTARGA
BOTARGA_CAPIBARA :: = BOTARGA
BOTARGA_TIGRE :: = BOTARGA
BOTARGA_DINO :: = BOTARGA
BOTARGA_GRINCH :: = BOTARGA
BOTARGA_RODOLFO :: = BOTARGA
BOTARGA_WOODY :: = BOTARGA
BOTARGA_JESSIE :: = BOTARGA
BOTARGA_MARIO :: = BOTARGA
BOTARGA_LUIGI :: = BOTARGA
BOTARGA_BOWSER :: = BOTARGA
BOTARGA_ZORRO :: = BOTARGA
BOTARGA_CONEJO :: = BOTARGA
BOTARGA_SHAKIRA :: = BOTARGA
BOTARGA_RAIDER :: polera_blanca_manga_larga + zapatos_blancos
BOTARGA_POLLITO :: = BOTARGA

# ===== PERSONAJES DELUXE (traje no botarga) =====
PRINCESA :: calsa_corta(siempre) + traje_provisto
PRINCIPE :: pantalon_negro_vestir + cinturon + zapatos_vestir_negros + camisa_blanca
HADA :: calsa_corta + short_corto
MARIPOSA :: calsa_corta + short_corto
DUENDE :: pantalon_neutro + botines
FLOR :: calsa_corta
SIRENA :: cola_provista + tacos_se_trae
CAPERUCITA :: calsa_corta
LOBO :: botines_beige + pantalon_beige + ropa_para_sudar
ABUELA :: ropa_neutra
GUARDABOSQUES :: pantalon_neutro + botines
MICKEY_DELUXE :: traje_deluxe_provisto + ropa_para_sudar
MINNIE_DELUXE :: traje_deluxe_provisto + calsa_corta
ELSA :: traje_provisto + zapatos_blancos
JAZMIN :: traje_provisto + calsa_corta
RAPUNZEL :: traje_provisto + calsa_corta
MOANA_PERSONAJE :: traje_provisto + calsa_corta
ARIEL :: cola_provista
BLANCA_NIEVES_PERSONAJE :: traje_provisto + calsa_corta
CENICIENTA_PERSONAJE :: traje_provisto + calsa_corta
BELLA :: traje_provisto + calsa_corta
AURORA :: traje_provisto + calsa_corta
HADA_MADRINA :: calsa_corta
BARBIE :: tacos
SPIDERMAN_PERSONAJE :: traje_provisto
BATMAN_PERSONAJE :: traje_provisto
MUJER_MARAVILLA :: traje_provisto + calsa_corta
CAP_AMERICA :: traje_provisto
DADDY_YANKEE :: traje_negro
MESSI :: polera_argentina_sport
BAD_BOBBY :: traje_provisto
GUERRERA_KPOP :: calsa_corta_blanca_o_negra + basica + zapatos_parecidos_al_personaje
RUMI :: = GUERRERA_KPOP
SAJA_BOY :: chulo_amarillo + pantalon_jeans + zapatos_blancos
TIGRE_BAILARIN :: vestuario_plateado + maquillaje
PATA_DAISY :: traje_deluxe + calsa_corta
PATO_DONALD :: traje_deluxe
HOST_SHOT :: basica_con_cuello_si_lentejuelas + calsa
BAR_MOVIL :: basica + calsa + traje_provisto(lentejuelas_o_cambitas)
BAR_MOVIL_CAMBITAS :: traje_cambitas_provisto + calsa
ROSA_BLANCA :: traje_provisto
RECEPCIONISTA_CABARET :: traje_provisto
GLITTER_BAR :: - (maleta_glitter_provista)
PINTACARITAS :: -
ROBOT_LED :: calsa_larga + basica
BAILARIN :: pantalon_blanco + zapatos_blancos(default)
BAILARIN_SHOW_LED :: pantalon_blanco + zapatos_blancos + ropa_negra_show_led
BAILARIN_HRL_PLATEADO :: polera_negra + pantalon_negro_vestir + botines_negros + cinturon
BAILARINA :: calsa_corta
BAILARINA_SHOW_LED :: calsa_blanca + molecas + ropa_negra_show_led
BAILARINA_HRL_PLATEADO :: basica_con_cuello + calsa_corta

# ===== PERSONAS ESPECÍFICAS CON DEFAULTS RECURRENTES =====
# Estos son patrones observados, no obligatorios — si aparece sin rol explícito
PERSONA_Maickel :: si_pool_party_short_negro + si_arbitro_short_deportivo
PERSONA_Anderson :: si_paw_patrol_Raider_polera_blanca_manga_larga
PERSONA_Franco :: si_saya_boy_chulo_amarillo
PERSONA_FrancoVaca :: si_botarga_vaca_ropa_sudar
PERSONA_Niki :: si_recepcion_premium_tacos
PERSONA_Nikol :: si_host_basica + si_boda_elegante_tacos
PERSONA_Ivonne :: si_princesa_adulta_tacos + si_baby_shower_coordinar_tacos
PERSONA_Laura :: si_hrl_boda_basica_negra + si_maestra_ceremonia_formal_negro
PERSONA_Majo :: si_zanquera_calsa_larga + si_shots_basica_con_cuello
PERSONA_Michelle :: si_zanquera_calsa_larga + si_hrl_basica
PERSONA_Wendy :: si_zanquera_calsa_larga
PERSONA_Brenda :: si_zanquera_calsa_larga + si_pintacaritas_ropa_neutra
PERSONA_Susan :: si_bailarina_calsa_corta
PERSONA_Felipe :: si_botarga_ropa_sudar + si_hrl_polera_negra + si_boda_zapatos_vestir
PERSONA_Mathias :: si_hrl_polera_negra + si_boda_pantalon_vestir
PERSONA_Gustavo :: si_hrl_polera_negra + si_arbitro_short_deportivo
PERSONA_Luis :: si_botarga_ropa_sudar + si_lobo_botines_beige
PERSONA_Mariel :: si_bailarina_calsa_corta
PERSONA_Noelia :: si_bailarina_calsa_corta
PERSONA_Sofia :: si_bailarina_calsa_corta
PERSONA_Shirley :: si_narradora_zapatos_blancos + si_sandalias_David_y_Goliat
PERSONA_Darling :: si_bailarina_calsa_corta
PERSONA_Melissa :: si_bailarina_calsa_corta
PERSONA_Simone :: si_bailarina_calsa_corta
PERSONA_Romina :: si_bailarina_calsa_corta
PERSONA_Ingrid :: si_bailarina_calsa_corta
PERSONA_Lino :: si_pantalon_jeans_azul + si_cascanueces_pantalon_blanco
PERSONA_Leo :: si_botarga_ropa_sudar + si_hrl_polera_negra
PERSONA_Edgar :: si_maestro_ceremonia_formal_negro + si_hrl_todo_negro
PERSONA_Bruno :: si_maestro_ceremonia_formal_negro
PERSONA_Rilver :: si_papa_noel_traje_provisto + si_batman_traje_provisto
PERSONA_Ricardo :: = PAPA_NOEL_ROL
PERSONA_Richi :: = PAPA_NOEL_ROL
PERSONA_Xander :: si_maestro_ceremonia_formal_negro + si_mickey_deluxe
PERSONA_Baldwin :: si_bailarin_pantalon_blanco
PERSONA_Jose :: si_bailarin_pantalon_blanco
PERSONA_Jhon :: si_bailarin_pantalon_blanco

PAPA_NOEL_ROL :: traje_papa_noel_provisto

# ===== ZONAS DE VESTUARIO PROTEGIDAS (provistos por empresa cliente) =====
# Si convocatoria dice: CAMSA, TIGO_KM9, EUROFARMA, ENDE_GUARACACHI, AGROPARTNER, OCTANOS, PIL, CBN, AGRO_CENTRO, COFAR, BANCO_SOL, CBA, RED_UNO, CRE, DHL, ROMAX, JOBBI, YANGO, CAMSA_TRAJE_AZUL, VINTAGE_PETROLEUM, AGROFARMERS, AGROPHARNERS, COCA_COLA, PEDIDOS_YA, SOFIA, RAIMBOW, HUMOR_TIGO → vestuario corporativo se respeta, solo agregar zapatos_blancos + polera_morada_AM(backup) + jogger_negro
