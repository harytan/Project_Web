Project_Web
===========

tools: java,jsp,ajax,jquery,html5,google adsense,google analytics

template: bootstrap

web-server: tomcat

framework: struts 2

db: mysql

cvs : github

backend functional req

frontend functional req 

Struts Flow

1.User clicks on a link in an HTML page.
2.Servlet controller receives the request, looks up mapping information in struts-config.xml, and routes to an action.
3.Action makes a call to a Model layer service.
4.Service makes a call to the Data layer (database) and the requested data is returned.
5.Service returns to the action.
6.Action forwards to a View resource (JSP page)
7.Servlet looks up the mapping for the requested resource and forwards to the appropriate JSP page.
8.JSP file is invoked and sent to the browser as HTML.
9.User is presented with a new HTML page in a web browser.
