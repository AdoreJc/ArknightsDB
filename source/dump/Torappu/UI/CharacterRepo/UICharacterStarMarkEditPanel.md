# UICharacterStarMarkEditPanel

**Namespace:** `Torappu.UI.CharacterRepo`


## Fields

- `Text _starMarkCount`

- `UIAnimationLocation _starMarkEditSwitchAnim`

- `RectTransform _backPressRt`

- `Action eventOnStarMarkEditConfirm`

- `Action eventOnClearAllStarMark`

- `Action eventOnExitEditMode`

- `Boolean m_panelShowed`

- `Boolean m_isInited`

- `AnimationSwitchTween m_starMarkEditModeSwitch`


## Properties

- `Boolean isShow`


## Methods

- `Boolean get_isShow()`

- `Void set_isShow(Boolean)`

- `Void Render(Int32)`

- `Void EventOnConfirmEdit()`

- `Void EventOnClearMarks()`

- `Void OnExitEditMode()`

- `Void _InitIfNot()`

- `Void _EnsureSwitchTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterRepo
public class UICharacterStarMarkEditPanel : MonoBehaviour, IHotfixable
{
	private Text _starMarkCount; // 0x18
	private UIAnimationLocation _starMarkEditSwitchAnim; // 0x20
	private RectTransform _backPressRt; // 0x30
	public Action eventOnStarMarkEditConfirm; // 0x38
	public Action eventOnClearAllStarMark; // 0x40
	public Action eventOnExitEditMode; // 0x48
	private Boolean m_panelShowed; // 0x50
	private Boolean m_isInited; // 0x51
	private AnimationSwitchTween m_starMarkEditModeSwitch; // 0x58
	private static DelegateBridge __Hotfix0_get_isShow; // 0x0
	private static DelegateBridge __Hotfix0_set_isShow; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_EventOnConfirmEdit; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClearMarks; // 0x20
	private static DelegateBridge __Hotfix0_OnExitEditMode; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__EnsureSwitchTween; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Boolean isShow { get; set; }

	// RVA: 0x2cfea80 VA: 0x7595316a80
	public Boolean get_isShow() { }
	// RVA: 0x2cfeae8 VA: 0x7595316ae8
	public Void set_isShow(Boolean value) { }
	// RVA: 0x2cfeca8 VA: 0x7595316ca8
	public Void Render(Int32 starMarkCnt) { }
	// RVA: 0x2cfee60 VA: 0x7595316e60
	public Void EventOnConfirmEdit() { }
	// RVA: 0x2cfef08 VA: 0x7595316f08
	public Void EventOnClearMarks() { }
	// RVA: 0x2cfefb0 VA: 0x7595316fb0
	public Void OnExitEditMode() { }
	// RVA: 0x2cfed5c VA: 0x7595316d5c
	private Void _InitIfNot() { }
	// RVA: 0x2cfeba4 VA: 0x7595316ba4
	private Void _EnsureSwitchTween() { }
	// RVA: 0x2cff034 VA: 0x7595317034
	public Void .ctor() { }
}
```