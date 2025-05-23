<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Análisis de Pruebas ECOS e IA</title>
  <!-- Bootstrap CSS -->
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    body {
      font-family: "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif;
      line-height: 1.6;
      color: #333;
      padding-top: 2rem;
      padding-bottom: 2rem;
    }
    .header {
      background: linear-gradient(to right, #0062cc, #0097ff);
      color: white;
      padding: 2rem 0;
      margin-bottom: 2rem;
      border-radius: 0.5rem;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }
    h1, h2 {
      font-weight: 700;
    }
    h3 {
      font-weight: 600;
      color: #0062cc;
      margin-top: 1.5rem;
    }
    .section {
      background-color: white;
      border-radius: 0.5rem;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
      padding: 1.5rem;
      margin-bottom: 1.5rem;
    }
    .table-responsive {
      margin-bottom: 1.5rem;
    }
    .table {
      font-size: 0.9rem;
    }
    .img-fluid {
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
      border-radius: 0.25rem;
      margin-bottom: 1.5rem;
    }
    .footer {
      background-color: #f8f9fa;
      padding: 1rem 0;
      text-align: center;
      font-size: 0.85rem;
      color: #6c757d;
      border-radius: 0.5rem;
      margin-top: 2rem;
    }
    .card {
      margin-bottom: 1.5rem;
      border: none;
      box-shadow: 0 2px 4px rgba(0,0,0,0.05);
    }
    .card-header {
      background-color: #0062cc;
      color: white;
      font-weight: 600;
    }
    .table-hover tbody tr:hover {
      background-color: rgba(0,123,255,0.1);
    }
    .nav-tabs {
      margin-bottom: 1rem;
    }
    .nav-tabs .nav-link.active {
      font-weight: 600;
      color: #0062cc;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="header text-center">
      <h1>Análisis Comparativo: Pruebas ECOS e IA</h1>
      <p class="lead">Universidad Iberoamericana | 11 de abril de 2025</p>
    </div>
    
    <div class="row">
      <div class="col-md-12">
        <div class="card">
          <div class="card-header">
            Resumen del Análisis
          </div>
          <div class="card-body">
            <p>Este informe presenta un análisis detallado y comparativo de las aplicaciones a las pruebas ECOS e IA. 
            Se incluyen tablas de frecuencias, porcentajes y análisis cruzados para ambos tipos de pruebas, considerando
            las variables: Status, Carrera, Coordinación, División y Semestre del curso.</p>
            
            <div class="row">
              <div class="col-md-6">
                <div class="alert alert-primary">
                  <strong>Total de pruebas IA:</strong> 594
                </div>
              </div>
              <div class="col-md-6">
                <div class="alert alert-success">
                  <strong>Total de pruebas ECOS:</strong> 609
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Sección 1: Distribución por Tipo de Prueba -->
    <div class="section">
      <h2 class="mb-4">1. Distribución por Tipo de Prueba</h2>
      <div class="row">
        <div class="col-md-6">
          <h3>Distribución General por Tipo de Prueba</h3><div class='table-responsive'><table class='table table-striped table-hover'><thead><tr><th>Categoría</th><th>Frecuencia</th><th>Porcentaje</th></tr></thead><tbody><tr><td>ECOS</td><td>609</td><td>40.2%</td></tr><tr><td>IA</td><td>594</td><td>39.21%</td></tr><tr><td>Sin aplicar</td><td>312</td><td>20.59%</td></tr><tr class='table-active'><td><strong>Total</strong></td><td><strong>1515</strong></td><td><strong>100%</strong></td></tr></tbody></table></div>
        </div>
        <div class="col-md-6">
          <img src="imagenes/grafico_tipo_prueba.png" alt="Gráfico de Tipo de Prueba" class="img-fluid">
        </div>
      </div>
    </div>
    
    <!-- Sección 2: Análisis por División -->
    <div class="section">
      <h2 class="mb-4">2. Análisis por División y Tipo de Prueba</h2>
      <div class="row">
        <div class="col-md-12">
          <h3>Distribución por División y Tipo de Prueba</h3><div class='table-responsive'><table class='table table-striped table-hover'><thead><tr><th></th><th>ECOS</th><th>IA</th><th>Sin aplicar</th><th>Total</th><th>% del total aplicados</th></tr></thead><tbody><tr><td><strong>DIVISIÓN DE CIENCIA, ARTE Y TECNOLOGÍA</strong></td><td>301</td><td>180</td><td>139</td><td><strong>481</strong></td><td><strong>40.02%</strong></td></tr><tr><td><strong>DIVISIÓN DE ESTUDIOS SOCIALES</strong></td><td>211</td><td>362</td><td>154</td><td><strong>573</strong></td><td><strong>47.67%</strong></td></tr><tr><td><strong>DIVISIÓN DE HUMANIDADES Y COMUNICACIÓN</strong></td><td>96</td><td>52</td><td>19</td><td><strong>148</strong></td><td><strong>12.31%</strong></td></tr><tr class='table-active'><td><strong>Total</strong></td><td><strong>608 (50.58%)</strong></td><td><strong>594 (49.42%)</strong></td><td><strong>312</strong></td><td><strong>1202</strong></td><td>100%</td></tr></tbody></table></div>
          <img src="imagenes/grafico_division_por_tipo.png" alt="Gráfico de División por Tipo de Prueba" class="img-fluid">
        </div>
      </div>
    </div>
    
    <!-- Sección 3: Análisis por Semestre -->
    <div class="section">
      <h2 class="mb-4">3. Análisis por Semestre y Tipo de Prueba</h2>
      <div class="row">
        <div class="col-md-12">
          <h3>Distribución por Semestre y Tipo de Prueba</h3><div class='table-responsive'><table class='table table-striped table-hover'><thead><tr><th></th><th>ECOS</th><th>IA</th><th>Sin aplicar</th><th>Total</th><th>% del total aplicados</th></tr></thead><tbody><tr><td><strong>1</strong></td><td>150</td><td>199</td><td>79</td><td><strong>349</strong></td><td><strong>29.03%</strong></td></tr><tr><td><strong>2</strong></td><td>87</td><td>86</td><td>55</td><td><strong>173</strong></td><td><strong>14.39%</strong></td></tr><tr><td><strong>3</strong></td><td>6</td><td>4</td><td>7</td><td><strong>10</strong></td><td><strong>0.83%</strong></td></tr><tr><td><strong>4</strong></td><td>30</td><td>16</td><td>37</td><td><strong>46</strong></td><td><strong>3.83%</strong></td></tr><tr><td><strong>5</strong></td><td>7</td><td>6</td><td>5</td><td><strong>13</strong></td><td><strong>1.08%</strong></td></tr><tr><td><strong>6</strong></td><td>13</td><td>13</td><td>6</td><td><strong>26</strong></td><td><strong>2.16%</strong></td></tr><tr><td><strong>7</strong></td><td>26</td><td>21</td><td>5</td><td><strong>47</strong></td><td><strong>3.91%</strong></td></tr><tr><td><strong>8</strong></td><td>163</td><td>123</td><td>49</td><td><strong>286</strong></td><td><strong>23.79%</strong></td></tr><tr><td><strong>9</strong></td><td>44</td><td>32</td><td>23</td><td><strong>76</strong></td><td><strong>6.32%</strong></td></tr><tr><td><strong>10</strong></td><td>62</td><td>67</td><td>33</td><td><strong>129</strong></td><td><strong>10.73%</strong></td></tr><tr><td><strong>11</strong></td><td>13</td><td>5</td><td>6</td><td><strong>18</strong></td><td><strong>1.5%</strong></td></tr><tr><td><strong>12</strong></td><td>3</td><td>11</td><td>5</td><td><strong>14</strong></td><td><strong>1.16%</strong></td></tr><tr><td><strong>13</strong></td><td>3</td><td>3</td><td>2</td><td><strong>6</strong></td><td><strong>0.5%</strong></td></tr><tr><td><strong>14</strong></td><td>1</td><td>5</td><td>0</td><td><strong>6</strong></td><td><strong>0.5%</strong></td></tr><tr><td><strong>15</strong></td><td>0</td><td>2</td><td>0</td><td><strong>2</strong></td><td><strong>0.17%</strong></td></tr><tr><td><strong>16</strong></td><td>0</td><td>1</td><td>0</td><td><strong>1</strong></td><td><strong>0.08%</strong></td></tr><tr class='table-active'><td><strong>Total</strong></td><td><strong>608 (50.58%)</strong></td><td><strong>594 (49.42%)</strong></td><td><strong>312</strong></td><td><strong>1202</strong></td><td>100%</td></tr></tbody></table></div>
        </div>
      </div>
      <div class="row">
        <div class="col-md-6">
          <img src="imagenes/grafico_semestre_IA.png" alt="Gráfico de Semestre - Pruebas IA" class="img-fluid">
        </div>
        <div class="col-md-6">
          <img src="imagenes/grafico_semestre_ECOS.png" alt="Gráfico de Semestre - Pruebas ECOS" class="img-fluid">
        </div>
      </div>
    </div>
    
    <!-- Sección 4: Análisis por Carrera -->
    <div class="section">
      <h2 class="mb-4">4. Top 10 Carreras por Tipo de Prueba</h2>
      <div class="row">
        <div class="col-md-12">
          <p>El siguiente gráfico muestra las 10 carreras con mayor número de estudiantes participantes, distinguiendo el número y porcentaje para cada tipo de prueba (IA y ECOS).</p>
          <img src="imagenes/grafico_carrera_top10_combinado.png" alt="Top 10 Carreras por Tipo de Prueba" class="img-fluid mb-4">
          
          <div class="row mt-4">
            <div class="col-md-6">
              <h4 class="text-primary">Top 10 Carreras - Pruebas IA</h4>
              <img src="imagenes/grafico_top10_carreras_IA.png" alt="Top 10 Carreras con Mayor Número de Estudiantes en Pruebas IA" class="img-fluid">
            </div>
            <div class="col-md-6">
              <h4 class="text-danger">Top 10 Carreras - Pruebas ECOS</h4>
              <img src="imagenes/grafico_top10_carreras_ECOS.png" alt="Top 10 Carreras con Mayor Número de Estudiantes en Pruebas ECOS" class="img-fluid">
            </div>
          </div>
        </div>
      </div>
    </div>
    
    <!-- Sección 5: Análisis Detallado Agrupado por Tipo de Prueba -->
    <div class="section">
      <h2 class="mb-4">5. Análisis Detallado por Tipo de Prueba</h2>
      
      <!-- Análisis de Carrera agrupado por tipo de prueba -->
      <h3 class="mt-4">Carrera por Tipo de Prueba</h3>
      <h3>Distribución de Carreras por Tipo de Prueba</h3><div class='table-responsive'><table class='table table-striped table-hover'><thead><tr><th></th><th>ECOS</th><th>IA</th><th>Sin aplicar</th><th>Total</th><th>% del total aplicados</th></tr></thead><tbody><tr><td><strong>ADMINISTRACIÓN DE EMPRESAS</strong></td><td>22</td><td>36</td><td>6</td><td><strong>58</strong></td><td><strong>4.83%</strong></td></tr><tr><td><strong>ADMINISTRACIÓN DE LA HOSPITALIDAD</strong></td><td>4</td><td>17</td><td>7</td><td><strong>21</strong></td><td><strong>1.75%</strong></td></tr><tr><td><strong>ARQUITECTURA</strong></td><td>44</td><td>25</td><td>21</td><td><strong>69</strong></td><td><strong>5.74%</strong></td></tr><tr><td><strong>CIENCIAS POLÍTICAS Y ADMINISTRACIÓN PÚBLICA</strong></td><td>7</td><td>6</td><td>5</td><td><strong>13</strong></td><td><strong>1.08%</strong></td></tr><tr><td><strong>CIENCIAS TEOLÓGICAS</strong></td><td>7</td><td>8</td><td>1</td><td><strong>15</strong></td><td><strong>1.25%</strong></td></tr><tr><td><strong>COMUNICACIÓN</strong></td><td>74</td><td>20</td><td>6</td><td><strong>94</strong></td><td><strong>7.82%</strong></td></tr><tr><td><strong>CONTADURÍA Y DIRECCIÓN DE NEGOCIOS</strong></td><td>2</td><td>2</td><td>6</td><td><strong>4</strong></td><td><strong>0.33%</strong></td></tr><tr><td><strong>CONTADURÍA Y GESTIÓN EMPRESARIAL</strong></td><td>0</td><td>0</td><td>10</td><td><strong>0</strong></td><td><strong>0%</strong></td></tr><tr><td><strong>DERECHO</strong></td><td>25</td><td>94</td><td>19</td><td><strong>119</strong></td><td><strong>9.9%</strong></td></tr><tr><td><strong>DISEÑO DE FICCIONES Y NARRATIVAS TRANSMEDIA</strong></td><td>11</td><td>5</td><td>7</td><td><strong>16</strong></td><td><strong>1.33%</strong></td></tr><tr><td><strong>DISEÑO DE MODA Y TEXTILES SOSTENIBLES</strong></td><td>30</td><td>8</td><td>6</td><td><strong>38</strong></td><td><strong>3.16%</strong></td></tr><tr><td><strong>DISEÑO DE PRODUCTOS Y EXPERIENCIAS</strong></td><td>50</td><td>47</td><td>18</td><td><strong>97</strong></td><td><strong>8.07%</strong></td></tr><tr><td><strong>DISEÑO SENSORIAL Y DIRECCIÓN CREATIVA</strong></td><td>10</td><td>9</td><td>34</td><td><strong>19</strong></td><td><strong>1.58%</strong></td></tr><tr><td><strong>ECONOMÍA</strong></td><td>20</td><td>0</td><td>5</td><td><strong>20</strong></td><td><strong>1.66%</strong></td></tr><tr><td><strong>FILOSOFÍA</strong></td><td>0</td><td>0</td><td>4</td><td><strong>0</strong></td><td><strong>0%</strong></td></tr><tr><td><strong>FINANZAS</strong></td><td>13</td><td>13</td><td>22</td><td><strong>26</strong></td><td><strong>2.16%</strong></td></tr><tr><td><strong>HISTORIA</strong></td><td>0</td><td>4</td><td>4</td><td><strong>4</strong></td><td><strong>0.33%</strong></td></tr><tr><td><strong>HISTORIA DEL ARTE</strong></td><td>0</td><td>20</td><td>0</td><td><strong>20</strong></td><td><strong>1.66%</strong></td></tr><tr><td><strong>INGENIERÍA BIOMÉDICA</strong></td><td>11</td><td>7</td><td>4</td><td><strong>18</strong></td><td><strong>1.5%</strong></td></tr><tr><td><strong>INGENIERÍA CIVIL</strong></td><td>3</td><td>19</td><td>6</td><td><strong>22</strong></td><td><strong>1.83%</strong></td></tr><tr><td><strong>INGENIERÍA DE ALIMENTOS</strong></td><td>9</td><td>0</td><td>0</td><td><strong>9</strong></td><td><strong>0.75%</strong></td></tr><tr><td><strong>INGENIERÍA EN CIENCIA DE DATOS</strong></td><td>5</td><td>1</td><td>1</td><td><strong>6</strong></td><td><strong>0.5%</strong></td></tr><tr><td><strong>INGENIERÍA EN MECATRÓNICA Y PRODUCCIÓN</strong></td><td>0</td><td>10</td><td>1</td><td><strong>10</strong></td><td><strong>0.83%</strong></td></tr><tr><td><strong>INGENIERÍA EN TECNOLOGÍAS DE CÓMPUTO Y TELECOMUNICACIONES</strong></td><td>1</td><td>4</td><td>0</td><td><strong>5</strong></td><td><strong>0.42%</strong></td></tr><tr><td><strong>INGENIERÍA FÍSICA</strong></td><td>12</td><td>0</td><td>0</td><td><strong>12</strong></td><td><strong>1%</strong></td></tr><tr><td><strong>INGENIERÍA INDUSTRIAL</strong></td><td>9</td><td>25</td><td>18</td><td><strong>34</strong></td><td><strong>2.83%</strong></td></tr><tr><td><strong>INGENIERÍA MECÁNICA Y ELÉCTRICA</strong></td><td>0</td><td>16</td><td>2</td><td><strong>16</strong></td><td><strong>1.33%</strong></td></tr><tr><td><strong>INGENIERÍA MECATRÓNICA Y SISTEMAS CIBERFÍSICOS</strong></td><td>1</td><td>0</td><td>4</td><td><strong>1</strong></td><td><strong>0.08%</strong></td></tr><tr><td><strong>INGENIERÍA QUÍMICA</strong></td><td>40</td><td>4</td><td>6</td><td><strong>44</strong></td><td><strong>3.66%</strong></td></tr><tr><td><strong>LITERATURA LATINOAMERICANA</strong></td><td>6</td><td>0</td><td>0</td><td><strong>6</strong></td><td><strong>0.5%</strong></td></tr><tr><td><strong>MERCADOTECNIA</strong></td><td>57</td><td>29</td><td>26</td><td><strong>86</strong></td><td><strong>7.15%</strong></td></tr><tr><td><strong>NEGOCIOS GLOBALES</strong></td><td>19</td><td>37</td><td>9</td><td><strong>56</strong></td><td><strong>4.66%</strong></td></tr><tr><td><strong>NUTRICIÓN Y CIENCIA DE LOS ALIMENTOS</strong></td><td>17</td><td>0</td><td>23</td><td><strong>17</strong></td><td><strong>1.41%</strong></td></tr><tr><td><strong>PEDAGOGÍA</strong></td><td>9</td><td>0</td><td>4</td><td><strong>9</strong></td><td><strong>0.75%</strong></td></tr><tr><td><strong>PSICOLOGÍA</strong></td><td>3</td><td>110</td><td>12</td><td><strong>113</strong></td><td><strong>9.4%</strong></td></tr><tr><td><strong>RELACIONES INTERNACIONALES</strong></td><td>22</td><td>18</td><td>4</td><td><strong>40</strong></td><td><strong>3.33%</strong></td></tr><tr><td><strong>SUSTENTABILIDAD AMBIENTAL</strong></td><td>65</td><td>0</td><td>11</td><td><strong>65</strong></td><td><strong>5.41%</strong></td></tr><tr class='table-active'><td><strong>Total</strong></td><td><strong>608 (50.58%)</strong></td><td><strong>594 (49.42%)</strong></td><td><strong>312</strong></td><td><strong>1202</strong></td><td>100%</td></tr></tbody></table></div>
      

      <!-- Análisis de Semestre agrupado por tipo de prueba -->
      <h3 class="mt-4">Semestre por Tipo de Prueba</h3>
      <h3>Distribución de Semestres por Tipo de Prueba</h3><div class='table-responsive'><table class='table table-striped table-hover'><thead><tr><th></th><th>ECOS</th><th>IA</th><th>Sin aplicar</th><th>Total</th><th>% del total aplicados</th></tr></thead><tbody><tr><td><strong>1</strong></td><td>150</td><td>199</td><td>79</td><td><strong>349</strong></td><td><strong>29.03%</strong></td></tr><tr><td><strong>2</strong></td><td>87</td><td>86</td><td>55</td><td><strong>173</strong></td><td><strong>14.39%</strong></td></tr><tr><td><strong>3</strong></td><td>6</td><td>4</td><td>7</td><td><strong>10</strong></td><td><strong>0.83%</strong></td></tr><tr><td><strong>4</strong></td><td>30</td><td>16</td><td>37</td><td><strong>46</strong></td><td><strong>3.83%</strong></td></tr><tr><td><strong>5</strong></td><td>7</td><td>6</td><td>5</td><td><strong>13</strong></td><td><strong>1.08%</strong></td></tr><tr><td><strong>6</strong></td><td>13</td><td>13</td><td>6</td><td><strong>26</strong></td><td><strong>2.16%</strong></td></tr><tr><td><strong>7</strong></td><td>26</td><td>21</td><td>5</td><td><strong>47</strong></td><td><strong>3.91%</strong></td></tr><tr><td><strong>8</strong></td><td>163</td><td>123</td><td>49</td><td><strong>286</strong></td><td><strong>23.79%</strong></td></tr><tr><td><strong>9</strong></td><td>44</td><td>32</td><td>23</td><td><strong>76</strong></td><td><strong>6.32%</strong></td></tr><tr><td><strong>10</strong></td><td>62</td><td>67</td><td>33</td><td><strong>129</strong></td><td><strong>10.73%</strong></td></tr><tr><td><strong>11</strong></td><td>13</td><td>5</td><td>6</td><td><strong>18</strong></td><td><strong>1.5%</strong></td></tr><tr><td><strong>12</strong></td><td>3</td><td>11</td><td>5</td><td><strong>14</strong></td><td><strong>1.16%</strong></td></tr><tr><td><strong>13</strong></td><td>3</td><td>3</td><td>2</td><td><strong>6</strong></td><td><strong>0.5%</strong></td></tr><tr><td><strong>14</strong></td><td>1</td><td>5</td><td>0</td><td><strong>6</strong></td><td><strong>0.5%</strong></td></tr><tr><td><strong>15</strong></td><td>0</td><td>2</td><td>0</td><td><strong>2</strong></td><td><strong>0.17%</strong></td></tr><tr><td><strong>16</strong></td><td>0</td><td>1</td><td>0</td><td><strong>1</strong></td><td><strong>0.08%</strong></td></tr><tr class='table-active'><td><strong>Total</strong></td><td><strong>608 (50.58%)</strong></td><td><strong>594 (49.42%)</strong></td><td><strong>312</strong></td><td><strong>1202</strong></td><td>100%</td></tr></tbody></table></div>
      
      <!-- Análisis de Status agrupado por tipo de prueba -->
      <h3 class="mt-4">Status por Tipo de Prueba</h3>
      <h3>Distribución de Status por Tipo de Prueba</h3><div class='table-responsive'><table class='table table-striped table-hover'><thead><tr><th></th><th>ECOS</th><th>IA</th><th>Sin aplicar</th><th>Total</th><th>% del total aplicados</th></tr></thead><tbody><tr><td><strong>ECOSV1</strong></td><td>281</td><td>0</td><td>0</td><td><strong>281</strong></td><td><strong>23.36%</strong></td></tr><tr><td><strong>ECOSV2</strong></td><td>328</td><td>0</td><td>0</td><td><strong>328</strong></td><td><strong>27.27%</strong></td></tr><tr><td><strong>IAV1</strong></td><td>0</td><td>349</td><td>0</td><td><strong>349</strong></td><td><strong>29.01%</strong></td></tr><tr><td><strong>IAV2</strong></td><td>0</td><td>245</td><td>0</td><td><strong>245</strong></td><td><strong>20.37%</strong></td></tr><tr class='table-active'><td><strong>Total</strong></td><td><strong>609 (50.62%)</strong></td><td><strong>594 (49.38%)</strong></td><td><strong>0</strong></td><td><strong>1203</strong></td><td>100%</td></tr></tbody></table></div>
      
    </div>
    
    <!-- Footer -->
    <div class="footer">
      <p>Reporte generado por el Programa de evaluación Educativa PEE - Universidad Iberoamericana</p>
    </div>
  </div>
  
  <!-- Bootstrap JS Bundle with Popper -->
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js"></script>
</body>
</html>
