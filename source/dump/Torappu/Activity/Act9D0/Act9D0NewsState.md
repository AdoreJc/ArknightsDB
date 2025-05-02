# Act9D0NewsState

**Namespace:** `Torappu.Activity.Act9D0`


## Fields

- `Act9D0NewsView _view`

- `AnimationWrapper _groupAnimation`

- `AnimationWrapper _detailAnimation`

- `Act9D0NewsStateBean m_stateBean`

- `String m_cachedNewsId`

- `Boolean m_detailOut`


## Methods

- `Void EventOnNewsObjClicked(String)`

- `Void _RenderDetailPart(String)`

- `Void _ResetAnimation()`

- `Void ClosePage()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act9D0
public class Act9D0NewsState : PopupFloatState
{
	private Act9D0NewsView _view; // 0x70
	private AnimationWrapper _groupAnimation; // 0x78
	private AnimationWrapper _detailAnimation; // 0x80
	private Act9D0NewsStateBean m_stateBean; // 0x88
	private String m_cachedNewsId; // 0x90
	private const String NEWS_LIST_ANIM; // 0x0
	private const String NEWS_DETAIL_ANIM; // 0x0
	private Boolean m_detailOut; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_EventOnNewsObjClicked; // 0x10
	private static DelegateBridge __Hotfix0__RenderDetailPart; // 0x18
	private static DelegateBridge __Hotfix0__ResetAnimation; // 0x20
	private static DelegateBridge __Hotfix0_ClosePage; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31a1bbc VA: 0x75957b9bbc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31a1c24 VA: 0x75957b9c24
	protected override Void OnEnter() { }
	// RVA: 0x31a1dc8 VA: 0x75957b9dc8
	public Void EventOnNewsObjClicked(String newsId) { }
	// RVA: 0x31a2114 VA: 0x75957ba114
	private Void _RenderDetailPart(String newsId) { }
	// RVA: 0x31a2318 VA: 0x75957ba318
	private Void _ResetAnimation() { }
	// RVA: 0x31a23d4 VA: 0x75957ba3d4
	public Void ClosePage() { }
	// RVA: 0x31a2494 VA: 0x75957ba494
	public Void .ctor() { }
	// RVA: 0x31a257c VA: 0x75957ba57c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```