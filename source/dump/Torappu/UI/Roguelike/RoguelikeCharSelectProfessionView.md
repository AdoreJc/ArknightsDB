# RoguelikeCharSelectProfessionView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _subProfName`

- `UICommentedText _subProfDetailBasic`

- `UICommentedText _subProfDetailAdditive`

- `Image _subProfImg`

- `RoguelikeCharSelectUniEquipView _objEquip`

- `GameObject _objNonEquip`


## Methods

- `Void RenderView(RoguelikeCharCardViewModel)`

- `Void _LoadUniqEquip(RoguelikeCharCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectProfessionView : MonoBehaviour, IHotfixable
{
	private Text _subProfName; // 0x18
	private UICommentedText _subProfDetailBasic; // 0x20
	private UICommentedText _subProfDetailAdditive; // 0x28
	private Image _subProfImg; // 0x30
	private RoguelikeCharSelectUniEquipView _objEquip; // 0x38
	private GameObject _objNonEquip; // 0x40
	private static DelegateBridge __Hotfix0_RenderView; // 0x0
	private static DelegateBridge __Hotfix0__LoadUniqEquip; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2acdc04 VA: 0x75950e5c04
	public Void RenderView(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2acddec VA: 0x75950e5dec
	private Void _LoadUniqEquip(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2ace0f4 VA: 0x75950e60f4
	public Void .ctor() { }
}
```