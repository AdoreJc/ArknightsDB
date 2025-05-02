# PredefinedInst

**Namespace:** ` `


## Fields

- `Boolean hidden`

- `String alias`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class PredefinedInst : AdvancedCharacterInst
{
	public Boolean hidden; // 0x58
	public String alias; // 0x60

	public override Boolean isPredefined { get; }
	public override Boolean isHidden { get; }

	// RVA: 0x34a4bec VA: 0x7595abcbec
	public override Boolean get_isPredefined() { }
	// RVA: 0x34a4bf4 VA: 0x7595abcbf4
	public override Boolean get_isHidden() { }
	// RVA: 0x34a4bfc VA: 0x7595abcbfc
	public override String GetAliasId() { }
	// RVA: 0x34a4c30 VA: 0x7595abcc30
	public Void .ctor() { }
}
```