# RoguelikeRewardEntryPopItemView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _txtPop`

- `Image _imgBg`

- `Image _imgPopIcon`


## Methods

- `Void Render(RoguelikeRewardsPopInfo)`

- `Void _RenderStyle(RoguelikeRewardEntryPopItemStyle)`

- `RoguelikeRewardEntryPopItemStyle _GetPopStyle(ROGUELIKE_REWARDS_LEVEL_UP_POP_TYPE)`

- `String _GetPopCountTxt(ROGUELIKE_REWARDS_LEVEL_UP_POP_TYPE, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardEntryPopItemView : MonoBehaviour, IHotfixable
{
	private Text _txtPop; // 0x18
	private Image _imgBg; // 0x20
	private Image _imgPopIcon; // 0x28
	private List`1 _styleList; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderStyle; // 0x8
	private static DelegateBridge __Hotfix0__GetPopStyle; // 0x10
	private static DelegateBridge __Hotfix0__GetPopCountTxt; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2a96050 VA: 0x75950ae050
	public Void Render(RoguelikeRewardsPopInfo popInfo) { }
	// RVA: 0x2a962e4 VA: 0x75950ae2e4
	private Void _RenderStyle(RoguelikeRewardEntryPopItemStyle style) { }
	// RVA: 0x2a96138 VA: 0x75950ae138
	private RoguelikeRewardEntryPopItemStyle _GetPopStyle(ROGUELIKE_REWARDS_LEVEL_UP_POP_TYPE type) { }
	// RVA: 0x2a96434 VA: 0x75950ae434
	private String _GetPopCountTxt(ROGUELIKE_REWARDS_LEVEL_UP_POP_TYPE type, Int32 count) { }
	// RVA: 0x2a965b8 VA: 0x75950ae5b8
	public Void .ctor() { }
}
```