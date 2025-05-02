# MissionBookSimpleView

**Namespace:** `Torappu.UI.Mission`


## Fields

- `MissionBookTagTab _tagPrefab`

- `Transform _bookContainer`

- `Transform _tagContainer`

- `Canvas _canvas`

- `Boolean m_initFlag`

- `MissionModel m_stateBean`


## Methods

- `Void RefreshFlag(MissionType)`

- `Void _Init(MissionModel)`

- `Boolean _NeedShowTabTrackPoint(MissionPageType, MissionModel)`

- `Boolean _IsStartMissionGroupComplete(MissionPageType, MissionModel)`

- `Void _RefreshPageOfType(MissionType)`

- `Void <>xLuaBaseProxy_Init(MissionModel, Nullable`1)`

- `Void <>xLuaBaseProxy_DealWithState(Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MissionBookSimpleView : MissionBookViewBase
{
	private const Int32 DEFAULT_INITIAL_PAGE_INDEX; // 0x0
	private MissionBookPageSimpleConfig[] _pageConfig; // 0x18
	private MissionBookTagTab _tagPrefab; // 0x20
	private Transform _bookContainer; // 0x28
	private Transform _tagContainer; // 0x30
	private Canvas _canvas; // 0x38
	private List`1 m_pageList; // 0x40
	private List`1 m_tagList; // 0x48
	private Boolean m_initFlag; // 0x50
	private Nullable`1 m_initPageType; // 0x54
	private MissionModel m_stateBean; // 0x60
	private static DelegateBridge __Hotfix0_RefreshFlag; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0__Init; // 0x10
	private static DelegateBridge __Hotfix0_EnumMissionViewModel; // 0x18
	private static DelegateBridge __Hotfix0__NeedShowTabTrackPoint; // 0x20
	private static DelegateBridge __Hotfix0__IsStartMissionGroupComplete; // 0x28
	private static DelegateBridge __Hotfix0__RefreshPageOfType; // 0x30
	private static DelegateBridge __Hotfix0_DealWithState; // 0x38
	private static DelegateBridge __Hotfix0__ConvertTypeToTabString; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x273f774 VA: 0x7594d57774
	public Void RefreshFlag(MissionType missionType) { }
	// RVA: 0x27403c4 VA: 0x7594d583c4
	public override Void Init(MissionModel stateBean, Nullable`1 initMissionPage) { }
	// RVA: 0x273fa68 VA: 0x7594d57a68
	private Void _Init(MissionModel stateBean) { }
	// RVA: 0x2740bf4 VA: 0x7594d58bf4
	private static IEnumerable`1 EnumMissionViewModel(MissionPageType pageType, MissionModel model) { }
	// RVA: 0x27407dc VA: 0x7594d587dc
	private Boolean _NeedShowTabTrackPoint(MissionPageType pageType, MissionModel model) { }
	// RVA: 0x2740cfc VA: 0x7594d58cfc
	private Boolean _IsStartMissionGroupComplete(MissionPageType pageType, MissionModel model) { }
	// RVA: 0x273fe54 VA: 0x7594d57e54
	private Void _RefreshPageOfType(MissionType type) { }
	// RVA: 0x2740da0 VA: 0x7594d58da0
	public override Void DealWithState(Int32 index, Boolean isInit) { }
	// RVA: 0x2740460 VA: 0x7594d58460
	private static String _ConvertTypeToTabString(MissionPageType type) { }
	// RVA: 0x2740f9c VA: 0x7594d58f9c
	public Void .ctor() { }
	// RVA: 0x274111c VA: 0x7594d5911c
	private Void <>xLuaBaseProxy_Init(MissionModel P0, Nullable`1 P1) { }
	// RVA: 0x27411a0 VA: 0x7594d591a0
	private Void <>xLuaBaseProxy_DealWithState(Int32 P0, Boolean P1) { }
}
```