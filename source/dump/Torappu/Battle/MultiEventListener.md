# MultiEventListener

**Namespace:** `Torappu.Battle`


## Fields

- `Event m_cachedEv`

- `Int32 m_receivedEventCounter`

- `Int32 m_consumedEventCounter`


## Methods

- `Void Bind(Event, Entity)`

- `Void Unbind()`

- `Boolean CheckReceivedNext()`

- `Boolean CheckNotReceivedNext()`

- `Void ConsumeNext()`

- `Void _ClearIfNot()`

- `Void _OnReceiveEvent(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MultiEventListener
{
	private Event m_cachedEv; // 0x10
	private ObjectPtr`1 m_cachedOwner; // 0x18
	private Int32 m_receivedEventCounter; // 0x28
	private Int32 m_consumedEventCounter; // 0x2c


	// RVA: 0x1c51f6c VA: 0x7594269f6c
	public Void Bind(Event ev, Entity owner) { }
	// RVA: 0x1c52228 VA: 0x759426a228
	public Void Unbind() { }
	// RVA: 0x1c5222c VA: 0x759426a22c
	public Boolean CheckReceivedNext() { }
	// RVA: 0x1c5223c VA: 0x759426a23c
	public Boolean CheckNotReceivedNext() { }
	// RVA: 0x1c5224c VA: 0x759426a24c
	public Void ConsumeNext() { }
	// RVA: 0x1c520cc VA: 0x759426a0cc
	private Void _ClearIfNot() { }
	// RVA: 0x1c5225c VA: 0x759426a25c
	private Void _OnReceiveEvent(Object arg) { }
	// RVA: 0x1c5226c VA: 0x759426a26c
	public Void .ctor() { }
}
```