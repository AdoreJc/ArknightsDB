# IconListAdapter

**Namespace:** ` `


## Fields

- `DialogSandboxUIPluginIconPair prefab`


## Methods

- `Void set_dataSet(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class IconListAdapter : SimpleLayoutAdapter
{
	public DialogSandboxUIPluginIconPair prefab; // 0x20
	private List`1 <dataSet>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_dataSet; // 0x0
	private static DelegateBridge __Hotfix0_set_dataSet; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge __Hotfix0_RenderView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 dataSet { get; set; }
	public override Int32 count { get; }

	// RVA: 0x1d2bab0 VA: 0x7594343ab0
	public List`1 get_dataSet() { }
	// RVA: 0x1d2b104 VA: 0x7594343104
	public Void set_dataSet(List`1 value) { }
	// RVA: 0x1d2bb18 VA: 0x7594343b18
	public override Int32 get_count() { }
	// RVA: 0x1d2bb9c VA: 0x7594343b9c
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x1d2b094 VA: 0x7594343094
	public Void .ctor() { }
}
```