<script>
    export let tweets;
</script>

<section>
    <div class="mx-auto max-w-7xl px-8 py-12">
      <div class="mx-auto max-w-xl">
        <div class="grid gap-12 md:gap-24">
          <div class="text-sm font-light">
            <p class="text-black dark:text-white font-medium">Top Tweets</p>
  
            <div class="grid gap-6 mt-3">
                {#each tweets as tweet}
                    <div class="text-neutral-500  items-start grid grid-cols-1 md:grid-cols-3">
                      <div>
                        <p class="text-neutral-400 dark:text-neutral-400">{tweet.date}</p>
                      </div>
                      <div class="md:col-span-2 w-full">
                        <p class="text-black dark:text-white">
                          <a
                            href={tweet.link}
                            class="underline hover:no-underline duration-200 after:content-['_↗']">
                            {tweet.title}
                          </a>
                        </p>
                        <p class="">{tweet.description}</p>
                      </div>
                    </div>
                {/each}
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>