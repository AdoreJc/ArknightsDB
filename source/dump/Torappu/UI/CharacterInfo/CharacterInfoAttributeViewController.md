# CharacterInfoAttributeViewController

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _maxHp`

- `Text _atk`

- `Text _def`

- `Text _res`

- `Text _reviveTime`

- `Text _cost`

- `Text _blockNum`

- `Text _atkSpeed`

- `Text _textPosition`

- `Text _textTags`

- `Image _professionTab`

- `GameObject _buttonMask`

- `RectTransform _hpRect`

- `RectTransform _attackRect`

- `RectTransform _defRect`

- `RectTransform _reRect`

- `RectTransform _favourBar`

- `Text _favourLvl`

- `CharacterInfoFavourAttributeView _attrView`

- `Transform _attrContainer`

- `Transform _panelPopup`

- `Boolean m_InOut`


## Methods

- `Void OnFavorShow()`

- `Void OnFavorDisable()`

- `Void OnStateChange()`

- `Void RefreshState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoAttributeViewController : DataBinder`1
{
	private Text _maxHp; // 0x20
	private Text _atk; // 0x28
	private Text _def; // 0x30
	private Text _res; // 0x38
	private Text _reviveTime; // 0x40
	private Text _cost; // 0x48
	private Text _blockNum; // 0x50
	private Text _atkSpeed; // 0x58
	private Text _textPosition; // 0x60
	private Text _textTags; // 0x68
	private Image _professionTab; // 0x70
	private Animator[] _animators; // 0x78
	private GameObject _buttonMask; // 0x80
	private RectTransform _hpRect; // 0x88
	private RectTransform _attackRect; // 0x90
	private RectTransform _defRect; // 0x98
	private RectTransform _reRect; // 0xa0
	private RectTransform _favourBar; // 0xa8
	private Text _favourLvl; // 0xb0
	private CharacterInfoFavourAttributeView _attrView; // 0xb8
	private Transform _attrContainer; // 0xc0
	private Transform _panelPopup; // 0xc8
	private List`1 m_attrLists; // 0xd0
	private Boolean m_InOut; // 0xd8
	private const Single BARWIDTH; // 0x0
	private const Single BARHEIGHT; // 0x0
	private const Single WIDTH; // 0x0
	private const Single HEIGHT; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnFavorShow; // 0x8
	private static DelegateBridge __Hotfix0_OnFavorDisable; // 0x10
	private static DelegateBridge __Hotfix0_OnStateChange; // 0x18
	private static DelegateBridge __Hotfix0_RefreshState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d67778 VA: 0x759537f778
	public override Void OnValueChanged(CharInfoGroupProperty property) { }
	// RVA: 0x2d683f8 VA: 0x75953803f8
	public Void OnFavorShow() { }
	// RVA: 0x2d684c0 VA: 0x75953804c0
	public Void OnFavorDisable() { }
	// RVA: 0x2d6855c VA: 0x759538055c
	public Void OnStateChange() { }
	// RVA: 0x2d67278 VA: 0x759537f278
	public Void RefreshState() { }
	// RVA: 0x2d6865c VA: 0x759538065c
	public Void .ctor() { }
}
```