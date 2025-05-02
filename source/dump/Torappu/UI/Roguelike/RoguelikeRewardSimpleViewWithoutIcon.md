# RoguelikeRewardSimpleViewWithoutIcon

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _itemBg`

- `Text _itemName`

- `Text _itemCount`

- `RoguelikeRewardShowType _showType`

- `GameObject _objReceiptBtn`

- `UIIntEvent <onClickEvent>k__BackingField`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardSimpleViewWithoutIcon : RoguelikeRewardItem
{
	private Image _itemBg; // 0x48
	private Text _itemName; // 0x50
	private Text _itemCount; // 0x58
	private RoguelikeRewardShowType _showType; // 0x60
	private GameObject _objReceiptBtn; // 0x68
	private UIIntEvent <onClickEvent>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2aa2464 VA: 0x75950ba464
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2aa24cc VA: 0x75950ba4cc
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2aa2550 VA: 0x75950ba550
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2aa25b8 VA: 0x75950ba5b8
	public override Void OnClick() { }
	// RVA: 0x2aa2680 VA: 0x75950ba680
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2aa282c VA: 0x75950ba82c
	public Void .ctor() { }
}
```