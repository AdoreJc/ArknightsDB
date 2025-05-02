# ActMultiV3QuickMatchPage

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _dlgContainer`

- `UICompDialogMgr m_dlgMgr`

- `String <actId>k__BackingField`


## Properties

- `String actId`

- `UICompDialogMgr dlgMgr`


## Methods

- `String get_actId()`

- `Void set_actId(String)`

- `UICompDialogMgr get_dlgMgr()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3QuickMatchPage : StateEnginePage
{
	private RectTransform _dlgContainer; // 0xe8
	private UICompDialogMgr m_dlgMgr; // 0xf0
	private String <actId>k__BackingField; // 0xf8
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_set_actId; // 0x8
	private static DelegateBridge __Hotfix0_get_dlgMgr; // 0x10
	private static DelegateBridge __Hotfix0_OnCreate; // 0x18
	private static DelegateBridge __Hotfix0_EffectsOnShow; // 0x20
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String actId { get; set; }
	public UICompDialogMgr dlgMgr { get; }

	// RVA: 0x312971c VA: 0x759574171c
	public String get_actId() { }
	// RVA: 0x3129784 VA: 0x7595741784
	private Void set_actId(String value) { }
	// RVA: 0x3129808 VA: 0x7595741808
	public UICompDialogMgr get_dlgMgr() { }
	// RVA: 0x3129870 VA: 0x7595741870
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x3129980 VA: 0x7595741980
	protected override IEnumerator EffectsOnShow(Boolean isFromStack) { }
	// RVA: 0x3129a70 VA: 0x7595741a70
	protected override IEnumerator EffectsOnHide(Boolean isFromStack) { }
	// RVA: 0x3129b60 VA: 0x7595741b60
	public Void .ctor() { }
	// RVA: 0x3129bd0 VA: 0x7595741bd0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x3129bd8 VA: 0x7595741bd8
	private IEnumerator <>xLuaBaseProxy_EffectsOnShow(Boolean P0) { }
	// RVA: 0x3129be4 VA: 0x7595741be4
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```