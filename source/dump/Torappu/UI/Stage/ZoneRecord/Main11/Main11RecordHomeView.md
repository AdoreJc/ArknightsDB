# Main11RecordHomeView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main11`


## Fields

- `GameObject _panelHardStageBanned`

- `Text _textTitle`

- `Text _textDesc`

- `Boolean m_hasInited`

- `Action <onAllRewardsClicked>k__BackingField`


## Properties

- `Action onAllRewardsClicked`


## Methods

- `Void set_onBtnClicked(Action`1)`

- `Action get_onAllRewardsClicked()`

- `Void set_onAllRewardsClicked(Action)`

- `Void OnAllRewardsBtnClicked()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main11
public class Main11RecordHomeView : DataBinder`1, IHotfixable
{
	private Main11RecordHomeButtonView[] _buttonView; // 0x20
	private GameObject _panelHardStageBanned; // 0x28
	private Text _textTitle; // 0x30
	private Text _textDesc; // 0x38
	private Boolean m_hasInited; // 0x40
	private Action`1 <onBtnClicked>k__BackingField; // 0x48
	private Action <onAllRewardsClicked>k__BackingField; // 0x50
	private static DelegateBridge __Hotfix0_get_onBtnClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onAllRewardsClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onAllRewardsClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnAllRewardsBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`1 onBtnClicked { get; set; }
	private Action onAllRewardsClicked { get; set; }

	// RVA: 0x2fd5e78 VA: 0x75955ede78
	private Action`1 get_onBtnClicked() { }
	// RVA: 0x2fd5ee0 VA: 0x75955edee0
	public Void set_onBtnClicked(Action`1 value) { }
	// RVA: 0x2fd5f64 VA: 0x75955edf64
	private Action get_onAllRewardsClicked() { }
	// RVA: 0x2fd5fcc VA: 0x75955edfcc
	public Void set_onAllRewardsClicked(Action value) { }
	// RVA: 0x2fd6050 VA: 0x75955ee050
	public override Void OnValueChanged(Main11ZoneRecordViewProperty property) { }
	// RVA: 0x2fd6318 VA: 0x75955ee318
	public Void OnAllRewardsBtnClicked() { }
	// RVA: 0x2fd61e8 VA: 0x75955ee1e8
	private Void _InitIfNot() { }
	// RVA: 0x2fd63b4 VA: 0x75955ee3b4
	public Void .ctor() { }
}
```