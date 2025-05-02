# OpenServerMainView

**Namespace:** `Torappu.UI.Home.Activity`


## Fields

- `OpenServerChainLoginView _chainLoginView`

- `OpenServerTotalCheckInView _totalCheckInView`

- `OpenServerMissionView _missionView`

- `TwoStateToggle _missionTab`

- `TwoStateToggle _totalCheckInTab`

- `TwoStateToggle _chainLoginTab`

- `UICommonTrackPoint _missionTrack`

- `UICommonTrackPoint _chainLoginTrack`

- `UICommonTrackPoint _totalCheckInTrack`

- `TrackPointViewProperty m_chainLogin`

- `TrackPointViewProperty m_totalCheckIn`

- `TrackPointViewProperty m_mission`

- `UIStateFinder m_stateFinder`


## Methods

- `Void _UpdateTrackPoint()`

- `Void OnChainLoginClick()`

- `Void OnMissionClick()`

- `Void OnTotalCheckClick()`

- `Void OnBackBtnClick()`

- `Void SendGetChain(Int32)`

- `Void SendGetCheckIn(Int32)`

- `Void SendConfirmMissionRequest(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home.Activity
public class OpenServerMainView : OpenServerMainAbstractView
{
	private OpenServerChainLoginView _chainLoginView; // 0x18
	private OpenServerTotalCheckInView _totalCheckInView; // 0x20
	private OpenServerMissionView _missionView; // 0x28
	private TwoStateToggle _missionTab; // 0x30
	private TwoStateToggle _totalCheckInTab; // 0x38
	private TwoStateToggle _chainLoginTab; // 0x40
	private UICommonTrackPoint _missionTrack; // 0x48
	private UICommonTrackPoint _chainLoginTrack; // 0x50
	private UICommonTrackPoint _totalCheckInTrack; // 0x58
	private TrackPointViewProperty m_chainLogin; // 0x60
	private TrackPointViewProperty m_totalCheckIn; // 0x68
	private TrackPointViewProperty m_mission; // 0x70
	private UIStateFinder m_stateFinder; // 0x78
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_UpdateWithType; // 0x8
	private static DelegateBridge __Hotfix0__UpdateTrackPoint; // 0x10
	private static DelegateBridge __Hotfix0_OnChainLoginClick; // 0x18
	private static DelegateBridge __Hotfix0_OnMissionClick; // 0x20
	private static DelegateBridge __Hotfix0_OnTotalCheckClick; // 0x28
	private static DelegateBridge __Hotfix0_OnBackBtnClick; // 0x30
	private static DelegateBridge __Hotfix0_SendGetChain; // 0x38
	private static DelegateBridge __Hotfix0_SendGetCheckIn; // 0x40
	private static DelegateBridge __Hotfix0_SendConfirmMissionRequest; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x28512b8 VA: 0x7594e692b8
	public override Void Render() { }
	// RVA: 0x2851690 VA: 0x7594e69690
	public override Void UpdateWithType(OpenServerFuncType funcType) { }
	// RVA: 0x2851774 VA: 0x7594e69774
	private Void _UpdateTrackPoint() { }
	// RVA: 0x28513c0 VA: 0x7594e693c0
	public Void OnChainLoginClick() { }
	// RVA: 0x2851528 VA: 0x7594e69528
	public Void OnMissionClick() { }
	// RVA: 0x2851d08 VA: 0x7594e69d08
	public Void OnTotalCheckClick() { }
	// RVA: 0x2851e74 VA: 0x7594e69e74
	public Void OnBackBtnClick() { }
	// RVA: 0x2851f28 VA: 0x7594e69f28
	public Void SendGetChain(Int32 rewardIndex) { }
	// RVA: 0x2852034 VA: 0x7594e6a034
	public Void SendGetCheckIn(Int32 rewardIndex) { }
	// RVA: 0x2852140 VA: 0x7594e6a140
	public Void SendConfirmMissionRequest(String missionId) { }
	// RVA: 0x285224c VA: 0x7594e6a24c
	public Void .ctor() { }
}
```