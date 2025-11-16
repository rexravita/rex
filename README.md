<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Rex Ravita II - [Windows XP Style]</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://unpkg.com/lucide@latest"></script>
    
    <!-- Custom Windows XP Styling -->
    <style>
        /* Define XP Colors and Font */
        .xp-bg { background-color: #ECE9D8; }
        .xp-window-bg { background-color: #FFFFFF; }
        .xp-title-blue { 
            background: linear-gradient(to bottom, #0A246A 0%, #3A6EA5 100%);
            color: white;
            font-family: Tahoma, sans-serif; 
        }
        .xp-border { border: 1px solid #000000; box-shadow: 2px 2px 0 0 #D4D0C8; }
        .xp-button {
            background-color: #ECE9D8;
            border: 1px solid #808080;
            box-shadow: 1px 1px 0 0 #FFFFFF, inset 1px 1px 0 0 #D4D0C8, inset -1px -1px 0 0 #808080;
            transition: all 0.05s;
        }
        .xp-button:hover {
            background-color: #D4D0C8;
        }
        .xp-button:active {
            box-shadow: inset 1px 1px 0 0 #808080, inset -1px -1px 0 0 #FFFFFF;
        }
        .xp-status-bar { border-top: 1px solid #808080; background-color: #ECE9D8; }
    </style>
    
    <!-- Tailwind Configuration (minimal overlap) -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Tahoma', 'Arial', 'sans-serif'], /* Prefer XP-era font */
                    }
                }
            }
        }
    </script>
</head>

<body class="xp-bg min-h-screen text-gray-800 p-4 md:p-8">

    <!-- Desktop Area -->
    <div class="max-w-7xl mx-auto space-y-8">

        <!-- ============================================= -->
        <!-- 1. HERO/TITLE WINDOW -->
        <!-- ============================================= -->
        <div id="hero" class="w-full xp-border shadow-xl xp-window-bg">
            <div class="xp-title-blue p-2 flex justify-between items-center text-sm font-bold">
                <span><i data-lucide="monitor-dot" class="w-4 h-4 inline mr-2"></i>REX RAVITA II - Portfolio</span>
                <div class="flex space-x-1">
                    <button class="text-xs w-5 h-5 xp-button">_</button>
                    <button class="text-xs w-5 h-5 xp-button">□</button>
                    <button class="text-xs w-5 h-5 xp-button">X</button>
                </div>
            </div>
            <div class="p-8 text-center">
                <p class="text-xs text-blue-700 font-bold uppercase tracking-widest mb-2">Howdy! I'm Rex Ravita II</p>
                <h1 class="text-4xl md:text-5xl font-extrabold leading-tight mb-4 text-gray-900">
                    Visual Storyteller & <span class="text-blue-700">Digital Growth Leader</span>
                </h1>
                <h2 class="text-lg md:text-xl text-gray-600 mb-8 max-w-3xl mx-auto border-t border-b py-2 border-gray-300">
                    Social Media Manager | Content Creator | Graphic Designer
                </h2>
                <div class="flex justify-center space-x-4">
                    <a href="#projects" class="xp-button text-sm font-bold py-2 px-6">
                        View Projects
                    </a>
                    <a href="#contact" class="xp-button text-sm font-bold py-2 px-6">
                        Contact Me
                    </a>
                </div>
            </div>
        </div>

        <!-- ============================================= -->
        <!-- 2. MAIN CONTENT WINDOW (ABOUT & PROJECTS) -->
        <!-- ============================================= -->
        <div class="w-full xp-border shadow-xl xp-window-bg">
            <div class="xp-title-blue p-2 flex justify-between items-center text-sm font-bold">
                <span><i data-lucide="folder" class="w-4 h-4 inline mr-2"></i>My Professional Files</span>
                <div class="flex space-x-1">
                    <button class="text-xs w-5 h-5 xp-button">_</button>
                    <button class="text-xs w-5 h-5 xp-button">□</button>
                    <button class="text-xs w-5 h-5 xp-button">X</button>
                </div>
            </div>
            
            <div class="p-6 space-y-12">

                <!-- ABOUT ME SECTION -->
                <section id="about" class="md:grid md:grid-cols-3 gap-8 pb-6 border-b border-gray-200">
                    <div class="md:col-span-1 border-r border-gray-300 pr-4">
                        <h2 class="text-2xl font-bold text-blue-700 mb-4 flex items-center"><i data-lucide="user-square" class="w-5 h-5 mr-2"></i>About Me</h2>
                        <div class="bg-gray-100 p-4 rounded-sm xp-border shadow-inner">
                            <h3 class="text-lg font-semibold mb-2 text-gray-800">Core Expertise</h3>
                            <ul class="space-y-1 text-sm text-gray-600">
                                <li class="flex items-center"><i data-lucide="check" class="w-4 h-4 text-green-600 mr-2"></i>Social Media Strategy</li>
                                <li class="flex items-center"><i data-lucide="check" class="w-4 h-4 text-green-600 mr-2"></i>Content Creation (UGC)</li>
                                <li class="flex items-center"><i data-lucide="check" class="w-4 h-4 text-green-600 mr-2"></i>Video & Audio Production</li>
                                <li class="flex items-center"><i data-lucide="check" class="w-4 h-4 text-green-600 mr-2"></i>Graphic Design & Identity</li>
                                <li class="flex items-center"><i data-lucide="check" class="w-4 h-4 text-green-600 mr-2"></i>Community Growth</li>
                            </ul>
                        </div>
                    </div>
                    
                    <div class="md:col-span-2 mt-6 md:mt-0 space-y-4 text-gray-700">
                        <p>
                            I’m Rex Ravita II, a content creator and social media manager with a passion for turning ideas into scroll-stopping stories. I’ve managed digital strategy and visual content for brands like **NewsRadio 1080 KRLD** and **Footprint Project**.
                        </p>
                        <p>
                            I currently lead social media at **Clapper**, helping the app grow its community and voice through bold, engaging content. Whether I’m behind the camera or behind the scenes, I’m driven by constantly finding fresh, creative ways to tell stories across every medium.
                        </p>
                    </div>
                </section>

                <!-- PROJECTS SECTION -->
                <section id="projects" class="py-6">
                    <h2 class="text-2xl font-bold text-blue-700 mb-6 flex items-center"><i data-lucide="layout-grid" class="w-5 h-5 mr-2"></i>Featured Projects</h2>
                    
                    <div class="grid sm:grid-cols-2 lg:grid-cols-3 gap-4">
                        
                        <!-- Project Card 1: Clapper -->
                        <div class="xp-window-bg p-4 xp-border shadow-md">
                            <h3 class="text-lg font-bold mb-1 text-blue-800">Clapper - Social Media Growth</h3>
                            <p class="text-xs text-gray-600 mb-3">Leading content strategy, managing community engagement, and driving platform growth for a fast-growing social media platform.</p>
                            <div class="flex flex-wrap gap-1 mb-3">
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">SMM</span>
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Community Growth</span>
                            </div>
                            <a href="#clapper-details" class="xp-button text-xs font-bold py-1 px-3 inline-block">View Details</a>
                        </div>

                        <!-- Project Card 2: NewsRadio 1080 KRLD -->
                        <div class="xp-window-bg p-4 xp-border shadow-md">
                            <h3 class="text-lg font-bold mb-1 text-blue-800">KRLD Visual Identity & Digital Content</h3>
                            <p class="text-xs text-gray-600 mb-3">Developed the visual brand identity and optimized news stories for social audiences, expanding their local presence digitally.</p>
                            <div class="flex flex-wrap gap-1 mb-3">
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">News Media</span>
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Visual Identity</span>
                            </div>
                            <a href="https://www.audacy.com/krld/authors/rex-ravita-ii" target="_blank" rel="noopener noreferrer" class="xp-button text-xs font-bold py-1 px-3 inline-block">View Articles</a>
                        </div>

                        <!-- Project Card 3: Footprint Project -->
                        <div class="xp-window-bg p-4 xp-border shadow-md">
                            <h3 class="text-lg font-bold mb-1 text-blue-800">Footprint Project - Disaster Response</h3>
                            <p class="text-xs text-gray-600 mb-3">Managed social media, highlighting disaster response efforts and the innovative use of renewable energy in relief work.</p>
                            <div class="flex flex-wrap gap-1 mb-3">
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Nonprofit</span>
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Disaster Relief</span>
                            </div>
                            <a href="#footprint-details" class="xp-button text-xs font-bold py-1 px-3 inline-block">View Case Study</a>
                        </div>

                        <!-- Project Card 4: Cosmic Sense -->
                        <div class="xp-window-bg p-4 xp-border shadow-md">
                            <h3 class="text-lg font-bold mb-1 text-blue-800">Cosmic Sense Feature</h3>
                            <p class="text-xs text-gray-600 mb-3">Conceptualized and produced a weekly national feature covering space, including audio, video, and visual components.</p>
                            <div class="flex flex-wrap gap-1 mb-3">
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Original Content</span>
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Audio Production</span>
                            </div>
                            <a href="https://www.youtube.com/watch?v=l0fshzzui5c&t=633s" target="_blank" rel="noopener noreferrer" class="xp-button text-xs font-bold py-1 px-3 inline-block">Watch Videos</a>
                        </div>
                        
                        <!-- Project Card 5: Short-Form Video & UGC -->
                        <div class="xp-window-bg p-4 xp-border shadow-md">
                            <h3 class="text-lg font-bold mb-1 text-blue-800">Short-Form Video Strategy</h3>
                            <p class="text-xs text-gray-600 mb-3">Pioneered vertical video strategy (TikTok, Reels, Shorts) to increase engagement across platforms.</p>
                            <div class="flex flex-wrap gap-1 mb-3">
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Video Strategy</span>
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">UGC Campaigns</span>
                            </div>
                            <a href="https://www.instagram.com/reel/C5WXEApuKXN/" target="_blank" rel="noopener noreferrer" class="xp-button text-xs font-bold py-1 px-3 inline-block">View Reels</a>
                        </div>
                        
                        <!-- Project Card 6: Misc. Graphic Design -->
                        <div class="xp-window-bg p-4 xp-border shadow-md">
                            <h3 class="text-lg font-bold mb-1 text-blue-800">Miscellaneous Graphic Design</h3>
                            <p class="text-xs text-gray-600 mb-3">A curated selection of diverse graphic design projects, demonstrating versatility in visual communication and branding.</p>
                            <div class="flex flex-wrap gap-1 mb-3">
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Visual Comms</span>
                                <span class="text-xs bg-gray-200 text-gray-700 px-1.5 py-0.5 border border-gray-400">Branding</span>
                            </div>
                            <a href="mailto:rexravita@gmail.com" class="xp-button text-xs font-bold py-1 px-3 inline-block">Request Samples</a>
                        </div>
                        
                    </div>
                </section>
            </div>
            
            <!-- Status Bar -->
            <div class="xp-status-bar p-1.5 flex justify-between text-xs text-gray-700">
                <span>Ready.</span>
                <span>© 2025 Rex Ravita II</span>
            </div>
        </div>

        <!-- ============================================= -->
        <!-- 3. CONTACT DIALOG BOX -->
        <!-- ============================================= -->
        <div id="contact" class="max-w-xl mx-auto xp-border shadow-xl xp-window-bg">
            <div class="xp-title-blue p-2 flex justify-between items-center text-sm font-bold">
                <span><i data-lucide="mail" class="w-4 h-4 inline mr-2"></i>Contact Dialog - Get In Touch</span>
                <div class="flex space-x-1">
                    <button class="text-xs w-5 h-5 xp-button">X</button>
                </div>
            </div>
            <div class="p-6">
                <p class="text-center text-sm text-gray-600 mb-4">Let's collaborate on your next digital project. Send me a message directly!</p>
                
                <form id="contact-form" class="space-y-4">
                    <div>
                        <label for="name" class="block text-xs font-medium text-gray-700 mb-1">Your Name:</label>
                        <input type="text" id="name" required class="w-full p-2 text-sm border border-gray-500 bg-white shadow-inner focus:outline-none">
                    </div>
                    <div>
                        <label for="email" class="block text-xs font-medium text-gray-700 mb-1">Your Email:</label>
                        <input type="email" id="email" required class="w-full p-2 text-sm border border-gray-500 bg-white shadow-inner focus:outline-none">
                    </div>
                    <div>
                        <label for="message" class="block text-xs font-medium text-gray-700 mb-1">Message:</label>
                        <textarea id="message" rows="4" required class="w-full p-2 text-sm border border-gray-500 bg-white shadow-inner focus:outline-none"></textarea>
                    </div>
                    <div class="flex justify-end space-x-2 pt-2">
                        <button type="submit" class="xp-button text-sm font-bold py-1.5 px-6">
                            Send Message
                        </button>
                        <a href="mailto:rexravita@gmail.com" class="xp-button text-sm font-bold py-1.5 px-6">
                            Email Directly
                        </a>
                    </div>
                </form>
            </div>
        </div>
        
    </div>

    <!-- JavaScript for Icon Initialization and Form Handling -->
    <script>
        // Initialize Lucide Icons
        lucide.createIcons();

        // Custom Message Box (Windows XP Dialog Box Style)
        function showMessage(title, message, isSuccess = true) {
            const icon = isSuccess ? '<i data-lucide="check" class="w-8 h-8 text-green-600 mr-4"></i>' : '<i data-lucide="alert-triangle" class="w-8 h-8 text-red-600 mr-4"></i>';
            
            const messageBox = document.createElement('div');
            messageBox.innerHTML = `
                <div class="fixed inset-0 bg-black/30 z-[100] flex items-center justify-center p-4">
                    <div class="xp-window-bg p-1 xp-border shadow-xl max-w-sm w-full">
                        <div class="xp-title-blue p-2 flex justify-between items-center text-sm font-bold">
                            <span>System Message</span>
                            <button onclick="this.closest('.fixed').remove()" class="text-xs w-5 h-5 xp-button">X</button>
                        </div>
                        <div class="p-6 text-center">
                            <h4 class="text-base font-bold mb-4 text-gray-900">${title}</h4>
                            <div class="flex items-center justify-center mb-6">
                                ${icon}
                                <p class="text-sm text-gray-700">${message}</p>
                            </div>
                            <button onclick="this.closest('.fixed').remove()" class="xp-button text-sm font-bold py-1.5 px-6">
                                OK
                            </button>
                        </div>
                    </div>
                </div>
            `;
            document.body.appendChild(messageBox);
            lucide.createIcons();
        }

        // Form submission handler
        document.getElementById('contact-form').addEventListener('submit', function(e) {
            e.preventDefault();
            showMessage('Message Sent', 'Your query was sent successfully. I will respond to your email shortly.', true);
            e.target.reset();
        });
    </script>
</body>
</html>
