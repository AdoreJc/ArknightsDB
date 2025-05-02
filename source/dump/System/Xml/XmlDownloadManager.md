# XmlDownloadManager

**Namespace:** `System.Xml`


## Fields

- `Hashtable connections`


## Methods

- `Stream GetNonFileStream(Uri, ICredentials, IWebProxy, RequestCachePolicy)`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
internal class XmlDownloadManager
{
	private Hashtable connections; // 0x10


	// RVA: 0x62ca050 VA: 0x75988e2050
	internal Stream GetStream(Uri uri, ICredentials credentials, IWebProxy proxy, RequestCachePolicy cachePolicy) { }
	// RVA: 0x62ca154 VA: 0x75988e2154
	private Stream GetNonFileStream(Uri uri, ICredentials credentials, IWebProxy proxy, RequestCachePolicy cachePolicy) { }
	// RVA: 0x62ca830 VA: 0x75988e2830
	internal Void Remove(String host) { }
	// RVA: 0x62ca99c VA: 0x75988e299c
	internal Task`1 GetStreamAsync(Uri uri, ICredentials credentials, IWebProxy proxy, RequestCachePolicy cachePolicy) { }
	// RVA: 0x62cab18 VA: 0x75988e2b18
	private Task`1 GetNonFileStreamAsync(Uri uri, ICredentials credentials, IWebProxy proxy, RequestCachePolicy cachePolicy) { }
	// RVA: 0x62cac98 VA: 0x75988e2c98
	public Void .ctor() { }
}
```