FROM cbrherms/shinobi:latest
LABEL org.freenas.interactive="false"                                   \
      org.freenas.version="latest"                                           \
      org.freenas.upgradeable="false"                                    \
      org.freenas.expose-ports-at-host="true"                           \
      org.freenas.autostart="true"                                      \
      org.freenas.web-ui-protocol="http"                                \
      org.freenas.web-ui-port="8080"                                    \
      org.freenas.web-ui-path=""                                        \
      org.freenas.port-mappings="8080:8080/tcp"                         \
      org.freenas.volumes="[                                            \
          {                                                             \
              \"name\": \"/opt/shinobi/videos\",                                    \
              \"descr\": \"Video storage location\"                       \
          }                                                             \
      ]"                                                                \
      org.freenas.settings="[                                           \
          {                                                             \
              \"env\": \"MYSQL_HOST\",                                          \
              \"descr\": \"IP or name of MySQL server\",               \
              \"optional\": false                                        \
          },                                                            \
          {                                                             \
              \"env\": \"MYSQL_DATABASE\",                                        \
              \"descr\": \"Name of the MYSQL database\",                                   \
              \"optional\": true                                        \
          },                                                            \
          {                                                             \
              \"env\": \"MYSQL_ROOT_USER\",                                        \
              \"descr\": \"Root username\",                                    \
              \"optional\": true                                        \
         },                                                              \
          {                                                             \
              \"env\": \"MYSQL_ROOT_PASSWORD\",                                          \
              \"descr\": \"MySQL root password\",               \
              \"optional\": false                                        \
          },                                                            \
          {                                                             \
              \"env\": \"MYSQL_USER\",                                        \
              \"descr\": \"Database username\",                                   \
              \"optional\": true                                        \
          },                                                            \
          {                                                             \
              \"env\": \"MYSQL_PASSWORD\",                                        \
              \"descr\": \"Database user password\",                                    \
              \"optional\": true                                        \
         },                                                              \
          {                                                             \
              \"env\": \"TIMEZONE\",                                        \
              \"descr\": \"Timezone - eg Europe/London\",                                    \
              \"optional\": true                                        \
         }                                                              \
      ]"
