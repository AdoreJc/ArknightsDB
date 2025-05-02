# RL03ShopDetailExtraInfoPlugin

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `Color _colorTotemTips`

- `Color _colorVisionTips`


## Methods

- `Boolean _CheckIfPlayerVisionIsMax(RoguelikeGameItemType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03ShopDetailExtraInfoPlugin : RoguelikeShopDetailExtraInfoPlugin
{
	private Color _colorTotemTips; // 0x18
	private Color _colorVisionTips; // 0x28
	private List`1 m_cachedTotemModels; // 0x38
	private static DelegateBridge __Hotfix0_GetExtraInfo; // 0x0
	private static DelegateBridge __Hotfix0__CheckIfPlayerVisionIsMax; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ba4574 VA: 0x75951bc574
	public override RoguelikeShopDetailExtraInfo GetExtraInfo(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ba4764 VA: 0x75951bc764
	private Boolean _CheckIfPlayerVisionIsMax(RoguelikeGameItemType itemType) { }
	// RVA: 0x2ba4858 VA: 0x75951bc858
	public Void .ctor() { }
}
```