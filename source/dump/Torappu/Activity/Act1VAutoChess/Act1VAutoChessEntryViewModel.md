# Act1VAutoChessEntryViewModel

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `ShowType m_lastShowType`

- `ShowType m_showType`

- `Int32 m_animSeq`

- `Int32 m_fastModeSeq`


## Properties

- `ShowType lastShowType`

- `ShowType showType`

- `Int32 animSeq`

- `Int32 fastModeSeq`


## Methods

- `ShowType get_lastShowType()`

- `ShowType get_showType()`

- `Int32 get_animSeq()`

- `Int32 get_fastModeSeq()`

- `Void OnInit()`

- `Void SetShowType(ShowType)`

- `Void UpdateSubViewModelInShowType(ShowType)`

- `Void LoadData(String)`

- `Void RefreshData()`

- `Void NotifyAnim()`

- `Void NotifyFastMode()`

- `Void NotifySubViewsUpdate()`

- `Void NotifySubViewUpdate(ShowType)`

- `T GetSubViewModelByType(ShowType)`

- `Void _InitSubViewModels(String)`

- `Void _RefreshSubViewData(ShowType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEntryViewModel : IHotfixable
{
	private ShowType m_lastShowType; // 0x10
	private ShowType m_showType; // 0x14
	private Int32 m_animSeq; // 0x18
	private Int32 m_fastModeSeq; // 0x1c
	private ListDict`2 m_subViewModelList; // 0x20
	private static DelegateBridge __Hotfix0_get_lastShowType; // 0x0
	private static DelegateBridge __Hotfix0_get_showType; // 0x8
	private static DelegateBridge __Hotfix0_get_animSeq; // 0x10
	private static DelegateBridge __Hotfix0_get_fastModeSeq; // 0x18
	private static DelegateBridge __Hotfix0_get_subViewModelList; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_SetShowType; // 0x30
	private static DelegateBridge __Hotfix0_UpdateSubViewModelInShowType; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x40
	private static DelegateBridge __Hotfix0_RefreshData; // 0x48
	private static DelegateBridge __Hotfix0_NotifyAnim; // 0x50
	private static DelegateBridge __Hotfix0_NotifyFastMode; // 0x58
	private static DelegateBridge __Hotfix0_NotifySubViewsUpdate; // 0x60
	private static DelegateBridge __Hotfix0_NotifySubViewUpdate; // 0x68
	private static DelegateBridge __Hotfix0_GetSubViewModelByType; // 0x70
	private static DelegateBridge __Hotfix0__InitSubViewModels; // 0x78
	private static DelegateBridge __Hotfix0__RefreshSubViewData; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public ShowType lastShowType { get; }
	public ShowType showType { get; }
	public Int32 animSeq { get; }
	public Int32 fastModeSeq { get; }
	public ListDict`2 subViewModelList { get; }

	// RVA: 0x3358a7c VA: 0x7595970a7c
	public ShowType get_lastShowType() { }
	// RVA: 0x3358ae4 VA: 0x7595970ae4
	public ShowType get_showType() { }
	// RVA: 0x3358b4c VA: 0x7595970b4c
	public Int32 get_animSeq() { }
	// RVA: 0x3358bb4 VA: 0x7595970bb4
	public Int32 get_fastModeSeq() { }
	// RVA: 0x3358c1c VA: 0x7595970c1c
	public ListDict`2 get_subViewModelList() { }
	// RVA: 0x3358c84 VA: 0x7595970c84
	public Void OnInit() { }
	// RVA: 0x3358cec VA: 0x7595970cec
	public Void SetShowType(ShowType showType) { }
	// RVA: 0x3358d6c VA: 0x7595970d6c
	public Void UpdateSubViewModelInShowType(ShowType showType) { }
	// RVA: 0x3358fb0 VA: 0x7595970fb0
	public Void LoadData(String actId) { }
	// RVA: 0x33593a4 VA: 0x75959713a4
	public Void RefreshData() { }
	// RVA: 0x33594a0 VA: 0x75959714a0
	public Void NotifyAnim() { }
	// RVA: 0x3359510 VA: 0x7595971510
	public Void NotifyFastMode() { }
	// RVA: 0x3359580 VA: 0x7595971580
	public Void NotifySubViewsUpdate() { }
	// RVA: 0x3358ed8 VA: 0x7595970ed8
	public Void NotifySubViewUpdate(ShowType subViewType) { }
	// RVA: 0x VA: 0x0
	public T GetSubViewModelByType(ShowType subViewType) { }
	// RVA: 0x3359038 VA: 0x7595971038
	private Void _InitSubViewModels(String actId) { }
	// RVA: 0x3358df8 VA: 0x7595970df8
	private Void _RefreshSubViewData(ShowType subViewType) { }
	// RVA: 0x3359670 VA: 0x7595971670
	public Void .ctor() { }
}
```