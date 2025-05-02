# RewardPreviewAdapter

**Namespace:** ` `


## Methods

- `Void set_cardModels(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class RewardPreviewAdapter : SimpleLayoutAdapter
{
	private const Int32 MAX_ITEM_COUNT; // 0x0
	private List`1 m_cardModels; // 0x20
	private static DelegateBridge __Hotfix0_get_cardModels; // 0x0
	private static DelegateBridge __Hotfix0_set_cardModels; // 0x8
	private static DelegateBridge __Hotfix0_get_count; // 0x10
	private static DelegateBridge __Hotfix0_RenderView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 cardModels { get; set; }
	public override Int32 count { get; }

	// RVA: 0x33d2b14 VA: 0x75959eab14
	public List`1 get_cardModels() { }
	// RVA: 0x33d237c VA: 0x75959ea37c
	public Void set_cardModels(List`1 value) { }
	// RVA: 0x33d2b7c VA: 0x75959eab7c
	public override Int32 get_count() { }
	// RVA: 0x33d2c18 VA: 0x75959eac18
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x33d2428 VA: 0x75959ea428
	public Void .ctor() { }
}
```