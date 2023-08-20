<script>
    let tournaments = [
        {
            "date": "31-08-2023",
            "link": "",
            "title": "Valkenburg Series Of Poker - Main Event",
            "cost": "785",
            "stake": "40",
            "status": "sold out"
        },
        
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
                        <p class="text-black dark:text-white font-medium">Upcoming</p>
              
                        <div class="grid gap-6 mt-3">
                            {#each tournaments as tournament}
                                <div class="text-neutral-500  items-start grid grid-cols-1 md:grid-cols-3">
                                  <div>
                                    <p class="text-neutral-400 dark:text-neutral-400">{tournament.date}</p>
                                  </div>
                                  <div class="md:col-span-2 w-full">
                                    <p class="text-black dark:text-white">
                                      <a
                                        href={tournament.link}
                                        class="underline hover:no-underline duration-200 after:content-['_↗']">
                                        {tournament.title}
                                      </a>
                                    </p>
                                    <p class="">€{tournament.cost} | Staked: {tournament.stake}% | {tournament.status}</p>
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