# SiracusaOperaCommentState

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `SiracusaOperaCommentView _view`

- `Boolean m_isInited`

- `SiracusaOperaCommentStateBean m_stateBean`

- `String m_cachedGroupId`

- `String m_cachedCharCardId`


## Methods

- `Void _OnReward(IStateBean)`

- `Void _InitIfNot()`

- `Void _UpdateProp(Boolean)`

- `Void _LikeComment(String)`

- `Void EventOnCommentLiked(String)`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaCommentState : PopupFadeState
{
	private SiracusaOperaCommentView _view; // 0x70
	private Boolean m_isInited; // 0x78
	private SiracusaOperaCommentStateBean m_stateBean; // 0x80
	private String m_cachedGroupId; // 0x88
	private String m_cachedCharCardId; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__OnReward; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__UpdateProp; // 0x30
	private static DelegateBridge __Hotfix0__LikeComment; // 0x38
	private static DelegateBridge __Hotfix0_EventOnCommentLiked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x23f71dc VA: 0x7594a0f1dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x23f7244 VA: 0x7594a0f244
	protected override Void OnResume() { }
	// RVA: 0x23f73c8 VA: 0x7594a0f3c8
	protected override Void OnEnter() { }
	// RVA: 0x23f75e8 VA: 0x7594a0f5e8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x23f7760 VA: 0x7594a0f760
	private Void _OnReward(IStateBean stateBean) { }
	// RVA: 0x23f7448 VA: 0x7594a0f448
	private Void _InitIfNot() { }
	// RVA: 0x23f72bc VA: 0x7594a0f2bc
	private Void _UpdateProp(Boolean isInit) { }
	// RVA: 0x23f7854 VA: 0x7594a0f854
	private Void _LikeComment(String commentId) { }
	// RVA: 0x23f7bb4 VA: 0x7594a0fbb4
	public Void EventOnCommentLiked(String commentId) { }
	// RVA: 0x23f7e08 VA: 0x7594a0fe08
	public Void .ctor() { }
	// RVA: 0x23f7eb4 VA: 0x7594a0feb4
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x23f7ebc VA: 0x7594a0febc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x23f7ec4 VA: 0x7594a0fec4
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```