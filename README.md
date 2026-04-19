# rehab-sherif-portfolio
Junior GIS Analyst Portfolio | Rehab Sherif
<!DOCTYPE html>
<html lang="en" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rehab Sherif | GIS Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        gis: {
                            dark: '#0f172a',    // Slate 900
                            primary: '#0ea5e9', // Sky 500
                            accent: '#10b981',  // Emerald 500
                            light: '#f8fafc'    // Slate 50
                        }
                    }
                }
            }
        }
    </script>
    <style>
        .map-pattern {
            background-color: #0f172a;
            background-image: radial-gradient(#1e293b 1px, transparent 1px);
            background-size: 20px 20px;
        }
    </style>
</head>
<body class="bg-gis-light text-slate-800 font-sans antialiased selection:bg-gis-primary selection:text-white">

    <!-- Navbar -->
    <nav class="fixed w-full bg-white/90 backdrop-blur-sm shadow-sm z-50 transition-all duration-300">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16 items-center">
                <div class="flex-shrink-0 flex items-center gap-2">
                    <i class="fa-solid fa-earth-americas text-gis-primary text-2xl"></i>
                    <span class="font-bold text-xl tracking-tight text-gis-dark">Rehab.GIS</span>
                </div>
                <div class="hidden md:flex space-x-8">
                    <a href="#about" class="text-slate-600 hover:text-gis-primary transition">About</a>
                    <a href="#skills" class="text-slate-600 hover:text-gis-primary transition">Skills</a>
                    <a href="#experience" class="text-slate-600 hover:text-gis-primary transition">Experience</a>
                    <a href="#portfolio" class="text-slate-600 hover:text-gis-primary transition">Portfolio</a>
                    <a href="#contact" class="bg-gis-primary text-white px-4 py-2 rounded-full hover:bg-sky-600 transition shadow-md">Hire Me</a>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden map-pattern">
        <div class="relative max-w-6xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-white">
            <div class="inline-block mb-4 px-4 py-1.5 rounded-full border border-gis-accent/30 bg-gis-accent/10 text-gis-accent text-sm font-semibold tracking-wide">
                Available for New Opportunities
            </div>
            <h1 class="text-4xl md:text-6xl font-extrabold tracking-tight mb-6">
                Hi, I'm <span class="text-transparent bg-clip-text bg-gradient-to-r from-gis-primary to-gis-accent">Rehab Sherif</span>
            </h1>
            <p class="text-xl md:text-2xl text-slate-300 mb-4 font-medium">
                GIS & Surveying Specialist | Junior GIS Analyst
            </p>
            <p class="max-w-2xl mx-auto text-slate-400 text-lg mb-10">
                Transforming complex geospatial datasets into actionable insights. Passionate about digital mapping, spatial analysis, and data-driven solutions.
            </p>
            <div class="flex justify-center gap-4">
                <a href="#portfolio" class="bg-gis-primary hover:bg-sky-600 text-white font-semibold py-3 px-8 rounded-full transition shadow-lg shadow-sky-500/30">
                    View My Work
                </a>
                <a href="#contact" class="bg-white/10 hover:bg-white/20 text-white border border-white/20 font-semibold py-3 px-8 rounded-full transition backdrop-blur-sm">
                    Contact Me
                </a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex flex-col md:flex-row items-center gap-12">
                <div class="w-full md:w-1/2">
                    <div class="relative rounded-2xl overflow-hidden shadow-2xl group">
                        <!-- Placeholder for Personal Photo or Map Graphic -->
                        <div class="bg-slate-200 w-full h-80 flex items-center justify-center">
                            <i class="fa-solid fa-map-location-dot text-6xl text-slate-400 group-hover:scale-110 transition duration-500"></i>
                        </div>
                    </div>
                </div>
                <div class="w-full md:w-1/2">
                    <h2 class="text-3xl font-bold text-gis-dark mb-6 flex items-center gap-3">
                        <i class="fa-solid fa-user-astronaut text-gis-primary"></i> Professional Profile
                    </h2>
                    <p class="text-lg text-slate-600 mb-6 leading-relaxed">
                        I am a Junior GIS Analyst with hands-on experience in spatial data analysis, digital mapping, and geospatial visualization using industry-standard tools like ArcGIS and QGIS. 
                    </p>
                    <p class="text-lg text-slate-600 mb-6 leading-relaxed">
                        My expertise lies in processing, cleaning, and validating geospatial datasets to support planning and decision-making. Currently, I am expanding my academic foundation by pursuing a Pre-Master in Human Geography (GIS) at Tanta University.
                    </p>
                    <div class="flex items-center gap-4 text-slate-500">
                        <i class="fa-solid fa-location-dot text-gis-accent text-xl"></i>
                        <span class="text-lg">Based in Tanta, Egypt</span>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Skills Section -->
    <section id="skills" class="py-20 bg-slate-50">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold text-gis-dark mb-4">Technical Competencies</h2>
                <div class="w-20 h-1 bg-gis-primary mx-auto rounded"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Software -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition border border-slate-100">
                    <div class="w-14 h-14 bg-blue-100 rounded-xl flex items-center justify-center mb-6">
                        <i class="fa-solid fa-laptop-code text-2xl text-blue-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 text-gis-dark">Software & Tools</h3>
                    <ul class="space-y-3 text-slate-600">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> ArcGIS</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> QGIS</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> Microsoft Excel</li>
                    </ul>
                </div>

                <!-- Core GIS -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition border border-slate-100">
                    <div class="w-14 h-14 bg-emerald-100 rounded-xl flex items-center justify-center mb-6">
                        <i class="fa-solid fa-layer-group text-2xl text-emerald-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 text-gis-dark">Core GIS Skills</h3>
                    <ul class="space-y-3 text-slate-600">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> Spatial Analysis</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> Digital Mapping & Cartography</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> GIS Data Cleaning</li>
                    </ul>
                </div>

                <!-- Field & Data -->
                <div class="bg-white p-8 rounded-2xl shadow-sm hover:shadow-md transition border border-slate-100">
                    <div class="w-14 h-14 bg-orange-100 rounded-xl flex items-center justify-center mb-6">
                        <i class="fa-solid fa-satellite-dish text-2xl text-orange-600"></i>
                    </div>
                    <h3 class="text-xl font-bold mb-4 text-gis-dark">Field & Data</h3>
                    <ul class="space-y-3 text-slate-600">
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> GPS Data Collection</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> Field Mapping</li>
                        <li class="flex items-center gap-2"><i class="fa-solid fa-check text-gis-accent"></i> Data Visualization</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Experience & Education -->
    <section id="experience" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-16">
                
                <!-- Experience Timeline -->
                <div>
                    <h2 class="text-3xl font-bold text-gis-dark mb-10 flex items-center gap-3">
                        <i class="fa-solid fa-briefcase text-gis-primary"></i> Experience
                    </h2>
                    <div class="space-y-8 relative before:absolute before:inset-0 before:ml-5 before:-translate-x-px md:before:mx-auto md:before:translate-x-0 before:h-full before:w-0.5 before:bg-gradient-to-b before:from-transparent before:via-slate-200 before:to-transparent">
                        
                        <!-- Job 1 -->
                        <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group is-active">
                            <div class="flex items-center justify-center w-10 h-10 rounded-full border border-white bg-gis-primary text-white shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
                                <i class="fa-solid fa-map"></i>
                            </div>
                            <div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] bg-slate-50 p-6 rounded-xl border border-slate-100 shadow-sm">
                                <div class="flex items-center justify-between mb-1">
                                    <h3 class="font-bold text-gis-dark text-lg">GIS Trainee</h3>
                                    <span class="text-sm font-medium text-gis-primary">2023 - 2024</span>
                                </div>
                                <div class="text-slate-500 text-sm mb-3">Creativa</div>
                                <ul class="text-slate-600 text-sm space-y-1 list-disc list-inside">
                                    <li>Analyzed and processed 15+ geospatial datasets using ArcGIS and QGIS.</li>
                                    <li>Produced 10+ thematic maps for land use and population analysis.</li>
                                    <li>Reduced spatial data errors by ~25% through data cleaning.</li>
                                </ul>
                            </div>
                        </div>

                        <!-- Job 2 -->
                        <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group is-active">
                            <div class="flex items-center justify-center w-10 h-10 rounded-full border border-white bg-gis-primary text-white shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
                                <i class="fa-solid fa-route"></i>
                            </div>
                            <div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] bg-slate-50 p-6 rounded-xl border border-slate-100 shadow-sm">
                                <div class="flex items-center justify-between mb-1">
                                    <h3 class="font-bold text-gis-dark text-lg">GIS & Surveying Assistant</h3>
                                    <span class="text-sm font-medium text-gis-primary">2022 - 2023</span>
                                </div>
                                <div class="text-slate-500 text-sm mb-3">GIS Gate</div>
                                <ul class="text-slate-600 text-sm space-y-1 list-disc list-inside">
                                    <li>Participated in 5+ GPS-based field data collection activities.</li>
                                    <li>Digitized and processed multiple spatial layers.</li>
                                    <li>Contributed to 8–12 GIS maps for internal projects.</li>
                                </ul>
                            </div>
                        </div>

                        <!-- Job 3 -->
                        <div class="relative flex items-center justify-between md:justify-normal md:odd:flex-row-reverse group is-active">
                            <div class="flex items-center justify-center w-10 h-10 rounded-full border border-white bg-slate-400 text-white shadow shrink-0 md:order-1 md:group-odd:-translate-x-1/2 md:group-even:translate-x-1/2 z-10">
                                <i class="fa-solid fa-headset"></i>
                            </div>
                            <div class="w-[calc(100%-4rem)] md:w-[calc(50%-2.5rem)] bg-slate-50 p-6 rounded-xl border border-slate-100 shadow-sm">
                                <div class="flex items-center justify-between mb-1">
                                    <h3 class="font-bold text-gis-dark text-lg">Customer Service Rep</h3>
                                    <span class="text-sm font-medium text-slate-500">2021 - 2022</span>
                                </div>
                                <div class="text-slate-500 text-sm mb-3">Social Insurance</div>
                                <ul class="text-slate-600 text-sm space-y-1 list-disc list-inside">
                                    <li>Handled 30–50 customer cases daily.</li>
                                    <li>Maintained high data accuracy and efficiency.</li>
                                </ul>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Education -->
                <div>
                    <h2 class="text-3xl font-bold text-gis-dark mb-10 flex items-center gap-3">
                        <i class="fa-solid fa-graduation-cap text-gis-accent"></i> Education
                    </h2>
                    <div class="space-y-6">
                        <div class="bg-slate-50 p-6 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition">
                            <span class="inline-block px-3 py-1 bg-gis-accent/10 text-gis-accent rounded-full text-xs font-bold mb-3">Current</span>
                            <h3 class="font-bold text-xl text-gis-dark">Pre-Master in Human Geography (GIS)</h3>
                            <div class="text-slate-500 mt-1 flex items-center gap-2">
                                <i class="fa-solid fa-building-columns"></i> Tanta University
                            </div>
                            <p class="mt-3 text-slate-600 text-sm">Focusing on advanced spatial analysis, human geography applications, and modern cartographic methodologies.</p>
                        </div>

                        <div class="bg-slate-50 p-6 rounded-xl border border-slate-100 shadow-sm hover:shadow-md transition">
                            <span class="inline-block px-3 py-1 bg-slate-200 text-slate-600 rounded-full text-xs font-bold mb-3">Graduated</span>
                            <h3 class="font-bold text-xl text-gis-dark">Bachelor of Arts in Geography</h3>
                            <div class="text-gis-primary font-medium mt-1">GIS Division</div>
                            <div class="text-slate-500 mt-1 flex items-center gap-2">
                                <i class="fa-solid fa-building-columns"></i> Tanta University
                            </div>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Portfolio Gallery -->
    <section id="portfolio" class="py-20 bg-slate-900 text-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl font-bold mb-4">Featured GIS Projects</h2>
                <div class="w-20 h-1 bg-gis-accent mx-auto rounded mb-6"></div>
                <p class="text-slate-400 max-w-2xl mx-auto">A selection of my recent work in digital mapping and spatial analysis.</p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Project 1 -->
                <div class="group relative rounded-2xl overflow-hidden bg-slate-800 border border-slate-700">
                    <!-- Placeholder for Map Image -->
                    <div class="aspect-video bg-slate-700 flex flex-col items-center justify-center text-slate-500 relative">
                        <i class="fa-regular fa-image text-4xl mb-2"></i>
                        <span class="text-sm">Add Map Image Here</span>
                        <!-- To add image, use an img tag like this: -->
                        <!-- <img src="your-map-image.jpg" class="absolute inset-0 w-full h-full object-cover opacity-80 group-hover:opacity-100 transition duration-500"> -->
                    </div>
                    <div class="p-6">
                        <div class="text-gis-accent text-sm font-bold mb-2">Creativa Program</div>
                        <h3 class="text-xl font-bold mb-3">Land Use & Population Density Mapping</h3>
                        <p class="text-slate-400 text-sm mb-4">Produced detailed thematic maps for land use and population distribution, utilizing rigorous data cleaning techniques to reduce spatial errors by 25%.</p>
                        <div class="flex gap-2">
                            <span class="px-2 py-1 bg-slate-700 rounded text-xs font-medium">ArcGIS</span>
                            <span class="px-2 py-1 bg-slate-700 rounded text-xs font-medium">QGIS</span>
                        </div>
                    </div>
                </div>

                <!-- Project 2 -->
                <div class="group relative rounded-2xl overflow-hidden bg-slate-800 border border-slate-700">
                    <!-- Placeholder for Map Image -->
                    <div class="aspect-video bg-slate-700 flex flex-col items-center justify-center text-slate-500 relative">
                        <i class="fa-regular fa-map text-4xl mb-2"></i>
                        <span class="text-sm">Add Digitzing/Map Image Here</span>
                    </div>
                    <div class="p-6">
                        <div class="text-gis-accent text-sm font-bold mb-2">GIS Gate</div>
                        <h3 class="text-xl font-bold mb-3">Spatial Data Digitization</h3>
                        <p class="text-slate-400 text-sm mb-4">Digitized multiple spatial layers from field data collection. Contributed directly to the creation of over 10 operational maps for internal surveying projects.</p>
                        <div class="flex gap-2">
                            <span class="px-2 py-1 bg-slate-700 rounded text-xs font-medium">Digitization</span>
                            <span class="px-2 py-1 bg-slate-700 rounded text-xs font-medium">GPS</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-gis-primary">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center text-white">
            <i class="fa-regular fa-paper-plane text-5xl mb-6 opacity-90"></i>
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Ready to collaborate?</h2>
            <p class="text-xl text-sky-100 mb-10">I'm currently looking for new opportunities in the GIS field. Let's discuss how my analytical skills can bring value to your team.</p>
            
            <div class="flex flex-col md:flex-row justify-center items-center gap-6 mb-12">
                <a href="mailto:UG_31110352@art.tanta.edu.eg" class="flex items-center gap-3 bg-white text-gis-primary px-8 py-4 rounded-full font-bold text-lg hover:bg-sky-50 transition shadow-lg w-full md:w-auto justify-center">
                    <i class="fa-solid fa-envelope"></i> Email Me
                </a>
                <!-- You can update this href with your actual LinkedIn link -->
                <a href="#" class="flex items-center gap-3 bg-gis-dark text-white px-8 py-4 rounded-full font-bold text-lg hover:bg-slate-800 transition shadow-lg border border-slate-700 w-full md:w-auto justify-center">
                    <i class="fa-brands fa-linkedin"></i> LinkedIn
                </a>
            </div>
            
            <div class="flex items-center justify-center gap-2 text-sky-100">
                <i class="fa-solid fa-location-dot"></i> Tanta, Egypt
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gis-dark text-slate-400 py-8 text-center">
        <div class="max-w-6xl mx-auto px-4">
            <p>&copy; 2024 Rehab Sherif Shaban. All Rights Reserved.</p>
            <p class="text-sm mt-2">GIS & Surveying Specialist</p>
        </div>
    </footer>

</body>
</html>
