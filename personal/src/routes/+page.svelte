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
</script>

<Header {name} {subtitle} {website} />
<TweetSummary />
