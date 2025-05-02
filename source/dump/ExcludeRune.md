# ExcludeRune

**Namespace:** ` `


## Fields

- `RuneData m_data`


## Properties

- `Blackboard blackboard`


## Methods

- `Blackboard get_blackboard()`

- `Boolean CheckExcluded(CharacterCardViewModel)`

- `Boolean CheckExcluded(CharQuery)`

- `Boolean _CheckExcluded(String, ProfessionCategory, BuildableType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ExcludeRune
{
	private RuneData m_data; // 0x10
	private String[] m_charIdList; // 0x18

	private Blackboard blackboard { get; }

	// RVA: 0x238da68 VA: 0x75949a5a68
	private Blackboard get_blackboard() { }
	// RVA: 0x238da84 VA: 0x75949a5a84
	public Void .ctor(RuneData data) { }
	// RVA: 0x238cac0 VA: 0x75949a4ac0
	public Boolean CheckExcluded(CharacterCardViewModel cardModel) { }
	// RVA: 0x238ce5c VA: 0x75949a4e5c
	public Boolean CheckExcluded(CharQuery charQuery) { }
	// RVA: 0x238db94 VA: 0x75949a5b94
	private Boolean _CheckExcluded(String charId, ProfessionCategory profession, BuildableType buildableType) { }
}
```