# Lab8-Starter
* Jude Gamba
* Ali AlSadah
* https://aalsadah.github.io/Lab8_Starter/
* ### How are graceful degradation and service workers related?
  Graceful degradation is the process of starting with all access to technology and then addressing lower levels. Service workers allow us to accomplish graceful degradation by creating a fallback for website functionality that require an internet connection. For example, in this lab, the recipe information for each card was initially fetched from an external URL, but with service workers, the information that was fetched is saved to cache so it can be retrieved without having to fetch the information again through the network.

![picture of web app](pwa.png)