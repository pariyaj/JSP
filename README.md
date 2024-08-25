# JSP 
# JSTL Tags 
JSTL is a collection of JSP tags that are used for different tasks.
There are 5 main category for JSTL tags.
 1. Core Tags
    Some Common tags: <c:out> - <c:set > - <c:remove > - <c:catch> - <c:choose> - <c:url> - <c:when>
    Syntax: <%@ taglib prefix = "c" uri = "" %>
 2. Formatting Tags
    Some Common tags: <fmt:parseNumber> - <fmt:formatNumber> - <fmt:formatDate> - <fmt:setTimeZone> - <fmt:requestEncoding>
    Syntax: <%@ taglib prefix = "fmt" uri = "" %> 
 3. SQL Tags
    Some Common tags: <sql:setDataSource> - <sql:query> - <sql:update> - <sql:param> - <sql:dateParam> - <sql:transaction>
    Syntax: <%@ taglib prefix = "sql" uri = "" %>
 4. XML Tags
    Some Common tags: <x:out> - <x:set > - <x:transform > - <x:param >
    Syntax: <%@ taglib prefix = "x" 
             uri = "http://java.sun.com/jsp/jstl/xml" %>    
 5. JSTL Functions
    Some Common tags: fn:contains() - fn:endsWith() - fn:length() - fn:split() - fn:toLowerCase() - fn:substring() - fn:replace()
    Syntax: <%@ taglib prefix = "fn"
             uri = "http://java.sun.com/jsp/jstl/functions" %>
