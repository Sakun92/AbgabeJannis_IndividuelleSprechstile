# AbgabeJannis_IndividuelleSprechstile

Im  Kurs: "Angewandte Aspekte der Sprechforschung: Individuelle Sprechstile", im SoSe 2021 geleitet von Prof. Dr. Felix Burkhardt, haben wir in diesem Semester die Stimme eines anderen Menschen analysiert. Dementsprechend war unsere erste Aufgabe uns eine/n Sprecher/in auszusuchen und von dieser Person eine gute Rede herauszusuchen. Die Rede sollte zwischen 3-7 Minuten sein und im besten Fall ohne größere Unterbrechungen und Zwischenrufe sein oder gar in einer sehr lauten Umgebung stattfinden. Ich habe mir dazu die erste große Rede im Bundestag von dem damals 26-Jährigen CDU-Politiker Philipp Amthor herausgesucht. Warum? Ich fande es sehr beeindruckend, wie rhetorisch stark der damals 26-Jährige die AFD bzw. deren Antrag damals 'auseinander genommen hat' (wie es im Videotitel hieß).
Zwar laufen meine politische Meinung und die von Philipp Amthor konträr, jedoch sind wir uns bestimmt alle einig, dass jeder Politiker der versucht eine rechte Partei (richtiger Weise) herabzusetzen, eine gute Wahl für eine Analyse ist.

Diese Rede mussten die Teilnehmenden dann von der jeweiligen Plattform als WAV-Datei herunterladen. Ich musste diese Rede ebenfalls ein wenig schneiden mittels Audacity. Eine weitere Voraussetzung war, dass diese Rede mit einer Samplerate von 16.000Hz, 16 Bit und mit einer Mono-Spur vorlag. Auch  dazu musste ich einige Arbeitsschritte, wie bspw. das Downsamplen, in Audacity vornehmen.
Anschließend wurde diese Audiodatei dann von Herrn Prof. Dr. Burkhardt mittels 'auvad', ein internes Package von Audeering, in ähnlich große Segmente unterteilt, welche sich besser zur Analyse eigneten.

Auch hier in diesem Kurs gab es die Idee die Segmente mit dem Speechalyzer von Prof. Dr. Burkhardt zu bearbeiten. Dies haben wir dann jedoch nicht für die Analyse benötigt und dementsprechend nicht weiter verfolgt. Der nächste Schritt war dann, dass wir uns die Segmente im Jupyter Notebook mit Python anguckten und die ersten Audioparameter herausarbeiteten.

Dazu erstellten wir [unser erstes Notebook](SeminarIndividuelleSprechstile_Nellesen.ipynb). Dieses Notebook haben wir uns zum Teil auch in Gruppenarbeit erarbeitet mit der Hilfe von dem Blog von Herrn Prof. Dr. Burkhardt. Dementsprechend habe ich dies nur oberflächlich kommentiert und sonst auch keine weitere eigene Leistung in diesem Notebook hinzugefügt. Dennoch wollte ich dieses Notebook der Vollständigkeit nach mit abgeben. In dem Notebook ging es hauptsächlich um die Grundzüge der Audioanalyse. Ein großer Teil hierbei war die Analyse und Berechnung der Formantwerte.

Etwas später starteten wir ein kleines Projekt in diesem Seminar. Wir starteten ein kleines Stimmenexperiment mit 'my-voice-analysis'. Dies war ein lustiges Spielzeug, jedoch hat es bei mir z.B. keinen Mehrwert geboten, da Herr Amthor bspw. von der Funktion als Frau erkannt wurde. Zwar gab es einige lustige Erkenntnisse und Dinge die gut funktioniert hatten, wie bspw. die Grundfrequenz oder das Herr Amthor leidenschaftlich gesprochen hat (wie es im Bundestag sein sollte), aber letztendlich war es nur ein kleiner Exkurs für uns und da ich auch keine Eigenleistung dort erbracht habe, habe ich diese Notebook selbstverständlich nicht mitabgegeben.

Meiner Ansicht nach hat das Seminar an diesem Punkt richtig an Fahrt aufgenommen und wurde deutlich interessanter und hat viel Spaß gemacht. Zu diesem Zeitpunkt haben wir nämlich mit den Mid-Level-Descriptors angefangen. Diese wurden von  Uwe Reichel programmiert und suchen auf Basis der Low-Level-Descriptors nach Silbenkernen, womit dann bspw. die Silbenrate analysiert werden kann.
Dieses [Mid-Level-Descriptors-Notebook](mid_level_descriptors.ipynb) habe ich hier als Eigenleistung genauestens kommentiert, weshalb ich im Readme auch nicht näher drauf eingehen möchte.
Dennoch sei kurz erwähnt, dass es sehr beeindruckend ist, wie viele Parameter letztendlich automatisiert erkannt und berechnet werden können. Auch der Linguistik-Exkurs mit der Automatic Speech Recognition und der Textanalyse habe ich an diesem Punkt als sehr spannend empfunden.

Mit dem Add-Annotations-Notebook, welches ich der Abgabe nicht hinzugefügt habe, da es keinerlei Eigenleistung enthält, haben wir den Endspurt des Semesters eingeläutet. Dort haben wir unserer Rede bestimmte Klassen zugeordnet. Philipp Amthor beispielsweise ist männlich, ein Mensch, heutzutage 28 Jahre alt, spricht deutsch und debattiert in seiner Rede. Dies haben wir aus dem Zweck gemacht, dass wir die Rede mit denen der Kommilitonen vergleichen können.

Das haben wir dann auch getan mit unserem letzten Notebook. Das [Large-Dataframe-Notebook](large_dataframe.ipynb) haben wir als Vergleichsnotebook der unterschiedlichen Reden genutzt. Dieses Notebook wurde als Eigenleistung genauestens kommentiert. Darüberhinaus wurden am Ende des Notebooks einige grafische Repräsentationen als Eigenleistung hinzugefügt, damit das Verständnis der Funktionsweise untermauert werden kann.

Schlussendlich lässt sich sagen, dass mir das Seminar bzw. die Seminare viel Spaß gemacht haben, mir jedoch auch einiges abverlangt haben. Ich habe unglaublich viel neues gelernt und hoffe, dass ich diese Informationen auch über die nächsten Monate und Jahre weiterhin abrufen kann.
Es gab spannende Ergebnisse und schlussendlich empfand ich es als sehr aufregend, den roten Faden wieder zu finden, welcher sich letztendlich durch das ganze Seminar gezogen hat.
Dieser rote Faden war nämlich für mich im 'Eifer des Gefechts' manchmal nicht mehr ganz erkennbar. Betrachtet man am Ende jedoch das große Ganze, bemerkt man, wie sich der rote Faden langsam aber sich durch das ganze Seminar gezogen hat.