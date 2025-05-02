# Act12D6MileStoneState

**Namespace:** `Torappu.Activity.Act12D6`


## Fields

- `Act12D6MileStoneStateBean _stateBean`

- `Act12D6MileStoneHolder _view`

- `RectTransform _topMenuContainer`

- `CommonTopMenu m_topMenu`

- `Boolean m_inited`

- `String m_cacheTransId`


## Methods

- `Void SendItemRequest(String)`

- `Void SendItemTryBestRequest()`

- `Void _SendItemTryBestRequest()`

- `Void _SendItemRequest(String)`

- `Void _InitIfNot()`

- `Void <_SendItemTryBestRequest>b__10_0(Act12D6MileStoneRewardTryBestResponse)`

- `Void <_SendItemRequest>b__11_0(Act12D6MileStoneRewardResponse)`

- `Void <_InitIfNot>b__13_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12D6
public class Act12D6MileStoneState : PopupFadeState, IHotfixable
{
	private Act12D6MileStoneStateBean _stateBean; // 0x70
	private Act12D6MileStoneHolder _view; // 0x78
	private RectTransform _topMenuContainer; // 0x80
	private CommonTopMenu m_topMenu; // 0x88
	private Boolean m_inited; // 0x90
	private String m_cacheTransId; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_SendItemRequest; // 0x10
	private static DelegateBridge __Hotfix0_SendItemTryBestRequest; // 0x18
	private static DelegateBridge __Hotfix0__SendItemTryBestRequest; // 0x20
	private static DelegateBridge __Hotfix0__SendItemRequest; // 0x28
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3470f48 VA: 0x7595a88f48
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3470fb0 VA: 0x7595a88fb0
	protected override Void OnEnter() { }
	// RVA: 0x3471818 VA: 0x7595a89818
	public Void SendItemRequest(String rewardId) { }
	// RVA: 0x3471af0 VA: 0x7595a89af0
	public Void SendItemTryBestRequest() { }
	// RVA: 0x3471b58 VA: 0x7595a89b58
	private Void _SendItemTryBestRequest() { }
	// RVA: 0x3471898 VA: 0x7595a89898
	private Void _SendItemRequest(String rewardId) { }
	// RVA: 0x3471d90 VA: 0x7595a89d90
	public static IEnumerator ReceiveItemsCoroutine(List`1 rewardList, Style style, Action onConfirm) { }
	// RVA: 0x3471050 VA: 0x7595a89050
	private Void _InitIfNot() { }
	// RVA: 0x3471e94 VA: 0x7595a89e94
	public Void .ctor() { }
	// RVA: 0x3471f3c VA: 0x7595a89f3c
	private Void <_SendItemTryBestRequest>b__10_0(Act12D6MileStoneRewardTryBestResponse response) { }
	// RVA: 0x34720f8 VA: 0x7595a8a0f8
	private Void <_SendItemRequest>b__11_0(Act12D6MileStoneRewardResponse response) { }
	// RVA: 0x34721dc VA: 0x7595a8a1dc
	private Void <_InitIfNot>b__13_0() { }
	// RVA: 0x34721e4 VA: 0x7595a8a1e4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```