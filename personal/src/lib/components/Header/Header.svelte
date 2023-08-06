<script>
    import avatar from '$lib/assets/avatar.webp';

    export let name;
    export let subtitle;
    export let website;
</script>

<section>
    <div class="mx-auto max-w-7xl px-8 py-12 lg:pt-24">
      <div class="mx-auto max-w-xl">
        <div>
          <div class="md:flex md:items-center md:justify-between md:space-x-5">
            <div class="flex items-center space-x-5">
              <div class="flex-shrink-0">
                <div class="relative">
                  <img
                    class="h-16 w-16 lg:h-28 lg:w-28 rounded-full border border-white/10"
                    src={avatar}
                    alt="avatar"
                  />
                  <span
                    class="absolute inset-0 rounded-full shadow-inner"
                    aria-hidden="true"></span>
                </div>
              </div>
  
              <div class="pt-1.5">
                <h1 class="lg:text-2xl text-black dark:text-white">
                  ✺ {name}
                </h1>
                <p class="text-md font-light text-neutral-500">
                  {subtitle}
                </p>
                <p class="mb-2">
                  <a
                    class="text-md underline hover:no-underline duration-200 dark:text-white"
                    href="https://twitter.com/AntonOtto_FFC" target="_blank">{website}</a
                  >
                </p>
                <a href="https://buy.stripe.com/14keUY4f1cwXgmY4gh?prefilled_promo_code=GORILLAGANG" class="rounded px-2 py-1 bg-[#EDA414] text-slate-800 font-bold text-sm md:text-md">Book now for only $19,80/hr</a>
              </div>
              

            </div>
          </div>
          <div class="mt-12 text-md font-light">
            <p class="text-black dark:text-slate-100 font-bold">About</p>
            <div class="text-neutral-500 dark:text-neutral-300 space-y-3 mt-3">
              <p>
                It all started with the curiosity of tech since I owned an Amiga a500. 
                At age 13 I got more into coding due to Second Life.
              </p>
              <p>
                From robotics and microcotrollers, to Python code for factory automation. 
                I have tried it all.
              </p>
              <p>
                Now I am learning how to use the internet. 
                My knowledge is endless and it is time for me to build systems which are lasting and help more people.
              </p>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>