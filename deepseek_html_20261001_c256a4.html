<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Exámenes interactivos - Rellenos Sanitarios y SEIA</title>
    <style>
        * { box-sizing: border-box; font-family: 'Segoe UI', Roboto, system-ui, sans-serif; }
        body { background: #f0f4f8; margin: 0; padding: 20px; display: flex; flex-direction: column; align-items: center; }
        .main-container { max-width: 1100px; width: 100%; }
        h1 { text-align: center; color: #1e3a5f; margin-bottom: 10px; font-weight: 600; }
        .subtitle { text-align: center; color: #2c5282; margin-bottom: 25px; font-style: italic; }
        .tabs-container { display: flex; flex-wrap: wrap; gap: 8px; justify-content: center; margin-bottom: 25px; background: white; padding: 12px; border-radius: 60px; box-shadow: 0 4px 15px rgba(0,0,0,0.08); }
        .tab-btn { background: #e2eaf3; border: none; color: #1e3a5f; font-weight: 600; padding: 10px 16px; border-radius: 40px; font-size: 0.9rem; cursor: pointer; transition: all 0.2s; display: flex; align-items: center; gap: 6px; white-space: nowrap; }
        .tab-btn:hover { background: #cbdae9; }
        .tab-btn.active { background: #2b6f9b; color: white; box-shadow: 0 4px 10px rgba(43,111,155,0.3); }
        .tab-btn .num { background: rgba(255,255,255,0.3); width: 22px; height: 22px; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 0.8rem; }
        .tab-btn.active .num { background: rgba(255,255,255,0.35); }
        .exam-card { background: white; border-radius: 24px; box-shadow: 0 10px 25px rgba(0,0,0,0.1); margin-bottom: 40px; padding: 25px 30px; border: 1px solid #d9e2ef; }
        .exam-card.hidden { display: none; }
        .exam-header { font-size: 1.6rem; font-weight: 700; color: #0b3b5c; border-bottom: 4px solid #3a7ca5; padding-bottom: 12px; margin-bottom: 25px; display: flex; align-items: center; gap: 12px; flex-wrap: wrap; }
        .exam-header span { background: #3a7ca5; color: white; font-size: 1.1rem; padding: 5px 14px; border-radius: 40px; }
        .section-title { font-size: 1.3rem; font-weight: 600; color: #1e4a6b; margin: 30px 0 15px 0; border-left: 8px solid #3a7ca5; padding-left: 15px; }
        .question-item { background: #f9fcff; border-radius: 16px; padding: 16px 20px; margin-bottom: 18px; border: 1px solid #e2edf7; transition: background 0.2s; }
        .question-item.correct { background: #e6f7e6; border-color: #7ac47a; }
        .question-item.incorrect { background: #ffeaea; border-color: #e07a7a; }
        .question-text { font-weight: 500; font-size: 1.02rem; margin-bottom: 12px; color: #0e2c44; }
        .options { display: flex; flex-wrap: wrap; gap: 10px 22px; margin-bottom: 10px; }
        .option { display: flex; align-items: center; gap: 8px; cursor: pointer; font-size: 0.95rem; }
        .option input[type="radio"] { width: 18px; height: 18px; accent-color: #2b6f9b; cursor: pointer; }
        .fill-input { padding: 10px 14px; font-size: 0.98rem; border: 2px solid #cbdae9; border-radius: 40px; width: 260px; max-width: 100%; transition: border 0.2s; outline: none; }
        .fill-input:focus { border-color: #2b6f9b; box-shadow: 0 0 0 3px rgba(43,111,155,0.15); }
        .fill-row { display: flex; flex-wrap: wrap; align-items: center; gap: 12px; margin-top: 5px; }
        .feedback { display: inline-flex; align-items: center; gap: 8px; font-weight: 600; font-size: 1.1rem; }
        .feedback .check { color: #2e7d32; }
        .feedback .cross { color: #c62828; }
        .correct-answer-msg { margin-top: 8px; font-size: 0.92rem; background: #fff3cd; padding: 8px 14px; border-radius: 40px; border-left: 6px solid #ffb74d; color: #7a5a00; display: inline-block; }
        .btn-verify { background: #2b6f9b; border: none; color: white; font-weight: 600; padding: 8px 22px; border-radius: 40px; font-size: 0.95rem; cursor: pointer; transition: background 0.2s; box-shadow: 0 2px 6px rgba(0,0,0,0.1); }
        .btn-verify:hover { background: #1d5479; }
        .btn-verify.small { padding: 7px 18px; font-size: 0.88rem; }
        .footer-note { text-align: center; color: #5b7f9b; margin-top: 20px; font-size: 0.95rem; }
        .reset-btn { background: #e2eaf3; border: none; color: #1e3a5f; padding: 8px 20px; border-radius: 40px; font-weight: 500; cursor: pointer; font-size: 0.9rem; transition: background 0.2s; margin-top: 15px; }
        .reset-btn:hover { background: #cbdae9; }
        .hidden { display: none; }
        .exam-footer { display: flex; justify-content: space-between; align-items: center; flex-wrap: wrap; gap: 15px; margin-top: 15px; padding-top: 15px; border-top: 1px solid #e2edf7; }
        .nav-exam-btns { display: flex; gap: 10px; }
        .nav-exam-btn { background: #3a7ca5; border: none; color: white; padding: 8px 18px; border-radius: 40px; font-weight: 500; cursor: pointer; font-size: 0.9rem; transition: background 0.2s; }
        .nav-exam-btn:hover { background: #1d5479; }
        .nav-exam-btn:disabled { background: #cbdae9; color: #8ba3b8; cursor: not-allowed; }
        .progress-info { font-size: 0.85rem; color: #5b7f9b; margin-bottom: 15px; text-align: center; }
    </style>
</head>
<body>
<div class="main-container">
    <h1>📋 Exámenes interactivos</h1>
    <div class="subtitle">Rellenos Sanitarios, SEIA y Gestión Ambiental</div>

    <!-- PESTAÑAS -->
    <div class="tabs-container" id="tabsContainer">
        <button class="tab-btn active" data-exam="1"><span class="num">1</span> Generación Residuos</button>
        <button class="tab-btn" data-exam="2"><span class="num">2</span> Infraestructura RS</button>
        <button class="tab-btn" data-exam="3"><span class="num">3</span> Bioseguridad RS</button>
        <button class="tab-btn" data-exam="4"><span class="num">4</span> Diseño y Cálculo</button>
        <button class="tab-btn" data-exam="5"><span class="num">5</span> Selección Sitio</button>
        <button class="tab-btn" data-exam="6"><span class="num">6</span> Área Estudio/AID</button>
        <button class="tab-btn" data-exam="7"><span class="num">7</span> Descripción/IGA</button>
        <button class="tab-btn" data-exam="8"><span class="num">8</span> Certificación Amb.</button>
        <button class="tab-btn" data-exam="9"><span class="num">9</span> Ley SEIA</button>
        <button class="tab-btn" data-exam="10"><span class="num">10</span> SEIA/Criterios</button>
        <button class="tab-btn" data-exam="11"><span class="num">11</span> Instrumentos IGA</button>
        <button class="tab-btn" data-exam="12"><span class="num">12</span> EIA/EAE Amazonía</button>
        <button class="tab-btn" data-exam="13"><span class="num">13</span> Casos Área Estudio</button>
    </div>

    <!-- CONTENEDOR DE EXÁMENES (se generan dinámicamente) -->
    <div id="examsContainer"></div>

    <div class="footer-note">✅ Haz clic en "Verificar" para comprobar tus respuestas. Las respuestas correctas se muestran si hay error.</div>
</div>

<script>
    // ======================== DATOS DE LOS EXÁMENES ========================
    const examsData = {
        1: {
            title: 'Cálculo de Generación Acumulada de Residuos Sólidos',
            multiple: [
                { id: '1-1', question: 'En la matriz de proyecciones, ¿qué variables son indispensables para proyectar la población futura de un distrito?', options: ['A) Área del distrito y densidad poblacional', 'B) Población inicial y tasa de crecimiento anual', 'C) Tasa de natalidad y tasa de mortalidad', 'D) Generación per cápita inicial'], correct: 'B' },
                { id: '1-2', question: '¿Cómo se expresa matemáticamente la Generación Per Cápita (GPC) en los estudios ambientales?', options: ['A) Toneladas por mes', 'B) m3 / habitante / año', 'C) kg / habitante / día', 'D) kg / kilómetro cuadrado'], correct: 'C' },
                { id: '1-3', question: 'Para calcular la cantidad de residuos domiciliarios diarios generados en un distrito, se debe multiplicar la población total por:', options: ['A) El área del distrito', 'B) La densidad de compactación', 'C) La Generación Per Cápita (GPC)', 'D) El factor de material de cobertura'], correct: 'C' },
                { id: '1-4', question: 'La Generación Municipal Total se calcula sumando los residuos domiciliarios, de barrido, de áreas públicas y:', options: ['A) Residuos peligrosos hospitalarios', 'B) Residuos industriales tóxicos', 'C) Residuos radiactivos', 'D) Residuos no domiciliarios asimilables (comerciales, institucionales)'], correct: 'D' },
                { id: '1-5', question: 'Si se tiene la generación total en toneladas por día (t/día), ¿qué operación matemática da como resultado la generación anual?', options: ['A) Multiplicar por 12', 'B) Dividir entre 30', 'C) Multiplicar por 365', 'D) Dividir entre 1000'], correct: 'C' },
                { id: '1-6', question: 'Según las consideraciones técnicas, ¿cuál es la densidad de compactación promedio empleada para dimensionar un relleno sanitario manual?', options: ['A) 0.10 - 0.20 t/m3', 'B) 0.50 - 0.60 t/m3', 'C) 0.80 - 1.00 t/m3', 'D) 1.20 - 1.50 t/m3'], correct: 'B' },
                { id: '1-7', question: '¿Cuál es la fórmula utilizada en las hojas de cálculo para determinar el volumen (m³) que ocuparán los residuos sólidos?', options: ['A) Densidad / Masa', 'B) Masa total * Densidad de compactación', 'C) Masa total / Densidad de compactación', 'D) Masa total + Densidad de compactación'], correct: 'C' },
                { id: '1-8', question: '¿Qué porcentaje del volumen de los residuos se estima habitualmente para el uso de material de cobertura?', options: ['A) Entre 5% y 10%', 'B) Entre 10% y 15%', 'C) Entre 20% y 25%', 'D) Más del 50%'], correct: 'C' },
                { id: '1-9', question: 'El volumen total de la "celda diaria" se obtiene sumando:', options: ['A) Volumen de lixiviados + Volumen de biogás', 'B) Volumen de residuos + Volumen de material de cobertura', 'C) Producción domiciliaria + Producción industrial', 'D) Volumen acumulado + Volumen de reserva'], correct: 'B' },
                { id: '1-10', question: 'En una matriz de proyección de diseño, ¿qué representa la columna "Volumen Acumulado"?', options: ['A) El volumen generado en el último mes de operación.', 'B) La diferencia entre el volumen ingresado y el volumen reciclado.', 'C) La suma progresiva del volumen dispuesto año tras año desde el inicio de operaciones.', 'D) El espacio vacío que queda disponible en el relleno sanitario.'], correct: 'C' },
                { id: '1-11', question: '¿Para qué es fundamental conocer el Volumen Acumulado Total al final de la vida proyectada del proyecto?', options: ['A) Para determinar la vida útil y calcular el área total requerida para el relleno.', 'B) Para calcular el presupuesto de recolección de basura.', 'C) Para diseñar la ruta de los camiones recolectores.', 'D) Para definir el color de los contenedores urbanos.'], correct: 'A' },
                { id: '1-12', question: 'Si la tasa de crecimiento poblacional es 0%, ¿cómo será la generación de residuos anual a lo largo del tiempo, asumiendo una GPC constante?', options: ['A) Crecerá exponencialmente', 'B) Disminuirá linealmente', 'C) Se mantendrá constante', 'D) Caerá a cero'], correct: 'C' },
                { id: '1-13', question: 'Para convertir la masa de residuos recolectados de kilogramos a toneladas en Excel, se debe:', options: ['A) Multiplicar por 1000', 'B) Dividir entre 1000', 'C) Dividir entre 365', 'D) Multiplicar por 2.2'], correct: 'B' },
                { id: '1-14', question: 'Si un operador logra una densidad de compactación mucho mayor a la calculada inicialmente, ¿qué sucede con la vida útil del relleno sanitario?', options: ['A) La vida útil se reduce rápidamente.', 'B) La vida útil no se ve afectada.', 'C) La vida útil se incrementa, ya que los residuos ocupan menos espacio.', 'D) Las celdas colapsan por exceso de peso.'], correct: 'C' },
                { id: '1-15', question: 'Para hallar el Área Total del relleno (en m2), se debe multiplicar el área requerida para disponer residuos por un factor de aumento (ej. 1.30 o 1.40). ¿Qué justifica este aumento?', options: ['A) Los errores matemáticos de la hoja de cálculo.', 'B) El espacio para áreas administrativas, patio de maniobras, vías e instalaciones.', 'C) La evasión de impuestos prediales.', 'D) La evaporación de los lixiviados.'], correct: 'B' },
                { id: '1-16', question: 'Los residuos producto del barrido de calles deben incluirse en la suma de generación municipal anual porque:', options: ['A) Son peligrosos y requieren incineración.', 'B) Su gestión es responsabilidad municipal y ocuparán volumen en el mismo relleno.', 'C) Contienen altos niveles de metales pesados.', 'D) Las barredoras mecánicas son muy costosas.'], correct: 'B' },
                { id: '1-17', question: 'Si en el Año 1 el volumen de residuos compactados es 1,000 m3 y el material de cobertura es el 20%, ¿cuál es el volumen anual total de la celda?', options: ['A) 1,020 m3', 'B) 1,200 m3', 'C) 1,500 m3', 'D) 2,000 m3'], correct: 'B' },
                { id: '1-18', question: 'En la realidad operativa, el dato inicial exacto de masa de residuos que ingresa al relleno sanitario para contrastar con las proyecciones se obtiene mediante:', options: ['A) Encuestas vecinales', 'B) Imágenes de drones', 'C) Una balanza de pesaje para camiones en el pórtico de ingreso', 'D) Medición con cinta métrica en la celda'], correct: 'C' },
                { id: '1-19', question: '¿Por qué es fundamental que la matriz de Excel proyecte la generación año a año en lugar de usar un valor estático?', options: ['A) Porque la densidad del aire cambia cada año.', 'B) Porque la topografía del terreno se expande anualmente.', 'C) Porque la población crece y, en consecuencia, la cantidad de basura aumenta con el tiempo.', 'D) Para hacer el documento más largo y complejo.'], correct: 'C' },
                { id: '1-20', question: '¿Qué unidad de medida física se utiliza para expresar el "Volumen Acumulado" en la matriz de diseño de un relleno sanitario?', options: ['A) Toneladas (t)', 'B) Metros cuadrados (m2)', 'C) Metros cúbicos (m3)', 'D) Hectáreas (ha)'], correct: 'C' }
            ],
            fill: [
                { id: '1-21', question: 'La cantidad de residuos que produce un solo habitante en un día se denomina Generación ________.', correct: ['per cápita', 'per capita', 'percapita'] },
                { id: '1-22', question: 'Para calcular el volumen ocupado por los residuos, la fórmula matemática exige dividir la masa total entre la ________ de compactación.', correct: ['densidad'] },
                { id: '1-23', question: 'La proyección de la cantidad de residuos se realiza para todo el período de diseño, el cual también es conocido como vida ________ del proyecto.', correct: ['útil', 'util'] },
                { id: '1-24', question: 'Al volumen de los residuos compactados se le debe sumar el volumen de la tierra o material de ________ para obtener el volumen de la celda.', correct: ['cobertura'] },
                { id: '1-25', question: 'La generación municipal anual se calcula sumando los residuos domiciliarios y los residuos de origen ________ (instituciones, comercios).', correct: ['no domiciliario', 'no domiciliarios'] },
                { id: '1-26', question: 'En las fórmulas, para pasar el valor de toneladas diarias a toneladas anuales, se debe multiplicar el valor diario por ________ (días).', correct: ['365'] },
                { id: '1-27', question: 'El volumen del año "n" se calcula sumando el volumen del año "n" más los volúmenes depositados de todos los años anteriores: volumen ________.', correct: ['acumulado'] },
                { id: '1-28', question: 'La compactación utilizando maquinaria pesada (tractores de oruga) permite lograr una mayor ________ que si se hace manualmente.', correct: ['densidad'] },
                { id: '1-29', question: 'El área a rellenar se calcula dividiendo el volumen acumulado final entre la ________ promedio o altura del relleno.', correct: ['profundidad', 'altura'] },
                { id: '1-30', question: 'El aumento progresivo de habitantes de un distrito a lo largo del tiempo se proyecta utilizando una tasa de crecimiento ________.', correct: ['anual', 'poblacional'] },
                { id: '1-31', question: 'En las conversiones matemáticas de la hoja de cálculo, un kilogramo equivale a la milésima parte de una ________.', correct: ['tonelada'] },
                { id: '1-32', question: 'Si un municipio implementa políticas de reciclaje y compostaje, la cantidad de residuos sólidos que irá a disposición final será ________ a la proyectada inicialmente.', correct: ['menor'] },
                { id: '1-33', question: 'Los residuos que provienen de la limpieza de vías públicas y calles peatonales se catalogan en la matriz como residuos de ________.', correct: ['barrido'] },
                { id: '1-34', question: 'El Área Total del relleno no solo considera la zona de entierro de basura, sino también el patio de ________, oficinas e instalaciones auxiliares.', correct: ['maniobras'] },
                { id: '1-35', question: 'El año inicial donde comienzan las operaciones y los cálculos de un proyecto se conoce comúnmente como año ________ (o año cero).', correct: ['base', 'cero'] },
                { id: '1-36', question: 'Si el material de cobertura corresponde al 20% del volumen de la basura, y la basura ocupa 100 m3, entonces la cobertura ocupará ________ m3.', correct: ['20'] },
                { id: '1-37', question: 'En el cuadro resumen, la masa de los residuos sólidos se expresa en toneladas, mientras que el espacio físico que ocupan se expresa en metros ________.', correct: ['cúbicos', 'cubicos'] },
                { id: '1-38', question: 'Un operador de maquinaria debe realizar un control riguroso de la ________ de los residuos para no agotar el espacio del relleno de manera prematura.', correct: ['densidad', 'compactación', 'compactacion'] },
                { id: '1-39', question: 'Una vez obtenida el Área Total del proyecto en metros cuadrados (m2), suele dividirse entre 10,000 para expresarla en ________.', correct: ['hectáreas', 'hectareas'] },
                { id: '1-40', question: 'La conformación física de tierra y residuos que los camiones descargan y los operadores tapan al término de cada jornada de trabajo recibe el nombre de celda ________.', correct: ['diaria'] }
            ]
        },
        2: {
            title: 'Diseño de Infraestructura de Relleno Sanitario',
            multiple: [
                { id: '2-1', question: '¿Cuál es la capacidad máxima de diseño para un Relleno Sanitario Manual?', options: ['A) Hasta 6 t/día', 'B) Entre 6 y 50 t/día', 'C) Más de 50 t/día', 'D) Hasta 100 t/día'], correct: 'A' },
                { id: '2-2', question: '¿Qué densidad de compactación se alcanza típicamente en un Relleno Sanitario Semimecanizado?', options: ['A) 0.40 - 0.50 t/m3', 'B) 0.50 - 0.60 t/m3', 'C) 0.60 - 0.70 t/m3', 'D) 0.70 - 1.00 t/m3'], correct: 'C' },
                { id: '2-3', question: 'Un relleno sanitario que recibe más de 50 t/día y requiere flota pesada permanente (tractores oruga, volquetes) se clasifica como:', options: ['A) Manual', 'B) Semimecanizado', 'C) Mecanizado', 'D) Botadero controlado'], correct: 'C' },
                { id: '2-4', question: 'Según las diapositivas, ¿cuál de los siguientes es un residuo ACEPTABLE en un relleno sanitario convencional?', options: ['A) Residuos agrícolas', 'B) Polvos químicos inflamables', 'C) Residuos biocontaminados', 'D) Lodos de aguas residuales sin tratar'], correct: 'A' },
                { id: '2-5', question: '¿Qué estudio básico permite determinar la profundidad del nivel freático y la dirección del flujo de agua subterránea?', options: ['A) Estudio de Mecánica de Suelos', 'B) Estudio Geológico', 'C) Estudio Geofísico', 'D) Estudio Geohidrológico'], correct: 'D' },
                { id: '2-6', question: 'Para identificar fallas tectónicas locales, sismicidad y litología, se debe realizar un:', options: ['A) Estudio Demográfico', 'B) Estudio Geológico', 'C) Estudio Topográfico', 'D) Estudio de Mecánica de Suelos'], correct: 'B' },
                { id: '2-7', question: '¿Qué método de construcción es ideal para terrenos planos con un nivel freático profundo?', options: ['A) Método de Área', 'B) Método de Trinchera (Zanja)', 'C) Método Combinado', 'D) Método de Terraplén'], correct: 'B' },
                { id: '2-8', question: 'Si el terreno tiene una topografía irregular o el nivel freático es muy alto, el método de construcción recomendado es:', options: ['A) Método de Área', 'B) Método de Trinchera', 'C) Método Combinado', 'D) Método de Terraplén'], correct: 'A' },
                { id: '2-9', question: 'El porcentaje de volumen que típicamente ocupa el material de cobertura respecto al total de residuos es:', options: ['A) 5% al 10%', 'B) 10% al 15%', 'C) 20% al 25%', 'D) 30% al 40%'], correct: 'C' },
                { id: '2-10', question: 'En la fórmula de proyección demográfica (Pf = P0(1+r)^n), ¿qué representa la variable "r"?', options: ['A) Tasa de recolección', 'B) Tasa de crecimiento anual', 'C) Residuos recolectados por semana', 'D) Número de años proyectados'], correct: 'B' },
                { id: '2-11', question: '¿Cuál es el estudio básico que evalúa la permeabilidad y la disponibilidad de material de cobertura natural?', options: ['A) Estudio Topográfico', 'B) Estudio Geofísico', 'C) Estudio de Mecánica de Suelos', 'D) Estudio de Caracterización de residuos'], correct: 'C' },
                { id: '2-12', question: 'Para calcular el volumen de residuos sólidos (m³) a disponer anualmente, se debe:', options: ['A) Multiplicar la generación anual por el 25%', 'B) Dividir la generación anual de residuos entre la densidad de residuos compactados', 'C) Sumar el volumen de material de cobertura al nivel freático', 'D) Multiplicar la población total por la tasa de crecimiento'], correct: 'B' },
                { id: '2-13', question: 'En el dimensionamiento de una trinchera, la letra "h" representa:', options: ['A) El largo de base mayor', 'B) El ancho de base menor', 'C) La humedad de los residuos', 'D) La altura o profundidad'], correct: 'D' },
                { id: '2-14', question: 'Según el cuadro de cálculo de cantidad de residuos a disponer, los residuos municipales totales resultan de sumar los residuos domiciliarios, de almacenamiento, de barrido y:', options: ['A) Residuos hospitalarios', 'B) Residuos radiactivos', 'C) Residuos no domiciliarios asimilables', 'D) Residuos industriales tóxicos'], correct: 'C' },
                { id: '2-15', question: 'En el método combinado de construcción de rellenos sanitarios, se maximiza el volumen útil mediante:', options: ['A) Uso exclusivo de plataformas en superficie', 'B) Zanjas en la base y plataformas en la superficie', 'C) Excavaciones hasta tocar el nivel freático', 'D) Barreras naturales perimetrales de 10 metros'], correct: 'B' },
                { id: '2-16', question: 'Los líquidos y lodos sin tratar, así como los compuestos orgánicos líquidos, en un relleno sanitario convencional son:', options: ['A) Totalmente aceptables si se mezclan con tierra', 'B) Aceptables solo en el método de trinchera', 'C) Inaceptables por ser de alto riesgo', 'D) Aceptables en rellenos manuales'], correct: 'C' },
                { id: '2-17', question: '¿Qué tipo de maquinaria se utiliza en la operación de un relleno sanitario manual?', options: ['A) Tractores oruga de forma constante', 'B) Compactadoras hidráulicas estacionarias', 'C) Maquinaria esporádica solo para acopio de tierra', 'D) Rodillos pata de cabra'], correct: 'C' },
                { id: '2-18', question: 'El volumen diario a disponer en la celda se calcula sumando:', options: ['A) El volumen de residuos y el volumen de cobertura', 'B) El volumen de lixiviados y biogás', 'C) La generación per cápita y la densidad', 'D) El área y la altura'], correct: 'A' },
                { id: '2-19', question: 'En el cálculo del área de la celda, ¿qué significa "Frente de descarga"?', options: ['A) La pared trasera de la trinchera', 'B) La superficie donde los vehículos descargan los residuos', 'C) El límite del cerco perimétrico', 'D) El área destinada exclusivamente para oficinas'], correct: 'B' },
                { id: '2-20', question: 'Para calcular la generación anual (toneladas/año) a partir de la generación diaria, se debe multiplicar la generación diaria por:', options: ['A) 12 meses', 'B) 52 semanas', 'C) 365 días', 'D) 10 años (período de diseño)'], correct: 'C' }
            ],
            fill: [
                { id: '2-21', question: 'El relleno sanitario ________ tiene una capacidad mayor a 6 toneladas pero hasta 50 t/día y usa equipo multiusos permanentemente.', correct: ['semimecanizado'] },
                { id: '2-22', question: 'Las herramientas manuales como rastrillos y ________ se utilizan predominantemente en la operación de un relleno manual.', correct: ['pisones'] },
                { id: '2-23', question: 'La densidad de compactación esperada en un relleno sanitario mecanizado varía entre 0.70 y ________ t/m3.', correct: ['1.00', '1.0', '1'] },
                { id: '2-24', question: 'Los residuos de establecimientos de salud son considerados ________ por ser de alto riesgo patógeno y biocontaminado.', correct: ['inaceptables'] },
                { id: '2-25', question: 'El estudio ________ es fundamental para conocer la pendiente, curvas de nivel y perfiles del terreno a utilizar.', correct: ['topográfico', 'topografico'] },
                { id: '2-26', question: 'El estudio geofísico sirve para detectar la estructura interna, fallas o ________ ocultas en el terreno.', correct: ['cavidades'] },
                { id: '2-27', question: 'En el método de ________ (zanja), la tierra que se remueve durante la excavación se usa posteriormente como material de cobertura.', correct: ['trinchera'] },
                { id: '2-28', question: 'El método de área se emplea cuando el terreno tiene topografía irregular o cuando el nivel ________ es muy alto.', correct: ['freático', 'freatico'] },
                { id: '2-29', question: 'En el estudio de caracterización, las siglas GPC significan Generación ________ per cápita.', correct: ['per cápita', 'per capita'] },
                { id: '2-30', question: 'Los residuos tóxicos, radiactivos y ________ no deben ingresar bajo ninguna circunstancia a la celda de un relleno convencional.', correct: ['explosivos', 'inflamables'] },
                { id: '2-31', question: 'En el cálculo del volumen de recepción, la variable "a" minúscula corresponde al largo de base ________.', correct: ['mayor'] },
                { id: '2-32', question: 'Asimismo, la variable "c" minúscula corresponde al ancho de base ________ de la trinchera.', correct: ['menor'] },
                { id: '2-33', question: 'El cálculo de la generación diaria de residuos municipales incluye la recolección en domicilios, almacenamiento, instituciones y vías sujetas a ________.', correct: ['barrido'] },
                { id: '2-34', question: 'Para obtener el volumen de los residuos (m³), se divide la generación anual (t/año) entre la ________ de compactación.', correct: ['densidad'] },
                { id: '2-35', question: 'El volumen de material de ________ varía habitualmente entre el 20 % y el 25 % del volumen total de los residuos sólidos.', correct: ['cobertura'] },
                { id: '2-36', question: 'En el Taller presentado al final de las diapositivas, se utiliza una tasa de ________ poblacional de 2.3 % anual.', correct: ['crecimiento'] },
                { id: '2-37', question: 'El método ________ es el más usado ya que se adapta a terrenos con variaciones topográficas, uniendo trincheras y plataformas.', correct: ['combinado'] },
                { id: '2-38', question: 'El estudio de mecánica de suelos es vital para comprobar la ________ del suelo y la estabilidad de los taludes de la celda.', correct: ['permeabilidad'] },
                { id: '2-39', question: 'La suma del volumen de los residuos sólidos y el volumen de la tierra de cobertura nos da como resultado el volumen de la celda ________.', correct: ['diaria'] },
                { id: '2-40', question: 'La operación en un relleno sanitario mecanizado es 100% ________ requiriendo tractores oruga de forma constante.', correct: ['mecanizada'] }
            ]
        },
        3: {
            title: 'Diseño de Relleno Sanitario y Bioseguridad',
            multiple: [
                { id: '3-1', question: '¿Cuál es la primera finalidad de la Gestión Integral de los Residuos Sólidos según el D.L. 1278?', options: ['A) La disposición final de los residuos.', 'B) La prevención o minimización de la generación de residuos sólidos en origen.', 'C) El transporte y barrido de calles.', 'D) La construcción de botaderos municipales.'], correct: 'B' },
                { id: '3-2', question: '¿Qué norma legal aprueba la actual Ley de Gestión Integral de Residuos Sólidos en el Perú?', options: ['A) Ley Nº 27314', 'B) Decreto Supremo Nº 014-2017-MINAM', 'C) Decreto Legislativo Nº 1278', 'D) Resolución Ministerial Nº 1501'], correct: 'C' },
                { id: '3-3', question: 'De acuerdo al Artículo 2 del D.L. 1278, la disposición final de los residuos sólidos constituye:', options: ['A) El principal método de valorización.', 'B) El primer paso del manejo de residuos.', 'C) La última alternativa de manejo.', 'D) Un proceso obsoleto y prohibido.'], correct: 'C' },
                { id: '3-4', question: '¿Mediante qué dispositivo se aprobó el Reglamento del Decreto Legislativo N° 1278?', options: ['A) D.S. Nº 014-2017-MINAM', 'B) D.L. 1501', 'C) R.M. Nº 1278-2018', 'D) D.S. Nº 004-2016-MINAM'], correct: 'A' },
                { id: '3-5', question: 'A nivel nacional, ¿a cuánto asciende la generación de residuos sólidos municipales por día, según los datos del MINAM mostrados?', options: ['A) 5.000 toneladas al día', 'B) 10.000 toneladas al día', 'C) 19.000 toneladas al día', 'D) 25.000 toneladas al día'], correct: 'C' },
                { id: '3-6', question: 'Según las diapositivas, la generación diaria de residuos sólidos en el Perú equivale a llenar:', options: ['A) 1 estadio nacional', 'B) 3 estadios nacionales', 'C) 5 estadios nacionales', 'D) 10 estadios nacionales'], correct: 'B' },
                { id: '3-7', question: '¿Qué institución elabora y administra el Inventario Nacional de Áreas Degradadas por Residuos Sólidos Municipales?', options: ['A) Ministerio de Salud (MINSA)', 'B) Ministerio del Ambiente (MINAM)', 'C) Organismo de Evaluación y Fiscalización Ambiental (OEFA)', 'D) Gobierno Regional'], correct: 'C' },
                { id: '3-8', question: 'Según el reporte de OEFA del 2018, ¿cuántos botaderos (áreas degradadas) se han identificado a nivel nacional?', options: ['A) 548', 'B) 1,023', 'C) 1,585', 'D) 3,450'], correct: 'C' },
                { id: '3-9', question: 'De las áreas degradadas identificadas, ¿cuántas han sido categorizadas como aptas para ser "reconvertidas" en infraestructura formal (rellenos sanitarios)?', options: ['A) 1,558', 'B) 149', 'C) 27', 'D) 54'], correct: 'C' },
                { id: '3-10', question: '¿Qué se debe hacer con los 1,558 botaderos que han sido categorizados como áreas a ser "recuperadas"?', options: ['A) Clausurarlas e iniciar un proceso de recuperación de la zona.', 'B) Ampliarlas para convertirlas en rellenos de seguridad.', 'C) Vender los terrenos a empresas privadas de reciclaje.', 'D) Utilizarlas indefinidamente hasta agotar su capacidad.'], correct: 'A' },
                { id: '3-11', question: '¿Qué significa la sigla PIFA en el contexto de las herramientas del OEFA?', options: ['A) Plan Integral de Fiscalización Ambiental', 'B) Portal Interactivo de Fiscalización Ambiental', 'C) Programa de Inversión y Formación Ambiental', 'D) Proyecto Integrado de Fuentes Ambientales'], correct: 'B' },
                { id: '3-12', question: 'Según el gráfico del Inventario Nacional del OEFA, ¿qué departamento presenta la mayor cantidad de áreas degradadas (149 botaderos)?', options: ['A) Cajamarca', 'B) Áncash', 'C) Puno', 'D) Lima'], correct: 'B' },
                { id: '3-13', question: '¿Cuál de los siguientes no es un impacto generado por los botaderos según el esquema presentado?', options: ['A) Contaminación de acuíferos por lixiviados.', 'B) Generación de biogás que causa efecto invernadero.', 'C) Reducción de la huella de carbono municipal.', 'D) Propagación de plagas y enfermedades.'], correct: 'C' },
                { id: '3-14', question: 'En la composición típica de los residuos sólidos municipales, ¿qué porcentaje representan los residuos sólidos orgánicos?', options: ['A) 19%', 'B) 20%', 'C) 54%', 'D) 7%'], correct: 'C' },
                { id: '3-15', question: '¿Qué porcentaje de los residuos sólidos municipales corresponde a "Residuos Inorgánicos Valorizables"?', options: ['A) 54%', 'B) 20%', 'C) 19%', 'D) 7%'], correct: 'B' },
                { id: '3-16', question: '¿Qué porcentaje representan los residuos sólidos peligrosos en el flujo municipal?', options: ['A) 7%', 'B) 19%', 'C) 20%', 'D) 54%'], correct: 'A' },
                { id: '3-17', question: '¿Cómo se denomina al proceso que permite transformar áreas donde se dispone basura de forma inadecuada en rellenos sanitarios formales?', options: ['A) Recuperación', 'B) Reconversión', 'C) Tratamiento térmico', 'D) Valorización material'], correct: 'B' },
                { id: '3-18', question: 'En el ciclo del manejo de residuos sólidos presentado, ¿cuál es el proceso que sigue inmediatamente después de la "Segregación"?', options: ['A) Tratamiento', 'B) Disposición Final', 'C) Barrido y limpieza de espacios públicos', 'D) Transferencia'], correct: 'C' },
                { id: '3-19', question: 'Los lugares donde se ha realizado acumulación de residuos sólidos sin consideraciones técnicas ni autorización son definidos legalmente como:', options: ['A) Rellenos sanitarios temporales.', 'B) Áreas degradadas por residuos sólidos.', 'C) Centros de acopio municipal.', 'D) Plantas de valorización inorgánica.'], correct: 'B' },
                { id: '3-20', question: 'El botadero conocido como "El Milagro", referenciado en las diapositivas, se encuentra ubicado en la ciudad de:', options: ['A) Chimbote', 'B) Tacna', 'C) Trujillo', 'D) Lima'], correct: 'C' }
            ],
            fill: [
                { id: '3-21', question: 'La gestión de los residuos sólidos en el país tiene como finalidad su manejo integral y ________.', correct: ['sostenible'] },
                { id: '3-22', question: 'El Decreto Legislativo N° 1278 establece derechos, atribuciones y responsabilidades de la sociedad en su conjunto: ________.', correct: ['obligaciones'] },
                { id: '3-23', question: 'Respecto de los residuos generados, la ley prefiere la recuperación y la ________ material y energética de los mismos.', correct: ['valorización', 'valorizacion'] },
                { id: '3-24', question: 'Las áreas degradadas son lugares de acumulación permanente de residuos sin las consideraciones ________ establecidas.', correct: ['técnicas', 'tecnicas'] },
                { id: '3-25', question: 'El Reglamento del D.L. 1278 fue promulgado mediante el Decreto Supremo N° ________ -MINAM.', correct: ['014-2017'] },
                { id: '3-26', question: 'El Ministerio del Ambiente publicó Guías Técnicas para la formulación del Plan de ________ de áreas degradadas.', correct: ['recuperación', 'recuperacion'] },
                { id: '3-27', question: 'Asimismo, existe una guía específica para el Programa de ________ y Manejo de áreas degradadas (cuando el botadero pasará a ser relleno).', correct: ['reconversión', 'reconversion'] },
                { id: '3-28', question: 'Los botaderos informales generan problemas de salud pública atrayendo vectores y ________.', correct: ['plagas', 'enfermedades'] },
                { id: '3-29', question: 'En los botaderos se produce un gas que contribuye al efecto invernadero: ________.', correct: ['biogás', 'biogas'] },
                { id: '3-30', question: 'El líquido altamente contaminante que se filtra a través de la basura y llega a los acuíferos subterráneos se denomina ________.', correct: ['lixiviado', 'lixiviados'] },
                { id: '3-31', question: 'El ________ es el organismo encargado de elaborar y administrar el Inventario Nacional de Áreas Degradadas.', correct: ['OEFA', 'UEFA'] },
                { id: '3-32', question: 'Según el Inventario, el departamento de Cajamarca cuenta con ________ áreas degradadas identificadas (indicar el número).', correct: ['123'] },
                { id: '3-33', question: 'El botadero "Alto Intiorko", mostrado a través de la plataforma PIFA, pertenece a la municipalidad provincial de ________.', correct: ['Tacna'] },
                { id: '3-34', question: 'La composición de los residuos indica que el 19% corresponde a residuos sólidos valorizables ________.', correct: ['no'] },
                { id: '3-35', question: 'El proceso de juntar residuos específicos en contenedores diferenciados en origen se denomina ________.', correct: ['segregación', 'segregacion'] },
                { id: '3-36', question: 'Antes de llegar a la disposición final o al tratamiento, los residuos pueden pasar por una planta de ________ para optimizar su transporte.', correct: ['transferencia'] },
                { id: '3-37', question: 'En total, se identificaron a nivel nacional ________ botaderos (indicar la cifra exacta según OEFA 2018).', correct: ['1585', '1,585'] },
                { id: '3-38', question: 'De ellos, 1,558 botaderos tienen que iniciar un proceso de cierre y ________ debido a su impacto ambiental negativo.', correct: ['recuperación', 'recuperacion'] },
                { id: '3-39', question: 'La ley busca maximizar la ________ en el uso de los materiales en todo el ciclo de vida del producto.', correct: ['eficiencia'] },
                { id: '3-40', question: 'La Ley exige que el manejo de residuos se sujete a los principios de minimización, prevención de riesgos ambientales y protección a la ________ y bienestar de la persona.', correct: ['salud'] }
            ]
        },
        4: {
            title: 'Diseño y Cálculo de Relleno Sanitario',
            multiple: [
                { id: '4-1', question: '¿Cuál es el rango de densidad aproximada esperada para un relleno sanitario operado de forma manual (o a 6 t/día)?', options: ['A) 0.3 a 0.5 t/m3', 'B) 0.5 a 0.6 t/m3', 'C) 0.6 a 0.7 t/m3', 'D) 0.7 a 1.0 t/m3'], correct: 'B' },
                { id: '4-2', question: 'Para calcular el Volumen del material de cobertura respecto al volumen de residuos sólidos, ¿qué rango porcentual se emplea?', options: ['A) Entre 10% y 15%', 'B) Entre 15% y 20%', 'C) Entre 20% y 25%', 'D) Entre 25% y 35%'], correct: 'C' },
                { id: '4-3', question: 'En la fórmula del Área Total Requerida (AT = F × ARS), ¿qué porcentaje de área adicional (Factor F) se considera para vías, áreas de aislamiento e instalaciones?', options: ['A) Entre 5% y 10%', 'B) Entre 10% y 20%', 'C) Entre 20% y 40%', 'D) Entre 40% y 50%'], correct: 'C' },
                { id: '4-4', question: '¿Cuál es la densidad de compactación típica lograda en un relleno semimecanizado (6 a 50 t/día)?', options: ['A) 0.4 - 0.5 t/m3', 'B) 0.5 - 0.6 t/m3', 'C) 0.6 - 0.7 t/m3', 'D) 0.7 - 1.0 t/m3'], correct: 'C' },
                { id: '4-5', question: 'Según los periodos de vida útil, ¿cuánto tiempo como mínimo debe considerarse para la infraestructura de disposición final de residuos sólidos (Relleno Sanitario)?', options: ['A) No menor a 3 años', 'B) No menor a 5 años', 'C) No menor a 10 años', 'D) No menor a 15 años'], correct: 'C' },
                { id: '4-6', question: '¿Cuál es la vida útil máxima recomendada para el funcionamiento de una "Celda transitoria"?', options: ['A) 2 años', 'B) 3 años', 'C) 5 años', 'D) 10 años'], correct: 'B' },
                { id: '4-7', question: '¿Cuál es la vida útil recomendable para una nave de pretratamiento y relleno seco?', options: ['A) No menor a 5 años', 'B) Máximo 10 años', 'C) No menor a 15 años', 'D) Entre 3 y 5 años'], correct: 'C' },
                { id: '4-8', question: 'En el esquema de impermeabilización de la base, ¿cuál es el espesor de la geomembrana HDPE indicada?', options: ['A) 0.5 mm', 'B) 1.0 mm', 'C) 1.5 mm', 'D) 2.0 mm'], correct: 'C' },
                { id: '4-9', question: '¿Qué especificación técnica corresponde al geotextil no tejido utilizado en la base del relleno?', options: ['A) 100 gr/m2', 'B) 200 gr/m2', 'C) 300 gr/m2', 'D) 500 gr/m2'], correct: 'C' },
                { id: '4-10', question: 'Según el esquema de corte, ¿cuál es el espesor de la "capa granulada de protección" que se coloca sobre los geosintéticos?', options: ['A) 0.10 m (10 cm)', 'B) 0.20 m (20 cm)', 'C) 0.30 m (30 cm)', 'D) 0.40 m (40 cm)'], correct: 'B' },
                { id: '4-11', question: 'Para un relleno sanitario semimecanizado, ¿cuál es el espesor de la "base conformada (tierra seleccionada)" bajo la geomembrana?', options: ['A) 0.20 m', 'B) 0.40 m', 'C) 0.60 m', 'D) 0.80 m'], correct: 'B' },
                { id: '4-12', question: 'Para calcular el volumen neto de residuos sólidos a disponer (m³/año), se debe dividir la generación anual en toneladas entre:', options: ['A) El factor de aumento F.', 'B) La densidad de los residuos sólidos compactados.', 'C) El volumen del material de cobertura.', 'D) La tasa de crecimiento poblacional.'], correct: 'B' },
                { id: '4-13', question: 'En los parámetros para el cálculo del volumen de recepción en trinchera, la variable "a" (minúscula) representa:', options: ['A) El ancho de la base mayor.', 'B) El ancho de la base menor.', 'C) El largo de la base mayor.', 'D) La altura.'], correct: 'C' },
                { id: '4-14', question: 'En el dimensionamiento de una trinchera, la letra "h" representa:', options: ['A) El largo de base mayor', 'B) El ancho de base menor', 'C) La humedad de los residuos', 'D) La altura o profundidad'], correct: 'D' },
                { id: '4-15', question: 'Un relleno sanitario que recibe más de 50 t/día (> 50) y emplea compactación mecánica se clasifica como:', options: ['A) Relleno Manual', 'B) Relleno Semimecanizado', 'C) Relleno Mecanizado', 'D) Botadero Controlado'], correct: 'C' },
                { id: '4-16', question: '¿Qué método geométrico es referido implícitamente en el cálculo de volumen de trincheras para integrar bases distintas con una altura?', options: ['A) Método de áreas promedio y altura.', 'B) Método del cilindro regular.', 'C) Método de polígonos de Thiessen.', 'D) Método de secciones rectangulares simples.'], correct: 'A' },
                { id: '4-17', question: 'En la matriz de diseño, el Volumen de la Celda Diaria resulta de la suma aritmética de:', options: ['A) El volumen de lixiviados y el de biogás.', 'B) El volumen de los residuos más el volumen de material de cobertura.', 'C) La densidad per cápita y la altura de la celda.', 'D) El área a rellenar y el área total requerida.'], correct: 'B' },
                { id: '4-18', question: 'En el cálculo de base para un relleno sanitario mecanizado, el espesor de la base conformada (tierra seleccionada) exigido es de:', options: ['A) 0.20 m', 'B) 0.40 m', 'C) 0.60 m', 'D) 0.80 m'], correct: 'D' },
                { id: '4-19', question: 'Al proyectar la cantidad total de residuos municipales anuales (t/año), se suman los residuos domiciliarios, no domiciliarios, de almacenamiento y:', options: ['A) Escombros de construcción.', 'B) Residuos peligrosos hospitalarios.', 'C) Residuos de barrido.', 'D) Residuos radiactivos.'], correct: 'C' },
                { id: '4-20', question: '¿Qué maquinaria/equipo caracteriza la compactación del relleno manual?', options: ['A) Tractores oruga.', 'B) Pisones manuales.', 'C) Rodillos pata de cabra.', 'D) Compactadoras hidráulicas estacionarias.'], correct: 'B' }
            ],
            fill: [
                { id: '4-21', question: 'En las fórmulas de cálculo poblacional, la generación ________ de residuos sólidos (ej. 0.391 kg/hab) es clave para estimar los volúmenes futuros.', correct: ['per cápita', 'per capita'] },
                { id: '4-22', question: 'Para calcular el Área Total (AT), se multiplica el factor "F" por el área a rellenar ________ de m2.', correct: ['sucesivamente'] },
                { id: '4-23', question: 'El Área Total incluye áreas administrativas, patio de ________, vías e instalaciones.', correct: ['maniobras'] },
                { id: '4-24', question: 'La vida útil mínima de un relleno sanitario debe ser no menor a ________ años.', correct: ['10', 'diez'] },
                { id: '4-25', question: 'Por el contrario, una celda ________ está diseñada para tener una vida útil máxima de 3 años.', correct: ['transitoria'] },
                { id: '4-26', question: 'La densidad de compactación esperada en un relleno mecanizado es del orden de ________ a 1.0 t/m3.', correct: ['0.7', '0.70'] },
                { id: '4-27', question: 'Según el método volumétrico de trincheras, la variable "b" minúscula representa el ________ de la base mayor.', correct: ['ancho'] },
                { id: '4-28', question: 'Así mismo, la variable "c" minúscula hace referencia al ancho de la base ________.', correct: ['menor'] },
                { id: '4-29', question: 'En el sistema de impermeabilización, debajo de la capa granulada de protección (0.20m), se instala el ________ no tejido de 300 gr/m2.', correct: ['geotextil'] },
                { id: '4-30', question: 'La barrera impermeable principal sobre la base de tierra seleccionada está compuesta por una ________ HDPE de 1.5mm.', correct: ['geomembrana'] },
                { id: '4-31', question: 'En un relleno de tipo ________, el nivel de compactación y la cantidad diaria oscila típicamente entre 6 y 50 t/día.', correct: ['semimecanizado'] },
                { id: '4-32', question: 'Para un relleno mecanizado, la tierra seleccionada que sirve como base conformada debe alcanzar un espesor de ________ m (80 cm).', correct: ['0.80', '0,80'] },
                { id: '4-33', question: 'En la base de todas las capas de impermeabilización y conformación, se encuentra el suelo original ________.', correct: ['compactado'] },
                { id: '4-34', question: 'El volumen de ________ de cobertura necesario se estima convencionalmente entre el 20% y el 25% del volumen de los residuos.', correct: ['material'] },
                { id: '4-35', question: 'La vida útil recomendable para una nave de pretratamiento y relleno ________ no debe ser menor a 15 años.', correct: ['seco'] },
                { id: '4-36', question: 'Para hallar el volumen anual de los residuos sólidos (m³/año), la fórmula indica que VRS = Generación municipal (t/año) / ________.', correct: ['densidad'] },
                { id: '4-37', question: 'En la geometría de la celda diaria, el área horizontal por la que los camiones ingresan a dejar el material se denomina frente de ________.', correct: ['descarga'] },
                { id: '4-38', question: 'La altura promedio (h) multiplicada por el Área a rellenar sucesivamente (ARS) debe darnos como resultado el ________ del relleno sanitario (VRS).', correct: ['volumen'] },
                { id: '4-39', question: 'Las siglas HDPE correspondientes al material de impermeabilización significan Polietileno de densidad ________ (en su traducción del inglés High Density Polyethylene).', correct: ['alta'] },
                { id: '4-40', question: 'Una localidad que genera menos de 6 t/día requiere implementar un relleno sanitario de tipo ________.', correct: ['manual'] }
            ]
        },
        5: {
            title: 'Estudio de Selección de Sitio',
            multiple: [
                { id: '5-1', question: 'Según la normativa peruana, ¿cuál es el principal objetivo de un Estudio de Selección de Área en este contexto?', options: ['A) Determinar la viabilidad económica de las empresas de reciclaje.', 'B) Identificar áreas potenciales en donde ubicar un relleno sanitario.', 'C) Clausurar botaderos informales en áreas protegidas.', 'D) Diseñar la infraestructura civil de la celda transitoria.'], correct: 'B' },
                { id: '5-2', question: '¿Qué Decreto Supremo aprueba el Reglamento de la Ley de Gestión Integral de Residuos Sólidos?', options: ['A) D.S Nº 014-2017-MINAM', 'B) D.S Nº 012-2015-MINAM', 'C) D.S Nº 1278-2017-PCM', 'D) D.S Nº 004-2018-MINAM'], correct: 'A' },
                { id: '5-3', question: 'De acuerdo al "Paso 1", ¿qué tipo de áreas se deben priorizar para la selección de sitio?', options: ['A) Únicamente áreas privadas sin uso agrícola.', 'B) Áreas públicas disponibles con las que cuente la municipalidad.', 'C) Áreas naturales protegidas por su lejanía.', 'D) Zonas de expansión urbana recientes.'], correct: 'B' },
                { id: '5-4', question: '¿Se pueden considerar áreas privadas para ubicar la infraestructura?', options: ['A) No, está estrictamente prohibido.', 'B) Sí, pero solo mediante expropiación forzosa del Estado.', 'C) Sí, si existe consentimiento previo del propietario.', 'D) Solo si la municipalidad no tiene ningún terreno público.'], correct: 'C' },
                { id: '5-5', question: 'En caso de existir discrepancia entre dos o más Municipalidades Provinciales respecto a la ubicación, ¿quién define la selección de áreas?', options: ['A) El Ministerio del Ambiente (MINAM).', 'B) El Gobierno Regional.', 'C) La Municipalidad Distrital afectada.', 'D) El Congreso de la República.'], correct: 'B' },
                { id: '5-6', question: 'Según el Artículo 110, ¿cuál es la distancia mínima general a poblaciones y granjas avícolas/porcinas?', options: ['A) No menor a 100 metros.', 'B) No menor a 300 metros.', 'C) No menor a 500 metros.', 'D) No menor a 1000 metros.'], correct: 'C' },
                { id: '5-7', question: 'El Artículo 110 establece que las infraestructuras de disposición final NO deben estar ubicadas en:', options: ['A) Zonas áridas y desérticas.', 'B) Zonas de pantanos, humedales o recarga de acuíferos.', 'C) Terrenos con pendientes menores al 2%.', 'D) Zonas cercanas a vías de acceso principales.'], correct: 'B' },
                { id: '5-8', question: 'Para ubicar una infraestructura cerca de aeródromos, se requiere opinión favorable de la DGAC si está dentro de un radio de:', options: ['A) 5.0 km del Punto de Referencia.', 'B) 10.0 km del Punto de Referencia.', 'C) 13.0 km del Punto de Referencia.', 'D) 20.0 km del Punto de Referencia.'], correct: 'C' },
                { id: '5-9', question: 'Una vez finalizado el Informe de Selección (Paso 5), ¿qué certificado se debe solicitar a la municipalidad provincial?', options: ['A) Certificado de Saneamiento Físico Legal.', 'B) Certificado de Compatibilidad de uso del terreno.', 'C) Certificado de Defensa Civil.', 'D) Certificado Ambiental.'], correct: 'B' },
                { id: '5-10', question: '¿Cuál es el peso ponderado del criterio "Distancia a la Población más cercana" en la matriz de calificación?', options: ['A) 3', 'B) 4', 'C) 5', 'D) 6'], correct: 'D' },
                { id: '5-11', question: 'En la matriz de calificación, ¿qué criterio tiene asignado un peso ponderado de 3 (el más bajo)?', options: ['A) Geología del suelo (permeabilidad).', 'B) Opinión Pública.', 'C) Posibilidad del material de cobertura.', 'D) Accesibilidad al área.'], correct: 'C' },
                { id: '5-12', question: '¿Qué puntaje base se le asigna a un criterio evaluado con un grado "Bueno"?', options: ['A) 1', 'B) 3', 'C) 5', 'D) 10'], correct: 'C' },
                { id: '5-13', question: 'Según la tabla de calificación, para que un terreno sea calificado como "Aceptable - Bueno", su puntaje ponderado total debe estar en el rango de:', options: ['A) 0 a 195', 'B) 195 a 355', 'C) 355 a 450', 'D) 450 a 600'], correct: 'B' },
                { id: '5-14', question: 'Un terreno con un puntaje ponderado total menor a 195 se clasifica como:', options: ['A) Aceptable - Bueno', 'B) Aceptable de Primera Opción - Muy Bueno', 'C) Terreno No Aceptable - Malo', 'D) Terreno Regular'], correct: 'C' },
                { id: '5-15', question: 'Según el contenido mínimo, el "Saneamiento físico legal del terreno" forma parte del:', options: ['A) Capítulo I', 'B) Capítulo II', 'C) Capítulo III', 'D) Anexo técnico'], correct: 'A' },
                { id: '5-16', question: 'En los criterios de selección (Artículo 109), se debe velar por la preservación de áreas naturales protegidas por:', options: ['A) Los municipios locales.', 'B) Las empresas privadas.', 'C) El Estado.', 'D) Las comunidades nativas.'], correct: 'C' },
                { id: '5-17', question: 'Según la Matriz de Calificación, ¿cuál de los siguientes criterios tiene un ponderado de 5?', options: ['A) Distancia a fallas geológicas.', 'B) Vulnerabilidad a desastres naturales.', 'C) Propiedad del terreno.', 'D) Área arqueológica.'], correct: 'D' },
                { id: '5-18', question: 'De acuerdo al inciso "a" del Art. 109, el área seleccionada debe ser compatible con:', options: ['A) Los planes de expansión urbana y uso de suelo.', 'B) La infraestructura vial nacional.', 'C) El desarrollo turístico regional.', 'D) Los corredores biológicos internacionales.'], correct: 'A' },
                { id: '5-19', question: '¿Qué instrumento de gestión ambiental se exige para la selección del sitio?', options: ['A) El Instrumento de Gestión Ambiental (IGA).', 'B) El Estudio de Impacto Ambiental detallado.', 'C) El Programa de Adecuación y Manejo Ambiental.', 'D) La Declaración de Impacto Ambiental.'], correct: 'A' },
                { id: '5-20', question: 'La Dirección predominante del viento debe ser idealmente ________ a la población más cercana.', options: ['A) perpendicular', 'B) paralela', 'C) contraria', 'D) indiferente'], correct: 'C' }
            ],
            fill: [
                { id: '5-21', question: 'El objetivo del estudio es identificar en el ámbito de estudio áreas potenciales en donde ubicar el ________.', correct: ['relleno sanitario'] },
                { id: '5-22', question: 'El Reglamento de la Ley de Gestión Integral de Residuos Sólidos fue aprobado mediante el Decreto Supremo Nº ________ -MINAM.', correct: ['014-2017'] },
                { id: '5-23', question: 'La municipalidad ________, en coordinación con la distrital, identifica los espacios geográficos en su jurisdicción.', correct: ['provincial'] },
                { id: '5-24', question: 'Según el Art. 109, la selección busca la minimización y prevención de los impactos sociales, sanitarios y ________ negativos.', correct: ['ambientales'] },
                { id: '5-25', question: 'Entre los factores que el Art. 109 manda evaluar están los climáticos, topográficos, geológicos, geomorfológicos e ________.', correct: ['hidrogeológicos', 'hidrogeologicos'] },
                { id: '5-26', question: 'Las infraestructuras no deben estar ubicadas a distancias menores de 500 metros de fuentes de aguas ________.', correct: ['superficiales'] },
                { id: '5-27', question: 'Las infraestructuras no deben ubicarse en zonas con presencia de ________ geológicas.', correct: ['fallas'] },
                { id: '5-28', question: 'Se debe evitar zonas donde se puedan generar asentamientos o ________ que desestabilicen la integridad de la infraestructura.', correct: ['deslizamientos'] },
                { id: '5-29', question: 'Entre los factores a evaluar también se consideran las ________.', correct: ['comunicaciones'] },
                { id: '5-30', question: 'En la sistematización de la información, se debe elaborar el ________ del Estudio de Selección de Área.', correct: ['informe'] },
                { id: '5-31', question: 'El Capítulo II de los contenidos mínimos exige la elaboración de una Matriz de ________ para la selección de sitio.', correct: ['calificación', 'calificacion'] },
                { id: '5-32', question: 'En la matriz de calificación, los criterios de distancia a poblaciones, fuentes de agua, granjas y fallas geológicas tienen un peso ponderado de ________.', correct: ['6'] },
                { id: '5-33', question: 'El criterio de "Vida útil" en la matriz recibe evaluación considerando si el terreno permite una vida útil menor o igual a ________ años.', correct: ['3', 'tres'] },
                { id: '5-34', question: 'Para evaluar un terreno, el grado calificado como "Malo" aporta ________ punto(s) antes de ser multiplicado por el ponderado.', correct: ['1', 'uno'] },
                { id: '5-35', question: 'El grado calificado como "Regular" aporta ________ punto(s) para la calificación del criterio.', correct: ['3', 'tres'] },
                { id: '5-36', question: 'Para calcular la Calificación final de cada criterio en la matriz, se multiplica el puntaje asignado por el ________ (AxB).', correct: ['ponderado'] },
                { id: '5-37', question: 'La alternativa seleccionada como ganadora será siempre aquella que obtenga el puntaje total ________.', correct: ['mayor'] },
                { id: '5-38', question: 'Una alternativa para ser considerada válida o ganadora debe superar obligatoriamente los ________ puntos.', correct: ['195'] },
                { id: '5-39', question: 'Un terreno calificado como "Aceptable de Primera Opción - Muy Bueno" debe alcanzar de ________ puntos a más.', correct: ['355'] },
                { id: '5-40', question: 'La Dirección predominante del viento debe ser idealmente ________ a la población más cercana.', correct: ['contraria'] }
            ]
        },
        6: {
            title: 'Área de Estudio, AID y AII',
            multiple: [
                { id: '6-1', question: '¿Qué Resolución Ministerial aprueba la Guía para la elaboración de la Línea Base en el marco del SEIA en 2025?', options: ['A) RM N° 00143-2025-MINAM', 'B) RM N° 27446-2025-MINAM', 'C) DS N° 019-2009-MINAM', 'D) RM N° 00125-2025-MINAM'], correct: 'A' },
                { id: '6-2', question: '¿En qué momento del proceso se define el Área de Estudio (también llamada área de actuación)?', options: ['A) Después de elaborar el Plan de Manejo Ambiental.', 'B) ANTES de la evaluación de impactos.', 'C) Al momento del cierre del proyecto.', 'D) Durante la fiscalización del OEFA.'], correct: 'B' },
                { id: '6-3', question: '¿En qué etapa del proceso técnico se define y delimita el Área de Influencia definitiva?', options: ['A) Etapa 1: Descripción del Proyecto.', 'B) Etapa 2: Área de influencia preliminar.', 'C) Etapa 3: Línea Base.', 'D) Etapa 6.d: Después de caracterizar y evaluar los impactos potenciales.'], correct: 'D' },
                { id: '6-4', question: 'El Área de Estudio Ambiental está conformada por:', options: ['A) Únicamente el área de emplazamiento.', 'B) Área de emplazamiento + Área de influencia preliminar + Zona de Control (+ zona de compensación, si aplica).', 'C) Las unidades vegetales y el ámbito político.', 'D) El área de reasentamiento poblacional.'], correct: 'B' },
                { id: '6-5', question: 'Para una mejor delimitación, el Área de Estudio Ambiental suele ajustarse a fronteras naturales, tales como:', options: ['A) Ríos y cuencas.', 'B) Límites distritales y provinciales exclusivamente.', 'C) Carreteras asfaltadas.', 'D) Concesiones mineras vecinas.'], correct: 'A' },
                { id: '6-6', question: '¿Cuál de los siguientes componentes NO forma parte del Área de Estudio Social?', options: ['A) Área de emplazamiento del proyecto.', 'B) Zonas de asentamiento y uso poblacional.', 'C) Ámbito político-administrativo en el que se desarrolla el proyecto.', 'D) Zona de Control Biológico de flora endémica.'], correct: 'D' },
                { id: '6-7', question: 'La suma de los espacios ocupados físicamente por los componentes y actividades del proyecto se denomina:', options: ['A) Área de Influencia Directa.', 'B) Área de Influencia Indirecta.', 'C) Área de Emplazamiento.', 'D) Zona de Control.'], correct: 'C' },
                { id: '6-8', question: 'El Área de Estudio Ambiental considera componentes de tipo:', options: ['A) Físico y químico únicamente.', 'B) Físico, biótico y socioeconómico.', 'C) Solo biótico.', 'D) Solo socioeconómico.'], correct: 'B' },
                { id: '6-9', question: '¿Cuál de las siguientes afirmaciones es correcta respecto al Área de Influencia?', options: ['A) Es siempre mayor que el Área de Estudio.', 'B) Es independiente del Área de Estudio.', 'C) Es siempre menor o igual que el Área de Estudio y resulta de la evaluación de impactos.', 'D) Solo se aplica a proyectos mineros.'], correct: 'C' },
                { id: '6-10', question: 'El Área de Influencia Directa (AID) se define como:', options: ['A) Donde llegan los efectos indirectos.', 'B) La microcuenca.', 'C) Donde llegan los impactos directos como ruido, polvo, cauces y predios.', 'D) El ámbito político regional.'], correct: 'C' },
                { id: '6-11', question: '¿Qué se entiende por Área de Influencia Indirecta (AII)?', options: ['A) La zona restringida al cerco perimétrico de la obra.', 'B) Donde llegan los efectos indirectos, como la microcuenca, localidades y distritos.', 'C) La zona donde no existe ningún tipo de impacto ambiental ni social.', 'D) El área designada para depositar material excedente.'], correct: 'B' },
                { id: '6-12', question: 'En el caso aplicado a un proyecto de carretera, ¿cómo se delimita inicialmente el área de estudio?', options: ['A) Se traza una banda a lo largo del eje y otra alrededor de canteras, depósitos y campamentos.', 'B) Se toma exclusivamente el polígono de la municipalidad distrital.', 'C) Se traza un círculo perfecto de 5 km de radio desde el campamento.', 'D) Se evalúa únicamente el punto de inicio y el punto final de la vía.'], correct: 'A' },
                { id: '6-13', question: 'Para un área de estudio menor de 5,000 hectáreas (ha), la guía recomienda utilizar mapas con una escala de trabajo de:', options: ['A) 1:100 000 – 1:250 000', 'B) 1:10 000 – 1:25 000', 'C) 1:1 000 – 1:5 000', 'D) 1:500 000'], correct: 'B' },
                { id: '6-14', question: 'En el caso de estudio de la carretera de 10 km, ¿cuántas etapas del proyecto se analizan?', options: ['A) Una (solo construcción).', 'B) Dos (construcción y operación).', 'C) Tres (construcción, operación y mantenimiento, cierre).', 'D) Cuatro (factibilidad, diseño, construcción y abandono).'], correct: 'C' },
                { id: '6-15', question: '¿Cuál de los siguientes es considerado un "Componente Auxiliar" dentro del caso de estudio de la carretera?', options: ['A) Derecho de vía y plataforma.', 'B) Canteras de material y campamento.', 'C) Caserío El Alto.', 'D) El eje principal de la carretera de 10 km.'], correct: 'B' },
                { id: '6-16', question: 'En la evaluación de "Aire y Ruido", ¿cuál se considera como el probable Área de Influencia Directa (AID)?', options: ['A) Las viviendas junto al eje, la cantera y el campamento.', 'B) Toda la cuenca hidrográfica.', 'C) El resto del área de estudio alejada de la obra.', 'D) Los distritos vecinos que no limitan con la vía.'], correct: 'A' },
                { id: '6-17', question: 'Para el factor "Agua", ¿hasta dónde se extiende el probable Área de Influencia Indirecta (AII)?', options: ['A) El cruce exacto de la quebrada.', 'B) Solamente el campamento de obreros.', 'C) La microcuenca de la quebrada.', 'D) Toda la región política.'], correct: 'C' },
                { id: '6-18', question: '¿Para qué factor se considera que el Área de Influencia Indirecta (AII) abarcaría "los distritos que usarán la vía"?', options: ['A) Flora y fauna.', 'B) Agua.', 'C) Población (social).', 'D) Aire y ruido.'], correct: 'C' },
                { id: '6-19', question: '¿Cuál es el Paso 3 del proceso de elaboración de la línea base?', options: ['A) Trabajo de campo.', 'B) Interpretación de datos.', 'C) Bases de datos y análisis.', 'D) Elaboración del informe final.'], correct: 'A' },
                { id: '6-20', question: '¿Qué se recomienda hacer antes de iniciar el trabajo de campo para la línea base?', options: ['A) Contratar personal extranjero.', 'B) Realizar una visita de reconocimiento (en la medida de lo posible).', 'C) Solicitar la certificación ambiental.', 'D) Construir el campamento.'], correct: 'B' }
            ],
            fill: [
                { id: '6-21', question: 'La Guía para la elaboración de la Línea Base en el marco del SEIA fue aprobada mediante la RM N° ________ -2025-MINAM.', correct: ['00143'] },
                { id: '6-22', question: 'El Área de Estudio también es conocida como área de actuación o de levantamiento de ________.', correct: ['información', 'informacion'] },
                { id: '6-23', question: 'El Área de ________ preliminar se basa en la potencial extensión de los impactos identificados durante el scoping.', correct: ['influencia'] },
                { id: '6-24', question: 'El proceso de "scoping" también es referido en los flujogramas como evaluación ambiental ________.', correct: ['preliminar'] },
                { id: '6-25', question: 'La delimitación del Área de Estudio se define ________ de la evaluación de impactos (antes / después).', correct: ['antes'] },
                { id: '6-26', question: 'El Área de Estudio Ambiental se ajusta a fronteras ________ como pueden ser ríos o cuencas.', correct: ['naturales'] },
                { id: '6-27', question: 'Para poder comparar los cambios futuros y tener una referencia sin impactos, dentro del Área de Estudio Ambiental se establece una Zona de ________.', correct: ['control'] },
                { id: '6-28', question: 'El Área de Estudio ________ incluye el área de emplazamiento, zonas de asentamiento/uso poblacional y el ámbito político-administrativo.', correct: ['social'] },
                { id: '6-29', question: 'Con el Área de Estudio Social se logran identificar las localidades que serán parte del plan de ________ ciudadana.', correct: ['participación', 'participacion'] },
                { id: '6-30', question: 'El Área de Influencia (AI) se obtiene como ________ final de la etapa de evaluación de impactos (Etapa 6.d).', correct: ['resultado'] },
                { id: '6-31', question: 'El Área de Influencia siempre será menor o ________ que el área de estudio inicial.', correct: ['igual'] },
                { id: '6-32', question: 'El Área de Influencia ________ (AID) es donde llegan efectos inmediatos como ruido, polvo y afectación a predios.', correct: ['directa'] },
                { id: '6-33', question: 'El Área de Influencia ________ (AII) abarca los espacios donde llegan los efectos no inmediatos, como la microcuenca o los distritos colindantes.', correct: ['indirecta'] },
                { id: '6-34', question: 'En el caso de estudio presentado, se analiza una carretera que tiene una longitud de ________ km de eje de vía.', correct: ['10', 'diez'] },
                { id: '6-35', question: 'El proyecto de carretera del caso de estudio cuenta con ________ componentes auxiliares (escriba el número).', correct: ['6', 'seis'] },
                { id: '6-36', question: 'Entre los componentes auxiliares requeridos para abastecer de áridos y agregados a una obra vial, destacan las ________ de material.', correct: ['canteras'] },
                { id: '6-37', question: 'El lugar designado para disponer los materiales sobrantes o de descarte del movimiento de tierras se conoce por las siglas DME, que significa Depósito de Material ________.', correct: ['excedente'] },
                { id: '6-38', question: 'Según el esquema referencial del caso, el probable AID para la "Flora y fauna" abarca la vegetación removida y los ________ de la vía.', correct: ['bordes'] },
                { id: '6-39', question: 'El Paso 3 del proceso de elaboración de la línea base corresponde a las Bases de ________ y análisis.', correct: ['datos'] },
                { id: '6-40', question: 'El Paso 5 (último paso) consiste en la interpretación de los datos y elaboración del ________ final de la línea base.', correct: ['informe'] }
            ]
        },
        7: {
            title: 'Descripción del Proyecto e IGA',
            multiple: [
                { id: '7-1', question: '¿Qué es un proyecto de inversión en el contexto del SEIA?', options: ['A) Exclusivamente obras públicas financiadas por el Estado.', 'B) Toda iniciativa propuesta que puede generar cambios o impactos ambientales significativos.', 'C) Solamente proyectos del sector minero y petrolero.', 'D) Planes teóricos sin ejecución de obras físicas.'], correct: 'B' },
                { id: '7-2', question: 'La principal diferencia entre un proyecto público y uno privado, de acuerdo al marco del SEIA, es:', options: ['A) Que los proyectos públicos no requieren certificación ambiental.', 'B) Que los privados siempre tienen categoría III.', 'C) Quién lo promueve/financia y quién es su titular.', 'D) El tipo de maquinaria empleada en la construcción.'], correct: 'C' },
                { id: '7-3', question: 'Para que un proyecto sea evaluado obligatoriamente por el Sistema Nacional de Evaluación de Impacto Ambiental (SEIA), debe:', options: ['A) Superar los 10 millones de dólares de inversión.', 'B) Estar incluido en el Listado de Inclusión de proyectos administrado por el MINAM.', 'C) Ser ejecutado únicamente en la región amazónica.', 'D) Estar en la fase de operación y mantenimiento.'], correct: 'B' },
                { id: '7-4', question: 'Según el caso de estudio presentado en las diapositivas, ¿en qué localidad se ubica el proyecto de saneamiento?', options: ['A) Caserío El Verde, distrito de Cutervo, Cajamarca.', 'B) Provincia de Jaén, Cajamarca.', 'C) Distrito de San Ignacio, Amazonas.', 'D) Provincia de Chota, Cajamarca.'], correct: 'A' },
                { id: '7-5', question: 'Hidrográficamente, ¿en qué cuenca se emplaza el proyecto del caso de estudio?', options: ['A) Cuenca del río Jequetepeque.', 'B) Intercuenca Alto Marañón IV.', 'C) Cuenca del río Huallaga.', 'D) Intercuenca del Mantaro.'], correct: 'B' },
                { id: '7-6', question: '¿Qué caudal máximo diario ha sido acreditado por la ANA para la captación en la quebrada Cerro Negro?', options: ['A) 0.250 l/s', 'B) 0.492 l/s', 'C) 0.750 l/s', 'D) 1.000 l/s'], correct: 'B' },
                { id: '7-7', question: '¿Qué tipo de tubería se utiliza en la línea de conducción del proyecto?', options: ['A) PVC SAL de Ø 2"', 'B) HDPE PE-100 de Ø 11/2"', 'C) Concreto simple de Ø 8"', 'D) Fierro fundido de Ø 4"'], correct: 'B' },
                { id: '7-8', question: '¿Cuál es la función del sedimentador en el sistema de agua potable?', options: ['A) Eliminar bacterias y virus.', 'B) Almacenar agua para épocas de sequía.', 'C) Separar partículas mayores a 0.05 mm para mejorar la calidad del agua.', 'D) Regular la presión en las tuberías.'], correct: 'C' },
                { id: '7-9', question: 'En el cruce de quebradas, ¿qué estructura se utiliza para sostener la tubería?', options: ['A) Los muros de contención.', 'B) Las cámaras rompe presión.', 'C) Los biodigestores.', 'D) Los pases aéreos.'], correct: 'D' },
                { id: '7-10', question: '¿Cuál es la función de las Cámaras Rompe Presión tipo 07?', options: ['A) Eliminar el aire de las tuberías.', 'B) Controlar y evitar daños por presiones superiores a 50 m.c.a.', 'C) Medir el caudal que pasa por la tubería.', 'D) Almacenar agua para la cloración.'], correct: 'B' },
                { id: '7-11', question: 'El reservorio cuadrado diseñado para el proyecto tiene una capacidad de almacenamiento de:', options: ['A) 5 m3', 'B) 10 m3', 'C) 25 m3', 'D) 50 m3'], correct: 'B' },
                { id: '7-12', question: 'En el reservorio, el sistema de desinfección consiste en:', options: ['A) Radiación ultravioleta.', 'B) Ozono.', 'C) Cloración por goteo con un tanque de 600 litros.', 'D) Pastillas de cloro en el canal de conducción.'], correct: 'C' },
                { id: '7-13', question: 'Para la red de distribución se instalaron Cámaras Rompe Presión tipo 07 con el fin de regular presiones en zonas bajas. ¿Cuántas se instalarán en total?', options: ['A) 2', 'B) 7', 'C) 11', 'D) 18'], correct: 'D' },
                { id: '7-14', question: '¿Qué válvulas se ubican estratégicamente en los puntos bajos de las líneas de conducción y distribución para eliminar sedimentos?', options: ['A) Válvulas de aire.', 'B) Válvulas de control de presión.', 'C) Válvulas de purga.', 'D) Válvulas check.'], correct: 'C' },
                { id: '7-15', question: 'En las obras de saneamiento rural, la Unidad Básica de Saneamiento (UBS) cuenta con una caseta que incluye:', options: ['A) Lavadora, tina y retrete.', 'B) Inodoro, lavatorio y ducha.', 'C) Letrina de pozo ciego exclusivamente.', 'D) Inodoro y biodigestor familiar únicamente, sin lavatorio.'], correct: 'B' },
                { id: '7-16', question: 'Para la construcción de la captación y el reservorio, la resistencia del concreto utilizado principalmente en muros y estructuras de retención es:', options: ['A) f\'c= 100 kg/cm2', 'B) f\'c= 140 kg/cm2', 'C) f\'c= 175 kg/cm2', 'D) f\'c= 210 kg/cm2'], correct: 'D' },
                { id: '7-17', question: '¿Qué es el "Arrastre Hidráulico" mencionado en los componentes de saneamiento?', options: ['A) Es la erosión que sufre la tubería por la velocidad del agua.', 'B) El sistema de captación en la quebrada.', 'C) El sistema que utiliza la fuerza del agua para transportar las excretas desde el inodoro al biodigestor.', 'D) El desvío de los cauces de los ríos durante la construcción.'], correct: 'C' },
                { id: '7-18', question: 'La caseta de la UBS requiere un techo con una inclinación mayor al 10% con la finalidad de:', options: ['A) Ahorrar materiales de construcción.', 'B) Estética arquitectónica.', 'C) Proteger contra la intemperie y evitar el empozamiento por lluvias.', 'D) Facilitar la instalación de paneles solares.'], correct: 'C' },
                { id: '7-19', question: '¿Cuál es la función de la tubería de ventilación en las UBS?', options: ['A) Suministrar aire fresco al interior.', 'B) Permitir la salida de gases de los aparatos sanitarios y proteger el sello de agua.', 'C) Medir la presión del sistema.', 'D) Conectar el biodigestor con el alcantarillado.'], correct: 'B' },
                { id: '7-20', question: '¿Qué software se utilizó para el modelamiento hidráulico de la red de distribución?', options: ['A) AutoCAD', 'B) SAP2000', 'C) WATERCAD V8i', 'D) ArcGIS'], correct: 'C' }
            ],
            fill: [
                { id: '7-21', question: 'La diferencia principal entre un proyecto público y privado bajo el SEIA, es quién lo promueve, financia y quién es su ________.', correct: ['titular'] },
                { id: '7-22', question: 'La institución que administra y mantiene actualizado el "Listado de Inclusión de proyectos sujetos al SEIA" es el ________.', correct: ['MINAM', 'Ministerio del Ambiente'] },
                { id: '7-23', question: 'En el caso de estudio de las diapositivas, la entidad que actúa como OPMI en la Fase de Ejecución es el Gobierno Regional de ________.', correct: ['Cajamarca'] },
                { id: '7-24', question: 'Según la clasificación del sector, la tipología funcional del proyecto de El Verde corresponde a "Sistema de ________ Rural".', correct: ['saneamiento'] },
                { id: '7-25', question: 'La fuente de agua seleccionada para la captación se ubica en la quebrada denominada ________.', correct: ['Cerro Negro'] },
                { id: '7-26', question: 'La estructura de captación diseñada en la quebrada es del tipo ________ y utilizará escollera empedrada.', correct: ['barraje'] },
                { id: '7-27', question: 'En las obras de captación y reservorio, el acero de refuerzo empleado habitualmente para resistir tracción es de diámetro ________ (indicar medida en pulgadas).', correct: ['1/2"', 'media pulgada'] },
                { id: '7-28', question: 'Las tuberías principales de la línea de conducción serán del material conocido por sus siglas HDPE, que significa Polietileno de Alta ________.', correct: ['densidad'] },
                { id: '7-29', question: 'Para sostener las tuberías HDPE al atravesar terrenos irregulares o hondonadas, se construirán 11 ________ de diferentes longitudes (5 a 30 m).', correct: ['pases aéreos', 'pases aereos'] },
                { id: '7-30', question: 'La Cámara de Distribución de Caudales ha sido diseñada para fraccionar y dirigir el agua cruda hacia dos ________.', correct: ['reservorios'] },
                { id: '7-31', question: 'Se instalarán ________ válvulas de aire en los puntos altos de la red para evitar la formación de vacíos que dañen el sistema.', correct: ['7', 'siete'] },
                { id: '7-32', question: 'El sedimentador separará partículas sólidas mayores a ________ mm.', correct: ['0.05'] },
                { id: '7-33', question: 'Para la distribución final en las viviendas del caserío El Verde, el proyecto contempla la instalación de un total de ________ conexiones domiciliarias.', correct: ['121'] },
                { id: '7-34', question: 'En la red de distribución se instalarán cajas o cámaras, cuyas dimensiones típicas serán de ________ x 0.80 m.', correct: ['0.80'] },
                { id: '7-35', question: 'En las Unidades Básicas de Saneamiento (UBS), las dimensiones internas de la caseta serán de 1.65 x ________ m.', correct: ['1.50'] },
                { id: '7-36', question: 'El piso de las casetas de saneamiento (UBS) se construirá con concreto de resistencia f\'c = ________ kg/cm2.', correct: ['140'] },
                { id: '7-37', question: 'La tubería de ventilación en los sistemas de saneamiento (UBS) se conectará empleando tuberías de material ________ SAL de Ø 2".', correct: ['PVC'] },
                { id: '7-38', question: 'Todo proyecto público se caracteriza financieramente porque los fondos provienen de recursos ________.', correct: ['públicos', 'del Estado'] },
                { id: '7-39', question: 'Un proyecto ________ se caracteriza porque la inversión proviene de empresas o personas naturales.', correct: ['privado'] },
                { id: '7-40', question: 'La letrina ________ es una alternativa de saneamiento que no requiere agua para su funcionamiento.', correct: ['seca'] }
            ]
        },
        8: {
            title: 'Certificación Ambiental',
            multiple: [
                { id: '8-1', question: 'El Procedimiento Administrativo de Certificación Ambiental en el Perú se rige bajo el marco del SEIA, regulado por:', options: ['A) La Ley Nº 28611 y su Reglamento.', 'B) La Ley Nº 27446 y su Reglamento (D.S. Nº 019-2009-MINAM).', 'C) La Ley Nº 29325 y el D.S. Nº 004-2022-MINAM.', 'D) La Ley Nº 28090 exclusivamente.'], correct: 'B' },
                { id: '8-2', question: '¿Qué entidad evalúa los Estudios de Impacto Ambiental Detallados (EIA-d) de gran envergadura en sectores transferidos?', options: ['A) El MINAM', 'B) Las Autoridades Sectoriales (MTC, MINEM, etc.)', 'C) El SENACE', 'D) El OEFA'], correct: 'C' },
                { id: '8-3', question: '¿Cuál es el rol de las Autoridades Sectoriales respecto a los proyectos de Categoría I (DIA) y Categoría II (EIA-sd)?', options: ['A) Derivarlos al SENACE para su evaluación.', 'B) Emitir opinión técnica vinculante sin evaluar el fondo.', 'C) Conservar la competencia para su evaluación y certificación.', 'D) Revisarlos en conjunto con el MINCUL y la DICAPI únicamente.'], correct: 'C' },
                { id: '8-4', question: 'Un informe técnico desfavorable emitido por la ANA o el SERNANP genera obligatoriamente:', options: ['A) La paralización temporal del proyecto hasta una segunda revisión.', 'B) La desaprobación de la certificación ambiental por la autoridad.', 'C) La derivación del expediente al MINAM para dirimir.', 'D) La imposición de una multa económica por parte del OEFA.'], correct: 'B' },
                { id: '8-5', question: '¿Cuál es el objetivo principal del "Pliego Unificado" que elabora el SENACE o la autoridad sectorial?', options: ['A) Unificar los pagos administrativos de las empresas.', 'B) Consolidar a todas las consultoras ambientales en un solo registro.', 'C) Reunir los requerimientos de las entidades opinantes para evitar duplicidades o contradicciones.', 'D) Integrar los estudios de impacto ambiental de distintas empresas en una sola zona.'], correct: 'C' },
                { id: '8-6', question: '¿Qué función cumple la Ventanilla Única de Certificación Ambiental (EVA)?', options: ['A) Permitir que la información se tramite en paralelo a todas las entidades, estandarizando plazos.', 'B) Reemplazar la función evaluadora del SENACE.', 'C) Otorgar licencias de uso de agua y títulos habilitantes automáticamente.', 'D) Fiscalizar los compromisos ambientales y emitir sanciones.'], correct: 'A' },
                { id: '8-7', question: 'La aprobación de un Informe Técnico Sustentatorio (ITS) para modificación es aplicable a:', options: ['A) Proyectos nuevos sin certificación.', 'B) Proyectos que ya cuentan con una certificación previa.', 'C) Proyectos abandonados.', 'D) Proyectos en fase de fiscalización.'], correct: 'B' },
                { id: '8-8', question: '¿Qué entidad es la encargada de la evaluación ambiental de proyectos de infraestructura de residuos sólidos del ámbito municipal?', options: ['A) AMSAC', 'B) SENACE', 'C) OEFA', 'D) MINAM'], correct: 'A' },
                { id: '8-9', question: 'El Ministerio de la Producción (PRODUCE) evalúa la DIA y EIA-sd para:', options: ['A) Proyectos mineros.', 'B) Proyectos de infraestructura vial.', 'C) La industria manufacturera, comercio interno y pesca.', 'D) Proyectos de irrigación.'], correct: 'C' },
                { id: '8-10', question: 'La Dirección General de Asuntos Ambientales Agrarios (DGAAA), que evalúa proyectos de irrigación y ganadería intensiva, pertenece al:', options: ['A) MIDAGRI', 'B) MVCS', 'C) PRODUCE', 'D) MINAM'], correct: 'A' },
                { id: '8-11', question: 'Los Valores Máximos Admisibles (VMA) para vertimientos al alcantarillado son regulados por el Ministerio de:', options: ['A) Energía y Minas (MINEM)', 'B) Transportes y Comunicaciones (MTC)', 'C) Vivienda, Construcción y Saneamiento (MVCS)', 'D) Salud (MINSA)'], correct: 'C' },
                { id: '8-12', question: '¿Qué entidad evalúa si el proyecto cuenta con oferta hídrica suficiente y asegura la preservación del caudal ecológico?', options: ['A) El SERNANP', 'B) La Autoridad Nacional del Agua (ANA)', 'C) El OEFA', 'D) La Dirección General de Capitanías y Guardacostas (DICAPI)'], correct: 'B' },
                { id: '8-13', question: 'Si un titular responde las observaciones, pero la ANA mantiene su opinión "no favorable" al término de la subsanación, ¿qué sucede?', options: ['A) El titular tiene una segunda oportunidad indefinida para subsanar.', 'B) El proyecto debe ser evaluado directamente por el Presidente de la República.', 'C) La certificación queda automáticamente desaprobada.', 'D) Se aprueba el estudio pero con penalidades económicas.'], correct: 'C' },
                { id: '8-14', question: '¿Cuál es el organismo técnico especializado, adscrito al MINAM, que emite opinión técnica previa vinculante sobre Áreas Naturales Protegidas?', options: ['A) SENACE', 'B) ANA', 'C) SERNANP', 'D) DICAPI'], correct: 'C' },
                { id: '8-15', question: '¿Qué etapa es obligatoria ante el SERNANP para confirmar la admisibilidad legal y física según la zonificación y Plan Maestro del ANP?', options: ['A) La Evaluación de Compatibilidad', 'B) El Estudio Arqueológico', 'C) El Plan de Cierre', 'D) El Plan de Relaciones Comunitarias'], correct: 'A' },
                { id: '8-16', question: '¿Qué entidad actúa como la Autoridad Marítima Nacional y protege el medio acuático hasta las 200 millas náuticas, ríos y lagos navegables?', options: ['A) ANA', 'B) DICAPI', 'C) PRODUCE', 'D) MTC'], correct: 'B' },
                { id: '8-17', question: 'La opinión técnica favorable de la DICAPI es un prerrequisito indispensable para obtener:', options: ['A) El Certificado de Inexistencia de Restos Arqueológicos (CIRA).', 'B) La certificación ambiental.', 'C) El Derecho de Uso de Área Acuática y autorizaciones de construcción.', 'D) La licencia de funcionamiento.'], correct: 'C' },
                { id: '8-18', question: '¿Qué planes deben presentar los titulares para proteger el patrimonio arqueológico durante la ejecución de obras?', options: ['A) Planes de Monitoreo Arqueológico (PMA)', 'B) Planes de Manejo Ambiental', 'C) Planes de Cierre', 'D) Planes de Contingencia'], correct: 'A' },
                { id: '8-19', question: 'El proceso de diálogo entre el Estado y los pueblos indígenas para adoptar medidas legislativas o administrativas se denomina:', options: ['A) Consulta Previa', 'B) Audiencia Pública', 'C) Participación Ciudadana', 'D) Mesa de Diálogo'], correct: 'A' },
                { id: '8-20', question: '¿Qué siglas corresponden a los Pueblos Indígenas en Situación de Aislamiento y Contacto Inicial?', options: ['A) PIACI', 'B) PIA', 'C) PICI', 'D) PICAI'], correct: 'A' }
            ],
            fill: [
                { id: '8-21', question: 'El SEIA constituye el marco que evalúa de forma preventiva los impactos ambientales negativos significativos antes de su ejecución, y está regulado por la Ley N° ________.', correct: ['27446'] },
                { id: '8-22', question: 'El organismo técnico encargado de la certificación ambiental de proyectos de gran envergadura (Categoría III) en sectores transferidos se llama ________.', correct: ['SENACE'] },
                { id: '8-23', question: 'Las autoridades ________ (ej. MTC, MINEM) conservan la competencia sobre proyectos de menor y mediano impacto (DIA / EIA-sd).', correct: ['sectoriales'] },
                { id: '8-24', question: 'Un informe técnico ________ emitido por una entidad con competencia vinculante, como la ANA, obliga legalmente a la autoridad a rechazar la certificación.', correct: ['desfavorable'] },
                { id: '8-25', question: 'La herramienta digital que permite tramitar la información en paralelo a todas las entidades, estandarizando plazos y trazabilidad, se denomina Ventanilla Única (EVA).', correct: ['Ventanilla'] },
                { id: '8-26', question: 'Los cambios o modificaciones no significativas en proyectos con certificación previa se tramitan a través de los ITS, que significan Informes Técnicos ________.', correct: ['Sustentatorios', 'Sustentatorio'] },
                { id: '8-27', question: 'El MTC es la autoridad ambiental del sector transporte a través de la DGAAM, que significa Dirección General de Asuntos ________.', correct: ['Ambientales'] },
                { id: '8-28', question: 'Para proyectos en curso que necesitan regularizar su adecuación normativa, se evalúan los PAMA, que significan Programas de Adecuación y ________ Ambiental.', correct: ['Manejo'] },
                { id: '8-29', question: 'El Ministerio de Energía y ________ (MINEM) es la autoridad sectorial para actividades extractivas e hidrocarburos.', correct: ['Minas'] },
                { id: '8-30', question: 'La Dirección General de Asuntos Ambientales ________ (DGAAA) ejerce las funciones ambientales dentro del MIDAGRI.', correct: ['Agrarios'] },
                { id: '8-31', question: 'El ________ (Ministerio de la Producción) clasifica proyectos y evalúa la DIA y EIA-sd para la industria manufacturera, comercio interno y pesca.', correct: ['PRODUCE'] },
                { id: '8-32', question: 'El Ministerio de Vivienda, Construcción y ________ (MVCS) evalúa proyectos de infraestructura como agua potable, alcantarillado y PTAR.', correct: ['Saneamiento'] },
                { id: '8-33', question: 'La Autoridad Nacional del Agua (ANA) se encuentra adscrita actualmente al Ministerio denominado ________.', correct: ['MIDAGRI'] },
                { id: '8-34', question: 'Cuando se reutilizan efluentes tratados (riego, enfriamiento industrial), la ANA revisa los parámetros para autorizar el ________ de Aguas Residuales.', correct: ['Reúso', 'Reuso'] },
                { id: '8-35', question: 'El ente rector del Sistema Nacional de Áreas Naturales Protegidas por el Estado, que emite opinión técnica previa vinculante obligatoria, es el ________.', correct: ['SERNANP'] },
                { id: '8-36', question: 'La DICAPI ejerce competencia territorial en el medio acuático hasta las ________ millas náuticas.', correct: ['200'] },
                { id: '8-37', question: 'Las funciones de evaluar la seguridad náutica y los planes de contingencia por derrames de hidrocarburos corresponden a la institución conocida como ________.', correct: ['DICAPI', 'Dirección General de Capitanías y Guardacostas'] },
                { id: '8-38', question: 'El Ministerio de Cultura es responsable de acompañar técnicamente a SENACE durante el proceso de diálogo llamado Consulta ________.', correct: ['Previa'] },
                { id: '8-39', question: 'El certificado que se considera condición previa al inicio de obras civiles para garantizar la inexistencia de restos arqueológicos se conoce por sus siglas ________.', correct: ['CIRA'] },
                { id: '8-40', question: 'El acrónimo PIACI, cuyas reservas territoriales son protegidas estrictamente, significa Pueblos Indígenas en Situación de Aislamiento y ________ Inicial.', correct: ['Contacto'] }
            ]
        },
        9: {
            title: 'Ley del SEIA y Reglamento',
            multiple: [
                { id: '9-1', question: '¿Qué norma legal crea el Sistema Nacional de Evaluación de Impacto Ambiental (SEIA)?', options: ['A) Ley N° 28611', 'B) Ley N° 27446', 'C) Decreto Legislativo N° 1013', 'D) Ley N° 29325'], correct: 'B' },
                { id: '9-2', question: 'Según el SEIA, ¿qué instrumento de gestión ambiental evalúa las políticas, planes y programas públicos?', options: ['A) Estudio de Impacto Ambiental Detallado (EIA-d)', 'B) Declaración de Impacto Ambiental (DIA)', 'C) Evaluación Ambiental Estratégica (EAE)', 'D) Programa de Adecuación y Manejo Ambiental (PAMA)'], correct: 'C' },
                { id: '9-3', question: '¿A qué categoría del SEIA corresponden los proyectos cuyos impactos ambientales negativos se consideran "leves"?', options: ['A) Categoría I', 'B) Categoría II', 'C) Categoría III', 'D) Categoría IV'], correct: 'A' },
                { id: '9-4', question: 'Los proyectos que pueden producir impactos ambientales negativos "moderados" requieren un:', options: ['A) DIA', 'B) EIA-sd (Estudio de Impacto Ambiental Semidetallado)', 'C) EIA-d (Estudio de Impacto Ambiental Detallado)', 'D) PAMA'], correct: 'B' },
                { id: '9-5', question: '¿Qué entidad es el organismo rector y administrador del SEIA a nivel nacional?', options: ['A) OEFA', 'B) SENACE', 'C) MINAM', 'D) PCM'], correct: 'C' },
                { id: '9-6', question: '¿Qué entidad es responsable de la supervisión, fiscalización y sanción del cumplimiento de los estudios ambientales?', options: ['A) MINAM', 'B) OEFA', 'C) Ministerio de Cultura', 'D) Gobierno Local'], correct: 'B' },
                { id: '9-7', question: '¿Cuál es el requisito previo e indispensable para iniciar la ejecución de un proyecto de inversión sujeto al SEIA?', options: ['A) La Licencia de Construcción', 'B) El Certificado de Inexistencia de Restos Arqueológicos (CIRA)', 'C) La Certificación Ambiental', 'D) La Autorización de Uso de Agua'], correct: 'C' },
                { id: '9-8', question: 'Si un proyecto incluye actividades de competencia de dos o más sectores distintos, ¿quién será la Autoridad Competente para otorgar la Certificación Ambiental?', options: ['A) El MINAM, de manera exclusiva.', 'B) El sector donde el proyecto ocupe mayor área geográfica.', 'C) El sector al que corresponda la actividad por la que el titular obtiene sus mayores ingresos brutos anuales.', 'D) Ambos sectores de manera compartida emitiendo dos certificaciones.'], correct: 'C' },
                { id: '9-9', question: 'Según el Reglamento del SEIA, ¿cuál es el plazo máximo de vigencia de la Certificación Ambiental si el titular no inicia las obras del proyecto?', options: ['A) 1 año', 'B) 2 años', 'C) 3 años, ampliable hasta por 2 años adicionales.', 'D) 5 años, sin posibilidad de prórroga.'], correct: 'C' },
                { id: '9-10', question: 'Para la aprobación de Estudios de Impacto Ambiental relacionados con el recurso hídrico, se debe contar obligatoriamente con la opinión técnica favorable de:', options: ['A) SERNANP', 'B) OEFA', 'C) Autoridad Nacional del Agua (ANA)', 'D) Ministerio de Salud (MINSA)'], correct: 'C' },
                { id: '9-11', question: 'Si un proyecto se localiza al interior de un Área Natural Protegida (ANP) o en su zona de amortiguamiento, ¿a qué entidad se debe solicitar opinión técnica favorable?', options: ['A) SERFOR', 'B) SERNANP', 'C) Gobierno Regional', 'D) Ministerio de Cultura'], correct: 'B' },
                { id: '9-12', question: '¿Qué nombre recibe la medida correctiva que busca atenuar o minimizar los impactos negativos que un proyecto puede generar sobre el ambiente?', options: ['A) Restauración', 'B) Compensación', 'C) Mitigación', 'D) Prevención'], correct: 'C' },
                { id: '9-13', question: 'De acuerdo al flujograma del procedimiento de certificación (Art. 6 de la Ley), ¿qué etapa continúa inmediatamente después de la "Presentación de la solicitud"?', options: ['A) Resolución', 'B) Clasificación de la acción', 'C) Seguimiento y control', 'D) Revisión del estudio de impacto ambiental'], correct: 'B' },
                { id: '9-14', question: 'Toda documentación incluida en el expediente administrativo de evaluación de impacto ambiental tiene carácter:', options: ['A) Confidencial', 'B) Secreto de Estado', 'C) Público (salvo la expresamente declarada reservada o confidencial)', 'D) Privado para uso exclusivo del titular'], correct: 'C' },
                { id: '9-15', question: 'El proceso mediante el cual los ciudadanos intervienen responsablemente y de buena fe en la definición y aplicación de las políticas y toma de decisiones ambientales se denomina:', options: ['A) Consulta Previa', 'B) Participación Ciudadana', 'C) Vigilancia Ambiental', 'D) Audiencia de Clasificación'], correct: 'B' },
                { id: '9-16', question: '¿A qué se refiere el término "Línea base" dentro de un Estudio de Impacto Ambiental?', options: ['A) Al presupuesto mínimo para ejecutar el proyecto.', 'B) A la zona donde se ubicarán los campamentos.', 'C) Al estado actual del área de actuación, previa a la ejecución de un proyecto.', 'D) A la primera fase de construcción de la obra.'], correct: 'C' },
                { id: '9-17', question: 'Según el Reglamento del SEIA, el proceso de evaluación de un Estudio de Impacto Ambiental Semidetallado (EIA-sd) se lleva a cabo en un plazo máximo legal de:', options: ['A) 30 días hábiles', 'B) 60 días hábiles', 'C) 90 días hábiles', 'D) 120 días hábiles'], correct: 'C' },
                { id: '9-18', question: '¿Con qué frecuencia el titular debe actualizar su Estudio Ambiental aprobado, en aquellos componentes que lo requieran, después de iniciada la ejecución del proyecto?', options: ['A) Al tercer año.', 'B) Al quinto año, y por periodos consecutivos similares.', 'C) Cada año obligatoriamente.', 'D) No existe obligación legal de actualizarlo.'], correct: 'B' },
                { id: '9-19', question: '¿Qué tipo de impactos son aquellos ocasionados por la acción humana sobre los componentes del ambiente, a partir de la ocurrencia de otros con los cuales están interrelacionados o son secuenciales?', options: ['A) Impactos Directos', 'B) Impactos Indirectos', 'C) Impactos Sinérgicos', 'D) Impactos Acumulativos'], correct: 'B' },
                { id: '9-20', question: 'Los documentos que el titular presente ante la Autoridad Competente para el SEIA deben estar redactados obligatoriamente en:', options: ['A) Inglés y Español', 'B) Castellano', 'C) El idioma oficial del lugar donde provengan los fondos del proyecto', 'D) La lengua nativa de la comunidad más cercana'], correct: 'B' }
            ],
            fill: [
                { id: '9-21', question: 'El Sistema Nacional de Evaluación de Impacto Ambiental fue creado por la Ley N° ________.', correct: ['27446'] },
                { id: '9-22', question: 'La resolución que aprueba el estudio de impacto ambiental constituye la ________ Ambiental, quedando así autorizada la ejecución del proyecto.', correct: ['Certificación'] },
                { id: '9-23', question: 'Los proyectos cuyas características, envergadura y/o localización pueden producir impactos ambientales negativos significativos se clasifican en la Categoría ________.', correct: ['III', 'Tres'] },
                { id: '9-24', question: 'La Evaluación Ambiental ________ (EAE) es el proceso destinado a internalizar la variable ambiental en las propuestas de políticas, planes y programas del Estado.', correct: ['Estratégica'] },
                { id: '9-25', question: 'El organismo rector y administrador del Sistema Nacional de Evaluación de Impacto Ambiental (SEIA) es el ________.', correct: ['MINAM', 'Ministerio del Ambiente'] },
                { id: '9-26', question: 'El organismo responsable de la fiscalización ambiental que revisa el cumplimiento de las obligaciones del estudio ambiental y que puede aplicar sanciones es el ________.', correct: ['OEFA'] },
                { id: '9-27', question: 'Los proyectos clasificados en la Categoría II requieren la elaboración de un Estudio de Impacto Ambiental ________ (EIA-sd).', correct: ['Semidetallado'] },
                { id: '9-28', question: 'Todo estudio ambiental debe ser elaborado únicamente por entidades o consultoras que se encuentren inscritas en el ________ de Entidades Autorizadas administrado por el MINAM.', correct: ['Registro'] },
                { id: '9-29', question: 'Los proyectos de inversión que impliquen reasentamientos, desplazamientos o reubicación de poblaciones serán clasificados obligatoriamente como Categoría ________.', correct: ['III', 'Tres'] },
                { id: '9-30', question: 'La Evaluación ________ es el documento inicial donde el titular presenta las características de la acción y los posibles impactos para sustentar su propuesta de clasificación.', correct: ['Preliminar'] },
                { id: '9-31', question: 'Si un proyecto pierde la vigencia de su Certificación Ambiental por no iniciar obras en el plazo establecido, el titular deberá tramitar una ________ Certificación Ambiental.', correct: ['Nueva'] },
                { id: '9-32', question: 'La ________ económica del impacto ambiental debe considerar el daño generado, el costo de mitigación, control, remediación o compensación, según el Reglamento del SEIA.', correct: ['Valorización', 'Valorizacion'] },
                { id: '9-33', question: 'Los impactos ________ son el efecto ambiental producido como consecuencia de varias acciones, cuya incidencia final es mayor a la suma de los impactos parciales individuales.', correct: ['Sinérgicos', 'Sinergicos'] },
                { id: '9-34', question: 'Para garantizar una relación armoniosa con la población, los Estudios de Impacto Ambiental (Categoría II y III) deben incluir un Plan de Participación ________.', correct: ['Ciudadana'] },
                { id: '9-35', question: 'El proceso de evaluación de un Estudio de Impacto Ambiental Detallado (EIA-d) se lleva a cabo en un plazo máximo de ________ días hábiles, según el Art. 52 del Reglamento.', correct: ['120', 'ciento veinte'] },
                { id: '9-36', question: 'Dentro de los ________ días hábiles posteriores al inicio de las obras del proyecto, el titular debe comunicar el hecho a la Autoridad Competente y a las autoridades de fiscalización.', correct: ['30', 'treinta'] },
                { id: '9-37', question: 'Las medidas para la gestión de riesgos y respuesta a los eventuales accidentes que afecten la salud o el ambiente deben estar descritas en el Plan de ________ dentro de la Estrategia de Manejo Ambiental.', correct: ['Contingencias'] },
                { id: '9-38', question: 'Toda la documentación presentada en el marco del SEIA, al estar suscrita por los profesionales y el titular, tiene carácter de declaración ________ para todos sus efectos legales.', correct: ['Jurada'] },
                { id: '9-39', question: 'La Certificación Ambiental obliga al titular a cumplir con las medidas para prevenir, controlar, ________, rehabilitar y compensar los impactos ambientales negativos.', correct: ['Mitigar'] },
                { id: '9-40', question: 'Las Autoridades Competentes no pueden otorgar la Certificación Ambiental de un proyecto de forma parcial, fraccionada, provisional o ________ bajo sanción de nulidad.', correct: ['Condicionada'] }
            ]
        },
        10: {
            title: 'SEIA y Criterios Ambientales',
            multiple: [
                { id: '10-1', question: '¿Con qué instrumento legal se creó el Sistema Nacional de Evaluación de Impacto Ambiental (SEIA) en el año 2001?', options: ['A) Ley N° 28611', 'B) Ley N° 27446', 'C) Decreto Supremo N° 019-2009-MINAM', 'D) Ley N° 29763'], correct: 'B' },
                { id: '10-2', question: 'De acuerdo con el Reglamento del SEIA, ¿qué instrumento evalúa las Políticas, Planes y Programas del Estado?', options: ['A) DIA', 'B) EIA-d', 'C) EAE (Evaluación Ambiental Estratégica)', 'D) PAMA'], correct: 'C' },
                { id: '10-3', question: '¿A qué categoría del SEIA corresponden los proyectos de inversión cuyos impactos ambientales negativos se prevén como "leves"?', options: ['A) Categoría I', 'B) Categoría II', 'C) Categoría III', 'D) Categoría IV'], correct: 'A' },
                { id: '10-4', question: '¿Qué significa ECA en el contexto de la calidad ambiental?', options: ['A) Evaluación de Criterios Ambientales', 'B) Estándares de Calidad Ambiental', 'C) Entidad de Control Ambiental', 'D) Emisiones Contaminantes Aprobadas'], correct: 'B' },
                { id: '10-5', question: 'A diferencia de los ECA, ¿dónde se miden y aplican directamente los Límites Máximos Permisibles (LMP)?', options: ['A) En el cuerpo receptor (río, lago, aire)', 'B) En el punto de vertimiento o emisión', 'C) En el área de amortiguamiento de las ANP', 'D) En las zonas arqueológicas exclusivamente'], correct: 'B' },
                { id: '10-6', question: 'Según el flujograma del procedimiento (Art. 6), ¿qué etapa sigue a la "Solicitud" y precede a la "Evaluación"?', options: ['A) Seguimiento', 'B) Resolución', 'C) Participación Ciudadana', 'D) Clasificación'], correct: 'D' },
                { id: '10-7', question: '¿En qué caso un proyecto debe pasar obligatoriamente por el SENACE en lugar de la autoridad sectorial?', options: ['A) Cuando el proyecto es pequeño.', 'B) Cuando el proyecto afecta Áreas Naturales Protegidas.', 'C) Cuando el proyecto es de infraestructura vial.', 'D) Cuando el proyecto es de saneamiento rural.'], correct: 'B' },
                { id: '10-8', question: '¿Qué entidad es responsable de la fiscalización ambiental en el Perú?', options: ['A) OEFA', 'B) SENACE', 'C) MINAM', 'D) SERNANP'], correct: 'A' },
                { id: '10-9', question: 'Según la Ley N° 28611, ¿cuál de los siguientes NO es un instrumento de gestión ambiental obligatorio mencionado?', options: ['A) Estudio de Impacto Ambiental (EIA)', 'B) Declaración de Impacto Ambiental (DIA)', 'C) Programa de Adecuación y Manejo Ambiental (PAMA)', 'D) Certificado de Propiedad Intelectual (CPI)'], correct: 'D' },
                { id: '10-10', question: 'En relación a la protección del Patrimonio Cultural (MINCUL), ¿qué documento deben obtener los titulares de proyectos de manera previa?', options: ['A) Certificación de Inexistencia de Restos Arqueológicos (CIRA)', 'B) Licencia Social de Operación (LSO)', 'C) Autorización de Vertimientos de Aguas Residuales', 'D) Estándar de Calidad Cultural (ECC)'], correct: 'A' },
                { id: '10-11', question: '¿Qué entidad es competente para aprobar un DIA (Categoría I) de una infraestructura de residuos sólidos de gestión municipal que abarca dos o más regiones?', options: ['A) MINAM (Dirección General de Gestión de Residuos Sólidos)', 'B) SENACE', 'C) Municipalidad Provincial', 'D) Gobierno Regional'], correct: 'A' },
                { id: '10-12', question: '¿Qué decreto supremo actualizado rige los Estándares de Calidad Ambiental (ECA) para Aire desde el año 2023?', options: ['A) D.S. N° 004-2017-MINAM', 'B) D.S. N° 011-2017-MINAM', 'C) D.S. N° 011-2023-MINAM', 'D) D.S. N° 019-2009-MINAM'], correct: 'C' },
                { id: '10-13', question: 'De acuerdo al Artículo 3° sobre la Certificación Ambiental, ninguna autoridad sectorial o local puede:', options: ['A) Exigir pagos tributarios a las empresas.', 'B) Autorizar o permitir obras sin la Resolución de Certificación expedida.', 'C) Realizar monitoreos ambientales sin la presencia del titular.', 'D) Emitir multas a empresas con DIA.'], correct: 'B' },
                { id: '10-14', question: '¿Qué tipo de proyectos requieren un Estudio de Impacto Ambiental Detallado (EIA-d) según la Categoría III?', options: ['A) Proyectos con impactos leves.', 'B) Proyectos con impactos moderados.', 'C) Proyectos con impactos negativos significativos.', 'D) Proyectos en curso sin estudios ambientales previos.'], correct: 'C' },
                { id: '10-15', question: 'Para proyectos que impliquen el aprovechamiento o afectación de ecosistemas forestales o de fauna silvestre, se requiere la opinión técnica previa de:', options: ['A) La Autoridad Nacional del Agua (ANA)', 'B) El Ministerio de Salud (MINSA)', 'C) SERFOR o las Autoridades Regionales Forestales', 'D) El Ministerio de Educación (MINEDU)'], correct: 'C' },
                { id: '10-16', question: 'El Artículo 5° establece Criterios de Protección. Entre ellos se encuentra la "Salud de las Personas". ¿Qué otro criterio pertenece a esta lista?', options: ['A) Protección del presupuesto nacional.', 'B) Incremento de las exportaciones.', 'C) Mantenimiento de los estándares de aire, agua, suelo y ruido (Calidad Ambiental).', 'D) Facilitar la obtención de financiamiento internacional.'], correct: 'C' },
                { id: '10-17', question: 'La aplicación de la normativa ECA y LMP es obligatoria en los IGA en el marco del:', options: ['A) Código Penal', 'B) Sistema Nacional de Evaluación de Impacto Ambiental (SEIA)', 'C) Sistema Nacional de Recursos Hídricos', 'D) Acuerdo de Escazú'], correct: 'B' },
                { id: '10-18', question: 'En la matriz de instrumentos del SEIA, ¿qué exige un EIA-d a diferencia de un DIA?', options: ['A) Aprobación directa sin mayor revisión.', 'B) Análisis profundo, valoración económica y consulta pública amplia.', 'C) Estrategia de manejo sin mitigación.', 'D) Solo la opinión del gobierno local.'], correct: 'B' },
                { id: '10-19', question: 'El ente encargado de emitir opinión técnica vinculante cuando los estudios de impacto ambiental involucran fuentes naturales de agua es:', options: ['A) ANA (Autoridad Nacional del Agua)', 'B) OEFA', 'C) MINCUL', 'D) SERNANP'], correct: 'A' },
                { id: '10-20', question: 'Según la Constitución (Art. 66), ¿quién es el propietario de los recursos naturales, renovables y no renovables?', options: ['A) Las empresas transnacionales', 'B) Las municipalidades', 'C) La Nación', 'D) El Ministerio del Ambiente'], correct: 'C' }
            ],
            fill: [
                { id: '10-21', question: 'La Constitución Política del Perú, en su artículo 2°, inciso 22, señala que toda persona tiene derecho a gozar de un ambiente ________ y adecuado para el desarrollo de su vida.', correct: ['equilibrado'] },
                { id: '10-22', question: 'El SEIA se define como un sistema ________ y coordinado de identificación y prevención de impactos ambientales.', correct: ['único', 'unico'] },
                { id: '10-23', question: 'La Estrategia de Manejo Ambiental se compone de cuatro grandes acciones: Prevención, Minimización, Rehabilitación y ________.', correct: ['Compensación', 'Compensacion'] },
                { id: '10-24', question: 'Ningún proyecto de inversión pública, privada o mixta puede iniciar su ejecución sin contar previamente con la ________ Ambiental.', correct: ['Certificación', 'Certificacion'] },
                { id: '10-25', question: 'La Categoría II corresponde a impactos moderados y requiere la presentación de un Estudio de Impacto Ambiental ________ (EIA-sd).', correct: ['Semidetallado'] },
                { id: '10-26', question: 'Los niveles de Categorías I, II y III se clasifican por su nivel de impactos ambientales, los cuales pueden ser leves, moderados o ________ (o altos).', correct: ['significativos'] },
                { id: '10-27', question: 'El Artículo 5° de los Criterios de Protección Ambiental tutela explícitamente las Áreas Naturales ________ (ANP) y los ecosistemas frágiles.', correct: ['Protegidas'] },
                { id: '10-28', question: 'En la Etapa 4 del Flujograma de Procedimientos del SEIA, la autoridad realiza la ________ que corresponde a la emisión de la Certificación Ambiental (aprobatorio o desaprobatorio).', correct: ['Resolución', 'Resolucion'] },
                { id: '10-29', question: 'El ________ es el ente que evalúa y aprueba los Estudios Ambientales categorías II y III para infraestructuras de residuos sólidos a nivel nacional en ciertos casos.', correct: ['SENACE'] },
                { id: '10-30', question: 'Un ________ de Impacto Ambiental es el documento de gestión que contiene la descripción del proyecto y el análisis de los efectos directos o indirectos previsibles de dicha actividad.', correct: ['Estudio'] },
                { id: '10-31', question: 'Las siglas LMP se refieren a los Límites ________ Permisibles aplicables a efluentes y emisiones.', correct: ['Máximos', 'Maximos'] },
                { id: '10-32', question: 'La aplicación de los ECA (Estándares de Calidad Ambiental) se realiza de forma directa en los cuerpos ________ (aire, agua, suelo).', correct: ['receptores'] },
                { id: '10-33', question: 'Para obtener el CIRA, el titular interactúa con el Ministerio de ________, el cual emite opinión técnica vinculante sobre el patrimonio de la Nación.', correct: ['Cultura'] },
                { id: '10-34', question: 'El Decreto Supremo N° 004-2017-MINAM regula específicamente los Estándares de Calidad Ambiental (ECA) para ________.', correct: ['Agua'] },
                { id: '10-35', question: 'La Evaluación Ambiental Estratégica (EAE) está diseñada no para proyectos específicos, sino para evaluar ________, Planes y Programas del gobierno.', correct: ['Políticas', 'Politicas'] },
                { id: '10-36', question: 'Las municipalidades provinciales evalúan las infraestructuras de residuos de gestión municipal cuando el servicio se brinda a uno o más ________ dentro de su jurisdicción.', correct: ['distritos'] },
                { id: '10-37', question: 'El Decreto Supremo N° 011-2017-MINAM es el cuerpo legal que establece los ECA para ________.', correct: ['Suelo'] },
                { id: '10-38', question: 'Si la evaluación prevé la generación de impactos ambientales negativos leves, se asigna la Categoría I, por lo cual se elaborará una ________ (DIA).', correct: ['Declaración de Impacto Ambiental'] },
                { id: '10-39', question: 'Durante la Etapa 1 (Solicitud), el titular del proyecto realiza la presentación de la evaluación ________ para iniciar el trámite.', correct: ['preliminar'] },
                { id: '10-40', question: 'El Artículo 5° exige la protección prioritaria de la vida humana y la ________ de vida de las poblaciones locales.', correct: ['calidad'] }
            ]
        },
        11: {
            title: 'Instrumentos de Gestión Ambiental',
            multiple: [
                { id: '11-1', question: 'De acuerdo a la Ley General del Ambiente (Ley N° 28611), ¿qué instrumento fija la concentración máxima permitida de sustancias sin representar riesgo para la salud o el ecosistema?', options: ['A) Estudio de Impacto Ambiental (EIA)', 'B) Estándar de Calidad Ambiental (ECA)', 'C) Plan de Adecuación y Manejo Ambiental (PAMA)', 'D) Declaración de Impacto Ambiental (DIA)'], correct: 'B' },
                { id: '11-2', question: '¿Cuál es el principal objetivo del Sistema Nacional de Evaluación del Impacto Ambiental (SEIA)?', options: ['A) Sancionar económicamente a las empresas infractoras.', 'B) Promover exclusivamente la inversión minera.', 'C) Identificar, prevenir, mitigar y compensar los impactos ambientales significativos.', 'D) Reemplazar la legislación laboral.'], correct: 'C' },
                { id: '11-3', question: '¿Qué instrumento preventivo se aplica a proyectos cuya ejecución no genera impactos ambientales negativos significativos (Categoría I)?', options: ['A) EIA-d', 'B) DIA', 'C) EIA-sd', 'D) IGAC'], correct: 'B' },
                { id: '11-4', question: '¿A qué categoría corresponden los proyectos cuyos impactos negativos son moderados y mitigables con tecnología conocida?', options: ['A) Categoría I', 'B) Categoría II', 'C) Categoría III', 'D) Categoría IV'], correct: 'B' },
                { id: '11-5', question: 'En el Perú, ¿qué institución es la autoridad evaluadora encargada de aprobar los Estudios de Impacto Ambiental Detallados (EIA-d)?', options: ['A) El MINSA', 'B) El Congreso de la República', 'C) El SENACE', 'D) La SUNAT'], correct: 'C' },
                { id: '11-6', question: 'Históricamente, ¿qué país latinoamericano fue el pionero al incorporar la evaluación de impacto ambiental en su Código de Recursos Naturales en 1973?', options: ['A) Perú', 'B) Brasil', 'C) Colombia', 'D) Chile'], correct: 'C' },
                { id: '11-7', question: 'La Evaluación Ambiental es un proceso administrativo integral. En contraste, ¿qué es el Estudio de Impacto Ambiental (EIA)?', options: ['A) Una ley aprobada por el congreso.', 'B) Un documento técnico específico y componente técnico dentro de la evaluación.', 'C) Un impuesto a las emisiones de carbono.', 'D) Una medida exclusiva de remediación de suelos.'], correct: 'B' },
                { id: '11-8', question: '¿Qué es la "Certificación Ambiental"?', options: ['A) Un premio otorgado a empresas por plantar árboles.', 'B) Una sanción monetaria del Estado.', 'C) El acto administrativo por el cual la autoridad aprueba el instrumento de gestión ambiental de un proyecto.', 'D) Un certificado ISO voluntario que no requiere ley.'], correct: 'C' },
                { id: '11-9', question: '¿Cuál de los siguientes es un Instrumento Complementario o Correctivo (para actividades en curso)?', options: ['A) DIA', 'B) PAMA', 'C) EIA-d', 'D) EIA-sd'], correct: 'B' },
                { id: '11-10', question: 'El IGAC (Instrumento de Gestión Ambiental Correctivo) se aplica principalmente a:', options: ['A) Proyectos de exploración petrolera en selva.', 'B) Pequeña minería y minería artesanal.', 'C) Construcción de hospitales nivel III.', 'D) Vuelos aerocomerciales.'], correct: 'B' },
                { id: '11-11', question: 'Según el Reglamento de Protección y Gestión Ambiental en Perú, el D.S. N° 004-2017-MTC regula las actividades del sector:', options: ['A) Agricultura y Riego', 'B) Pesca y Acuicultura', 'C) Transportes', 'D) Comunicaciones'], correct: 'C' },
                { id: '11-12', question: '¿Qué significa la sigla NEPA en el contexto del origen histórico de la EIA en Estados Unidos (1970)?', options: ['A) Normativa Estatal para la Protección Agrícola', 'B) National Environmental Policy Act', 'C) Natural Ecosystem Preservation Agency', 'D) National Evaluation of Public Assets'], correct: 'B' },
                { id: '11-13', question: '¿Cuál es el plazo máximo que tiene la autoridad para evaluar un IGAPRO?', options: ['A) 120 días hábiles', 'B) 15 días calendario', 'C) 30 días hábiles', 'D) 6 meses'], correct: 'C' },
                { id: '11-14', question: '¿Qué es un "Aspecto Ambiental"?', options: ['A) La alteración irreversible del clima local.', 'B) Elementos de las actividades, obras o servicios que pueden interactuar con el medio ambiente.', 'C) La opinión de las ONGs sobre un proyecto minero.', 'D) La compensación económica entregada a la comunidad.'], correct: 'B' },
                { id: '11-15', question: 'Según el SEIA, ¿quién es el responsable directo de elaborar y presentar los estudios ambientales?', options: ['A) La Ciudadanía', 'B) La Autoridad Competente', 'C) El Titular del proyecto', 'D) Las ONGs'], correct: 'C' },
                { id: '11-16', question: 'El Plan Ambiental Detallado (PAD) tiene naturaleza correctiva y está dirigido a titulares que:', options: ['A) Aún no tienen un terreno comprado para su proyecto.', 'B) Vienen realizando actividades sin contar con un IGA aprobado o realizaron ampliaciones sin tramitarlo.', 'C) Buscan ganar una licitación internacional de energía eólica.', 'D) Tienen una Categoría I (DIA) aprobada sin observaciones.'], correct: 'B' },
                { id: '11-17', question: '¿A qué se refiere el principio de evaluación entre el escenario "con proyecto" y "sin proyecto"?', options: ['A) A medir económicamente si el proyecto es rentable.', 'B) A la lógica propuesta por Conesa para medir la alteración ambiental que causa el proyecto.', 'C) A la decisión de la ciudadanía de aceptar o rechazar la obra.', 'D) Al cálculo de impuestos a pagar al Estado.'], correct: 'B' },
                { id: '11-18', question: '¿En qué año se promulgó el Código del Medio Ambiente en el Perú (D.L. N° 613)?', options: ['A) 1990', 'B) 2001', 'C) 2005', 'D) 2012'], correct: 'A' },
                { id: '11-19', question: 'El EIA de Categoría III (EIA-d) exige un plan de manejo ambiental integral y además un robusto proceso de participación ciudadana que incluye:', options: ['A) La votación nacional vinculante de toda la población.', 'B) Audiencias públicas obligatorias.', 'C) Cierre inmediato de las vías de comunicación.', 'D) Revisión por organismos internacionales exclusivamente.'], correct: 'B' },
                { id: '11-20', question: '¿Qué anexo del Reglamento de la Ley del SEIA contiene el listado de inclusión de los Proyectos de Inversión sujetos a dicho sistema?', options: ['A) Anexo I', 'B) Anexo II', 'C) Anexo V', 'D) Anexo X'], correct: 'B' }
            ],
            fill: [
                { id: '11-21', question: 'Un modelo de desarrollo no puede estar ________ de lo ambiental.', correct: ['desvinculado'] },
                { id: '11-22', question: 'En el marco legal peruano, la Ley de creación del Sistema Nacional de Evaluación del Impacto Ambiental (SEIA) es la Ley N° ________ promulgada en el año 2001.', correct: ['27446'] },
                { id: '11-23', question: 'Los proyectos con impactos ambientales negativos significativos que pueden ser irreversibles se clasifican en la Categoría ________ y requieren un EIA-d.', correct: ['III', 'Tres'] },
                { id: '11-24', question: 'Un aspecto ambiental es el elemento que interactúa con el entorno (la causa), mientras que el ________ ambiental corresponde a la alteración positiva o negativa generada (el efecto).', correct: ['impacto'] },
                { id: '11-25', question: 'La autoridad competente evalúa y aprueba un IGA; en el caso de los proyectos de gran envergadura (Categoría III), esta entidad técnica adscrita al MINAM es el ________.', correct: ['SENACE'] },
                { id: '11-26', question: 'El PAMA significa ________ de Adecuación y Manejo Ambiental.', correct: ['Programa'] },
                { id: '11-27', question: 'El artículo 17 de la Ley General del Ambiente clasifica a los instrumentos de gestión en preventivos, de control, económicos y de participación: correctivos.', correct: ['correctivos'] },
                { id: '11-28', question: 'El IGAPRO fue diseñado específicamente para intervenciones de construcción orientadas a la prevención de daños originados por ________ naturales.', correct: ['desastres'] },
                { id: '11-29', question: 'La categorización por riesgo ambiental del proyecto se realiza aplicando los criterios de protección previstos en el Anexo ________ del Reglamento de la Ley del SEIA.', correct: ['V', 'Cinco'] },
                { id: '11-30', question: 'En la línea de tiempo de Latinoamérica, se reconoce a ________ como el país pionero en incorporar la EIA al modificar su Código de Recursos Naturales en 1973.', correct: ['Colombia'] },
                { id: '11-31', question: 'Todo IGA responde a una lógica metodológica para medir la alteración comparando el escenario "________ proyecto" frente al escenario "sin proyecto".', correct: ['con'] },
                { id: '11-32', question: 'La ________ Ambiental es el acto administrativo obligatorio y de carácter previo por el cual la autoridad aprueba el DIA, EIA-sd o EIA-d.', correct: ['Certificación', 'Certificacion'] },
                { id: '11-33', question: 'Según la estructura del cronograma presupuestado del Plan de Manejo Ambiental, se identifican las medidas preventivas, de mitigación, y el plan de ________ ambiental temporal e informativo.', correct: ['señalización', 'senalizacion'] },
                { id: '11-34', question: 'La EIA-d exige el uso de metodologías rigurosas de evaluación. Una de las más mencionadas para valorar impactos es la Matriz de Importancia de ________.', correct: ['Conesa'] },
                { id: '11-35', question: 'Los Estándares de Calidad Ambiental (ECA) fijan la ________ máxima permitida de sustancias en el ambiente receptor.', correct: ['concentración', 'concentracion'] },
                { id: '11-36', question: 'El Ministerio del ________ (MINAM) fue creado en Perú mediante el D.L. 1013 en el año 2008.', correct: ['Ambiente'] },
                { id: '11-37', question: 'El PAD es el ________ Ambiental Detallado, que aplica a actividades en curso sin un IGA aprobado.', correct: ['Plan'] },
                { id: '11-38', question: 'Las siglas DIA, correspondientes al instrumento preventivo de la Categoría I, significan ________ de Impacto Ambiental.', correct: ['Declaración', 'Declaracion'] },
                { id: '11-39', question: 'Los Instrumentos ________ a diferencia de los preventivos, se aplican cuando la actividad económica o productiva ya está en marcha.', correct: ['Correctivos', 'Complementarios'] },
                { id: '11-40', question: 'El Reglamento de protección ambiental para las actividades de Electricidad está normado bajo el D.S. N° 014-2019-________.', correct: ['EM'] }
            ]
        },
        12: {
            title: 'EIA y EAE en la Región Amazónica',
            multiple: [
                { id: '12-1', question: 'Según el informe, ¿cuál es la diferencia principal entre una EIA (Evaluación de Impacto Ambiental) y una EAE (Evaluación Ambiental Estratégica)?', options: ['A) La EIA es voluntaria, la EAE es estrictamente obligatoria y penalizada.', 'B) La EIA evalúa proyectos específicos, mientras que la EAE se aplica a políticas, planes y programas.', 'C) La EIA se aplica solo al sector privado y la EAE al sector público.', 'D) No existe diferencia técnica, solo cambian de nombre según el país.'], correct: 'B' },
                { id: '12-2', question: 'En Brasil, ¿qué organismo estatal tiene la obligación de manifestarse sobre los componentes indígenas en todos los procesos de licenciamiento ambiental?', options: ['A) IBAMA', 'B) Ministerio de Cultura', 'C) FUNAI (Fundación Nacional del Indio)', 'D) ANLA'], correct: 'C' },
                { id: '12-3', question: 'El caso de estudio hidroeléctrico analizado en Brasil, que forma parte del Complejo Teles Pires, es:', options: ['A) UHE Belo Monte', 'B) UHE São Manoel', 'C) UHE Jirau', 'D) UHE Santo Antônio'], correct: 'B' },
                { id: '12-4', question: 'De acuerdo con el análisis de los casos, ¿en qué etapa de los grandes proyectos suelen tomarse las decisiones clave de inversión, usualmente sin consultar a las poblaciones?', options: ['A) En la fase de construcción.', 'B) Durante las audiencias públicas del EsIA.', 'C) En las fases de preinversión y estudios conceptuales.', 'D) En la etapa de abandono y cierre.'], correct: 'C' },
                { id: '12-5', question: '¿Qué autoridad nacional en Colombia es responsable de otorgar licencias ambientales para la exploración y explotación de hidrocarburos?', options: ['A) SENACE', 'B) ANLA (Autoridad Nacional de Licencias Ambientales)', 'C) IBAMA', 'D) FUNAI'], correct: 'B' },
                { id: '12-6', question: 'Según el documento, ¿cuál es el componente frecuentemente subestimado en los EsIA que tiene impacto directo sobre las comunidades?', options: ['A) La salud pública de la población humana.', 'B) La geología del terreno.', 'C) La hidrología superficial.', 'D) La calidad del aire.'], correct: 'A' },
                { id: '12-7', question: 'El Proyecto Hidrovía Amazónica (Perú) contempla obras de dragado en zonas específicas para mantener la navegabilidad. ¿Cómo se conocen localmente estas zonas críticas?', options: ['A) Áreas de reserva', 'B) Malos pasos', 'C) Zonas de sacrificio', 'D) Quirumas'], correct: 'B' },
                { id: '12-8', question: 'En el caso del Bloque PUT-12 en Colombia, operado recientemente por Geopark, el informe destaca violaciones previas a los derechos del pueblo indígena:', options: ['A) Achuar', 'B) Kayabi', 'C) Siona', 'D) Wampis'], correct: 'C' },
                { id: '12-9', question: '¿Cuál de los siguientes es el Tratado Internacional clave de la OIT que exige la consulta previa, libre e informada?', options: ['A) Convenio 169', 'B) Protocolo de Kioto', 'C) Acuerdo de Escazú', 'D) Declaración de Río'], correct: 'A' },
                { id: '12-10', question: 'El estudio de DAR sobre el Lote 8 en el Perú resalta que la empresa operadora inició un proceso de liquidación evadiendo responsabilidades de remediación. ¿Qué empresa operaba este lote?', options: ['A) Gran Tierra Energy', 'B) Pluspetrol Norte (PPN)', 'C) Amerisur Exploration', 'D) Cohidro S.A.'], correct: 'B' },
                { id: '12-11', question: 'A pesar del derecho a la consulta previa, las normativas de Brasil, Colombia y Perú coinciden en una gran limitación para los pueblos indígenas, que es:', options: ['A) Solo las comunidades tituladas tienen derecho a asistir.', 'B) Los pueblos indígenas no tienen derecho a veto sobre las actividades u obras.', 'C) Las consultas solo se realizan en idioma español o portugués.', 'D) Las empresas deciden qué comunidades consultarán sin intervención del Estado.'], correct: 'B' },
                { id: '12-12', question: 'Según las mejores prácticas, ¿qué son los Términos de Referencia (TdR) en el contexto de una EIA?', options: ['A) El resumen del presupuesto financiero de la obra.', 'B) El documento que dicta la sentencia de aprobación o rechazo del proyecto.', 'C) La guía que define el contenido, el método y el alcance del Estudio de Impacto Ambiental.', 'D) La constancia de haber finalizado la consulta previa.'], correct: 'C' },
                { id: '12-13', question: 'En el análisis del sector transporte en Perú, ¿qué proyecto vial se observó que fue declarado de "necesidad pública" sin tener estudios ambientales detallados ni consulta previa?', options: ['A) Carretera Transamazónica', 'B) Carretera Iquitos-Saramiriza', 'C) Carretera Interoceánica Sur', 'D) Carretera Central'], correct: 'B' },
                { id: '12-14', question: '¿Qué es un problema recurrente en la determinación de las Áreas de Influencia Directa e Indirecta en los EsIA, según los casos de estudio?', options: ['A) Son demasiado extensas y encarecen el estudio.', 'B) Se basan en delimitaciones legales o franjas arbitrarias, excluyendo zonas de uso tradicional y comunidades enteras.', 'C) Siempre requieren la aprobación de la Corte Suprema de Justicia.', 'D) Se basan exclusivamente en el conocimiento indígena ancestral, ignorando la ingeniería.'], correct: 'B' },
                { id: '12-15', question: 'En el Perú, ¿cuál es la única experiencia de EAE (Evaluación Ambiental Estratégica) aplicada a una propuesta de desarrollo regional y multisectorial que se analiza en el documento?', options: ['A) EAE del Corredor Vial Interoceánico Sur', 'B) EAE del Plan Indicativo de Abastecimiento', 'C) EAE del Plan de Desarrollo Regional Concertado (PDRC) de Loreto al 2021', 'D) EAE del Arco Noroccidental Amazónico'], correct: 'C' },
                { id: '12-16', question: 'Una deficiencia técnica de los EsIA en la Amazonía es que limitan la predicción de impactos a un solo escenario. El documento recomienda que los análisis sean:', options: ['A) Cuantitativos exclusivamente', 'B) Multitemporales (que analicen los cambios a lo largo del tiempo)', 'C) Financieramente viables antes que ambientales', 'D) Realizados únicamente por entidades extranjeras'], correct: 'B' },
                { id: '12-17', question: '¿Qué papel juegan las empresas consultoras en la falta de objetividad de los EsIA?', options: ['A) Son contratadas y financiadas por los mismos proponentes del proyecto, lo que puede influenciar sus resultados a favor de la empresa.', 'B) Están conformadas exclusivamente por funcionarios del Estado.', 'C) Cobran honorarios demasiado bajos, resultando en estudios deficientes.', 'D) Tienen poder de veto sobre la construcción de la obra.'], correct: 'A' },
                { id: '12-18', question: '¿Cómo afecta la reciente normativa conocida como "deslicenciamiento" o flexibilización en Colombia y Perú (ej. los "paquetazos" ambientales)?', options: ['A) Aumentan el presupuesto del Estado para fiscalizar.', 'B) Obligan a paralizar toda actividad extractiva en zonas indígenas.', 'C) Reducen los requisitos y aceleran los procesos administrativos, eximiendo a ciertas actividades de contar con EIA detallados.', 'D) Incrementan los requisitos de consulta previa a la etapa de diseño.'], correct: 'C' },
                { id: '12-19', question: 'Respecto al cumplimiento de los acuerdos de las Consultas Previas:', options: ['A) Son siempre respetados debido a las estrictas sanciones del código penal.', 'B) Existe un vacío legal sobre qué sucede si no se incorporan en su totalidad, lo que suele derivar en incumplimientos.', 'C) Se requiere la aprobación de la ONU para que sean vinculantes.', 'D) Las empresas están obligadas a pagar regalías directas como único acuerdo posible.'], correct: 'B' },
                { id: '12-20', question: 'Según el documento, los mega-proyectos en la Amazonía (transporte y energía) se construyen principalmente impulsados por:', options: ['A) La necesidad de los núcleos infantiles de acceder a la materialidad.', 'B) Demandas del mercado global de materias primas (commodities).', 'C) Políticas de conservación internacional.', 'D) Presiones de las comunidades locales.'], correct: 'B' }
            ],
            fill: [
                { id: '12-21', question: 'La Evaluación Ambiental Estratégica (EAE) es un instrumento diseñado para evaluar las consecuencias socioambientales de un conjunto de Políticas, Planes y ________ gubernamentales.', correct: ['Programas'] },
                { id: '12-22', question: 'En el Perú, la institución encargada de revisar y aprobar los EsIA detallados (EIA-d) para grandes proyectos de inversión es el ________ (siglas).', correct: ['SENACE'] },
                { id: '12-23', question: 'Para justificar el mejoramiento de la navegabilidad, el Proyecto Hidrovía Amazónica plantea realizar labores de ________ en el lecho del río en los conocidos "malos pasos".', correct: ['dragado'] },
                { id: '12-24', question: 'El estudio señala que una limitación estructural grave es que los Estados carecen de una visión integral que evalúe los impactos ________ y sinérgicos de múltiples megaproyectos superpuestos en una misma cuenca.', correct: ['acumulativos'] },
                { id: '12-25', question: 'En Brasil, la sigla IBAMA corresponde al Instituto Brasileño del Medio Ambiente y de los Recursos Naturales ________.', correct: ['Renovables'] },
                { id: '12-26', question: 'El caso de estudio en Brasil evaluó la situación del proyecto hidroeléctrico UHE São Manoel, ubicado sobre el río ________.', correct: ['Teles Pires'] },
                { id: '12-27', question: 'El documento reporta que en muchos procesos de licenciamiento se da más importancia a la formalidad del proceso ________ que al alcance de los objetivos ambientales reales.', correct: ['administrativo', 'burocrático'] },
                { id: '12-28', question: 'En la evaluación técnica de los EsIA, un componente frecuentemente ausente y subestimado que tiene impacto directo sobre las comunidades es el análisis de los efectos en la ________ pública.', correct: ['salud'] },
                { id: '12-29', question: 'El informe denuncia que la participación de los pueblos indígenas ocurre ________ en el proceso de toma de decisiones, cuando los diseños y contratos ya están establecidos.', correct: ['tarde', 'al final', 'posteriormente'] },
                { id: '12-30', question: 'Frente al abandono de las instalaciones y pasivos ambientales en el Lote 8, el OEFA solicitó medidas cautelares contra la empresa ________ Norte (PPN) ante su anuncio de liquidación.', correct: ['Pluspetrol'] },
                { id: '12-31', question: 'El proceso sistemático para evaluar las opciones de un proyecto antes de que se tomen compromisos, en inglés se conoce como screening o ________ ambiental inicial.', correct: ['cribado', 'examen preliminar'] },
                { id: '12-32', question: 'La ley de Consulta Previa se basa internacionalmente en el Convenio ________ de la OIT.', correct: ['169'] },
                { id: '12-33', question: 'En Colombia, el caso de estudio involucró los bloques de exploración operados por Gran Tierra Energy, específicamente el Bloque ________ y el Área Moquetá en el Putumayo.', correct: ['Chaza'] },
                { id: '12-34', question: 'En el análisis del Perú se resalta que el Ministerio de ________ no tiene opinión vinculante en los procesos de EIA, a pesar de ser la entidad rectora para la protección de los pueblos indígenas y su cultura.', correct: ['Cultura'] },
                { id: '12-35', question: 'A menudo, las empresas preparan el EIA utilizando fuentes de información ________ (de gabinete o literatura existente) en lugar de recopilar información de línea base representativa mediante trabajo de campo prolongado.', correct: ['secundarias'] },
                { id: '12-36', question: 'El retiro físico de palos y troncos sumergidos que obstaculizan la navegación en los ríos amazónicos se conoce localmente en Perú como la remoción de ________.', correct: ['quirumas'] },
                { id: '12-37', question: 'La Evaluación Nacional de Brasil indicó que durante el proceso de la hidroeléctrica São Manoel, tanto la FUNAI como el IBAMA sufrieron presiones políticas por parte de la EPE, cuyas siglas significan Empresa de Pesquisa ________.', correct: ['Energética', 'Energetica'] },
                { id: '12-38', question: 'Una recomendación del informe es exigir la creación de fondos de ________ financiera para asegurar que las empresas cubran la mitigación y el cierre de pasivos ambientales.', correct: ['garantía', 'garantia'] },
                { id: '12-39', question: 'Para evadir realizar consultas rigurosas, en muchos casos las empresas y autoridades definen un Área de Influencia ________ demasiado pequeña, excluyendo a muchas comunidades indígenas.', correct: ['directa', 'social directa'] },
                { id: '12-40', question: 'La deforestación, proyectos extractivos y quemas están provocando que la Amazonía esté perdiendo aceleradamente su papel regulador del clima como el sumidero de ________ más grande del mundo.', correct: ['carbono'] }
            ]
        },
        13: {
            title: 'Casos de Área de Estudio, AID y AII',
            multiple: [
                { id: '13-1', question: 'Caso Normativo: Una consultora ambiental va a iniciar la elaboración de la Línea Base de un proyecto vial. ¿Qué normativa reciente debe utilizar como guía obligatoria?', options: ['A) D.S. N° 019-2009-MINAM', 'B) RM N° 00143-2025-MINAM', 'C) Ley N° 27446', 'D) RM N° 28611-2025-MINAM'], correct: 'B' },
                { id: '13-2', question: 'Caso Delimitación Temprana: Un equipo técnico se encuentra en la Etapa 2 del proceso (antes de la evaluación de impactos) y necesita trazar un polígono para salir a levantar información de campo. Este polígono se denomina:', options: ['A) Área de Influencia Directa (AID).', 'B) Área de Influencia Indirecta (AII).', 'C) Área de Estudio (o Área de Actuación).', 'D) Zona de Compensación Ambiental.'], correct: 'C' },
                { id: '13-3', question: 'Caso Diseño de Polígonos: Al trazar el Área de Estudio Ambiental de un proyecto de represa, el especialista en SIG incluye una franja de terreno donde se sabe que NO habrá impactos. Al preguntarle la razón técnica, él responde correctamente que:', options: ['A) Es para justificar un mayor presupuesto de viáticos.', 'B) Ese espacio servirá como "Zona de Control" para comparar.', 'C) Se requiere expropiar más terreno por precaución.', 'D) Así lo exige la municipalidad local.'], correct: 'B' },
                { id: '13-4', question: 'Caso Identificación de Impactos (Aire/Ruido): Durante la construcción de una vía, el ruido de la maquinaria pesada y el polvo generado afectan a las viviendas ubicadas junto al eje de la carretera. Estas viviendas se ubican en:', options: ['A) El Área de Influencia Indirecta (AII).', 'B) La Zona de Control.', 'C) El Área de Emplazamiento.', 'D) El Área de Influencia Directa (AID).'], correct: 'D' },
                { id: '13-5', question: 'Caso Identificación de Impactos (Agua): Una planta de asfalto sufre un derrame que cae a una quebrada. Aunque el derrame ocurre en el cruce de la vía (AID), los sedimentos son arrastrados kilómetros abajo afectando a otras comunidades de la cuenca. La microcuenca afectada se clasifica como:', options: ['A) Área de Influencia Indirecta (AII).', 'B) Área de Influencia Directa (AID).', 'C) Área de Estudio Social.', 'D) Zona de Amelioramiento Ecológico.'], correct: 'A' },
                { id: '13-6', question: 'Caso de Componentes: El área donde se ubicarán los componentes auxiliares del proyecto (campamentos, canteras, DME) y que forma parte del área de estudio, se considera:', options: ['A) El Área de Influencia Directa (AID y AII).', 'B) El Área de Influencia (AID y AII).', 'C) Componentes auxiliares.', 'D) El Área de Emplazamiento.'], correct: 'B' },
                { id: '13-7', question: 'Caso Social: Para delimitar el Área de Estudio Social, el equipo debe mapear el ámbito político-administrativo y las zonas de asentamiento. ¿Qué área de estudio se está delimitando?', options: ['A) Área de Estudio Ambiental.', 'B) Área de Estudio Social.', 'C) Área de Influencia Directa.', 'D) Área de Influencia Indirecta.'], correct: 'B' },
                { id: '13-8', question: 'Caso Componentes Auxiliares: La planta de asfalto, el patio de máquinas y el campamento de obreros no son la vía en sí misma, sino que se categorizan en el proyecto como:', options: ['A) Componentes principales.', 'B) Componentes auxiliares.', 'C) Área de Influencia Directa.', 'D) Área de Estudio Social.'], correct: 'B' },
                { id: '13-9', question: 'Caso Cartografía: Un proyecto de desarrollo abarca un área de estudio total de 3,102 hectáreas. De acuerdo con las recomendaciones de la guía, el especialista en SIG debería generar mapas a una escala de trabajo de:', options: ['A) 1:100 000 a 1:250 000', 'B) 1:1 000 a 1:5 000', 'C) 1:10 000 a 1:25 000', 'D) 1:500 000'], correct: 'C' },
                { id: '13-10', question: 'Caso Control de Calidad: Durante la revisión de un expediente, la autoridad nota que el polígono del Área de Influencia (AI) delineado por la consultora sobresale y es más grande que el polígono del Área de Estudio. Según la norma, ¿es esto correcto?', options: ['A) Sí, porque la influencia del proyecto siempre es incontrolable.', 'B) No, el AI siempre debe ser menor o igual que el Área de Estudio.', 'C) Sí, si los vientos en la zona son muy fuertes.', 'D) No, porque ambos polígonos deben ser idénticos por obligación.'], correct: 'B' },
                { id: '13-11', question: 'Caso Fronteras Naturales: Para delimitar el Área de Estudio Ambiental de una hidroeléctrica, el equipo de hidrología utiliza las divisorias de aguas de la cuenca en lugar de trazar un círculo. ¿Qué criterio técnico de la guía están aplicando?', options: ['A) Ajustar el área a los límites distritales.', 'B) Mapear el alcance del impacto del ruido.', 'C) Ajustar el polígono a fronteras naturales (ríos, cuencas).', 'D) Sumar zonas de compensación poblacional.'], correct: 'C' },
                { id: '13-12', question: 'Caso Flujograma (Paso 1): El gerente del proyecto indica a su equipo que deben compilar la información existente, revisar imágenes satelitales y elaborar un plan de trabajo antes de salir de la oficina. Según el flujograma de la línea base, ¿en qué paso se encuentran?', options: ['A) Paso 1: Planificación de la línea base.', 'B) Paso 2: Trabajo de campo.', 'C) Paso 3: Bases de datos y análisis.', 'D) Paso 5: Interpretación de los datos.'], correct: 'A' },
                { id: '13-13', question: 'Caso Flujograma (Paso 2): Los especialistas viajan a la zona del proyecto para recolectar información primaria, validar las estaciones de muestreo y entrevistar a los informantes clave. Este accionar corresponde al:', options: ['A) Paso 4: Elaboración de mapas temáticos.', 'B) Paso 2: Trabajo de campo.', 'C) Paso 1: Evaluación ambiental preliminar.', 'D) Paso 5: Elaboración de informe.'], correct: 'B' },
                { id: '13-14', question: 'Caso Definición Espacial: El supervisor solicita calcular en metros cuadrados la suma de los espacios que serán ocupados físicamente por la vía, los Depósitos de Material Excedente (DME) y las obras de arte. Este cálculo corresponde a:', options: ['A) El Área de Influencia Indirecta.', 'B) La Zona de Amortiguamiento.', 'C) El Área de Control Biológico.', 'D) El Área de Emplazamiento.'], correct: 'D' },
                { id: '13-15', question: 'Caso Impactos en Población: Al evaluar los impactos sociales del proyecto vial, se determina que los distritos vecinos, aunque no tienen obras físicas en su jurisdicción, se beneficiarán del comercio gracias a la nueva vía. Para el factor "Población", estos distritos se consideran:', options: ['A) Probable Área de Influencia Directa (AID).', 'B) Probable Área de Influencia Indirecta (AII).', 'C) El Ámbito político-administrativo.', 'D) Área de Estudio Social.'], correct: 'B' },
                { id: '13-16', question: 'Caso Social Complementario: Para el Área de Estudio Social, además de las zonas de asentamiento y uso poblacional, se debe incluir:', options: ['A) El área de emplazamiento.', 'B) La zona de control biológico.', 'C) El ámbito político-administrativo.', 'D) El área de influencia indirecta.'], correct: 'C' },
                { id: '13-17', question: 'Caso Componentes (DME): Durante la construcción de la vía, se excavan toneladas de roca que no servirán para rellenar, por lo que se disponen en un botadero autorizado. ¿Con qué siglas se conoce a este componente auxiliar?', options: ['A) AID', 'B) DME', 'C) AII', 'D) TdR'], correct: 'B' },
                { id: '13-18', question: 'Caso Etapas del Proyecto: El estudio ambiental de la carretera de 10 km detalla tres momentos temporales clave de la obra. Estos son:', options: ['A) Planificación, Construcción y Demolición.', 'B) Factibilidad, Viabilidad y Ejecución.', 'C) Construcción, Operación/Mantenimiento y Cierre.', 'D) Línea Base, Scoping y Fiscalización.'], correct: 'C' },
                { id: '13-19', question: 'Caso Impactos Biológicos: Se ha talado una franja de árboles para ampliar el derecho de vía. ¿Cómo se clasifica espacialmente a esta "vegetación removida y bordes de la vía" para el factor Flora y Fauna?', options: ['A) Zona de Control Ambiental.', 'B) Área de Influencia Directa (AID).', 'C) Área de Influencia Indirecta (AII).', 'D) Ámbito Intangible.'], correct: 'B' },
                { id: '13-20', question: 'Caso Redacción Final: En el Paso 5 de la elaboración de la línea base, el redactor debe interpretar la información para dar a conocer al lector la condición actual de los ecosistemas, y además debe incluir obligatoriamente:', options: ['A) El presupuesto financiero de la empresa constructora.', 'B) Las referencias utilizadas (bibliografía).', 'C) Los contratos del personal obrero.', 'D) El estudio de rentabilidad comercial del proyecto.'], correct: 'B' }
            ],
            fill: [
                { id: '13-21', question: 'Caso Normativa: El documento legal que deben usar las consultoras en 2025 para la Línea Base del SEIA es la Guía aprobada mediante la RM N° ________ -2025-MINAM.', correct: ['00143'] },
                { id: '13-22', question: 'Caso Concepto Territorial: El espacio donde se levanta la información primaria ANTES de evaluar los impactos se denomina Área de Estudio, también conocida como área de ________.', correct: ['actuación', 'actuacion', 'levantamiento'] },
                { id: '13-23', question: 'Caso Scoping: El Área de Influencia ________ se define basándose en la potencial extensión de los impactos identificados en la evaluación preliminar (scoping).', correct: ['preliminar'] },
                { id: '13-24', question: 'Caso Metodología Científica: Para asegurar que los impactos de la mina sean evaluables frente a un estado natural no alterado, el Área de Estudio debe contener un espacio adyacente denominado Zona de ________.', correct: ['control'] },
                { id: '13-25', question: 'Caso Secuencia Lógica: El ingeniero no puede delimitar el Área de Influencia final en el Paso 2; debe esperar a la Etapa 6.d, lo que significa que el AI se obtiene como ________ de la evaluación de impactos.', correct: ['resultado'] },
                { id: '13-26', question: 'Caso Antropología: El equipo que delimita el Área de Estudio Social necesita mapear tres componentes: emplazamiento, zonas de asentamiento y el ámbito político-administrativo, además del ________ de la población.', correct: ['uso'] },
                { id: '13-27', question: 'Caso Impacto Hídrico: Un derrame de aceite en el cruce del río genera un impacto directo en ese punto (AID), pero las corrientes arrastran trazas a lo largo de toda la ________, la cual se considera como AII.', correct: ['microcuenca', 'cuenca'] },
                { id: '13-28', question: 'Caso Impacto Social: Los distritos vecinos que se benefician del comercio por la nueva vía, aunque no tengan obras en su jurisdicción, se consideran dentro del Área de Influencia ________.', correct: ['indirecta'] },
                { id: '13-29', question: 'Caso Tipología de Obra: La planta de asfalto, el patio de máquinas y el campamento de obreros no son la vía en sí misma, sino que se categorizan en el proyecto como componentes ________.', correct: ['auxiliares'] },
                { id: '13-30', question: 'Caso Cartografía: Si el Área de Estudio de un proyecto de riego abarca 4,500 ha (menor de 5,000 ha), el especialista debe usar mapas a una escala de trabajo de 1:10 000 a 1: ________.', correct: ['25000', '25 000'] },
                { id: '13-31', question: 'Caso Cálculo Geométrico: La suma exacta de los polígonos que ocupan físicamente todas las instalaciones, vías y estructuras del proyecto conforma el Área de ________.', correct: ['emplazamiento'] },
                { id: '13-32', question: 'Caso Flujograma 1: El equipo técnico valida la ubicación de las estaciones de muestreo y recolecta información in situ. Esto corresponde al Paso 2, denominado Trabajo de ________.', correct: ['campo'] },
                { id: '13-33', question: 'Caso Flujograma 2: Una vez ingresados los datos al SIG (Sistema de Información Geográfica), el Paso 4 exige la elaboración de ________ temáticos finales.', correct: ['mapas'] },
                { id: '13-34', question: 'Caso Impacto Ambiental: Las partículas suspendidas (polvo) generadas por los volquetes en la cantera afectan la calidad del aire de un caserío cercano. Este caserío es catalogado como Probable Área de Influencia ________ de Aire y Ruido.', correct: ['directa'] },
                { id: '13-35', question: 'Caso Criterio de Ajuste: Para evitar polígonos arbitrarios cuadrados, la guía recomienda que el Área de Estudio se ajuste a fronteras ________ como las divisorias de aguas de una cuenca.', correct: ['naturales'] },
                { id: '13-36', question: 'Caso Gestión Social: Con el mapa del Área de Estudio Social terminado, la empresa ya sabe exactamente en qué poblados y comunidades debe realizar el plan de ________ ciudadana.', correct: ['participación', 'participacion'] },
                { id: '13-37', question: 'Caso Regla Espacial: Al superponer los mapas, el polígono del Área de Influencia debe ser matemáticamente menor o ________ que el polígono del Área de Estudio.', correct: ['igual'] },
                { id: '13-38', question: 'Caso Siglas Comunes: Durante el movimiento de tierras, el material inerte que no se usará se depositará en el DME, que significa Depósito de Material ________.', correct: ['excedente'] },
                { id: '13-39', question: 'Caso Flujograma 3: El Paso 3 exige a los analistas realizar la validación y control de calidad de datos, y estructurar las bases de ________ antes de pasarlo al equipo SIG.', correct: ['datos'] },
                { id: '13-40', question: 'Caso Impacto Hídrico: Un derrame de aceite en el cruce del río genera un impacto directo en ese punto (AID), pero las corrientes arrastran trazas a lo largo de toda la microcuenca, la cual se considera como AII.', correct: ['microcuenca', 'cuenca'] }
            ]
        }
    };

    // ======================== CONSTRUCCIÓN DINÁMICA ========================
    const examsContainer = document.getElementById('examsContainer');

    function buildExamHTML(examId, data) {
        const div = document.createElement('div');
        div.className = 'exam-card' + (examId === 1 ? '' : ' hidden');
        div.id = `exam${examId}`;

        let multipleHtml = '';
        data.multiple.forEach(q => {
            let optionsHtml = '';
            q.options.forEach((opt, idx) => {
                const letter = String.fromCharCode(65 + idx);
                optionsHtml += `
                    <label class="option">
                        <input type="radio" name="q${q.id}" value="${letter}">
                        ${opt}
                    </label>
                `;
            });
            multipleHtml += `
                <div class="question-item" id="q-${q.id}">
                    <div class="question-text">${q.id.split('-')[1]}. ${q.question}</div>
                    <div class="options">${optionsHtml}</div>
                    <div class="fill-row">
                        <button class="btn-verify small" data-exam="${examId}" data-qid="${q.id}" data-type="multiple">Verificar</button>
                        <span class="feedback" id="fb-${q.id}"></span>
                    </div>
                    <div class="correct-answer-msg hidden" id="ans-${q.id}"></div>
                </div>
            `;
        });

        let fillHtml = '';
        data.fill.forEach(q => {
            fillHtml += `
                <div class="question-item" id="q-${q.id}">
                    <div class="question-text">${q.id.split('-')[1]}. ${q.question}</div>
                    <div class="fill-row">
                        <input type="text" class="fill-input" id="input-${q.id}" placeholder="Escribe tu respuesta...">
                        <button class="btn-verify small" data-exam="${examId}" data-qid="${q.id}" data-type="fill">Verificar</button>
                        <span class="feedback" id="fb-${q.id}"></span>
                    </div>
                    <div class="correct-answer-msg hidden" id="ans-${q.id}"></div>
                </div>
            `;
        });

        div.innerHTML = `
            <div class="exam-header"><span>${examId}</span> ${data.title}</div>
            <div class="section-title">Parte I: Opción múltiple</div>
            <div id="exam${examId}-multiple">${multipleHtml}</div>
            <div class="section-title">Parte II: Completar espacios</div>
            <div id="exam${examId}-fill">${fillHtml}</div>
            <div class="exam-footer">
                <button class="reset-btn" onclick="resetExam(${examId})">🔄 Reiniciar examen ${examId}</button>
                <div class="nav-exam-btns">
                    <button class="nav-exam-btn" ${examId === 1 ? 'disabled' : `onclick="switchExam(${examId - 1})"`}>◀ Anterior</button>
                    <button class="nav-exam-btn" ${examId === Object.keys(examsData).length ? 'disabled' : `onclick="switchExam(${examId + 1})"`}>Siguiente ▶</button>
                </div>
            </div>
        `;
        return div;
    }

    for (const [id, data] of Object.entries(examsData)) {
        const numId = parseInt(id);
        examsContainer.appendChild(buildExamHTML(numId, data));
    }

    // ======================== VERIFICACIÓN ========================
    function verificarMultiple(examId, qId) {
        const data = examsData[examId];
        const q = data.multiple.find(item => item.id === qId);
        if (!q) return;
        const selected = document.querySelector(`input[name="q${qId}"]:checked`);
        const feedback = document.getElementById(`fb-${qId}`);
        const ansDiv = document.getElementById(`ans-${qId}`);
        const container = document.getElementById(`q-${qId}`);
        if (!selected) {
            feedback.innerHTML = '<span class="cross">❌</span> Selecciona una opción';
            container.classList.remove('correct', 'incorrect');
            container.classList.add('incorrect');
            ansDiv.classList.add('hidden');
            return;
        }
        const isCorrect = selected.value === q.correct;
        if (isCorrect) {
            feedback.innerHTML = '<span class="check">✔️</span> ¡Correcto!';
            container.classList.remove('incorrect');
            container.classList.add('correct');
            ansDiv.classList.add('hidden');
        } else {
            feedback.innerHTML = '<span class="cross">❌</span> Incorrecto';
            container.classList.remove('correct');
            container.classList.add('incorrect');
            const correctOption = q.options.find(opt => opt.startsWith(q.correct + ')'));
            ansDiv.innerHTML = `💡 Respuesta correcta: <strong>${correctOption || q.correct}</strong>`;
            ansDiv.classList.remove('hidden');
        }
    }

    function verificarFill(examId, qId) {
        const data = examsData[examId];
        const q = data.fill.find(item => item.id === qId);
        if (!q) return;
        const input = document.getElementById(`input-${qId}`);
        const feedback = document.getElementById(`fb-${qId}`);
        const ansDiv = document.getElementById(`ans-${qId}`);
        const container = document.getElementById(`q-${qId}`);
        const userValue = input.value.trim().toLowerCase();
        if (!userValue) {
            feedback.innerHTML = '<span class="cross">❌</span> Escribe una respuesta';
            container.classList.remove('correct', 'incorrect');
            container.classList.add('incorrect');
            ansDiv.classList.add('hidden');
            return;
        }
        const normalizedUser = userValue.normalize('NFD').replace(/[\u0300-\u036f]/g, '').replace(/[^a-z0-9 ]/g, '');
        const isCorrect = q.correct.some(correct => {
            const normalizedCorrect = correct.toLowerCase().normalize('NFD').replace(/[\u0300-\u036f]/g, '').replace(/[^a-z0-9 ]/g, '');
            return normalizedUser === normalizedCorrect;
        });
        if (isCorrect) {
            feedback.innerHTML = '<span class="check">✔️</span> ¡Correcto!';
            container.classList.remove('incorrect');
            container.classList.add('correct');
            ansDiv.classList.add('hidden');
        } else {
            feedback.innerHTML = '<span class="cross">❌</span> Incorrecto';
            container.classList.remove('correct');
            container.classList.add('incorrect');
            ansDiv.innerHTML = `💡 Respuesta correcta: <strong>${q.correct[0]}</strong>`;
            ansDiv.classList.remove('hidden');
        }
    }

    // ======================== RESET ========================
    function resetExam(examId) {
        document.querySelectorAll(`#exam${examId} input[type="radio"]`).forEach(radio => {
            radio.checked = false;
        });
        document.querySelectorAll(`#exam${examId} .fill-input`).forEach(input => {
            input.value = '';
        });
        document.querySelectorAll(`#exam${examId} .feedback`).forEach(el => el.innerHTML = '');
        document.querySelectorAll(`#exam${examId} .correct-answer-msg`).forEach(el => {
            el.classList.add('hidden');
            el.innerHTML = '';
        });
        document.querySelectorAll(`#exam${examId} .question-item`).forEach(el => {
            el.classList.remove('correct', 'incorrect');
        });
    }

    // ======================== CAMBIO DE EXAMEN ========================
    function switchExam(examId) {
        for (let i = 1; i <= Object.keys(examsData).length; i++) {
            const card = document.getElementById(`exam${i}`);
            if (card) card.classList.add('hidden');
        }
        const selected = document.getElementById(`exam${examId}`);
        if (selected) selected.classList.remove('hidden');

        document.querySelectorAll('.tab-btn').forEach(btn => {
            btn.classList.toggle('active', parseInt(btn.dataset.exam) === examId);
        });

        selected.scrollIntoView({ behavior: 'smooth', block: 'start' });
    }

    // ======================== EVENTOS ========================
    document.addEventListener('click', function(e) {
        const btn = e.target.closest('.btn-verify');
        if (!btn) return;
        const examId = parseInt(btn.dataset.exam);
        const qId = btn.dataset.qid;
        const type = btn.dataset.type;
        if (type === 'multiple') {
            verificarMultiple(examId, qId);
        } else if (type === 'fill') {
            verificarFill(examId, qId);
        }
    });

    document.querySelectorAll('.tab-btn').forEach(btn => {
        btn.addEventListener('click', function() {
            const examId = parseInt(this.dataset.exam);
            switchExam(examId);
        });
    });

    // Mostrar el examen 1 por defecto
    window.addEventListener('DOMContentLoaded', () => {
        switchExam(1);
    });
</script>
</body>
</html>
