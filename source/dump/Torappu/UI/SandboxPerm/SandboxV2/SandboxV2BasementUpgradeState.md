# SandboxV2BasementUpgradeState

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2BasementUpgradeView _upgradeView`

- `SandboxV2BasementUpgradeStateBean m_cachedBean`

- `String m_cachedTopicId`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnBasementUpgrade()`

- `Void _OnUpgradeResp(SandboxV2BasementUpgradeResponse)`

- `Void _PlayUpgradeAudio()`

- `Void _UpgradeAnimFinish()`

- `Void OnBtnBackClicked()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BasementUpgradeState : PopupFadeState, IValueMsgReceiver
{
	private SandboxV2BasementUpgradeView _upgradeView; // 0x70
	public const Int32 MSG_SANDBOX_V2_UPGRADE_BASEMENT; // 0x0
	public const Int32 MSG_SANDBOX_V2_CLOSE_STATE; // 0x0
	private const String ANIM_UPGRADE; // 0x0
	private SandboxV2BasementUpgradeStateBean m_cachedBean; // 0x78
	private String m_cachedTopicId; // 0x80
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_OnResume; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnBasementUpgrade; // 0x20
	private static DelegateBridge __Hotfix0__OnUpgradeResp; // 0x28
	private static DelegateBridge __Hotfix0__PlayUpgradeAudio; // 0x30
	private static DelegateBridge __Hotfix0__UpgradeAnimFinish; // 0x38
	private static DelegateBridge __Hotfix0_OnBtnBackClicked; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x250cae0 VA: 0x7594b24ae0
	protected override Void OnEnter() { }
	// RVA: 0x250cf9c VA: 0x7594b24f9c
	protected override Void OnResume() { }
	// RVA: 0x250d008 VA: 0x7594b25008
	public override IStateBean GetCacheBean() { }
	// RVA: 0x250d070 VA: 0x7594b25070
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x250d130 VA: 0x7594b25130
	private Void _OnBasementUpgrade() { }
	// RVA: 0x250d54c VA: 0x7594b2554c
	private Void _OnUpgradeResp(SandboxV2BasementUpgradeResponse resp) { }
	// RVA: 0x250d6dc VA: 0x7594b256dc
	private Void _PlayUpgradeAudio() { }
	// RVA: 0x250d784 VA: 0x7594b25784
	private Void _UpgradeAnimFinish() { }
	// RVA: 0x250d310 VA: 0x7594b25310
	public Void OnBtnBackClicked() { }
	// RVA: 0x250d84c VA: 0x7594b2584c
	public Void .ctor() { }
	// RVA: 0x250d9a4 VA: 0x7594b259a4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x250d9ac VA: 0x7594b259ac
	private Void <>xLuaBaseProxy_OnResume() { }
}
```