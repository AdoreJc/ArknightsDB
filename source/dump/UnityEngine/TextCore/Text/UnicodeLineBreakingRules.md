# UnicodeLineBreakingRules

**Namespace:** `UnityEngine.TextCore.Text`


## Fields

- `TextAsset m_UnicodeLineBreakingRules`

- `TextAsset m_LeadingCharacters`

- `TextAsset m_FollowingCharacters`

- `Boolean m_UseModernHangulLineBreakingRules`


## Dump
```C#
// Dll : UnityEngine.TextCoreTextEngineModule.dll
// Namespace : UnityEngine.TextCore.Text
public class UnicodeLineBreakingRules
{
	private static UnicodeLineBreakingRules s_Instance; // 0x0
	private TextAsset m_UnicodeLineBreakingRules; // 0x10
	private TextAsset m_LeadingCharacters; // 0x18
	private TextAsset m_FollowingCharacters; // 0x20
	private Boolean m_UseModernHangulLineBreakingRules; // 0x28
	private static HashSet`1 s_LeadingCharactersLookup; // 0x8
	private static HashSet`1 s_FollowingCharactersLookup; // 0x10

	internal HashSet`1 leadingCharactersLookup { get; }
	internal HashSet`1 followingCharactersLookup { get; }

	// RVA: 0x6910994 VA: 0x7598f28994
	internal HashSet`1 get_leadingCharactersLookup() { }
	// RVA: 0x6910a1c VA: 0x7598f28a1c
	internal HashSet`1 get_followingCharactersLookup() { }
	// RVA: 0x690dc5c VA: 0x7598f25c5c
	internal static Void LoadLineBreakingRules() { }
	// RVA: 0x6910aa4 VA: 0x7598f28aa4
	private static HashSet`1 GetCharacters(TextAsset file) { }
	// RVA: 0x690dc54 VA: 0x7598f25c54
	public Void .ctor() { }
	// RVA: 0x6910b8c VA: 0x7598f28b8c
	private static Void .cctor() { }
}
```