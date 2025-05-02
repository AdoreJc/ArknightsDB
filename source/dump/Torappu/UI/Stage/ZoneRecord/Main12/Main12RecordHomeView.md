# Main12RecordHomeView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main12`


## Fields

- `Text _recordTitle`

- `Text _recordDesc`

- `ZoneRecordRewardBuffPlugin _rewardBuffPlugin`

- `Boolean m_isInited`

- `Action <onClickAllRewardBtn>k__BackingField`

- `Action <onClickRewardBuffBtn>k__BackingField`


## Properties

- `Action onClickAllRewardBtn`

- `Action onClickRewardBuffBtn`


## Methods

- `Void set_onClickBtn(Action`1)`

- `Action get_onClickAllRewardBtn()`

- `Void set_onClickAllRewardBtn(Action)`

- `Action get_onClickRewardBuffBtn()`

- `Void set_onClickRewardBuffBtn(Action)`

- `Void OnClickAllRewardBtn()`

- `Void OnClickRewardBuffBtn()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main12
public class Main12RecordHomeView : DataBinder`1
{
	private List`1 _buttonViews; // 0x20
	private Text _recordTitle; // 0x28
	private Text _recordDesc; // 0x30
	private ZoneRecordRewardBuffPlugin _rewardBuffPlugin; // 0x38
	private Boolean m_isInited; // 0x40
	private Action`1 <onClickBtn>k__BackingField; // 0x48
	private Action <onClickAllRewardBtn>k__BackingField; // 0x50
	private Action <onClickRewardBuffBtn>k__BackingField; // 0x58
	private static DelegateBridge __Hotfix0_get_onClickBtn; // 0x0
	private static DelegateBridge __Hotfix0_set_onClickBtn; // 0x8
	private static DelegateBridge __Hotfix0_get_onClickAllRewardBtn; // 0x10
	private static DelegateBridge __Hotfix0_set_onClickAllRewardBtn; // 0x18
	private static DelegateBridge __Hotfix0_get_onClickRewardBuffBtn; // 0x20
	private static DelegateBridge __Hotfix0_set_onClickRewardBuffBtn; // 0x28
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x30
	private static DelegateBridge __Hotfix0_OnClickAllRewardBtn; // 0x38
	private static DelegateBridge __Hotfix0_OnClickRewardBuffBtn; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private Action`1 onClickBtn { get; set; }
	private Action onClickAllRewardBtn { get; set; }
	private Action onClickRewardBuffBtn { get; set; }

	// RVA: 0x2fce1a4 VA: 0x75955e61a4
	private Action`1 get_onClickBtn() { }
	// RVA: 0x2fce20c VA: 0x75955e620c
	public Void set_onClickBtn(Action`1 value) { }
	// RVA: 0x2fce290 VA: 0x75955e6290
	private Action get_onClickAllRewardBtn() { }
	// RVA: 0x2fce2f8 VA: 0x75955e62f8
	public Void set_onClickAllRewardBtn(Action value) { }
	// RVA: 0x2fce37c VA: 0x75955e637c
	private Action get_onClickRewardBuffBtn() { }
	// RVA: 0x2fce3e4 VA: 0x75955e63e4
	public Void set_onClickRewardBuffBtn(Action value) { }
	// RVA: 0x2fce468 VA: 0x75955e6468
	public override Void OnValueChanged(Main12ZoneRecordViewProperty property) { }
	// RVA: 0x2fce7e8 VA: 0x75955e67e8
	public Void OnClickAllRewardBtn() { }
	// RVA: 0x2fce884 VA: 0x75955e6884
	public Void OnClickRewardBuffBtn() { }
	// RVA: 0x2fce654 VA: 0x75955e6654
	private Void _InitIfNot() { }
	// RVA: 0x2fce920 VA: 0x75955e6920
	public Void .ctor() { }
}
```