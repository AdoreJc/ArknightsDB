# SandboxPermDiffState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxPermDiffStateBean _stateBean`

- `SandboxPermDiffView _diffView`

- `Button _dismissButton`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void SendSwitchExploreModeService(Int32)`

- `Void _OnExploreModeServiceCallback(Int32)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxPermDiffState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 MSG_CONFIRM_CLICKED; // 0x0
	private SandboxPermDiffStateBean _stateBean; // 0x70
	private SandboxPermDiffView _diffView; // 0x78
	private Button _dismissButton; // 0x80
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_SendSwitchExploreModeService; // 0x18
	private static DelegateBridge __Hotfix0__OnExploreModeServiceCallback; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2480df0 VA: 0x7594a98df0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2480e58 VA: 0x7594a98e58
	protected override Void OnEnter() { }
	// RVA: 0x2481008 VA: 0x7594a99008
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x24810dc VA: 0x7594a990dc
	public Void SendSwitchExploreModeService(Int32 mode) { }
	// RVA: 0x2481360 VA: 0x7594a99360
	private Void _OnExploreModeServiceCallback(Int32 mode) { }
	// RVA: 0x248161c VA: 0x7594a9961c
	public Void .ctor() { }
	// RVA: 0x248168c VA: 0x7594a9968c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```