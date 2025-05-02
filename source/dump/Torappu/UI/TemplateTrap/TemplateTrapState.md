# TemplateTrapState

**Namespace:** `Torappu.UI.TemplateTrap`


## Fields

- `TemplateTrapStateBean m_trapStateBean`

- `Transform _container`

- `TemplateTrapView m_trapView`

- `Tween m_tween`


## Methods

- `Void OnShowTween()`

- `Void OnSelectTrap(Int32, String)`

- `Void OnSaveTrapSquad()`

- `Void <OnEnter>b__5_0(String, Int32)`

- `Void <OnSaveTrapSquad>b__8_0(SetTemplateTrapResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateTrap
public class TemplateTrapState : State
{
	private TemplateTrapStateBean m_trapStateBean; // 0x50
	private Transform _container; // 0x58
	private TemplateTrapView m_trapView; // 0x60
	private Tween m_tween; // 0x68
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnShowTween; // 0x10
	private static DelegateBridge __Hotfix0_OnSelectTrap; // 0x18
	private static DelegateBridge __Hotfix0_OnSaveTrapSquad; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x234e5d0 VA: 0x75949665d0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x234e638 VA: 0x7594966638
	protected override Void OnEnter() { }
	// RVA: 0x234ebcc VA: 0x7594966bcc
	public Void OnShowTween() { }
	// RVA: 0x234ec9c VA: 0x7594966c9c
	public Void OnSelectTrap(Int32 index, String trapId) { }
	// RVA: 0x234ee40 VA: 0x7594966e40
	public Void OnSaveTrapSquad() { }
	// RVA: 0x234f418 VA: 0x7594967418
	public Void .ctor() { }
	// RVA: 0x234f534 VA: 0x7594967534
	private Void <OnEnter>b__5_0(String trapid, Int32 i) { }
	// RVA: 0x234f544 VA: 0x7594967544
	private Void <OnSaveTrapSquad>b__8_0(SetTemplateTrapResponse response) { }
	// RVA: 0x234f5d8 VA: 0x75949675d8
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```