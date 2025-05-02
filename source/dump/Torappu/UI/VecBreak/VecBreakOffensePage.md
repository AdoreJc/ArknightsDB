# VecBreakOffensePage

**Namespace:** `Torappu.UI.VecBreak`


## Fields

- `RectTransform _dlgContainer`

- `VecBreakOffenseProp m_prop`

- `UICompDialogMgr m_dlgMgr`


## Properties

- `VecBreakOffenseProp prop`

- `UICompDialogMgr dlgMgr`


## Methods

- `VecBreakOffenseProp get_prop()`

- `UICompDialogMgr get_dlgMgr()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VecBreak
public class VecBreakOffensePage : StateEnginePage
{
	public const String KEY_PARAM_BUNDLE; // 0x0
	private RectTransform _dlgContainer; // 0xe8
	private VecBreakOffenseProp m_prop; // 0xf0
	private UICompDialogMgr m_dlgMgr; // 0xf8
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_get_dlgMgr; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public VecBreakOffenseProp prop { get; }
	public UICompDialogMgr dlgMgr { get; }

	// RVA: 0x22ce834 VA: 0x75948e6834
	public VecBreakOffenseProp get_prop() { }
	// RVA: 0x22ce89c VA: 0x75948e689c
	public UICompDialogMgr get_dlgMgr() { }
	// RVA: 0x22ce904 VA: 0x75948e6904
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x22cebf8 VA: 0x75948e6bf8
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x22ceccc VA: 0x75948e6ccc
	public Void .ctor() { }
	// RVA: 0x22cede4 VA: 0x75948e6de4
	private IEnumerator <>n__0() { }
	// RVA: 0x22cedec VA: 0x75948e6dec
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x22cedf4 VA: 0x75948e6df4
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```