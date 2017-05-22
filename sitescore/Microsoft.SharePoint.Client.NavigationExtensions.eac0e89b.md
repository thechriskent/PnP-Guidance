# NavigationExtensions.GetCustomActions Method  
  

**Namespace:** [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md)  
**Assembly:** OfficeDevPnP.Core.dll  
## Syntax
```C#
public static IEnumerable<UserCustomAction> GetCustomActions(this Web web, Expression<Func<UserCustomAction, Object>>[] expressions)
```
### Parameters
#### web  
&emsp;&emsp;Type: Microsoft.SharePoint.Client.Web  
&emsp;&emsp;  

  

#### expressions  
&emsp;&emsp;Type: System.Linq.Expressions.Expression&lt;System.Func&lt;Microsoft.SharePoint.Client.UserCustomAction, System.Object&gt;&gt;[]  
&emsp;&emsp;  

  

### Return Value
Type: IEnumerable<UserCustomAction>  

## See also
- [NavigationExtensions](Microsoft.SharePoint.Client.NavigationExtensions.md) 
- [Microsoft.SharePoint.Client](Microsoft.SharePoint.Client.md) 