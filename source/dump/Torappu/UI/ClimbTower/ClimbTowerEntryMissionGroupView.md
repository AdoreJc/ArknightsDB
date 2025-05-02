# ClimbTowerEntryMissionGroupView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerEntryMissionGridAdapter _adapter`

- `Text _seasonNum`

- `Text _seasonName`

- `SimpleLayoutContent _progressContent`

- `Text _seasonEndTime`

- `Text _seasonRemainTime`

- `UIPage <page>k__BackingField`

- `Boolean m_hasInited`

- `Int32 m_periodSum`

- `Int32 m_periodCurr`

- `SeasonProgressAdapter m_progressAdapter`


## Properties

- `UIPage page`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void set_onItemClicked(Action`1)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryMissionGroupView : DataBinder`1, IHotfixable
{
	private ClimbTowerEntryMissionGridAdapter _adapter; // 0x20
	private Text _seasonNum; // 0x28
	private Text _seasonName; // 0x30
	private SimpleLayoutContent _progressContent; // 0x38
	private Text _seasonEndTime; // 0x40
	private Text _seasonRemainTime; // 0x48
	private UIPage <page>k__BackingField; // 0x50
	private Action`1 <onItemClicked>k__BackingField; // 0x58
	private Boolean m_hasInited; // 0x60
	private Int32 m_periodSum; // 0x64
	private Int32 m_periodCurr; // 0x68
	private SeasonProgressAdapter m_progressAdapter; // 0x70
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private UIPage page { get; set; }
	private Action`1 onItemClicked { get; set; }

	// RVA: 0x2c68b64 VA: 0x7595280b64
	private UIPage get_page() { }
	// RVA: 0x2c68bcc VA: 0x7595280bcc
	public Void set_page(UIPage value) { }
	// RVA: 0x2c68c50 VA: 0x7595280c50
	private Action`1 get_onItemClicked() { }
	// RVA: 0x2c68cb8 VA: 0x7595280cb8
	public Void set_onItemClicked(Action`1 value) { }
	// RVA: 0x2c68d3c VA: 0x7595280d3c
	public override Void OnValueChanged(ClimbTowerEntryMissionProperty property) { }
	// RVA: 0x2c691a0 VA: 0x75952811a0
	private Void _InitIfNot() { }
	// RVA: 0x2c69304 VA: 0x7595281304
	public Void .ctor() { }
}
```