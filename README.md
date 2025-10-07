<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title></title>
    <!-- Load Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font and basic setup */
        body {
            font-family: 'Inter', sans-serif;
            background-color: #;
        }
        /* Custom box shadow for a premium but friendly look */
        .card-shadow {
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.1), 0 2px 4px -2px rgba(0, 0, 0, 0.06);
        }
        /* Style for the COD badge */
        .cod-badge {
            background-color: #ef4444; /* Red-500 */
            color: white;
            padding: 2px 8px;
            font-size: 0.75rem;
            font-weight: 600;
            border-radius: 9999px; /* Full rounded */
        }
        /* Hover effect for buttons */
        .btn-primary:hover {
            opacity: 0.9;
            transform: translateY(-1px);
        }
    </style>
</head>
<body class="min-h-screen">

    <!-- Header & Value Proposition Section -->
    <header class="bg-white sticky top-0 z-10 shadow-md">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-4 flex flex-col sm:flex-row justify-between items-center">
            <!-- Logo/Brand Name -->
            <h1 class="text-3xl font-extrabold text-gray-800 tracking-tight">
                <span class="text-red-600">HAMZA</span><span class="text-indigo-600">SHOPE</span>
            </h1>
            <!-- Main Value Proposition -->
            <div class="mt-2 sm:mt-0 text-center sm:text-right">
                <p class="text-xl font-semibold text-gray-700">جـودة عالية بثـمن مناسـب</p>
                <p class="text-sm text-gray-500 font-medium flex items-center justify-center sm:justify-end mt-1">
                    <svg xmlns="http://www.w3.org/2000/svg" class="h-5 w-5 mr-1 text-green-600" viewBox="0 0 20 20" fill="currentColor">
                        <path fill-rule="evenodd" d="M10 18a8 8 0 100-16 8 8 0 000 16zm3.707-9.293a1 1 0 00-1.414-1.414L9 10.586 7.707 9.293a1 1 0 00-1.414 1.414l2 2a1 1 0 001.414 0l4-4z" clip-rule="evenodd" />
                    </svg>
                    <span class="font-bold text-lg text-green-700">(الدفع عند الاستلام)</span>
                </p>
            </div>
        </div>
    </header>

    <!-- Main Content: Product Grid -->
    <main class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8">
        <!-- Section Title -->
        <h2 class="text-2xl sm:text-3xl font-bold text-gray-800 mb-6 text-center">
            أفضل العروض اليوم
        </h2>

        <!-- Product Grid -->
        <div id="product-grid" class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">

            <!-- Product Card 1: Performance Running Shoes -->
            <div class="bg-white rounded-xl overflow-hidden card-shadow transition-all duration-300 hover:shadow-xl">
                <img src="https://f.top4top.io/p_35667fsn61.jpg" onerror="this.src='https://placehold.co/600x400/2563eb/ffffff?text=Running+Shoe'" alt="Performance Running Shoes" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="text-lg font-semibold text-gray-900 truncate">مشروع شيخ لحسن بنيطو</h3>
                    <p class="text-sm text-gray-500 mt-1">مشروع مصنوع بالإحترافية و بأدوات بسيطة</p>
                    <div class="flex items-center justify-between mt-3">
                        <span class="text-2xl font-bold text-red-600">10DH</span>
                        <span class="cod-badge">دفع عند إستلام</span>
                    </div>
                    <button class="btn-primary w-full mt-4 bg-indigo-600 text-white py-2 rounded-lg font-bold transition-transform duration-150">
                        إضافة بطاقة
                    </button>
                </div>
            </div>

            <!-- Product Card 2: Quick-Dry Workout Tee -->
            <div class="bg-white rounded-xl overflow-hidden card-shadow transition-all duration-300 hover:shadow-xl">
                <img src="https://e.top4top.io/p_3566kvlzc1.jpg" onerror="this.src='https://placehold.co/600x400/10b981/ffffff?text=Workout+Tee'" alt="Quick-Dry Workout Tee" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="text-lg font-semibold text-gray-900 truncate">مشروع فتيات قوى</h3>
                    <p class="text-sm text-gray-500 mt-1">مشروع يرمز لثقافة المغربية معاصرة</p>
                    <div class="flex items-center justify-between mt-3">
                        <span class="text-2xl font-bold text-red-600">5DH</span>
                        <span class="cod-badge">دفع عند استلام</span>
                    </div>
                    <button class="btn-primary w-full mt-4 bg-indigo-600 text-white py-2 rounded-lg font-bold transition-transform duration-150">
                        إضافة بطاقة
                    </button>
                </div>
            </div>

            <!-- Product Card 3: Compression Leggings -->
            <div class="bg-white rounded-xl overflow-hidden card-shadow transition-all duration-300 hover:shadow-xl">
                <img src="https://j.top4top.io/p_3566ahrd01.jpg" onerror="this.src='https://placehold.co/600x400/f59e0b/ffffff?text=Leggings'" alt="Compression Leggings" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="text-lg font-semibold text-gray-900 truncate"></h3>
                    <p class="text-sm text-gray-500 mt-1"></p>
                    <div class="flex items-center justify-between mt-3">
                        <span class="text-2xl font-bold text-red-600">0DH</span>
                        <span class="cod-badge">دفع عند استلام</span>
                    </div>
                    <button class="btn-primary w-full mt-4 bg-indigo-600 text-white py-2 rounded-lg font-bold transition-transform duration-150">
                        إضافة بطاقة
                    </button>
                </div>
            </div>

            <!-- Product Card 4: Classic Lifestyle Sneaker -->
            <div class="bg-white rounded-xl overflow-hidden card-shadow transition-all duration-300 hover:shadow-xl">
                <img src="https://j.top4top.io/p_3566ahrd01.jpg" onerror="this.src='https://placehold.co/600x400/9ca3af/ffffff?text=Sneaker'" alt="Classic Lifestyle Sneaker" class="w-full h-48 object-cover">
                <div class="p-5">
                    <h3 class="text-lg font-semibold text-gray-900 truncate"></h3>
                    <p class="text-sm text-gray-500 mt-1"></p>
                    <div class="flex items-center justify-between mt-3">
                        <span class="text-2xl font-bold text-red-600">0DH</span>
                        <span class="cod-badge">دفع عند استلام</span>
                    </div>
                    <button class="btn-primary w-full mt-4 bg-indigo-600 text-white py-2 rounded-lg font-bold transition-transform duration-150">
                        إضافة بطاقة
                    </button>
                </div>
            </div>

        </div> <!-- End Product Grid -->

        <!-- Highlight Banner -->
        <div class="mt-12 p-6 bg-indigo-500 rounded-xl text-white text-center shadow-lg">
            <h3 class="text-2xl font-extrabold mb-2">وعدنا : قيمة لا تقبل المنافسة</h3>
            <p class="text-lg">تسوق بثقة. أسعارنا مناسبة للجميع، ولن تدفع إلا عند وصول طلبك إلى باب منزلك.</p>
        </div>

    </main>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white mt-12">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 py-8 text-center">
            <p>&copy; 2025 HAMZASHOPE</p>
            <div class="mt-3 text-sm text-gray-400">
                <a href="#" class="hover:text-white mx-2">FAQ</a> |
                <a href="#" class="hover:text-white mx-2">Contact Us</a> |
                <a href="#" class="hover:text-white mx-2">Return Policy</a>
            </div>
        </div>
    </footer>

    <!-- Simple Cart/Message Box Logic (no alerts) -->
    <div id="message-box" class="fixed bottom-4 right-4 bg-green-500 text-white px-4 py-3 rounded-lg shadow-xl hidden transition-all duration-300 z-50">
        Item added to cart! Proceed to checkout to choose Pay Upon Receipt.
    </div>

    <script>
        // Simple JavaScript for button interaction and showing the message box
        document.addEventListener('DOMContentLoaded', () => {
            const buttons = document.querySelectorAll('.btn-primary');
            const messageBox = document.getElementById('message-box');
            
            // Function to show the custom message box
            const showMessage = () => {
                messageBox.classList.remove('hidden');
                messageBox.classList.add('animate-slideUp'); // Simple animation class for visual flair
                
                // Hide the message box after 3 seconds
                setTimeout(() => {
                    messageBox.classList.add('hidden');
                    messageBox.classList.remove('animate-slideUp');
                }, 3000);
            };

            // Add click listener to all 'Add to Cart' buttons
            buttons.forEach(button => {
                button.addEventListener('click', () => {
                    // In a real app, this would add the item to a shopping cart array/database
                    console.log('Product added to simulated cart.');
                    showMessage();
                });
            });

            // Add a simple Tailwind animation utility for better visual feedback
            const style = document.createElement('style');
            style.textContent = `
                @keyframes slideUp {
                    from { transform: translateY(20px); opacity: 0; }
                    to { transform: translateY(0); opacity: 1; }
                }
                .animate-slideUp {
                    animation: slideUp 0.3s ease-out forwards;
                }
            `;
            document.head.appendChild(style);
        });
    </script>
</body>
</html>

