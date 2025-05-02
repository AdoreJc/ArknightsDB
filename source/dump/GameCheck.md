# GameCheck

**Namespace:** ` `


## Fields

- `Int32 seq`

- `UInt32 checksum`

- `Int32 hp`


## Methods

- `Void <>xLuaBaseProxy_OnWrite(IStreamWriter)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameCheck : Protocol
{
	public const UInt32 ID; // 0x0
	public Int32 seq; // 0x14
	public UInt32 checksum; // 0x18
	public Int32 hp; // 0x1c
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnWrite; // 0x8


	// RVA: 0x3599e14 VA: 0x7595bb1e14
	public Void .ctor() { }
	// RVA: 0x3599e88 VA: 0x7595bb1e88
	protected override Void OnWrite(IStreamWriter to) { }
	// RVA: 0x359a044 VA: 0x7595bb2044
	private Void <>xLuaBaseProxy_OnWrite(IStreamWriter P0) { }
}
```