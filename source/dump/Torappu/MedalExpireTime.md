# MedalExpireTime

**Namespace:** `Torappu`


## Fields

- `Int64 start`

- `Int64 end`

- `MedalExpireType type`


## Methods

- `Int64 GetEndTs()`

- `Int64 GetStartTs()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class MedalExpireTime : ITimeValidInfo
{
	public Int64 start; // 0x10
	public Int64 end; // 0x18
	public MedalExpireType type; // 0x20


	// RVA: 0x34a510c VA: 0x7595abd10c
	public Int64 GetEndTs() { }
	// RVA: 0x34a5114 VA: 0x7595abd114
	public Int64 GetStartTs() { }
	// RVA: 0x34a511c VA: 0x7595abd11c
	public virtual Boolean ShouldSerializetype() { }
	// RVA: 0x34a5124 VA: 0x7595abd124
	public Void .ctor() { }
}
```