# PlayerAvatarDisplayState

**Namespace:** `Torappu.UI.PlayerAvatar`


## Fields

- `PlayerAvatarDisplayView _view`

- `RectTransform _backClick`

- `PlayerAvatarDisplayStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void CloseState()`

- `Boolean _IsStateStable()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.PlayerAvatar
public class PlayerAvatarDisplayState : PopupFloatState
{
	private PlayerAvatarDisplayView _view; // 0x70
	private RectTransform _backClick; // 0x78
	private PlayerAvatarDisplayStateBean m_stateBean; // 0x80
	private Boolean m_hasInited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_CloseState; // 0x18
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2723674 VA: 0x7594d3b674
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27236dc VA: 0x7594d3b6dc
	protected override Void OnEnter() { }
	// RVA: 0x2723774 VA: 0x7594d3b774
	private Void _InitIfNot() { }
	// RVA: 0x27238a8 VA: 0x7594d3b8a8
	public Void CloseState() { }
	// RVA: 0x2723934 VA: 0x7594d3b934
	private Boolean _IsStateStable() { }
	// RVA: 0x27239f0 VA: 0x7594d3b9f0
	public Void .ctor() { }
	// RVA: 0x2723b48 VA: 0x7594d3bb48
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```