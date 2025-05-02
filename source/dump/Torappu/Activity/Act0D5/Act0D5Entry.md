# Act0D5Entry

**Namespace:** `Torappu.Activity.Act0D5`


## Fields

- `Transform _container`

- `ActivityCommonMissionItem _missionItem`

- `GameObject _allFinishPart`

- `GameObject _notAllFinishPart`

- `GameObject _btnReceived`

- `GameObject _btnLocked`

- `GameObject _btnAble`

- `Single maxLength`

- `RectTransform _yellowBar`

- `Text _remainTime`

- `MissionGroup m_missionGroup`


## Methods

- `Void _RenderMissionGroup(MissionGroup)`

- `Void SendMissionRequest(String)`

- `Void SendMissionGroupRequest()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void <SendMissionRequest>b__13_0(ActivityConfirmMissionResponse)`

- `Void <SendMissionGroupRequest>b__14_0(ActivityConfirmMissionGroupResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act0D5
public class Act0D5Entry : ActivityCommonMissionEntry, IHotfixable
{
	private Transform _container; // 0x38
	private ActivityCommonMissionItem _missionItem; // 0x40
	private GameObject _allFinishPart; // 0x48
	private GameObject _notAllFinishPart; // 0x50
	private GameObject _btnReceived; // 0x58
	private GameObject _btnLocked; // 0x60
	private GameObject _btnAble; // 0x68
	private Single maxLength; // 0x70
	private RectTransform _yellowBar; // 0x78
	private Text _remainTime; // 0x80
	private MissionGroup m_missionGroup; // 0x88
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__RenderMissionGroup; // 0x8
	private static DelegateBridge __Hotfix0_SendMissionRequest; // 0x10
	private static DelegateBridge __Hotfix0_SendMissionGroupRequest; // 0x18
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x34927f8 VA: 0x7595aaa7f8
	public override Void OnEnter(String activityId) { }
	// RVA: 0x3492e5c VA: 0x7595aaae5c
	private Void _RenderMissionGroup(MissionGroup missionGroup) { }
	// RVA: 0x3493494 VA: 0x7595aab494
	public Void SendMissionRequest(String missionId) { }
	// RVA: 0x34936c4 VA: 0x7595aab6c4
	public Void SendMissionGroupRequest() { }
	// RVA: 0x34938ec VA: 0x7595aab8ec
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x34939d4 VA: 0x7595aab9d4
	public Void .ctor() { }
	// RVA: 0x3493a50 VA: 0x7595aaba50
	private Void <SendMissionRequest>b__13_0(ActivityConfirmMissionResponse response) { }
	// RVA: 0x3493ad8 VA: 0x7595aabad8
	private Void <SendMissionGroupRequest>b__14_0(ActivityConfirmMissionGroupResponse response) { }
}
```