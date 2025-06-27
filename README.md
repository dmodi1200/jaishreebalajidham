<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>श्री हनुमान मंदिर</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        saffron: '#FF9933',
                        hanumanred: '#FF2400',
                    }
                }
            }
        }
    </script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap');
        body {
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }
        .saffron-gradient {
            background: linear-gradient(135deg, #FF9933 0%, #FF5733 100%);
        }
        .hanuman-red-text {
            color: #FF2400;
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Navigation -->
    <nav class="bg-white shadow-lg sticky top-0 z-50">
        <div class="max-w-6xl mx-auto px-4">
            <div class="flex justify-between">
                <div class="flex space-x-7">
                    <div class="flex items-center space-x-2">
                        <img src="https://placehold.co/40x40" alt="हनुमान जी का प्रतीक - एक ज्योतिर्लिंग के साथ गदा और हाथ में पर्वत लिए हुए" class="h-10 w-10">
                        <span class="font-semibold text-gray-900 text-lg">श्री हनुमान मंदिर</span>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-1">
                    <a href="#home" class="py-4 px-2 text-gray-700 hover:text-saffron transition">मुख्य</a>
                    <a href="#about" class="py-4 px-2 text-gray-700 hover:text-saffron transition">हमारे बारे में</a>
                    <a href="#chalisa" class="py-4 px-2 text-gray-700 hover:text-saffron transition">हनुमान चालीसा</a>
                    <a href="#gallery" class="py-4 px-2 text-gray-700 hover:text-saffron transition">गैलरी</a>
                    <a href="#timings" class="py-4 px-2 text-gray-700 hover:text-saffron transition">आरती समय</a>
                    <a href="#contact" class="py-4 px-2 text-gray-700 hover:text-saffron transition">संपर्क</a>
                </div>
                <div class="md:hidden flex items-center">
                    <button class="mobile-menu-button p-2 focus:outline-none">
                        <svg class="w-6 h-6" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                            <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M4 6h16M4 12h16M4 18h16"></path>
                        </svg>
                    </button>
                </div>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <section id="home" class="relative h-screen flex items-center justify-center">
        <img src="https://placehold.co/1920x1080" alt="भगवान हनुमान जी की प्रतिमा - शक्तिशाली मुद्रा में खड़े हुए, एक हाथ में गदा और दूसरे हाथ में पर्वत उठाए हुए, लाल रंग के वस्त्र और चेहरे पर तेज" class="absolute inset-0 w-full h-full object-cover">
        <div class="absolute inset-0 bg-black bg-opacity-40"></div>
        <div class="relative z-10 text-center px-4 md:px-0">
            <h1 class="text-4xl md:text-6xl font-bold text-white mb-6">श्री हनुमान मंदिर</h1>
            <p class="text-xl md:text-2xl text-white mb-8">शक्ति, भक्ति और साहस का प्रतीक</p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#about" class="saffron-gradient text-white font-bold py-3 px-8 rounded-full hover:shadow-lg transition">और जानें</a>
                <a href="#chalisa" class="bg-white hanuman-red-text font-bold py-3 px-8 rounded-full hover:shadow-lg transition">हनुमान चालीसा</a>
            </div>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">हमारे बारे में</h2>
                <div class="w-24 h-1 saffron-gradient mx-auto mt-4"></div>
            </div>
            <div class="flex flex-col md:flex-row items-center">
                <div class="md:w-1/2 mb-8 md:mb-0 md:pr-8">
                    <img src="https://placehold.co/600x400" alt="हनुमान मंदिर का इतिहास - पुराने फोटो में संतों द्वारा मंदिर की स्थापना करते हुए, पारंपरिक वेशभूषा में" class="rounded-lg shadow-xl w-full">
                </div>
                <div class="md:w-1/2">
                    <h3 class="text-2xl font-bold text-gray-800 mb-4">एक पावन धार्मिक स्थल</h3>
                    <p class="text-gray-600 mb-4">1985 में स्थापित, श्री हनुमान मंदिर आस्था और शक्ति का प्रमुख केंद्र है। यह मंदिर संत श्री रामदास जी महाराज के आशीर्वाद से बना था।</p>
                    <p class="text-gray-600 mb-6">हमारा मंदिर हनुमान जी की एक विशाल 21 फीट ऊंची मूर्ति का घर है जो भक्तों को साहस और शक्ति प्रदान करती है। मंगलवार और शनिवार को विशेष पूजा का आयोजन किया जाता है।</p>
                    <div class="flex flex-wrap gap-4">
                        <a href="#timings" class="saffron-gradient text-white font-bold py-2 px-6 rounded-full hover:shadow-lg transition inline-block">आरती समय</a>
                        <a href="#chalisa" class="bg-gray-100 hanuman-red-text font-bold py-2 px-6 rounded-full hover:shadow-lg transition inline-block">हनुमान चालीसा पढ़ें</a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Hanuman Chalisa Section -->
    <section id="chalisa" class="py-20 bg-gray-100">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">श्री हनुमान चालीसा</h2>
                <div class="w-24 h-1 hanuman-red-text bg-hanumanred mx-auto mt-4"></div>
                <p class="mt-4 text-gray-600">पाठ करने के लिए नीचे स्क्रॉल करें</p>
            </div>
            
            <div class="bg-white rounded-lg shadow-xl p-8 md:p-12">
                <div class="saffron-gradient rounded-full w-20 h-20 flex items-center justify-center mx-auto mb-8">
                    <img src="https://placehold.co/40x40" alt="छोटी हनुमान जी की मूर्ति - लाल रंग में, हाथ जुड़े हुए" class="w-12 h-12">
                </div>
                
                <div class="text-center mb-8">
                    <h3 class="text-2xl font-bold mb-4 hanuman-red-text">श्री हनुमान चालीसा</h3>
                    <p class="text-gray-600 mb-2">(दोहा)</p>
                    <p class="text-lg font-medium mb-6">"श्रीगुरु चरण सरोज रज, निज मनु मुकुर सुधारि।<br>
                    बरनऊ रघुबर बिमल जसु, जो दायकु फल चारि॥"</p>
                </div>
                
                <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
                    <div>
                        <h4 class="text-xl font-semibold mb-4 hanuman-red-text">चौपाई</h4>
                        <p class="text-gray-700 leading-relaxed">
                            जय हनुमान ज्ञान गुण सागर। जय कपीश तिहुँ लोक उजागर॥<br><br>
                            राम दूत अतुलित बल धामा। अंजनि पुत्र पवनसुत नामा॥<br><br>
                            महावीर विक्रम बजरंगी। कुमति निवार सुमति के संगी॥<br><br>
                            कंचन बरन बिराज सुबेसा। कानन कुंडल कुन्चित केसा॥
                        </p>
                    </div>
                    <div>
                        <h4 class="text-xl font-semibold mb-4 hanuman-red-text">अर्थ</h4>
                        <p class="text-gray-700 leading-relaxed">
                            हे हनुमान जी! आपका जय हो, आप ज्ञान और गुणों के सागर हैं।<br><br>
                            आप अतुलनीय बल के धाम हैं और अंजना माता के पुत्र हैं।<br><br>
                            आप महावीर हैं, विक्रमशाली हैं और कुमति का नाश करने वाले हैं।<br><br>
                            आपके शरीर का रंग स्वर्ण के समान है और आप सुंदर वस्त्र धारण करते हैं।
                        </p>
                    </div>
                </div>
                
                <div class="text-center mt-12">
                    <a href="#" class="saffron-gradient text-white font-bold py-3 px-8 rounded-full hover:shadow-lg transition inline-block">पूरी चालीसा पढ़ें</a>
                </div>
            </div>
        </div>
    </section>

    <!-- Gallery Section -->
    <section id="gallery" class="py-20 bg-white">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">मंदिर गैलरी</h2>
                <div class="w-24 h-1 saffron-gradient mx-auto mt-4"></div>
                <p class="mt-4 text-gray-600">हमारे मंदिर के दर्शनीय दृश्य</p>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition">
                    <img src="https://placehold.co/600x400" alt="मुख्य मंदिर प्रांगण - हनुमान जी की बड़ी मूर्ति के सामने भक्तों की भीड़, पीले फूलों से सजा हुआ" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h4 class="font-semibold text-lg mb-2 hanuman-red-text">मुख्य प्रतिमा</h4>
                        <p class="text-gray-600">21 फीट ऊंची हनुमान जी की मूर्ति</p>
                    </div>
                </div>
                
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition">
                    <img src="https://placehold.co/600x400" alt="संध्या आरती का दृश्य - दीपों से जगमगाता मंदिर, पुजारी आरती करते हुए" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h4 class="font-semibold text-lg mb-2 hanuman-red-text">संध्या आरती</h4>
                        <p class="text-gray-600">शाम 7 बजे की विशेष आरती</p>
                    </div>
                </div>
                
                <div class="overflow-hidden rounded-lg shadow-md hover:shadow-xl transition">
                    <img src="https://placehold.co/600x400" alt="नवरात्रि उत्सव - रंग-बिरंगी लाइट्स से सजा मंदिर, हजारों भक्तों का समूह" class="w-full h-64 object-cover">
                    <div class="p-4 bg-white">
                        <h4 class="font-semibold text-lg mb-2 hanuman-red-text">वार्षिक उत्सव</h4>
                        <p class="text-gray-600">हनुमान जयंती का भव्य आयोजन</p>
                    </div>
                </div>
            </div>
            
            <div class="text-center mt-12">
                <a href="#" class="saffron-gradient text-white font-bold py-3 px-8 rounded-full hover:shadow-lg transition inline-block">और तस्वीरें देखें</a>
            </div>
        </div>
    </section>

    <!-- Timings Section -->
    <section id="timings" class="py-20 bg-gray-100">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">पूजा और आरती समय</h2>
                <div class="w-24 h-1 hanuman-red-text bg-hanumanred mx-auto mt-4"></div>
                <p class="mt-4 text-gray-600">नियमित दर्शन का समय</p>
            </div>
            
            <div class="max-w-3xl mx-auto">
                <div class="bg-white rounded-lg shadow-xl overflow-hidden">
                    <div class="saffron-gradient px-6 py-4">
                        <h3 class="text-xl font-bold text-white">नित्य पूजा कार्यक्रम</h3>
                    </div>
                    
                    <div class="divide-y divide-gray-200">
                        <div class="p-6 flex justify-between items-center">
                            <div>
                                <h4 class="font-semibold text-lg hanuman-red-text">मंगलवार स्पेशल</h4>
                                <p class="text-gray-600">विशेष पूजा और भंडारा</p>
                            </div>
                            <div class="text-right">
                                <p class="font-medium">5:00 AM - 9:00 PM</p>
                                <p class="text-sm text-gray-500">(लंच ब्रेक 1:00-3:00 PM)</p>
                            </div>
                        </div>
                        
                        <div class="p-6 flex justify-between items-center">
                            <div>
                                <h4 class="font-semibold text-lg hanuman-red-text">सुबह की पूजा</h4>
                                <p class="text-gray-600">मंगला आरती</p>
                            </div>
                            <div class="text-right">
                                <p class="font-medium">5:00 AM - 6:30 AM</p>
                            </div>
                        </div>
                        
                        <div class="p-6 flex justify-between items-center">
                            <div>
                                <h4 class="font-semibold text-lg hanuman-red-text">शाम की आरती</h4>
                                <p class="text-gray-600">संध्या आरती</p>
                            </div>
                            <div class="text-right">
                                <p class="font-medium">7:00 PM - 7:30 PM</p>
                            </div>
                        </div>
                        
                        <div class="p-6 flex justify-between items-center">
                            <div>
                                <h4 class="font-semibold text-lg hanuman-red-text">शनिवार विशेष</h4>
                                <p class="text-gray-600">शनि दोष निवारण पूजा</p>
                            </div>
                            <div class="text-right">
                                <p class="font-medium">4:00 PM - 6:00 PM</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Donation Section -->
    <section class="py-20">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 bg-hanumanred rounded-2xl shadow-xl p-12 text-center">
            <h2 class="text-3xl md:text-4xl font-bold text-white mb-4">मंदिर के विकास में सहयोग करें</h2>
            <p class="text-white mb-8">आपका दान मंदिर के रखरखाव और समाजसेवा कार्यों में सहायक होगा</p>
            <div class="flex flex-wrap justify-center gap-4">
                <a href="#" class="bg-white hanuman-red-text font-bold py-3 px-8 rounded-full hover:shadow-lg transition">ऑनलाइन दान</a>
                <a href="#" class="border-2 border-white text-white font-bold py-3 px-8 rounded-full hover:bg-white hover:text-hanumanred transition">संपर्क करें</a>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-20 bg-white border-t border-gray-200">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-16">
                <h2 class="text-3xl md:text-4xl font-bold text-gray-900">हमसे संपर्क करें</h2>
                <div class="w-24 h-1 saffron-gradient mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-12">
                <div>
                    <h3 class="text-2xl font-bold mb-6 hanuman-red-text">पता</h3>
                    <p class="text-gray-700 mb-6">
                        श्री हनुमान मंदिर, श्री राम नगर<br>
                        नई दिल्ली - 1100XX<br>
                        भारत
                    </p>
                    
                    <div class="space-y-4">
                        <div class="flex items-start space-x-4">
                            <div class="saffron-gradient rounded-full p-2">
                                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 5a2 2 0 012-2h3.28a1 1 0 01.948.684l1.498 4.493a1 1 0 01-.502 1.21l-2.257 1.13a11.042 11.042 0 005.516 5.516l1.13-2.257a1 1 0 011.21-.502l4.493 1.498a1 1 0 01.684.949V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z"></path>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold hanuman-red-text">फोन नंबर</h4>
                                <p class="text-gray-600">+91 98765 43210</p>
                            </div>
                        </div>
                        
                        <div class="flex items-start space-x-4">
                            <div class="saffron-gradient rounded-full p-2">
                                <svg class="w-6 h-6 text-white" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                    <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 8l7.89 5.26a2 2 0 002.22 0L21 8M5 19h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v10a2 2 0 002 2z"></path>
                                </svg>
                            </div>
                            <div>
                                <h4 class="font-semibold hanuman-red-text">ईमेल</h4>
                                <p class="text-gray-600">contact@hanumanmandir.com</p>
                            </div>
                        </div>
                    </div>
                </div>
                
                <div>
                    <h3 class="text-2xl font-bold mb-6 hanuman-red-text">संदेश भेजें</h3>
                    <form class="space-y-6">
                        <div>
                            <label for="name" class="block text-sm font-medium text-gray-700 mb-1">आपका नाम</label>
                            <input type="text" id="name" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-saffron focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="email" class="block text-sm font-medium text-gray-700 mb-1">ईमेल पता</label>
                            <input type="email" id="email" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-saffron focus:border-transparent">
                        </div>
                        
                        <div>
                            <label for="message" class="block text-sm font-medium text-gray-700 mb-1">संदेश</label>
                            <textarea id="message" rows="4" class="w-full px-4 py-2 border border-gray-300 rounded-md focus:ring-2 focus:ring-saffron focus:border-transparent"></textarea>
                        </div>
                        
                        <button type="submit" class="saffron-gradient text-white font-bold py-3 px-8 rounded-full hover:shadow-lg transition w-full">संदेश भेजें</button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <div>
                    <h3 class="text-xl font-bold mb-4">श्री हनुमान मंदिर</h3>
                    <p class="text-gray-400">भक्ति, शक्ति और साहस का प्रतीक</p>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">जल्दी लिंक</h4>
                    <ul class="space-y-2">
                        <li><a href="#home" class="text-gray-400 hover:text-saffron transition">मुख्य</a></li>
                        <li><a href="#about" class="text-gray-400 hover:text-saffron transition">हमारे बारे में</a></li>
                        <li><a href="#chalisa" class="text-gray-400 hover:text-saffron transition">हनुमान चालीसा</a></li>
                        <li><a href="#timings" class="text-gray-400 hover:text-saffron transition">समय</a></li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">पूजा समय</h4>
                    <ul class="text-gray-400 space-y-2">
                        <li>सुबह: 5:00 AM - 12:00 PM</li>
                        <li>शाम: 4:00 PM - 9:00 PM</li>
                        <li>मंगलवार: विशेष पूजा</li>
                    </ul>
                </div>
                
                <div>
                    <h4 class="text-lg font-semibold mb-4">सोशल मीडिया</h4>
                    <div class="flex space-x-4">
                        <a href="#" class="bg-saffron text-white p-2 rounded-full hover:bg-orange-600 transition">
                            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33v6.988C18.343 21.128 22 16.991 22 12z"></path>
                            </svg>
                        </a>
                        <a href="#" class="bg-saffron text-white p-2 rounded-full hover:bg-orange-600 transition">
                            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M12.315 2c2.43 0 2.784.013 3.808.06 1.064.049 1.791.218 2.427.465a4.902 4.902 0 011.772 1.153 4.902 4.902 0 011.153 1.772c.247.636.416 1.363.465 2.427.048 1.067.06 1.407.06 4.123v.08c0 2.643-.012 2.987-.06 4.043-.049 1.064-.218 1.791-.465 2.427a4.902 4.902 0 01-1.153 1.772 4.902 4.902 0 01-1.772 1.153c-.636.247-1.363.416-2.427.465-1.067.048-1.407.06-4.123.06h-.08c-2.643 0-2.987-.012-4.043-.06-1.064-.049-1.791-.218-2.427-.465a4.902 4.902 0 01-1.772-1.153 4.902 4.902 0 01-1.153-1.772c-.247-.636-.416-1.363-.465-2.427-.047-1.024-.06-1.379-.06-3.808v-.63c0-2.43.013-2.784.06-3.808.049-1.064.218-1.791.465-2.427a4.902 4.902 0 011.153-1.772A4.902 4.902 0 015.45 2.525c.636-.247 1.363-.416 2.427-.465C8.901 2.013 9.256 2 11.685 2h.63zm-.081 1.802h-.468c-2.456 0-2.784.011-3.807.058-.975.045-1.504.207-1.857.344-.467.182-.8.398-1.15.748-.35.35-.566.683-.748 1.15-.137.353-.3.882-.344 1.857-.047 1.023-.058 1.351-.058 3.807v.468c0 2.456.011 2.784.058 3.807.045.975.207 1.504.344 1.857.182.466.399.8.748 1.15.35.35.683.566 1.15.748.353.137.882.3 1.857.344 1.054.048 1.37.058 4.041.058h.08c2.597 0 2.917-.01 3.96-.058.976-.045 1.505-.207 1.858-.344.466-.182.8-.398 1.15-.748.35-.35.566-.683.748-1.15.137-.353.3-.882.344-1.857.048-1.055.058-1.37.058-4.041v-.08c0-2.597-.01-2.917-.058-3.96-.045-.976-.207-1.505-.344-1.858a3.097 3.097 0 00-.748-1.15 3.098 3.098 0 00-1.15-.748c-.353-.137-.882-.3-1.857-.344-1.023-.047-1.351-.058-3.807-.058zM12 6.865a5.135 5.135 0 110 10.27 5.135 5.135 0 010-10.27zm0 1.802a3.333 3.333 0 100 6.666 3.333 3.333 0 000-6.666zm5.338-3.205a1.2 1.2 0 110 2.4 1.2 1.2 0 010-2.4z"></path>
                            </svg>
                        </a>
                        <a href="#" class="bg-saffron text-white p-2 rounded-full hover:bg-orange-600 transition">
                            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M8.29 20.251c7.547 0 11.675-6.253 11.675-11.675 0-.178 0-.355-.012-.53A8.348 8.348 0 0022 5.92a8.19 8.19 0 01-2.357.646 4.118 4.118 0 001.804-2.27 8.224 8.224 0 01-2.605.996 4.107 4.107 0 00-6.993 3.743 11.65 11.65 0 01-8.457-4.287 4.106 4.106 0 001.27 5.477A4.072 4.072 0 012.8 9.713v.052a4.105 4.105 0 003.292 4.022 4.095 4.095 0 01-1.853.07 4.108 4.108 0 003.834 2.85A8.233 8.233 0 012 18.407a11.616 11.616 0 006.29 1.84"></path>
                            </svg>
                        </a>
                        <a href="#" class="bg-saffron text-white p-2 rounded-full hover:bg-orange-600 transition">
                            <svg class="w-5 h-5" fill="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
                                <path d="M19.615 3.184c-3.604-.246-11.631-.245-15.23 0-3.897.266-4.356 2.62-4.385 8.816.029 6.185.484 8.549 4.385 8.816 3.6.245 11.626.246 15.23 0 3.897-.266 4.356-2.62 4.385-8.816-.029-6.185-.484-8.549-4.385-8.816zm-10.615 12.816v-8l8 3.993-8 4.007z"></path>
                            </svg>
                        </a>
                    </div>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-12 pt-8 text-center text-gray-400">
                <p>© 2023 श्री हनुमान मंदिर. सर्वाधिकार सुरक्षित।</p>
            </div>
        </div>
    </footer>

    <script>
        // Mobile menu toggle
        const mobileMenuButton = document.querySelector('.mobile-menu-button');
        const mobileMenu = document.querySelector('.mobile-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // Smooth scrolling for anchor links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });
    </script>
</body>
</html>
