# VecBreakDefensePage

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `RectTransform _dlgContainer`

- `VecBreakDefenseProp m_prop`

- `UICompDialogMgr m_dlgMgr`


## Properties

- `VecBreakDefenseProp prop`

- `UICompDialogMgr dlgMgr`


## Methods

- `VecBreakDefenseProp get_prop()`

- `UICompDialogMgr get_dlgMgr()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakDefensePage : StateEnginePage
{
	public const String KEY_PARAM_BUNDLE; // 0x0
	private RectTransform _dlgContainer; // 0xe8
	private VecBreakDefenseProp m_prop; // 0xf0
	private UICompDialogMgr m_dlgMgr; // 0xf8
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_get_dlgMgr; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public VecBreakDefenseProp prop { get; }
	public UICompDialogMgr dlgMgr { get; }

	// RVA: 0x22cb1a0 VA: 0x75948e31a0
	public VecBreakDefenseProp get_prop() { }
	// RVA: 0x22cb434 VA: 0x75948e3434
	public UICompDialogMgr get_dlgMgr() { }
	// RVA: 0x22cbbb0 VA: 0x75948e3bb0
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x22cc2b4 VA: 0x75948e42b4
	public Void .ctor() { }
	// RVA: 0x22cc3cc VA: 0x75948e43cc
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
}
```