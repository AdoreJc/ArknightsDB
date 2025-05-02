# BasicCharBuff

**Namespace:** `Torappu.Battle.Roguelike`


## Fields

- `BasicRelic m_relic`


## Properties

- `RelicType relicType`


## Methods

- `RelicType get_relicType()`

- `Void Init(BasicRelic, List`1)`

- `Boolean VerifyCharUID(UInt32)`

- `Void PreprocessChar(ref)`

- `Void PreprocessDeck(ref)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Roguelike
public class BasicCharBuff
{
	private List`1 m_charUniqueIDs; // 0x10
	private BasicRelic m_relic; // 0x18

	public RelicType relicType { get; }

	// RVA: 0x1d4646c VA: 0x759435e46c
	public RelicType get_relicType() { }
	// RVA: 0x1d45f78 VA: 0x759435df78
	public Void Init(BasicRelic relic, List`1 charUniqueIDs) { }
	// RVA: 0x1d4a5c8 VA: 0x75943625c8
	private Boolean VerifyCharUID(UInt32 charUID) { }
	// RVA: 0x1d4648c VA: 0x759435e48c
	public Void PreprocessChar(ref RelicInOut inOut) { }
	// RVA: 0x1d467d0 VA: 0x759435e7d0
	public Void PreprocessDeck(ref RelicInOut inOut) { }
	// RVA: 0x1d45f70 VA: 0x759435df70
	public Void .ctor() { }
}
```