# RoguelikeRewardRelicSelectView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIIntEvent <onClickEvent>k__BackingField`

- `Image _selectBg`

- `Text _description`

- `GameObject _objReceiptBtn`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardRelicSelectView : RoguelikeRewardItem
{
	private UIIntEvent <onClickEvent>k__BackingField; // 0x48
	private Image _selectBg; // 0x50
	private Text _description; // 0x58
	private GameObject _objReceiptBtn; // 0x60
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_showType; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override UIIntEvent onClickEvent { get; set; }
	public override RoguelikeRewardShowType showType { get; }

	// RVA: 0x2a9fd90 VA: 0x75950b7d90
	protected override UIIntEvent get_onClickEvent() { }
	// RVA: 0x2a9fdf8 VA: 0x75950b7df8
	public override Void set_onClickEvent(UIIntEvent value) { }
	// RVA: 0x2a9fe7c VA: 0x75950b7e7c
	public override RoguelikeRewardShowType get_showType() { }
	// RVA: 0x2a9fee4 VA: 0x75950b7ee4
	public override Void OnClick() { }
	// RVA: 0x2a9ffac VA: 0x75950b7fac
	public override Void Render(RoguelikeRewardItemViewModel viewModel, String topicId) { }
	// RVA: 0x2aa021c VA: 0x75950b821c
	public Void .ctor() { }
}
```