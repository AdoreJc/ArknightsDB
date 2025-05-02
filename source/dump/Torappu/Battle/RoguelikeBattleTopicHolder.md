# RoguelikeBattleTopicHolder

**Namespace:** `Torappu.Battle`


## Fields

- `String m_rogue1`

- `String m_rogue2`

- `String m_rogue3`

- `String m_rogue4`

- `String m_rogue3HideUILifePoint`


## Properties

- `String rogue3HideUILifePoint`


## Methods

- `String get_rogue3HideUILifePoint()`

- `SchedulerPreprocessor GetSchedulerPreprocessor(RoguelikeInput)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class RoguelikeBattleTopicHolder : ScriptableObject, IHotfixable
{
	private String m_rogue1; // 0x18
	private String m_rogue2; // 0x20
	private String m_rogue3; // 0x28
	private String m_rogue4; // 0x30
	private String m_rogue3HideUILifePoint; // 0x38
	private static DelegateBridge __Hotfix0_get_rogue3HideUILifePoint; // 0x0
	private static DelegateBridge __Hotfix0_GetSchedulerPreprocessor; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public String rogue3HideUILifePoint { get; }

	// RVA: 0x40cbf7c VA: 0x75966e3f7c
	public String get_rogue3HideUILifePoint() { }
	// RVA: 0x40cbfe4 VA: 0x75966e3fe4
	public SchedulerPreprocessor GetSchedulerPreprocessor(RoguelikeInput input) { }
	// RVA: 0x40cc2d4 VA: 0x75966e42d4
	public Void .ctor() { }
}
```