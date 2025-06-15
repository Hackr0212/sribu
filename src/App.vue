<template>
  <div class="min-h-screen bg-white">
    <!-- Header -->
    <header class="bg-white shadow-sm border-b border-gray-100">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="flex justify-between items-center py-4">
          <div class="flex items-center">
            <div class="text-2xl font-bold text-primary">
              Sribu<span class="text-gray-600">.com</span>
            </div>
          </div>
          <nav class="hidden md:flex space-x-8">
            <a href="#portfolio" class="text-gray-600 hover:text-primary transition-colors">Portfolio</a>
            <a href="#how-it-works" class="text-gray-600 hover:text-primary transition-colors">How It Works</a>
            <a href="#testimonials" class="text-gray-600 hover:text-primary transition-colors">Testimonials</a>
          </nav>
        </div>
      </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-gradient-to-br from-primary/5 to-white py-20">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center">
          <h1 class="text-5xl md:text-6xl font-bold text-gray-900 mb-6">
            Work with Talented
            <span class="text-primary block">Graphic Designers</span>
            Online
          </h1>
          <p class="text-xl text-gray-600 mb-8 max-w-3xl mx-auto leading-relaxed">
            Access quality design ideas from talented designers worldwide without the hassle of offline meetings. 
            Get professional designs that elevate your brand through our innovative contest-based platform.
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center items-center">
            <button class="bg-primary text-white px-8 py-4 rounded-lg font-semibold hover:bg-primary/90 transition-all transform hover:scale-105 shadow-lg">
              Start Your Design Contest
            </button>
            <a href="#portfolio" class="text-primary font-semibold hover:underline">
              View Our Portfolio →
            </a>
          </div>
        </div>
      </div>
    </section>

    <!-- Problem Statement -->
    <section class="py-16 bg-gray-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-12">
          <h2 class="text-3xl font-bold text-gray-900 mb-4">
            The Challenge of Finding Great Design
          </h2>
          <p class="text-lg text-gray-600 max-w-3xl mx-auto">
            Traditional design sourcing methods often fall short, leaving businesses struggling with limited options, 
            high costs, and uncertain quality. There has to be a better way.
          </p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8">
          <div class="text-center p-6">
            <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8v4m0 4h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Limited Options</h3>
            <p class="text-gray-600">Traditional methods give you only one designer's perspective, limiting creative possibilities.</p>
          </div>
          
          <div class="text-center p-6">
            <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M12 8c-1.657 0-3 .895-3 2s1.343 2 3 2 3 .895 3 2-1.343 2-3 2m0-8c1.11 0 2.08.402 2.599 1M12 8V7m0 1v8m0 0v1m0-1c-1.11 0-2.08-.402-2.599-1"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">High Costs</h3>
            <p class="text-gray-600">Agencies and in-house designers come with hefty price tags and ongoing commitments.</p>
          </div>
          
          <div class="text-center p-6">
            <div class="w-16 h-16 bg-red-100 rounded-full flex items-center justify-center mx-auto mb-4">
              <svg class="w-8 h-8 text-red-600" fill="none" stroke="currentColor" viewBox="0 0 24 24">
                <path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8.228 9c.549-1.165 2.03-2 3.772-2 2.21 0 4 1.343 4 3 0 1.4-1.278 2.575-3.006 2.907-.542.104-.994.54-.994 1.093m0 3h.01M21 12a9 9 0 11-18 0 9 9 0 0118 0z"></path>
              </svg>
            </div>
            <h3 class="text-xl font-semibold text-gray-900 mb-2">Uncertain Quality</h3>
            <p class="text-gray-600">No guarantee that the final design will meet your expectations or brand standards.</p>
          </div>
        </div>
      </div>
    </section>

    <!-- Comparison Chart -->
    <section class="py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-12">
          <h2 class="text-3xl font-bold text-gray-900 mb-4">
            Why Choose Sribu Over Traditional Options?
          </h2>
          <p class="text-lg text-gray-600">
            See how our platform compares to other design sourcing methods
          </p>
        </div>

        <div class="overflow-x-auto">
          <table class="w-full bg-white rounded-lg shadow-lg overflow-hidden">
            <thead class="bg-primary text-white">
              <tr>
                <th class="px-6 py-4 text-left font-semibold">Features</th>
                <th class="px-6 py-4 text-center font-semibold">Sribu.com</th>
                <th class="px-6 py-4 text-center font-semibold">Freelancers</th>
                <th class="px-6 py-4 text-center font-semibold">In-house Designer</th>
                <th class="px-6 py-4 text-center font-semibold">Design Agency</th>
              </tr>
            </thead>
            <tbody class="divide-y divide-gray-200">
              <tr>
                <td class="px-6 py-4 font-medium text-gray-900">Multiple Design Options</td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-red-600 text-xl">✗</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-red-600 text-xl">✗</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-yellow-600 text-xl">~</span>
                </td>
              </tr>
              <tr class="bg-gray-50">
                <td class="px-6 py-4 font-medium text-gray-900">Cost Effective</td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-red-600 text-xl">✗</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-red-600 text-xl">✗</span>
                </td>
              </tr>
              <tr>
                <td class="px-6 py-4 font-medium text-gray-900">Quality Guarantee</td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-red-600 text-xl">✗</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-yellow-600 text-xl">~</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
              </tr>
              <tr class="bg-gray-50">
                <td class="px-6 py-4 font-medium text-gray-900">Fast Turnaround</td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-yellow-600 text-xl">~</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-red-600 text-xl">✗</span>
                </td>
              </tr>
              <tr>
                <td class="px-6 py-4 font-medium text-gray-900">No Long-term Commitment</td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-green-600 text-xl">✓</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-red-600 text-xl">✗</span>
                </td>
                <td class="px-6 py-4 text-center">
                  <span class="text-red-600 text-xl">✗</span>
                </td>
              </tr>
            </tbody>
          </table>
        </div>
      </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-16 bg-gray-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-12">
          <h2 class="text-3xl font-bold text-gray-900 mb-4">
            Discover Quality Designs from Our Platform
          </h2>
          <p class="text-lg text-gray-600 mb-8">
            See the exceptional work created by our talented designers for businesses like yours
          </p>
          <div class="flex flex-col sm:flex-row gap-4 justify-center">
            <a href="#" class="bg-primary text-white px-6 py-3 rounded-lg font-semibold hover:bg-primary/90 transition-colors">
              View Full Portfolio
            </a>
            <a href="#testimonials" class="border border-primary text-primary px-6 py-3 rounded-lg font-semibold hover:bg-primary hover:text-white transition-colors">
              Read Testimonials
            </a>
          </div>
        </div>

        <!-- Portfolio Grid -->
        <div class="grid md:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition-shadow">
            <div class="h-48 bg-gradient-to-br from-blue-400 to-purple-500"></div>
            <div class="p-6">
              <h3 class="font-semibold text-gray-900 mb-2">Brand Identity Design</h3>
              <p class="text-gray-600 text-sm">Complete branding package for tech startup</p>
            </div>
          </div>
          
          <div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition-shadow">
            <div class="h-48 bg-gradient-to-br from-green-400 to-blue-500"></div>
            <div class="p-6">
              <h3 class="font-semibold text-gray-900 mb-2">Website Design</h3>
              <p class="text-gray-600 text-sm">Modern e-commerce website design</p>
            </div>
          </div>
          
          <div class="bg-white rounded-lg shadow-md overflow-hidden hover:shadow-lg transition-shadow">
            <div class="h-48 bg-gradient-to-br from-pink-400 to-red-500"></div>
            <div class="p-6">
              <h3 class="font-semibold text-gray-900 mb-2">Marketing Materials</h3>
              <p class="text-gray-600 text-sm">Print and digital marketing collateral</p>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Email Capture Section -->
    <section class="py-16 bg-primary">
      <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
        <h2 class="text-3xl font-bold text-white mb-4">
          Get Your Complete Guide to Working with Talented Designers Online
        </h2>
        <p class="text-xl text-white/90 mb-8">
          Enter your email to receive our comprehensive guide on how to get the best designs for your business. 
          No spam, just valuable insights.
        </p>
        
        <form class="max-w-md mx-auto">
          <div class="flex flex-col sm:flex-row gap-4">
            <input 
              type="email" 
              placeholder="Enter your email address"
              class="flex-1 px-4 py-3 rounded-lg border-0 focus:ring-2 focus:ring-white/50 outline-none"
              required
            >
            <button 
              type="submit"
              class="bg-white text-primary px-6 py-3 rounded-lg font-semibold hover:bg-gray-100 transition-colors"
            >
              Get Free Guide
            </button>
          </div>
          <p class="text-white/80 text-sm mt-4">
            We respect your privacy. Unsubscribe at any time.
          </p>
        </form>
      </div>
    </section>

    <!-- About Section -->
    <section class="py-16">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid lg:grid-cols-2 gap-12 items-center">
          <div>
            <h2 class="text-3xl font-bold text-gray-900 mb-6">
              About Sribu.com
            </h2>
            <p class="text-lg text-gray-600 mb-6">
              Sribu.com is a revolutionary platform that connects clients and designers globally through our innovative 
              contest-based concept. We bridge the gap between businesses needing quality design and talented designers 
              worldwide who are ready to bring your vision to life.
            </p>
            <p class="text-lg text-gray-600 mb-6">
              Our platform offers various design categories including logo design, website design, print materials, 
              packaging, and more. Through our contest system, you receive multiple design options from different 
              designers, ensuring you get the perfect design that matches your brand and vision.
            </p>
            <div class="space-y-4">
              <div class="flex items-center">
                <div class="w-2 h-2 bg-primary rounded-full mr-3"></div>
                <span class="text-gray-700">Global network of talented designers</span>
              </div>
              <div class="flex items-center">
                <div class="w-2 h-2 bg-primary rounded-full mr-3"></div>
                <span class="text-gray-700">Contest-based design process</span>
              </div>
              <div class="flex items-center">
                <div class="w-2 h-2 bg-primary rounded-full mr-3"></div>
                <span class="text-gray-700">Multiple design categories available</span>
              </div>
              <div class="flex items-center">
                <div class="w-2 h-2 bg-primary rounded-full mr-3"></div>
                <span class="text-gray-700">Perfect for SMBs and entrepreneurs</span>
              </div>
            </div>
          </div>
          
          <div class="bg-gray-50 rounded-lg p-8">
            <h3 class="text-xl font-semibold text-gray-900 mb-4">Our Target Market</h3>
            <div class="space-y-4">
              <div class="flex items-start">
                <div class="w-6 h-6 bg-primary/10 rounded-full flex items-center justify-center mr-3 mt-1">
                  <div class="w-2 h-2 bg-primary rounded-full"></div>
                </div>
                <div>
                  <h4 class="font-medium text-gray-900">Small to Medium Businesses</h4>
                  <p class="text-gray-600 text-sm">Companies with less than 20 employees looking for professional design solutions</p>
                </div>
              </div>
              
              <div class="flex items-start">
                <div class="w-6 h-6 bg-primary/10 rounded-full flex items-center justify-center mr-3 mt-1">
                  <div class="w-2 h-2 bg-primary rounded-full"></div>
                </div>
                <div>
                  <h4 class="font-medium text-gray-900">Entrepreneurs</h4>
                  <p class="text-gray-600 text-sm">Business owners aged 24-58 who need quality design without the overhead</p>
                </div>
              </div>
              
              <div class="flex items-start">
                <div class="w-6 h-6 bg-primary/10 rounded-full flex items-center justify-center mr-3 mt-1">
                  <div class="w-2 h-2 bg-primary rounded-full"></div>
                </div>
                <div>
                  <h4 class="font-medium text-gray-900">Startups</h4>
                  <p class="text-gray-600 text-sm">New businesses needing professional branding and design materials</p>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Testimonials -->
    <section id="testimonials" class="py-16 bg-gray-50">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-12">
          <h2 class="text-3xl font-bold text-gray-900 mb-4">
            What Our Clients Say
          </h2>
          <p class="text-lg text-gray-600">
            Hear from businesses that have transformed their brand with our platform
          </p>
        </div>

        <div class="grid md:grid-cols-3 gap-8">
          <div class="bg-white rounded-lg shadow-md p-6">
            <div class="flex items-center mb-4">
              <div class="flex text-yellow-400">
                <span>★★★★★</span>
              </div>
            </div>
            <p class="text-gray-600 mb-4">
              "Sribu gave us exactly what we needed - multiple design options at an affordable price. 
              The quality exceeded our expectations!"
            </p>
            <div class="flex items-center">
              <div class="w-10 h-10 bg-gray-300 rounded-full mr-3"></div>
              <div>
                <h4 class="font-semibold text-gray-900">Sarah Johnson</h4>
                <p class="text-gray-600 text-sm">CEO, TechStart Inc.</p>
              </div>
            </div>
          </div>

          <div class="bg-white rounded-lg shadow-md p-6">
            <div class="flex items-center mb-4">
              <div class="flex text-yellow-400">
                <span>★★★★★</span>
              </div>
            </div>
            <p class="text-gray-600 mb-4">
              "The contest format was brilliant. We received 15+ designs and found the perfect one 
              that captured our brand essence."
            </p>
            <div class="flex items-center">
              <div class="w-10 h-10 bg-gray-300 rounded-full mr-3"></div>
              <div>
                <h4 class="font-semibold text-gray-900">Michael Chen</h4>
                <p class="text-gray-600 text-sm">Founder, GreenEats</p>
              </div>
            </div>
          </div>

          <div class="bg-white rounded-lg shadow-md p-6">
            <div class="flex items-center mb-4">
              <div class="flex text-yellow-400">
                <span>★★★★★</span>
              </div>
            </div>
            <p class="text-gray-600 mb-4">
              "Fast, affordable, and high-quality. Sribu solved our design challenges without 
              breaking the budget."
            </p>
            <div class="flex items-center">
              <div class="w-10 h-10 bg-gray-300 rounded-full mr-3"></div>
              <div>
                <h4 class="font-semibold text-gray-900">Lisa Rodriguez</h4>
                <p class="text-gray-600 text-sm">Marketing Director, LocalBiz</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-900 text-white py-12">
      <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid md:grid-cols-4 gap-8">
          <div>
            <div class="text-2xl font-bold mb-4">
              Sribu<span class="text-gray-400">.com</span>
            </div>
            <p class="text-gray-400">
              Connecting clients and designers worldwide through innovative contest-based design solutions.
            </p>
          </div>
          
          <div>
            <h3 class="font-semibold mb-4">Services</h3>
            <ul class="space-y-2 text-gray-400">
              <li><a href="#" class="hover:text-white transition-colors">Logo Design</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Website Design</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Print Design</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Packaging Design</a></li>
            </ul>
          </div>
          
          <div>
            <h3 class="font-semibold mb-4">Company</h3>
            <ul class="space-y-2 text-gray-400">
              <li><a href="#" class="hover:text-white transition-colors">About Us</a></li>
              <li><a href="#" class="hover:text-white transition-colors">How It Works</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Pricing</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Contact</a></li>
            </ul>
          </div>
          
          <div>
            <h3 class="font-semibold mb-4">Connect</h3>
            <ul class="space-y-2 text-gray-400">
              <li><a href="#" class="hover:text-white transition-colors">Support</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Community</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Blog</a></li>
              <li><a href="#" class="hover:text-white transition-colors">Newsletter</a></li>
            </ul>
          </div>
        </div>
        
        <div class="border-t border-gray-800 mt-8 pt-8 text-center text-gray-400">
          <p>&copy; 2025 Sribu.com. All rights reserved.</p>
        </div>
      </div>
    </footer>
  </div>
</template>

<script setup lang="ts">
// Landing page functionality can be added here
</script>

<style scoped>
/* Additional custom styles if needed */
</style>