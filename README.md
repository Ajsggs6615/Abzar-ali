# Abzar-ali
Best is first!
<!-- MVP ساخت سایت اشتراک و فروش پرامپت --><!-- این قالب اولیه Frontend است؛ Backend جداگانه باید اضافه شود --><!DOCTYPE html><html lang="fa">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>بازار پرامپت | Promptino</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-100 font-sans">
  <header class="bg-white shadow p-4 flex justify-between items-center">
    <h1 class="text-xl font-bold text-purple-600">📦 Promptino</h1>
    <nav>
      <a href="#" class="mr-4 text-gray-600 hover:text-purple-600">خانه</a>
      <a href="#" class="mr-4 text-gray-600 hover:text-purple-600">دسته‌بندی‌ها</a>
      <a href="#" class="mr-4 text-gray-600 hover:text-purple-600">ورود/ثبت‌نام</a>
    </nav>
  </header>  <main class="p-6">
    <section class="mb-8">
      <h2 class="text-2xl font-semibold mb-4">جدیدترین پرامپت‌ها</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-4">
        <!-- Card Sample -->
        <div class="bg-white p-4 rounded-xl shadow">
          <h3 class="text-lg font-bold text-purple-700">پرامپت نوشتن پست اینستاگرام</h3>
          <p class="text-sm text-gray-600">تولید متن تبلیغاتی بر اساس ویژگی محصول با tone مشخص</p>
          <p class="text-xs mt-2">دسته: تولید محتوا</p>
          <button class="mt-4 bg-purple-600 text-white px-3 py-1 rounded hover:bg-purple-700">خرید ۲۰٬۰۰۰ تومان</button>
        </div>
        <!-- More prompt cards go here -->
      </div>
    </section><section>
  <h2 class="text-2xl font-semibold mb-4">افزودن پرامپت</h2>
  <form class="bg-white p-4 rounded-xl shadow grid gap-4">
    <input type="text" placeholder="عنوان پرامپت" class="p-2 border rounded">
    <textarea placeholder="توضیح دقیق پرامپت و نتیجه مورد انتظار" class="p-2 border rounded"></textarea>
    <input type="text" placeholder="دسته‌بندی (مثلاً: طراحی، GPT-4، تبلیغات...)" class="p-2 border rounded">
    <input type="number" placeholder="قیمت (تومان)" class="p-2 border rounded">
    <button class="bg-green-600 text-white px-4 py-2 rounded hover:bg-green-700">ثبت پرامپت</button>
  </form>
</section>

  </main>  <footer class="text-center text-sm text-gray-500 p-4">
    ساخته شده با ❤️ برای فروش پرامپت‌ها | Promptino.ir
  </footer>
</body>
</html>