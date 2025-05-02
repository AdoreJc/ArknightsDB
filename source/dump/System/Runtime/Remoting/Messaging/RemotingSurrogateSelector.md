# RemotingSurrogateSelector

**Namespace:** `System.Runtime.Remoting.Messaging`


## Fields

- `ISurrogateSelector _next`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Runtime.Remoting.Messaging
public class RemotingSurrogateSelector : ISurrogateSelector
{
	private static Type s_cachedTypeObjRef; // 0x0
	private static ObjRefSurrogate _objRefSurrogate; // 0x8
	private static RemotingSurrogate _objRemotingSurrogate; // 0x10
	private ISurrogateSelector _next; // 0x10


	// RVA: 0x5f9cbbc VA: 0x75985b4bbc
	public Void .ctor() { }
	// RVA: 0x5fab5c4 VA: 0x75985c35c4
	public virtual ISerializationSurrogate GetSurrogate(Type type, StreamingContext context, out ISurrogateSelector ssout) { }
	// RVA: 0x5fab77c VA: 0x75985c377c
	private static Void .cctor() { }
}
```