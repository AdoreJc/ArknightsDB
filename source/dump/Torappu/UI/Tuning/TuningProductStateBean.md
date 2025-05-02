# TuningProductStateBean

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `TuningProductProperty m_prop`

- `String m_actId`

- `Int32 m_enterSequenceNum`

- `String m_resultProductId`

- `Boolean m_isMusicFromStart`

- `Boolean m_resultProductIsNew`


## Properties

- `TuningProductProperty prop`

- `String resultProductId`

- `Boolean isMusicFromStart`

- `Boolean resultProductIsNew`


## Methods

- `TuningProductProperty get_prop()`

- `String get_resultProductId()`

- `Boolean get_isMusicFromStart()`

- `Boolean get_resultProductIsNew()`

- `Void InitData(String)`

- `Void UpdateData()`

- `Void SetResultProductId(String)`

- `Void SetMusicPlayType(Boolean)`

- `Boolean CheckResProductIsNewProductType(Dictionary`2, String, out)`

- `Void _SetResultProductIsNew(Boolean)`

- `Boolean _CheckResProductIsNewProductType(Dictionary`2, String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductStateBean : IStateBean, IHotfixable
{
	private TuningProductProperty m_prop; // 0x10
	private String m_actId; // 0x18
	private Int32 m_enterSequenceNum; // 0x20
	private String m_resultProductId; // 0x28
	private Boolean m_isMusicFromStart; // 0x30
	private Boolean m_resultProductIsNew; // 0x31
	private static DelegateBridge __Hotfix0_get_prop; // 0x0
	private static DelegateBridge __Hotfix0_get_resultProductId; // 0x8
	private static DelegateBridge __Hotfix0_get_isMusicFromStart; // 0x10
	private static DelegateBridge __Hotfix0_get_resultProductIsNew; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x20
	private static DelegateBridge __Hotfix0_UpdateData; // 0x28
	private static DelegateBridge __Hotfix0_SetResultProductId; // 0x30
	private static DelegateBridge __Hotfix0_SetMusicPlayType; // 0x38
	private static DelegateBridge __Hotfix0_CheckResProductIsNewProductType; // 0x40
	private static DelegateBridge __Hotfix0__SetResultProductIsNew; // 0x48
	private static DelegateBridge __Hotfix0__CheckResProductIsNewProductType; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public TuningProductProperty prop { get; }
	public String resultProductId { get; }
	public Boolean isMusicFromStart { get; }
	public Boolean resultProductIsNew { get; }

	// RVA: 0x233e234 VA: 0x7594956234
	public TuningProductProperty get_prop() { }
	// RVA: 0x233e29c VA: 0x759495629c
	public String get_resultProductId() { }
	// RVA: 0x233e304 VA: 0x7594956304
	public Boolean get_isMusicFromStart() { }
	// RVA: 0x233e36c VA: 0x759495636c
	public Boolean get_resultProductIsNew() { }
	// RVA: 0x233e3d4 VA: 0x75949563d4
	public Void InitData(String actId) { }
	// RVA: 0x233e4d0 VA: 0x75949564d0
	public Void UpdateData() { }
	// RVA: 0x233e564 VA: 0x7594956564
	public Void SetResultProductId(String inputProductId) { }
	// RVA: 0x233e5e8 VA: 0x75949565e8
	public Void SetMusicPlayType(Boolean iIsMusicFromStart) { }
	// RVA: 0x233e668 VA: 0x7594956668
	public Boolean CheckResProductIsNewProductType(Dictionary`2 prevFormNax, String productId, out String productTypeId) { }
	// RVA: 0x233e9dc VA: 0x75949569dc
	private Void _SetResultProductIsNew(Boolean iResultIsNew) { }
	// RVA: 0x233e724 VA: 0x7594956724
	private Boolean _CheckResProductIsNewProductType(Dictionary`2 prevFormNax, String productId, out String productTypeId) { }
	// RVA: 0x233ea5c VA: 0x7594956a5c
	public Void .ctor() { }
}
```