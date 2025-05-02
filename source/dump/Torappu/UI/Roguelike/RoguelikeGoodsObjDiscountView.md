# RoguelikeGoodsObjDiscountView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _originPrice`

- `Text _currentPrice`

- `GameObject _recyclePanel`


## Methods

- `Boolean _HasDiscountPrice(RoguelikeGoodsViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeGoodsObjDiscountView : RoguelikeGoodsObjPlugin
{
	private Text _originPrice; // 0x18
	private Text _currentPrice; // 0x20
	private GameObject _recyclePanel; // 0x28
	private static DelegateBridge __Hotfix0_get_pluginType; // 0x0
	private static DelegateBridge __Hotfix0_NeedShowPlugin; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__HasDiscountPrice; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override RoguelikeShopGoodPluginType pluginType { get; }

	// RVA: 0x2ae47fc VA: 0x75950fc7fc
	public override RoguelikeShopGoodPluginType get_pluginType() { }
	// RVA: 0x2ae4864 VA: 0x75950fc864
	public override Boolean NeedShowPlugin(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae4974 VA: 0x75950fc974
	public override Void Render(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae48e4 VA: 0x75950fc8e4
	private Boolean _HasDiscountPrice(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae4a8c VA: 0x75950fca8c
	public Void .ctor() { }
}
```