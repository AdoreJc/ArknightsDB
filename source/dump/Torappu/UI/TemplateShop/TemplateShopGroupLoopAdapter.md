# TemplateShopGroupLoopAdapter

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `TemplateShopResHolder resHolder`

- `TemplateShopLoopGroupView groupView`

- `Int32 constraintCount`

- `AsyncGameObjectLoader loader`

- `Vector2 cellSize`

- `Vector2 spaceing`


## Methods

- `Void RebuildList()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopGroupLoopAdapter : UIRecycleLayoutAdapter
{
	public List`1 viewModelList; // 0x18
	public TemplateShopResHolder resHolder; // 0x20
	public TemplateShopLoopGroupView groupView; // 0x28
	public Int32 constraintCount; // 0x30
	public AsyncGameObjectLoader loader; // 0x38
	public Vector2 cellSize; // 0x40
	public Vector2 spaceing; // 0x48
	private static DelegateBridge __Hotfix0_RebuildList; // 0x0
	private static DelegateBridge __Hotfix0_GenerateViewsForRebuild; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x235d3c8 VA: 0x75949753c8
	public Void RebuildList() { }
	// RVA: 0x235d594 VA: 0x7594975594
	public override IList`1 GenerateViewsForRebuild() { }
	// RVA: 0x235d240 VA: 0x7594975240
	public Void .ctor() { }
}
```