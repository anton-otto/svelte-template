<script>
    import "../app.css";
    let showMenu = false;

function toggleNavbar() {
  showMenu = !showMenu;
}
</script>
<div>
    <div>
      <nav
        class="container px-6 py-8 mx-auto md:flex md:justify-center md:items-center"
      >
        <div class="flex items-center">
          <!-- Mobile menu button -->
          <div on:click={toggleNavbar} class="flex md:hidden">
            <button
              type="button"
              class="text-gray-800 hover:text-gray-400 focus:outline-none focus:text-gray-400"
            >
              <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="w-6 h-6">
              <path stroke-linecap="round" stroke-linejoin="round" d="M3.75 6.75h16.5M3.75 12h16.5m-16.5 5.25h16.5" />
            </svg>
            </button>
          </div>
        </div>
  
        <!-- Mobile Menu open: "block", Menu closed: "hidden" -->
        <div
          class="flex-col mt-8 space-y-4 md:flex md:space-y-0 md:flex-row md:items-center md:space-x-10 md:mt-0 dark:text-slate-300 {showMenu
            ? 'flex'
            : 'hidden'}"
        >
            <a href="/" class="hover:text-amber-500">home</a>
            <a href="/achievements" class="hover:text-amber-500">achievements</a>
            <a href="/resources" class="hover:text-amber-500">free resources</a>
            <a href="/testimonials" class="hover:text-amber-500">testimonials</a>
        </div>
      </nav>
    </div>
  </div>


<slot />