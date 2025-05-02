# BuildingBuffDescView

**Namespace:** `Torappu.Building.UI`


## Fields

- `Text _textName`

- `Image _icon`

- `Image _bkgTitle`

- `Text _textDesc`

- `Boolean _useDarkCommentColor`

- `Text _unlockCondition`

- `GameObject _panelLocked`

- `Color _colorBkgLocked`

- `GameObject _btnNextLevel`

- `UIAutoSlideRect _autoSlideRect`

- `Boolean m_isInited`

- `BuildingBuffDescStruct m_buffCache`


## Properties

- `RectTransform anchorNextLevelButton`

- `BuildingBuffDescStruct buffStruct`


## Methods

- `Void set_onNextLevelClicked(Action`1)`

- `RectTransform get_anchorNextLevelButton()`

- `BuildingBuffDescStruct get_buffStruct()`

- `Void OnEnable()`

- `Void Render(BuildingBuffDescStruct)`

- `Void _StartAutoLayoutCoroutine()`

- `IEnumerator _UpdateAutoLayoutsCoroutine()`

- `Void EventOnNextLevelClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingBuffDescView : MonoBehaviour, IHotfixable
{
	private Text _textName; // 0x18
	private Image _icon; // 0x20
	private Image _bkgTitle; // 0x28
	private Text _textDesc; // 0x30
	private Boolean _useDarkCommentColor; // 0x38
	private Text _unlockCondition; // 0x40
	private GameObject _panelLocked; // 0x48
	private Color _colorBkgLocked; // 0x50
	private GameObject _btnNextLevel; // 0x60
	private RectTransform[] _autoLayouts; // 0x68
	private UIAutoSlideRect _autoSlideRect; // 0x70
	private Boolean m_isInited; // 0x78
	private BuildingBuffDescStruct m_buffCache; // 0x80
	private Action`1 <onNextLevelClicked>k__BackingField; // 0xf0
	private static DelegateBridge __Hotfix0_get_onNextLevelClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onNextLevelClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_anchorNextLevelButton; // 0x10
	private static DelegateBridge __Hotfix0_get_buffStruct; // 0x18
	private static DelegateBridge __Hotfix0_OnEnable; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge __Hotfix0__StartAutoLayoutCoroutine; // 0x30
	private static DelegateBridge __Hotfix0__UpdateAutoLayoutsCoroutine; // 0x38
	private static DelegateBridge __Hotfix0_EventOnNextLevelClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public Action`1 onNextLevelClicked { get; set; }
	public RectTransform anchorNextLevelButton { get; }
	public BuildingBuffDescStruct buffStruct { get; }

	// RVA: 0x3d36dbc VA: 0x759634edbc
	public Action`1 get_onNextLevelClicked() { }
	// RVA: 0x3d36e24 VA: 0x759634ee24
	public Void set_onNextLevelClicked(Action`1 value) { }
	// RVA: 0x3d36ea8 VA: 0x759634eea8
	public RectTransform get_anchorNextLevelButton() { }
	// RVA: 0x3d36f8c VA: 0x759634ef8c
	public BuildingBuffDescStruct get_buffStruct() { }
	// RVA: 0x3d37030 VA: 0x759634f030
	private Void OnEnable() { }
	// RVA: 0x3d3717c VA: 0x759634f17c
	public Void Render(BuildingBuffDescStruct buffDesc) { }
	// RVA: 0x3d37098 VA: 0x759634f098
	private Void _StartAutoLayoutCoroutine() { }
	// RVA: 0x3d374e8 VA: 0x759634f4e8
	private IEnumerator _UpdateAutoLayoutsCoroutine() { }
	// RVA: 0x3d375bc VA: 0x759634f5bc
	public Void EventOnNextLevelClicked() { }
	// RVA: 0x3d3765c VA: 0x759634f65c
	public Void .ctor() { }
}
```