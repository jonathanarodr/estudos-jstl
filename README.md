# estudos-jstl

## Pacotes
* **core**: pacote de funções do core
```java
<%@ taglib uri="http://java.sun.com/jsp/jstl/core" prefix="c" %>
```
* **format**: pacote de funções para formatação
```java
<%@ taglib uri="http://java.sun.com/jsp/jstl/fmt" prefix="fmt" %>
```

## Tags
* **forEach**: utilizado para realizar loop
```html
<c:forEach var="l" items="${list}">
  ... html aqui ...
</c:forEach>
```
