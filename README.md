# HandySuite 
PK&#x0;&#x0;&#x0;&#x0;&#x0;���Z�j�ʯ&#x0;&#x0;&#x0;�&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;netlify.toml[build]
  publish = "."
  functions = "netlify/functions"
  command = ""

[dev]
  port = 8888
  publish = "."

[[redirects]]
  from = "/*"
  to = "/index.html"
  status = 200
PK&#x0;&#x0;&#x0;&#x0;&#x0;���Z��7��&#x0;&#x0;�&#x0;&#x0;
&#x0;&#x0;&#x0;index.html<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Supahandy Inc</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    :root {
      --primary: #1F2937;
      --accent: #22C55E;
    }
  </style>
</head>
<body class="bg-white text-gray-800 font-sans">
  <header class="bg-[var(--primary)] text-white p-6 shadow-md">
    <div class="max-w-7xl mx-auto flex items-center justify-between">
      <h1 class="text-2xl font-bold">Supahandy Inc</h1>
      <nav class="space-x-4">
        <a href="index.html" class="hover:underline">Home</a>
        <a href="housekeeping.html" class="hover:underline">Housekeeping</a>
        <a href="handyscapes.html" class="hover:underline">Handyscapes</a>
        <a href="heroes.html" class="hover:underline">Heroes</a>
        <a href="booking.html" class="hover:underline">Booking</a>
        <a href="agreement.html" class="hover:underline">Agreement</a>
        <a href="admin.html" class="hover:underline">Admin</a>
        <a href="technician.html" class="hover:underline">Technician</a>
        <a href="client.html" class="hover:underline">Client</a>
      </nav>
    </div>
  </header>

  <main class="max-w-5xl mx-auto py-16 px-6">
    <section class="text-center mb-12">
      <h2 class="text-4xl font-bold mb-4">When You Need a Hand?</h2>
      <p class="text-lg text-gray-600">Professional cleaning, landscaping, and handyman services for homes and businesses. Transparent pricing, trusted support, and easy scheduling — all in one place.</p>
    </section>

    <section class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      <div class="p-6 border rounded shadow">
        <h3 class="text-xl font-semibold text-[var(--accent)]">Handy Housekeeping</h3>
        <p class="mt-2">Routine, Deep, and Move-In/Out cleans tailored to your lifestyle. Add-ons include laundry, dishes, and appliance detailing.</p>
        <a href="housekeeping.html" class="text-blue-600 mt-4 inline-block">Get a Quote →</a>
      </div>
      <div class="p-6 border rounded shadow">
        <h3 class="text-xl font-semibold text-[var(--accent)]">Handyscapes</h3>
        <p class="mt-2">Lawn care, mulching, edging, garden prep, and seasonal clean-ups. We transform yards with care and creativity.</p>
        <a href="handyscapes.html" class="text-blue-600 mt-4 inline-block">Get a Quote →</a>
      </div>
      <div class="p-6 border rounded shadow">
        <h3 class="text-xl font-semibold text-[var(--accent)]">Handy Heroes</h3>
        <p class="mt-2">Repairs, remodeling, basic electrical and plumbing, and skilled installations. Residential and light commercial welcome.</p>
        <a href="heroes.html" class="text-blue-600 mt-4 inline-block">Get a Quote →</a>
      </div>
    </section>

    <section class="mt-16 text-center">
      <h3 class="text-2xl font-semibold mb-4 text-[var(--primary)]">Book, Track, and Get Estimates — All in One Platform</h3>
      <p class="text-gray-600 max-w-2xl mx-auto">Supahandy Inc provides full-service transparency. Clients can schedule directly online, technicians can upload job reports, and admins can access dashboards with live project logs and punch-ins.</p>
      <div class="mt-6 flex justify-center gap-4 flex-wrap">
        <a href="client.html" class="bg-yellow-500 text-white px-5 py-2 rounded shadow hover:bg-yellow-600">Client Portal</a>
        <a href="technician.html" class="bg-green-600 text-white px-5 py-2 rounded shadow hover:bg-green-700">Technician Portal</a>
        <a href="admin.html" class="bg-blue-700 text-white px-5 py-2 rounded shadow hover:bg-blue-800">Admin Portal</a>
      </div>
    </section>
  </main>

  <footer class="bg-gray-100 text-center p-6 mt-12 text-sm text-gray-600">
    &copy; 2025 Supahandy Inc. All rights reserved.<br>
    <a href="mailto:attendantsuper@gmail.com" class="text-blue-600">Contact Admin</a>
  </footer>
</body>
</html>
PK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Zf��q&#x0;&#x0;&#x0;q&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;technician.html<html><body><h1>Technician Portal</h1><p>Manage tasks, upload job photos, and submit punch-ins.</p></body></html>PK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z
_|�m&#x0;&#x0;&#x0;m&#x0;&#x0;&#x0;
&#x0;&#x0;&#x0;admin.html<html><body><h1>Admin Dashboard</h1><p>Track hours, manage schedules, view client activity.</p></body></html>PK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z;LAf&#x0;&#x0;&#x0;f&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;client.html<html><body><h1>Client Portal</h1><p>Book services, view estimates, contact support.</p></body></html>PK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z�
�Yn&#x0;&#x0;&#x0;n&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;housekeeping.html<html><body><h1>Handy Housekeeping</h1><p>Packages and estimate tools for cleaning services.</p></body></html>PK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�ZF���d&#x0;&#x0;&#x0;d&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;handyscapes.html<html><body><h1>Handyscapes</h1><p>Landscaping service descriptions and estimates.</p></body></html>PK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z��� ^&#x0;&#x0;&#x0;^&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;heroes.html<html><body><h1>Handy Heroes</h1><p>Repair and remodeling service estimates.</p></body></html>PK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z��|^&#x0;&#x0;&#x0;^&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;booking.html<html><body><h1>Booking Page</h1><p>Select your service, time, and location.</p></body></html>PK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z���3n&#x0;&#x0;&#x0;n&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;agreement.html<html><body><h1>Service Agreement</h1><p>Terms and conditions of working with Supahandy Inc.</p></body></html>PK&#x0;&#x0;&#x0;&#x0;&#x0;���Z�j�ʯ&#x0;&#x0;&#x0;�&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;��&#x0;&#x0;&#x0;&#x0;netlify.tomlPK&#x0;&#x0;&#x0;&#x0;&#x0;���Z��7��&#x0;&#x0;�&#x0;&#x0;
&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;���&#x0;&#x0;&#x0;index.htmlPK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Zf��q&#x0;&#x0;&#x0;q&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;���&#x0;&#x0;technician.htmlPK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z
_|�m&#x0;&#x0;&#x0;m&#x0;&#x0;&#x0;
&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;��o&#x0;&#x0;admin.htmlPK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z;LAf&#x0;&#x0;&#x0;f&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;��&#x0;&#x0;client.htmlPK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z�
�Yn&#x0;&#x0;&#x0;n&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;���&#x0;&#x0;housekeeping.htmlPK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�ZF���d&#x0;&#x0;&#x0;d&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;��0&#x0;&#x0;handyscapes.htmlPK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z��� ^&#x0;&#x0;&#x0;^&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;���&#x0;&#x0;heroes.htmlPK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z��|^&#x0;&#x0;&#x0;^&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;��I&#x0;&#x0;booking.htmlPK&#x0;&#x0;&#x0;&#x0;&#x0;ڹ�Z���3n&#x0;&#x0;&#x0;n&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;&#x0;���&#x0;&#x0;agreement.htmlPK&#x0;&#x0;&#x0;&#x0;

&#x0;L&#x0;&#x0;k&#x0;&#x0;&#x0;&#x0;<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Supahandy Inc</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    :root {
      --primary: #1F2937; /* blue-gray */
      --accent: #22C55E;  /* emerald/green */
    }
  </style>
</head>
<body class="bg-white text-gray-800 font-sans">
  <header class="bg-[var(--primary)] text-white p-6 shadow-md">
    <div class="max-w-7xl mx-auto flex items-center justify-between">
      <h1 class="text-2xl font-bold">Supahandy Inc</h1>
      <nav class="space-x-4">
        <a href="index.html" class="hover:underline">Home</a>
        <a href="housekeeping.html" class="hover:underline">Housekeeping</a>
        <a href="handyscapes.html" class="hover:underline">Handyscapes</a>
        <a href="heroes.html" class="hover:underline">Heroes</a>
        <a href="booking.html" class="hover:underline">Booking</a>
        <a href="agreement.html" class="hover:underline">Agreement</a>
        <a href="admin.html" class="hover:underline">Admin</a>
        <a href="technician.html" class="hover:underline">Technician</a>
        <a href="client.html" class="hover:underline">Client</a>
      </nav>
    </div>
  </header>

  <main class="max-w-5xl mx-auto py-16 px-6">
    <section class="text-center mb-12">
      <h2 class="text-4xl font-bold mb-4">When You Need a Hand?</h2>
      <p class="text-lg text-gray-600">Professional cleaning, landscaping, and handyman services for homes and businesses. Transparent pricing, trusted support, and easy scheduling — all in one place.</p>
    </section>

    <section class="grid grid-cols-1 md:grid-cols-3 gap-8 text-center">
      <div class="p-6 border rounded shadow">
        <h3 class="text-xl font-semibold text-[var(--accent)]">Handy Housekeeping</h3>
        <p class="mt-2">Routine, Deep, and Move-In/Out cleans tailored to your lifestyle. Add-ons include laundry, dishes, and appliance detailing.</p>
        <a href="housekeeping.html" class="text-blue-600 mt-4 inline-block">Get a Quote →</a>
      </div>
      <div class="p-6 border rounded shadow">
        <h3 class="text-xl font-semibold text-[var(--accent)]">Handyscapes</h3>
        <p class="mt-2">Lawn care, mulching, edging, garden prep, and seasonal clean-ups. We transform yards with care and creativity.</p>
        <a href="handyscapes.html" class="text-blue-600 mt-4 inline-block">Get a Quote →</a>
      </div>
      <div class="p-6 border rounded shadow">
        <h3 class="text-xl font-semibold text-[var(--accent)]">Handy Heroes</h3>
        <p class="mt-2">Repairs, remodeling, basic electrical and plumbing, and skilled installations. Residential and light commercial welcome.</p>
        <a href="heroes.html" class="text-blue-600 mt-4 inline-block">Get a Quote →</a>
      </div>
    </section>

    <section class="mt-16 text-center">
      <h3 class="text-2xl font-semibold mb-4 text-[var(--primary)]">Book, Track, and Get Estimates — All in One Platform</h3>
      <p class="text-gray-600 max-w-2xl mx-auto">Supahandy Inc provides full-service transparency. Clients can schedule directly online, technicians can upload job reports, and admins can access dashboards with live project logs and punch-ins.</p>
      <div class="mt-6 flex justify-center gap-4 flex-wrap">
        <a href="client.html" class="bg-yellow-500 text-white px-5 py-2 rounded shadow hover:bg-yellow-600">Client Portal</a>
        <a href="technician.html" class="bg-green-600 text-white px-5 py-2 rounded shadow hover:bg-green-700">Technician Portal</a>
        <a href="admin.html" class="bg-blue-700 text-white px-5 py-2 rounded shadow hover:bg-blue-800">Admin Portal</a>
      </div>
    </section>
  </main>

  <footer class="bg-gray-100 text-center p-6 mt-12 text-sm text-gray-600">
    &copy; 2025 Supahandy Inc. All rights reserved.<br>
    <a href="mailto:attendantsuper@gmail.com" class="text-blue-600">Contact Admin</a>
  </footer>
</body>
</html>

