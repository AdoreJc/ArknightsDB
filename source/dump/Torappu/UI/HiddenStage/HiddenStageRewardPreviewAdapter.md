# HiddenStageRewardPreviewAdapter

**Namespace:** `Torappu.UI.HiddenStage`


## Methods

- `Void set_cardModels(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HiddenStage
public class HiddenStageRewardPreviewAdapter : SimpleLayoutAdapter
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

	// RVA: 0x285bde8 VA: 0x7594e73de8
	public List`1 get_cardModels() { }
	// RVA: 0x285b17c VA: 0x7594e7317c
	public Void set_cardModels(List`1 value) { }
	// RVA: 0x285be50 VA: 0x7594e73e50
	public override Int32 get_count() { }
	// RVA: 0x285beec VA: 0x7594e73eec
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x285a8a4 VA: 0x7594e728a4
	public Void .ctor() { }
}
```