"[2021-07-14T12:21:34.207Z] LOG - BadgeService - Setting badge val: 0
[2021-07-14T12:21:37.317Z] DEBUG - punt - Punt start succeeded
[2021-07-14T12:21:37.546Z] DEBUG - punt - Punt did succeed
[2021-07-14T12:21:41.881Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 2.55, downlinkMax: null, effectiveType: 4g, rtt: 100, type: null"
"[2021-07-14T12:21:58.702Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 2.2, downlinkMax: null, effectiveType: 4g, rtt: 200, type: null
[2021-07-14T12:22:04.006Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 1.7, downlinkMax: null, effectiveType: 4g, rtt: 250, type: null"
"[2021-07-14T12:22:10.713Z] INFO - Profile - setUpPhoneService() called
[2021-07-14T12:22:11.083Z] DEBUG - phoneService - initialize() called with config = {\"phoneNumber\":\"3525801398\",\"sipInfo\":{\"tncp\":{\"credentials\":{\"urname\":\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\",\"password\":\"1a4204a83c5e818d4e7253f9a5d52648\"},\"endpoints\":[{\"address\":\"udp://prod.tncp.textnow.com:5070\"},{\"address\":\"wss://prod.tncp.textnow.com:443\"}],\"features\":{\"inbound\":false,\"outbound_free\":true,\"outbound_paid\":false}},\"legacy\":{\"credentials\":{\"username\":\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\",\"password\":\"0311ae7e7abae1c8b10dc66b5795be0d\"},\"endpoint\":\"enflick.layered.net\",\"features\":{\"inbound\":false,\"outbound_free\":false,\"outbound_paid\":false}}}}
[2021-07-14T12:22:11.084Z] INFO - phoneService - setting up SipJsCallAdapter with config: {\"useWebProxy\":true,\"webProxySubdomain\":\"web1\",\"credentials\":{\"username\":\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\",\"password\":\"1a4204a83c5e818d4e7253f9a5d52648\"},\"endpoints\":[\"wss://prod.tncp.textnow.com/\"],\"enabled_for\":{\"outbound_free_enabled\":true,\"outbound_paid_enabled\":true,\"inbound_enabled\":true}}
[2021-07-14T12:22:11.085Z] DEBUG - phoneServiceModule/eventRouter -Saturday, August 21, 2021 registerConnectionEvents: registering connection events for sip-js
[2021-07-14T12:22:11.086Z] DEBUG - phoneServiceModule/eventRouter - registerCallingEvents: registering outgoing calling events for sip-js
[2021-07-14T12:22:11.086Z] DEBUG - phoneServiceModule/eventRouter - registerCallingEvents: registering incoming calling events for sip-js
[2021-07-14T12:22:11.086Z] DEBUG - phoneServiceModule/eventRouter - registerCallingEvents: registering calling events for sip-js
[2021-07-14T12:22:11.087Z] DEBUG - SipJsCallAdapter - initialize() called
[2021-07-14T12:22:11.088Z] DEBUG - SipJsCallAdapter - _tryConnecting() called
[2021-07-14T12:22:11.088Z] DEBUG - SipJsCallAdapter - _tryConnecting: starting connection attempt 1
[2021-07-14T12:22:11.113Z] INFO - sip.ua - configuration parameters after validation:
[2021-07-14T12:22:11.113Z] INFO - sip.ua - · viaHost: \"jch579qmvb8v.invalid\"
[2021-07-14T12:22:11.114Z] INFO - sip.ua - · uri: sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com
[2021-07-14T12:22:11.114Z] INFO - sip.ua - · custom: \\
[2021-07-14T12:22:11.115Z] INFO - sip.ua - · displayName: \"\"
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · password: NOT SHOWN
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · registerExpires: 600
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · register: false
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · registrarServer: sip:prod.tncp.textnow.com
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · transportConstructor: n
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · transportOptions: 
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · userAgentString: \"SIP.js/0.11.6\"
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · noAnswerTimeout: 60000
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · hackViaTcp: false
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · hackIpInContact: false
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · hackWssInTransport: false
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · hackAllowUnregisteredOptionTags: false
[2021-07-14T12:22:11.116Z] INFO - sip.ua - · sessionDescriptionHandlerFactoryOptions: },\"modifiers\":[null]}
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · contactName: \"8gneof4o\"
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · contactTransport: \"ws\"
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · forceRport: false
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · autostart: false
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · autostop: true
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · rel100: \"none\"
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · dtmfType: \"rtp\"
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · replaces: \"none\"
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · sessionDescriptionHandlerFactory: function(e,t)
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · authenticationFactory: undefined
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · allowLegacyNotifications: false
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · allowOutOfDialogRefers: false
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · authorizationUser: \"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\"
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · instanceId: \"ecdab1d1-1d5a-4090-bf1c-590373338f2a\"
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · sipjsId: \"ers5d\"
[2021-07-14T12:22:11.117Z] INFO - sip.ua - · hostportParams: \"prod.tncp.textnow.com\"
[2021-07-14T12:22:11.121Z] INFO - sip.ua - user requested startup...
[2021-07-14T12:22:11.123Z] INFO - sip.transport - configuration parameters after validation:
[2021-07-14T12:22:11.123Z] INFO - sip.transport - · wsServers: []
[2021-07-14T12:22:11.125Z] INFO - sip.transport - · connectionTimeout: 5
[2021-07-14T12:22:11.125Z] INFO - sip.transport - · maxReconnectionAttempts: 0
[2021-07-14T12:22:11.125Z] INFO - sip.transport - · reconnectionTimeout: 4
[2021-07-14T12:22:11.125Z] INFO - sip.transport - · keepAliveInterval: 0
[2021-07-14T12:22:11.125Z] INFO - sip.transport - · keepAliveDebounce: 10
[2021-07-14T12:22:11.125Z] INFO - sip.transport - · traceSip: true
[2021-07-14T12:22:11.126Z] INFO - sip.transport - connecting to WebSocket wss://web1.prod.tncp.textnow.com/
[2021-07-14T12:22:11.587Z] INFO - SipJsCallAdapter - _tryConnecting: sipjs user agent transport connected
[2021-07-14T12:22:11.587Z] DEBUG - SipJsCallAdapter - _register()
[2021-07-14T12:22:11.589Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - REGISTER sip:prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2314317\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8413 REGISTER\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;reg-id=1;+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";expires=600\r
Allow: ACK,CANCEL,INVITE,MESSAGE,BYE,OPTIONS,INFO,NOTIFY,REFER\r
Supported: path, gruu, outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:22:11.590Z] INFO - sip.transport - WebSocket wss://web1.prod.tncp.textnow.com/ connected
[2021-07-14T12:22:11.661Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 401 Unauthorized\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;rport=63650;received=10.241.41.241;branch=z9hG4bK2314317\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ccca8f0153ed95869468b86ccfa14efc.67c20000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8413 REGISTER\r
WWW-Authenticate: Digest realm=\"prod.tncp.textnow.com\", nonce=\"YO7YH2Du1vOJK7Z+nSluxPEiqXp/WFr9\"\r
Server: sip-registrar1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:22:11.683Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - REGISTER sip:prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2879088\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8414 REGISTER\r
Authorization: Digest algorithm=MD5, username=\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\", realm=\"prod.tncp.textnow.com\", nonce=\"YO7YH2Du1vOJK7Z+nSluxPEiqXp/WFr9\", uri=\"sip:prod.tncp.textnow.com\", response=\"99d451184d58e3cf8967666a17858ed3\"\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;reg-id=1;+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";expires=600\r
Allow: ACK,CANCEL,INVITE,MESSAGE,BYE,OPTIONS,INFO,NOTIFY,REFER\r
Supported: path, gruu, outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:22:11.792Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;rport=63650;received=10.241.41.241;branch=z9hG4bK2879088\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ccca8f0153ed95869468b86ccfa14efc.67c20000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8414 REGISTER\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;expires=486;pub-gruu=\"sip:13525801398@prod.tncp.textnow.com;gr=urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a\";temp-gruu=\"sip:uloc-60ea2099-3ad1-553c8-80409d9b@prod.tncp.textnow.com;gr\";+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";reg-id=1\r
Path: <sip:dm6/OIP45VT83QUK8TAWH5AK8Snx+KI=@10.241.48.22;lr;ob>\r
Supported: outbound\r
Require: outbound\r
Server: sip-registrar1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:22:11.836Z] DEBUG - phoneServiceModule/eventRouter - registerConnectionEvents: event received: phone-service-ready, adapter: sip-js"
"[2021-07-14T12:22:22.495Z] DEBUG - permissionService - handleMicrophoneAccessDenied()
[2021-07-14T12:22:22.514Z] DEBUG - phoneServiceModule/eventRouter - setServiceState(disabled-no-audio)"
"[2021-07-14T12:22:33.728Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 1.8, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null
[2021-07-14T12:22:41.866Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK407553\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=o8ho436927\r
Call-ID: ers5dcncf5oi49j8kv1m\r
CSeq: 3581 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:22:41.983Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK407553;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=o8ho436927\r
Call-ID: ers5dcncf5oi49j8kv1m\r
CSeq: 3581 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:23:11.855Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK8061820\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=22iv688086\r
Call-ID: ers5d5280t30duv1q08c\r
CSeq: 2464 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:23:11.985Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK8061820;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=22iv688086\r
Call-ID: ers5d5280t30duv1q08c\r
CSeq: 2464 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:23:41.846Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2089709\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=t90jfohfkm\r
Call-ID: ers5d9a5rvtu9o2jp25t\r
CSeq: 1034 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:23:41.983Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2089709;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=t90jfohfkm\r
Call-ID: ers5d9a5rvtu9o2jp25t\r
CSeq: 1034 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:23:53.382Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 2.65, downlinkMax: null, effectiveType: 4g, rtt: 100, type: null"
"[2021-07-14T12:24:11.855Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1509569\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=3j5oj4u7hh\r
Call-ID: ers5d9lukak7orlglkvh\r
CSeq: 9281 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:24:11.985Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1509569;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=3j5oj4u7hh\r
Call-ID: ers5d9lukak7orlglkvh\r
CSeq: 9281 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:24:41.854Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6686558\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=0goumrf8d1\r
Call-ID: ers5di8cmjls3pdn3mr5\r
CSeq: 6116 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:24:41.979Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6686558;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=0goumrf8d1\r
Call-ID: ers5di8cmjls3pdn3mr5\r
CSeq: 6116 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:25:01.084Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 2.2, downlinkMax: null, effectiveType: 4g, rtt: 200, type: null
[2021-07-14T12:25:02.912Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 1.75, downlinkMax: null, effectiveType: 4g, rtt: 200, type: null"
"[2021-07-14T12:25:11.854Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6693577\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=sp6ri6o7hk\r
Call-ID: ers5dn5rk089v87oo5au\r
CSeq: 2205 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:25:11.983Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6693577;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=sp6ri6o7hk\r
Call-ID: ers5dn5rk089v87oo5au\r
CSeq: 2205 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:25:41.854Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4144645\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=f72kdnielh\r
Call-ID: ers5dpkm4l5apgj6n08j\r
CSeq: 5892 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:25:42.057Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4144645;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=f72kdnielh\r
Call-ID: ers5dpkm4l5apgj6n08j\r
CSeq: 5892 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:26:11.855Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4349749\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=meo75nrtnn\r
Call-ID: ers5dmo3in4thi6e7se7\r
CSeq: 6721 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:26:11.994Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4349749;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=meo75nrtnn\r
Call-ID: ers5dmo3in4thi6e7se7\r
CSeq: 6721 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:26:41.852Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3376444\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=jsi3fl67cd\r
Call-ID: ers5dqh142q65mma42t9\r
CSeq: 7397 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:26:41.982Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3376444;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=jsi3fl67cd\r
Call-ID: ers5dqh142q65mma42t9\r
CSeq: 7397 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:27:11.857Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5061543\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=pr6paqbmfa\r
Call-ID: ers5de9qk9i06av6j9ho\r
CSeq: 8720 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:27:11.984Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5061543;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=pr6paqbmfa\r
Call-ID: ers5de9qk9i06av6j9ho\r
CSeq: 8720 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:27:41.096Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 1.35, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null
[2021-07-14T12:27:41.855Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK8182798\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=l6o2l8furv\r
Call-ID: ers5drs6ju2c5nvsfust\r
CSeq: 55 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:27:41.977Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK8182798;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=l6o2l8furv\r
Call-ID: ers5drs6ju2c5nvsfust\r
CSeq: 55 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:28:11.992Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK8406677\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=9rtvepihmf\r
Call-ID: ers5dpd8alrj8327a8m3\r
CSeq: 1964 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:28:11.993Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 1.65, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null
[2021-07-14T12:28:12.642Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK8406677;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=9rtvepihmf\r
Call-ID: ers5dpd8alrj8327a8m3\r
CSeq: 1964 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:28:41.878Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5036816\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=0pll6t0tgq\r
Call-ID: ers5daqvql2jhuf4up7g\r
CSeq: 8035 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:28:41.981Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5036816;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=0pll6t0tgq\r
Call-ID: ers5daqvql2jhuf4up7g\r
CSeq: 8035 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:28:45.870Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 1.25, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null"
"[2021-07-14T12:29:11.863Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3617644\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=vbc26mjspf\r
Call-ID: ers5dv5dbn9j37lr24u6\r
CSeq: 1256 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:29:11.978Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3617644;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=vbc26mjspf\r
Call-ID: ers5dv5dbn9j37lr24u6\r
CSeq: 1256 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:29:41.863Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4734878\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=56rmntjlog\r
Call-ID: ers5dc64d4u5eftkg2dn\r
CSeq: 4557 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:29:41.977Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4734878;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=56rmntjlog\r
Call-ID: ers5dc64d4u5eftkg2dn\r
CSeq: 4557 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:29:50.063Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 1.6, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null"
"[2021-07-14T12:30:11.863Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3936090\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=7ar0hpe53u\r
Call-ID: ers5d0tefmr004ob693a\r
CSeq: 9306 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:30:11.981Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3936090;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=7ar0hpe53u\r
Call-ID: ers5d0tefmr004ob693a\r
CSeq: 9306 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:30:14.846Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - REGISTER sip:prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4138757\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8415 REGISTER\r
Authorization: Digest algorithm=MD5, username=\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\", realm=\"prod.tncp.textnow.com\", nonce=\"YO7YH2Du1vOJK7Z+nSluxPEiqXp/WFr9\", uri=\"sip:prod.tncp.textnow.com\", response=\"99d451184d58e3cf8967666a17858ed3\"\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;reg-id=1;+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";expires=600\r
Allow: ACK,CANCEL,INVITE,MESSAGE,BYE,OPTIONS,INFO,NOTIFY,REFER\r
Supported: path, gruu, outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:30:14.919Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;rport=63650;received=10.241.41.241;branch=z9hG4bK4138757\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ccca8f0153ed95869468b86ccfa14efc.67c20000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8415 REGISTER\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;expires=529;pub-gruu=\"sip:13525801398@prod.tncp.textnow.com;gr=urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a\";temp-gruu=\"sip:uloc-60ea2099-3ad1-553c8-80409d9b@prod.tncp.textnow.com;gr\";+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";reg-id=1\r
Path: <sip:dm6/OIP45VT83QUK8TAWH5AK8Snx+KI=@10.241.48.22;lr;ob>\r
Supported: outbound\r
Require: outbound\r
Server: sip-registrar1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:30:41.865Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5114868\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=j6dgkusv0i\r
Call-ID: ers5d2l4krorentgb4t0\r
CSeq: 4471 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:30:41.981Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5114868;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=j6dgkusv0i\r
Call-ID: ers5d2l4krorentgb4t0\r
CSeq: 4471 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:31:11.864Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK9517616\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=vuqr9lrnmh\r
Call-ID: ers5d54cvph3tusp3sun\r
CSeq: 233 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:31:11.982Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK9517616;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=vuqr9lrnmh\r
Call-ID: ers5d54cvph3tusp3sun\r
CSeq: 233 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:31:41.887Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7702707\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=s3ae00efda\r
Call-ID: ers5dsa1scrlmut61sr6\r
CSeq: 5410 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:31:42.003Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7702707;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=s3ae00efda\r
Call-ID: ers5dsa1scrlmut61sr6\r
CSeq: 5410 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:31:58.817Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 2.15, downlinkMax: null, effectiveType: 4g, rtt: 100, type: null"
"[2021-07-14T12:32:11.903Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK9428817\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=vbhe6sdvlo\r
Call-ID: ers5djpde92utcajvtj6\r
CSeq: 2602 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:32:12.019Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK9428817;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=vbhe6sdvlo\r
Call-ID: ers5djpde92utcajvtj6\r
CSeq: 2602 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:32:41.906Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7173748\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=rd0gbktek8\r
Call-ID: ers5dklg8mviogq0gm55\r
CSeq: 6796 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:32:42.134Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7173748;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=rd0gbktek8\r
Call-ID: ers5dklg8mviogq0gm55\r
CSeq: 6796 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:33:11.907Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6777675\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=jhd33f92e3\r
Call-ID: ers5dhaiaj0l4j88iimi\r
CSeq: 2722 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:33:12.017Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6777675;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=jhd33f92e3\r
Call-ID: ers5dhaiaj0l4j88iimi\r
CSeq: 2722 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:33:41.909Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1989290\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=33du0afhqq\r
Call-ID: ers5d0cmilrngoq8u4k4\r
CSeq: 5867 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:33:42.131Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1989290;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=33du0afhqq\r
Call-ID: ers5d0cmilrngoq8u4k4\r
CSeq: 5867 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:34:00.108Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 2.65, downlinkMax: null, effectiveType: 4g, rtt: 100, type: null"
"[2021-07-14T12:34:12.806Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3489696\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=efmt87kuk4\r
Call-ID: ers5dct0e0913batun22\r
CSeq: 7068 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:34:12.894Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3489696;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=efmt87kuk4\r
Call-ID: ers5dct0e0913batun22\r
CSeq: 7068 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:34:42.794Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4489445\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=kknquhtnaa\r
Call-ID: ers5d5gan7601bjh854p\r
CSeq: 3605 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:34:42.885Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4489445;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=kknquhtnaa\r
Call-ID: ers5d5gan7601bjh854p\r
CSeq: 3605 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:35:12.855Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1222347\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=asrebc9cul\r
Call-ID: ers5d1f6lfemto7tt0hh\r
CSeq: 7280 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:35:12.944Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1222347;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=asrebc9cul\r
Call-ID: ers5d1f6lfemto7tt0hh\r
CSeq: 7280 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:35:43.021Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5248053\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=1vtgb908v2\r
Call-ID: ers5damss7v6mq82t1qu\r
CSeq: 2280 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:35:43.112Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5248053;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=1vtgb908v2\r
Call-ID: ers5damss7v6mq82t1qu\r
CSeq: 2280 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:36:12.842Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4529896\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=d30lq471gf\r
Call-ID: ers5d2k7hb1dln7mhfsc\r
CSeq: 3047 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:36:12.936Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4529896;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=d30lq471gf\r
Call-ID: ers5d2k7hb1dln7mhfsc\r
CSeq: 3047 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:36:42.732Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6329225\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=40erhba308\r
Call-ID: ers5d40giu95j1n2k4b9\r
CSeq: 8849 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:36:42.821Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6329225;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=40erhba308\r
Call-ID: ers5d40giu95j1n2k4b9\r
CSeq: 8849 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:37:12.529Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1895619\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=p1esfk4cfr\r
Call-ID: ers5dd0036uk6mvu10kf\r
CSeq: 2034 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:37:12.620Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1895619;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=p1esfk4cfr\r
Call-ID: ers5dd0036uk6mvu10kf\r
CSeq: 2034 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:37:42.586Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4621904\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=rdv3g8580l\r
Call-ID: ers5d7ji2de4obbe5o57\r
CSeq: 9229 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:37:42.678Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4621904;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=rdv3g8580l\r
Call-ID: ers5d7ji2de4obbe5o57\r
CSeq: 9229 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:38:12.932Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5901561\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=hsortpttkt\r
Call-ID: ers5df6kuk3n6rm84gb6\r
CSeq: 4430 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:38:13.024Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5901561;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=hsortpttkt\r
Call-ID: ers5df6kuk3n6rm84gb6\r
CSeq: 4430 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:39:01.676Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - REGISTER sip:prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6302957\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8416 REGISTER\r
Authorization: Digest algorithm=MD5, username=\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\", realm=\"prod.tncp.textnow.com\", nonce=\"YO7YH2Du1vOJK7Z+nSluxPEiqXp/WFr9\", uri=\"sip:prod.tncp.textnow.com\", response=\"99d451184d58e3cf8967666a17858ed3\"\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;reg-id=1;+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";expires=600\r
Allow: ACK,CANCEL,INVITE,MESSAGE,BYE,OPTIONS,INFO,NOTIFY,REFER\r
Supported: path, gruu, outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:39:01.758Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;rport=63650;received=10.241.41.241;branch=z9hG4bK6302957\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ccca8f0153ed95869468b86ccfa14efc.67c20000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8416 REGISTER\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;expires=526;pub-gruu=\"sip:13525801398@prod.tncp.textnow.com;gr=urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a\";temp-gruu=\"sip:uloc-60ea2099-3ad1-553c8-80409d9b@prod.tncp.textnow.com;gr\";+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";reg-id=1\r
Path: <sip:dm6/OIP45VT83QUK8TAWH5AK8Snx+KI=@10.241.48.22;lr;ob>\r
Supported: outbound\r
Require: outbound\r
Server: sip-registrar1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:39:30.916Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6540759\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=4pd17mbakr\r
Call-ID: ers5d8pg7d7eoqnv8gdh\r
CSeq: 5406 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:39:31.009Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6540759;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=4pd17mbakr\r
Call-ID: ers5d8pg7d7eoqnv8gdh\r
CSeq: 5406 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:40:31.820Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK714250\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=t9tdpgdp28\r
Call-ID: ers5dp73v7ba5qt8c3lr\r
CSeq: 7233 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:40:32.011Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK714250;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=t9tdpgdp28\r
Call-ID: ers5dp73v7ba5qt8c3lr\r
CSeq: 7233 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:41:30.783Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3580744\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=rklqv6po58\r
Call-ID: ers5dp2gm5a8pjhtuau7\r
CSeq: 6739 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:41:30.869Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3580744;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=rklqv6po58\r
Call-ID: ers5dp2gm5a8pjhtuau7\r
CSeq: 6739 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:42:32.865Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1449420\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ougbep8sne\r
Call-ID: ers5d7bk5phq1n2k1p06\r
CSeq: 7949 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:42:32.952Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1449420;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ougbep8sne\r
Call-ID: ers5d7bk5phq1n2k1p06\r
CSeq: 7949 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:43:31.310Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1095363\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ktmn79h6ud\r
Call-ID: ers5dakqife5s35emodb\r
CSeq: 7770 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:43:31.400Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1095363;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ktmn79h6ud\r
Call-ID: ers5dakqife5s35emodb\r
CSeq: 7770 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:44:30.688Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3604194\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ovsjlp6ael\r
Call-ID: ers5dhjt26l0ag68q3si\r
CSeq: 8780 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:44:30.897Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3604194;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ovsjlp6ael\r
Call-ID: ers5dhjt26l0ag68q3si\r
CSeq: 8780 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:45:32.508Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4617046\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=q0grn3ccal\r
Call-ID: ers5dnuu82tfeap51c53\r
CSeq: 4980 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:45:32.709Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4617046;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=q0grn3ccal\r
Call-ID: ers5dnuu82tfeap51c53\r
CSeq: 4980 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:46:31.394Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2555783\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ao1fg294c9\r
Call-ID: ers5d5pgu0uqohofe0d6\r
CSeq: 5803 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:46:31.562Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2555783;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ao1fg294c9\r
Call-ID: ers5d5pgu0uqohofe0d6\r
CSeq: 5803 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:46:36.209Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 5.4, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null
[2021-07-14T12:46:40.468Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 1.9, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null"
"[2021-07-14T12:47:18.821Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 4.45, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null"
"[2021-07-14T12:47:30.589Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4302919\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=lhoiqvccs2\r
Call-ID: ers5d9t36rj5ksdjp0pu\r
CSeq: 7056 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:47:30.757Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4302919;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=lhoiqvccs2\r
Call-ID: ers5d9t36rj5ksdjp0pu\r
CSeq: 7056 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:47:45.544Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - REGISTER sip:prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6640322\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8417 REGISTER\r
Authorization: Digest algorithm=MD5, username=\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\", realm=\"prod.tncp.textnow.com\", nonce=\"YO7YH2Du1vOJK7Z+nSluxPEiqXp/WFr9\", uri=\"sip:prod.tncp.textnow.com\", response=\"99d451184d58e3cf8967666a17858ed3\"\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;reg-id=1;+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";expires=600\r
Allow: ACK,CANCEL,INVITE,MESSAGE,BYE,OPTIONS,INFO,NOTIFY,REFER\r
Supported: path, gruu, outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:47:45.722Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;rport=63650;received=10.241.41.241;branch=z9hG4bK6640322\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ccca8f0153ed95869468b86ccfa14efc.67c20000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8417 REGISTER\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;expires=470;pub-gruu=\"sip:13525801398@prod.tncp.textnow.com;gr=urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a\";temp-gruu=\"sip:uloc-60ea2099-3ad1-553c8-80409d9b@prod.tncp.textnow.com;gr\";+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";reg-id=1\r
Path: <sip:dm6/OIP45VT83QUK8TAWH5AK8Snx+KI=@10.241.48.22;lr;ob>\r
Supported: outbound\r
Require: outbound\r
Server: sip-registrar1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:48:31.643Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7297322\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=865877kvh1\r
Call-ID: ers5dhg62lfpchk09gnh\r
CSeq: 2401 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:48:31.997Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7297322;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=865877kvh1\r
Call-ID: ers5dhg62lfpchk09gnh\r
CSeq: 2401 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:49:30.915Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7735087\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=dk3ipl3rsm\r
Call-ID: ers5d912oi23v2qb8ge1\r
CSeq: 5267 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:49:31.116Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7735087;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=dk3ipl3rsm\r
Call-ID: ers5d912oi23v2qb8ge1\r
CSeq: 5267 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:50:31.014Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5492083\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=a56npaad8m\r
Call-ID: ers5dgij26de282qiv08\r
CSeq: 4782 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:50:31.167Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5492083;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=a56npaad8m\r
Call-ID: ers5dgij26de282qiv08\r
CSeq: 4782 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:51:30.578Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6437276\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=uttfjjlse5\r
Call-ID: ers5dn1bqgtqduac7l4t\r
CSeq: 398 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:51:30.757Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6437276;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=uttfjjlse5\r
Call-ID: ers5dn1bqgtqduac7l4t\r
CSeq: 398 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:52:32.912Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK9930259\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=c4v9m38ipn\r
Call-ID: ers5dkklt7kpfbsgdnpb\r
CSeq: 5247 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:52:33.077Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK9930259;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=c4v9m38ipn\r
Call-ID: ers5dkklt7kpfbsgdnpb\r
CSeq: 5247 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:53:30.553Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7877125\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=jbtn52v0bu\r
Call-ID: ers5d66nq1l67u62p9ik\r
CSeq: 8578 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:53:30.700Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7877125;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=jbtn52v0bu\r
Call-ID: ers5d66nq1l67u62p9ik\r
CSeq: 8578 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:54:30.833Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1593831\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=27fh903lkb\r
Call-ID: ers5dhs01kh00b4den84\r
CSeq: 4586 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:54:31.012Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1593831;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=27fh903lkb\r
Call-ID: ers5dhs01kh00b4den84\r
CSeq: 4586 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:55:31.340Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1526939\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=c01qn08mkq\r
Call-ID: ers5dthj202kkbhuk7to\r
CSeq: 710 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:55:31.451Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1526939;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=c01qn08mkq\r
Call-ID: ers5dthj202kkbhuk7to\r
CSeq: 710 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:55:34.277Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - REGISTER sip:prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1332692\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8418 REGISTER\r
Authorization: Digest algorithm=MD5, username=\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\", realm=\"prod.tncp.textnow.com\", nonce=\"YO7YH2Du1vOJK7Z+nSluxPEiqXp/WFr9\", uri=\"sip:prod.tncp.textnow.com\", response=\"99d451184d58e3cf8967666a17858ed3\"\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;reg-id=1;+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";expires=600\r
Allow: ACK,CANCEL,INVITE,MESSAGE,BYE,OPTIONS,INFO,NOTIFY,REFER\r
Supported: path, gruu, outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:55:34.362Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;rport=63650;received=10.241.41.241;branch=z9hG4bK1332692\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ccca8f0153ed95869468b86ccfa14efc.67c20000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8418 REGISTER\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;expires=585;pub-gruu=\"sip:13525801398@prod.tncp.textnow.com;gr=urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a\";temp-gruu=\"sip:uloc-60ea2099-3ad1-553c8-80409d9b@prod.tncp.textnow.com;gr\";+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";reg-id=1\r
Path: <sip:dm6/OIP45VT83QUK8TAWH5AK8Snx+KI=@10.241.48.22;lr;ob>\r
Supported: outbound\r
Require: outbound\r
Server: sip-registrar1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:56:30.804Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2745376\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=k090j8snek\r
Call-ID: ers5d1d5g8fpd82871is\r
CSeq: 6360 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:56:30.908Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2745376;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=k090j8snek\r
Call-ID: ers5d1d5g8fpd82871is\r
CSeq: 6360 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:57:31.765Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3505467\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=m3gpc4sba5\r
Call-ID: ers5dvua3tcpjq1ccfn4\r
CSeq: 3702 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:57:31.887Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3505467;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=m3gpc4sba5\r
Call-ID: ers5dvua3tcpjq1ccfn4\r
CSeq: 3702 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T12:58:30.886Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5326638\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=1crrv3dsan\r
Call-ID: ers5dbvfqvrp8o7ustca\r
CSeq: 9956 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:58:31.020Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5326638;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=1crrv3dsan\r
Call-ID: ers5dbvfqvrp8o7ustca\r
CSeq: 9956 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T12:59:16.025Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 2.7, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null"
"[2021-07-14T12:59:30.558Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5571005\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ojd8esg0nv\r
Call-ID: ers5dafq3vgomsj5ksa0\r
CSeq: 9840 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T12:59:30.714Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5571005;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ojd8esg0nv\r
Call-ID: ers5dafq3vgomsj5ksa0\r
CSeq: 9840 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:00:30.849Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3213402\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=l40c4qk2cj\r
Call-ID: ers5dv6eajfg7a9bggh5\r
CSeq: 9568 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:00:30.986Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3213402;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=l40c4qk2cj\r
Call-ID: ers5dv6eajfg7a9bggh5\r
CSeq: 9568 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:01:30.874Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2302549\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6itpf1i7uk\r
Call-ID: ers5dch7plg669m124mc\r
CSeq: 9315 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:01:31.023Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK2302549;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6itpf1i7uk\r
Call-ID: ers5dch7plg669m124mc\r
CSeq: 9315 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:02:32.822Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4023705\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ll97gcpuvc\r
Call-ID: ers5dokudsm110mp7gv0\r
CSeq: 8765 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:02:32.974Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4023705;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ll97gcpuvc\r
Call-ID: ers5dokudsm110mp7gv0\r
CSeq: 8765 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T13:03:30.837Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7763706\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e215m7tb6n\r
Call-ID: ers5d8g9lbdsm12bo50a\r
CSeq: 2803 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:03:31.084Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK7763706;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e215m7tb6n\r
Call-ID: ers5d8g9lbdsm12bo50a\r
CSeq: 2803 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:04:30.850Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3602782\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=gevs8cc7p6\r
Call-ID: ers5d3h18nbdf0rhvrr9\r
CSeq: 1539 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:04:30.955Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK3602782;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=gevs8cc7p6\r
Call-ID: ers5d3h18nbdf0rhvrr9\r
CSeq: 1539 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T13:05:17.641Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - REGISTER sip:prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK9479324\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8419 REGISTER\r
Authorization: Digest algorithm=MD5, username=\"13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv\", realm=\"prod.tncp.textnow.com\", nonce=\"YO7YH2Du1vOJK7Z+nSluxPEiqXp/WFr9\", uri=\"sip:prod.tncp.textnow.com\", response=\"99d451184d58e3cf8967666a17858ed3\"\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;reg-id=1;+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";expires=600\r
Allow: ACK,CANCEL,INVITE,MESSAGE,BYE,OPTIONS,INFO,NOTIFY,REFER\r
Supported: path, gruu, outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:05:17.777Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;rport=63650;received=10.241.41.241;branch=z9hG4bK9479324\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=ccca8f0153ed95869468b86ccfa14efc.67c20000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6ttg5uvjov\r
Call-ID: qu07g7f0104k1f9bu7uouf\r
CSeq: 8419 REGISTER\r
Contact: <sip:8gneof4o@jch579qmvb8v.invalid;transport=ws>;expires=452;pub-gruu=\"sip:13525801398@prod.tncp.textnow.com;gr=urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a\";temp-gruu=\"sip:uloc-60ea2099-3ad1-553c8-80409d9b@prod.tncp.textnow.com;gr\";+sip.instance=\"<urn:uuid:ecdab1d1-1d5a-4090-bf1c-590373338f2a>\";reg-id=1\r
Path: <sip:dm6/OIP45VT83QUK8TAWH5AK8Snx+KI=@10.241.48.22;lr;ob>\r
Supported: outbound\r
Require: outbound\r
Server: sip-registrar1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:05:30.617Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6967675\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=opnr2uaf5o\r
Call-ID: ers5d370k9r5amfp51sh\r
CSeq: 77 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:05:30.738Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK6967675;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=opnr2uaf5o\r
Call-ID: ers5d370k9r5amfp51sh\r
CSeq: 77 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:06:31.793Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK270770\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=cgng7qb91f\r
Call-ID: ers5dfu8i7dv11m65igr\r
CSeq: 1025 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:06:31.916Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK270770;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=cgng7qb91f\r
Call-ID: ers5dfu8i7dv11m65igr\r
CSeq: 1025 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:07:32.899Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1509718\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=u3675nh67r\r
Call-ID: ers5dfvlfqcp1tqbrghs\r
CSeq: 2893 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:07:33.003Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1509718;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=u3675nh67r\r
Call-ID: ers5dfvlfqcp1tqbrghs\r
CSeq: 2893 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T13:08:33.004Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5109352\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=kj8faupm3g\r
Call-ID: ers5d2fpopus5gor6apq\r
CSeq: 7602 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:08:33.125Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK5109352;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=kj8faupm3g\r
Call-ID: ers5d2fpopus5gor6apq\r
CSeq: 7602 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:09:31.008Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1626373\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=b0p1idhne6\r
Call-ID: ers5ddnj03mkub7o8r6f\r
CSeq: 6745 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:09:31.130Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK1626373;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=b0p1idhne6\r
Call-ID: ers5ddnj03mkub7o8r6f\r
CSeq: 6745 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
"[2021-07-14T13:09:42.083Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4325935\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=tgm1vb0esg\r
Call-ID: ers5dn2uupmojdh0ipdb\r
CSeq: 6356 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:09:42.234Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4325935;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=tgm1vb0esg\r
Call-ID: ers5dn2uupmojdh0ipdb\r
CSeq: 6356 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r


[2021-07-14T13:09:45.004Z] INFO - CallDetailsLog - CALL_DETAILS_NETWORK_CHANGED: downlink: 4.5, downlinkMax: null, effectiveType: 4g, rtt: 150, type: null"
"[2021-07-14T13:10:11.996Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Outgoing - OPTIONS sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com SIP/2.0\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4459919\r
Max-Forwards: 70\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6a81mvi82d\r
Call-ID: ers5dvqfibpi0bnrml0h\r
CSeq: 6442 OPTIONS\r
Supported: outbound\r
User-Agent: SIP.js/0.11.6\r
Content-Length: 0\r
\r


[2021-07-14T13:10:12.086Z] INFO - CallDetailsLog - CALL_DETAILS_SIP_MESSAGE: Incoming - SIP/2.0 200 OK\r
Via: SIP/2.0/WSS jch579qmvb8v.invalid;branch=z9hG4bK4459919;rport=63650;received=10.241.41.241\r
To: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=e95814102b11b868533fab3273132772.6a910000\r
From: <sip:13525801398_3B2akTbTW9nTxzzjUR081j500eDh1XHXX4O6lbxNtBvv@prod.tncp.textnow.com>;tag=6a81mvi82d\r
Call-ID: ers5dvqfibpi0bnrml0h\r
CSeq: 6442 OPTIONS\r
Server: sip-proxy-ws1.tncp\r
Content-Length: 0\r
\r

"
