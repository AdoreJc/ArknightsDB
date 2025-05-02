# ActMultiV3ManualTitleSelectViewModel

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `String actId`

- `ActMultiV3ManualTitleListModel prefixModel`

- `ActMultiV3ManualTitleListModel suffixModel`

- `Int32 initSeqNum`

- `Boolean isItemValid`

- `Boolean isScrolling`


## Methods

- `Void InitData(String)`

- `Void UpdateSelection(Boolean, Int32)`

- `Void UpdatePage(Boolean, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualTitleSelectViewModel : IHotfixable
{
	public String actId; // 0x10
	public ActMultiV3ManualTitleListModel prefixModel; // 0x18
	public ActMultiV3ManualTitleListModel suffixModel; // 0x20
	public Int32 initSeqNum; // 0x28
	public Boolean isItemValid; // 0x2c
	public Boolean isScrolling; // 0x2d
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateSelection; // 0x8
	private static DelegateBridge __Hotfix0_UpdatePage; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x31206c0 VA: 0x75957386c0
	public Void InitData(String actId) { }
	// RVA: 0x3120dd4 VA: 0x7595738dd4
	public Void UpdateSelection(Boolean isBack, Int32 pageIdx) { }
	// RVA: 0x3120f5c VA: 0x7595738f5c
	public Void UpdatePage(Boolean isBack, Int32 pageIdx) { }
	// RVA: 0x3121014 VA: 0x7595739014
	public Void .ctor() { }
}
```