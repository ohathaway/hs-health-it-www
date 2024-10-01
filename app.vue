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
    <section class="bg-lightGray py-16 text-center">
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
          <p class="text-lg">At HS Health IT, we're proud to offer tailored IT solutions to healthcare practices referred through trusted partners. Whether you're a small clinic or a growing practice, we're here to provide expert support without the pressure of upselling. Our focus is on building lasting, reliable relationships—because your success is our success.</p>
        </div>
        <div>
          <ul class="list-disc ml-8">
            <li>Data Security and Compliance</li>
            <li>IT Infrastructure Support</li>
            <li>Vendor Management</li>
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
          <p>We ensure your healthcare IT systems are reliable and optimized for performance. From managing network configurations to server maintenance, we handle the technical side so your practice can run smoothly without interruptions.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-4">Data Security and Compliance</h3>
          <p>Safeguard sensitive patient information with our comprehensive security measures. We help you stay compliant with healthcare regulations like HIPAA, ensuring your data is protected from breaches and vulnerabilities.</p>
        </div>
        <div>
          <h3 class="text-xl font-semibold mb-4">Vendor Management</h3>
          <p>We coordinate with your software and medical device vendors, like EMR systems and medical imaging providers, to make sure everything works as needed. Acting as your point of contact, we help you navigate complex vendor relationships so you can focus on patient care.</p>
        </div>
      </div>
    </section>

    <!-- Footer Section -->
    <footer class="bg-gray-800 text-white py-8">
      <div class="container mx-auto text-center">
        <p>Contact us: <a href="mailto:support@hshealthit.com">support@hshealthit.com</a> | <a href="tel:+17209867175">720-986-7175</a></p>
        <p>© 2024 HS Health IT</p>
      </div>
    </footer>
  </div>
</template>