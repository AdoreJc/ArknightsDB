# Act5D0StageEntry

**Namespace:** `Torappu.Activity.Act5D0`


## Fields

- `UIActTrackPoint _mileStoneTrackPoint`

- `Transform _topMenuContainer`

- `Text _actTime`

- `Text _actDesc`

- `Animator _brushAnim`

- `Text _actLeftTime`

- `Text _mileStoneToken`

- `GameObject _exBlock`

- `Animator _animMission`

- `Animator _animMilestone`

- `Animator _animBrush`

- `Animator _animBlink`

- `Animator _animToDowntown`

- `Animator _animToEx`

- `Animator _animBlockToEx`

- `Animator _animRetro`

- `CommonTopMenu m_topMenu`

- `Boolean m_isLoaded`

- `Boolean m_isBindedToParent`

- `TrackPointViewProperty m_mileStoneRedPoint`

- `Boolean m_isInited`


## Methods

- `Void OnEnable()`

- `Void NotifyBackToFloatEmptyState()`

- `Void _TryPlayAni()`

- `Void _InitTopMenu()`

- `Void _InitData()`

- `Void <>xLuaBaseProxy_OnBindToParent()`

- `Void <>xLuaBaseProxy_OnLoaded()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D0
public class Act5D0StageEntry : ActivityStageSingleComponent
{
	private UIActTrackPoint _mileStoneTrackPoint; // 0x20
	private Transform _topMenuContainer; // 0x28
	private Text _actTime; // 0x30
	private Text _actDesc; // 0x38
	private Animator _brushAnim; // 0x40
	private Text _actLeftTime; // 0x48
	private Text _mileStoneToken; // 0x50
	private GameObject _exBlock; // 0x58
	private Animator _animMission; // 0x60
	private Animator _animMilestone; // 0x68
	private Animator _animBrush; // 0x70
	private Animator _animBlink; // 0x78
	private Animator _animToDowntown; // 0x80
	private Animator _animToEx; // 0x88
	private Animator _animBlockToEx; // 0x90
	private Animator _animRetro; // 0x98
	private CommonTopMenu m_topMenu; // 0xa0
	private const String START_ANIM_KEY; // 0x0
	private Boolean m_isLoaded; // 0xa8
	private Boolean m_isBindedToParent; // 0xa9
	private TrackPointViewProperty m_mileStoneRedPoint; // 0xb0
	private Boolean m_isInited; // 0xb8
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_NotifyBackToFloatEmptyState; // 0x8
	private static DelegateBridge __Hotfix0_OnBindToParent; // 0x10
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x18
	private static DelegateBridge __Hotfix0__TryPlayAni; // 0x20
	private static DelegateBridge __Hotfix0__InitTopMenu; // 0x28
	private static DelegateBridge __Hotfix0__InitData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x31bc7f4 VA: 0x75957d47f4
	private Void OnEnable() { }
	// RVA: 0x31bc9ec VA: 0x75957d49ec
	public Void NotifyBackToFloatEmptyState() { }
	// RVA: 0x31bca80 VA: 0x75957d4a80
	protected override Void OnBindToParent() { }
	// RVA: 0x31bcafc VA: 0x75957d4afc
	protected override Void OnLoaded() { }
	// RVA: 0x31bc85c VA: 0x75957d485c
	private Void _TryPlayAni() { }
	// RVA: 0x31bcb88 VA: 0x75957d4b88
	private Void _InitTopMenu() { }
	// RVA: 0x31bcdb8 VA: 0x75957d4db8
	private Void _InitData() { }
	// RVA: 0x31bd770 VA: 0x75957d5770
	public Void .ctor() { }
	// RVA: 0x31bd820 VA: 0x75957d5820
	private Void <>xLuaBaseProxy_OnBindToParent() { }
	// RVA: 0x31bd828 VA: 0x75957d5828
	private Void <>xLuaBaseProxy_OnLoaded() { }
}
```