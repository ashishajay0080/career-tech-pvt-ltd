<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Career Tech Pvt. Ltd. - Launch Your Future</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        :root {
            --primary: #002F6C;
            --accent: #3BB3E4;
            --gray-bg: #E0E0E0;
        }
        body {
            font-family: 'Roboto', sans-serif;
        }
        .heading {
            font-family: 'Poppins', sans-serif;
        }
        .hero-bg {
            background: linear-gradient(rgba(0, 47, 108, 0.8), rgba(0, 47, 108, 0.8)), 
                        url('https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f0cb8e6b-1e25-441c-870a-d0d950dc50ce.png') no-repeat center center/cover;
        }
        .service-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
        }
        .opportunity-card:hover {
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.1);
        }
        .ticker-item {
            animation: ticker 15s linear infinite;
        }
        @keyframes ticker {
            0% { transform: translateX(100%); }
            100% { transform: translateX(-100%); }
        }
        .accordion-content {
            max-height: 0;
            overflow: hidden;
            transition: max-height 0.3s ease-out;
        }
        .toggle-chevron {
            transition: transform 0.3s ease;
        }
        .toggle-chevron.active {
            transform: rotate(180deg);
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-md sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between h-16">
                <div class="flex items-center">
                    <div class="flex-shrink-0 flex items-center">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/fc426719-bcab-4fe6-9156-798b72b8dc9a.png" alt="Career Tech logo with blue and white design" class="h-8 w-auto">
                        <span class="ml-2 heading text-xl text-[#002F6C]">Career Tech</span>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-8">
                    <a href="#home" class="text-[#002F6C] hover:text-[#3BB3E4] px-3 py-2 font-medium">Home</a>
                    <a href="#services" class="text-[#002F6C] hover:text-[#3BB3E4] px-3 py-2 font-medium">Services</a>
                    <a href="#opportunities" class="text-[#002F6C] hover:text-[#3BB3E4] px-3 py-2 font-medium">Opportunities</a>
                    <a href="#about" class="text-[#002F6C] hover:text-[#3BB3E4] px-3 py-2 font-medium">About</a>
                    <a href="#contact" class="text-[#002F6C] hover:text-[#3BB3E4] px-3 py-2 font-medium">Contact</a>
                    <a href="#login" class="bg-[#3BB3E4] text-white px-4 py-2 rounded-md hover:bg-[#002F6C]">Login</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button id="mobile-menu-button" class="text-[#002F6C] hover:text-[#3BB3E4] focus:outline-none">
                        <svg class="h-6 w-6" fill="none" viewBox="0 0 24 24" stroke="currentColor">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
        
        <!-- Mobile menu -->
        <div id="mobile-menu" class="hidden md:hidden bg-white">
            <div class="px-2 pt-2 pb-3 space-y-1 sm:px-3">
                <a href="#home" class="text-[#002F6C] block px-3 py-2 font-medium">Home</a>
                <a href="#services" class="text-[#002F6C] block px-3 py-2 font-medium">Services</a>
                <a href="#opportunities" class="text-[#002F6C] block px-3 py-2 font-medium">Opportunities</a>
                <a href="#about" class="text-[#002F6C] block px-3 py-2 font-medium">About</a>
                <a href="#contact" class="text-[#002F6C] block px-3 py-2 font-medium">Contact</a>
                <a href="#login" class="block bg-[#3BB3E4] text-white px-3 py-2 rounded-md w-max">Login</a>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="hero-bg text-white py-20 md:py-32">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="md:flex items-center">
                <div class="md:w-1/2 mb-10 md:mb-0">
                    <h1 class="heading text-4xl md:text-5xl lg:text-6xl font-bold mb-4">Launch Your Future with Career Tech</h1>
                    <p class="text-xl mb-8">We bridge the gap between education and employment through quality training programs, internships, and job placement assistance.</p>
                    <div class="flex flex-col sm:flex-row space-y-4 sm:space-y-0 sm:space-x-4">
                        <a href="#services" class="bg-[#3BB3E4] hover:bg-[#002F6C] text-white px-6 py-3 rounded-md text-center font-medium">Explore Services</a>
                        <a href="#contact" class="bg-white hover:bg-gray-100 text-[#002F6C] px-6 py-3 rounded-md text-center font-medium">Contact Us</a>
                    </div>
                </div>
                <div class="md:w-1/2 flex justify-center">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/0aaa44a9-2fc4-4ed1-80e2-32ab96e32f7b.png" alt="Students and professionals engaged in learning and career development activities" class="rounded-lg shadow-xl max-w-full h-auto">
                </div>
            </div>
        </div>
    </section>

    <!-- Features Bar -->
    <div class="bg-[#002F6C] text-white py-2">
        <div class="max-w-7xl mx-auto px-4 overflow-hidden">
            <div class="flex space-x-8 whitespace-nowrap">
                <div class="ticker-item inline-block px-8">
                    <i class="fas fa-bullhorn mr-2"></i> Internship Deadlines Approaching • 
                </div>
                <div class="ticker-item inline-block px-8">
                    <i class="fas fa-calendar-alt mr-2"></i> New Training Batch Starting June 15 • 
                </div>
                <div class="ticker-item inline-block px-8">
                    <i class="fas fa-certificate mr-2"></i> 500+ Certificates Issued Last Month • 
                </div>
                <div class="ticker-item inline-block px-8">
                    <i class="fas fa-handshake mr-2"></i> 50+ New Industry Partners Joined •
                </div>
            </div>
        </div>
    </div>

    <!-- Featured Programs -->
    <section class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="heading text-3xl md:text-4xl font-bold text-[#002F6C] mb-4 text-center">Featured Programs</h2>
                <p class="max-w-2xl mx-auto text-gray-600">Our most popular programs with guaranteed placement support</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Program 1 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden service-card transition duration-300">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/24817a8e-cf8f-4c5e-ae20-81d93d8fe174.png" alt="Students learning web development through online course with instructor" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex items-center mb-2">
                            <span class="bg-[#3BB3E4] text-white text-xs px-3 py-1 rounded-full">IT</span>
                            <span class="ml-auto text-sm text-gray-500"><i class="fas fa-clock mr-1"></i> 12 Weeks</span>
                        </div>
                        <h3 class="text-xl font-bold text-[#002F6C] mb-2">Full Stack Web Development</h3>
                        <p class="text-gray-600 mb-4">Master HTML, CSS, JavaScript, React, Node.js and MongoDB to build complete web applications.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-[#3BB3E4] font-medium"><i class="fas fa-rupee-sign mr-1"></i> 25,000</span>
                            <a href="#" class="text-[#002F6C] hover:underline">Learn More →</a>
                        </div>
                    </div>
                </div>
                
                <!-- Program 2 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden service-card transition duration-300">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/218d68e0-aae4-414f-82a4-04082f39c8a4.png" alt="Data scientist analyzing complex data visualizations on computer screens" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex items-center mb-2">
                            <span class="bg-[#3BB3E4] text-white text-xs px-3 py-1 rounded-full">Analytics</span>
                            <span class="ml-auto text-sm text-gray-500"><i class="fas fa-clock mr-1"></i> 16 Weeks</span>
                        </div>
                        <h3 class="text-xl font-bold text-[#002F6C] mb-2">Data Science & Analytics</h3>
                        <p class="text-gray-600 mb-4">Learn Python, SQL, machine learning, and data visualization tools to analyze complex datasets.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-[#3BB3E4] font-medium"><i class="fas fa-rupee-sign mr-1"></i> 35,000</span>
                            <a href="#" class="text-[#002F6C] hover:underline">Learn More →</a>
                        </div>
                    </div>
                </div>
                
                <!-- Program 3 -->
                <div class="bg-white rounded-xl shadow-md overflow-hidden service-card transition duration-300">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/36379672-6dfb-4980-aa0d-4b2c626715b5.png" alt="Marketing team reviewing campaign performance on digital dashboard" class="w-full h-48 object-cover">
                    <div class="p-6">
                        <div class="flex items-center mb-2">
                            <span class="bg-[#3BB3E4] text-white text-xs px-3 py-1 rounded-full">Marketing</span>
                            <span class="ml-auto text-sm text-gray-500"><i class="fas fa-clock mr-1"></i> 8 Weeks</span>
                        </div>
                        <h3 class="text-xl font-bold text-[#002F6C] mb-2">Digital Marketing Certification</h3>
                        <p class="text-gray-600 mb-4">Master SEO, social media marketing, Google Ads, and analytics to drive business growth.</p>
                        <div class="flex justify-between items-center">
                            <span class="text-[#3BB3E4] font-medium"><i class="fas fa-rupee-sign mr-1"></i> 18,000</span>
                            <a href="#" class="text-[#002F6C] hover:underline">Learn More →</a>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#services" class="inline-flex items-center px-6 py-3 border border-[#002F6C] text-[#002F6C] rounded-md hover:bg-[#002F6C] hover:text-white transition duration-300">
                    View All Programs
                    <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                    </svg>
                </a>
            </div>
        </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-left mb-12">
                <h2 class="heading text-3xl md:text-4xl font-bold text-[#002F6C] mb-4">Our Services</h2>
                <p class="max-w-2xl mx-auto text-gray-600">Comprehensive career solutions to help you achieve your professional goals</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
                <!-- Education Programs -->
                <div class="bg-white rounded-xl shadow-md p-6">
                    <div class="flex items-start mb-4">
                        <div class="bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                            <i class="fas fa-graduation-cap text-[#3BB3E4] text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#002F6C]">Education Programs</h3>
                            <p class="text-gray-600">Quality education for academic and professional growth</p>
                        </div>
                    </div>
                    <div class="pl-16">
                        <ul class="list-disc text-gray-700 space-y-2 mb-4">
                            <li>Online & Offline Certification</li>
                            <li>Academic Support for Students</li>
                            <li>Degree Enhancement Programs</li>
                            <li>Soft Skills Development</li>
                        </ul>
                        <a href="#" class="text-[#3BB3E4] hover:underline font-medium">Learn more →</a>
                    </div>
                </div>
                
                <!-- Skill Training -->
                <div class="bg-white rounded-xl shadow-md p-6">
                    <div class="flex items-start mb-4">
                        <div class="bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                            <i class="fas fa-laptop-code text-[#3BB3E4] text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#002F6C]">Skill Training</h3>
                            <p class="text-gray-600">Industry-relevant skills for today's job market</p>
                        </div>
                    </div>
                    <div class="pl-16">
                        <ul class="list-disc text-gray-700 space-y-2 mb-4">
                            <li>IT (Web, Cybersecurity, Data)</li>
                            <li>Healthcare Training Programs</li>
                            <li>Engineering Certifications</li>
                            <li>Trade Skills Development</li>
                        </ul>
                        <a href="#" class="text-[#3BB3E4] hover:underline font-medium">Learn more →</a>
                    </div>
                </div>
                
                <!-- Internships -->
                <div class="bg-white rounded-xl shadow-md p-6">
                    <div class="flex items-start mb-4">
                        <div class="bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                            <i class="fas fa-briefcase text-[#3BB3E4] text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#002F6C]">Internships</h3>
                            <p class="text-gray-600">Hands-on experience with leading companies</p>
                        </div>
                    </div>
                    <div class="pl-16">
                        <ul class="list-disc text-gray-700 space-y-2 mb-4">
                            <li>Ongoing Internship Batches</li>
                            <li>Company Tie-ups</li>
                            <li>Stipend and Non-Stipend Options</li>
                            <li>International Internship Opportunities</li>
                        </ul>
                        <a href="#opportunities" class="text-[#3BB3E4] hover:underline font-medium">Browse internships →</a>
                    </div>
                </div>
                
                <!-- Job Placement -->
                <div class="bg-white rounded-xl shadow-md p-6">
                    <div class="flex items-start mb-4">
                        <div class="bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                            <i class="fas fa-user-tie text-[#3BB3E4] text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#002F6C]">Job Placement</h3>
                            <p class="text-gray-600">Launch your career with our network</p>
                        </div>
                    </div>
                    <div class="pl-16">
                        <ul class="list-disc text-gray-700 space-y-2 mb-4">
                            <li>Resume Submission Portal</li>
                            <li>Industry Partnerships</li>
                            <li>Job Matching Services</li>
                            <li>Career Counseling</li>
                        </ul>
                        <a href="#opportunities" class="text-[#3BB3E4] hover:underline font-medium">Browse jobs →</a>
                    </div>
                </div>
                
                <!-- Career Support -->
                <div class="bg-white rounded-xl shadow-md p-6">
                    <div class="flex items-start mb-4">
                        <div class="bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                            <i class="fas fa-handshake text-[#3BB3E4] text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#002F6C]">Career Support</h3>
                            <p class="text-gray-600">Personalized guidance for your career journey</p>
                        </div>
                    </div>
                    <div class="pl-16">
                        <ul class="list-disc text-gray-700 space-y-2 mb-4">
                            <li>Resume Building</li>
                            <li>Interview Preparation</li>
                            <li>Mock Interview Booking</li>
                            <li>Career Path Guidance</li>
                        </ul>
                        <a href="#" class="text-[#3BB3E4] hover:underline font-medium">Book session →</a>
                    </div>
                </div>
                
                <!-- Refer & Earn -->
                <div class="bg-white rounded-xl shadow-md p-6">
                    <div class="flex items-start mb-4">
                        <div class="bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                            <i class="fas fa-gift text-[#3BB3E4] text-xl"></i>
                        </div>
                        <div>
                            <h3 class="text-xl font-bold text-[#002F6C]">Refer & Earn</h3>
                            <p class="text-gray-600">Share opportunities and get rewarded</p>
                        </div>
                    </div>
                    <div class="pl-16">
                        <p class="text-gray-700 mb-4">Invite friends & get referral rewards when they enroll in any program.</p>
                        <a href="#" class="text-[#3BB3E4] hover:underline font-medium">View program →</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Opportunities Section -->
    <section id="opportunities" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="heading text-3xl md:text-4xl font-bold text-[#002F6C] mb-4">Current Opportunities</h2>
                <p class="max-w-2xl mx-auto text-gray-600">Browse through our latest job and internship openings</p>
            </div>
            
            <!-- Filters -->
            <div class="bg-[#E0E0E0] p-4 rounded-lg mb-8">
                <div class="grid grid-cols-1 md:grid-cols-4 gap-4">
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-1">Domain</label>
                        <select class="w-full rounded-md border-gray-300 shadow-sm focus:border-[#3BB3E4] focus:ring focus:ring-[#3BB3E4] focus:ring-opacity-50 text-sm">
                            <option>All Domains</option>
                            <option>IT/Software</option>
                            <option>Marketing</option>
                            <option>Healthcare</option>
                            <option>Engineering</option>
                            <option>Business</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-1">Location</label>
                        <select class="w-full rounded-md border-gray-300 shadow-sm focus:border-[#3BB3E4] focus:ring focus:ring-[#3BB3E4] focus:ring-opacity-50 text-sm">
                            <option>All Locations</option>
                            <option>Remote</option>
                            <option>Delhi/NCR</option>
                            <option>Bangalore</option>
                            <option>Mumbai</option>
                            <option>Hyderabad</option>
                        </select>
                    </div>
                    <div>
                        <label class="block text-sm font-medium text-gray-700 mb-1">Type</label>
                        <select class="w-full rounded-md border-gray-300 shadow-sm focus:border-[#3BB3E4] focus:ring focus:ring-[#3BB3E4] focus:ring-opacity-50 text-sm">
                            <option>All Types</option>
                            <option>Internship</option>
                            <option>Full-time</option>
                            <option>Part-time</option>
                            <option>Training Program</option>
                        </select>
                    </div>
                    <div class="flex items-end">
                        <button class="w-full bg-[#3BB3E4] hover:bg-[#002F6C] text-white py-2 px-4 rounded-md text-sm font-medium transition duration-300">
                            Search Opportunities
                        </button>
                    </div>
                </div>
            </div>
            
            <!-- Opportunity Listings -->
            <div class="grid grid-cols-1 gap-6">
                <!-- Opportunity 1 -->
                <div class="opportunity-card bg-white rounded-lg shadow-sm overflow-hidden border border-gray-200 hover:border-[#3BB3E4] transition duration-300">
                    <div class="p-4 border-b">
                        <div class="flex flex-col md:flex-row md:justify-between">
                            <div>
                                <h3 class="text-lg font-bold text-[#002F6C]">Frontend Developer</h3>
                                <div class="flex items-center text-sm text-gray-600 mt-1">
                                    <i class="fas fa-building mr-2"></i>
                                    Tech Solutions Inc.
                                </div>
                            </div>
                            <div class="mt-2 md:mt-0">
                                <span class="bg-[#002F6C] text-white text-xs px-3 py-1 rounded-full">Full-time</span>
                                <span class="ml-2 bg-green-100 text-green-800 text-xs px-3 py-1 rounded-full">Urgent</span>
                            </div>
                        </div>
                    </div>
                    <div class="p-4">
                        <p class="text-gray-700 mb-4">We're looking for a skilled Frontend Developer with 2+ years experience in React.js to join our product team. You'll work on building user interfaces for our SaaS platform.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">React</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">JavaScript</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">HTML/CSS</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Redux</span>
                        </div>
                        <div class="flex flex-col md:flex-row md:justify-between text-sm">
                            <div class="mb-2 md:mb-0">
                                <i class="fas fa-map-marker-alt text-[#3BB3E4] mr-1"></i>
                                <span>Bangalore (Remote possible)</span>
                            </div>
                            <div class="mb-2 md:mb-0">
                                <i class="fas fa-rupee-sign text-[#3BB3E4] mr-1"></i>
                                <span>4,00,000 - 6,00,000/year</span>
                            </div>
                            <div>
                                <i class="far fa-clock text-[#3BB3E4] mr-1"></i>
                                <span>Apply by Jun 15, 2023</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-gray-50 px-4 py-3 flex justify-end space-x-3">
                        <button class="text-[#002F6C] hover:text-[#3BB3E4] text-sm font-medium flex items-center">
                            <i class="far fa-bookmark mr-1"></i> Save
                        </button>
                        <button class="bg-[#3BB3E4] hover:bg-[#002F6C] text-white px-4 py-1 rounded-md text-sm font-medium transition duration-300">
                            Apply Now
                        </button>
                    </div>
                </div>
                
                <!-- Opportunity 2 -->
                <div class="opportunity-card bg-white rounded-lg shadow-sm overflow-hidden border border-gray-200 hover:border-[#3BB3E4] transition duration-300">
                    <div class="p-4 border-b">
                        <div class="flex flex-col md:flex-row md:justify-between">
                            <div>
                                <h3 class="text-lg font-bold text-[#002F6C]">Digital Marketing Intern</h3>
                                <div class="flex items-center text-sm text-gray-600 mt-1">
                                    <i class="fas fa-building mr-2"></i>
                                    Growth Marketing Ltd.
                                </div>
                            </div>
                            <div class="mt-2 md:mt-0">
                                <span class="bg-[#3BB3E4] text-white text-xs px-3 py-1 rounded-full">Internship</span>
                                <span class="ml-2 bg-yellow-100 text-yellow-800 text-xs px-3 py-1 rounded-full">Stipend</span>
                            </div>
                        </div>
                    </div>
                    <div class="p-4">
                        <p class="text-gray-700 mb-4">6-month internship opportunity for marketing students/graduates to learn hands-on digital marketing skills including SEO, social media, and content creation.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">SEO</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Social Media</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Content Writing</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Analytics</span>
                        </div>
                        <div class="flex flex-col md:flex-row md:justify-between text-sm">
                            <div class="mb-2 md:mb-0">
                                <i class="fas fa-map-marker-alt text-[#3BB3E4] mr-1"></i>
                                <span>Delhi (Hybrid)</span>
                            </div>
                            <div class="mb-2 md:mb-0">
                                <i class="fas fa-rupee-sign text-[#3BB3E4] mr-1"></i>
                                <span>10,000/month + Performance Bonus</span>
                            </div>
                            <div>
                                <i class="far fa-clock text-[#3BB3E4] mr-1"></i>
                                <span>Apply by Jun 30, 2023</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-gray-50 px-4 py-3 flex justify-end space-x-3">
                        <button class="text-[#002F6C] hover:text-[#3BB3E4] text-sm font-medium flex items-center">
                            <i class="far fa-bookmark mr-1"></i> Save
                        </button>
                        <button class="bg-[#3BB3E4] hover:bg-[#002F6C] text-white px-4 py-1 rounded-md text-sm font-medium transition duration-300">
                            Apply Now
                        </button>
                    </div>
                </div>
                
                <!-- Opportunity 3 -->
                <div class="opportunity-card bg-white rounded-lg shadow-sm overflow-hidden border border-gray-200 hover:border-[#3BB3E4] transition duration-300">
                    <div class="p-4 border-b">
                        <div class="flex flex-col md:flex-row md:justify-between">
                            <div>
                                <h3 class="text-lg font-bold text-[#002F6C]">Cybersecurity Certification</h3>
                                <div class="flex items-center text-sm text-gray-600 mt-1">
                                    <i class="fas fa-university mr-2"></i>
                                    Career Tech Academy
                                </div>
                            </div>
                            <div class="mt-2 md:mt-0">
                                <span class="bg-purple-100 text-purple-800 text-xs px-3 py-1 rounded-full">Training</span>
                                <span class="ml-2 bg-blue-100 text-blue-800 text-xs px-3 py-1 rounded-full">Placement</span>
                            </div>
                        </div>
                    </div>
                    <div class="p-4">
                        <p class="text-gray-700 mb-4">12-week intensive training program covering ethical hacking, network security, cryptography with hands-on labs and certification. Placement assistance provided.</p>
                        <div class="flex flex-wrap gap-2 mb-4">
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Ethical Hacking</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Network Security</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Cryptography</span>
                            <span class="bg-gray-100 text-gray-800 text-xs px-3 py-1 rounded-full">Pen Testing</span>
                        </div>
                        <div class="flex flex-col md:flex-row md:justify-between text-sm">
                            <div class="mb-2 md:mb-0">
                                <i class="fas fa-map-marker-alt text-[#3BB3E4] mr-1"></i>
                                <span>Online (Live Instructor)</span>
                            </div>
                            <div class="mb-2 md:mb-0">
                                <i class="fas fa-rupee-sign text-[#3BB3E4] mr-1"></i>
                                <span>35,000 (EMI Available)</span>
                            </div>
                            <div>
                                <i class="far fa-clock text-[#3BB3E4] mr-1"></i>
                                <span>Next Batch: Jul 10, 2023</span>
                            </div>
                        </div>
                    </div>
                    <div class="bg-gray-50 px-4 py-3 flex justify-end space-x-3">
                        <button class="text-[#002F6C] hover:text-[#3BB3E4] text-sm font-medium flex items-center">
                            <i class="far fa-bookmark mr-1"></i> Save
                        </button>
                        <button class="bg-[#3BB3E4] hover:bg-[#002F6C] text-white px-4 py-1 rounded-md text-sm font-medium transition duration-300">
                            View Details
                        </button>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-8">
                <button class="inline-flex items-center px-4 py-2 border border-[#002F6C] text-[#002F6C] rounded-md hover:bg-[#002F6C] hover:text-white transition duration-300">
                    Load More Opportunities
                    <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                        <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M19 9l-7 7-7-7"></path>
                    </svg>
                </button>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 bg-[#002F6C] text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-2 md:grid-cols-4 gap-8 text-center">
                <div>
                    <div class="text-4xl md:text-5xl font-bold mb-2">500+</div>
                    <div class="text-sm uppercase tracking-wider">Placements</div>
                </div>
                <div>
                    <div class="text-4xl md:text-5xl font-bold mb-2">100+</div>
                    <div class="text-sm uppercase tracking-wider">Partner Companies</div>
                </div>
                <div>
                    <div class="text-4xl md:text-5xl font-bold mb-2">2,000+</div>
                    <div class="text-sm uppercase tracking-wider">Trained Students</div>
                </div>
                <div>
                    <div class="text-4xl md:text-5xl font-bold mb-2">50+</div>
                    <div class="text-sm uppercase tracking-wider">Training Programs</div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials -->
    <section class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="heading text-3xl md:text-4xl font-bold text-[#002F6C] mb-4">Success Stories</h2>
                <p class="max-w-2xl mx-auto text-gray-600">What our students and partners say about us</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <!-- Testimonial 1 -->
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <div class="flex items-center mb-4">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/bca603cc-68bd-440d-82c7-a35e6f181b2b.png" alt="Smiling young woman in professional attire" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold text-[#002F6C]">Priya Sharma</h4>
                            <p class="text-sm text-gray-500">Web Developer at TechCorp</p>
                        </div>
                    </div>
                    <p class="text-gray-700 italic">"The Full Stack Developer program at Career Tech completely transformed my career. The hands-on projects and industry-relevant curriculum helped me land my dream job within 2 months of completing the course."</p>
                    <div class="mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testimonial 2 -->
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <div class="flex items-center mb-4">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/61f99043-72ae-459a-bf22-1bc7649bc53b.png" alt="Young man in business casual attire" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold text-[#002F6C]">Rahul Mehta</h4>
                            <p class="text-sm text-gray-500">Data Analyst at AnalyticsPro</p>
                        </div>
                    </div>
                    <p class="text-gray-700 italic">"Career Tech's placement team went above and beyond to prepare me for interviews. Their mock sessions and resume building workshop were instrumental in helping me transition into data analytics from my previous role."</p>
                    <div class="mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                    </div>
                </div>
                
                <!-- Testimonial 3 -->
                <div class="bg-white p-6 rounded-xl shadow-sm">
                    <div class="flex items-center mb-4">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/f7f5c244-77cd-4c97-8aab-616f4d112336.png" alt="Senior executive in formal business suit" class="w-12 h-12 rounded-full mr-4">
                        <div>
                            <h4 class="font-bold text-[#002F6C]">Neha Kapoor</h4>
                            <p class="text-sm text-gray-500">HR Manager at GrowthMarketing</p>
                        </div>
                    </div>
                    <p class="text-gray-700 italic">"We've been partnering with Career Tech for our hiring needs and have consistently found well-trained, job-ready candidates. Their internship-to-hire program has been particularly valuable for our team."</p>
                    <div class="mt-4 text-yellow-400">
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star"></i>
                        <i class="fas fa-star-half-alt"></i>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="md:flex items-center">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <h2 class="heading text-3xl md:text-4xl font-bold text-[#002F6C] mb-6">About Career Tech Pvt. Ltd.</h2>
                    <p class="text-gray-700 mb-4">Founded in 2015 by Ashish Ajay, Career Tech Pvt. Ltd. has established itself as a premier career development platform, offering education, training, internships and job placement services.</p>
                    <p class="text-gray-700 mb-6">Our mission is to empower individuals with the skills, knowledge, and opportunities they need to build successful careers in today's competitive job market.</p>
                    <div class="mb-6">
                        <h3 class="text-xl font-bold text-[#002F6C] mb-3 flex items-center">
                            <i class="fas fa-bullseye text-[#3BB3E4] mr-2"></i>
                            Our Vision
                        </h3>
                        <p class="text-gray-700 pl-8">To become India's most trusted career development partner, recognized for transforming education into employment opportunities.</p>
                    </div>
                    <div class="mb-6">
                        <h3 class="text-xl font-bold text-[#002F6C] mb-3 flex items-center">
                            <i class="fas fa-chart-line text-[#3BB3E4] mr-2"></i>
                            Our Approach
                        </h3>
                        <p class="text-gray-700 pl-8">We combine quality education with practical training, industry partnerships, and personalized career guidance to ensure our students' success.</p>
                    </div>
                    <a href="#contact" class="inline-flex items-center px-6 py-3 bg-[#3BB3E4] hover:bg-[#002F6C] text-white rounded-md font-medium transition duration-300">
                        Get in Touch
                        <svg class="ml-2 w-4 h-4" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M14 5l7 7m0 0l-7 7m7-7H3"></path>
                        </svg>
                    </a>
                </div>
                <div class="md:w-1/2">
                    <div class="relative">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/bbeea4ef-8375-43a2-a595-967babda12b8.png" alt="Career Tech team members collaborating in modern office" class="rounded-lg shadow-xl w-full">
                        <div class="absolute -bottom-6 -right-6 bg-[#3BB3E4] p-4 rounded-lg shadow-lg w-2/3">
                            <div class="flex items-center">
                                <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/e694f6e5-b0fa-409e-82a9-ce30c34448db.png" alt="Ashish Ajay, founder of Career Tech in professional portrait" class="w-16 h-16 rounded-full border-4 border-white mr-4">
                                <div>
                                    <h4 class="font-bold text-white">Ashish Ajay</h4>
                                    <p class="text-white text-sm">Founder & CEO</p>
                                    <div class="flex space-x-2 mt-1">
                                        <a href="#" class="text-white hover:text-gray-200"><i class="fab fa-linkedin"></i></a>
                                        <a href="#" class="text-white hover:text-gray-200"><i class="fab fa-twitter"></i></a>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Partners Section -->
    <section class="py-16 bg-gray-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="heading text-3xl md:text-4xl font-bold text-[#002F6C] mb-4">Our Partners</h2>
                <p class="max-w-2xl mx-auto text-gray-600">Trusted by leading companies and educational institutions</p>
            </div>
            
            <div class="grid grid-cols-2 md:grid-cols-4 lg:grid-cols-6 gap-8">
                <div class="flex items-center justify-center p-4 bg-white rounded shadow-sm">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/6e6e22b2-01e1-4341-8afa-ead1c13cf4c6.png" alt="TechCorp company logo" class="h-12 object-contain opacity-70 hover:opacity-100 transition duration-300">
                </div>
                <div class="flex items-center justify-center p-4 bg-white rounded shadow-sm">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/579272dc-b77d-49c5-ab9f-96bcc40f4826.png" alt="AnalyticsPro company logo" class="h-12 object-contain opacity-70 hover:opacity-100 transition duration-300">
                </div>
                <div class="flex items-center justify-center p-4 bg-white rounded shadow-sm">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/2236cdb2-ea02-4204-be18-81c0fdbe9b4a.png" alt="GrowthMarketing company logo" class="h-12 object-contain opacity-70 hover:opacity-100 transition duration-300">
                </div>
                <div class="flex items-center justify-center p-4 bg-white rounded shadow-sm">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/13eec447-2ab4-446a-9282-90f47bae7a1c.png" alt="EduNext educational institution logo" class="h-12 object-contain opacity-70 hover:opacity-100 transition duration-300">
                </div>
                <div class="flex items-center justify-center p-4 bg-white rounded shadow-sm">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/43878d21-7510-426e-a23c-d01dc276a051.png" alt="SecureIT cybersecurity company logo" class="h-12 object-contain opacity-70 hover:opacity-100 transition duration-300">
                </div>
                <div class="flex items-center justify-center p-4 bg-white rounded shadow-sm">
                    <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/6dee69a9-5611-4b49-a5f5-19fc0044ea4e.png" alt="DesignHub creative agency logo" class="h-12 object-contain opacity-70 hover:opacity-100 transition duration-300">
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <h2 class="heading text-3xl md:text-4xl font-bold text-[#002F6C] mb-4">Contact Us</h2>
                <p class="max-w-2xl mx-auto text-gray-600">Have questions? We're here to help guide your career journey</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <div>
                    <div class="bg-white rounded-xl shadow-sm p-6 mb-8">
                        <h3 class="text-xl font-bold text-[#002F6C] mb-6">Get In Touch</h3>
                        <form id="contactForm">
                            <div class="mb-4">
                                <label for="name" class="block text-sm font-medium text-gray-700 mb-1">Full Name</label>
                                <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-[#3BB3E4] focus:border-[#3BB3E4]" required>
                            </div>
                            <div class="mb-4">
                                <label for="email" class="block text-sm font-medium text-gray-700 mb-1">Email Address</label>
                                <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-[#3BB3E4] focus:border-[#3BB3E4]" required>
                            </div>
                            <div class="mb-4">
                                <label for="phone" class="block text-sm font-medium text-gray-700 mb-1">Phone Number</label>
                                <input type="tel" id="phone" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-[#3BB3E4] focus:border-[#3BB3E4]">
                            </div>
                            <div class="mb-4">
                                <label for="subject" class="block text-sm font-medium text-gray-700 mb-1">Subject</label>
                                <select id="subject" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-[#3BB3E4] focus:border-[#3BB3E4]">
                                    <option>General Inquiry</option>
                                    <option>Course Information</option>
                                    <option>Placement Assistance</option>
                                    <option>Partnership</option>
                                    <option>Other</option>
                                </select>
                            </div>
                            <div class="mb-6">
                                <label for="message" class="block text-sm font-medium text-gray-700 mb-1">Message</label>
                                <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-[#3BB3E4] focus:border-[#3BB3E4]"></textarea>
                            </div>
                            <button type="submit" class="w-full bg-[#3BB3E4] hover:bg-[#002F6C] text-white py-3 px-6 rounded-md font-medium transition duration-300">
                                Send Message
                            </button>
                        </form>
                    </div>
                    
                    <div class="flex justify-center">
                        <button class="flex items-center px-6 py-3 bg-green-500 hover:bg-green-600 text-white rounded-md font-medium transition duration-300">
                            <i class="fab fa-whatsapp mr-2 text-xl"></i>
                            Chat on WhatsApp
                        </button>
                    </div>
                </div>
                
                <div>
                    <div class="bg-white rounded-xl shadow-sm p-6 h-full">
                        <h3 class="text-xl font-bold text-[#002F6C] mb-6">Contact Information</h3>
                        
                        <div class="space-y-6">
                            <div class="flex">
                                <div class="flex-shrink-0 bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                                    <i class="fas fa-map-marker-alt text-[#3BB3E4] text-xl"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-[#002F6C] mb-1">Address</h4>
                                    <p class="text-gray-700">123 Career Plaza, Sector 15<br>Noida, Uttar Pradesh 201301</p>
                                </div>
                            </div>
                            
                            <div class="flex">
                                <div class="flex-shrink-0 bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                                    <i class="fas fa-phone-alt text-[#3BB3E4] text-xl"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-[#002F6C] mb-1">Phone</h4>
                                    <p class="text-gray-700">+91 7858078115<br>Support: +91 9876543210</p>
                                </div>
                            </div>
                            
                            <div class="flex">
                                <div class="flex-shrink-0 bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                                    <i class="fas fa-envelope text-[#3BB3E4] text-xl"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-[#002F6C] mb-1">Email</h4>
                                    <p class="text-gray-700">careertech26@gmail.com<br>contact@careerteach26.com</p>
                                </div>
                            </div>
                            
                            <div class="flex">
                                <div class="flex-shrink-0 bg-[#3BB3E4] bg-opacity-10 p-3 rounded-lg mr-4">
                                    <i class="fas fa-clock text-[#3BB3E4] text-xl"></i>
                                </div>
                                <div>
                                    <h4 class="font-bold text-[#002F6C] mb-1">Hours</h4>
                                    <p class="text-gray-700">Monday - Saturday: 9AM - 7PM<br>Sunday: Closed</p>
                                </div>
                            </div>
                        </div>
                        
                        <div class="mt-8 pt-6 border-t border-gray-200">
                            <h4 class="font-bold text-[#002F6C] mb-4">Follow Us</h4>
                            <div class="flex space-x-4">
                                <a href="#" class="bg-[#3BB3E4] bg-opacity-10 hover:bg-opacity-20 p-3 rounded-full text-[#3BB3E4] transition duration-300">
                                    <i class="fab fa-facebook-f"></i>
                                </a>
                                <a href="#" class="bg-[#3BB3E4] bg-opacity-10 hover:bg-opacity-20 p-3 rounded-full text-[#3BB3E4] transition duration-300">
                                    <i class="fab fa-twitter"></i>
                                </a>
                                <a href="#" class="bg-[#3BB3E4] bg-opacity-10 hover:bg-opacity-20 p-3 rounded-full text-[#3BB3E4] transition duration-300">
                                    <i class="fab fa-linkedin-in"></i>
                                </a>
                                <a href="#" class="bg-[#3BB3E4] bg-opacity-10 hover:bg-opacity-20 p-3 rounded-full text-[#3BB3E4] transition duration-300">
                                    <i class="fab fa-instagram"></i>
                                </a>
                                <a href="#" class="bg-[#3BB3E4] bg-opacity-10 hover:bg-opacity-20 p-3 rounded-full text-[#3BB3E4] transition duration-300">
                                    <i class="fab fa-youtube"></i>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- CTA Section -->
    <section class="py-16 bg-[#002F6C] text-white">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="heading text-3xl md:text-4xl font-bold mb-6">Ready to Launch Your Career?</h2>
            <p class="max-w-2xl mx-auto text-xl mb-8">Join thousands of students who transformed their careers with Career Tech</p>
            <div class="flex flex-col sm:flex-row justify-center space-y-4 sm:space-y-0 sm:space-x-4">
                <a href="#contact" class="bg-[#3BB3E4] hover:bg-white hover:text-[#002F6C] text-white px-8 py-3 rounded-md text-lg font-medium transition duration-300">Get Started</a>
                <a href="tel:+917858078115" class="bg-white hover:bg-gray-100 text-[#002F6C] px-8 py-3 rounded-md text-lg font-medium transition duration-300">
                    <i class="fas fa-phone mr-2"></i> Call Us Now
                </a>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <div class="flex items-center mb-4">
                        <img src="https://storage.googleapis.com/workspace-0f70711f-8b4e-4d94-86f1-2a93ccde5887/image/706e0712-5034-4303-bb80-458525431b58.png" alt="Career Tech small logo in footer" class="h-8 w-auto mr-2">
                        <span class="heading text-xl">Career Tech</span>
                    </div>
                    <p class="text-gray-400 mb-4">Launch Your Future with comprehensive career solutions including education, training, internships, and job placements.</p>
                    <p class="text-sm text-gray-500">© 2023 Career Tech Pvt. Ltd. All rights reserved.</p>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Quick Links</h3>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-white transition duration-300">Home</a></li>
                        <li><a href="#services" class="text-gray-400 hover:text-white transition duration-300">Services</a></li>
                        <li><a href="#opportunities" class="text-gray-400 hover:text-white transition duration-300">Opportunities</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-white transition duration-300">About Us</a></li>
                        <li><a href="#contact" class="text-gray-400 hover:text-white transition duration-300">Contact</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Services</h3>
                    <ul class="space-y-2">
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Education Programs</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Skill Training</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Internships</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Job Placement</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition duration-300">Career Support</a></li>
                    </ul>
                </div>
                
                <div>
                    <h3 class="text-lg font-bold mb-4">Contact</h3>
                    <address class="not-italic text-gray-400 space-y-2">
                        <p><i class="fas fa-map-marker-alt mr-2 text-[#3BB3E4]"></i> 123 Career Plaza, Sector 15, Noida</p>
                        <p><i class="fas fa-phone-alt mr-2 text-[#3BB3E4]"></i> +91 7858078115</p>
                        <p><i class="fas fa-envelope mr-2 text-[#3BB3E4]"></i> careertech26@gmail.com</p>
                    </address>
                    
                    <div class="mt-4">
                        <h4 class="font-medium mb-2">Subscribe to Newsletter</h4>
                        <div class="flex">
                            <input type="email" placeholder="Your email" class="px-3 py-2 text-gray-800 rounded-l-md w-full focus:outline-none">
                            <button class="bg-[#3BB3E4] hover:bg-[#002F6C] px-4 py-2 rounded-r-md transition duration-300">
                                <i class="fas fa-paper-plane"></i>
                            </button>
                        </div>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-8 pt-8 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-500 text-sm mb-4 md:mb-0">Website: <a href="https://www.careerteach26.com" class="hover:text-white" target="_blank">www.careerteach26.com</a></p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">Privacy Policy</a>
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">Terms of Service</a>
                    <a href="#" class="text-gray-400 hover:text-white transition duration-300">Sitemap</a>
                </div>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        document.getElementById('mobile-menu-button').addEventListener('click', function() {
            const menu = document.getElementById('mobile-menu');
            menu.classList.toggle('hidden');
        });

        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                const target = document.querySelector(this.getAttribute('href'));
                if (target) {
                    window.scrollTo({
                        top: target.offsetTop - 80,
                        behavior: 'smooth'
                    });
                    
                    // Close mobile menu if open
                    const mobileMenu = document.getElementById('mobile-menu');
                    if (!mobileMenu.classList.contains('hidden')) {
                        mobileMenu.classList.add('hidden');
                    }
                }
            });
        });

        // Accordion functionality for services
        document.querySelectorAll('.accordion-toggle').forEach(button => {
            button.addEventListener('click', function() {
                const content = this.nextElementSibling;
                const chevron = this.querySelector('.toggle-chevron');
                
                // Toggle chevron
                chevron.classList.toggle('active');
                
                // Toggle content
                if (content.style.maxHeight) {
                    content.style.maxHeight = null;
                } else {
                    content.style.maxHeight = content.scrollHeight + 'px';
                }
            });
        });

        // Hide splash screen after 3 seconds
        setTimeout(function() {
            document.getElementById('splash').style.display = 'none';
            document.getElementById('app').style.display = 'flex';
        }, 3000);
    </script>
</body>
</html>
