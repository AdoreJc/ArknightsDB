# Act5D1StageEntry

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Act5D1StageEntryButtonObj _periodObj`

- `Act5D1StageEntryButtonObj _perpetualObj`

- `UIActTrackPoint _missionTrackPoint`

- `Text _coinCount`

- `Text _coinName`

- `GameObject _periodTimeOutButton`

- `GameObject _perpetualOutButton`

- `Button _missionBtn`

- `Button _shopBtn`

- `TrackPointViewProperty m_missionTrackPoint`

- `Boolean m_isInited`


## Methods

- `Void _InitTrack()`

- `Void OnBannedEveryButton()`

- `Void OnBannedStageButton()`

- `Void _RenderInfoWithData()`

- `Void InitData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1StageEntry : ActivityStageSingleComponent, IHotfixable
{
	private Act5D1StageEntryButtonObj _periodObj; // 0x20
	private Act5D1StageEntryButtonObj _perpetualObj; // 0x28
	private UIActTrackPoint _missionTrackPoint; // 0x30
	private Text _coinCount; // 0x38
	private Text _coinName; // 0x40
	private GameObject _periodTimeOutButton; // 0x48
	private GameObject _perpetualOutButton; // 0x50
	private Button _missionBtn; // 0x58
	private Button _shopBtn; // 0x60
	private TrackPointViewProperty m_missionTrackPoint; // 0x68
	private Boolean m_isInited; // 0x70
	private static DelegateBridge __Hotfix0__InitTrack; // 0x0
	private static DelegateBridge __Hotfix0_OnBannedEveryButton; // 0x8
	private static DelegateBridge __Hotfix0_OnBannedStageButton; // 0x10
	private static DelegateBridge __Hotfix0__RenderInfoWithData; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31c8020 VA: 0x75957e0020
	private Void _InitTrack() { }
	// RVA: 0x31c6000 VA: 0x75957de000
	public Void OnBannedEveryButton() { }
	// RVA: 0x31c5e20 VA: 0x75957dde20
	public Void OnBannedStageButton() { }
	// RVA: 0x31c80c8 VA: 0x75957e00c8
	private Void _RenderInfoWithData() { }
	// RVA: 0x31c877c VA: 0x75957e077c
	public Void InitData() { }
	// RVA: 0x31c885c VA: 0x75957e085c
	public Void .ctor() { }
}
```