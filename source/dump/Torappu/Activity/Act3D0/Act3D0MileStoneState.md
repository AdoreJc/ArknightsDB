# Act3D0MileStoneState

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `Act3D0MileStoneStateBean _stateBean`

- `Act3D0MileStoneHolder _view`

- `GameObject _topMenu`


## Methods

- `Void SendGachaRequest(String)`

- `Void _SendGachaRequest(String)`

- `Void <_SendGachaRequest>b__6_0(Act3D0MileStoneResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0MileStoneState : PopupFadeState
{
	private Act3D0MileStoneStateBean _stateBean; // 0x70
	private Act3D0MileStoneHolder _view; // 0x78
	private GameObject _topMenu; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_SendGachaRequest; // 0x10
	private static DelegateBridge __Hotfix0__SendGachaRequest; // 0x18
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x323074c VA: 0x759584874c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32307b4 VA: 0x75958487b4
	protected override Void OnEnter() { }
	// RVA: 0x3230b48 VA: 0x7595848b48
	public Void SendGachaRequest(String rewardId) { }
	// RVA: 0x3230bc8 VA: 0x7595848bc8
	private Void _SendGachaRequest(String rewardId) { }
	// RVA: 0x3230df8 VA: 0x7595848df8
	public static IEnumerator ReceiveItemsCoroutine(List`1 rewardList, Style style, Action onConfirm) { }
	// RVA: 0x3230efc VA: 0x7595848efc
	public Void .ctor() { }
	// RVA: 0x3230f6c VA: 0x7595848f6c
	private Void <_SendGachaRequest>b__6_0(Act3D0MileStoneResponse response) { }
	// RVA: 0x32311a0 VA: 0x75958491a0
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```