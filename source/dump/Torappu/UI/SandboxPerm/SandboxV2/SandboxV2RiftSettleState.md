# SandboxV2RiftSettleState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2RiftSettleView _view`

- `SandboxV2RiftSettleStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnConfirmClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2RiftSettleState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_CONFIRM_CLICKED; // 0x0
	private SandboxV2RiftSettleView _view; // 0x70
	private SandboxV2RiftSettleStateBean m_stateBean; // 0x78
	private Boolean m_hasInited; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnConfirmClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x251ad88 VA: 0x7594b32d88
	public override IStateBean GetCacheBean() { }
	// RVA: 0x251adf0 VA: 0x7594b32df0
	protected override Void OnEnter() { }
	// RVA: 0x251af90 VA: 0x7594b32f90
	private Void _InitIfNot() { }
	// RVA: 0x251b5d8 VA: 0x7594b335d8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x251b67c VA: 0x7594b3367c
	private Void _OnConfirmClicked() { }
	// RVA: 0x251b970 VA: 0x7594b33970
	public Void .ctor() { }
	// RVA: 0x251bac8 VA: 0x7594b33ac8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```