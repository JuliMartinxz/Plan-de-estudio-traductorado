<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Malla Curricular - Traductorado de Inglés</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f4f4f4;
      margin: 0;
      padding: 20px;
      color: #333;
    }
    h1 {
      text-align: center;
      color: #444;
      margin-bottom: 30px;
    }
    .container {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
      max-width: 1200px;
      margin: 0 auto;
    }
    .year {
      background: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 20px;
      width: 260px;
      box-sizing: border-box;
      transition: box-shadow 0.3s ease;
    }
    .year:hover {
      box-shadow: 0 8px 16px rgba(0,0,0,0.15);
    }
    .year h2 {
      text-align: center;
      margin-top: 0;
      color: #2c3e50;
      font-weight: 600;
      border-bottom: 2px solid #4285f4;
      padding-bottom: 8px;
      margin-bottom: 15px;
    }
    .subject {
      background: #d9eaff;
      border-left: 6px solid #4285f4;
      margin: 8px 0;
      padding: 10px 15px;
      border-radius: 6px;
      cursor: default;
      transition: background-color 0.3s ease;
      user-select: none;
    }
    .subject:hover {
      background-color: #b0cfff;
    }
    @media (max-width: 600px) {
      .year {
        width: 100%;
      }
    }
  </style>
</head>
<body>
  <h1>Malla Curricular - Traductorado de Inglés</h1>
  <div class="container">

    <section class="year">
      <h2>Ciclo de Nivelación</h2>
      <div class="subject">Lengua Castellana</div>
      <div class="subject">Lengua Inglesa</div>
    </section>

    <section class="year">
      <h2>1º Año</h2>
      <div class="subject">Lengua Castellana I</div>
      <div class="subject">Lengua Inglesa I</div>
      <div class="subject">Práctica Gramatical del Inglés</div>
      <div class="subject">Práctica de la Pronunciación del Inglés</div>
      <div class="subject">Introducción a la Traductología</div>
    </section>

    <section class="year">
      <h2>2º Año</h2>
      <div class="subject">Lengua Castellana II</div>
      <div class="subject">Lengua Inglesa II</div>
      <div class="subject">Gramática Inglesa I</div>
      <div class="subject">Fonética y Fonología I</div>
      <div class="subject">Métodos y Técnicas de la Traducción</div>
      <div class="subject">Terminología y Documentación</div>
      <div class="subject">Teoría y Práctica de la Investigación</div>
    </section>

    <section class="year">
      <h2>3º Año</h2>
      <div class="subject">Lengua Inglesa III</div>
      <div class="subject">Gramática Inglesa II</div>
      <div class="subject">Fonética y Fonología II</div>
      <div class="subject">Traducción Comercial</div>
      <div class="subject">Traducción Técnica</div>
      <div class="subject">Elementos del Derecho Aplicados a la Traducción</div>
    </section>

    <section class="year">
      <h2>4º Año</h2>
      <div class="subject">Lengua Inglesa IV</div>
      <div class="subject">Lingüística I</div>
      <div class="subject">Cultura y Civilización de los Pueblos de Habla Inglesa I</div>
      <div class="subject">Gramática Contrastiva</div>
      <div class="subject">Traducción Jurídica</div>
      <div class="subject">Introducción a la Literatura de Habla Inglesa I</div>
    </section>

    <section class="year">
      <h2>5º Año</h2>
      <div class="subject">Lengua Inglesa V</div>
      <div class="subject">Lingüística II</div>
      <div class="subject">Cultura y Civilización de los Pueblos de Habla Inglesa II</div>
      <div class="subject">Traducción Científica</div>
      <div class="subject">Traducción Periodística</div>
      <div class="subject">Traducción Literaria</div>
      <div class="subject">Introducción a la Interpretación</div>
    </section>

    <section class="year">
      <h2>Extra</h2>
      <div class="subject">Prueba de Suficiencia</div>
    </section>

  </div>
</body>
</html>
