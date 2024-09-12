# Öffnen Sie die WebUI (ehemals Ollama WebUI)

! [GitHub-Sterne] (https://img.shields.io/github/stars/open-webui/open-webui?style=social)

! [GitHub-Forks] (https://img.shields.io/github/forks/open-webui/open-webui?style=social)

! [GitHub-Beobachter] (https://img.shields.io/github/watchers/open-webui/open-webui?style=social)

! [Größe des GitHub-Repositorys] (https://img.shields.io/github/repo-size/open-webui/open-webui)

! [Anzahl der GitHub-Sprachen] (https://img.shields.io/github/languages/count/open-webui/open-webui)

! [GitHub Top-Sprache] (https://img.shields.io/github/languages/top/open-webui/open-webui)

! [GitHub letzter Commit] (https://img.shields.io/github/last-commit/open-webui/open-webui?color=red)

! [Treffer] (https://hits.seeyoufarm.com/api/count/incr/badge.svg?url=https%3A%2F%2Fgithub.com%2Follama-webui%2Follama-wbui&count_bg=%2379C83D&title_bg=%23555555&icon=&icon_color=%23E7E7E7&title=hits&edge_flat=false)

[! [Zwietracht] (https://img.shields.io/badge/Discord-Open_WebUI-blue?logo=discord&logoColor=white)] (https://discord.gg/5rJgQTnV4s)

[! [](https://img.shields.io/static/v1?label=Sponsor&message=%E2%9D%A4&logo=GitHub&color=%23fe8e86)](https://github.com/sponsors/tjbck)

Open WebUI ist eine [erweiterbare](https://github.com/open-webui/pipelines), funktionsreiche und benutzerfreundliche, selbst gehostete WebUI, die für den vollständigen Offline-Betrieb konzipiert wurde. Es unterstützt verschiedene LLM-Runner, einschließlich Ollama und OpenAI-kompatible APIs. Weitere Informationen finden Sie in unserer [Open WebUI Documentation](https://docs.openwebui.com/).

! [WebUI-Demo öffnen] (./demo.gif)

## Hauptmerkmale von Open WebUI

- **Mühelose Einrichtung**: Nahtlose Installation mit Docker oder Kubernetes (kubectl, kustomize oder helm) für ein problemloses Erlebnis mit Unterstützung für sowohl ':ollama' als auch ':cuda' getaggte Images.

- **Ollama/OpenAI-API-Integration**: Integrieren Sie mühelos OpenAI-kompatible APIs für vielseitige Konversationen neben Ollama-Modellen. Passen Sie die OpenAI API-URL so an, dass sie mit **LMStudio, GroqCloud, Mistral, OpenRouter und mehr** verknüpft wird.

- **Pipelines, Open WebUI Plugin Support**: Nahtlose Integration von benutzerdefinierter Logik und Python-Bibliotheken in Open WebUI mit [Pipelines Plugin Framework](https://github.com/open-webui/pipelines). Starten Sie Ihre Pipelines-Instanz, legen Sie die OpenAI-URL auf die Pipelines-URL fest und erkunden Sie die endlosen Möglichkeiten. [Beispiele] (https://github.com/open-webui/pipelines/tree/main/examples) umfassen **Function Calling**, User **Rate Limiting** zur Steuerung des Zugriffs, **Nutzungsüberwachung** mit Tools wie Langfuse, **Live-Übersetzung mit LibreTranslate** für mehrsprachige Unterstützung, **Toxic Message Filtering** und vieles mehr.

- **Responsives Design**: Genießen Sie ein nahtloses Erlebnis auf Desktop-PCs, Laptops und Mobilgeräten.

- **Progressive Web App (PWA) für Mobilgeräte**: Genießen Sie mit unserer PWA ein natives App-ähnliches Erlebnis auf Ihrem Mobilgerät, das Offline-Zugriff auf localhost und eine nahtlose Benutzeroberfläche bietet.

- **Vollständige Markdown- und LaTeX-Unterstützung**: Verbessern Sie Ihre LLM-Erfahrung mit umfassenden Markdown- und LaTeX-Funktionen für eine angereicherte Interaktion.

- **Freisprech-/Videoanrufe**: Erleben Sie nahtlose Kommunikation mit integrierten Freisprechfunktionen für Sprach- und Videoanrufe, die eine dynamischere und interaktivere Chat-Umgebung ermöglichen.

- **Model Builder**: Erstellen Sie ganz einfach Ollama-Modelle über die Web-Benutzeroberfläche. Erstellen und fügen Sie benutzerdefinierte Charaktere/Agenten hinzu, passen Sie Chat-Elemente an und importieren Sie Modelle mühelos durch die Integration von [Open WebUI Community](https://openwebui.com/).

- **Natives Python Function Calling Tool**: Verbessern Sie Ihre LLMs mit integrierter Code-Editor-Unterstützung im Arbeitsbereich Tools. Bring Your Own Function (BYOF), indem Sie einfach Ihre reinen Python-Funktionen hinzufügen und so eine nahtlose Integration mit LLMs ermöglichen.

- **Lokale RAG-Integration**: Tauchen Sie ein in die Zukunft der Chat-Interaktionen mit der bahnbrechenden Unterstützung von Retrieval Augmented Generation (RAG). Diese Funktion integriert Dokumenteninteraktionen nahtlos in Ihr Chat-Erlebnis. Sie können Dokumente direkt in den Chat laden oder Dateien zu Ihrer Dokumentenbibliothek hinzufügen, indem Sie mühelos mit dem Befehl '#' vor einer Abfrage darauf zugreifen.

- **Websuche für RAG**: Führen Sie Websuchen mit Anbietern wie 'SearXNG', 'Google PSE', 'Brave Search', 'serpstack', 'serper', 'Serply', 'DuckDuckGo', 'TavilySearch' und 'SearchApi' durch und fügen Sie die Ergebnisse direkt in Ihr Chat-Erlebnis ein.

- **Web-Browsing-Funktion**: Integrieren Sie Websites nahtlos in Ihr Chat-Erlebnis, indem Sie den Befehl "#" gefolgt von einer URL verwenden. Mit dieser Funktion können Sie Webinhalte direkt in Ihre Konversationen einbinden und so den Reichtum und die Tiefe Ihrer Interaktionen verbessern.

- **Integration der Bildgenerierung**: Integrieren Sie nahtlos Bildgenerierungsfunktionen mit Optionen wie AUTOMATIC1111 API oder ComfyUI

(lokal) und OpenAIs DALL-E (extern) und bereichern Sie Ihr Chat-Erlebnis mit dynamischen visuellen Inhalten.

- **Gespräche mit vielen Models**: Interagieren Sie mühelos mit verschiedenen Models gleichzeitig und nutzen Sie ihre einzigartigen Stärken für optimale Antworten. Verbessern Sie Ihre Erfahrung, indem Sie eine Vielzahl von Modellen parallel nutzen.

- **Rollenbasierte Zugriffskontrolle (RBAC)**: Gewährleisten Sie einen sicheren Zugriff mit eingeschränkten Berechtigungen; Nur autorisierte Personen können auf Ihr Ollama zugreifen, und exklusive Rechte zum Erstellen/Abrufen von Modellen sind Administratoren vorbehalten.

- **Mehrsprachiger Support**: Erleben Sie Open WebUI in Ihrer bevorzugten Sprache mit unserem Internationalisierungs-Support (i18n). Erweitern Sie mit uns unsere unterstützten Sprachen! Wir sind aktiv auf der Suche nach Mitwirkenden!

- **Kontinuierliche Updates**: Wir sind bestrebt, Open WebUI mit regelmäßigen Updates, Fehlerbehebungen und neuen Funktionen zu verbessern.

Möchten Sie mehr über die Funktionen von Open WebUI erfahren? Schauen Sie sich unsere [Open WebUI Dokumentation](https://docs.openwebui.com/features) an, um einen umfassenden Überblick zu erhalten!

## Schauen Sie sich auch die Open WebUI Community an!

Vergessen Sie nicht, unser Schwesterprojekt [Open WebUI Community](https://openwebui.com/) zu erkunden, in dem Sie benutzerdefinierte Modelfiles entdecken, herunterladen und erkunden können. Die Open WebUI Community bietet eine Vielzahl spannender Möglichkeiten, Ihre Chat-Interaktionen mit Open WebUI zu verbessern!

## Wie installiere ich

> [! ANMERKUNG]

> Bitte beachten Sie, dass für bestimmte Docker-Umgebungen möglicherweise zusätzliche Konfigurationen erforderlich sind. Wenn Sie auf Verbindungsprobleme stoßen, steht Ihnen unser ausführlicher Leitfaden zur [Open WebUI Documentation](https://docs.openwebui.com/) zur Verfügung.

### Schnellstart mit Docker

> [! WARNUNG]

> Wenn Sie Docker verwenden, um Open WebUI zu installieren, stellen Sie sicher, dass Sie "-v open-webui:/app/backend/data" in Ihren Docker-Befehl aufnehmen. Dieser Schritt ist von entscheidender Bedeutung, da er sicherstellt, dass Ihre Datenbank ordnungsgemäß bereitgestellt wird, und Datenverluste verhindert werden.

> [! TIPP]

> Wenn Sie Open WebUI mit Ollama oder CUDA-Beschleunigung verwenden möchten, empfehlen wir Ihnen, unsere offiziellen Bilder zu verwenden, die entweder mit ":cuda" oder ":ollama" gekennzeichnet sind. Um CUDA zu aktivieren, müssen Sie das [Nvidia CUDA Container Toolkit](https://docs.nvidia.com/dgx/nvidia-container-runtime-upgrade/) auf Ihrem Linux/WSL-System installieren.

### Installation mit Standardkonfiguration

- **Wenn Ollama auf Ihrem Computer ist**, verwenden Sie diesen Befehl:

'''Schlag

docker run -d -p 3000:8080 --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart immer ghcr.io/open-webui/open-webui:main

```

- **Wenn Ollama auf einem anderen Server ist**, verwenden Sie diesen Befehl:

Um eine Verbindung zu Ollama auf einem anderen Server herzustellen, ändern Sie die "OLLAMA_BASE_URL" in die URL des Servers:

'''Schlag

docker run -d -p 3000:8080 -e OLLAMA_BASE_URL=https://example.com -v open-webui:/app/backend/data --name open-webui --restart immer ghcr.io/open-webui/open-webui:main

```

- **Verwenden Sie den folgenden Befehl, um Open WebUI mit Nvidia-GPU-Unterstützung auszuführen**:

'''Schlag

docker run -d -p 3000:8080 --gpus all --add-host=host.docker.internal:host-gateway -v open-webui:/app/backend/data --name open-webui --restart immer ghcr.io/open-webui/open-webui:cuda

```

### Installation nur für die Nutzung der OpenAI API

- **Wenn Sie nur die OpenAI-API verwenden**, verwenden Sie diesen Befehl:

'''Schlag

docker run -d -p 3000:8080 -e OPENAI_API_KEY=your_secret_key -v open-webui:/app/backend/data --name open-webui --restart immer ghcr.io/open-webui/open-webui:main

```

### Installation von Open WebUI mit gebündelter Ollama-Unterstützung

Diese Installationsmethode verwendet ein einzelnes Container-Image, das Open WebUI mit Ollama bündelt und so eine optimierte Einrichtung mit einem einzigen Befehl ermöglicht. Wählen Sie den entsprechenden Befehl basierend auf Ihrem Hardware-Setup aus:

- **Mit GPU-Unterstützung**:

Nutzen Sie GPU-Ressourcen, indem Sie den folgenden Befehl ausführen:

'''Schlag

docker run -d -p 3000:8080 --gpus=all -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart immer ghcr.io/open-webui/open-webui:ollama

```

- **Nur für CPU**:

Wenn Sie keine GPU verwenden, verwenden Sie stattdessen diesen Befehl:

'''Schlag

docker run -d -p 3000:8080 -v ollama:/root/.ollama -v open-webui:/app/backend/data --name open-webui --restart immer ghcr.io/open-webui/open-webui:ollama

```

Beide Befehle ermöglichen eine integrierte, problemlose Installation von Open WebUI und Ollama und stellen sicher, dass Sie alles schnell zum Laufen bringen können.

Nach der Installation können Sie unter [http://localhost:3000](http://localhost:3000) auf Open WebUI zugreifen. Genießen!

### Andere Installationsmethoden

Wir bieten verschiedene Installationsalternativen an, darunter native Installationsmethoden, die nicht von Docker stammen, Docker Compose, Kustomize und Helm. Besuchen Sie unsere [Open WebUI-Dokumentation](https://docs.openwebui.com/getting-started/) oder treten Sie unserer [Discord-Community](https://discord.gg/5rJgQTnV4s) bei, um eine umfassende Anleitung zu erhalten.

### Fehlerbehebung

Stoßen Sie auf Verbindungsprobleme? Unsere [Open WebUI Documentation](https://docs.openwebui.com/troubleshooting/) ist genau das Richtige für Sie. Für weitere Unterstützung und um unserer lebendigen Community beizutreten, besuchen Sie den [Open WebUI Discord](https://discord.gg/5rJgQTnV4s).

#### WebUI öffnen: Fehler bei der Serververbindung

Wenn Verbindungsprobleme auftreten, liegt dies häufig daran, dass der WebUI-Docker-Container den Ollama-Server unter 127.0.0.1:11434 (host.docker.internal:11434) innerhalb des Containers nicht erreichen kann. Verwenden Sie das Flag '--network=host' in Ihrem Docker-Befehl, um dies zu beheben. Beachten Sie, dass sich der Port von 3000 auf 8080 ändert, was zu dem Link führt: 'http://localhost:8080'.

**Beispiel für einen Docker-Befehl**:

'''Schlag

docker run -d --network=host -v open-webui:/app/backend/data -e OLLAMA_BASE_URL=http://127.0.0.1:11434 --name open-webui --restart immer ghcr.io/open-webui/open-webui:main

```

### Halten Sie Ihre Docker-Installation auf dem neuesten Stand

Falls Sie Ihre lokale Docker-Installation auf die neueste Version aktualisieren möchten, können Sie dies mit [Watchtower](https://containrrr.dev/watchtower/) tun:

'''Schlag

docker run --rm --volume /var/run/docker.sock:/var/run/docker.sock containrrr/watchtower --run-once open-webui

```

Ersetzen Sie im letzten Teil des Befehls "open-webui" durch den Namen Ihres Containers, falls dieser sich unterscheidet.

Schauen Sie sich unseren Migrationsleitfaden an, der in unserer [Open WebUI Documentation](https://docs.openwebui.com/migration/) verfügbar ist.

### Verwenden des dev-Zweigs

> [! WARNUNG]

> Der Zweig ':d ev' enthält die neuesten instabilen Funktionen und Änderungen. Verwenden Sie es auf eigenes Risiko, da es Fehler oder unvollständige Funktionen enthalten kann.

Wenn Sie die neuesten hochmodernen Funktionen ausprobieren möchten und mit gelegentlicher Instabilität einverstanden sind, können Sie das ":d ev"-Tag wie folgt verwenden:

'''Schlag

docker run -d -p 3000:8080 -v open-webui:/app/backend/data --name open-webui --add-host=host.docker.internal:host-gateway --restart immer ghcr.io/open-webui/open-webui:dev

```

## Was kommt als nächstes?

Entdecken Sie kommende Funktionen auf unserer Roadmap in der [Open WebUI Documentation](https://docs.openwebui.com/roadmap/).

## Unterstützer

Ein großes Dankeschön an unsere großartigen Unterstützer, die helfen, dieses Projekt möglich zu machen!

### Platin-Sponsoren

- Wir sind auf der Suche nach Sponsoren!

### Danksagung

Besonderer Dank geht an [Prof. Lawrence Kim](https://www.lhkim.com/) und [Prof. Nick Vincent](https://www.nickmvincent.com/) für ihre unschätzbare Unterstützung und Anleitung bei der Gestaltung dieses Projekts zu einem Forschungsvorhaben. Dankbar für Ihre Mentorenschaft während der gesamten Reise!

## Lizenz

Dieses Projekt ist unter der [MIT License](LICENSE) lizenziert - siehe die Datei [LICENSE](LICENSE) für Details.

## Unterstützung

Wenn Sie Fragen oder Anregungen haben oder Hilfe benötigen, öffnen Sie bitte ein Problem oder treten Sie unserem bei

[Öffnen Sie die WebUI-Discord-Community] (https://discord.gg/5rJgQTnV4s) um sich mit uns zu verbinden!

## Geschichte der Stars

<a href="https://star-history.com/#open-webui/open-webui&Date">

<Bild>

<source media="(bevorzugtes-farbschema: dunkel)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date&theme=dark" />

<source media="(bevorzugtes-farbschema: hell)" srcset="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />

<img alt="Sternen-Geschichtskarte" src="https://api.star-history.com/svg?repos=open-webui/open-webui&type=Date" />

</Bild>

</a>



Erstellt von [Timothy J. Baek](https://github.com/tjbck) - Lassen Sie uns Open WebUI gemeinsam noch erstaunlicher machen!

------
