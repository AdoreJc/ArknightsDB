# EmoticonLocalCache

**Namespace:** `Torappu.UI.Emoticon`


## Methods

- `Data _EnsureMemCacheData()`

- `Void _SaveData(Data)`

- `String GetEmoticonThemeLastGain()`

- `Void SetEmoticonThemeGain(String)`

- `Void ClearEmoticonThemeGain()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Emoticon
public class EmoticonLocalCache : Singleton`1
{
	private Data`1 m_memData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__EnsureMemCacheData; // 0x8
	private static DelegateBridge __Hotfix0__SaveData; // 0x10
	private static DelegateBridge __Hotfix0_CheckHasNewEmoticonTheme; // 0x18
	private static DelegateBridge __Hotfix0_GetEmoticonThemeLastGain; // 0x20
	private static DelegateBridge __Hotfix0_SetEmoticonThemeGain; // 0x28
	private static DelegateBridge __Hotfix0_ClearEmoticonThemeGain; // 0x30


	// RVA: 0x29b6974 VA: 0x7594fce974
	private Void .ctor() { }
	// RVA: 0x29b6a04 VA: 0x7594fcea04
	private Data _EnsureMemCacheData() { }
	// RVA: 0x29b6b68 VA: 0x7594fceb68
	private Void _SaveData(Data data) { }
	// RVA: 0x29b6c14 VA: 0x7594fcec14
	public static Boolean CheckHasNewEmoticonTheme() { }
	// RVA: 0x29b6ca8 VA: 0x7594fceca8
	public String GetEmoticonThemeLastGain() { }
	// RVA: 0x29b6d40 VA: 0x7594fced40
	public Void SetEmoticonThemeGain(String themeId) { }
	// RVA: 0x29b6dec VA: 0x7594fcedec
	public Void ClearEmoticonThemeGain() { }
}
```