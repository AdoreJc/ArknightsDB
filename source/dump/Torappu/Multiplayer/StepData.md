# StepData

**Namespace:** `Torappu.Multiplayer`


## Fields

- `UInt32 index`

- `UInt32 duration`

- `Int32 checkSeq`

- `Byte pause`


## Methods

- `Void ReadFrom(IStreamReader)`

- `Void OnAllocate()`

- `Void OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Multiplayer
public class StepData : IReusable
{
	public UInt32 index; // 0x10
	public UInt32 duration; // 0x14
	public List`1 oprts; // 0x18
	public Int32 checkSeq; // 0x20
	public Byte pause; // 0x24


	// RVA: 0x358c10c VA: 0x7595ba410c
	public Void .ctor() { }
	// RVA: 0x358c13c VA: 0x7595ba413c
	public Void ReadFrom(IStreamReader from) { }
	// RVA: 0x358c918 VA: 0x7595ba4918
	public Void OnAllocate() { }
	// RVA: 0x358c91c VA: 0x7595ba491c
	public Void OnRecycle() { }
}
```