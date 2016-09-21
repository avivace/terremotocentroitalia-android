# terremotocentroitalia-android
Una semplice applicazione Android per fornire un accesso rapido alla versione Mobile di [terremotocentroitalia.info](https://terremotocentroitalia.info).

### [Google Play Store]()


In breve, l'app è una webview che punta alla home page del sito, con qualche accorgimento:
- Pull down to refresh (e indicatore);
- Ovverride del comportamento del tasto back. Porta la webview ad <code>history-1</code> invece di chiudere l'app;
- I link <code>_blank</code> vengono aperti in una nuova attività Android.

Alcune note agli sviluppatori Android:
- Se avete una build pronta al rilascio, contattatemi privatamente per la firma del pacchetto (Keystore) e verificate <code>package name</code>, <code>version_name</code> e <code>version_code</code> su tutti i file e Gradle;
- La repo contiene solo i file *utili* all'app;
- Attualmente compilata con SDK <code> API level 14 - Android 4.0 (IceCreamSandwich)</code>. Virtualmente si dovrebbe poter tornare ancora più indietro utilizzando il componente legacy webview.


![](http://i.imgur.com/4mDoxqn.png)
