# RecruitUpCharSlotSelectCard

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `GameObject _panelNoChar`

- `GameObject _panelChar`

- `UIAtlasImage _imgChar`

- `Image _imgRarity`

- `Image _imgProfession`

- `Text _txtName`

- `Int32 m_index`

- `String m_charId`


## Methods

- `Void set_onCardClick(Action`1)`

- `Void Render(Int32, String)`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitUpCharSlotSelectCard : MonoBehaviour, IHotfixable
{
	private GameObject _panelNoChar; // 0x18
	private GameObject _panelChar; // 0x20
	private UIAtlasImage _imgChar; // 0x28
	private Image _imgRarity; // 0x30
	private Image _imgProfession; // 0x38
	private Text _txtName; // 0x40
	private Action`1 <onCardClick>k__BackingField; // 0x48
	private Int32 m_index; // 0x50
	private String m_charId; // 0x58
	private static DelegateBridge __Hotfix0_get_onCardClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onCardClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onCardClick { get; set; }

	// RVA: 0x26fe948 VA: 0x7594d16948
	private Action`1 get_onCardClick() { }
	// RVA: 0x26fe9b0 VA: 0x7594d169b0
	public Void set_onCardClick(Action`1 value) { }
	// RVA: 0x26fea34 VA: 0x7594d16a34
	public Void Render(Int32 index, String charId) { }
	// RVA: 0x26fecb8 VA: 0x7594d16cb8
	public Void EventOnClick() { }
	// RVA: 0x26fed58 VA: 0x7594d16d58
	public Void .ctor() { }
}
```