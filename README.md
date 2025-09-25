<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Humanizer & Detector - Transforma y Detecta Contenido IA</title>
    <meta name="description" content="Humaniza texto generado por IA y detecta contenido artificial. Herramientas profesionales para mejorar tu contenido.">
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Font Awesome -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;500;600;700&display=swap" rel="stylesheet">
    
    <style>
        body { font-family: 'Inter', sans-serif; }
        .gradient-bg { background: linear-gradient(135deg, #667eea 0%, #764ba2 100%); }
        .glass-effect { backdrop-filter: blur(10px); background: rgba(255, 255, 255, 0.1); }
        .animate-float { animation: float 6s ease-in-out infinite; }
        @keyframes float {
            0%, 100% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
        }
        .typing-animation { border-right: 2px solid #667eea; animation: blink 1s infinite; }
        @keyframes blink {
            0%, 50% { border-color: transparent; }
            51%, 100% { border-color: #667eea; }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg fixed w-full z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <i class="fas fa-robot text-2xl text-purple-600 mr-2"></i>
                    <span class="text-xl font-bold text-gray-900">AI Tools Pro</span>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#inicio" class="text-gray-700 hover:text-purple-600 transition">Inicio</a>
                    <a href="#humanizador" class="text-gray-700 hover:text-purple-600 transition">Humanizador</a>
                    <a href="#detector" class="text-gray-700 hover:text-purple-600 transition">Detector</a>
                    <a href="#precios" class="text-gray-700 hover:text-purple-600 transition">Precios</a>
                    <a href="#contacto" class="text-gray-700 hover:text-purple-600 transition">Contacto</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-btn" class="text-gray-700">
                        <i class="fas fa-bars text-xl"></i>
                    </button>
                </div>
            </div>
        </div>
        <!-- Mobile Menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white border-t">
            <div class="px-2 pt-2 pb-3 space-y-1">
                <a href="#inicio" class="block px-3 py-2 text-gray-700">Inicio</a>
                <a href="#humanizador" class="block px-3 py-2 text-gray-700">Humanizador</a>
                <a href="#detector" class="block px-3 py-2 text-gray-700">Detector</a>
                <a href="#precios" class="block px-3 py-2 text-gray-700">Precios</a>
                <a href="#contacto" class="block px-3 py-2 text-gray-700">Contacto</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="inicio" class="gradient-bg min-h-screen flex items-center pt-16">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-20">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12 items-center">
                <div class="text-white">
                    <h1 class="text-4xl md:text-6xl font-bold mb-6">
                        Transforma y Detecta
                        <span class="text-yellow-300">Contenido IA</span>
                    </h1>
                    <p class="text-xl mb-8 text-gray-200">
                        Humaniza texto generado por IA y detecta contenido artificial con nuestras herramientas avanzadas de procesamiento de lenguaje natural.
                    </p>
                    <div class="flex flex-col sm:flex-row gap-4">
                        <button id="btn-humanizador" class="bg-yellow-400 text-gray-900 px-8 py-3 rounded-lg font-semibold hover:bg-yellow-300 transition transform hover:scale-105">
                            Probar Humanizador
                        </button>
                        <button id="btn-detector" class="border border-white text-white px-8 py-3 rounded-lg font-semibold hover:bg-white hover:text-gray-900 transition">
                            Probar Detector
                        </button>
                    </div>
                </div>
                <div class="animate-float">
                    <div class="glass-effect rounded-2xl p-8">
                        <div class="bg-white rounded-lg p-6 mb-4">
                            <div class="flex items-center mb-3">
                                <i class="fas fa-robot text-purple-600 mr-2"></i>
                                <span class="text-sm text-gray-600">Texto IA Original</span>
                            </div>
                            <p class="text-gray-800 text-sm">The artificial intelligence system generates content with perfect grammar and structured sentences...</p>
                        </div>
                        <div class="bg-green-50 rounded-lg p-6">
                            <div class="flex items-center mb-3">
                                <i class="fas fa-user text-green-600 mr-2"></i>
                                <span class="text-sm text-gray-600">Texto Humanizado</span>
                            </div>
                            <p class="text-gray-800 text-sm">AI systems create content, but sometimes it feels a bit robotic. That's where humanization comes in...</p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Features Section -->
    <section class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                    Características Principales
                </h2>
                <p class="text-xl text-gray-600">
                    Herramientas profesionales para optimizar tu contenido
                </p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="text-center p-6 rounded-lg hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-magic text-2xl text-purple-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Humanización Avanzada</h3>
                    <p class="text-gray-600">Convierte texto robótico en contenido natural y auténtico que conecta con tu audiencia.</p>
                </div>
                
                <div class="text-center p-6 rounded-lg hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-search text-2xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Detección Precisa</h3>
                    <p class="text-gray-600">Identifica contenido generado por IA con alta precisión usando algoritmos de última generación.</p>
                </div>
                
                <div class="text-center p-6 rounded-lg hover:shadow-lg transition">
                    <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <i class="fas fa-bolt text-2xl text-green-600"></i>
                    </div>
                    <h3 class="text-xl font-semibold mb-3">Procesamiento Rápido</h3>
                    <p class="text-gray-600">Resultados instantáneos para que puedas optimizar tu flujo de trabajo sin interrupciones.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Humanizer Tool -->
    <section id="humanizador" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                    <i class="fas fa-magic text-purple-600 mr-3"></i>
                    Humanizador de IA
                </h2>
                <p class="text-xl text-gray-600">Convierte texto robótico en contenido natural y humano</p>
            </div>
            
            <div class="bg-white rounded-2xl shadow-xl p-8">
                <div class="grid grid-cols-1 lg:grid-cols-2 gap-8">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">
                            <i class="fas fa-robot mr-2"></i>Texto Original (IA)
                        </label>
                        <textarea 
                            id="originalText" 
                            rows="10" 
                            class="w-full p-4 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent"
                            placeholder="Pega aquí el texto generado por IA que quieres humanizar..."
                        ></textarea>
                        <div class="mt-4 flex justify-between items-center">
                            <span id="originalCount" class="text-sm text-gray-500">0 caracteres</span>
                            <button 
                                id="humanizeBtn" 
                                class="bg-purple-600 text-white px-6 py-2 rounded-lg hover:bg-purple-700 transition flex items-center"
                            >
                                <i class="fas fa-magic mr-2"></i>Humanizar
                            </button>
                        </div>
                    </div>
                    
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-2">
                            <i class="fas fa-user mr-2"></i>Texto Humanizado
                        </label>
                        <textarea 
                            id="humanizedText" 
                            rows="10" 
                            class="w-full p-4 border border-gray-300 rounded-lg bg-gray-50"
                            placeholder="Aquí aparecerá tu texto humanizado..."
                            readonly
                        ></textarea>
                        <div class="mt-4 flex justify-between items-center">
                            <span id="humanizedCount" class="text-sm text-gray-500">0 caracteres</span>
                            <button 
                                id="copyBtn" 
                                class="bg-green-600 text-white px-6 py-2 rounded-lg hover:bg-green-700 transition flex items-center"
                            >
                                <i class="fas fa-copy mr-2"></i>Copiar
                            </button>
                        </div>
                    </div>
                </div>
                
                <div class="mt-6 p-4 bg-blue-50 rounded-lg">
                    <div class="flex items-center">
                        <i class="fas fa-info-circle text-blue-600 mr-2"></i>
                        <span class="text-sm text-blue-800">
                            El humanizador mejora la fluidez, reduce repeticiones y añade variación natural al texto.
                        </span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- AI Detector Tool -->
    <section id="detector" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">
                    <i class="fas fa-search text-blue-600 mr-3"></i>
                    Detector de IA
                </h2>
                <p class="text-xl text-gray-600">Identifica si el contenido fue generado por inteligencia artificial</p>
            </div>
            
            <div class="bg-white rounded-2xl shadow-xl p-8">
                <div class="mb-6">
                    <label class="block text-sm font-medium text-gray-700 mb-2">
                        <i class="fas fa-file-text mr-2"></i>Texto a Analizar
                    </label>
                    <textarea 
                        id="detectText" 
                        rows="8" 
                        class="w-full p-4 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-transparent"
                        placeholder="Introduce el texto que quieres analizar para detectar si fue generado por IA..."
                    ></textarea>
                    <div class="mt-4 flex justify-between items-center">
                        <span id="detectCount" class="text-sm text-gray-500">0 caracteres</span>
                        <button 
                            id="detectBtn" 
                            class="bg-blue-600 text-white px-6 py-2 rounded-lg hover:bg-blue-700 transition flex items-center"
                        >
                            <i class="fas fa-search mr-2"></i>Analizar Texto
                        </button>
                    </div>
                </div>
                
                <div id="detectionResults" class="hidden">
                    <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-6">
                        <div class="text-center p-4 bg-gray-50 rounded-lg">
                            <div class="text-2xl font-bold text-gray-900" id="aiProbability">0%</div>
                            <div class="text-sm text-gray-600">Probabilidad IA</div>
                        </div>
                        <div class="text-center p-4 bg-gray-50 rounded-lg">
                            <div class="text-2xl font-bold text-gray-900" id="humanProbability">0%</div>
                            <div class="text-sm text-gray-600">Probabilidad Humana</div>
                        </div>
                        <div class="text-center p-4 bg-gray-50 rounded-lg">
                            <div class="text-2xl font-bold text-gray-900" id="confidenceScore">0%</div>
                            <div class="text-sm text-gray-600">Confianza</div>
                        </div>
                    </div>
                    
                    <div class="p-4 rounded-lg" id="resultCard">
                        <div class="flex items-center mb-2">
                            <i id="resultIcon" class="fas fa-circle mr-2"></i>
                            <span class="font-semibold" id="resultText"></span>
                        </div>
                        <p class="text-sm" id="resultDescription"></p>
                    </div>
                    
                    <div class="mt-4 p-4 bg-gray-50 rounded-lg">
                        <h4 class="font-semibold mb-2">
                            <i class="fas fa-chart-bar mr-2"></i>Análisis Detallado
                        </h4>
                        <div class="space-y-2">
                            <div class="flex justify-between">
                                <span class="text-sm">Repetitividad:</span>
                                <span class="text-sm font-medium" id="repetitiveness">-</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-sm">Variación de vocabulario:</span>
                                <span class="text-sm font-medium" id="vocabulary">-</span>
                            </div>
                            <div class="flex justify-between">
                                <span class="text-sm">Estructura de oraciones:</span>
                                <span class="text-sm font-medium" id="structure">-</span>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Pricing Section -->
    <section id="precios" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Planes y Precios</h2>
                <p class="text-xl text-gray-600">Elige el plan que mejor se adapte a tus necesidades</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="bg-white rounded-lg shadow-lg p-8 relative">
                    <div class="text-center">
                        <h3 class="text-xl font-semibold text-gray-900 mb-4">Básico</h3>
                        <div class="text-4xl font-bold text-gray-900 mb-2">Gratis</div>
                        <p class="text-gray-600 mb-6">Para uso personal</p>
                        
                        <ul class="space-y-3 mb-8">
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>1,000 caracteres/día</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>Humanizador básico</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>Detector de IA</span>
                            </li>
                        </ul>
                        
                        <button class="w-full bg-gray-200 text-gray-800 py-3 rounded-lg font-semibold hover:bg-gray-300 transition">
                            Comenzar Gratis
                        </button>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg shadow-lg p-8 relative border-2 border-purple-500">
                    <div class="absolute -top-4 left-1/2 transform -translate-x-1/2">
                        <span class="bg-purple-500 text-white px-4 py-2 rounded-full text-sm font-semibold">
                            Más Popular
                        </span>
                    </div>
                    <div class="text-center">
                        <h3 class="text-xl font-semibold text-gray-900 mb-4">Pro</h3>
                        <div class="text-4xl font-bold text-gray-900 mb-2">€19</div>
                        <p class="text-gray-600 mb-6">por mes</p>
                        
                        <ul class="space-y-3 mb-8">
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>50,000 caracteres/día</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>Humanizador avanzado</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>Detector premium</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>API access</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>Soporte prioritario</span>
                            </li>
                        </ul>
                        
                        <button class="w-full bg-purple-600 text-white py-3 rounded-lg font-semibold hover:bg-purple-700 transition">
                            Empezar Prueba
                        </button>
                    </div>
                </div>
                
                <div class="bg-white rounded-lg shadow-lg p-8 relative">
                    <div class="text-center">
                        <h3 class="text-xl font-semibold text-gray-900 mb-4">Empresa</h3>
                        <div class="text-4xl font-bold text-gray-900 mb-2">€99</div>
                        <p class="text-gray-600 mb-6">por mes</p>
                        
                        <ul class="space-y-3 mb-8">
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>Caracteres ilimitados</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>IA personalizada</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>API empresarial</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>Integraciones</span>
                            </li>
                            <li class="flex items-center">
                                <i class="fas fa-check text-green-500 mr-3"></i>
                                <span>Soporte 24/7</span>
                            </li>
                        </ul>
                        
                        <button class="w-full bg-gray-900 text-white py-3 rounded-lg font-semibold hover:bg-gray-800 transition">
                            Contactar Ventas
                        </button>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contacto" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mb-4">Contacto</h2>
                <p class="text-xl text-gray-600">¿Tienes preguntas? Nos encantaría ayudarte</p>
            </div>
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-semibold mb-6">Información de Contacto</h3>
                    <div class="space-y-4">
                        <div class="flex items-center">
                            <i class="fas fa-envelope text-purple-600 mr-4"></i>
                            <span>contacto@aitoolspro.com</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-phone text-purple-600 mr-4"></i>
                            <span>+34 900 123 456</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fas fa-map-marker-alt text-purple-600 mr-4"></i>
                            <span>Madrid, España</span>
                        </div>
                    </div>
                    
                    <div class="mt-8">
                        <h4 class="text-lg font-semibold mb-4">Síguenos</h4>
                        <div class="flex space-x-4">
                            <a href="#" class="w-10 h-10 bg-purple-600 text-white rounded-full flex items-center justify-center hover:bg-purple-700 transition">
                                <i class="fab fa-twitter"></i>
                            </a>
                            <a href="#" class="w-10 h-10 bg-purple-600 text-white rounded-full flex items-center justify-center hover:bg-purple-700 transition">
                                <i class="fab fa-linkedin"></i>
                            </a>
                            <a href="#" class="w-10 h-10 bg-purple-600 text-white rounded-full flex items-center justify-center hover:bg-purple-700 transition">
                                <i class="fab fa-github"></i>
                            </a>
                        </div>
                    </div>
                </div>
                
                <div>
                    <form id="contactForm" class="space-y-6">
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Nombre</label>
                            <input type="text" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent" placeholder="Tu nombre">
                        </div>
                        
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Email</label>
                            <input type="email" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent" placeholder="tu@email.com">
                        </div>
                        
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Asunto</label>
                            <input type="text" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent" placeholder="Asunto del mensaje">
                        </div>
                        
                        <div>
                            <label class="block text-sm font-medium text-gray-700 mb-2">Mensaje</label>
                            <textarea rows="5" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent" placeholder="Tu mensaje..."></textarea>
                        </div>
                        
                        <button type="submit" class="w-full bg-purple-600 text-white py-3 rounded-lg font-semibold hover:bg-purple-700 transition">
                            <i class="fas fa-paper-plane mr-2"></i>Enviar Mensaje
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center mb-4">
                        <i class="fas fa-robot text-2xl text-purple-400 mr-2"></i>
                        <span class="text-xl font-bold">AI Tools Pro</span>
                    </div>
                    <p class="text-gray-400">
                        Herramientas avanzadas de IA para humanizar y detectar contenido artificial.
                    </p>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Herramientas</h4>
                    <ul class="space-y-2">
                        <li><a href="#humanizador" class="text-gray-400 hover:text-white transition">Humanizador</a></li>
                        <li><a href="#detector" class="text-gray-400 hover:text-white transition">Detector</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">API</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Empresa</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Acerca de</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Blog</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Carreras</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">Soporte</h4>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Centro de Ayuda</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition">Documentación</a></li>
                        <li><a href="#contacto" class="text-gray-400 hover:text-white transition">Contacto</a></li>
                    </ul>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-8 flex flex-col md:flex-row justify-between items-center">
                <div class="text-gray-400 text-sm mb-4 md:mb-0">
                    © 2024 AI Tools Pro. Todos los derechos reservados.
                </div>
                <div class="flex space-x-6 text-sm">
                    <a href="#" class="text-gray-400 hover:text-white transition">Política de Privacidad</a>
                    <a href="#" class="text-gray-400 hover:text-white transition">Términos de Uso</a>
                    <a href="#" class="text-gray-400 hover:text-white transition">Cookies</a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Global variables to store app state
        let appState = {
            isProcessing: false
        };

        // Utility Functions
        function scrollToSection(sectionId) {
            const element = document.getElementById(sectionId);
            if (element) {
                element.scrollIntoView({ behavior: 'smooth' });
            }
        }

        function updateCharacterCount(inputId, countId) {
            const input = document.getElementById(inputId);
            const counter = document.getElementById(countId);
            if (input && counter) {
                counter.textContent = input.value.length + ' caracteres';
            }
        }

        // Advanced Humanization Algorithm - Anti-Detection (Spanish Version)
        function performHumanization(text) {
            if (!text || text.trim() === '') return '';
            
            let humanized = text;
            
            // Step 1: Advanced word replacements with multiple Spanish variations
            const advancedReplacements = [
                // AI-typical words to human alternatives in Spanish
                [/\bdemonstrate[sd]?\b/gi, () => randomChoice(['muestra', 'demuestra', 'revela', 'indica', 'enseña'])],
                [/\butilize[sd]?\b/gi, () => randomChoice(['usa', 'emplea', 'aplica', 'utiliza'])],
                [/\bfacilitate[sd]?\b/gi, () => randomChoice(['ayuda', 'facilita', 'hace más fácil', 'permite'])],
                [/\benhance[sd]?\b/gi, () => randomChoice(['mejora', 'aumenta', 'potencia', 'optimiza'])],
                [/\boptimize[sd]?\b/gi, () => randomChoice(['mejora', 'optimiza', 'perfecciona', 'ajusta'])],
                [/\bleverage[sd]?\b/gi, () => randomChoice(['usa', 'aprovecha', 'saca partido de'])],
                [/\bimplement[sed]?\b/gi, () => randomChoice(['implementa', 'pone en marcha', 'lleva a cabo', 'ejecuta'])],
                [/\bcomprehensive\b/gi, () => randomChoice(['completo', 'integral', 'total', 'detallado'])],
                [/\bsignificant\b/gi, () => randomChoice(['importante', 'grande', 'notable', 'considerable'])],
                [/\bsubstantial\b/gi, () => randomChoice(['grande', 'considerable', 'importante', 'significativo'])],
                [/\bfundamental\b/gi, () => randomChoice(['básico', 'fundamental', 'esencial', 'clave'])],
                [/\bessential\b/gi, () => randomChoice(['crucial', 'vital', 'importante', 'necesario'])],
                [/\bcritical\b/gi, () => randomChoice(['crucial', 'vital', 'importante', 'clave'])],
                [/\bparadigm\b/gi, () => randomChoice(['modelo', 'enfoque', 'método', 'forma'])],
                [/\bmethodology\b/gi, () => randomChoice(['método', 'enfoque', 'forma', 'proceso'])],
                
                // Formal connectors with varied Spanish alternatives
                [/\bhowever\b/gi, () => randomChoice(['pero', 'aunque', 'sin embargo', 'no obstante', 'por otro lado'])],
                [/\bfurthermore\b/gi, () => randomChoice(['además', 'también', 'encima', 'por si fuera poco', 'y'])],
                [/\bmoreover\b/gi, () => randomChoice(['además', 'también', 'encima', 'por si fuera poco'])],
                [/\bin addition\b/gi, () => randomChoice(['además', 'también', 'y', 'encima de eso'])],
                [/\btherefore\b/gi, () => randomChoice(['por eso', 'así que', 'por lo tanto', 'entonces'])],
                [/\bconsequently\b/gi, () => randomChoice(['por eso', 'como resultado', 'esto significa', 'debido a esto'])],
                [/\bnevertheless\b/gi, () => randomChoice(['aun así', 'sin embargo', 'pero', 'igualmente'])],
                [/\bsubsequently\b/gi, () => randomChoice(['después', 'luego', 'más tarde', 'a continuación'])],
                [/\bin conclusion\b/gi, () => randomChoice(['para resumir', 'al final', 'finalmente', 'en resumen'])],
                [/\bto summarize\b/gi, () => randomChoice(['en resumen', 'básicamente', 'resumiendo', 'en pocas palabras'])],
                [/\bfor instance\b/gi, () => randomChoice(['por ejemplo', 'como', 'tal como', 'pongamos'])],
                [/\bspecifically\b/gi, () => randomChoice(['en particular', 'especialmente', 'concretamente'])],
                [/\bnotably\b/gi, () => randomChoice(['especialmente', 'particularmente', 'sobre todo'])],
                [/\bundoubtedly\b/gi, () => randomChoice(['claramente', 'obviamente', 'definitivamente', 'sin duda'])],
                [/\bcertainly\b/gi, () => randomChoice(['definitivamente', 'sin duda', 'absolutamente', 'claramente'])],
                [/\bobviously\b/gi, () => randomChoice(['claramente', 'por supuesto', 'naturalmente'])],
                
                // Contractions and natural Spanish expressions
                [/\bdo not\b/gi, "no"],
                [/\bdoes not\b/gi, "no"],
                [/\bwill not\b/gi, "no va a"],
                [/\bcannot\b/gi, "no puede"],
                [/\bshould not\b/gi, "no debería"],
                [/\bwould not\b/gi, "no haría"],
                [/\bcould not\b/gi, "no podría"],
                [/\bit is\b/gi, () => randomChoice(["es", "está"])],
                [/\bthat is\b/gi, () => randomChoice(["eso es", "es decir"])],
                [/\bwhat is\b/gi, "qué es"],
                [/\bwhere is\b/gi, "dónde está"],
                [/\bwhen is\b/gi, "cuándo es"],
                [/\bwho is\b/gi, "quién es"],
                [/\bhow is\b/gi, "cómo está"],
                [/\bwe are\b/gi, "somos"],
                [/\bthey are\b/gi, "son"],
                [/\byou are\b/gi, "eres"],
                [/\bI am\b/gi, "soy"],
                [/\bhe is\b/gi, "él es"],
                [/\bshe is\b/gi, "ella es"],
                
                // Formal phrases to casual Spanish
                [/\bin order to\b/gi, 'para'],
                [/\bdue to the fact that\b/gi, 'porque'],
                [/\bfor the purpose of\b/gi, 'para'],
                [/\bwith regard to\b/gi, () => randomChoice(['sobre', 'acerca de', 'en cuanto a'])],
                [/\bin the event that\b/gi, 'si'],
                [/\bat this point in time\b/gi, () => randomChoice(['ahora', 'en este momento', 'actualmente'])],
                [/\bdespite the fact that\b/gi, () => randomChoice(['aunque', 'a pesar de que', 'pese a'])],
                [/\bin light of the fact that\b/gi, () => randomChoice(['ya que', 'porque', 'dado que'])],
                [/\bprior to\b/gi, 'antes de'],
                [/\bsubsequent to\b/gi, 'después de'],
                [/\bat the present time\b/gi, () => randomChoice(['ahora', 'actualmente', 'en este momento'])],
                [/\bin the near future\b/gi, () => randomChoice(['pronto', 'en breve', 'en los próximos días'])],
                [/\ba considerable amount of\b/gi, () => randomChoice(['mucho', 'una gran cantidad de', 'bastante'])],
                [/\ba large number of\b/gi, () => randomChoice(['muchos', 'una gran cantidad de', 'bastantes'])],
                [/\bin the majority of cases\b/gi, () => randomChoice(['normalmente', 'la mayoría de las veces', 'por lo general'])],
            ];
            
            // Helper function for random choices
            function randomChoice(arr) {
                return arr[Math.floor(Math.random() * arr.length)];
            }
            
            // Apply advanced replacements
            advancedReplacements.forEach(([pattern, replacement]) => {
                if (typeof replacement === 'function') {
                    humanized = humanized.replace(pattern, replacement);
                } else {
                    humanized = humanized.replace(pattern, replacement);
                }
            });
            
            // Step 2: Sentence structure variation and humanization in Spanish
            let sentences = humanized.split(/([.!?]+)/);
            let processedSentences = [];
            
            for (let i = 0; i < sentences.length; i += 2) {
                let sentence = sentences[i];
                let punctuation = sentences[i + 1] || '';
                
                if (sentence && sentence.trim()) {
                    sentence = sentence.trim();
                    
                    // Add human-like Spanish sentence starters randomly
                    if (i > 0 && Math.random() < 0.25) {
                        const humanStarters = [
                            'Mira, ', 'Escucha, ', 'Bueno, ', 'La cosa es que ', 'Sinceramente, ',
                            'En realidad, ', '¿Sabes qué? ', 'La verdad es que ', 'Te digo que ',
                            'Yo creo que ', 'Lo que pasa es que ', 'Básicamente, ', 'Para ser honesto, ',
                            'Hablando claro, ', 'A ver, ', 'Fíjate que ', 'Resulta que '
                        ];
                        const starter = randomChoice(humanStarters);
                        sentence = starter + sentence.toLowerCase();
                    }
                    
                    // Break long sentences more naturally in Spanish
                    if (sentence.length > 120) {
                        const breakWords = [', y ', ', pero ', ', así que ', ', que ', ', donde '];
                        let broken = false;
                        
                        for (let breakWord of breakWords) {
                            if (sentence.includes(breakWord) && !broken) {
                                const parts = sentence.split(breakWord);
                                if (parts.length === 2 && parts[0].length > 30 && parts[1].length > 30) {
                                    processedSentences.push(parts[0] + '.');
                                    processedSentences.push(' ');
                                    
                                    // Add Spanish connecting words
                                    const connectors = ['Además, ', 'También, ', 'Y ', 'Encima, ', ''];
                                    const connector = randomChoice(connectors);
                                    processedSentences.push(connector + parts[1].charAt(0).toUpperCase() + parts[1].slice(1));
                                    processedSentences.push(punctuation);
                                    broken = true;
                                    break;
                                }
                            }
                        }
                        
                        if (!broken) {
                            processedSentences.push(sentence);
                            if (punctuation) processedSentences.push(punctuation);
                        }
                    } else {
                        processedSentences.push(sentence);
                        if (punctuation) processedSentences.push(punctuation);
                    }
                } else if (punctuation) {
                    processedSentences.push(punctuation);
                }
            }
            
            humanized = processedSentences.join('');
            
            // Step 3: Add Spanish human imperfections and natural flow
            // Occasionally add Spanish filler words
            if (Math.random() < 0.3) {
                const fillers = [' ya sabes,', ' o sea,', ' vamos,', ' bueno,', ' ¿no?'];
                const sentences = humanized.split('.');
                if (sentences.length > 1) {
                    const randomIndex = Math.floor(Math.random() * (sentences.length - 1));
                    const filler = randomChoice(fillers);
                    sentences[randomIndex] = sentences[randomIndex] + filler;
                    humanized = sentences.join('.');
                }
            }
            
            // Step 4: Vary punctuation slightly
            humanized = humanized.replace(/\. /g, () => {
                return Math.random() < 0.1 ? '... ' : '. ';
            });
            
            // Add occasional Spanish emphasis
            const words = humanized.split(' ');
            for (let i = 0; i < words.length; i++) {
                if (Math.random() < 0.05) { // 5% chance
                    const emphasisWords = ['realmente', 'en realidad', 'definitivamente', 'totalmente', 'completamente'];
                    if (!emphasisWords.some(ew => words[i].toLowerCase().includes(ew))) {
                        const emphasis = randomChoice(emphasisWords);
                        words[i] = emphasis + ' ' + words[i];
                    }
                }
            }
            humanized = words.join(' ');
            
            // Step 5: Clean up and finalize
            humanized = humanized.replace(/\s+/g, ' ').trim();
            humanized = humanized.replace(/\.\s*\./g, '.');
            humanized = humanized.replace(/,\s*,/g, ',');
            humanized = humanized.replace(/\s+([,.!?])/g, '$1');
            
            // Ensure first letter is capitalized
            if (humanized.length > 0) {
                humanized = humanized.charAt(0).toUpperCase() + humanized.slice(1);
            }
            
            return humanized;
        }

        // AI Detection Algorithm
        function performAIDetection(text) {
            if (!text || text.trim() === '') return null;
            
            let aiScore = 0;
            const totalPoints = 100;
            
            // Metric 1: Formal language patterns (25 points)
            const formalPatterns = [
                /\bhowever\b/gi, /\bfurthermore\b/gi, /\bmoreover\b/gi, /\bin addition\b/gi,
                /\btherefore\b/gi, /\bconsequently\b/gi, /\bnevertheless\b/gi, /\bsubsequently\b/gi,
                /\bin conclusion\b/gi, /\bto summarize\b/gi, /\bfor instance\b/gi, /\bspecifically\b/gi,
                /\bnotably\b/gi, /\bundoubtedly\b/gi, /\bcertainly\b/gi, /\bobviously\b/gi
            ];
            
            let formalCount = 0;
            formalPatterns.forEach(pattern => {
                const matches = text.match(pattern) || [];
                formalCount += matches.length;
            });
            
            const formalScore = Math.min(25, formalCount * 2);
            aiScore += formalScore;
            
            // Metric 2: Lack of contractions (20 points)
            const contractions = text.match(/\b(don't|doesn't|won't|can't|shouldn't|wouldn't|couldn't|it's|that's|what's|where's|when's|who's|how's|we're|they're|you're|I'm|he's|she's)\b/gi) || [];
            const words = text.split(/\s+/).filter(word => word.length > 0);
            const contractionRatio = (contractions.length / words.length) * 100;
            
            const contractionScore = Math.max(0, 20 - (contractionRatio * 4));
            aiScore += contractionScore;
            
            // Metric 3: Sentence length uniformity (20 points)
            const sentences = text.split(/[.!?]+/).filter(s => s.trim().length > 10);
            if (sentences.length > 2) {
                const lengths = sentences.map(s => s.trim().split(/\s+/).length);
                const avgLength = lengths.reduce((a, b) => a + b, 0) / lengths.length;
                const variance = lengths.reduce((sum, len) => sum + Math.pow(len - avgLength, 2), 0) / lengths.length;
                const stdDev = Math.sqrt(variance);
                
                // Lower standard deviation = more uniform = more AI-like
                const uniformityScore = Math.max(0, 20 - stdDev);
                aiScore += uniformityScore;
            }
            
            // Metric 4: Repetitive sentence starters (15 points)
            const starters = ['The ', 'This ', 'These ', 'That ', 'Those ', 'It ', 'There ', 'In ', 'On ', 'With '];
            const starterCounts = {};
            
            sentences.forEach(sentence => {
                const trimmed = sentence.trim();
                starters.forEach(starter => {
                    if (trimmed.toLowerCase().startsWith(starter.toLowerCase())) {
                        starterCounts[starter] = (starterCounts[starter] || 0) + 1;
                    }
                });
            });
            
            const maxRepeats = Math.max(...Object.values(starterCounts), 0);
            const repetitionScore = Math.min(15, maxRepeats * 2);
            aiScore += repetitionScore;
            
            // Metric 5: Complex vocabulary density (20 points)
            const complexWords = text.match(/\b\w{8,}\b/g) || [];
            const complexityRatio = (complexWords.length / words.length) * 100;
            
            // High complexity can indicate AI
            const complexityScore = Math.min(20, complexityRatio * 1.5);
            aiScore += complexityScore;
            
            // Calculate final percentages
            const aiProbability = Math.round(Math.min(95, Math.max(5, aiScore)));
            const humanProbability = 100 - aiProbability;
            const confidence = Math.min(95, Math.max(60, Math.abs(aiProbability - 50) * 1.8));
            
            return {
                aiProbability,
                humanProbability,
                confidence,
                metrics: {
                    formalCount,
                    contractionRatio: Math.round(contractionRatio * 10) / 10,
                    sentences: sentences.length,
                    complexWords: complexWords.length,
                    repetitionScore
                }
            };
        }

        // Display detection results
        function displayDetectionResults(results) {
            if (!results) return;
            
            const resultsDiv = document.getElementById('detectionResults');
            resultsDiv.classList.remove('hidden');
            
            // Update main metrics
            document.getElementById('aiProbability').textContent = results.aiProbability + '%';
            document.getElementById('humanProbability').textContent = results.humanProbability + '%';
            document.getElementById('confidenceScore').textContent = results.confidence + '%';
            
            // Update result card
            const resultCard = document.getElementById('resultCard');
            const resultIcon = document.getElementById('resultIcon');
            const resultText = document.getElementById('resultText');
            const resultDescription = document.getElementById('resultDescription');
            
            if (results.aiProbability >= 70) {
                resultCard.className = 'p-4 rounded-lg bg-red-50 border border-red-200';
                resultIcon.className = 'fas fa-robot mr-2 text-red-600';
                resultText.textContent = 'Probablemente generado por IA';
                resultText.className = 'font-semibold text-red-800';
                resultDescription.textContent = 'El texto muestra múltiples características típicas de contenido generado por inteligencia artificial.';
                resultDescription.className = 'text-sm text-red-700';
            } else if (results.aiProbability >= 40) {
                resultCard.className = 'p-4 rounded-lg bg-yellow-50 border border-yellow-200';
                resultIcon.className = 'fas fa-question-circle mr-2 text-yellow-600';
                resultText.textContent = 'Posiblemente mixto o editado';
                resultText.className = 'font-semibold text-yellow-800';
                resultDescription.textContent = 'El texto podría ser una mezcla de contenido humano y generado por IA, o texto de IA editado.';
                resultDescription.className = 'text-sm text-yellow-700';
            } else {
                resultCard.className = 'p-4 rounded-lg bg-green-50 border border-green-200';
                resultIcon.className = 'fas fa-user mr-2 text-green-600';
                resultText.textContent = 'Probablemente escrito por humano';
                resultText.className = 'font-semibold text-green-800';
                resultDescription.textContent = 'El texto muestra características naturales de escritura humana con variaciones orgánicas.';
                resultDescription.className = 'text-sm text-green-700';
            }
            
            // Update detailed analysis
            const metrics = results.metrics;
            
            document.getElementById('repetitiveness').textContent = 
                metrics.formalCount > 8 ? 'Alta' : 
                metrics.formalCount > 4 ? 'Media' : 'Baja';
                
            document.getElementById('vocabulary').textContent = 
                metrics.contractionRatio > 3 ? 'Natural' : 
                metrics.contractionRatio > 1 ? 'Semiformal' : 'Formal';
                
            document.getElementById('structure').textContent = 
                metrics.repetitionScore > 6 ? 'Repetitiva' : 
                metrics.repetitionScore > 3 ? 'Algo repetitiva' : 'Variada';
        }

        // Main Functions
        function humanizeText() {
            if (appState.isProcessing) return;
            
            const originalText = document.getElementById('originalText').value;
            if (!originalText.trim()) {
                alert('Por favor, introduce texto para humanizar');
                return;
            }
            
            appState.isProcessing = true;
            const button = document.getElementById('humanizeBtn');
            const originalButtonText = button.innerHTML;
            button.innerHTML = '<i class="fas fa-spinner fa-spin mr-2"></i>Humanizando...';
            button.disabled = true;
            
            setTimeout(() => {
                const humanizedText = performHumanization(originalText);
                document.getElementById('humanizedText').value = humanizedText;
                updateCharacterCount('humanizedText', 'humanizedCount');
                
                // Reset button
                button.innerHTML = originalButtonText;
                button.disabled = false;
                appState.isProcessing = false;
            }, 1500);
        }

        function detectAI() {
            if (appState.isProcessing) return;
            
            const detectText = document.getElementById('detectText').value;
            if (!detectText.trim()) {
                alert('Por favor, introduce texto para analizar');
                return;
            }
            
            appState.isProcessing = true;
            const button = document.getElementById('detectBtn');
            const originalButtonText = button.innerHTML;
            button.innerHTML = '<i class="fas fa-spinner fa-spin mr-2"></i>Analizando...';
            button.disabled = true;
            
            setTimeout(() => {
                const results = performAIDetection(detectText);
                displayDetectionResults(results);
                
                // Reset button
                button.innerHTML = originalButtonText;
                button.disabled = false;
                appState.isProcessing = false;
            }, 2000);
        }

        function copyHumanizedText() {
            const text = document.getElementById('humanizedText').value;
            if (!text || text.trim() === '') {
                alert('No hay texto humanizado para copiar');
                return;
            }
            
            navigator.clipboard.writeText(text).then(() => {
                const button = document.getElementById('copyBtn');
                const originalText = button.innerHTML;
                button.innerHTML = '<i class="fas fa-check mr-2"></i>¡Copiado!';
                button.classList.add('bg-green-700');
                button.classList.remove('bg-green-600', 'hover:bg-green-700');
                
                setTimeout(() => {
                    button.innerHTML = originalText;
                    button.classList.remove('bg-green-700');
                    button.classList.add('bg-green-600', 'hover:bg-green-700');
                }, 2000);
            }).catch(() => {
                alert('Error al copiar el texto. Intenta seleccionar y copiar manualmente.');
            });
        }

        // Event Listeners
        document.addEventListener('DOMContentLoaded', function() {
            // Mobile menu toggle
            const mobileMenuBtn = document.getElementById('mobile-menu-btn');
            const mobileMenu = document.getElementById('mobile-menu');
            
            if (mobileMenuBtn && mobileMenu) {
                mobileMenuBtn.addEventListener('click', () => {
                    mobileMenu.classList.toggle('hidden');
                });
            }
            
            // Navigation buttons
            const btnHumanizador = document.getElementById('btn-humanizador');
            const btnDetector = document.getElementById('btn-detector');
            
            if (btnHumanizador) {
                btnHumanizador.addEventListener('click', () => scrollToSection('humanizador'));
            }
            
            if (btnDetector) {
                btnDetector.addEventListener('click', () => scrollToSection('detector'));
            }
            
            // Tool buttons
            const humanizeBtn = document.getElementById('humanizeBtn');
            const detectBtn = document.getElementById('detectBtn');
            const copyBtn = document.getElementById('copyBtn');
            
            if (humanizeBtn) {
                humanizeBtn.addEventListener('click', humanizeText);
            }
            
            if (detectBtn) {
                detectBtn.addEventListener('click', detectAI);
            }
            
            if (copyBtn) {
                copyBtn.addEventListener('click', copyHumanizedText);
            }
            
            // Character counters
            const originalText = document.getElementById('originalText');
            const detectText = document.getElementById('detectText');
            const humanizedText = document.getElementById('humanizedText');
            
            if (originalText) {
                originalText.addEventListener('input', () => updateCharacterCount('originalText', 'originalCount'));
            }
            
            if (detectText) {
                detectText.addEventListener('input', () => updateCharacterCount('detectText', 'detectCount'));
            }
            
            if (humanizedText) {
                humanizedText.addEventListener('input', () => updateCharacterCount('humanizedText', 'humanizedCount'));
            }
            
            // Contact form
            const contactForm = document.getElementById('contactForm');
            if (contactForm) {
                contactForm.addEventListener('submit', (e) => {
                    e.preventDefault();
                    
                    const inputs = contactForm.querySelectorAll('input, textarea');
                    let allFilled = true;
                    
                    inputs.forEach(input => {
                        if (!input.value.trim()) {
                            allFilled = false;
                        }
                    });
                    
                    if (!allFilled) {
                        alert('Por favor, completa todos los campos');
                        return;
                    }
                    
                    alert('¡Mensaje enviado correctamente! Te responderemos pronto.');
                    contactForm.reset();
                });
            }
            
            // Smooth scrolling for anchor links
            document.querySelectorAll('a[href^="#"]').forEach(anchor => {
                anchor.addEventListener('click', function (e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href').substring(1);
                    scrollToSection(targetId);
                });
            });
        });
    </script>
</body>
</html>
