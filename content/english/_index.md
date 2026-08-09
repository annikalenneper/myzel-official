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
  content: "Myzel ist ein freies und unkommerzielles Kollektiv aus Köln, das Techno und House liebt und lebt. Wir verstehen uns als lebendiges Netzwerk aus Menschen, Ideen und Leidenschaft für elektronische Musik. <br><br>Wir feiern nicht einfach, wir bauen eigene Welten: Räume voller Klang, Licht und Magie. Unsere Raves entstehen wie ein Myzelium – im Verborgenen, gemeinsam, durch unzählige Hände und Gedanken, die zusammen etwas Größeres erschaffen. Was uns antreibt, ist die Liebe zum Detail, die Freude am Teilen und der Wunsch, einen Ort zu schaffen, an dem sich jede*r frei, sicher und willkommen fühlen kann. <br><br> Myzel wächst mit jedem Beat, jeder helfenden Hand, jeder neuen Begegnung. Wir feiern das Leben – respektvoll, bewusst und immer ein bisschen magisch."

# Features
features:
  - title: "UP NEXT"
    image: "/images/myzel_down_imSommerglueck.jpeg"
    content: "📍 Auf der Lichtung (Hürth)<br>🔊 down. Records × Myzel<br>☀️ Tickets im VVK erhältlich<br><br>Line up:<br>Überhaupt & Außerdem (Live)<br>Deep Ändi (Live)<br>I.M.D. (Live)<br>Nyo Mirage (NUAH)<br>Katschinka<br>Kira Kete<br>Rota<br>Myzel Crew"
    button:
      enable: true
      label: "Tickets"
      link: "https://pretix.eu/myzel/down/?utm_source=ig&utm_medium=social&utm_content=link_in_bio"

  - title: "LAGEPLAN"
    image: "/images/mzyel_down_lageplan.jpeg"
    content: "📍 Anfahrt leicht gemacht!<br><br>Damit ihr entspannt bei Myzel & down. im Sommerglück ankommt, haben wir für euch einen Lage- & Anfahrtsplan erstellt. 🌿<br><br>🚋 KVB Linie 18<br>📍 Haltestelle Fischenich<br><br>🅿️ Parkplatz Fahrrad / Auto / Camper vorhanden.<br><br>Von dort geht’s nur wenige Minuten entlang der Driving Range bis zum Open Air Gelände.<br><br>📍 Open Air Gelände<br>TinCup<br>Bonnstr. 409<br>50354 Köln / Hürth"

  - title: "AWARENESS"
    content: "Wir wünschen uns, dass bei Myzel alle frei und sicher feiern können. Kommt auf uns zu, wenn ihr euch während des Raves unwohl fühlt oder kritisches Verhalten beobachtet. <br><br> Es gibt einen Code of Conduct!<br><br> Je mehr Leute ihn kennen, desto besser können wir gemeinsam eine sichere, entspannte und inklusive Atmosphäre kreieren."
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