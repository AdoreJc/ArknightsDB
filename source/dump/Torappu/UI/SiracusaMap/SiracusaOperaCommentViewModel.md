# SiracusaOperaCommentViewModel

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `String operaId`

- `String operaName`

- `String operaSubName`

- `String score`

- `String selectedCommentId`

- `Int32 leftLike`

- `Int32 totalLike`

- `String leftTimeNum`

- `String leftTimeUnit`

- `Boolean isAllRelease`

- `Boolean isInit`


## Methods

- `Void LoadData(String)`

- `Void _GenerateGroups()`

- `TimeSpan _GetHoursToNextCrossDay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaOperaCommentViewModel : IHotfixable
{
	public List`1 commentItems; // 0x10
	public List`1 commentGroups; // 0x18
	public String operaId; // 0x20
	public String operaName; // 0x28
	public String operaSubName; // 0x30
	public String score; // 0x38
	public String selectedCommentId; // 0x40
	public Int32 leftLike; // 0x48
	public Int32 totalLike; // 0x4c
	public String leftTimeNum; // 0x50
	public String leftTimeUnit; // 0x58
	public Boolean isAllRelease; // 0x60
	public Boolean isInit; // 0x61
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__GenerateGroups; // 0x8
	private static DelegateBridge __Hotfix0__GetHoursToNextCrossDay; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x23fcd04 VA: 0x7594a14d04
	public Void LoadData(String operaId) { }
	// RVA: 0x23fd74c VA: 0x7594a1574c
	private Void _GenerateGroups() { }
	// RVA: 0x23fd678 VA: 0x7594a15678
	private TimeSpan _GetHoursToNextCrossDay() { }
	// RVA: 0x23fdaf4 VA: 0x7594a15af4
	public Void .ctor() { }
}
```