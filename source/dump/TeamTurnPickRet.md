# TeamTurnPickRet

**Namespace:** ` `


## Fields

- `Int32 <charInstId>k__BackingField`


## Properties

- `Int32 charInstId`


## Methods

- `Int32 get_charInstId()`

- `Void set_charInstId(Int32)`

- `Void <>xLuaBaseProxy_OnRead(IStreamReader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class TeamTurnPickRet : Protocol
{
	public const UInt32 ID; // 0x0
	private Int32 <charInstId>k__BackingField; // 0x14
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_charInstId; // 0x8
	private static DelegateBridge __Hotfix0_set_charInstId; // 0x10
	private static DelegateBridge __Hotfix0_OnRead; // 0x18

	public Int32 charInstId { get; set; }

	// RVA: 0x359ded8 VA: 0x7595bb5ed8
	public Void .ctor() { }
	// RVA: 0x359df4c VA: 0x7595bb5f4c
	public Int32 get_charInstId() { }
	// RVA: 0x359dfb4 VA: 0x7595bb5fb4
	private Void set_charInstId(Int32 value) { }
	// RVA: 0x359e030 VA: 0x7595bb6030
	protected override Void OnRead(IStreamReader from) { }
	// RVA: 0x359e128 VA: 0x7595bb6128
	private Void <>xLuaBaseProxy_OnRead(IStreamReader P0) { }
}
```