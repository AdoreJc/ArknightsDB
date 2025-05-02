# TuningHomeMajorInvestViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Status status`

- `Int32 currIndex`

- `Int32 maxIndex`

- `Int32 tokenCount`


## Methods

- `Void LoadData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeMajorInvestViewModel : TuningHomeInvestBaseViewModel, IHotfixable
{
	public Status status; // 0x30
	public Int32 currIndex; // 0x34
	public Int32 maxIndex; // 0x38
	public Int32 tokenCount; // 0x3c
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2329ffc VA: 0x7594941ffc
	public Void LoadData(String actId) { }
	// RVA: 0x232a3a4 VA: 0x75949423a4
	public Void .ctor() { }
}
```