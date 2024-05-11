# huegrok

Like ngrok but okhuennyy

# Setup

1. Get a server in any cloud
2. Set HUEGROK_HOST environment variable
3. Setup server: `ansible-playbook -i $HUEGROK_HOST, -e "{target: $HUEGROK_HOST}" server-playbook.yaml`
4. Run `huegrok LOCAL_PORT [DEST_SUBDOMAIN]`

## DEST_SUBDOMAIN

  * http://c8080.$HUEGROK_HOST
  * http://c8081.$HUEGROK_HOST
  * http://c8082.$HUEGROK_HOST
  * http://c8083.$HUEGROK_HOST
  * http://c8084.$HUEGROK_HOST
  * http://c8085.$HUEGROK_HOST

Maybe someday it will be not only HTTP
