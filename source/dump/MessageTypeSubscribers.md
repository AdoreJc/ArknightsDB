# MessageTypeSubscribers

**Namespace:** ` `


## Fields

- `String m_messageTypeId`

- `Int32 subscriberCount`

- `MessageEvent messageCallback`


## Properties

- `Guid MessageTypeId`


## Methods

- `Guid get_MessageTypeId()`

- `Void set_MessageTypeId(Guid)`


## Dump
```C#
// Dll : UnityEngine.CoreModule.dll
// Namespace : 
public class MessageTypeSubscribers
{
	private String m_messageTypeId; // 0x10
	public Int32 subscriberCount; // 0x18
	public MessageEvent messageCallback; // 0x20

	public Guid MessageTypeId { get; set; }

	// RVA: 0x689c4bc VA: 0x7598eb44bc
	public Guid get_MessageTypeId() { }
	// RVA: 0x689c5c0 VA: 0x7598eb45c0
	public Void set_MessageTypeId(Guid value) { }
	// RVA: 0x689c54c VA: 0x7598eb454c
	public Void .ctor() { }
}
```