FROM dlandon/zoneminder:latest
LABEL org.freenas.interactive="false"                                   \
      org.freenas.version="latest"                                           \
      org.freenas.upgradeable="true"                                    \
      org.freenas.expose-ports-at-host="true"                           \
      org.freenas.autostart="true"                                      \
	  org.freenas.privileged="true"                                      \
      org.freenas.web-ui-protocol="http"                                \
      org.freenas.web-ui-port="8080"                                    \
      org.freenas.web-ui-path=""                                        \
      org.freenas.port-mappings="8080:80/tcp"                         \
      org.freenas.volumes="[                                            \
          {                                                             \
              \"name\": \"/config\",                                    \
              \"descr\": \"Zoneminder config\"                       \
          },                                                             \
          {                                                             \
              \"name\": \"/var/cache/zoneminder\",                                    \
              \"descr\": \"Zoneminder data\"                       \
          }                                                             \
      ]"                                                                \
      org.freenas.settings="[                                           \
          {                                                             \
              \"env\": \"PUID\",                                          \
              \"descr\": \"User ID\",               \
              \"optional\": true                                        \
          },                                                            \
          {                                                             \
              \"env\": \"PGID\",                                        \
              \"descr\": \"Group ID\",                                   \
              \"optional\": true                                        \
          },                                                            \
          {                                                             \
              \"env\": \"TZ\",                                        \
              \"descr\": \"Timezone - eg Europe/London\",                                    \
              \"optional\": true                                        \
         }                                                               \
      ]"
