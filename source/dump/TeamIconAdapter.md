# TeamIconAdapter

**Namespace:** ` `


## Fields

- `NameCardV2CollectModuleView m_closure`

- `Color <collectedIconColor>k__BackingField`


## Properties

- `Color collectedIconColor`


## Methods

- `Void set_collectedIconColor(Color)`

- `Color get_collectedIconColor()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class TeamIconAdapter : SimpleLayoutAdapter
{
	private NameCardV2CollectModuleView m_closure; // 0x20
	private Color <collectedIconColor>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_set_collectedIconColor; // 0x0
	private static DelegateBridge __Hotfix0_get_collectedIconColor; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_get_count; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	private Color collectedIconColor { get; set; }
	public override Int32 count { get; }

	// RVA: 0x28e2eb8 VA: 0x7594efaeb8
	public Void set_collectedIconColor(Color value) { }
	// RVA: 0x28e34bc VA: 0x7594efb4bc
	private Color get_collectedIconColor() { }
	// RVA: 0x28e2fc4 VA: 0x7594efafc4
	public Void .ctor(NameCardV2CollectModuleView closure) { }
	// RVA: 0x28e3524 VA: 0x7594efb524
	public override Int32 get_count() { }
	// RVA: 0x28e35b0 VA: 0x7594efb5b0
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```