# BattleLogCollector

**Namespace:** `Torappu`


## Methods

- `Void ForeachPackedRuneData(Action`1)`

- `Void ForeachRuneData(Action`1)`

- `Void Collect(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BattleLogCollector : Singleton`1, IRuneDataHolder
{
	private List`1 m_crisisV2Runes; // 0x10
	private const String CRISIS_V2_KEY; // 0x0
	private static DelegateBridge __Hotfix0_get_crisisV2Runes; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_ForeachPackedRuneData; // 0x10
	private static DelegateBridge __Hotfix0_ForeachRuneData; // 0x18
	private static DelegateBridge __Hotfix0_Collect; // 0x20

	public List`1 crisisV2Runes { get; }

	// RVA: 0x2d02f80 VA: 0x759531af80
	public List`1 get_crisisV2Runes() { }
	// RVA: 0x2d02fe8 VA: 0x759531afe8
	private Void .ctor() { }
	// RVA: 0x2d030cc VA: 0x759531b0cc
	public Void ForeachPackedRuneData(Action`1 visitor) { }
	// RVA: 0x2d03144 VA: 0x759531b144
	public Void ForeachRuneData(Action`1 visitor) { }
	// RVA: 0x2d03244 VA: 0x759531b244
	public Void Collect(String levelId) { }
}
```