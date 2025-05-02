# RL04ShopDetailExtraInfoPlugin

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Color _colorLimitWeightWarning`

- `Color _colorOverWeightWarning`

- `String m_cachedTopicId`

- `Int32 m_cachedLimitThreshold`

- `Int32 m_cachedOverThreshold`


## Methods

- `Void _LoadGameDataIfNeed(String)`

- `RoguelikeShopDetailExtraInfo _ProcessAsFragment(RoguelikeGoodsViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ShopDetailExtraInfoPlugin : RoguelikeShopDetailExtraInfoPlugin
{
	private Color _colorLimitWeightWarning; // 0x18
	private Color _colorOverWeightWarning; // 0x28
	private String m_cachedTopicId; // 0x38
	private Int32 m_cachedLimitThreshold; // 0x40
	private Int32 m_cachedOverThreshold; // 0x44
	private static DelegateBridge __Hotfix0_GetExtraInfo; // 0x0
	private static DelegateBridge __Hotfix0__LoadGameDataIfNeed; // 0x8
	private static DelegateBridge __Hotfix0__ProcessAsFragment; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2b53d40 VA: 0x759516bd40
	public override RoguelikeShopDetailExtraInfo GetExtraInfo(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2b53e2c VA: 0x759516be2c
	private Void _LoadGameDataIfNeed(String topicId) { }
	// RVA: 0x2b53f3c VA: 0x759516bf3c
	private RoguelikeShopDetailExtraInfo _ProcessAsFragment(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2b541b0 VA: 0x759516c1b0
	public Void .ctor() { }
}
```