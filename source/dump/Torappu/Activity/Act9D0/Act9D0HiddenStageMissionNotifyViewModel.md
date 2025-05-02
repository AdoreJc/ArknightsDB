# Act9D0HiddenStageMissionNotifyViewModel

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `String rawActId`

- `HiddenStageMissionNotifyState notifyState`

- `String stageId`

- `String textContent`


## Methods

- `Void LoadData(HiddenStageMissionPushMsg, String)`

- `String _GenRawActId(String)`

- `String _GenToastWithMsg(HiddenStageMissionPushMsg, String)`

- `HiddenStageMissionNotifyState _GetNotifyStage(PlayerHiddenStage, HiddenStageMissionPushMsg, ActivityHiddenStageData, out, out)`

- `String _GetToastByState(HiddenStageMissionNotifyState, String, Int32, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0HiddenStageMissionNotifyViewModel : IHotfixable
{
	public String rawActId; // 0x10
	public HiddenStageMissionNotifyState notifyState; // 0x18
	public String stageId; // 0x20
	public String textContent; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__GenRawActId; // 0x8
	private static DelegateBridge __Hotfix0__GenToastWithMsg; // 0x10
	private static DelegateBridge __Hotfix0__GetNotifyStage; // 0x18
	private static DelegateBridge __Hotfix0__GetToastByState; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x31abfa4 VA: 0x75957c3fa4
	public Void LoadData(HiddenStageMissionPushMsg payLoad, String funcId) { }
	// RVA: 0x31ac0ac VA: 0x75957c40ac
	private String _GenRawActId(String funcId) { }
	// RVA: 0x31ac20c VA: 0x75957c420c
	private String _GenToastWithMsg(HiddenStageMissionPushMsg payload, String actId) { }
	// RVA: 0x31ac310 VA: 0x75957c4310
	private HiddenStageMissionNotifyState _GetNotifyStage(PlayerHiddenStage playerData, HiddenStageMissionPushMsg payload, ActivityHiddenStageData hiddenData, out Int32 finishendCnt, out Int32 totalCnt) { }
	// RVA: 0x31ac508 VA: 0x75957c4508
	private String _GetToastByState(HiddenStageMissionNotifyState state, String actId, Int32 progress, Int32 total) { }
	// RVA: 0x31ac828 VA: 0x75957c4828
	public Void .ctor() { }
}
```