# cpinstall

Cloud Pak Install - lon06dev

ROKS - 4.7

cp4i - cloudpak namespace

entitlement secret created

add ibm catalog

install plattform navigator - all namespaces / automatic update (use file bronze gid because of foundation cartridge)

add mq operator - all namespaces / auto

create mq projecy and entitlement secret

add mq tls secrets for single and ha

create config map for ini and mqsc

create qmsingle (QMSINGLE)

LEE channel with TLS on as optional and ANY_TLS12

route for LEE channel

qmsingle-ibm-mq-qm-mq.lon06dev-5ea9e8378e96c3c98ca588682ecb5d03-0000.eu-gb.containers.appdomain.cloud

test from rfhutil using LEE channel - OK


add app connect operator - all namespaces / auto (1.5)

create ace project

create entitlement secret

deploy ace dashboard (v12)
ping api v12 - ok
test parse - HUGE memory - add 1 to front of everything
test queue - 

**service and 1414 with SSL optional on SYSTEM.DEF.SVRCONN - for MQEndpoint policy **


**hl7qmgr**
add ini and mqsc
add tls
add supplmental group

SYSTEM.DEF.SVRCONN  = mqm mcauser and tls optional

**hl7-ingest**

**remember to compile bar**

**add nodeport on ace deploy**

**add remote qmgr server conf on ace deploy** 31111

route name = hl7-ingest-hl7 - pointing to hl7 port.

address on route: hl7-ingest-hl7-ace.lon06dev-5ea9e8378e96c3c98ca588682ecb5d03-0000.eu-gb.containers.appdomain.cloud

**increase resources on ace deploy**

address for hl7 tester:

hl7-ingest-hl7-ace.lon06dev-5ea9e8378e96c3c98ca588682ecb5d03-0000.eu-gb.containers.appdomain.cloud:31111
















