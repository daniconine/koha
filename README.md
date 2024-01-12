# koha
Repositorio de instalacion Koha

video:
https://www.youtube.com/watch?v=LCcwRy48v8g&ab_channel=Ayudant%C3%ADasCatalogaci%C3%B3n

🔗 ENLACES:
- Guía para instalar Koha 22.11 en Ubuntu 22.04 https://mega.nz/file/5yRTRaBI#3LrvFyu...
- Manual Koha 22.11 (Documentación oficial) https://koha-community.org/manual/22....
- Ubuntu en Windows con Virtualbox   

 • ✅ Instalar Ubuntu 22.04  en Virtualbo...  
- Ubuntu en Mac con Virtualbox   

 • INSTALAR UBUNTU EN VIRTUALBOX MAC  

https://koha-community.org/manual/22.11/es/html/installation.html

configuracion del servicio koha
<config>
 <db_scheme>mysql</db_scheme>
 <database>koha_biblio_gerens</database>
 <hostname>localhost</hostname>
 <port>3306</port>
 <user>koha_biblio_gerens</user>
 <pass>XWu0r$B%aH|2N*bE</pass>
 <tls>__DB_USE_TLS__</tls>
 <ca>__DB_TLS_CA_CERTIFICATE__</ca>
 <cert>__DB_TLS_CLIENT_CERTIFICATE__</cert>
 <key>__DB_TLS_CLIENT_KEY__</key>
 <biblioserver>biblios</biblioserver>
 <biblioservershadow>1</biblioservershadow>
 <authorityserver>authorities</authorityserver>
 <authorityservershadow>1</authorityservershadow>
 <pluginsdir>/var/lib/koha/biblio_gerens/plugins</pluginsdir> <!-- This entry can be repeated to use multiple directories>
 <enable_plugins>0</enable_plugins>
 <upload_path>/var/lib/koha/biblio_gerens/uploads</upload_path>
 <tmp_path>/var/lib/koha/biblio_gerens/tmp</tmp_path>
 <intranetdir>/usr/share/koha/intranet/cgi-bin</intranetdir>
 <opacdir>/usr/share/koha/opac/cgi-bin/opac</opacdir>
 <opachtdocs>/usr/share/koha/opac/htdocs/opac-tmpl</opachtdocs>
 <intrahtdocs>/usr/share/koha/intranet/htdocs/intranet-tmpl</intrahtdocs>
 <includes>/usr/share/koha/intranet/htdocs/intranet-tmpl/prog/en/includes/</includes>
 <logdir>/var/log/koha/biblio_gerens</logdir>
 <docdir>/usr/share/doc/koha-common</docdir>
 <backupdir>/var/spool/koha/biblio_gerens</backupdir>


 user: ccastillo@gerens.pe
 pass: cLAUDIA-2023
