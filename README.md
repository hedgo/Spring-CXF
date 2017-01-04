Spring-CXF
==========

RESTful web service using Apache Cfx and Spring

AO:
Uruchomienie:
http://localhost:8080/Spring-CXF/ws/foobar/heeeeeeeeeej


Ciekawsze:
	<jaxrs:server id="fooBarWs" address="/foobar">
		<jaxrs:serviceBeans>
			<ref bean="fooBarWsClass" />
		</jaxrs:serviceBeans>
