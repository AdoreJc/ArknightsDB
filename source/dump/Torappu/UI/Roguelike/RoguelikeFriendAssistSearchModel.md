# RoguelikeFriendAssistSearchModel

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `String m_recruitIndex`

- `Recruit m_recruitData`

- `ProfessionCategory m_profession`

- `Int32 m_population`

- `String m_topicId`


## Properties

- `String recruitIndex`

- `Int32 population`

- `ProfessionCategory profession`

- `ProfessionCategory activeProfession`


## Methods

- `String get_recruitIndex()`

- `Int32 get_population()`

- `ProfessionCategory get_profession()`

- `ProfessionCategory get_activeProfession()`

- `Void LoadData(String)`

- `Boolean _TryGetCurrentPopulation(out)`

- `Boolean _TryGetPendingRecruitIndex(out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFriendAssistSearchModel : IHotfixable
{
	public static List`1 PROFESSION_LIST; // 0x0
	private String m_recruitIndex; // 0x10
	private Recruit m_recruitData; // 0x18
	private ProfessionCategory m_profession; // 0x20
	private Int32 m_population; // 0x24
	private String m_topicId; // 0x28
	private static DelegateBridge __Hotfix0_get_recruitIndex; // 0x8
	private static DelegateBridge __Hotfix0_get_population; // 0x10
	private static DelegateBridge __Hotfix0_get_profession; // 0x18
	private static DelegateBridge __Hotfix0_get_professionList; // 0x20
	private static DelegateBridge __Hotfix0_get_activeProfession; // 0x28
	private static DelegateBridge __Hotfix0_get_assistList; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x38
	private static DelegateBridge __Hotfix0__TryGetCurrentPopulation; // 0x40
	private static DelegateBridge __Hotfix0__TryGetPendingRecruitIndex; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public String recruitIndex { get; }
	public Int32 population { get; }
	public ProfessionCategory profession { get; }
	public List`1 professionList { get; }
	public ProfessionCategory activeProfession { get; }
	public List`1 assistList { get; }

	// RVA: 0x2a39f4c VA: 0x7595051f4c
	public String get_recruitIndex() { }
	// RVA: 0x2a3b0b4 VA: 0x75950530b4
	public Int32 get_population() { }
	// RVA: 0x2a39fc4 VA: 0x7595051fc4
	public ProfessionCategory get_profession() { }
	// RVA: 0x2a3b12c VA: 0x759505312c
	public List`1 get_professionList() { }
	// RVA: 0x2a3b1bc VA: 0x75950531bc
	public ProfessionCategory get_activeProfession() { }
	// RVA: 0x2a3b234 VA: 0x7595053234
	public List`1 get_assistList() { }
	// RVA: 0x2a3a134 VA: 0x7595052134
	public Void LoadData(String topicId) { }
	// RVA: 0x2a3b338 VA: 0x7595053338
	private Boolean _TryGetCurrentPopulation(out Int32 population) { }
	// RVA: 0x2a3b43c VA: 0x759505343c
	private Boolean _TryGetPendingRecruitIndex(out String recruitIndex) { }
	// RVA: 0x2a3b58c VA: 0x759505358c
	public Void .ctor() { }
	// RVA: 0x2a3b60c VA: 0x759505360c
	private static Void .cctor() { }
}
```