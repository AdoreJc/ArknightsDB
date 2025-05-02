# BuildingCharAvatar

**Namespace:** `Torappu.Building.UI`


## Fields

- `GameObject _panelActive`

- `GameObject _panelAdd`

- `GameObject _panelLocked`

- `GameObject _panelAddLabel`

- `Text _textAdd`

- `GameObject _panelEmpty`

- `GameObject _panelClickable`

- `Image _imgAvatar`

- `GameObject _hilightMask`

- `GameObject _statusContainer`

- `GameObject _darkMask`

- `GameObject _tiredMask`

- `GameObject _iconTired`

- `GameObject _iconWork`

- `GameObject _iconRest`

- `FillProgressBar _progress`

- `GameObject _iconRemove`

- `GameObject _iconTraining`

- `Image _iconApStatus`

- `Object m_param`

- `Boolean m_isInited`

- `OverrideStatus m_overrideStatus`

- `Boolean m_isRemovable`

- `BuildingCharModel m_charModel`

- `CountDownTask m_countDown`


## Properties

- `Boolean isClickable`

- `Boolean isHilgihted`

- `Boolean enableStatusPanel`

- `String labelAddText`


## Methods

- `Boolean get_isClickable()`

- `Void Start()`

- `Void OnDestroy()`

- `Void UpdateTime(Single)`

- `Void SetParam(Object)`

- `Boolean get_isHilgihted()`

- `Void set_isHilgihted(Boolean)`

- `Boolean get_enableStatusPanel()`

- `Void set_enableStatusPanel(Boolean)`

- `String get_labelAddText()`

- `Void set_labelAddText(String)`

- `Void Render(BuildingCharModel, OverrideStatus, Boolean)`

- `Void EventOnAvatarClicked()`

- `Void _OnUpdateManpower()`

- `Void _UpdateActivePanel()`

- `Void _UpdateManpower()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingCharAvatar : MonoBehaviour, ITimeWatcher, IHotfixable
{
	private GameObject _panelActive; // 0x18
	private GameObject _panelAdd; // 0x20
	private GameObject _panelLocked; // 0x28
	private GameObject _panelAddLabel; // 0x30
	private Text _textAdd; // 0x38
	private GameObject _panelEmpty; // 0x40
	private GameObject _panelClickable; // 0x48
	private Image _imgAvatar; // 0x50
	private GameObject _hilightMask; // 0x58
	private GameObject _statusContainer; // 0x60
	private GameObject _darkMask; // 0x68
	private GameObject _tiredMask; // 0x70
	private GameObject _iconTired; // 0x78
	private GameObject _iconWork; // 0x80
	private GameObject _iconRest; // 0x88
	private FillProgressBar _progress; // 0x90
	private GameObject _iconRemove; // 0x98
	private GameObject _iconTraining; // 0xa0
	private Image _iconApStatus; // 0xa8
	private StateConfig[] _apStateConfigs; // 0xb0
	private Object m_param; // 0xb8
	private Boolean m_isInited; // 0xc0
	private OverrideStatus m_overrideStatus; // 0xc4
	private Boolean m_isRemovable; // 0xc8
	private BuildingCharModel m_charModel; // 0xd0
	private CountDownTask m_countDown; // 0x140
	public Action`2 onAvatarClicked; // 0x148
	public Action`1 onLockClicked; // 0x150
	private static DelegateBridge __Hotfix0_get_isClickable; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x18
	private static DelegateBridge __Hotfix0_SetParam; // 0x20
	private static DelegateBridge __Hotfix0_get_isHilgihted; // 0x28
	private static DelegateBridge __Hotfix0_set_isHilgihted; // 0x30
	private static DelegateBridge __Hotfix0_get_enableStatusPanel; // 0x38
	private static DelegateBridge __Hotfix0_set_enableStatusPanel; // 0x40
	private static DelegateBridge __Hotfix0_get_labelAddText; // 0x48
	private static DelegateBridge __Hotfix0_set_labelAddText; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x58
	private static DelegateBridge __Hotfix0_EventOnAvatarClicked; // 0x60
	private static DelegateBridge __Hotfix0__OnUpdateManpower; // 0x68
	private static DelegateBridge __Hotfix0__UpdateActivePanel; // 0x70
	private static DelegateBridge __Hotfix0__UpdateManpower; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	public Boolean isClickable { get; }
	public Boolean isHilgihted { get; set; }
	public Boolean enableStatusPanel { get; set; }
	public String labelAddText { get; set; }

	// RVA: 0x3d37864 VA: 0x759634f864
	public Boolean get_isClickable() { }
	// RVA: 0x3d378d4 VA: 0x759634f8d4
	private Void Start() { }
	// RVA: 0x3d37944 VA: 0x759634f944
	private Void OnDestroy() { }
	// RVA: 0x3d379b4 VA: 0x759634f9b4
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x3d37a48 VA: 0x759634fa48
	public Void SetParam(Object param) { }
	// RVA: 0x3d37acc VA: 0x759634facc
	public Boolean get_isHilgihted() { }
	// RVA: 0x3d37b40 VA: 0x759634fb40
	public Void set_isHilgihted(Boolean value) { }
	// RVA: 0x3d37bc4 VA: 0x759634fbc4
	public Boolean get_enableStatusPanel() { }
	// RVA: 0x3d37c38 VA: 0x759634fc38
	public Void set_enableStatusPanel(Boolean value) { }
	// RVA: 0x3d37cbc VA: 0x759634fcbc
	public String get_labelAddText() { }
	// RVA: 0x3d37d78 VA: 0x759634fd78
	public Void set_labelAddText(String value) { }
	// RVA: 0x3d37e4c VA: 0x759634fe4c
	public Void Render(BuildingCharModel charModel, OverrideStatus overrideStatus, Boolean isRemovable) { }
	// RVA: 0x3d38220 VA: 0x7596350220
	public Void EventOnAvatarClicked() { }
	// RVA: 0x3d38324 VA: 0x7596350324
	private Void _OnUpdateManpower() { }
	// RVA: 0x3d38084 VA: 0x7596350084
	private Void _UpdateActivePanel() { }
	// RVA: 0x3d3838c VA: 0x759635038c
	private Void _UpdateManpower() { }
	// RVA: 0x3d3863c VA: 0x759635063c
	public Void .ctor() { }
}
```