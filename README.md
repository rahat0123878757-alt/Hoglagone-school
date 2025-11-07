<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hoglagaon Abul Hashem High School</title>
    <!-- Tailwind CSS লোড করা হচ্ছে -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* ইন্টার ফন্ট ব্যবহার করা হচ্ছে */
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@100..900&display=swap');
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f7f7f7;
            color: #333;
        }
        .header-bg {
            background-color: #004d40; /* গাঢ় সবুজ থিম */
        }
        .primary-color {
            color: #004d40;
        }
        .bg-primary {
            background-color: #004d40;
        }
        .hover-primary:hover {
            background-color: #00897b;
        }
        /* কাস্টম সেকশন হেডার */
        .section-header {
            border-bottom: 3px solid #004d40;
            padding-bottom: 10px;
        }
    </style>
</head>
<body>
    
    <!-- নেভিগেশন বার (NAVBAR) -->
    <nav class="header-bg text-white shadow-lg sticky top-0 z-50">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-20">
                <!-- স্কুল নাম (ব্র্যান্ড) -->
                <a href="#home" class="text-2xl font-extrabold tracking-wider">
                    Hoglagaon High School
                </a>

                <!-- মেনু আইটেম (ডেস্কটপ) -->
                <div class="hidden md:flex space-x-6 text-sm font-semibold">
                    <a href="#about" class="hover:text-yellow-400 transition duration-200 py-5">আমাদের সম্পর্কে</a>
                    <a href="#mission" class="hover:text-yellow-400 transition duration-200 py-5">লক্ষ্য ও উদ্দেশ্য</a>
                    <a href="#success" class="hover:text-yellow-400 transition duration-200 py-5">সাফল্য</a>
                    <a href="#teachers" class="hover:text-yellow-400 transition duration-200 py-5">শিক্ষকবৃন্দ</a>
                    <a href="#gallery" class="hover:text-yellow-400 transition duration-200 py-5">গ্যালারি</a>
                    <a href="#location" class="hover:text-yellow-400 transition duration-200 py-5">অবস্থান</a>
                    <a href="#contact" class="bg-yellow-500 text-gray-900 px-4 py-2 rounded-full hover:bg-yellow-400 transition duration-200 shadow-md">যোগাযোগ</a>
                </div>
            </div>
        </div>
    </nav>
    
    <!-- প্রধান কন্টেইনার -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">

        <!-- ১. হোম সেকশন ও স্কুলের নাম -->
        <section id="home" class="bg-white p-10 rounded-xl shadow-2xl text-center mb-12">
            <h1 class="text-5xl md:text-6xl font-extrabold primary-color mb-4 animate-pulse">হগলাগাঁও আবুল হাশেম হাই স্কুল</h1>
            <p class="text-xl text-gray-600">জ্ঞান ও নৈতিকতা দিয়ে ভবিষ্যৎ প্রজন্ম গড়ার অঙ্গীকার</p>
            <img src="https://placehold.co/1200x400/004d40/ffffff?text=School+Building+Placeholder" alt="School Building Placeholder" class="mt-8 rounded-lg shadow-xl w-full h-auto object-cover" onerror="this.onerror=null;this.src='https://placehold.co/1200x400/004d40/ffffff?text=Hoglagaon+Abul+Hashem+High+School+Building'">
        </section>

        <!-- ২. আমাদের সম্পর্কে (About our school) -->
        <section id="about" class="bg-white p-8 rounded-xl shadow-lg mb-12">
            <h2 class="text-3xl font-bold section-header primary-color mb-6">১. আমাদের স্কুল সম্পর্কে</h2>
            <p class="text-lg text-gray-700 leading-relaxed">
                হগলাগাঁও আবুল হাশেম হাই স্কুল স্থানীয় জনগনের শিক্ষা বিস্তারের লক্ষ্যে প্রতিষ্ঠিত একটি ঐতিহ্যবাহী শিক্ষা প্রতিষ্ঠান। প্রতিষ্ঠার পর থেকে স্কুলটি সুনামের সাথে কাজ করে যাচ্ছে, শিক্ষার্থীদের মানসম্পন্ন শিক্ষা এবং নৈতিক মূল্যবোধের ওপর জোর দিয়ে যাচ্ছে। শিক্ষকরা তাদের জ্ঞান এবং অভিজ্ঞতার মাধ্যমে ছাত্রদের ভবিষ্যতের জন্য প্রস্তুত করেন। আমাদের স্কুল শুধু পড়াশোনায় নয়, খেলাধুলা ও সাংস্কৃতিক কার্যক্রমেও সমান গুরুত্ব দেয়।
            </p>
        </section>

        <!-- ৩. লক্ষ্য ও উদ্দেশ্য (Our aim or mission) -->
        <section id="mission" class="bg-gray-100 p-8 rounded-xl shadow-lg mb-12">
            <h2 class="text-3xl font-bold section-header primary-color mb-6">২. লক্ষ্য ও উদ্দেশ্য (Our Aim or Mission)</h2>
            <ul class="space-y-4 text-gray-700 list-disc list-inside ml-4">
                <li class="font-semibold text-lg">মানসম্পন্ন শিক্ষা প্রদান: প্রত্যেক শিক্ষার্থীকে আধুনিক বিশ্বের উপযোগী করে তুলতে মানসম্মত পাঠ্যক্রম নিশ্চিত করা।</li>
                <li class="font-semibold text-lg">নৈতিক শিক্ষা: শিক্ষার্থীদের মধ্যে সততা, শৃঙ্খলা ও দেশপ্রেমের মতো নৈতিক মূল্যবোধ গড়ে তোলা।</li>
                <li class="font-semibold text-lg">সমন্বিত উন্নয়ন: খেলাধুলা, বিজ্ঞান ও সংস্কৃতি চর্চার মাধ্যমে ছাত্রদের শারীরিক ও মানসিক বিকাশে সহায়তা করা।</li>
            </ul>
        </section>

        <!-- ৪. সাফল্য (Our success) -->
        <section id="success" class="bg-white p-8 rounded-xl shadow-lg mb-12">
            <h2 class="text-3xl font-bold section-header primary-color mb-6">৩. স্কুলের সাফল্য</h2>
            <p class="text-gray-600 mb-4">আমাদের স্কুলের এসএসসি পরীক্ষার ফলাফল সবসময়ই গর্বের বিষয়। বিগত বছরগুলোতে আমাদের শিক্ষার্থীরা উজ্জ্বল সাফল্য অর্জন করেছে।</p>
            
            <div class="grid grid-cols-2 md:grid-cols-4 gap-6 text-center">
                <!-- সাফল্যের কার্ড (উদাহরণ) -->
                <div class="p-4 bg-green-50 rounded-lg shadow-md border-t-4 border-green-600">
                    <p class="text-3xl font-extrabold text-green-600">২০২৩</p>
                    <p class="text-sm font-semibold text-gray-700">এসএসসি ব্যাচ</p>
                    <p class="text-xl font-bold mt-1">১২ জন</p>
                    <p class="text-xs text-gray-500">A+ প্রাপ্ত</p>
                </div>
                <div class="p-4 bg-green-50 rounded-lg shadow-md border-t-4 border-green-600">
                    <p class="text-3xl font-extrabold text-green-600">২০২২</p>
                    <p class="text-sm font-semibold text-gray-700">এসএসসি ব্যাচ</p>
                    <p class="text-xl font-bold mt-1">১০ জন</p>
                    <p class="text-xs text-gray-500">A+ প্রাপ্ত</p>
                </div>
                <div class="p-4 bg-green-50 rounded-lg shadow-md border-t-4 border-green-600">
                    <p class="text-3xl font-extrabold text-green-600">২০২১</p>
                    <p class="text-sm font-semibold text-gray-700">এসএসসি ব্যাচ</p>
                    <p class="text-xl font-bold mt-1">১৫ জন</p>
                    <p class="text-xs text-gray-500">A+ প্রাপ্ত</p>
                </div>
                <div class="p-4 bg-green-50 rounded-lg shadow-md border-t-4 border-green-600">
                    <p class="text-3xl font-extrabold text-green-600">মোট</p>
                    <p class="text-sm font-semibold text-gray-700">পাসের হার</p>
                    <p class="text-xl font-bold mt-1">৯৮%+</p>
                    <p class="text-xs text-gray-500">গড় সাফল্য</p>
                </div>
            </div>
        </section>

        <!-- ৫. শিক্ষকবৃন্দ (Our teacher) -->
        <section id="teachers" class="bg-gray-100 p-8 rounded-xl shadow-lg mb-12">
            <h2 class="text-3xl font-bold section-header primary-color mb-8">৪. শিক্ষক ও শিক্ষিকাবৃন্দ</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 lg:grid-cols-4 gap-8">
                
                <!-- ১. প্রধান শিক্ষক (Headmaster) -->
                <div class="bg-white p-5 rounded-xl shadow-lg text-center border-t-4 border-red-500">
                    <img src="https://placehold.co/150x150/f0f0f0/333333?text=Headmaster" alt="Headmaster Photo" class="w-28 h-28 object-cover rounded-full mx-auto mb-4 border-4 border-red-200">
                    <h3 class="text-xl font-bold primary-color">প্রধান শিক্ষক</h3>
                    <p class="text-lg font-semibold text-gray-800 mt-1">নাম এখানে দিন</p>
                    <p class="text-sm text-gray-500">পদ: প্রধান শিক্ষক</p>
                    <p class="text-sm text-gray-500">বিষয়: অজানা</p>
                </div>

                <!-- ২. Satindra Samadder -->
                <div class="bg-white p-5 rounded-xl shadow-lg text-center border-t-4 border-blue-500">
                    <img src="https://placehold.co/150x150/f0f0f0/333333?text=Teacher+Photo" alt="Satindra Samadder Photo" class="w-28 h-28 object-cover rounded-full mx-auto mb-4 border-4 border-blue-200">
                    <h3 class="text-xl font-bold text-blue-700">সতিন্দ্র সমাদ্দার</h3>
                    <p class="text-lg font-semibold text-gray-800 mt-1">Assistent Teacher</p>
                    <p class="text-sm text-gray-500">বিষয়: পদার্থবিজ্ঞান</p>
                    <p class="text-sm text-red-500 font-medium">শিক্ষাগত ট্যালেন্ট: Unknown</p>
                </div>
                
                <!-- বাকি শিক্ষকদের জন্য Placeholder -->
                <div class="bg-white p-5 rounded-xl shadow-lg text-center border-t-4 border-gray-400">
                    <img src="https://placehold.co/150x150/f0f0f0/333333?text=Teacher" alt="Teacher Photo" class="w-28 h-28 object-cover rounded-full mx-auto mb-4">
                    <h3 class="text-xl font-bold primary-color">শিক্ষক নাম (৩)</h3>
                    <p class="text-sm text-gray-500">পদ: সহকারী শিক্ষক</p>
                    <p class="text-sm text-gray-500">বিষয়: বাংলা</p>
                </div>
                 <div class="bg-white p-5 rounded-xl shadow-lg text-center border-t-4 border-gray-400">
                    <img src="https://placehold.co/150x150/f0f0f0/333333?text=Teacher" alt="Teacher Photo" class="w-28 h-28 object-cover rounded-full mx-auto mb-4">
                    <h3 class="text-xl font-bold primary-color">শিক্ষক নাম (৪)</h3>
                    <p class="text-sm text-gray-500">পদ: সহকারী শিক্ষক</p>
                    <p class="text-sm text-gray-500">বিষয়: গণিত</p>
                </div>
            </div>
            
            <p class="text-center text-gray-500 mt-8 text-sm">আমাদের স্কুলে মোট ২০ জন (প্রধান শিক্ষকসহ) শিক্ষক-শিক্ষিকা রয়েছেন।</p>
        </section>

        <!-- ৬. গ্যালারি (Our school gallery) -->
        <section id="gallery" class="bg-white p-8 rounded-xl shadow-lg mb-12">
            <h2 class="text-3xl font-bold section-header primary-color mb-6">৫. গ্যালারি ও স্কুল প্রাঙ্গণের ছবি</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <!-- ছবির জন্য প্লেসহোল্ডার -->
                <img src="https://placehold.co/600x400/999999/ffffff?text=School+View+1" alt="School Gallery Image 1" class="rounded-lg shadow-md w-full h-auto object-cover">
                <img src="https://placehold.co/600x400/999999/ffffff?text=Classroom+Image" alt="School Gallery Image 2" class="rounded-lg shadow-md w-full h-auto object-cover">
            </div>
            
            <h3 class="text-2xl font-bold primary-color mt-10 mb-4">ভিডিও বা ছবি লিংক (ভিডিওর ম্যাপ লোকেশন)</h3>
            <ul class="space-y-3 text-gray-700 list-disc list-inside ml-4">
                <li><a href="https://maps.app.goo.gl/AkZykQAHhSGdN6Bg9?g_st=ac" target="_blank" class="text-blue-600 hover:underline">স্কুল প্রাঙ্গণের ভিডিও লিংক ১ (Google Maps)</a></li>
                <li><a href="https://maps.app.goo.gl/8XNrehPX4JD7h1N37" target="_blank" class="text-blue-600 hover:underline">স্কুল প্রাঙ্গণের ভিডিও লিংক ২ (Google Maps)</a></li>
            </ul>
        </section>

        <!-- ৭. স্কুলের অবস্থান (Our school location) -->
        <section id="location" class="bg-gray-100 p-8 rounded-xl shadow-lg mb-12">
            <h2 class="text-3xl font-bold section-header primary-color mb-6">৬. স্কুলের অবস্থান</h2>
            <div class="bg-white p-4 rounded-lg shadow-inner">
                <p class="text-lg font-semibold mb-3 text-gray-700">ঠিকানা: হগলাগাঁও, পশ্চিমবঙ্গ/বাংলাদেশ</p>
                <!-- ম্যাপ এম্বেড (Google Maps iframe) -->
                <div class="aspect-w-16 aspect-h-9" style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; border-radius: 8px;">
                    <iframe 
                        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d1000!2d89.5085!3d23.6705!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMTPCsDA5JzQ0LjMiTiA4OcKwMzAnMTQuNyJF!5e0!3m2!1sen!2sbd!4v1637760000000&q=Hoglagaon+Abul+Hashem+High+School" 
                        width="100%" 
                        height="450" 
                        style="border:0; position: absolute; top: 0; left: 0; width: 100%; height: 100%;" 
                        allowfullscreen="" 
                        loading="lazy" 
                        referrerpolicy="no-referrer-when-downgrade"
                        title="Hoglagaon Abul Hashem High School Location"
                    ></iframe>
                </div>
                <p class="text-sm text-gray-500 mt-3">ম্যাপ লিংক: <a href="https://maps.app.goo.gl/U5Cfa1pCBw3qEPqw8" target="_blank" class="text-blue-600 hover:underline">Google Maps</a></p>
            </div>
        </section>

        <!-- ৮. যোগাযোগ (Contact us) -->
        <section id="contact" class="bg-white p-8 rounded-xl shadow-lg mb-12">
            <h2 class="text-3xl font-bold section-header primary-color mb-6">৭. যোগাযোগ করুন (Contact Us)</h2>
            <div class="grid md:grid-cols-2 gap-6">
                <div class="space-y-4">
                    <p class="text-xl font-semibold text-gray-800">ফোন:</p>
                    <a href="tel:+88018XXXXXXX" class="text-2xl font-bold text-red-600 hover:text-red-700 transition duration-200">০১৮XXXXXXX</a>
                    <p class="text-xl font-semibold text-gray-800 pt-4">ইমেইল:</p>
                    <a href="mailto:sasxxxxx@gmail.com" class="text-2xl font-bold text-red-600 hover:text-red-700 transition duration-200">sasxxxxx@gmail.com</a>
                </div>
                <!-- যোগাযোগ ফর্ম (প্লেসহোল্ডার) -->
                <div class="bg-gray-100 p-6 rounded-lg shadow-md">
                    <h3 class="text-xl font-semibold primary-color mb-4">আমাদের মেসেজ পাঠান</h3>
                    <form onsubmit="alert('মেসেজটি ডেটাবেস ছাড়া কাজ করবে না।'); return false;">
                        <input type="text" placeholder="আপনার নাম" class="w-full p-3 mb-3 border rounded-lg focus:border-green-500">
                        <input type="email" placeholder="আপনার ইমেইল" class="w-full p-3 mb-3 border rounded-lg focus:border-green-500">
                        <textarea placeholder="আপনার বার্তা" rows="4" class="w-full p-3 mb-4 border rounded-lg focus:border-green-500"></textarea>
                        <button type="submit" class="w-full bg-primary text-white py-3 rounded-lg hover-primary transition duration-200">পাঠিয়ে দিন</button>
                    </form>
                </div>
            </div>
        </section>

    </main>

    <!-- ফুটার -->
    <footer class="header-bg text-white p-6 shadow-xl">
        <div class="max-w-7xl mx-auto text-center">
            <p class="text-sm">&copy; ২০২৫ Hoglagaon Abul Hashem High School. সমস্ত অধিকার সংরক্ষিত।</p>
            <div class="mt-2 pt-2 border-t border-gray-700">
                <p class="text-xs text-yellow-400 font-semibold">
                    Developed by rm71 team & Rahat (owner of rm71 team)
                </p>
            </div>
        </div>
    </footer>

    <!-- JavaScript For Smooth Scrolling -->
    <script>
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
