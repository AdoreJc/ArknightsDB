# Act3D5Entry

**Namespace:** `Torappu.Activity.Act3D5`


## Fields

- `Text _actDescLabel`

- `Text _pointTitle`

- `Text _pointCnt`

- `Text _timeDesc`

- `Image _pointIcon`

- `Text _helpBtnDesc`

- `Slider _prg`

- `Transform _itemContainer`

- `ScrollRect _scrollView`

- `Activity3D5Item _itemPrefab`

- `Activity3D5HelpView _helpViewPrefab`

- `Boolean m_adjustPrgWidth`

- `Activity3D5HelpView m_helpView`

- `String m_activityId`


## Methods

- `Void _SynPrg(List`1, Int32, Int32, Int32)`

- `Void _CheckMissionStatus()`

- `Void OnOpenHelpPage()`

- `Void _HandleHelpViewClose()`

- `Void OnScrollTo()`

- `Single _CalculateItemScrollPrg(Int32, Int32)`

- `Void <_CheckMissionStatus>b__18_0(ActivityMissionCheckResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D5
public class Act3D5Entry : ActivityCommonEntry, IHotfixable
{
	private static Boolean s_sorted; // 0x0
	private Text _actDescLabel; // 0x38
	private Text _pointTitle; // 0x40
	private Text _pointCnt; // 0x48
	private Text _timeDesc; // 0x50
	private Image _pointIcon; // 0x58
	private Text _helpBtnDesc; // 0x60
	private Slider _prg; // 0x68
	private Transform _itemContainer; // 0x70
	private ScrollRect _scrollView; // 0x78
	private Activity3D5Item _itemPrefab; // 0x80
	private Activity3D5HelpView _helpViewPrefab; // 0x88
	private List`1 m_itemList; // 0x90
	private Boolean m_adjustPrgWidth; // 0x98
	private Activity3D5HelpView m_helpView; // 0xa0
	private String m_activityId; // 0xa8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__SynPrg; // 0x10
	private static DelegateBridge __Hotfix0__CheckMissionStatus; // 0x18
	private static DelegateBridge __Hotfix0_OnOpenHelpPage; // 0x20
	private static DelegateBridge __Hotfix0__HandleHelpViewClose; // 0x28
	private static DelegateBridge __Hotfix0_OnScrollTo; // 0x30
	private static DelegateBridge __Hotfix0__CalculateItemScrollPrg; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3223158 VA: 0x759583b158
	public override Void OnEnter(String activityId) { }
	// RVA: 0x32241f8 VA: 0x759583c1f8
	private Void _SynPrg(List`1 collections, Int32 completeIdx, Int32 pointCurCnt, Int32 lastCanGetIdx) { }
	// RVA: 0x3223cec VA: 0x759583bcec
	private Void _CheckMissionStatus() { }
	// RVA: 0x3224708 VA: 0x759583c708
	public Void OnOpenHelpPage() { }
	// RVA: 0x32248b4 VA: 0x759583c8b4
	private Void _HandleHelpViewClose() { }
	// RVA: 0x3224948 VA: 0x759583c948
	public Void OnScrollTo() { }
	// RVA: 0x3224b34 VA: 0x759583cb34
	private Single _CalculateItemScrollPrg(Int32 itemIdx, Int32 totalCount) { }
	// RVA: 0x3224c70 VA: 0x759583cc70
	public Void .ctor() { }
	// RVA: 0x3224d34 VA: 0x759583cd34
	private Void <_CheckMissionStatus>b__18_0(ActivityMissionCheckResponse response) { }
}
```