# BossRushStageDetailNormalButtonView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `BossRushStageType _bindStageType`

- `CanvasGroup _selectCanvasGroup`

- `CanvasGroup _textCanvasGroup`

- `Graphic _btnHotSpot`

- `GameObject _panelLocked`

- `Text _textMode`

- `Boolean m_hasInited`

- `NormalBtnFadeSwitch m_fadeSwitchTween`


## Methods

- `Void set_onBtnClick(Action`1)`

- `Void Render(BossRushStageType, Dictionary`2)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailNormalButtonView : MonoBehaviour, IHotfixable
{
	private const Single SWITCH_FADETIME; // 0x0
	private BossRushStageType _bindStageType; // 0x18
	private CanvasGroup _selectCanvasGroup; // 0x20
	private CanvasGroup _textCanvasGroup; // 0x28
	private Graphic _btnHotSpot; // 0x30
	private GameObject _panelLocked; // 0x38
	private Text _textMode; // 0x40
	private Boolean m_hasInited; // 0x48
	private NormalBtnFadeSwitch m_fadeSwitchTween; // 0x50
	private Action`1 <onBtnClick>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 onBtnClick { get; set; }

	// RVA: 0x2e759d8 VA: 0x759548d9d8
	private Action`1 get_onBtnClick() { }
	// RVA: 0x2e75a40 VA: 0x759548da40
	public Void set_onBtnClick(Action`1 value) { }
	// RVA: 0x2e75ac4 VA: 0x759548dac4
	public Void Render(BossRushStageType selectStage, Dictionary`2 unlockMap) { }
	// RVA: 0x2e75cdc VA: 0x759548dcdc
	public Void OnClick() { }
	// RVA: 0x2e75bd0 VA: 0x759548dbd0
	private Void _InitIfNot() { }
	// RVA: 0x2e75e10 VA: 0x759548de10
	public Void .ctor() { }
}
```