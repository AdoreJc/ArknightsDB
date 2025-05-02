# CharSelectBranchItemViewModel

**Namespace:** `Torappu.UI.CharSelect`


## Fields

- `String equipId`

- `Int32 equipLevel`

- `Sprite branchIcon`

- `String typeIcon`

- `String branchName`

- `String branchExtraName`

- `Boolean isAvailable`

- `UniEquipType equipType`

- `Int32 sortOrder`


## Methods

- `Int32 CompareTo(CharSelectBranchItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharSelect
public class CharSelectBranchItemViewModel : IComparable`1
{
	public String equipId; // 0x10
	public Int32 equipLevel; // 0x18
	public Sprite branchIcon; // 0x20
	public String typeIcon; // 0x28
	public String branchName; // 0x30
	public String branchExtraName; // 0x38
	public Boolean isAvailable; // 0x40
	public UniEquipType equipType; // 0x44
	public Int32 sortOrder; // 0x48


	// RVA: 0x2cee7a8 VA: 0x75953067a8
	public Int32 CompareTo(CharSelectBranchItemViewModel other) { }
	// RVA: 0x2cee7c8 VA: 0x75953067c8
	public Void .ctor() { }
}
```