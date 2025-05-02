# RoguelikeShopDetailExtraInfoView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _panelExtraInfo`

- `Text _textExtraInfo`

- `Color _colorRecruitHint`

- `Color _colorTrapHint`

- `Color _colorEffectiveHint`

- `RoguelikeShopDetailExtraInfo m_info`

- `RoguelikeShopDetailExtraInfoPlugin m_infoPlugin`


## Methods

- `Void Render(RoguelikeGoodsViewModel)`

- `Void InjectPlugin(RoguelikeShopDetailExtraInfoPlugin)`

- `RoguelikeShopDetailExtraInfo _GetTipsInfo(RoguelikeGoodsViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeShopDetailExtraInfoView : MonoBehaviour, IHotfixable
{
	private RectTransform _panelExtraInfo; // 0x18
	private Text _textExtraInfo; // 0x20
	private Color _colorRecruitHint; // 0x28
	private Color _colorTrapHint; // 0x38
	private Color _colorEffectiveHint; // 0x48
	private RoguelikeShopDetailExtraInfo m_info; // 0x58
	private RoguelikeShopDetailExtraInfoPlugin m_infoPlugin; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_InjectPlugin; // 0x8
	private static DelegateBridge __Hotfix0__GetTipsInfo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2ae7c64 VA: 0x75950ffc64
	public Void Render(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae80c4 VA: 0x75951000c4
	public Void InjectPlugin(RoguelikeShopDetailExtraInfoPlugin plugin) { }
	// RVA: 0x2ae7df8 VA: 0x75950ffdf8
	private RoguelikeShopDetailExtraInfo _GetTipsInfo(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ae8148 VA: 0x7595100148
	public Void .ctor() { }
}
```