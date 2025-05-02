# CharacterDB

**Namespace:** `Torappu`


## Methods

- `Boolean ContainsKey(String)`

- `Boolean CharUtilOnlyTryGetValue(String, out)`

- `Boolean EditorTryGetValue(String, out)`

- `Boolean TryGetValue(String, out)`

- `CharacterData GetValueOrDefault(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharacterDB : SimpleKVTable`2
{
	private List`1 m_allCharacterIds; // 0x68
	private static DelegateBridge __Hotfix0_get_allCharacterIds; // 0x0
	private static DelegateBridge __Hotfix0_ContainsKey; // 0x8
	private static DelegateBridge __Hotfix0_CharUtilOnlyTryGetValue; // 0x10
	private static DelegateBridge __Hotfix0_OnInit; // 0x18
	private static DelegateBridge __Hotfix0_EditorTryGetValue; // 0x20
	private static DelegateBridge __Hotfix0_TryGetValue; // 0x28
	private static DelegateBridge __Hotfix0_GetValueOrDefault; // 0x30
	private static DelegateBridge __Hotfix0_GetValues; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public List`1 allCharacterIds { get; }

	// RVA: 0x31e9908 VA: 0x7595801908
	public List`1 get_allCharacterIds() { }
	// RVA: 0x31e9970 VA: 0x7595801970
	public Boolean ContainsKey(String key) { }
	// RVA: 0x31e9a2c VA: 0x7595801a2c
	public Boolean CharUtilOnlyTryGetValue(String charId, out CharacterData result) { }
	// RVA: 0x31e9af8 VA: 0x7595801af8
	protected override Void OnInit() { }
	// RVA: 0x31e9ce0 VA: 0x7595801ce0
	public Boolean EditorTryGetValue(String charId, out CharacterData result) { }
	// RVA: 0x31e9dac VA: 0x7595801dac
	public Boolean TryGetValue(String charId, out CharacterData result) { }
	// RVA: 0x31e9e84 VA: 0x7595801e84
	public CharacterData GetValueOrDefault(String charId) { }
	// RVA: 0x31e9f44 VA: 0x7595801f44
	public IList`1 GetValues(IList`1 keys) { }
	// RVA: 0x31e9fbc VA: 0x7595801fbc
	public Void .ctor() { }
}
```