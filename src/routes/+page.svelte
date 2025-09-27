<script>
  // You can put your name, tagline, and social links here
  let name = "xCode";
  let tagline = "Building digital experiences with code & design.";
  let cta = "View My Work";
</script>

<!-- Full screen hero -->
<section class="relative flex items-center justify-center h-screen overflow-hidden bg-gradient-to-br from-gray-900 via-black to-gray-800 text-white">
  
  <!-- Background gradient animation -->
  <div class="absolute inset-0 bg-gradient-to-r from-purple-500 via-pink-500 to-yellow-500 opacity-20 animate-pulse"></div>
  
  <!-- Content -->
  <div class="relative z-10 text-center max-w-3xl px-6">
    <!-- Name -->
    <h1 class="text-5xl md:text-7xl font-extrabold tracking-tight mb-4">
      {name}
    </h1>
    
    <!-- Tagline -->
    <p class="text-xl md:text-2xl text-gray-300 mb-8">
      {tagline}
    </p>
    
    <!-- Call to Action -->
    <a href="#projects" 
       class="inline-block px-6 py-3 text-lg font-medium rounded-2xl bg-gradient-to-r from-pink-500 to-yellow-500 text-black shadow-lg hover:scale-105 transition-transform">
       {cta}
    </a>
  </div>

  <!-- Floating background shapes -->
  <div class="absolute top-10 left-10 w-24 h-24 bg-purple-500 rounded-full mix-blend-screen filter blur-2xl opacity-30 animate-bounce"></div>
  <div class="absolute bottom-20 right-20 w-32 h-32 bg-pink-500 rounded-full mix-blend-screen filter blur-2xl opacity-30 animate-pulse"></div>
</section>
