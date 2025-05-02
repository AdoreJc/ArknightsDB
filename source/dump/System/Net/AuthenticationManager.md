# AuthenticationManager

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class AuthenticationManager
{
	private static ArrayList modules; // 0x0
	private static Object locker; // 0x8
	private static ICredentialPolicy credential_policy; // 0x10


	// RVA: 0x6445004 VA: 0x7598a5d004
	private static Void EnsureModules() { }
	// RVA: 0x64452b4 VA: 0x7598a5d2b4
	public static Authorization Authenticate(String challenge, WebRequest request, ICredentials credentials) { }
	// RVA: 0x64453c0 VA: 0x7598a5d3c0
	private static Authorization DoAuthenticate(String challenge, WebRequest request, ICredentials credentials) { }
	// RVA: 0x64458b4 VA: 0x7598a5d8b4
	public static Authorization PreAuthenticate(WebRequest request, ICredentials credentials) { }
	// RVA: 0x6445df8 VA: 0x7598a5ddf8
	private static Void .cctor() { }
}
```