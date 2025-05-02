# VOutputRoom

**Namespace:** `Torappu.Building.Vault`


## Fields

- `Boolean m_isWorking`


## Properties

- `Boolean isWorking`


## Methods

- `Boolean get_isWorking()`

- `Void set_isWorking(Boolean)`

- `Void OnEnable()`

- `Void _OnPlayerDataChanged(Object)`

- `Void _UpdateIsWorking(Boolean)`

- `Void _SetIsWorkingInternal(Boolean, Boolean)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreInit()`

- `Void <>xLuaBaseProxy_OnDestroyRoom()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.Vault
public class VOutputRoom : VRoom
{
	private Boolean m_isWorking; // 0x80
	private static DelegateBridge __Hotfix0_get_isWorking; // 0x0
	private static DelegateBridge __Hotfix0_set_isWorking; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnPreInit; // 0x18
	private static DelegateBridge __Hotfix0_OnDestroyRoom; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x30
	private static DelegateBridge __Hotfix0__UpdateIsWorking; // 0x38
	private static DelegateBridge __Hotfix0__SetIsWorkingInternal; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	protected Boolean isWorking { get; set; }

	// RVA: 0x3cf0a40 VA: 0x7596308a40
	protected Boolean get_isWorking() { }
	// RVA: 0x3cf0aa8 VA: 0x7596308aa8
	private Void set_isWorking(Boolean value) { }
	// RVA: 0x3cf0c74 VA: 0x7596308c74
	public override Void OnEnter() { }
	// RVA: 0x3cf0d98 VA: 0x7596308d98
	protected override Void OnPreInit() { }
	// RVA: 0x3cf0f80 VA: 0x7596308f80
	protected override Void OnDestroyRoom() { }
	// RVA: 0x3cf1174 VA: 0x7596309174
	private Void OnEnable() { }
	// RVA: 0x3cf11e0 VA: 0x75963091e0
	private Void _OnPlayerDataChanged(Object _) { }
	// RVA: 0x3cf0ce8 VA: 0x7596308ce8
	private Void _UpdateIsWorking(Boolean force) { }
	// RVA: 0x3cf0b2c VA: 0x7596308b2c
	private Void _SetIsWorkingInternal(Boolean value, Boolean force) { }
	// RVA: 0x3cf1324 VA: 0x7596309324
	public Void .ctor() { }
	// RVA: 0x3cf13b4 VA: 0x75963093b4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3cf13b8 VA: 0x75963093b8
	private Void <>xLuaBaseProxy_OnPreInit() { }
	// RVA: 0x3cf13bc VA: 0x75963093bc
	private Void <>xLuaBaseProxy_OnDestroyRoom() { }
}
```