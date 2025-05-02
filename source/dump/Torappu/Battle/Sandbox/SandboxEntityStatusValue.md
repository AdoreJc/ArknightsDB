# SandboxEntityStatusValue

**Namespace:** `Torappu.Battle.Sandbox`


## Fields

- `Boolean isDead`

- `Int32 hpRatio`

- `Int32 extraParam`


## Properties

- `Int32 totalNotCollected`

- `Int32 maxStockCount`

- `Int32 droppedNotCollected`

- `Single statusHpRatio`


## Methods

- `Int32 get_totalNotCollected()`

- `Void set_totalNotCollected(Int32)`

- `Int32 get_maxStockCount()`

- `Void set_maxStockCount(Int32)`

- `Int32 get_droppedNotCollected()`

- `Void set_droppedNotCollected(Int32)`

- `Void set_statusHpRatio(Single)`

- `Single get_statusHpRatio()`

- `String <>xLuaBaseProxy_ToString()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Sandbox
public class SandboxEntityStatusValue : IHotfixable
{
	public Boolean isDead; // 0x10
	public Int32 hpRatio; // 0x14
	public List`1 count; // 0x18
	public Int32 extraParam; // 0x20
	private static DelegateBridge __Hotfix0_get_totalNotCollected; // 0x0
	private static DelegateBridge __Hotfix0_set_totalNotCollected; // 0x8
	private static DelegateBridge __Hotfix0_get_maxStockCount; // 0x10
	private static DelegateBridge __Hotfix0_set_maxStockCount; // 0x18
	private static DelegateBridge __Hotfix0_get_droppedNotCollected; // 0x20
	private static DelegateBridge __Hotfix0_set_droppedNotCollected; // 0x28
	private static DelegateBridge __Hotfix0_set_statusHpRatio; // 0x30
	private static DelegateBridge __Hotfix0_get_statusHpRatio; // 0x38
	private static DelegateBridge __Hotfix0_ToString; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Int32 totalNotCollected { get; set; }
	public Int32 maxStockCount { get; set; }
	public Int32 droppedNotCollected { get; set; }
	public Single statusHpRatio { get; set; }

	// RVA: 0x1df92cc VA: 0x75944112cc
	public Int32 get_totalNotCollected() { }
	// RVA: 0x1df9390 VA: 0x7594411390
	public Void set_totalNotCollected(Int32 value) { }
	// RVA: 0x1df955c VA: 0x759441155c
	public Int32 get_maxStockCount() { }
	// RVA: 0x1df9620 VA: 0x7594411620
	public Void set_maxStockCount(Int32 value) { }
	// RVA: 0x1df97ec VA: 0x75944117ec
	public Int32 get_droppedNotCollected() { }
	// RVA: 0x1df9854 VA: 0x7594411854
	public Void set_droppedNotCollected(Int32 value) { }
	// RVA: 0x1df98d0 VA: 0x75944118d0
	public Void set_statusHpRatio(Single value) { }
	// RVA: 0x1df2da8 VA: 0x759440ada8
	public Single get_statusHpRatio() { }
	// RVA: 0x1df99bc VA: 0x75944119bc
	public override String ToString() { }
	// RVA: 0x1df9100 VA: 0x7594411100
	public Void .ctor() { }
	// RVA: 0x1df9cdc VA: 0x7594411cdc
	private String <>xLuaBaseProxy_ToString() { }
}
```