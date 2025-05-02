# RequestHandlers

**Namespace:** `Torappu.Multiplayer.Mode`


## Methods

- `Void _SetHandler(RequestType, RequestHandler)`

- `Void SetHandler(RequestType, Func`2)`

- `Void SetHandler(RequestType, Func`1)`

- `Boolean Do(RequestType, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer.Mode
public class RequestHandlers
{
	private readonly RequestHandler[] m_handlers; // 0x10


	// RVA: 0x35a5194 VA: 0x7595bbd194
	public Void .ctor(Int32 maxcnt) { }
	// RVA: 0x35a5204 VA: 0x7595bbd204
	private Void _SetHandler(RequestType req, RequestHandler handler) { }
	// RVA: 0x VA: 0x0
	public Void SetHandler(RequestType req, Func`2 handler) { }
	// RVA: 0x35a5288 VA: 0x7595bbd288
	public Void SetHandler(RequestType req, Func`1 handler) { }
	// RVA: 0x35a5498 VA: 0x7595bbd498
	public Boolean Do(RequestType req, Object param) { }
}
```