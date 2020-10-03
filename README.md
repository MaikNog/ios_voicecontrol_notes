# "Can one automate taking a timestamp on an iPhone hands-free?"

Sparked by a twitter question (in German) from Heiko Stapf (https://twitter.com/Criamon).

Tweet: https://twitter.com/Criamon/status/1312363408868679683?s=20


I probably worked 30 minutes on it, researching and trying it out on my iPhone with iOS 14.x

## Prerequisites:
- Voicecontrol / Sprachsteuerung = iOS 13 and higher
- Shortcut / Kurzbefehle = iOS 12 and higher


## English - Short guide
1. Create a shortcut in the Shortcut app.
2. Then activate VoiceControl (VC).
3. Link a new VoiceControl with the shortcut.
4. (*) Additionally link VoiceControl with the action: < item name >. _(This is required to execute the "confirm" command.)_

Tried it at home with a noisy TV in the background.

TODO: Would like to get rid of the (*) for the "confirm" command.


## German - Kurzanleitung
1. Einen Kurzbefehl (KB) erstellen.
2. Dann Sprachsteuerung (SP) aktivieren.
3. In der Sprachsteuerung den Kurzbefehl verknüpfen.
4. (*) Zusätzlich in der Sprachsteuerung mit der Aktion: <item-Name> verknüpfen. _(Dieses wird für das "Ausführen" Kommando gebraucht.)_

Habe es zuhause mit TV Geräuschen im Hintergrund ausprobiert.

TODO: Würde gerne das (*) wegbekommen für den „Bestätigen“ Befehl.

# What are we doing?
We create a shortcut (name it with one syllable, e.g. "note"), which takes actions: 
- get current date
- format the date
- put it into the clipboard)
- paste the clipboard into a note in the Notes app.

# How do I use this?
- Activate VoiceControl. 
- Say the name of the shortcut (e.g. "note").
- Say "Confirm".
 
_Result_: A note with the date and timestamp is created.


#### Reading inspiration:
https://www.macrumors.com/guide/voice-control/
https://www.reddit.com/r/shortcuts/comments/dotbtq/a_workaround_that_can_run_gestures_and_run/
https://uk.pcmag.com/apple-ipod-touch-2015/118227/how-to-automate-your-life-with-apples-ios-shortcuts-app
https://support.apple.com/guide/shortcuts/welcome/ios
https://support.apple.com/de-de/guide/shortcuts/welcome/ios (German)
