# FurnitureItemView

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `Text _nameText`

- `GameObject _countTextRoot`

- `GameObject _countTextCornerRoot`

- `Text _countText`

- `Text _countCornerText`

- `Button _button`

- `Button _upperInfoButton`

- `Button _lowerInfoButton`

- `Button _renameButton`

- `Image _bigIcon`

- `Image _smallIcon`

- `GameObjectArrayCountControl _starArray`

- `GameObject _meetingOnlyIcon`

- `GameObject _comfortPanel`

- `Text _comfortLabel`

- `GameObject _selectedMark`

- `CanvasGroup _canvasGroup`

- `Single _disableAlpha`

- `GameObject _newMark`

- `GameObject _pnlInvalidMask`

- `Text _textInvalid`

- `GameObject _disableMask`

- `Graphic _disableGraphic`

- `DIYItemViewData m_itemData`

- `Int32 m_viewIndex`


## Methods

- `Void add_buttonPressed(Action`2)`

- `Void remove_buttonPressed(Action`2)`

- `Void add_subButtonPressed(Action`2)`

- `Void remove_subButtonPressed(Action`2)`

- `Void add_renameButtonPressed(Action`2)`

- `Void remove_renameButtonPressed(Action`2)`

- `Void add_infoButtonPressed(Action`2)`

- `Void remove_infoButtonPressed(Action`2)`

- `Void _SetupIcon(Image, Sprite)`

- `Void Setup(DIYItemViewData)`

- `Int32 GetViewIndex()`

- `Void SetViewIndex(Int32)`

- `Void OnButtonPressed()`

- `Void OnSubButtonPressed()`

- `Void OnRenameButtonPressed()`

- `Void OnInfoButtonPressed()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class FurnitureItemView : MonoBehaviour, IHotfixable
{
	private static readonly Color COLOR_NORMAL; // 0x0
	private static readonly Color COLOR_DISABLED; // 0x10
	private Text _nameText; // 0x18
	private GameObject _countTextRoot; // 0x20
	private GameObject _countTextCornerRoot; // 0x28
	private Text _countText; // 0x30
	private Text _countCornerText; // 0x38
	private Button _button; // 0x40
	private Button _upperInfoButton; // 0x48
	private Button _lowerInfoButton; // 0x50
	private Button _renameButton; // 0x58
	private Image _bigIcon; // 0x60
	private Image _smallIcon; // 0x68
	private GameObjectArrayCountControl _starArray; // 0x70
	private GameObject _meetingOnlyIcon; // 0x78
	private GameObject _comfortPanel; // 0x80
	private Text _comfortLabel; // 0x88
	private GameObject _selectedMark; // 0x90
	private CanvasGroup _canvasGroup; // 0x98
	private Single _disableAlpha; // 0xa0
	private GameObject _newMark; // 0xa8
	private GameObject _pnlInvalidMask; // 0xb0
	private Text _textInvalid; // 0xb8
	private GameObject _disableMask; // 0xc0
	private Graphic _disableGraphic; // 0xc8
	private DIYItemViewData m_itemData; // 0xd0
	private Int32 m_viewIndex; // 0xd8
	private Action`2 buttonPressed; // 0xe0
	private Action`2 subButtonPressed; // 0xe8
	private Action`2 renameButtonPressed; // 0xf0
	private Action`2 infoButtonPressed; // 0xf8
	private static DelegateBridge __Hotfix0_add_buttonPressed; // 0x20
	private static DelegateBridge __Hotfix0_remove_buttonPressed; // 0x28
	private static DelegateBridge __Hotfix0_add_subButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0_remove_subButtonPressed; // 0x38
	private static DelegateBridge __Hotfix0_add_renameButtonPressed; // 0x40
	private static DelegateBridge __Hotfix0_remove_renameButtonPressed; // 0x48
	private static DelegateBridge __Hotfix0_add_infoButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0_remove_infoButtonPressed; // 0x58
	private static DelegateBridge __Hotfix0__SetupIcon; // 0x60
	private static DelegateBridge __Hotfix0_Setup; // 0x68
	private static DelegateBridge __Hotfix0_GetViewIndex; // 0x70
	private static DelegateBridge __Hotfix0_SetViewIndex; // 0x78
	private static DelegateBridge __Hotfix0_OnButtonPressed; // 0x80
	private static DelegateBridge __Hotfix0_OnSubButtonPressed; // 0x88
	private static DelegateBridge __Hotfix0_OnRenameButtonPressed; // 0x90
	private static DelegateBridge __Hotfix0_OnInfoButtonPressed; // 0x98
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x381e2b8 VA: 0x7595e362b8
	public Void add_buttonPressed(Action`2 value) { }
	// RVA: 0x381e1b4 VA: 0x7595e361b4
	public Void remove_buttonPressed(Action`2 value) { }
	// RVA: 0x381e4c0 VA: 0x7595e364c0
	public Void add_subButtonPressed(Action`2 value) { }
	// RVA: 0x381e3bc VA: 0x7595e363bc
	public Void remove_subButtonPressed(Action`2 value) { }
	// RVA: 0x381e6c8 VA: 0x7595e366c8
	public Void add_renameButtonPressed(Action`2 value) { }
	// RVA: 0x381e5c4 VA: 0x7595e365c4
	public Void remove_renameButtonPressed(Action`2 value) { }
	// RVA: 0x381e8d0 VA: 0x7595e368d0
	public Void add_infoButtonPressed(Action`2 value) { }
	// RVA: 0x381e7cc VA: 0x7595e367cc
	public Void remove_infoButtonPressed(Action`2 value) { }
	// RVA: 0x382cef0 VA: 0x7595e44ef0
	private Void _SetupIcon(Image img, Sprite sp) { }
	// RVA: 0x381d124 VA: 0x7595e35124
	public Void Setup(DIYItemViewData data) { }
	// RVA: 0x382d034 VA: 0x7595e45034
	public Int32 GetViewIndex() { }
	// RVA: 0x381e128 VA: 0x7595e36128
	public Void SetViewIndex(Int32 index) { }
	// RVA: 0x382d0ac VA: 0x7595e450ac
	public Void OnButtonPressed() { }
	// RVA: 0x382d170 VA: 0x7595e45170
	public Void OnSubButtonPressed() { }
	// RVA: 0x382d234 VA: 0x7595e45234
	public Void OnRenameButtonPressed() { }
	// RVA: 0x382d2f8 VA: 0x7595e452f8
	public Void OnInfoButtonPressed() { }
	// RVA: 0x382d398 VA: 0x7595e45398
	private Void OnDestroy() { }
	// RVA: 0x382d42c VA: 0x7595e4542c
	public Void .ctor() { }
	// RVA: 0x382d4ac VA: 0x7595e454ac
	private static Void .cctor() { }
}
```