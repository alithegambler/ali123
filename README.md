<!DOCTYPE html>
<html lang="sv">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Min Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Anpassade stilar för extra finess */
        body {
            font-family: 'Inter', sans-serif;
        }
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
    </style>
</head>
<body class="bg-gray-50 text-gray-900">

    <!-- Header / Hero Section -->
    <header class="gradient-bg text-white py-20 px-6 text-center">
        <h1 class="text-4xl md:text-6xl font-bold mb-4">Välkommen till min sida</h1>
        <p class="text-xl opacity-90">Här hittar du mina projekt och meriter</p>
    </header>

    <!-- Huvudinnehåll -->
    <main class="max-w-4xl mx-auto py-12 px-6">
        
        <section class="grid md:grid-cols-2 gap-8">
            <!-- Gymnasiearbete Card -->
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 hover:shadow-md transition-shadow">
                <div class="text-blue-600 mb-4">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="9 12h6m-6 4h6m2 5H7a2 2 0 01-2-2V5a2 2 0 012-2h5.586a1 1 0 01.707.293l5.414 5.414a1 1 0 01.293.707V19a2 2 0 01-2 2z" />
                    </svg>
                </div>
                <h2 class="text-2xl font-bold mb-2">Gymnasiearbete</h2>
                <p class="text-gray-600 mb-6">Här kan du läsa mitt fullständiga gymnasiearbete och se resultaten av min forskning/mitt projekt.</p>
                <!-- Ersätt 'gymnasiearbete.pdf' med din faktiska fil -->
                <a href="gymnasiearbete.pdf" target="_blank" class="inline-block bg-blue-600 text-white px-6 py-2 rounded-lg font-medium hover:bg-blue-700 transition-colors">
                    Läs arbetet
                </a>
            </div>

            <!-- CV Card -->
            <div class="bg-white p-8 rounded-2xl shadow-sm border border-gray-100 hover:shadow-md transition-shadow">
                <div class="text-purple-600 mb-4">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-10 w-10" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z" />
                    </svg>
                </div>
                <h2 class="text-2xl font-bold mb-2">Mitt CV</h2>
                <p class="text-gray-600 mb-6">Se min utbildning, mina arbetslivserfarenheter och de kompetenser jag har förvärvat.</p>
                <!-- Ersätt 'cv.pdf' med din faktiska fil -->
                <a href="cv.pdf" target="_blank" class="inline-block bg-purple-600 text-white px-6 py-2 rounded-lg font-medium hover:bg-purple-700 transition-colors">
                    Visa CV
                </a>
            </div>
        </section>

    </main>

    <!-- Footer -->
    <footer class="text-center py-12 text-gray-500 text-sm">
        <p>&copy; 2024 - Skapad med hjälp av Kodningspartner</p>
    </footer>

</body>
</html>
