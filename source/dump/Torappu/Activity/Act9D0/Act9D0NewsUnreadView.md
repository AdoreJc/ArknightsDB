# Act9D0NewsUnreadView

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `GameObject _unreadObj`

- `GameObject _noUnreadObj`

- `GameObject _unreadTitle`

- `Text _unreadCount`

- `UIAnimationLocation _showAnim`

- `CoroutineOnEnable m_displayCoroutine`


## Methods

- `Void OnEnable()`

- `Void OnDisable()`

- `Void _OnNewsUpdated(Object)`

- `Void _OnAnimationPlay()`

- `IEnumerator _DisplayCoroutine()`

- `Void _StatusBegin()`

- `Void _StatusEnd()`

- `Void EventOnNewsClicked()`

- `Void <>xLuaBaseProxy_OnLoaded()`

- `Void <>xLuaBaseProxy_BeforeUnload()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0NewsUnreadView : ActivityStageComponent, IHotfixable
{
	private GameObject _unreadObj; // 0x20
	private GameObject _noUnreadObj; // 0x28
	private GameObject _unreadTitle; // 0x30
	private Text _unreadCount; // 0x38
	private UIAnimationLocation _showAnim; // 0x40
	private CoroutineOnEnable m_displayCoroutine; // 0x50
	private const String UNREAD_ANIM; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_OnDisable; // 0x8
	private static DelegateBridge __Hotfix0_OnLoaded; // 0x10
	private static DelegateBridge __Hotfix0_BeforeUnload; // 0x18
	private static DelegateBridge __Hotfix0__OnNewsUpdated; // 0x20
	private static DelegateBridge __Hotfix0__OnAnimationPlay; // 0x28
	private static DelegateBridge __Hotfix0__DisplayCoroutine; // 0x30
	private static DelegateBridge __Hotfix0__StatusBegin; // 0x38
	private static DelegateBridge __Hotfix0__StatusEnd; // 0x40
	private static DelegateBridge __Hotfix0_EventOnNewsClicked; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x31a95f4 VA: 0x75957c15f4
	private Void OnEnable() { }
	// RVA: 0x31a9a00 VA: 0x75957c1a00
	private Void OnDisable() { }
	// RVA: 0x31a9b28 VA: 0x75957c1b28
	protected override Void OnLoaded() { }
	// RVA: 0x31a9cc0 VA: 0x75957c1cc0
	protected override Void BeforeUnload() { }
	// RVA: 0x31a9660 VA: 0x75957c1660
	private Void _OnNewsUpdated(Object _) { }
	// RVA: 0x31a9e58 VA: 0x75957c1e58
	private Void _OnAnimationPlay() { }
	// RVA: 0x31a9f38 VA: 0x75957c1f38
	private IEnumerator _DisplayCoroutine() { }
	// RVA: 0x31aa00c VA: 0x75957c200c
	private Void _StatusBegin() { }
	// RVA: 0x31a9a68 VA: 0x75957c1a68
	private Void _StatusEnd() { }
	// RVA: 0x31aa0cc VA: 0x75957c20cc
	public Void EventOnNewsClicked() { }
	// RVA: 0x31aa1b4 VA: 0x75957c21b4
	public Void .ctor() { }
	// RVA: 0x31aa224 VA: 0x75957c2224
	private Void <>xLuaBaseProxy_OnLoaded() { }
	// RVA: 0x31aa22c VA: 0x75957c222c
	private Void <>xLuaBaseProxy_BeforeUnload() { }
}
```