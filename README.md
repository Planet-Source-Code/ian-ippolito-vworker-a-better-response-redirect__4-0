<div align="center">

## A better response\.redirect


</div>

### Description

The response.redirect method is great for moving a user from one page to another. However, it does have one major limitation--you can only use it if absolutely nothing has been written to the page. Sometimes, you actually do want to write something to the page and then redirect it, for example when displaying the status of an operation. In this case, the following JavaRedirect function comes in handy. It requires a Java compatible browser. (Note:this script has been changed to incorporate Lewis Moten's helpful suggestions).
 
### More Info
 


<span>             |<span>
---                |---
**Submitted On**   |
**By**             |[Ian Ippolito \(vWorker\)](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByAuthor/ian-ippolito-vworker.md)
**Level**          |Intermediate
**User Rating**    |3.8 (38 globes from 10 users)
**Compatibility**  |ASP \(Active Server Pages\)
**Category**       |[Internet/ Browsers/ HTML](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByCategory/internet-browsers-html__4-9.md)
**World**          |[ASP / VbScript](https://github.com/Planet-Source-Code/PSCIndex/blob/master/ByWorld/asp-vbscript.md)
**Archive File**   |[](https://github.com/Planet-Source-Code/ian-ippolito-vworker-a-better-response-redirect__4-0/archive/master.zip)





### Source Code

```
sub JavaRedirect (strURL)
'Response.Write "redirect to:" & strURL
%>
<SCRIPT language="JavaScript">
<!--
window.location.href =
'<%=URL%>';
//-->
</SCRIPT>
<%
end sub
```

