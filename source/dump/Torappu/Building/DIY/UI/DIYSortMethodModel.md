# DIYSortMethodModel

**Namespace:** `Torappu.Building.DIY.UI`


## Fields

- `DiySortType diySortType`

- `String methodName`

- `Int32 methodIndex`

- `DiyUISortOrder sortOrder`

- `DiyUISortOrder defaultSortOrder`

- `String stableSequence`

- `DiyUISortOrder stableSequenceOrder`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY.UI
public class DIYSortMethodModel : IHotfixable
{
	public DiySortType diySortType; // 0x10
	public String methodName; // 0x18
	public Int32 methodIndex; // 0x20
	public DiyUISortOrder sortOrder; // 0x24
	public DiyUISortOrder defaultSortOrder; // 0x28
	public List`1 sortTemplates; // 0x30
	public String stableSequence; // 0x38
	public DiyUISortOrder stableSequenceOrder; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x383fc60 VA: 0x7595e57c60
	public Void .ctor() { }
}
```