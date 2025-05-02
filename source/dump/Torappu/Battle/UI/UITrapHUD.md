# UITrapHUD

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Transform _costPanel`

- `Text _costLabel`


## Methods

- `Void _SetCostPanel(Unit)`

- `Void <>xLuaBaseProxy_SetData(Unit)`

- `Void <>xLuaBaseProxy_Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UITrapHUD : UIUnitHUD
{
	private Transform _costPanel; // 0xf0
	private Text _costLabel; // 0xf8
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__SetCostPanel; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2083168 VA: 0x759469b168
	protected override Void SetData(Unit owner) { }
	// RVA: 0x2083cf8 VA: 0x759469bcf8
	protected override Void Update() { }
	// RVA: 0x2083950 VA: 0x759469b950
	private Void _SetCostPanel(Unit owner) { }
	// RVA: 0x2084180 VA: 0x759469c180
	public Void .ctor() { }
	// RVA: 0x208425c VA: 0x759469c25c
	private Void <>xLuaBaseProxy_SetData(Unit P0) { }
	// RVA: 0x2084260 VA: 0x759469c260
	private Void <>xLuaBaseProxy_Update() { }
}
```