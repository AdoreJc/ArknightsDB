# PlayerAvatarGroupListAdapter

**Namespace:** ` `


## Fields

- `UIPlayerAvatarEvent clickEvent`

- `String pageName`


## Methods

- `Void set_viewModelList(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PlayerAvatarGroupListAdapter : SimpleLayoutAdapter, IHotfixable
{
	private List`1 <viewModelList>k__BackingField; // 0x20
	public UIPlayerAvatarEvent clickEvent; // 0x28
	public String pageName; // 0x30
	private static DelegateBridge __Hotfix0_get_viewModelList; // 0x0
	private static DelegateBridge __Hotfix0_set_viewModelList; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge __Hotfix0_RenderView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 viewModelList { get; set; }
	public override Int32 count { get; }

	// RVA: 0x2725ddc VA: 0x7594d3dddc
	public List`1 get_viewModelList() { }
	// RVA: 0x2725ce8 VA: 0x7594d3dce8
	public Void set_viewModelList(List`1 value) { }
	// RVA: 0x2725e44 VA: 0x7594d3de44
	public override Int32 get_count() { }
	// RVA: 0x2725ec8 VA: 0x7594d3dec8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x2725c78 VA: 0x7594d3dc78
	public Void .ctor() { }
}
```