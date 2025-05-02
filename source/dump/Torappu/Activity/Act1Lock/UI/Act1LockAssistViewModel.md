# Act1LockAssistViewModel

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `String charId`

- `EvolvePhase evolvePhase`

- `Int32 level`

- `Int32 mainSkillLevel`

- `CharacterData charData`

- `Int32 m_skillSelectIndex`


## Properties

- `Int32 skillCount`

- `Boolean isSkillSelect`

- `Int32 skillSelectIndex`


## Methods

- `Int32 get_skillCount()`

- `Boolean get_isSkillSelect()`

- `Int32 get_skillSelectIndex()`

- `Void LoadData(SharedCharData)`

- `String GetSkillId(Int32)`

- `Void SetSkillSelected(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockAssistViewModel : IHotfixable
{
	public String charId; // 0x10
	public EvolvePhase evolvePhase; // 0x18
	public Int32 level; // 0x1c
	public Int32 mainSkillLevel; // 0x20
	public CharacterData charData; // 0x28
	private Int32 m_skillSelectIndex; // 0x30
	private static DelegateBridge __Hotfix0_get_skillCount; // 0x0
	private static DelegateBridge __Hotfix0_get_isSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_skillSelectIndex; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_GetSkillId; // 0x20
	private static DelegateBridge __Hotfix0_SetSkillSelected; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Int32 skillCount { get; }
	public Boolean isSkillSelect { get; }
	public Int32 skillSelectIndex { get; }

	// RVA: 0x33d46dc VA: 0x75959ec6dc
	public Int32 get_skillCount() { }
	// RVA: 0x33d4774 VA: 0x75959ec774
	public Boolean get_isSkillSelect() { }
	// RVA: 0x33d47f8 VA: 0x75959ec7f8
	public Int32 get_skillSelectIndex() { }
	// RVA: 0x33d4860 VA: 0x75959ec860
	public Void LoadData(SharedCharData assistData) { }
	// RVA: 0x33d4a10 VA: 0x75959eca10
	public String GetSkillId(Int32 index) { }
	// RVA: 0x33d4b40 VA: 0x75959ecb40
	public Void SetSkillSelected(Int32 index) { }
	// RVA: 0x33d4bbc VA: 0x75959ecbbc
	public Void .ctor() { }
}
```