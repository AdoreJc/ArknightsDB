# BossRushStageDetailSwitchButtonView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `GameObject _panelSpUnselect`

- `GameObject _panelSpSelect`

- `TwoStateToggle _normalBtnToggle`

- `GameObject _panelAnimSwitch`

- `CanvasGroup _canvasGroupAnimSwitch`

- `RectTransform _rectAnimSwitch`

- `TwoStateToggle _toggleAnimSwitch`

- `SwitchTween m_switchTween`

- `Boolean m_hasInited`

- `Action <onBtnClick>k__BackingField`


## Properties

- `Action onBtnClick`


## Methods

- `Action get_onBtnClick()`

- `Void set_onBtnClick(Action)`

- `Void Render(Boolean, Boolean)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailSwitchButtonView : MonoBehaviour, IHotfixable
{
	private const Single START_WIDTH; // 0x0
	private const Single END_WIDTH; // 0x0
	private const Single HEIGHT; // 0x0
	private const Single TWEEN_DURATION; // 0x0
	private GameObject _panelSpUnselect; // 0x18
	private GameObject _panelSpSelect; // 0x20
	private TwoStateToggle _normalBtnToggle; // 0x28
	private GameObject _panelAnimSwitch; // 0x30
	private CanvasGroup _canvasGroupAnimSwitch; // 0x38
	private RectTransform _rectAnimSwitch; // 0x40
	private TwoStateToggle _toggleAnimSwitch; // 0x48
	private SwitchTween m_switchTween; // 0x50
	private Boolean m_hasInited; // 0x58
	private Action <onBtnClick>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action onBtnClick { get; set; }

	// RVA: 0x2e7a0fc VA: 0x75954920fc
	private Action get_onBtnClick() { }
	// RVA: 0x2e7a164 VA: 0x7595492164
	public Void set_onBtnClick(Action value) { }
	// RVA: 0x2e7a1e8 VA: 0x75954921e8
	public Void Render(Boolean canSpModeShow, Boolean isSpModeShow) { }
	// RVA: 0x2e7a394 VA: 0x7595492394
	public Void OnClick() { }
	// RVA: 0x2e7a2d8 VA: 0x75954922d8
	private Void _InitIfNot() { }
	// RVA: 0x2e7a4e4 VA: 0x75954924e4
	public Void .ctor() { }
}
```