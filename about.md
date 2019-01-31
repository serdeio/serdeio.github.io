---
layout: page
title: About
permalink: /about/
---

<script defer src="https://s3.us-east-2.amazonaws.com/serde/serde.js"></script>

<script>
    (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
    (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
    m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
    })(window,document,'script','https://www.google-analytics.com/analytics.js','ga');
    ga('create', 'UA-73327015-1', 'auto');
    ga('require', 'serde', {debug: false, endpoint: 'https://pitqj79xxe.execute-api.us-east-1.amazonaws.com/dev/v1/ingestion-engine'});
    ga('send', 'pageview');
</script>

# Serde
0 to SQL in 60 Seconds

<a class="btn btn-large btn-success" href="#" onclick="fire();">Send Test Track</a>

<script>
    function fire() {
        console.log('*Bang!*')
        ga('send', {
        hitType: 'event',
        eventCategory: 'Test',
        eventAction: 'click',
        eventLabel: 'Simplest hello world test',
        customValue: 42
        });
    }
</script>
