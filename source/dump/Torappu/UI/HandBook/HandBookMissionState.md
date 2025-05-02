# HandBookMissionState

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookMissionStateBean _stateBean`

- `HandBookMissionGroup _missionGroup`

- `Transform _missionContainer`

- `Boolean m_notFromEnterFlag`


## Methods

- `Void OnCollectionRequest(String)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void RefreshData()`

- `Void <OnCollectionRequest>b__5_0(ReceiveTeamCollectionRewardResponse)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPopup()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookMissionState : PopupFloatState
{
	private HandBookMissionStateBean _stateBean; // 0x70
	private HandBookMissionGroup _missionGroup; // 0x78
	private Transform _missionContainer; // 0x80
	private Boolean m_notFromEnterFlag; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnCollectionRequest; // 0x8
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_RefreshData; // 0x20
	private static DelegateBridge __Hotfix0_OnPopup; // 0x28
	private static DelegateBridge __Hotfix0_OnExit; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2e9db34 VA: 0x75954b5b34
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2e9db9c VA: 0x75954b5b9c
	public Void OnCollectionRequest(String id) { }
	// RVA: 0x2e9dd88 VA: 0x75954b5d88
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x2e9de80 VA: 0x75954b5e80
	protected override Void OnResume() { }
	// RVA: 0x2e9e42c VA: 0x75954b642c
	public Void RefreshData() { }
	// RVA: 0x2e9e908 VA: 0x75954b6908
	protected override Void OnPopup() { }
	// RVA: 0x2e9e97c VA: 0x75954b697c
	protected override Void OnExit() { }
	// RVA: 0x2e9e9f8 VA: 0x75954b69f8
	public Void .ctor() { }
	// RVA: 0x2e9ea68 VA: 0x75954b6a68
	private Void <OnCollectionRequest>b__5_0(ReceiveTeamCollectionRewardResponse response) { }
	// RVA: 0x2e9eae4 VA: 0x75954b6ae4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2e9eaec VA: 0x75954b6aec
	private Void <>xLuaBaseProxy_OnPopup() { }
	// RVA: 0x2e9eaf4 VA: 0x75954b6af4
	private Void <>xLuaBaseProxy_OnExit() { }
}
```