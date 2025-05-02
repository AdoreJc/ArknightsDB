# HeartBeat

**Namespace:** ` `


## Fields

- `UInt32 seq`

- `Int64 time`


## Methods

- `Void <>xLuaBaseProxy_OnWrite(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class HeartBeat : Protocol
{
	public const UInt32 ID; // 0x0
	public UInt32 seq; // 0x14
	public Int64 time; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnWrite; // 0x8


	// RVA: 0x3575bb8 VA: 0x7595b8dbb8
	public Void .ctor() { }
	// RVA: 0x3575c28 VA: 0x7595b8dc28
	protected override Void OnWrite(IStreamWriter to) { }
	// RVA: 0x3575d80 VA: 0x7595b8dd80
	private Void <>xLuaBaseProxy_OnWrite(IStreamWriter P0) { }
}
```