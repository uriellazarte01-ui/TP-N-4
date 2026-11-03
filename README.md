[index.html](https://github.com/user-attachments/files/34324803/index.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>TP04 - Electricidad Básica</title>
    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            line-height: 1.6;
            max-width: 800px;
            margin: auto;
            padding: 20px;
            color: #333;
        }

/* Estilo de la carátula */
header.caratula {
            text-align: center;
            border: 2px solid #333;
            padding: 40px;
            margin-bottom: 40px;
            background-color: #f9f9f9;
        }

 section {
            margin-bottom: 30px;
            border-bottom: 1px solid #ccc;
            padding-bottom: 20px;
        }

.ohm-triangle {
            text-align: center;
            font-size: 1.5em;
            border: 2px solid #333;
            width: 150px;
            margin: 10px auto;
            padding: 10px;
        }

code {
            background: #f4f4f4;
            padding: 2px 5px;
            border-radius: 4px;
        }
    </style>
 </head>
<body>
<!-- Nueva Carátula -->
    <header class="caratula">
        <h1>Trabajo Práctico N° 04</h1>
        <h2>Electricidad Básica y Aplicada</h2>
        <br>
        <p><strong>Alumnos:</strong> Lazarte uriel y Condori candy</p>
        <p><strong>Materia:</strong> Instalación, Mantenimiento y reparación de redes informáticas</p>
        <p><strong>Profesor:</strong> Gonzalo Ariel Carbajal</p>
        <p><strong>Fecha:</strong> 22 de agosto de 2026</p>
    </header>

<section>
        <h2>1. Instalación de la Puesta a Tierra</h2>
        <p>La puesta a tierra protege a las personas ante fallos de aislamiento desviando la corriente a tierra. Se compone de una pica de cobre enterrada a al menos 50 cm de profundidad.</p>
        <ol>
            <li><strong>Materiales:</strong> Picas de cobre, abrazaderas, cable desnudo de cobre (mín. 25 mm²).</li>
            <li><strong>Instalación:</strong> Se entierra la pica y se conecta al cable conductor de protección (verde/amarillo).</li>
            <li><strong>Distribución:</strong> Este cable se lleva desde el cuadro general hasta cada toma de corriente y carcasa metálica de los aparatos.</li>
        </ol>
    </section>

<section>
        <h2>2. Diccionario Eléctrico</h2>
        <ul>
            <li><strong>Amperio (A):</strong> Unidad de intensidad que circula por un circuito.</li>
            <li><strong>Voltaje (V):</strong> Diferencia de potencial o "presión" eléctrica.</li>
            <li><strong>Resistencia (Ω):</strong> Oposición de un material al paso de la corriente.</li>
            <li><strong>Cortocircuito:</strong> Fallo por contacto accidental de dos conductores de distinta polaridad.</li>
        </ul>
    </section>

 <section>
        <h2>3. Ley de Ohm</h2>
        <p>Establece que la intensidad es directamente proporcional al voltaje e inversamente proporcional a la resistencia: <code>I = V / R</code>.</p>

 <div class="ohm-triangle">
            <div>V</div>
            <div style="border-top: 1px solid #333;">I × R</div>
        </div>

<h3>Ejemplo 1: Circuito Serie</h3>
        <p>Fuente de 10V con dos resistencias en serie: R1 = 2Ω y R2 = 3Ω.</p>
        <ul>
            <li>Resistencia Total (RT) = R1 + R2 = 2Ω + 3Ω = 5Ω</li>
            <li>Intensidad (I) = V / RT = 10V / 5Ω = <strong>2 Amperios</strong></li>
        </ul>

 <h3>Ejemplo 2: Circuito Paralelo</h3>
        <p>Fuente de 10V con dos resistencias en paralelo: R1 = 2Ω y R2 = 2Ω.</p>
        <ul>
            <li>Resistencia Total (1/RT) = 1/R1 + 1/R2 = 1/2 + 1/2 = 1</li>
            <li>RT = 1Ω</li>
            <li>Intensidad (I) = V / RT = 10V / 1Ω = <strong>10 Amperios</strong></li>
        </ul>
        <a href="HTMLpage2.html">TCP - Trabajo Práctico N.º 5</a>
    </section>

</body>
</html>
