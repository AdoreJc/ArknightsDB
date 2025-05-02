# UICommonEquipTypeIcon

**Namespace:** `Torappu.UI`


## Fields

- `Image _icon1`

- `Image _icon2`

- `Image _shiningImg`

- `GameObject _panelSingleType`

- `GameObject _panelMultiType`

- `Text _uniEquipSingleTypeDesc`

- `Text _uniEquipMultiTypeDesc`

- `Image _uniEquipMultiTypeDescImg`

- `AnimationWrapper _animHaveWrapper`

- `GameObject _backImg`

- `UIColorGraphic _colorGraphic`

- `GameObject _haveIconPart`

- `GameObject _noIconPart`

- `String ANIM_HAVE_PARAM`


## Properties

- `UIColorGraphic colorGraphic`


## Methods

- `UIColorGraphic get_colorGraphic()`

- `Void Render(UniEquipData, Boolean, Boolean, Boolean, Boolean)`

- `Void PlayAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICommonEquipTypeIcon : MonoBehaviour, IHotfixable
{
	private Image _icon1; // 0x18
	private Image _icon2; // 0x20
	private Image _shiningImg; // 0x28
	private GameObject _panelSingleType; // 0x30
	private GameObject _panelMultiType; // 0x38
	private Text _uniEquipSingleTypeDesc; // 0x40
	private Text _uniEquipMultiTypeDesc; // 0x48
	private Image _uniEquipMultiTypeDescImg; // 0x50
	private AnimationWrapper _animHaveWrapper; // 0x58
	private GameObject _backImg; // 0x60
	private UIColorGraphic _colorGraphic; // 0x68
	private GameObject _haveIconPart; // 0x70
	private GameObject _noIconPart; // 0x78
	private String ANIM_HAVE_PARAM; // 0x80
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_PlayAnim; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public UIColorGraphic colorGraphic { get; }

	// RVA: 0x229043c VA: 0x75948a843c
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x22904a4 VA: 0x75948a84a4
	public Void Render(UniEquipData data, Boolean haveFlag, Boolean showDesc, Boolean showShining, Boolean showBack) { }
	// RVA: 0x22906ec VA: 0x75948a86ec
	public Void PlayAnim() { }
	// RVA: 0x2290780 VA: 0x75948a8780
	public Void .ctor() { }
}
```