# EmoticonConfig

**Namespace:** ` `


## Methods

- `String GetFocusEmoticonThemeId(ValueBundle)`

- `Void SaveSendEmoticonThemeId(ValueBundle, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EmoticonConfig : IEmoticonCustomConfig, IHotfixable
{
	private static DelegateBridge __Hotfix0_GetFocusEmoticonThemeId; // 0x0
	private static DelegateBridge __Hotfix0_SaveSendEmoticonThemeId; // 0x8
	private static DelegateBridge __Hotfix0_GetEnabledEmoticonList; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29847a8 VA: 0x7594f9c7a8
	public String GetFocusEmoticonThemeId(ValueBundle vb) { }
	// RVA: 0x29849fc VA: 0x7594f9c9fc
	public Void SaveSendEmoticonThemeId(ValueBundle vb, String themeId) { }
	// RVA: 0x2984948 VA: 0x7594f9c948
	public List`1 GetEnabledEmoticonList(ValueBundle vb) { }
	// RVA: 0x2984ae8 VA: 0x7594f9cae8
	public Void .ctor() { }
}
```