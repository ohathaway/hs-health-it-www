<template>
  <div>
    <!-- Header Section -->
    <header class="bg-white shadow-lg py-4">
      <div class="container mx-auto flex justify-between items-center">
        <h1 class="text-2xl font-bold">HS Health IT</h1>
        <nav>
          <a href="#" class="mx-4 text-gray-600 hover:text-blue-600">Home</a>
          <a href="#services" class="mx-4 text-gray-600 hover:text-blue-600">Services</a>
        </nav>
        <a href="https://support.hshealthit.com" class="bg-blue-500 text-white px-4 py-2 rounded-lg">Get Support</a>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-blue-50 py-16 text-center">
      <h2 class="text-4xl font-bold mb-4">IT Solutions for Healthcare Professionals</h2>
      <p class="text-lg mb-8">Providing expert IT solutions tailored to healthcare professionals, so you can focus on what matters most—caring for your patients.</p>
      <div class="flex justify-center space-x-4">
        <a href="https://support.hshealthit.com" class="bg-blue-500 text-white px-6 py-3 rounded-lg">Access Support Portal</a>
        <a href="mailto:support@hshealthit.com" class="bg-gray-500 text-white px-6 py-3 rounded-lg">Contact Us</a>
      </div>
    </section>

    <!-- About Us Section -->
    <section class="py-16 container mx-auto">
      <h2 class="text-3xl font-bold text-center mb-8">Why Choose HS Health IT?</h2>
      <div class="grid grid-cols-2 gap-8">
        <div>
          <p class="text-lg">At HS Health IT, we leverage decades of combined experience to deliver healthcare-focused IT support services.</p>
        </div>
        <div>
          <ul class="list-disc ml-8">
            <li>Data Security and Compliance</li>
            <li>IT Infrastructure Support</li>
            <li>24/7 Dedicated IT Support</li>
          </ul>
        </div>
      </div>
    </section>

    <!-- Services Section -->
    <section id="services" class="bg-gray-100 py-16">
      <h2 class="text-3xl font-bold text-center mb-8">Our IT Support Services</h2>
      <div class="grid grid-cols-3 gap-8 container mx-auto">
        <div>
          <h3 class="text-xl font-semibold mb-4">Healthcare IT Infrastructure Support</h3>
          <p>We ensure your healthcare infrastructure is secure and compliant with industry standards.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-4">Data Security and Compliance</h3>
          <p>Protect your data with our security protocols tailored to the healthcare industry.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-4">24/7 IT Support</h3>
          <p>Our dedicated team is available around the clock to assist with any IT issues.</p>
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white py-8">
      <div class="container mx-auto text-center">
        <p>Contact us: support@hshealthit.com | (720) 986-7175</p>
        <p>© 2024 HS Health IT</p>
      </div>
    </footer>
  </div>
</template>