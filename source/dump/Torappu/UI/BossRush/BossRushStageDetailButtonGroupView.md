# BossRushStageDetailButtonGroupView

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `BossRushStageDetailSwitchButtonView _spModeSwitchBtn`

- `TwoStateToggle _startBattleToggle`

- `GameObject _imgBkgEx`

- `Boolean m_hasInited`

- `Action <onModeSwitchButtonClick>k__BackingField`

- `Action <onStartBattleClick>k__BackingField`

- `Action <onRewardClick>k__BackingField`


## Properties

- `Action onModeSwitchButtonClick`

- `Action onStartBattleClick`

- `Action onRewardClick`


## Methods

- `Void set_onModeButtonClick(Action`1)`

- `Action get_onModeSwitchButtonClick()`

- `Void set_onModeSwitchButtonClick(Action)`

- `Action get_onStartBattleClick()`

- `Void set_onStartBattleClick(Action)`

- `Action get_onRewardClick()`

- `Void set_onRewardClick(Action)`

- `Void OnStartBattleClick()`

- `Void OnRewardClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailButtonGroupView : DataBinder`1, IHotfixable
{
	private List`1 _normalBtnList; // 0x20
	private BossRushStageDetailSwitchButtonView _spModeSwitchBtn; // 0x28
	private TwoStateToggle _startBattleToggle; // 0x30
	private GameObject _imgBkgEx; // 0x38
	private Boolean m_hasInited; // 0x40
	private Action`1 <onModeButtonClick>k__BackingField; // 0x48
	private Action <onModeSwitchButtonClick>k__BackingField; // 0x50
	private Action <onStartBattleClick>k__BackingField; // 0x58
	private Action <onRewardClick>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onModeButtonClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onModeButtonClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onModeSwitchButtonClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onModeSwitchButtonClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onStartBattleClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onStartBattleClick; // 0x28
	private static DelegateBridge __Hotfix0_get_onRewardClick; // 0x30
	private static DelegateBridge __Hotfix0_set_onRewardClick; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x40
	private static DelegateBridge __Hotfix0_OnStartBattleClick; // 0x48
	private static DelegateBridge __Hotfix0_OnRewardClick; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Action`1 onModeButtonClick { get; set; }
	private Action onModeSwitchButtonClick { get; set; }
	private Action onStartBattleClick { get; set; }
	private Action onRewardClick { get; set; }

	// RVA: 0x2e715d0 VA: 0x75954895d0
	private Action`1 get_onModeButtonClick() { }
	// RVA: 0x2e71638 VA: 0x7595489638
	public Void set_onModeButtonClick(Action`1 value) { }
	// RVA: 0x2e716bc VA: 0x75954896bc
	private Action get_onModeSwitchButtonClick() { }
	// RVA: 0x2e71724 VA: 0x7595489724
	public Void set_onModeSwitchButtonClick(Action value) { }
	// RVA: 0x2e717a8 VA: 0x75954897a8
	private Action get_onStartBattleClick() { }
	// RVA: 0x2e71810 VA: 0x7595489810
	public Void set_onStartBattleClick(Action value) { }
	// RVA: 0x2e71894 VA: 0x7595489894
	private Action get_onRewardClick() { }
	// RVA: 0x2e718fc VA: 0x75954898fc
	public Void set_onRewardClick(Action value) { }
	// RVA: 0x2e71980 VA: 0x7595489980
	public override Void OnValueChanged(BossRushStageDetailProperty property) { }
	// RVA: 0x2e71c40 VA: 0x7595489c40
	public Void OnStartBattleClick() { }
	// RVA: 0x2e71d14 VA: 0x7595489d14
	public Void OnRewardClick() { }
	// RVA: 0x2e71b0c VA: 0x7595489b0c
	private Void _InitIfNot() { }
	// RVA: 0x2e71db0 VA: 0x7595489db0
	public Void .ctor() { }
}
```