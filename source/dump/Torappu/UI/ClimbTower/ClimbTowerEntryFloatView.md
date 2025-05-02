# ClimbTowerEntryFloatView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerEntryFloatMissionView _missionView`

- `ClimbTowerEntryFloatSeasonProgressView _seasonProgressView`

- `ClimbTowerEntryFloatGodCardView _godCardView`

- `Text _seasonName`

- `Text _seasonNumTxt`

- `Text _textEndTime`

- `Text _textRemainTime`

- `Boolean m_hasInited`

- `String m_seasonId`

- `UIPage <page>k__BackingField`

- `Action <onMissionClicked>k__BackingField`

- `Action <onGodCardBtnClicked>k__BackingField`


## Properties

- `UIPage page`

- `Action onMissionClicked`

- `Action onGodCardBtnClicked`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Action get_onMissionClicked()`

- `Void set_onMissionClicked(Action)`

- `Void set_onGodCardItemClicked(Action`1)`

- `Action get_onGodCardBtnClicked()`

- `Void set_onGodCardBtnClicked(Action)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryFloatView : DataBinder`1, IHotfixable
{
	private ClimbTowerEntryFloatMissionView _missionView; // 0x20
	private ClimbTowerEntryFloatSeasonProgressView _seasonProgressView; // 0x28
	private ClimbTowerEntryFloatGodCardView _godCardView; // 0x30
	private GameObject[] _panelNeedBanned; // 0x38
	private Text _seasonName; // 0x40
	private Text _seasonNumTxt; // 0x48
	private Text _textEndTime; // 0x50
	private Text _textRemainTime; // 0x58
	private Boolean m_hasInited; // 0x60
	private String m_seasonId; // 0x68
	private UIPage <page>k__BackingField; // 0x70
	private Action <onMissionClicked>k__BackingField; // 0x78
	private Action`1 <onGodCardItemClicked>k__BackingField; // 0x80
	private Action <onGodCardBtnClicked>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_onMissionClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onMissionClicked; // 0x18
	private static DelegateBridge __Hotfix0_get_onGodCardItemClicked; // 0x20
	private static DelegateBridge __Hotfix0_set_onGodCardItemClicked; // 0x28
	private static DelegateBridge __Hotfix0_get_onGodCardBtnClicked; // 0x30
	private static DelegateBridge __Hotfix0_set_onGodCardBtnClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	private UIPage page { get; set; }
	private Action onMissionClicked { get; set; }
	private Action`1 onGodCardItemClicked { get; set; }
	private Action onGodCardBtnClicked { get; set; }

	// RVA: 0x2c647fc VA: 0x759527c7fc
	private UIPage get_page() { }
	// RVA: 0x2c64864 VA: 0x759527c864
	public Void set_page(UIPage value) { }
	// RVA: 0x2c648e8 VA: 0x759527c8e8
	private Action get_onMissionClicked() { }
	// RVA: 0x2c64950 VA: 0x759527c950
	public Void set_onMissionClicked(Action value) { }
	// RVA: 0x2c649d4 VA: 0x759527c9d4
	private Action`1 get_onGodCardItemClicked() { }
	// RVA: 0x2c64a3c VA: 0x759527ca3c
	public Void set_onGodCardItemClicked(Action`1 value) { }
	// RVA: 0x2c64ac0 VA: 0x759527cac0
	private Action get_onGodCardBtnClicked() { }
	// RVA: 0x2c64b28 VA: 0x759527cb28
	public Void set_onGodCardBtnClicked(Action value) { }
	// RVA: 0x2c64bac VA: 0x759527cbac
	public override Void OnValueChanged(ClimbTowerEntryFloatPanelProperty property) { }
	// RVA: 0x2c6501c VA: 0x759527d01c
	private Void _InitIfNot() { }
	// RVA: 0x2c65128 VA: 0x759527d128
	public Void .ctor() { }
}
```