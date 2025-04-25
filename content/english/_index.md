---
# Banner
banner:
  # title: "The Ultimate Starter Template You Need To Start Your Hugo Project"
  # content: "Hugoplate is a free starter template built with Hugo and TailwindCSS, providing everything you need to jumpstart your Hugo project and save valuable time."
  image: "/images/header.jpg"
  button:
    enable: false
    label: "Get Started For Free"
    link: "https://github.com/zeon-studio/hugoplate"

# Pre-Features Section (NEU)
pre_features:
  title: "WER WIR SIND"
  content: "Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet. Lorem ipsum dolor sit amet, consetetur sadipscing elitr, sed diam nonumy eirmod tempor invidunt ut labore et dolore magna aliquyam erat, sed diam voluptua. At vero eos et accusam et justo duo dolores et ea rebum. Stet clita kasd gubergren, no sea takimata sanctus est Lorem ipsum dolor sit amet."

# Features
features:
  - title: "UP NEXT"
    image: "/images/flyer-baui.jpg"
    content: "
Mach dich bereit für die nächste Ausgabe des Myzel Collective – dort wo Kultur, Kunst und Community wie Pilzfäden unter der Oberfläche miteinander verwachsen! <br><br>

Ob du Künstlerin, Denkerin oder einfach nur neugierig bist – this one’s for you. <br><br>

Let’s grow together!"
    bulletpoints:
      - "**Wann?** 30. Mai in&outdoor "
      - "**Wo?** Friedenspark "
      - "**Was?** Ein Tag voller Musik, Austausch, kreativer Impulse & Überraschungen."
    button:
      enable: false
      label: "Get Started Now"
      link: "#"

  - title: "AWARENESS"
    image: "/images/awareness.png"
    content: "Wir wünschen uns, dass bei Myzel alle frei und sicher feiern können - ohne Angst vor Belästigung oder Diskriminierung. Kommt auf uns zu, wenn ihr euch während des Raves unwohl fühlt oder kritisches Verhalten beobachtet. <br><br>

    Es gibt einen Code of Conduct!"

    button:
      enable: true
      label: "Code of Conduct"
      link: "/code-of-conduct"

  # - title: "The Top Reasons to Choose Hugo for Your Hugo Project"
  #   image: "/images/service-3.png"
  #   content: "With Hugo, you can build modern and content-focused websites without sacrificing performance or ease of use."
  #   bulletpoints:
  #     - "Instantly load static sites for better user experience and SEO."
  #     - "Intuitive syntax and support for popular frameworks make learning and using Hugo a breeze."
  #     - "Use any front-end library or framework, or build custom components, for any project size."
  #     - "Built on cutting-edge technology to keep your projects up-to-date with the latest web standards."
  #   button:
  #     enable: false
  #     label: ""
  #     link: ""
---

<!-- Galerie für größere Bildschirme (Tablet aufwärts, md-Breakpoint von Tailwind) -->
<div class="hidden md:block">
  {{< gallery dir="images/gallery" class="" height="400" width="400" webp="true" command="Fit" option="" zoomable="true" >}}
</div>

<!-- Slider für kleinere Bildschirme (Smartphone) -->
<div class="block md:hidden">
  {{< slider dir="images/gallery" class="max-w-[600px] mx-auto" height="400" width="400" webp="true" command="Fit" option="" zoomable="true" >}}
</div>