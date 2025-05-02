# XmlUrlResolver

**Namespace:** `System.Xml`


## Fields

- `ICredentials _credentials`

- `IWebProxy _proxy`

- `RequestCachePolicy _cachePolicy`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlUrlResolver : XmlResolver
{
	private static Object s_DownloadManager; // 0x0
	private ICredentials _credentials; // 0x10
	private IWebProxy _proxy; // 0x18
	private RequestCachePolicy _cachePolicy; // 0x20

	private static XmlDownloadManager DownloadManager { get; }

	// RVA: 0x62cfd74 VA: 0x75988e7d74
	private static XmlDownloadManager get_DownloadManager() { }
	// RVA: 0x62cfe48 VA: 0x75988e7e48
	public Void .ctor() { }
	// RVA: 0x62cfe50 VA: 0x75988e7e50
	public override Object GetEntity(Uri absoluteUri, String role, Type ofObjectToReturn) { }
	// RVA: 0x62cffcc VA: 0x75988e7fcc
	public override Uri ResolveUri(Uri baseUri, String relativeUri) { }
	// RVA: 0x62cffd0 VA: 0x75988e7fd0
	public override Task`1 GetEntityAsync(Uri absoluteUri, String role, Type ofObjectToReturn) { }
}
```