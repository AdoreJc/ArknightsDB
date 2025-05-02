# UniEquipLevelUpState

**Namespace:** `Torappu.UI.UniEquip`


## Fields

- `UniEquipLevelUpView _levelUpView`

- `Boolean m_isInited`

- `UniEquipLevelUpStateBean m_stateBean`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void EventOnConfirmClick()`

- `Void EventOnCancelClick()`

- `Void _InitIfNot()`

- `Void _EventOnSelectTargetLevel(Int32)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquip
public class UniEquipLevelUpState : PopupFadeState, IValueMsgReceiver
{
	private UniEquipLevelUpView _levelUpView; // 0x70
	private Boolean m_isInited; // 0x78
	private UniEquipLevelUpStateBean m_stateBean; // 0x80
	public const Int32 MSG_TARGET_LEVEL_CHANGE; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirmClick; // 0x20
	private static DelegateBridge __Hotfix0_EventOnCancelClick; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__EventOnSelectTargetLevel; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x22f96b4 VA: 0x75949116b4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x22f971c VA: 0x759491171c
	protected override Void OnEnter() { }
	// RVA: 0x22f9840 VA: 0x7594911840
	protected override Void OnResume() { }
	// RVA: 0x22f98dc VA: 0x75949118dc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x22f9a54 VA: 0x7594911a54
	public Void EventOnConfirmClick() { }
	// RVA: 0x22f9dc0 VA: 0x7594911dc0
	public Void EventOnCancelClick() { }
	// RVA: 0x22f9790 VA: 0x7594911790
	private Void _InitIfNot() { }
	// RVA: 0x22f9988 VA: 0x7594911988
	private Void _EventOnSelectTargetLevel(Int32 selectLevel) { }
	// RVA: 0x22f9e34 VA: 0x7594911e34
	public Void .ctor() { }
	// RVA: 0x22f9ee4 VA: 0x7594911ee4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x22f9eec VA: 0x7594911eec
	private Void <>xLuaBaseProxy_OnResume() { }
}
```