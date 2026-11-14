---
layout: null
permalink: /visits/
sitemap: false
---
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Talks &amp; Visits | Kesavan Mohana Sundaram</title>
  <link rel="canonical" href="{{ '/talks/' | absolute_url }}">
  <meta http-equiv="refresh" content="0; url={{ '/talks/#research-visits' | relative_url }}">
  <script>
    let fragment = window.location.hash || '#research-visits';
    if (/^#20\d{2}$/.test(fragment)) fragment = '#conferences-' + fragment.slice(1);
    window.location.replace({{ '/talks/' | relative_url | jsonify }} + fragment);
  </script>
</head>
<body>
  <p>This page has moved to <a href="{{ '/talks/' | relative_url }}">Talks &amp; Visits</a>.</p>
</body>
</html>
