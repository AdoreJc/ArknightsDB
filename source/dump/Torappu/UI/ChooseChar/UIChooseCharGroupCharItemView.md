# UIChooseCharGroupCharItemView

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `Image _imgCharAvatar`

- `Image _imgCharRarity`

- `Image _imgCharProfession`

- `Text _txtCharName`

- `Image _imgPotential`

- `GameObject _panelPotential`

- `GameObject _hotspot`

- `String m_cacheCharId`


## Methods

- `Void set_onClickEvent(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class UIChooseCharGroupCharItemView : CommonChooseCharCardView, IHotfixable
{
	private Image _imgCharAvatar; // 0x18
	private Image _imgCharRarity; // 0x20
	private Image _imgCharProfession; // 0x28
	private Text _txtCharName; // 0x30
	private Image _imgPotential; // 0x38
	private GameObject _panelPotential; // 0x40
	private GameObject _hotspot; // 0x48
	private Action`1 <onClickEvent>k__BackingField; // 0x50
	private String m_cacheCharId; // 0x58
	private Action`1 m_cacheAction; // 0x60
	private static DelegateBridge __Hotfix0_get_onClickEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickEvent; // 0x8
	private static DelegateBridge __Hotfix0_SetClickCallback; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnItemClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onClickEvent { get; set; }

	// RVA: 0x2c41278 VA: 0x7595259278
	private Action`1 get_onClickEvent() { }
	// RVA: 0x2c412e0 VA: 0x75952592e0
	public Void set_onClickEvent(Action`1 value) { }
	// RVA: 0x2c41364 VA: 0x7595259364
	public override Void SetClickCallback(Action`1 action) { }
	// RVA: 0x2c413e8 VA: 0x75952593e8
	public override Void Render(ICommonChooseCharCardViewModel viewModel) { }
	// RVA: 0x2c41880 VA: 0x7595259880
	public override Void OnItemClick() { }
	// RVA: 0x2c41908 VA: 0x7595259908
	public Void .ctor() { }
}
```