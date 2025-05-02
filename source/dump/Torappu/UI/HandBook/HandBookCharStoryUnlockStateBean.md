# HandBookCharStoryUnlockStateBean

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `CharacterIllustViewProperty _charIllustProperty`

- `String m_storyTitle`

- `String m_charName`


## Properties

- `String storyTitle`

- `String charName`


## Methods

- `String get_storyTitle()`

- `String get_charName()`

- `Void LoadData(String, String, List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookCharStoryUnlockStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	private CharacterIllustViewProperty _charIllustProperty; // 0x18
	private String m_storyTitle; // 0x20
	private String m_charName; // 0x28
	private List`1 m_itemList; // 0x30
	private static DelegateBridge __Hotfix0_get_storyTitle; // 0x0
	private static DelegateBridge __Hotfix0_get_charName; // 0x8
	private static DelegateBridge __Hotfix0_get_itemList; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String storyTitle { get; }
	public String charName { get; }
	public List`1 itemList { get; }

	// RVA: 0x2e9f5a8 VA: 0x75954b75a8
	public String get_storyTitle() { }
	// RVA: 0x2e9f610 VA: 0x75954b7610
	public String get_charName() { }
	// RVA: 0x2e9f974 VA: 0x75954b7974
	public List`1 get_itemList() { }
	// RVA: 0x2e9f09c VA: 0x75954b709c
	public Void LoadData(String charId, String storyTitle, List`1 itemModels) { }
	// RVA: 0x2e9fad0 VA: 0x75954b7ad0
	public Void .ctor() { }
}
```