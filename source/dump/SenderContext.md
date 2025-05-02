# SenderContext

**Namespace:** ` `


## Fields

- `IRequestSendHandler queryRequestHandler`

- `IRequestSendHandler cancelRequestHandler`

- `IRequestSendHandler initRequestHandler`

- `IRequestWaitStrategy waitStrategy`

- `ICoroutineHost coroutineHost`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SenderContext
{
	public IRequestSendHandler queryRequestHandler; // 0x10
	public IRequestSendHandler cancelRequestHandler; // 0x18
	public IRequestSendHandler initRequestHandler; // 0x20
	public IRequestWaitStrategy waitStrategy; // 0x28
	public ICoroutineHost coroutineHost; // 0x30
	public Action`1 onTick; // 0x38


	// RVA: 0x22262b0 VA: 0x759483e2b0
	public Void .ctor() { }
}
```