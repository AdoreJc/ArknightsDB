# CrisisV2EntryViewModel

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `String seasonId`

- `Boolean isServerDataInited`

- `PermPart permStage`

- `Int64 endTime`

- `String themeColor1`

- `String themeColor2`

- `String medalId`

- `Boolean medalAvail`

- `String medalGroupId`

- `Int32 coin`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2EntryViewModel : IHotfixable
{
	public String seasonId; // 0x10
	public Boolean isServerDataInited; // 0x18
	public List`1 tempStages; // 0x20
	public PermPart permStage; // 0x28
	public Int64 endTime; // 0x30
	public String themeColor1; // 0x38
	public String themeColor2; // 0x40
	public String medalId; // 0x48
	public Boolean medalAvail; // 0x50
	public String medalGroupId; // 0x58
	public Int32 coin; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x2be6510 VA: 0x75951fe510
	public Void .ctor() { }
}
```