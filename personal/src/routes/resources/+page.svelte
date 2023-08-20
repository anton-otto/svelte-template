<script>
    let resources = [
        {
            "date": "05-07-2023",
            "link": " https://twitter.com/that_igor_/status/1676661795912667149?s=20",
            "title": "Do you want to start earning from the Internet and live a better life?",
            "description": "LOL I sound guru-ish 🤣  But I have nothing to sell!  @nano_fund  GRIT is free and public 🦍 [...]"
        },
        {
            "date": "07-08-2023",
            "link": "https://twitter.com/AntonOtto_FFC/status/1687913501619044352?s=20",
            "title": "Monetization is an important part of creating a sustainable business 🤑",
            "description": "There is 101 ways to monetize your skills and knowledge   But these are my favorites: [...]"
        },
        {
            "date": "09-07-2023",
            "link": "https://twitter.com/AntonOtto_FFC/status/1678152618235908096?s=20",
            "title": "20+ book advices that made me 'rich' between 2012 and 2020 👇",
            "description": "Always take massive action. Multiply your effort by 10X to surpass your goals. [...]"
        },
        {
            "date": "06-07-2023",
            "link": "https://twitter.com/AntonOtto_FFC/status/1677063104872497152?s=20",
            "title": "🧵The 9 paths to finding yourself.",
            "description": "Tried to use own words and thoughts.  Then make it direct and simple.  With a little bit of stupidly simple. [...]"
        }
    ]
</script>

<section>
    <div class="mx-auto max-w-7xl px-8 py-12 lg:pt-12">
        <div class="mx-auto max-w-xl">
            <section>
                <div class="mx-auto max-w-7xl px-8 py-12">
                  <div class="mx-auto max-w-xl">
                    <div class="grid gap-12 md:gap-24">
                      <div class="text-sm font-light">
                        <p class="text-black dark:text-white">Latest Resources</p>
              
                        <div class="grid gap-6 mt-3">
                            {#each resources as resource}
                                <div class="text-neutral-500  items-start grid grid-cols-1 md:grid-cols-3">
                                  <div>
                                    <p class="text-neutral-400 dark:text-neutral-400">{resource.date}</p>
                                  </div>
                                  <div class="md:col-span-2 w-full">
                                    <p class="text-black dark:text-white">
                                      <a
                                        href={resource.link}
                                        class="underline hover:no-underline duration-200 after:content-['_↗']">
                                        {resource.title}
                                      </a>
                                    </p>
                                    <p class="">{resource.description}</p>
                                  </div>
                                </div>
                            {/each}
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </section>
        </div>
    </div>
</section>