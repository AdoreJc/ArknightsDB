# WebProxy

**Namespace:** `System.Net`


## Fields

- `Boolean _UseRegistry`

- `Boolean _BypassOnLocal`

- `Boolean m_EnableAutoproxy`

- `Uri _ProxyAddress`

- `ArrayList _BypassList`

- `ICredentials _Credentials`

- `Hashtable _ProxyHostAddresses`

- `AutoWebProxyScriptEngine m_ScriptEngine`


## Properties

- `ICredentials Credentials`

- `Boolean UseDefaultCredentials`


## Methods

- `ICredentials get_Credentials()`

- `Boolean get_UseDefaultCredentials()`

- `Void set_UseDefaultCredentials(Boolean)`

- `Uri GetProxy(Uri)`

- `Void UpdateRegExList(Boolean)`

- `Boolean IsMatchInBypassList(Uri)`

- `Boolean IsLocal(Uri)`

- `Boolean IsLocalInProxyHash(Uri)`

- `Boolean IsBypassed(Uri)`

- `Boolean IsBypassedManual(Uri)`

- `Boolean GetProxyAuto(Uri, out)`

- `Boolean IsBypassedAuto(Uri, out)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class WebProxy : IWebProxy, ISerializable
{
	private Boolean _UseRegistry; // 0x10
	private Boolean _BypassOnLocal; // 0x11
	private Boolean m_EnableAutoproxy; // 0x12
	private Uri _ProxyAddress; // 0x18
	private ArrayList _BypassList; // 0x20
	private ICredentials _Credentials; // 0x28
	private Regex[] _RegExBypassList; // 0x30
	private Hashtable _ProxyHostAddresses; // 0x38
	private AutoWebProxyScriptEngine m_ScriptEngine; // 0x40

	public ICredentials Credentials { get; }
	public Boolean UseDefaultCredentials { get; set; }
	internal AutoWebProxyScriptEngine ScriptEngine { get; }

	// RVA: 0x6441cac VA: 0x7598a59cac
	public Void .ctor() { }
	// RVA: 0x6441cc0 VA: 0x7598a59cc0
	public Void .ctor(Uri Address, Boolean BypassOnLocal, String[] BypassList, ICredentials Credentials) { }
	// RVA: 0x6442000 VA: 0x7598a5a000
	public ICredentials get_Credentials() { }
	// RVA: 0x6442008 VA: 0x7598a5a008
	public Boolean get_UseDefaultCredentials() { }
	// RVA: 0x6442084 VA: 0x7598a5a084
	public Void set_UseDefaultCredentials(Boolean value) { }
	// RVA: 0x6442100 VA: 0x7598a5a100
	public Uri GetProxy(Uri destination) { }
	// RVA: 0x6441d9c VA: 0x7598a59d9c
	private Void UpdateRegExList(Boolean canThrow) { }
	// RVA: 0x64423cc VA: 0x7598a5a3cc
	private Boolean IsMatchInBypassList(Uri input) { }
	// RVA: 0x6442564 VA: 0x7598a5a564
	private Boolean IsLocal(Uri host) { }
	// RVA: 0x64426c4 VA: 0x7598a5a6c4
	private Boolean IsLocalInProxyHash(Uri host) { }
	// RVA: 0x64427b4 VA: 0x7598a5a7b4
	public Boolean IsBypassed(Uri host) { }
	// RVA: 0x6442304 VA: 0x7598a5a304
	private Boolean IsBypassedManual(Uri host) { }
	// RVA: 0x64428f8 VA: 0x7598a5a8f8
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x6442c90 VA: 0x7598a5ac90
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x6442c9c VA: 0x7598a5ac9c
	protected virtual Void GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x6442dc0 VA: 0x7598a5adc0
	internal AutoWebProxyScriptEngine get_ScriptEngine() { }
	// RVA: 0x6442dc8 VA: 0x7598a5adc8
	public static IWebProxy CreateDefaultProxy() { }
	// RVA: 0x6442e30 VA: 0x7598a5ae30
	internal Void .ctor(Boolean enableAutoproxy) { }
	// RVA: 0x6442c84 VA: 0x7598a5ac84
	internal Void UnsafeUpdateFromRegistry() { }
	// RVA: 0x6442284 VA: 0x7598a5a284
	private Boolean GetProxyAuto(Uri destination, out Uri proxyUri) { }
	// RVA: 0x644288c VA: 0x7598a5a88c
	private Boolean IsBypassedAuto(Uri destination, out Boolean isBypassed) { }
	// RVA: 0x6442e80 VA: 0x7598a5ae80
	private static Boolean AreAllBypassed(IEnumerable`1 proxies, Boolean checkFirstOnly) { }
	// RVA: 0x6443188 VA: 0x7598a5b188
	private static Uri ProxyUri(String proxyName) { }
}
```