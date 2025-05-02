# AudioAssetRefCollection

**Namespace:** `Torappu.Audio.Engine`


## Methods

- `Boolean CheckIfContains(AudioAsset)`

- `Void Reset()`

- `Void AddKey(String)`

- `Void ExportKeys(List`1)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.Audio.Engine
public class AudioAssetRefCollection : IHotfixable
{
	private String[] m_cachedKeys; // 0x10
	private Object[] m_cachedAssets; // 0x18
	private HashSet`1 m_keys; // 0x20
	private static __XLua_Gen_Delegate177 __Hotfix0_CheckIfContains; // 0x0
	private static __XLua_Gen_Delegate1 __Hotfix0_Reset; // 0x8
	private static __XLua_Gen_Delegate0 __Hotfix0_AddKey; // 0x10
	private static __XLua_Gen_Delegate0 __Hotfix0_ExportKeys; // 0x18
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x20


	// RVA: 0x67b8898 VA: 0x7598dd0898
	public Boolean CheckIfContains(AudioAsset asset) { }
	// RVA: 0x67b89fc VA: 0x7598dd09fc
	public Void Reset() { }
	// RVA: 0x67b8a8c VA: 0x7598dd0a8c
	public Void AddKey(String key) { }
	// RVA: 0x67b8b34 VA: 0x7598dd0b34
	public Void ExportKeys(List`1 keys) { }
	// RVA: 0x67b8c18 VA: 0x7598dd0c18
	public Void .ctor() { }
}
```