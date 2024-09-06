---
layout: page
title: LPBF Simulation
description: Makro-Skala
img: assets/img/12.jpg
importance: 1
category: PhD
related_publications: true
---

Dieses Projekt ist Teil meiner Dissertation und entstand während meiner Promotion am Lehrstuhl für Computational Physics in Engineering. Im Rahmen des Projekts wird zunächst ein Temperaturfeld in Abhängigkeit von den Prozessparametern berechnet. Darauf aufbauend erfolgt die thermo-mechanische Berechnung, bei der ein J2-Plastizitätsmodell zur Beschreibung der plastischen Verformung des Materials berücksichtigt wird.

Die Implementierung des gesamten Simulationsmodells wurde in der Programmiersprache [Julia](https://julialang.org/) realisiert. Dabei wurde die Finite-Differenzen-Methode verwendet, um die Differentialgleichungen numerisch zu lösen. Durch die GPU-Unterstützung konnte die Berechnungszeit erheblich reduziert und eine effiziente Verarbeitung großer Datenmengen ermöglicht werden, was insbesondere bei der Simulation komplexer Geometrien und Prozessbedingungen von Vorteil ist.

<div class="row mt-3">
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Impeller_T.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include video.liquid path="assets/video/Impeller_pe_Mag.mp4" class="img-fluid rounded z-depth-1" controls=true autoplay=true loop=true %}
    </div>
</div>
<div class="caption">
    Temperaturfeld (rechts) und Betrag der plastischen Dehnungen (links) für einen im LPBF-Prozess gefertigten Impeller.
</div>


