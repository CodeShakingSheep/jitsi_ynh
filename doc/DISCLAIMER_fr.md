## Points importants � pr�parer avant l'installation

1. **Jitsi** a besoin d'un **domaine racine** d�di�, par exemple : jitsi.domain.tld
2. **Jitsi** n�cessite des domaines suppl�mentaires au niveau du DNS et de votre YunoHost
  * auth.jitsi.domain.tld
  * conference.jitsi.domain.tld
  * jitsi-videobridge.jitsi.domain.tld
  * focus.jitsi.domain.tld
3. **Jitsi** demande que les ports TCP/4443 et UDP/10000 soient rout�s vers votre YunoHost (De la m�me mani�re que le sont les ports 80 (HTTP), 443 (HTTPS), etc... https://yunohost.org/#/isp_box_config)
