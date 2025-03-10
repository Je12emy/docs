---
layout: ~/layouts/MainLayout.astro
title: Warum Astro?
description: "Astro ist ein Web-Framework, das eine Komplettlösung zur Erstellung schneller, inhaltsfokussierter Websites darstellt."
i18nReady: true
---
Astro ist ein **Web-Framework**, das eine **Komplettlösung** zur Erstellung **schneller**, **inhaltsfokussierter** Websites darstellt.

Warum sollte man Astro einem anderen Web-Framework vorziehen? Hier sind 5 Kern-Designkonzepte, um dir zu zeigen, warum wir Astro entwickelt haben, welche Probleme damit gelöst werden können und warum Astro die beste Wahl für dein Projekt oder Team sein könnte.

#### Astro ist...

1. [Inhaltsfokussiert](#inhaltsfokussiert): Astro wurde für inhaltsreiche Websites entworfen.
2. [Server-first](#server-first): Websites sind schneller, wenn sie HTML auf dem Server rendern.
3. [Standardmäßig schnell](#standardmäßig-schnell): Es sollte nahezu unmöglich sein, mit Astro eine langsame Website zu erstellen.
4. [Einfach zu benutzen](#einfach-zu-benutzen): Du musst kein Experte sein, um etwas mit Astro zu erstellen.
5. [Funktionsreich, aber flexibel](#funktionsreich-aber-flexibel): Über 100+ Astro Integrationen zur Auswahl.


## Inhaltsfokussiert

**Astro wurde für das Entwickeln von inhaltsfokussierten Websites entworfen.** Dazu gehören die meisten Marketing-Websites, Verlagsseiten, Dokumentations-Websites, Blogs, Portfolios und einige E-Commerce-Websites.

Im Gegensatz dazu sind die meisten modernen Web-Frameworks für die Erstellung von *Webanwendungen* konzipiert. Diese Frameworks eignen sich am besten für die Erstellung komplexer, anwendungsähnlicher Erlebnisse im Browser: Admin-Dashboards mit Login, Posteingänge, soziale Netzwerke, ToDo-Listen und sogar nativ wirkende Anwendungen wie [Figma](https://figma.com) und [Ping](https://ping.gg).

Dies ist einer der wichtigsten Unterschiede, die es bei Astro zu verstehen gilt. Der einzigartige Fokus von Astro auf Inhalte ermöglicht es, Kompromisse einzugehen und unübertroffene Leistungsmerkmale zu liefern, deren Implementierung für anwendungsorientierte Web-Frameworks nicht sinnvoll wäre.


:::tip
Wenn dein Projekt in das zweite "Anwendungs"-Gebiet fällt, ist Astro vielleicht nicht die richtige Wahl für dein Projekt... **und das ist in Ordnung!** Schaue dir [Next.js](https://nextjs.org) an, um eine großartige, anwendungsorientierte Web-Framework-Alternative zu finden.
:::




## Server-first

**Astro setzt so weit wie möglich auf serverseitiges Rendering statt auf clientseitiges Rendering.** Dies ist derselbe Ansatz, den traditionelle serverseitige Frameworks — PHP, WordPress, Laravel, Ruby on Rails usw. — schon seit Jahrzehnten verwenden. Allerdings musst du keine zweite serverseitige Sprache lernen, um Astro zu nutzen, denn in Astro besteht alles nur aus HTML, CSS und JavaScript (oder TypeScript, falls du dieses bevorzugst).

Dieser Ansatz steht im Gegensatz zu anderen modernen JavaScript-Web-Frameworks wie Next.js, SvelteKit, Nuxt, Remix und weiteren. Diese Frameworks erfordern das clientseitige Rendering der gesamten Website und beinhalten das serverseitige Rendering hauptsächlich, um Leistungsprobleme zu lösen. Dieser Ansatz wird als **Single Page App (SPA)** bezeichnet, im Gegensatz zum **Multi Page App (MPA)**-Ansatz von Astro.

Das SPA-Modell hat seine Vorteile, diese kommen jedoch zum Preis zusätzlicher Komplexität und reduzierter Leistung. Solche Kompromisse schaden der Website-Leistung — einschließlich kritischer Metriken wie [Time to Interactive (TTI)](https://web.dev/interactive/). Gerade für inhaltsfokussierte Websites ist dies nicht sehr sinnvoll, da hier die Leistung beim ersten Laden entscheidend ist.

📚 [Erfahre mehr darüber, was die MPA-Architektur von Astro einzigartig macht](/de/concepts/mpa-vs-spa/)


## Standardmäßig schnell

Eine gute Leistung ist immer wichtig, aber sie ist *besonders* wichtig für inhaltsfokussierte Websites. Es ist erwiesen, dass eine schlechte Leistung zu einem Verlust an Engagement, Konversionen und Einnahmen führt. Ein Beispiel:

- Jede 100ms schneller -> 1% mehr Konversionen ([Mobify](https://web.dev/why-speed-matters/), Verdienst +$380,000/Jahr)
- 50% schneller -> 12% mehr Umsatz ([AutoAnything](https://www.digitalcommerce360.com/2010/08/19/web-accelerator-revs-conversion-and-sales-autoanything/))
- 20% schneller → 10% mehr Konversionen ([Furniture Village](https://www.thinkwithgoogle.com/intl/en-gb/marketing-strategies/app-and-mobile/furniture-village-and-greenlight-slash-page-load-times-boosting-user-experience/))
- 40% schneller → 15% mehr Registrierungen ([Pinterest](https://medium.com/pinterest-engineering/driving-user-growth-with-performance-improvements-cfc50dafadd7))
- 850ms schneller → 7% mehr Konversionen ([COOK](https://web.dev/why-speed-matters/))
- Jede 1 Sekunde langsamer → 10% weniger Nutzer ([BBC](https://www.creativebloq.com/features/how-the-bbc-builds-websites-that-scale))

Bei vielen Web-Frameworks ist es leicht möglich, eine Website zu erstellen, die während der Entwicklung großartig aussieht, aber nach der Veröffentlichung schmerzhaft langsam lädt. JavaScript ist oft der Schuldige, da Smartphones und Geräte mit geringerer Leistung selten die Geschwindigkeit des Laptops eines Entwicklers erreichen.

Die Magie von Astro liegt in der Kombination der beiden oben genannten Werte - ein Fokus auf Inhalte mit einer Server-first MPA-Architektur - um Kompromisse zu machen und Funktionen zu liefern, die andere Frameworks nicht bieten können. Das Ergebnis ist eine erstaunliche Web-Performance für jede Website, Out-of-the-Box. Unser Ziel: **Es sollte nahezu unmöglich sein, mit Astro eine langsame Website zu erstellen.**

Eine Astro-Website kann [mit 90 % weniger JavaScript](https://twitter.com/t3dotgg/status/1437195415439360003) 40 % schneller laden als die gleiche Website, die mit dem beliebten React-Webframework erstellt wurde. Aber nimm uns nicht beim Wort: Sieh dir an, wie Astros Leistung Ryan Carniato (Schöpfer von Solid.js und Marko) [sprachlos](https://youtu.be/2ZEMb_H-LYE?t=8163) macht.


## Einfach zu benutzen

**Das Ziel von Astro ist es, für jeden Webentwickler zugänglich zu sein.** Astro wurde so konzipiert, dass es sich vertraut und zugänglich anfühlt, unabhängig von den Fähigkeiten oder der bisherigen Erfahrung mit Webentwicklung.

Wir haben zunächst dafür gesorgt, dass du alle bevorzugten UI-Komponenten-Sprachen verwenden kannst, die du bereits kennst. React, Preact, Svelte, Vue, Solid, Lit und einige andere werden für die Erstellung neuer UI-Komponenten in einem Astro-Projekt unterstützt.

Wir wollten auch sicherstellen, dass Astro über eine großartige integrierte Komponentensprache verfügt. Zu diesem Zweck haben wir unsere eigene UI-Sprache `.astro` entwickelt. Sie ist stark von HTML beeinflusst: Jedes gültige HTML-Snippet ist bereits eine gültige Astro-Komponente! Aber sie kombiniert auch einige unserer Lieblingsfunktionen, die wir von anderen Komponentensprachen übernommen haben, wie JSX-Ausdrücke (React) und standardmäßiges CSS-Scoping (Svelte und Vue).

Astro wurde entwickelt, um weniger komplex zu sein als andere UI-Frameworks und Sprachen. Ein wichtiger Grund dafür ist, dass Astro für das Rendering auf dem Server und nicht im Browser entwickelt wurde. Das bedeutet, dass du dir keine Gedanken über Hooks (React), Stale Closures (auch React), Refs (Vue), Observables (Svelte), Atoms, Selektoren, Reactions oder Derivations machen musst. Es gibt keine Reaktivität auf dem Server, also schmilzt all diese Komplexität dahin.

Einer unserer Lieblingssprüche ist: **Opt-in to complexity.** Wir haben Astro so konzipiert, dass so viel "erforderliche Komplexität" wie möglich aus der Entwicklungserfahrung entfernt wird, vor allem, wenn du zum ersten Mal Astro verwendest. Du kannst eine "Hello World"-Beispiel-Website in Astro erstellen und dafür ausschließlich HTML und CSS verwenden. Wenn du dann etwas Leistungsfähigeres erstellen musst, kannst du nach und nach neue Funktionen und APIs nutzen.


## Funktionsreich, aber flexibel

**Astro ist ein All-in-One-Web-Framework, das alles enthält, was du zum Erstellen einer Website benötigst.** Astro umfasst eine Komponentensyntax, dateibasiertes Routing, Verarbeitung statischer Inhalte, einen Build-Prozess, Bündelung, Optimierungen, Datenabrufe und mehr. Du kannst großartige Websites erstellen, ohne jemals über die Kernfunktionen von Astro hinauszugehen.

Wenn du mehr Kontrolle benötigst, kannst du Astro mit über [100+ Integrationen](https://astro.build/integrations/) wie [React](https://www.npmjs.com/package/@astrojs/react), [Svelte](https://www.npmjs.com/package/@astrojs/svelte), [Vue](https://www.npmjs.com/package/@astrojs/vue), [Tailwind CSS](https://www.npmjs.com/package/@astrojs/tailwind), [MDX](https://www.npmjs.com/package/@astrojs/mdx), [Bildoptimierung](https://www.npmjs.com/package/@astrojs/image), und mehr erweitern. [Verbinde dein bevorzugtes CMS](https://astro.build/integrations) oder [veröffentliche deine Website](/de/guides/deploy/) bei deinem bevorzugten Hosting-Anbieter mit nur einem einzigen Befehl.

Astro ist UI-agnostisch, d.h. du kannst **dein eigenes UI-Framework mitbringen (BYOF)**. React, Preact, Solid, Svelte, Vue und Lit werden alle offiziell von Astro unterstützt. Du kannst sogar verschiedene Frameworks auf derselben Seite mischen und anpassen, was künftige Migrationen erleichtert und verhindert, dass dein Projekt an ein einziges Framework gebunden ist.
