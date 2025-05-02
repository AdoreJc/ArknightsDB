# Act33SignRedpackItemViewModel

**Namespace:** `Torappu.Activity.Act33Sign`


## Fields

- `Int32 order`

- `String blessing`

- `Int64 absolutData`

- `String adTip`

- `Int32 relativeData`

- `Act33SignRedpackStatus status`

- `String titleId`

- `String descId`

- `String numId`

- `String extraTips`

- `Int32 daysLeftToCalm`

- `Boolean absolutDatePass`


## Methods

- `Void LoadData(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act33Sign
public class Act33SignRedpackItemViewModel : IHotfixable
{
	private const String TITLE_ID; // 0x0
	private const String DESC_ID; // 0x0
	private const String NUMBER_ID; // 0x0
	public Int32 order; // 0x10
	public String blessing; // 0x18
	public Int64 absolutData; // 0x20
	public String adTip; // 0x28
	public Int32 relativeData; // 0x30
	public List`1 itemList; // 0x38
	public Act33SignRedpackStatus status; // 0x40
	public Func`2 loadSpriteFunc; // 0x48
	public String titleId; // 0x50
	public String descId; // 0x58
	public String numId; // 0x60
	public String extraTips; // 0x68
	public Int32 daysLeftToCalm; // 0x70
	public Boolean absolutDatePass; // 0x74
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x325657c VA: 0x759586e57c
	public Void LoadData(Int32 signCount) { }
	// RVA: 0x3256824 VA: 0x759586e824
	public Void .ctor() { }
}
```