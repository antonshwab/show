{{ episode.intro }} 🤓 Show notes: https://github.com/hello-rust/show/episode/{{ episode.number }}

Keywords: {{ episode.keywords | join(sep=", ") }}

{% if episode.markers -%}
Markers (for navigation):

{% for marker in episode.markers -%}
{{ marker }}
{% endfor %}
{% endif -%}


Hello Rust! is a show about the Rust programming language.
My goal is to address beginner and intermediate Rust questions and show that systems programming can be a lot of fun!

SUBSCRIBE: https://www.youtube.com/channel/UCZ_EWaQZCZuGGfnuqUoHujw  
WEBSITE: http://hello-rust.show/  
GITHUB: https://github.com/hello-rust/show  
TWITTER: https://twitter.com/hellorustshow  

💖 Support the show by becoming a patron at https://www.patreon.com/hellorust