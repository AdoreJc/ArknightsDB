# FifthAnnivExploreMissionDialog

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `FifthAnnivExploreMissionView _view`

- `FifthAnnivExploreMissionProperty m_cachedProperty`


## Methods

- `Void EventOnMissionObjClicked(String)`

- `Void EventOnCollectAll()`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void OnBackEvent()`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreMissionDialog : UICompDialog`1
{
	private FifthAnnivExploreMissionView _view; // 0x48
	private FifthAnnivExploreMissionProperty m_cachedProperty; // 0x50
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0_EventOnMissionObjClicked; // 0x10
	private static DelegateBridge __Hotfix0_EventOnCollectAll; // 0x18
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0x20
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x292ad68 VA: 0x7594f42d68
	protected override Void OnInit() { }
	// RVA: 0x292af4c VA: 0x7594f42f4c
	protected override Void OnRender(Option input) { }
	// RVA: 0x292b988 VA: 0x7594f43988
	public Void EventOnMissionObjClicked(String missionId) { }
	// RVA: 0x292bd0c VA: 0x7594f43d0c
	public Void EventOnCollectAll() { }
	// RVA: 0x292c254 VA: 0x7594f44254
	private IEnumerator _ReceiveItemsCoroutine(List`1 rewardList) { }
	// RVA: 0x292c33c VA: 0x7594f4433c
	public Void OnBackEvent() { }
	// RVA: 0x292c410 VA: 0x7594f44410
	public Void .ctor() { }
	// RVA: 0x292c4a0 VA: 0x7594f444a0
	private Void <>xLuaBaseProxy_OnInit() { }
}
```