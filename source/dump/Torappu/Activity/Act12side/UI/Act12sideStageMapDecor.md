# Act12sideStageMapDecor

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Act12sideMapZoneGroupView _zoneGroupView`

- `UICommonTrackPoint _missionTrackPoint`

- `UICommonTrackPoint _charmRecycleTrackPoint`

- `UICommonTrackPoint _charmFirstGotTrackPoint`

- `GameObject _btnCharmLockGo`

- `Text _textCharmLockHint`

- `Button _btnCharm`

- `Boolean m_hasInited`

- `AudioClickPlayer m_btnCharmAudio`


## Methods

- `Void _InitIfNot()`

- `Void EventOnCharmBtnClicked()`

- `Void EventOnResearchBtnClicked()`

- `Void EventOnZoneBtnClicked(String)`

- `Void _AddTopToActStateEngine()`

- `Void <>xLuaBaseProxy_OnLoaded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class Act12sideStageMapDecor : ActivityStageSingleComponent
{
	private Act12sideMapZoneGroupView _zoneGroupView; // 0x20
	private UICommonTrackPoint _missionTrackPoint; // 0x28
	private UICommonTrackPoint _charmRecycleTrackPoint; // 0x30
	private UICommonTrackPoint _charmFirstGotTrackPoint; // 0x38
	private GameObject _btnCharmLockGo; // 0x40
	private Text _textCharmLockHint; // 0x48
	private Button _btnCharm; // 0x50
	private Boolean m_hasInited; // 0x58
	private AudioClickPlayer m_btnCharmAudio; // 0x60
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_EventOnCharmBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnResearchBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_EventOnZoneBtnClicked; // 0x20
	private static DelegateBridge __Hotfix0__AddTopToActStateEngine; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x344f7c4 VA: 0x7595a677c4
	protected override Void OnLoaded() { }
	// RVA: 0x344fa20 VA: 0x7595a67a20
	private Void _InitIfNot() { }
	// RVA: 0x344fad4 VA: 0x7595a67ad4
	public Void EventOnCharmBtnClicked() { }
	// RVA: 0x344fb54 VA: 0x7595a67b54
	public Void EventOnResearchBtnClicked() { }
	// RVA: 0x344fbd4 VA: 0x7595a67bd4
	public Void EventOnZoneBtnClicked(String zoneId) { }
	// RVA: 0x VA: 0x0
	private Void _AddTopToActStateEngine() { }
	// RVA: 0x344fcfc VA: 0x7595a67cfc
	public Void .ctor() { }
	// RVA: 0x344fd6c VA: 0x7595a67d6c
	private Void <>xLuaBaseProxy_OnLoaded() { }
}
```