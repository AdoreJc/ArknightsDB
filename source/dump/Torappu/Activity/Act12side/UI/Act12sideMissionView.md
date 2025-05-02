# Act12sideMissionView

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Act12sideMissionListAdapter _listAdapter`

- `Text _textCompletion`

- `Text _textMilestonePoint`

- `Boolean m_hasInited`

- `Act12sideMissionProperty m_property`

- `Act12sideMissionViewModel m_missionViewModel`

- `String m_actId`


## Methods

- `Void Init(String)`

- `Void _InitIfNot()`

- `Void _OnFilterSelected(ActZoneClass)`

- `Void _TraverseFilterList(Action`1)`

- `Void <_InitIfNot>b__10_0(Act12sideMissionFilterItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideMissionView : DataBinder`1
{
	private Act12sideMissionListAdapter _listAdapter; // 0x20
	private Act12sideMissionFilterItemView[] _filterItems; // 0x28
	private Text _textCompletion; // 0x30
	private Text _textMilestonePoint; // 0x38
	private Boolean m_hasInited; // 0x40
	private Act12sideMissionProperty m_property; // 0x48
	private Act12sideMissionViewModel m_missionViewModel; // 0x50
	private String m_actId; // 0x58
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__OnFilterSelected; // 0x18
	private static DelegateBridge __Hotfix0__TraverseFilterList; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x345fa10 VA: 0x7595a77a10
	public Void Init(String actId) { }
	// RVA: 0x346763c VA: 0x7595a7f63c
	public override Void OnValueChanged(Act12sideMissionProperty property) { }
	// RVA: 0x34678fc VA: 0x7595a7f8fc
	private Void _InitIfNot() { }
	// RVA: 0x3467b18 VA: 0x7595a7fb18
	private Void _OnFilterSelected(ActZoneClass zoneClass) { }
	// RVA: 0x34679d0 VA: 0x7595a7f9d0
	private Void _TraverseFilterList(Action`1 action) { }
	// RVA: 0x3467bf0 VA: 0x7595a7fbf0
	public Void .ctor() { }
	// RVA: 0x3467c80 VA: 0x7595a7fc80
	private Void <_InitIfNot>b__10_0(Act12sideMissionFilterItemView filterItem) { }
}
```