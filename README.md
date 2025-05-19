# Proyecto-grupo2
Proyecto grupo2-htlm
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yamaha Motors - Concesionario Oficial</title>

    <link href="https://cdnjs.cloudflare.com/ajax/libs/tailwindcss/2.2.19/tailwind.min.css" rel="stylesheet">
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.0/jquery.min.js"></script>
</head>
<body>


    <!-- Navegación -->
    <nav class="bg-black text-white p-4">
        <div class="container mx-auto flex justify-between items-center">
            <div class="flex items-center">
                     <img src="https://www.yamahamotos.cl/wp-content/uploads/2019/10/logo-header-black.jpg" alt="Logo do site" class="logo" width="300" height="70" >



            </div>


            <div class="space-x-4">
                <a href="#inicio" class="hover:text-blue-300">Inicio</a>
                <a href="#motos" class="hover:text-blue-300">Modelos</a>
                <a href="#servicios" class="hover:text-blue-300">Servicios</a>
                <a href="#ubicaciones" class="hover:text-blue-300">Ubicaciones</a>
                <a href="#contacto" class="hover:text-blue-300">Contacto</a>
            </div>
        </div>
    </nav>


 <div class="video">
                   <iframe width="100%" height="315" src="https://www.youtube.com/embed/k3o4Qk0bYjg?si=HrXXpaI4aDrU2pA3" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
                </div>

    <!-- Hero Section -->



 <header class="relative h-96" id="inicio">
        <img src="https://bcnmotorbikes.com/wp-content/uploads/2023/06/2022-Yamaha-YZF1000R1SPL-EU-Icon_Performance-Static-001-03.jpg" alt="Yamaha R1M" class="w-full h-full object-cover">
        <div class="absolute inset-0 bg-black bg-opacity-40 flex items-center justify-center">
            <div class="text-center text-white">
                <h2 class="text-4xl font-bold mb-4">REVS YOUR HEART</h2>
                <p class="text-xl mb-8">Descubre la nueva gama Yamaha 2025</p>
                <a href="#motos" class="bg-red-600 text-white px-8 py-3 rounded-lg hover:bg-blue-700">
                    Ver Modelos
                </a>
            </div>
        </div>
    </header>


    <!-- Sección de Motos -->

    <section id="motos" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4"; >
            <h2 class="text-3xl font-bold text-center mb-12">Modelos Destacados</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">


                <!-- Moto 1 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <img src="https://www.yamahamotos.cl/wp-content/uploads/2021/03/21mt09Storm-1200-06.jpg" alt="Yamaha MT-09" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha MT-09</h3>
                        <p class="text-gray-600 mb-4">El poder del Dark Side of Japan.</p>
                        <a href="mt09.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>



                <!-- Moto 2 -->
<div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <img src="https://www.yamahamotos.cl/wp-content/uploads/2021/03/21mt03storm-1200-01.jpg" alt="Yamaha MT-03" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha MT-03</h3>
                        <p class="text-gray-600 mb-4"> La calle definitiva. 321cc de libertad urbana.</p>

                <a href="mt03.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>

                </div>
                </div>







               
                <!-- Moto 3 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <img src="https://www.yamahamotos.cl/wp-content/uploads/2021/03/21mt07Storm-1200-06.jpg" alt="Yamaha MT-07" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha MT-07</h3>
                        <p class="text-gray-600 mb-4">La rebeldía en dos ruedas. Libertad sin ataduras.</p>
                        <a href="mt07.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>

 <!-- Moto 4 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <img src="https://www.yamahamotos.cl/wp-content/uploads/2022/07/22mt10storm-1200-14.jpg" alt="Yamaha MT-10" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha MT-10</h3>
                        <p class="text-gray-600 mb-4">Un demonio urbano: 180 CV de adrenalina pura.</p>
                        <a href="mt10.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>

 <!-- Moto 5 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
       <img src="https://www.yamahamotos.cl/wp-content/uploads/2022/11/250FX.png" alt="Yamaha YZ-250FX" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha YZ-250FX</h3>
                        <p class="text-gray-600 mb-4"> La fiera del cross-country.</p>
               <a href="YZ-250FX.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>


 <!-- Moto 6 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
           <img src="https://www.yamahamotos.cl/wp-content/uploads/2023/09/NEW_XTZ-125_AZUL.jpg" alt="Yamaha XTZ-125" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">YamahaXTZ-125</h3>
                        <p class="text-gray-600 mb-4">La llave maestra del terreno: Abre cualquier camino.</p>
                        <a href="XTZ-125.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>


 <!-- Moto 7 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <img src="https://www.yamahamotos.cl/wp-content/uploads/2020/01/2020-Yamaha-YZF1000R1-EU-Icon_Blue-360-Degrees-035_Tablet.jpg" alt="Yamaha R1" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha R1</h3>
                        <p class="text-gray-600 mb-4">El rey del asfalto: 200 hp de pasión desatada.</p>
                        <a href="R1.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>

 <!-- Moto 8 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <img src="https://www.yamahamotos.cl/wp-content/uploads/2022/02/22xsr700black-1200-06.jpg" alt="Yamaha XSR-700" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha XSR-700</h3>
                        <p class="text-gray-600 mb-4">La nostalgia moderna 689cc de emoción clásica.</p>
                        <a href="XSR-700.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>

 <!-- Moto 9 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <img src="https://www.yamahamotos.cl/wp-content/uploads/2023/06/FZ25-azul-abs.jpg" alt="Yamaha MT-09" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha FZ-25 A</h3>
                        <p class="text-gray-600 mb-4">El equilibrio perfecto: chasis diamante y frenos ABS.</p>
                        <a href="FZ-25 A.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>

 <!-- Moto 10 -->
                <div class="bg-white rounded-lg shadow-lg overflow-hidden">
                    <img src="https://www.yamahamotos.cl/wp-content/uploads/2024/05/5-1.jpg" alt="Yamaha NEW WR-450F" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <h3 class="text-xl font-bold mb-2">Yamaha NEW WR-450F</h3>
                        <p class="text-gray-600 mb-4">El rey del off-road: adrenalina pura en cada tramo.</p>
                        <a href="NEW WR-450F.html" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Ver Detalles</a>
                    </div>
                </div>




            </div>
        </div>
    </section>

    <!-- Sección de Servicios -->
    <section id="servicios" class="py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Servicios Oficiales Yamaha</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <div class="flex items-start space-x-4">
                    <div class="bg-red-600 p-3 rounded-lg text-white">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"/>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-2">Mantenimiento Oficial</h3>
                        <p class="text-gray-600">Servicio técnico certificado Yamaha con repuestos originales.</p>
                    </div>
                </div>
                <div class="flex items-start space-x-4">
                    <div class="bg-red-600 p-3 rounded-lg text-white">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 6v6m0 0v6m0-6h6m-6 0H6"/>
                        </svg>
                    </div>
                    <div>
                        <h3 class="text-xl font-bold mb-2">Yamaha Genuine Parts</h3>
                        <p class="text-gray-600">Accesorios y repuestos originales para tu Yamaha.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>



    <!-- Sección de Ubicaciones -->
    <section id="ubicaciones" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Nuestras Ubicaciones</h2>
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">


                <!-- Sucursal 1 -->
                <div class="bg-white rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-3">Sucursal Triangulo</h3>
                    <p class="text-gray-600 mb-4">Av. Gral. Rumiñahui 782, Quito</p>
                    <button onclick="openModal('modal1')" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">
                        Ver en Mapa

                    </button>



    <!-- Modal para mostrar el mapa -->
    <div id="modal1" style="display:none;">
        <!-- Aquí va tu iframe con el código de Google Maps -->
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3111.8081510831353!2d-78.46221522635847!3d-0.2988700353412465!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x91d5bd4faaf2e227%3A0x794388d853757925!2sYAMAHA%20EL%20TRI%C3%81NGULO!5e1!3m2!1ses!2sec!4v1738888552990!5m2!1ses!2sec" width="300" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        <!-- Cierra modal -->
        <button onclick='document.getElementById("modal1").style.display = "none";' class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Cerrar</button>
    </div>

</div>

<script>
function openModal(id) {
  document.getElementById(id).style.display = 'block';
}
</script>





                </div>


  <!-- Sucursal 2 -->
                <div class="bg-white rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-3">Sucursal Atahualpa</h3>
                    <p class="text-gray-600 mb-4">Avenue Alonso de Angulo, Quito 170111</p>
                    <button onclick="openModal('modal2')" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">
                        Ver en Mapa

                    </button>



    <!-- Modal para mostrar el mapa -->
    <div id="modal2" style="display:none;">
        <!-- Aquí va tu iframe con el código de Google Maps -->
        <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3111.821269463469!2d-78.53121703231785!3d-0.24828423478931594!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x91d5992402afa10b%3A0x5acd4e72189362c4!2sYamaha%20Atahualpa!5e1!3m2!1ses!2sec!4v1738889672462!5m2!1ses!2sec" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        <!-- Cierra modal -->
        <button onclick='document.getElementById("modal2").style.display = "none";' class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Cerrar</button>
    </div>

</div>

<script>
function openModal(id) {
  document.getElementById(id).style.display = 'block';
}
</script>
      </div>



                <!-- Sucursal 3 -->
                <div class="bg-white rounded-lg shadow-lg p-6">
                    <h3 class="text-xl font-bold mb-3">Sucursal Ibarra</h3>
                    <p class="text-gray-600 mb-4">Av Mariano Acosta, y, Ibarra 100106</p>
                    <button onclick="openModal('modal3')" class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">
                        Ver en Mapa

                    </button>



    <!-- Modal para mostrar el mapa -->
    <div id="modal3" style="display:none;">
        <!-- Aquí va tu iframe con el código de Google Maps -->
       <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3111.7930574520433!2d-78.12964812636112!3d0.3480935639794135!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x8e2a3cb8a7171f07%3A0xdac17b7203f64549!2sYamaha%20Ibarra!5e1!3m2!1ses!2sec!4v1738889945817!5m2!1ses!2sec" width="400" height="300" style="border:0;" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
        <!-- Cierra modal -->
        <button onclick='document.getElementById("modal3").style.display = "none";' class="bg-red-600 text-white px-4 py-2 rounded hover:bg-blue-700">Cerrar</button>
    </div>

</div>

<script>
function openModal(id) {
  document.getElementById(id).style.display = 'block';
}
</script>





                </div>



            </div>
        </div>
    </section>




    <!-- Sección de Contacto -->
    <section id="contacto" class="py-16">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-12">Contacta con tu Concesionario Oficial</h2>
            <div class="max-w-lg mx-auto">
                <form class="space-y-6">
                    <div>
                        <label class="block text-gray-700 mb-2" for="nombre">Nombre</label>
                        <input type="text" id="nombre" class="w-full p-3 border rounded-lg">
                    </div>
                    <div>
                        <label class="block text-gray-700 mb-2" for="email">Email</label>
                        <input type="email" id="email" class="w-full p-3 border rounded-lg">
                    </div>
                    <div>
                        <label class="block text-gray-700 mb-2" for="modelo">Modelo de interés</label>
                        <select id="modelo" class="w-full p-3 border rounded-lg">
                            <option>MT-09</option>
                            <option>MT-03</option>
                            <option>MT-07</option>
                            <option>MT-10</option>
                            <option>YZ-250X</option>
                            <option>XTZ-125</option>
                            <option>R1</option>
                            <option>XSR-700</option>
                            <option>FZ-25 A</option>
                            <option>NEW WR-450F</option>


                    </select>
                    </div>
                    <div>
                        <label class="block text-gray-700 mb-2" for="mensaje">Mensaje</label>
                        <textarea id="mensaje" rows="4" class="w-full p-3 border rounded-lg"></textarea>
                    </div>
                    <button type="submit" class="w-full bg-red-600 text-white py-3 rounded-lg hover:bg-blue-700">
                        Solicitar Información
                    </button>
                </form>
            </div>
        </div>
    </section>

    <!-- Nueva sección de Redes Sociales -->
    <section class="py-12 bg-black text-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Síguenos en Redes Sociales</h2>
            <div class="flex justify-center space-x-8">
                <a href="https://www.facebook.com/YamahaEcuador/?locale=es_LA" target="_blank" class="hover:text-blue-400 transition-colors">
                    <i class="fab fa-facebook-f text-3xl"></i>
                </a>
                <a href="https://twitter.com/YAMAHAECUADOR/status/650807637492154368?lang=es"" class="hover:text-blue-400 transition-colors">
                    <i class="fab fa-twitter text-3xl"></i>
                </a>
                <a href="https://www.instagram.com/yamahaecuador/?hl=es" class="hover:text-pink-400 transition-colors">
                    <i class="fab fa-instagram text-3xl"></i>
                </a>
                <a href="https://www.youtube.com/@yamahamotoreu" class="hover:text-red-600 transition-colors">
                    <i class="fab fa-youtube text-3xl"></i>
                </a>
                <a href="#" class="hover:text-blue-600 transition-colors">
                    <i class="fab fa-linkedin-in text-3xl"></i>
                </a>
            </div>
            <div class="text-center mt-6">
                <p class="text-gray-400">Mantente conectado con las últimas novedades</p>
                <div class="mt-4 max-w-md mx-auto">
                    <form class="flex gap-2">
                        <input type="email" placeholder="Tu email" class="flex-1 p-2 rounded text-black">
                        <button class="bg-red-600 px-4 py-2 rounded hover:bg-blue-700">Suscribirse</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-red-900 text-white py-8">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="font-bold text-lg mb-4">Contacto</h3>
                    <p>Email: info@yamaha.com</p>
                    <p>Tel:0992756458</p>
                    <p>Tel:0984284560</p>
                    <p>Tel:0987919621</p>
                </div>
                <div>
                    <h3 class="font-bold text-lg mb-4">Enlaces Rápidos</h3>
                    <ul class="space-y-2">
                        <li><a href="#motos" class="hover:text-blue-300">Modelos</a></li>
                        <li><a href="#servicios" class="hover:text-blue-300">Servicios</a></li>
                        <li><a href="#contacto" class="hover:text-blue-300">Contacto</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold text-lg mb-4">Servicios</h3>
                    <ul class="space-y-2">
                        <li>Mantenimiento</li>
                        <li>Repuestos</li>
                        <li>Financiación</li>
                    </ul>
                </div>
                <div>
                    <h3 class="font-bold text-lg mb-4">Síguenos</h3>
                    <div class="flex space-x-4">
                        <a href="#" class="hover:text-blue-300"><i class="fab fa-facebook-f"></i></a>
                        <a href="#" class="hover:text-blue-300"><i class="fab fa-twitter"></i>    </section>

    <!-- Mismo footer que index.html -->
</body>
</html>
