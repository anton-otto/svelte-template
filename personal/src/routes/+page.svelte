<script>
    import Header from "$lib/components/Header/Header.svelte";
    import TweetSummary from "$lib/components/TweetSummary/TweetSummary.svelte";

    let person = {
        name: "Anton Otto",
        subtitle: "Webdeveloper using the internet!",
        website: "antonotto.nl",
    };

    let name = person.name;
    let subtitle = person.subtitle;
    let website = person.website;



    let tweets = [
    {
        "date": "12-07-2023",
        "link": "https://twitter.com/AntonOtto_FFC/status/1679213807552323584?s=20",
        "title": "12 of my Mantras",
        "description": "12 of my Mantras YOU SHOULD not only Recite but try to understand and integrate in your life!"
    },
    {
        "date": "22-07-2023",
        "link": "https://twitter.com/AntonOtto_FFC/status/1682515996739772418?s=20",
        "title": "Let me share you a story.",
        "description": "Let me share you a story.  About me.  Lately I get some questions from people about how I do so much.  And what motivates me.  Is it my daughters?  Is it something else? [...]"
    },
    {
        "date": "07-08-2023",
        "link": "https://twitter.com/AntonOtto_FFC/status/1687913501619044352?s=20",
        "title": "Monetization is an important part of creating a sustainable business 🤑",
        "description": "There is 101 ways to monetize your skills and knowledge   But these are my favorites: [...]"
    }


   
    ]
</script>

<Header {name} {subtitle} {website} />
<TweetSummary {tweets} />

