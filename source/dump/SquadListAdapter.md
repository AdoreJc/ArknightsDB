# SquadListAdapter

**Namespace:** ` `


## Fields

- `ClimbTowerSquadGroupViewModel m_squadViewModel`

- `Int32 m_displayCount`


## Methods

- `Void set_onSlotClick(Action`1)`

- `Void set_onGetAssistClick(Action`1)`

- `Void set_onClearAssistClick(Action`1)`

- `Void SetData(ClimbTowerSquadGroupViewModel, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SquadListAdapter : SimpleLayoutAdapter
{
	private ClimbTowerSquadGroupViewModel m_squadViewModel; // 0x20
	private Int32 m_displayCount; // 0x28
	private Action`1 <onSlotClick>k__BackingField; // 0x30
	private Action`1 <onGetAssistClick>k__BackingField; // 0x38
	private Action`1 <onClearAssistClick>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_onSlotClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onSlotClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onGetAssistClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onGetAssistClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onClearAssistClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onClearAssistClick; // 0x28
	private static DelegateBridge __Hotfix0_SetData; // 0x30
	private static DelegateBridge __Hotfix0_get_count; // 0x38
	private static DelegateBridge __Hotfix0_RenderView; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 onSlotClick { get; set; }
	private Action`1 onGetAssistClick { get; set; }
	private Action`1 onClearAssistClick { get; set; }
	public override Int32 count { get; }

	// RVA: 0x2cb7df0 VA: 0x75952cfdf0
	private Action`1 get_onSlotClick() { }
	// RVA: 0x2cb79c8 VA: 0x75952cf9c8
	public Void set_onSlotClick(Action`1 value) { }
	// RVA: 0x2cb7e58 VA: 0x75952cfe58
	private Action`1 get_onGetAssistClick() { }
	// RVA: 0x2cb7ad0 VA: 0x75952cfad0
	public Void set_onGetAssistClick(Action`1 value) { }
	// RVA: 0x2cb7ec0 VA: 0x75952cfec0
	private Action`1 get_onClearAssistClick() { }
	// RVA: 0x2cb7a4c VA: 0x75952cfa4c
	public Void set_onClearAssistClick(Action`1 value) { }
	// RVA: 0x2cb7934 VA: 0x75952cf934
	public Void SetData(ClimbTowerSquadGroupViewModel squadViewModel, Int32 displayCount) { }
	// RVA: 0x2cb7f28 VA: 0x75952cff28
	public override Int32 get_count() { }
	// RVA: 0x2cb7fbc VA: 0x75952cffbc
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2cb7ce8 VA: 0x75952cfce8
	public Void .ctor() { }
}
```