# RequestHandlerRegistry

**Namespace:** `Torappu.SocketNetwork.ServerBase`


## Methods

- `Void _SetHandler(RequestEnum, IHandler)`

- `Void SetHandler(RequestEnum, Func`2)`

- `Void SetHandler(RequestEnum, Func`1)`

- `Boolean Do(RequestEnum, Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.SocketNetwork.ServerBase
public class RequestHandlerRegistry`1
{
	private Dictionary`2 m_handlers; // 0x0


	// RVA: 0x VA: 0x0
	private Void _SetHandler(RequestEnum req, IHandler handler) { }
	// RVA: 0x VA: 0x0
	public Void SetHandler(RequestEnum req, Func`2 handler) { }
	// RVA: 0x VA: 0x0
	public Void SetHandler(RequestEnum req, Func`1 handler) { }
	// RVA: 0x VA: 0x0
	public Boolean Do(RequestEnum req, Object param) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```