# I18nUtils

**Namespace:** `Torappu.I18N`


## Methods

- `Boolean _TryGetTextAndCheck(String, out)`

- `Void RegisterTextProvider(ITextProvider)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.I18N
public class I18nUtils : Singleton`1
{
	private HashSet`1 s_activeProviders; // 0x10
	private static __XLua_Gen_Delegate120 __Hotfix0__TryGetTextAndCheck; // 0x0
	private static __XLua_Gen_Delegate1 __Hotfix0__LogMissingTextId; // 0x8
	private static __XLua_Gen_Delegate0 __Hotfix0_RegisterTextProvider; // 0x10
	private static __XLua_Gen_Delegate174 __Hotfix0_TryGetText; // 0x18
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x20


	// RVA: 0x67b5414 VA: 0x7598dcd414
	private Boolean _TryGetTextAndCheck(String textId, out String text) { }
	// RVA: 0x67b567c VA: 0x7598dcd67c
	private static Void _LogMissingTextId(String textId) { }
	// RVA: 0x67b5768 VA: 0x7598dcd768
	public Void RegisterTextProvider(ITextProvider provider) { }
	// RVA: 0x67b5824 VA: 0x7598dcd824
	public static Boolean TryGetText(String textId, out String text) { }
	// RVA: 0x67b58d0 VA: 0x7598dcd8d0
	private Void .ctor() { }
}
```