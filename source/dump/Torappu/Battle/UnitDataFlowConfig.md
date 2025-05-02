# UnitDataFlowConfig

**Namespace:** `Torappu.Battle`


## Methods

- `Void Init(BattleCharacterData, Dictionary`2)`

- `Delta GetDelta(Blackboard, DataType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UnitDataFlowConfig : MonoBehaviour
{
	private ModifierConfig[] _config; // 0x18
	private List`1 m_modifiers; // 0x20


	// RVA: 0x1c396c8 VA: 0x75942516c8
	public Void Init(BattleCharacterData dataSource, Dictionary`2 talentMap) { }
	// RVA: 0x1c39ea8 VA: 0x7594251ea8
	public Delta GetDelta(Blackboard blackboardSource, DataType target, String talentKey) { }
	// RVA: 0x1c3a1b0 VA: 0x75942521b0
	public Void .ctor() { }
}
```