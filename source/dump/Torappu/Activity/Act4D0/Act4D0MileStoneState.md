# Act4D0MileStoneState

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `Act4D0MileStoneStateBean _stateBean`

- `Act4D0MileStoneHolder _view`

- `GameObject _topMenu`

- `String m_cacheTransId`


## Methods

- `Void SendItemRequest(String)`

- `Void _SendItemRequest(String)`

- `Void SendStoryRequest(String)`

- `Void _SendStoryRequest(String)`

- `Void <RegisterToDataListener>b__6_0(IStateBean)`

- `Void <_SendItemRequest>b__8_0(Act4D0MileStoneItemResponse)`

- `Void <_SendStoryRequest>b__10_0(Act4D0MileStoneStoryResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0MileStoneState : PopupFadeState
{
	private Act4D0MileStoneStateBean _stateBean; // 0x70
	private Act4D0MileStoneHolder _view; // 0x78
	private GameObject _topMenu; // 0x80
	private String m_cacheTransId; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_SendItemRequest; // 0x18
	private static DelegateBridge __Hotfix0__SendItemRequest; // 0x20
	private static DelegateBridge __Hotfix0_SendStoryRequest; // 0x28
	private static DelegateBridge __Hotfix0__SendStoryRequest; // 0x30
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x31dcb7c VA: 0x75957f4b7c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31dcbe4 VA: 0x75957f4be4
	protected override Void OnEnter() { }
	// RVA: 0x31dd7c8 VA: 0x75957f57c8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x31dd940 VA: 0x75957f5940
	public Void SendItemRequest(String rewardId) { }
	// RVA: 0x31dd9c0 VA: 0x75957f59c0
	private Void _SendItemRequest(String rewardId) { }
	// RVA: 0x31ddbf0 VA: 0x75957f5bf0
	public Void SendStoryRequest(String rewardId) { }
	// RVA: 0x31ddc70 VA: 0x75957f5c70
	private Void _SendStoryRequest(String rewardId) { }
	// RVA: 0x31ddea0 VA: 0x75957f5ea0
	public static IEnumerator ReceiveItemsCoroutine(List`1 rewardList, Style style, Action onConfirm) { }
	// RVA: 0x31ddfa4 VA: 0x75957f5fa4
	public Void .ctor() { }
	// RVA: 0x31de04c VA: 0x75957f604c
	private Void <RegisterToDataListener>b__6_0(IStateBean stateBean) { }
	// RVA: 0x31de1a4 VA: 0x75957f61a4
	private Void <_SendItemRequest>b__8_0(Act4D0MileStoneItemResponse response) { }
	// RVA: 0x31de380 VA: 0x75957f6380
	private Void <_SendStoryRequest>b__10_0(Act4D0MileStoneStoryResponse response) { }
	// RVA: 0x31de490 VA: 0x75957f6490
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x31de498 VA: 0x75957f6498
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```