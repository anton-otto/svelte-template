<script>
    let testimonials = [
    {
            "date": "15-08-2023",
            "link": "https://twitter.com/AntonOtto_FFC/status/1691248070195896320?s=20",
            "title": "[...] Looks really cool 😁 great work Anton!",
            "name": "-- Sergiu"
        },
        {
            "date": "04-08-2023",
            "link": "https://twitter.com/AntonOtto_FFC/status/1687869779766616064?s=20",
            "title": "[...] I still don't understand how you can be so kind and helpful [...]",
            "name": "-- Lera | Momentum"
        },
        {
            "date": "19-07-2023",
            "link": "https://twitter.com/AntonOtto_FFC/status/1681606256488792067?s=20",
            "title": "Can't stop learning from you!",
            "name": "-- Marina Mironova"
        },
        {
            "date": "07-07-2023",
            "link": "https://twitter.com/AntonOtto_FFC/status/1677225387800010752?s=20",
            "title": "[...] people should follow you [...]",
            "name": "Muaaz • Designer"
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
                        <p class="text-black dark:text-white">Latest Testimonials</p>
              
                        <div class="grid gap-6 mt-3">
                            {#each testimonials as testimonial}
                                <div class="text-neutral-500  items-start grid grid-cols-1 md:grid-cols-3">
                                  <div>
                                    <p class="text-neutral-400 dark:text-neutral-400">{testimonial.date}</p>
                                  </div>
                                  <div class="md:col-span-2 w-full">
                                    <p class="text-black dark:text-white">
                                      <a
                                        href={testimonial.link}
                                        class="underline hover:no-underline duration-200 after:content-['_↗']">
                                        {testimonial.title}
                                      </a>
                                    </p>
                                    <p class="">{testimonial.name}</p>
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