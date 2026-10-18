---
layout: page
title: Übungsbuch Analysis I
permalink: /study-books/analysis-i/
description: Übungsaufgaben mit Lösungshinweisen, Musterlösungen und Übungsklausuren zur Analysis I
nav: false
---

<img src="{{ '/assets/img/publication_preview/analysis1.jpg' | relative_url }}" alt="Cover des Übungsbuchs Analysis I" style="float: right; width: 220px; max-width: 40%; margin: 0 0 1rem 1.5rem;" class="rounded z-depth-1">

Das [Übungsbuch Analysis I](https://link.springer.com/book/10.1007/978-3-662-64569-7) enthält fast 500 Teilaufgaben, die Studierende beim Bearbeiten von Übungsblättern, beim Nacharbeiten der Vorlesung und bei der Prüfungsvorbereitung unterstützen. Das Buch besteht aus vier Teilen: Übungsaufgaben, Lösungshinweise, Musterlösungen und Übungsklausuren.

## So funktioniert das Buch

Angenommen, in Ihrer Analysis-I-Vorlesung geht es gerade um die Konvergenz von Reihen, oder Sie müssen ein Übungsblatt zu diesem Thema abgeben. Um das Prüfen auf Konvergenz zu üben, nehmen Sie sich Aufgabe 57 (a) vor:

> **Aufgabe 57.** Untersuchen Sie die Reihe $$\sum_{n=0}^{\infty} \left(\frac{1}{7}\right)^n$$ auf Konvergenz.

Sie schlagen die Konvergenzkriterien aus der Vorlesung nach, wissen aber nicht recht, welches hier passt. Also werfen Sie einen Blick in den Lösungshinweis:

> **Lösungshinweis zu Aufgabe 57.** Die Reihe konvergiert nach dem [Wurzelkriterium](https://de.wikipedia.org/wiki/Wurzelkriterium) oder dem [Quotientenkriterium](https://de.wikipedia.org/wiki/Quotientenkriterium). Setzen Sie dazu $$x_n = (1/7)^n$$ für $$n \in \mathbb{N}_0$$ und überlegen Sie sich, dass $$\sqrt[n]{\lvert x_n \rvert} = 1/7$$ und $$\lvert x_{n+1} / x_n \rvert = 1/7$$ gilt.

Mit diesem Anstoß können Sie die Aufgabe selbstständig lösen. Wenn Sie sich bei Ihrem Ergebnis noch unsicher sind, vergleichen Sie es mit der Musterlösung im Buch:

> **Lösung zu Aufgabe 57.** Die Reihe konvergiert nach dem Wurzel- oder dem Quotientenkriterium. Wir setzen dazu $$x_n = (1/7)^n$$ für $$n \in \mathbb{N}_0$$. Offensichtlich gilt $$\sqrt[n]{\lvert x_n \rvert} = 1/7$$, womit wir
>
> $$\limsup_{n \to \infty} \sqrt[n]{\lvert x_n \rvert} = \limsup_{n \to \infty} \frac{1}{7} = \frac{1}{7}$$
>
> erhalten. Da dieser Limes superior kleiner als 1 ist, konvergiert die Reihe nach dem Wurzelkriterium. Alternativ folgt wegen $$\lvert x_{n+1} / x_n \rvert = 1/7$$ direkt
>
> $$\limsup_{n \to \infty} \left\lvert \frac{x_{n+1}}{x_n} \right\rvert = \frac{1}{7},$$
>
> sodass die Reihe auch nach dem Quotientenkriterium konvergiert.

So sehen Sie auf einen Blick, ob Ihre Lösung stimmt oder an welcher Stelle Sie noch nachbessern sollten.

## Übungsklausuren

An vielen Universitäten gibt es Altklausuren, aber selten die passenden Lösungen dazu. Deshalb enthält das Buch zusätzlich fünf Übungsklausuren mit vollständigen Lösungen. Sie unterscheiden sich in Themen und Umfang, sodass Sie die Klausur wählen können, die am besten zu Ihrer Vorbereitung passt. Eine davon hat zum Beispiel eine Bearbeitungszeit von 120 Minuten, erlaubt keine Hilfsmittel wie programmierbare Taschenrechner, und es sind maximal 55 Punkte erreichbar. Eine typische Klausuraufgabe sieht so aus:

> **Aufgabe 1 (8 Punkte).** Sei $$x \in \mathbb{R} \setminus \{1\}$$ beliebig. Beweisen Sie mittels vollständiger Induktion für alle $$n \in \mathbb{N}$$ die Identität
>
> $$\sum_{\nu = 0}^{n} \nu x^{\nu - 1} = \frac{1 - x^{n+1}}{(1-x)^2} - \frac{(n+1)x^n}{1-x}.$$

Nach der Bearbeitung können Sie Ihre Antworten mit den Musterlösungen vergleichen. Diese zeigen auch, wie die Punkte auf die einzelnen Lösungsschritte verteilt werden. Selbst wenn Sie eine Aufgabe nur teilweise lösen, bekommen Sie so ein realistisches Gefühl dafür, wie viele Punkte Sie in einer echten Klausur erreicht hätten.

[Zurück zu allen Übungsbüchern]({{ '/projects/' | relative_url }})
