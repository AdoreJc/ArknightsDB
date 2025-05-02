# SandboxV2ExpeditionCharSelectViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_expeditionId`

- `Boolean m_isValid`

- `Int32 m_minEliteRank`

- `Int32 m_duration`

- `Int32 m_drinkCost`

- `Int32 m_drinkObtain`

- `Int32 m_costAction`

- `Int32 m_actionObtain`

- `Int32 m_charCount`

- `ProfessionCategory m_profession`

- `ExpeditionOption m_expeditionOption`


## Properties

- `String expeditionId`

- `Boolean isValid`

- `Int32 minEliteRank`

- `Int32 duration`

- `Int32 drinkCost`

- `Int32 drinkObtain`

- `Int32 costAction`

- `Int32 actionObtain`

- `Int32 charCount`

- `ProfessionCategory profession`

- `ExpeditionOption expeditionOption`


## Methods

- `String get_expeditionId()`

- `Boolean get_isValid()`

- `Int32 get_minEliteRank()`

- `Int32 get_duration()`

- `Int32 get_drinkCost()`

- `Int32 get_drinkObtain()`

- `Int32 get_costAction()`

- `Int32 get_actionObtain()`

- `Int32 get_charCount()`

- `ProfessionCategory get_profession()`

- `ExpeditionOption get_expeditionOption()`

- `Void LoadData(String, ExpeditionOption)`

- `Void RefreshData(String, SandboxV2Data)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ExpeditionCharSelectViewModel : IHotfixable
{
	private String m_expeditionId; // 0x10
	private Boolean m_isValid; // 0x18
	private Int32 m_minEliteRank; // 0x1c
	private Int32 m_duration; // 0x20
	private Int32 m_drinkCost; // 0x24
	private Int32 m_drinkObtain; // 0x28
	private Int32 m_costAction; // 0x2c
	private Int32 m_actionObtain; // 0x30
	private Int32 m_charCount; // 0x34
	private ProfessionCategory m_profession; // 0x38
	private ExpeditionOption m_expeditionOption; // 0x40
	private static DelegateBridge __Hotfix0_get_expeditionId; // 0x0
	private static DelegateBridge __Hotfix0_get_isValid; // 0x8
	private static DelegateBridge __Hotfix0_get_minEliteRank; // 0x10
	private static DelegateBridge __Hotfix0_get_duration; // 0x18
	private static DelegateBridge __Hotfix0_get_drinkCost; // 0x20
	private static DelegateBridge __Hotfix0_get_drinkObtain; // 0x28
	private static DelegateBridge __Hotfix0_get_costAction; // 0x30
	private static DelegateBridge __Hotfix0_get_actionObtain; // 0x38
	private static DelegateBridge __Hotfix0_get_charCount; // 0x40
	private static DelegateBridge __Hotfix0_get_profession; // 0x48
	private static DelegateBridge __Hotfix0_get_expeditionOption; // 0x50
	private static DelegateBridge __Hotfix0_LoadData; // 0x58
	private static DelegateBridge __Hotfix0_RefreshData; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public String expeditionId { get; }
	public Boolean isValid { get; }
	public Int32 minEliteRank { get; }
	public Int32 duration { get; }
	public Int32 drinkCost { get; }
	public Int32 drinkObtain { get; }
	public Int32 costAction { get; }
	public Int32 actionObtain { get; }
	public Int32 charCount { get; }
	public ProfessionCategory profession { get; }
	public ExpeditionOption expeditionOption { get; }

	// RVA: 0x24b4be4 VA: 0x7594accbe4
	public String get_expeditionId() { }
	// RVA: 0x24b29fc VA: 0x7594aca9fc
	public Boolean get_isValid() { }
	// RVA: 0x24b2acc VA: 0x7594acaacc
	public Int32 get_minEliteRank() { }
	// RVA: 0x24b4c4c VA: 0x7594accc4c
	public Int32 get_duration() { }
	// RVA: 0x24b4cb4 VA: 0x7594acccb4
	public Int32 get_drinkCost() { }
	// RVA: 0x24b4d1c VA: 0x7594accd1c
	public Int32 get_drinkObtain() { }
	// RVA: 0x24b4d84 VA: 0x7594accd84
	public Int32 get_costAction() { }
	// RVA: 0x24b4dec VA: 0x7594accdec
	public Int32 get_actionObtain() { }
	// RVA: 0x24b4e54 VA: 0x7594acce54
	public Int32 get_charCount() { }
	// RVA: 0x24b2a64 VA: 0x7594acaa64
	public ProfessionCategory get_profession() { }
	// RVA: 0x24b4ebc VA: 0x7594accebc
	public ExpeditionOption get_expeditionOption() { }
	// RVA: 0x24b1f78 VA: 0x7594ac9f78
	public Void LoadData(String topicId, ExpeditionOption expeditionOption) { }
	// RVA: 0x24b3a20 VA: 0x7594acba20
	public Void RefreshData(String topicId, SandboxV2Data topicDetailData) { }
	// RVA: 0x24b1f08 VA: 0x7594ac9f08
	public Void .ctor() { }
}
```