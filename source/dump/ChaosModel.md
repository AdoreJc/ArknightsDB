# ChaosModel

**Namespace:** ` `


## Fields

- `String chaosId`

- `String chaosName`

- `String chaosDesc`

- `String chaosIconId`

- `Int32 chaosLevel`

- `String description`


## Methods

- `Void LoadData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ChaosModel : IHotfixable
{
	public String chaosId; // 0x10
	public String chaosName; // 0x18
	public String chaosDesc; // 0x20
	public String chaosIconId; // 0x28
	public Int32 chaosLevel; // 0x30
	public String description; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2bb510c VA: 0x75951cd10c
	public Void LoadData(String topicId, String chaosId) { }
	// RVA: 0x2bb52f0 VA: 0x75951cd2f0
	public Void .ctor() { }
}
```