# MainMissionSimpleView

**Namespace:** `Torappu.UI.Mission`


## Fields

- `MainMissionTask _mainMissionTask`

- `Image _backImage`

- `Transform _rightPanel`

- `RectTransform _backPanel`

- `MainMissionConfirmAllTask _confirmAll`

- `Single _defaultTop`

- `Single _confirmAllTop`

- `GameObject _noSubMissionHint`

- `GameObject _haveUnlockedSubMission`

- `MainMissionTask _taskPrefab`

- `MainMissionLockedTask _lockedTaskPrefab`

- `UIRecycleLayoutGroup _layoutGroup`

- `UIStringEvent _onSpreadFold`

- `UIStringEvent _onHideFold`

- `MainMissionTaskLoopAdapter m_adapter`

- `String m_imagePathCache`

- `MainMissionConfirmAllTask m_confirmAll`


## Methods

- `Void _InitIfNot()`

- `Void OnSpreadFold(String)`

- `Void OnHideFold(String)`

- `Void _UpdateMainMission(MissionModel)`

- `Int32 _SortSubMission(MainMissionTaskDataWrapper, MainMissionTaskDataWrapper)`

- `Void _RefreshView()`

- `Void <>xLuaBaseProxy_RefreshView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Mission
public class MainMissionSimpleView : MissionSinglePage
{
	private MainMissionTask _mainMissionTask; // 0x30
	private Image _backImage; // 0x38
	private Transform _rightPanel; // 0x40
	private RectTransform _backPanel; // 0x48
	private MainMissionConfirmAllTask _confirmAll; // 0x50
	private Single _defaultTop; // 0x58
	private Single _confirmAllTop; // 0x5c
	private GameObject _noSubMissionHint; // 0x60
	private GameObject _haveUnlockedSubMission; // 0x68
	private MainMissionTask _taskPrefab; // 0x70
	private MainMissionLockedTask _lockedTaskPrefab; // 0x78
	private UIRecycleLayoutGroup _layoutGroup; // 0x80
	private UIStringEvent _onSpreadFold; // 0x88
	private UIStringEvent _onHideFold; // 0x90
	private MainMissionTaskLoopAdapter m_adapter; // 0x98
	private String m_imagePathCache; // 0xa0
	private MainMissionConfirmAllTask m_confirmAll; // 0xa8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnSpreadFold; // 0x8
	private static DelegateBridge __Hotfix0_OnHideFold; // 0x10
	private static DelegateBridge __Hotfix0__UpdateMainMission; // 0x18
	private static DelegateBridge __Hotfix0__SortSubMission; // 0x20
	private static DelegateBridge __Hotfix0_RefreshView; // 0x28
	private static DelegateBridge __Hotfix0__RefreshView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x273cd6c VA: 0x7594d54d6c
	private Void _InitIfNot() { }
	// RVA: 0x273cf48 VA: 0x7594d54f48
	public Void OnSpreadFold(String foldId) { }
	// RVA: 0x273cfd8 VA: 0x7594d54fd8
	public Void OnHideFold(String foldId) { }
	// RVA: 0x273d068 VA: 0x7594d55068
	private Void _UpdateMainMission(MissionModel stateBean) { }
	// RVA: 0x273dad4 VA: 0x7594d55ad4
	private Int32 _SortSubMission(MainMissionTaskDataWrapper lhs, MainMissionTaskDataWrapper rhs) { }
	// RVA: 0x273dbec VA: 0x7594d55bec
	protected override Void RefreshView() { }
	// RVA: 0x273dc68 VA: 0x7594d55c68
	private Void _RefreshView() { }
	// RVA: 0x273e274 VA: 0x7594d56274
	public Void .ctor() { }
	// RVA: 0x273e2f0 VA: 0x7594d562f0
	private Void <>xLuaBaseProxy_RefreshView() { }
}
```