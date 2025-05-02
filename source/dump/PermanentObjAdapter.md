# PermanentObjAdapter

**Namespace:** ` `


## Methods

- `Void set_dataSet(List`1)`

- `Void set_onObjClicked(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PermanentObjAdapter : SimpleLayoutAdapter
{
	private List`1 <dataSet>k__BackingField; // 0x20
	private Action`1 <onObjClicked>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_onObjClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onObjClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_count; // 0x20
	private static DelegateBridge __Hotfix0_RenderView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public List`1 dataSet { get; set; }
	public Action`1 onObjClicked { get; set; }
	public override Int32 count { get; }

	// RVA: 0x2dd0d00 VA: 0x75953e8d00
	public List`1 get_dataSet() { }
	// RVA: 0x2dd092c VA: 0x75953e892c
	public Void set_dataSet(List`1 value) { }
	// RVA: 0x2dd0d68 VA: 0x75953e8d68
	public Action`1 get_onObjClicked() { }
	// RVA: 0x2dd0a34 VA: 0x75953e8a34
	public Void set_onObjClicked(Action`1 value) { }
	// RVA: 0x2dd0dd0 VA: 0x75953e8dd0
	public override Int32 get_count() { }
	// RVA: 0x2dd0e54 VA: 0x75953e8e54
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2dd0c20 VA: 0x75953e8c20
	public Void .ctor() { }
}
```