<!-- ## Configure cookies -->
>*Supported versions: Microsoft Edge on Windows 10*<br>
>*Default setting: Disabled or not configured (Allow all cookies from all sites)*

[!INCLUDE [configure-cookies-shortdesc](../shortdesc/configure-cookies-shortdesc.md)]

### Allowed values

|Group Policy  |MDM |Registry |Description |Most restricted |
|---|:---:|:---:|---|:---:|
|Enabled |0 |0 |Block all cookies from all sites |![Most restricted value](../images/check-gn.png) |
|Enabled |1 |1 |Block only coddies from third party websites | |
|Disabled or not configured<br>**(default)** |2 |2 |Allow all cookies from all sites | |
---

### ADMX info and settings
#### ADMX info
- **GP English name:** Configure cookies
- **GP name:** Cookies
- **GP element:** CookiesListBox
- **GP path:** Windows Components/Microsoft Edge
- **GP ADMX file name:** MicrosoftEdge.admx

#### MDM settings
- **MDM name:** Browser/[AllowCookies](https://docs.microsoft.com/en-us/windows/client-management/mdm/policy-csp-browser\#browser-allowcookies)
- **Supported devices:** Desktop and Mobile
- **URI full path:** ./Vendor/MSFT/Policy/Config/Browser/AllowCookies 
- **Data type:** Integer

#### Registry settings
** |<ul><li>**Path:** HKLM\\Software\\Policies\\Microsoft\\MicrosoftEdge\\Main 
**Value name:** Cookies
**Value type:** REG_DWORD

<hr>