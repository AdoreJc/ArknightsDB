# CookieContainer

**Namespace:** `System.Net`


## Fields

- `Hashtable m_domainTable`

- `Int32 m_maxCookieSize`

- `Int32 m_maxCookies`

- `Int32 m_maxCookiesPerDomain`

- `Int32 m_count`

- `String m_fqdnMyDomain`


## Methods

- `Void AddRemoveDomain(String, PathList)`

- `Boolean AgeCookies(String)`

- `Int32 ExpireCollection(CookieCollection)`

- `Void BuildCookieCollectionFromDomainMatches(Uri, Boolean, Int32, CookieCollection, List`1, Boolean)`

- `Void MergeUpdateCollections(CookieCollection, CookieCollection, Int32, Boolean, Boolean)`

- `String GetCookieHeader(Uri)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class CookieContainer
{
	private static readonly HeaderVariantInfo[] HeaderInfo; // 0x0
	private Hashtable m_domainTable; // 0x10
	private Int32 m_maxCookieSize; // 0x18
	private Int32 m_maxCookies; // 0x1c
	private Int32 m_maxCookiesPerDomain; // 0x20
	private Int32 m_count; // 0x24
	private String m_fqdnMyDomain; // 0x28


	// RVA: 0x643a3e4 VA: 0x7598a523e4
	public Void .ctor() { }
	// RVA: 0x643a504 VA: 0x7598a52504
	private Void AddRemoveDomain(String key, PathList value) { }
	// RVA: 0x643a62c VA: 0x7598a5262c
	internal Void Add(Cookie cookie, Boolean throwOnError) { }
	// RVA: 0x643b48c VA: 0x7598a5348c
	private Boolean AgeCookies(String domain) { }
	// RVA: 0x643ca00 VA: 0x7598a54a00
	private Int32 ExpireCollection(CookieCollection cc) { }
	// RVA: 0x643cb90 VA: 0x7598a54b90
	internal Boolean IsLocalDomain(String host) { }
	// RVA: 0x643ce2c VA: 0x7598a54e2c
	internal CookieCollection CookieCutter(Uri uri, String headerName, String setCookieHeader, Boolean isThrow) { }
	// RVA: 0x643d500 VA: 0x7598a55500
	internal CookieCollection InternalGetCookies(Uri uri) { }
	// RVA: 0x643d9cc VA: 0x7598a559cc
	private Void BuildCookieCollectionFromDomainMatches(Uri uri, Boolean isSecure, Int32 port, CookieCollection cookies, List`1 domainAttribute, Boolean matchOnlyPlainCookie) { }
	// RVA: 0x643e1f4 VA: 0x7598a561f4
	private Void MergeUpdateCollections(CookieCollection destination, CookieCollection source, Int32 port, Boolean isSecure, Boolean isPlainOnly) { }
	// RVA: 0x643e400 VA: 0x7598a56400
	public String GetCookieHeader(Uri uri) { }
	// RVA: 0x643e4d0 VA: 0x7598a564d0
	internal String GetCookieHeader(Uri uri, out String optCookie2) { }
	// RVA: 0x643e874 VA: 0x7598a56874
	private static Void .cctor() { }
}
```