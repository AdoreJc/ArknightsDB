# ExpeditionReturnSingleData

**Namespace:** ` `


## Fields

- `String topicId`

- `String instId`

- `String charId`

- `String charName`

- `Boolean isUpgrade`

- `ExpedType expedType`


## Methods

- `Void LoadData(Options, Char)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ExpeditionReturnSingleData : IHotfixable
{
	public String topicId; // 0x10
	public String instId; // 0x18
	public String charId; // 0x20
	public String charName; // 0x28
	public Boolean isUpgrade; // 0x30
	public ExpedType expedType; // 0x34
	public List`1 rewards; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x29e7cf8 VA: 0x7594fffcf8
	public Void LoadData(Options options, Char returnChar) { }
	// RVA: 0x29e7ee8 VA: 0x7594fffee8
	public Void .ctor() { }
}
```