---
layout: page
title: Search
---

<div style="display: flex; place-content: start center; width: 100%; min-height: 50vh; background-image: linear-gradient(to bottom right, #e1e1e1, #c1c1c1)">
    <!-- Html Elements for Search -->
    <div id="search-container" style="width: 90%; margin-top: 4rem;">
        <input type="text" id="search-input" placeholder="search..." style="width: 100%; height: 5rem">
        <ul id="results-container"></ul>
        <ul id="content-results-container"></ul>
    </div>
    <!-- Script pointing to search-script.js -->
    <script src="/assets/js/search.js" type="text/javascript"></script>

    <!-- Configuration -->
    <script>
        SimpleJekyllSearch({
            searchInput: document.getElementById('search-input'),
            resultsContainer: document.getElementById('results-container'),
            json: '/search.json'
        })
    </script>
    <script>
        SimpleJekyllSearch({
            searchInput: document.getElementById('search-input'),
            resultsContainer: document.getElementById('results-container'),
            json: '/search.json'
        })
    </script>
</div>

