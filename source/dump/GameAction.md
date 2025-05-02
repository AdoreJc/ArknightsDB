# GameAction

**Namespace:** ` `


## Methods

- `Void <>xLuaBaseProxy_OnWrite(IStreamWriter)`

- `Void <>xLuaBaseProxy_OnRecycle()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class GameAction : Protocol
{
	public const UInt32 ID; // 0x0
	public List`1 list; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnWrite; // 0x8
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x10


	// RVA: 0x3599938 VA: 0x7595bb1938
	public Void .ctor() { }
	// RVA: 0x3599a00 VA: 0x7595bb1a00
	protected override Void OnWrite(IStreamWriter to) { }
	// RVA: 0x3599b5c VA: 0x7595bb1b5c
	protected override Void OnRecycle() { }
	// RVA: 0x3599c04 VA: 0x7595bb1c04
	private Void <>xLuaBaseProxy_OnWrite(IStreamWriter P0) { }
	// RVA: 0x3599c0c VA: 0x7595bb1c0c
	private Void <>xLuaBaseProxy_OnRecycle() { }
}
```