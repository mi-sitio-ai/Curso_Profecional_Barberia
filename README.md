<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Curso Profesional de Barbería | Oferta Relámpago $9.99 USD</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#3b82f6',
                        secondary: '#f59e0b'
                    },
                    borderRadius: {
                        'none': '0px',
                        'sm': '4px',
                        DEFAULT: '8px',
                        'md': '12px',
                        'lg': '16px',
                        'xl': '20px',
                        '2xl': '24px',
                        '3xl': '32px',
                        'full': '9999px',
                        'button': '8px'
                    }
                }
            }
        }
    </script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
    <style>
        :where([class^="ri-"])::before { content: "\f3c2"; }
        body {
            font-family: 'Montserrat', sans-serif;
            color: #333;
        }
        .countdown-timer {
            display: flex;
            justify-content: center;
            gap: 10px;
        }
        .countdown-box {
            display: flex;
            flex-direction: column;
            align-items: center;
            background-color: #f8fafc;
            border-radius: 8px;
            padding: 8px 12px;
            box-shadow: 0 1px 3px rgba(0,0,0,0.1);
        }
        .module-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease;
        }
        .module-content.active {
            max-height: 500px;
        }
        @keyframes pulse {
            0% { transform: scale(1); }
            50% { transform: scale(1.02); }
            100% { transform: scale(1); }
        }
        .offer-badge {
            animation: pulse 2s infinite;
            box-shadow: 0 10px 25px -5px rgba(239, 68, 68, 0.3);
        }
    </style>
</head>
<body class="bg-gray-50">
    
    <!-- Banner Principal -->
    <div class="relative w-full bg-cover bg-center h-[500px]" style="background-image: url('https://images.unsplash.com/photo-1595476108010-b4d1f102b1b1?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1920&q=80');">
        <div class="absolute inset-0 bg-black bg-opacity-50"></div>
        <div class="container mx-auto px-4 h-full relative z-10">
            <header class="flex justify-between items-center py-6">
                <div class="text-white text-3xl font-['Pacifico']">BarberPro</div>
                <nav class="hidden md:flex space-x-8">
                    <a href="#" class="text-white hover:text-primary transition">Inicio</a>
                    <a href="#" class="text-white hover:text-primary transition">Cursos</a>
                    <a href="#" class="text-white hover:text-primary transition">Instructores</a>
                    <a href="#" class="text-white hover:text-primary transition">Contacto</a>
                </nav>
                <div class="flex items-center space-x-4">
                    <a href="#" class="text-white hover:text-primary transition">Iniciar Sesión</a>
                    <button class="bg-primary text-white px-6 py-2 !rounded-button whitespace-nowrap hover:bg-blue-600 transition">Registrarse</button>
                </div>
            </header>
            <div class="flex flex-col md:flex-row items-center justify-between h-[350px]">
                <div class="w-full md:w-7/12 text-white">
                    <h1 class="text-4xl md:text-5xl font-bold mb-4">Maestría en Barbería Profesional</h1>
                    <div class="flex items-center mb-4">
                        <div class="flex">
                            <i class="ri-star-fill text-yellow-400"></i>
                            <i class="ri-star-fill text-yellow-400"></i>
                            <i class="ri-star-fill text-yellow-400"></i>
                            <i class="ri-star-fill text-yellow-400"></i>
                            <i class="ri-star-half-fill text-yellow-400"></i>
                        </div>
                        <span class="ml-2">4.8 (342 reseñas)</span>
                    </div>
                    <p class="text-lg mb-6">Domina el arte de la barbería moderna con técnicas avanzadas de corte, afeitado y estilizado. Curso completo para principiantes y barberos que buscan perfeccionar sus habilidades.</p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <button class="bg-primary text-white px-8 py-3 !rounded-button whitespace-nowrap hover:bg-blue-600 transition text-lg font-semibold">Ver Contenido del Curso</button>
                        <button class="bg-white text-primary px-8 py-3 !rounded-button whitespace-nowrap hover:bg-gray-100 transition text-lg font-semibold">Ver Demostración</button>
                    </div>
                </div>
            </div>
        </div>
        
        <!-- Botón flotante de inscripción -->
        <div class="hidden md:block absolute top-32 right-8 bg-white p-6 rounded-lg offer-badge">
            <div class="bg-red-600 text-white text-center py-2 px-4 rounded-t-lg font-bold absolute -top-5 left-0 right-0 mx-auto w-4/5">¡OFERTA RELÁMPAGO!</div>
            <div class="text-center mb-4">
                <p class="text-gray-500 line-through text-lg">$297 USD</p>
                <p class="text-4xl font-bold text-primary">$9.99 USD</p>
                <p class="text-sm text-gray-600 mt-1">¡Ahorra 96%! Oferta por 24 horas</p>
            </div>
            <div class="mb-4">
                <p class="text-center text-sm mb-2">La oferta termina en:</p>
                <div class="countdown-timer">
                    <div class="countdown-box">
                        <span class="font-bold" id="days">01</span>
                        <span class="text-xs">Día</span>
                    </div>
                    <div class="countdown-box">
                        <span class="font-bold" id="hours">06</span>
                        <span class="text-xs">Horas</span>
                    </div>
                    <div class="countdown-box">
                        <span class="font-bold" id="minutes">30</span>
                        <span class="text-xs">Min</span>
                    </div>
                    <div class="countdown-box">
                        <span class="font-bold" id="seconds">00</span>
                        <span class="text-xs">Seg</span>
                    </div>
                </div>
            </div>
            <button class="w-full bg-primary text-white py-3 !rounded-button whitespace-nowrap hover:bg-blue-600 transition font-bold text-lg">¡Quiero mi cupón!</button>
            
            <!-- Métodos de pago actualizados -->
            <div class="mt-4 border-t pt-4">
                <p class="text-xs font-semibold text-center mb-2">Métodos de pago:</p>
                <div class="grid grid-cols-3 gap-2 text-center">
                    <div class="p-1 bg-gray-50 rounded">
                        <i class="ri-money-dollar-circle-fill text-green-500"></i>
                        <p class="text-xs mt-1">Binance</p>
                        <p class="text-xs font-mono break-all">TXTKRq2vHW7eDy...</p>
                    </div>
                    <div class="p-1 bg-gray-50 rounded">
                        <i class="ri-smartphone-fill text-blue-500"></i>
                        <p class="text-xs mt-1">Pago Móvil</p>
                        <p class="text-xs">0412-5224076</p>
                    </div>
                    <div class="p-1 bg-gray-50 rounded">
                        <i class="ri-paypal-fill text-blue-700"></i>
                        <p class="text-xs mt-1">PayPal</p>
                        <p class="text-xs">jesusjacob378@gmail.com</p>
                    </div>
                </div>
                <p class="text-xs text-center mt-3 text-gray-500">Banco Bancamiga | C.I. 19273535</p>
            </div>
        </div>
    </div>

    <!-- Sección de Precios Móvil -->
    <section class="py-16 bg-gradient-to-br from-blue-50 to-blue-100 md:hidden">
        <div class="container mx-auto px-4">
            <div class="max-w-md mx-auto bg-white rounded-xl shadow-lg overflow-hidden offer-badge">
                <div class="bg-red-600 text-white text-center py-2 px-4 font-bold">¡OFERTA RELÁMPAGO!</div>
                <div class="p-6">
                    <div class="text-center mb-6">
                        <p class="text-gray-500 line-through text-lg">$297 USD</p>
                        <p class="text-5xl font-bold text-primary">$9.99 USD</p>
                        <p class="text-sm text-gray-600 mt-1">¡Ahorra 96%! Oferta por 24 horas</p>
                    </div>
                    <div class="mb-6">
                        <p class="text-center text-sm mb-2">La oferta termina en:</p>
                        <div class="countdown-timer">
                            <div class="countdown-box">
                                <span class="font-bold">01</span>
                                <span class="text-xs">Día</span>
                            </div>
                            <div class="countdown-box">
                                <span class="font-bold">06</span>
                                <span class="text-xs">Horas</span>
                            </div>
                            <div class="countdown-box">
                                <span class="font-bold">30</span>
                                <span class="text-xs">Min</span>
                            </div>
                        </div>
                    </div>
                    
                    <!-- Métodos de pago para móvil -->
                    <div class="mb-6 border-t pt-4">
                        <p class="text-xs font-semibold text-center mb-3">MÉTODOS DE PAGO:</p>
                        <div class="space-y-3">
                            <div class="flex items-center bg-gray-50 p-2 rounded">
                                <div class="w-8 h-8 flex items-center justify-center bg-green-100 rounded-full mr-3">
                                    <i class="ri-money-dollar-circle-fill text-green-600"></i>
                                </div>
                                <div>
                                    <p class="font-semibold text-sm">Binance</p>
                                    <p class="text-xs font-mono break-all">TXTKRq2vHW7eDyhp49RSLB1a5JgwNnoZNw</p>
                                </div>
                            </div>
                            <div class="flex items-center bg-gray-50 p-2 rounded">
                                <div class="w-8 h-8 flex items-center justify-center bg-blue-100 rounded-full mr-3">
                                    <i class="ri-smartphone-fill text-blue-600"></i>
                                </div>
                                <div>
                                    <p class="font-semibold text-sm">Pago Móvil</p>
                                    <p class="text-xs">0412-5224076 (Bancamiga)</p>
                                    <p class="text-xs">C.I. 19273535</p>
                                </div>
                            </div>
                            <div class="flex items-center bg-gray-50 p-2 rounded">
                                <div class="w-8 h-8 flex items-center justify-center bg-blue-100 rounded-full mr-3">
                                    <i class="ri-paypal-fill text-blue-700"></i>
                                </div>
                                <div>
                                    <p class="font-semibold text-sm">PayPal</p>
                                    <p class="text-xs">jesusjacob378@gmail.com</p>
                                </div>
                            </div>
                        </div>
                    </div>
                    
                    <button class="w-full bg-primary text-white py-3 !rounded-button whitespace-nowrap hover:bg-blue-600 transition font-bold text-lg">¡Quiero mi cupón!</button>
                    <p class="text-xs text-center mt-4 text-gray-500">Garantía de devolución de 30 días</p>
                </div>
            </div>
        </div>
    </section>

    <!-- ... (resto de las secciones del curso se mantienen igual) ... -->

    <script>
        // Contador regresivo (24 horas)
        document.addEventListener('DOMContentLoaded', function() {
            function updateCountdown() {
                const days = document.querySelectorAll('#days');
                const hours = document.querySelectorAll('#hours');
                const minutes = document.querySelectorAll('#minutes');
                const seconds = document.querySelectorAll('#seconds');
                
                let secondsValue = parseInt(seconds[0].textContent);
                let minutesValue = parseInt(minutes[0].textContent);
                let hoursValue = parseInt(hours[0].textContent);
                let daysValue = parseInt(days[0].textContent);
                
                secondsValue--;
                if (secondsValue < 0) {
                    secondsValue = 59;
                    minutesValue--;
                    if (minutesValue < 0) {
                        minutesValue = 59;
                        hoursValue--;
                        if (hoursValue < 0) {
                            hoursValue = 23;
                            daysValue--;
                            if (daysValue < 0) {
                                daysValue = 0;
                                hoursValue = 0;
                                minutesValue = 0;
                                secondsValue = 0;
                            }
                        }
                    }
                }
                
                days.forEach(day => day.textContent = daysValue < 10 ? '0' + daysValue : daysValue);
                hours.forEach(hour => hour.textContent = hoursValue < 10 ? '0' + hoursValue : hoursValue);
                minutes.forEach(minute => minute.textContent = minutesValue < 10 ? '0' + minutesValue : minutesValue);
                seconds.forEach(second => second.textContent = secondsValue < 10 ? '0' + secondsValue : secondsValue);
            }
            setInterval(updateCountdown, 1000);
        });
    </script>
</body>
</html> #Curso_Profecional_Barberia
