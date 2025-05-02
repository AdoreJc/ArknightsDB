# UITextAspects

**Namespace:** `Torappu.UI`


## Methods

- `Boolean _GetTextAndAssignedToTextToShow(Text, ref)`

- `Boolean _LoadTextFromDBById(String, out)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu.UI
public class UITextAspects : TextAspects, IHotfixable
{
	private static UITextAspects s_instance; // 0x0
	private static __XLua_Gen_Delegate117 __Hotfix0_ProcessTextToShow; // 0x8
	private static __XLua_Gen_Delegate118 __Hotfix0__GetTextAndAssignedToTextToShow; // 0x10
	private static __XLua_Gen_Delegate119 __Hotfix0_SetText; // 0x18
	private static __XLua_Gen_Delegate120 __Hotfix0__LoadTextFromDBById; // 0x20
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x28
	private static __XLua_Gen_Delegate4 __Hotfix0_BindToUGUI; // 0x30


	// RVA: 0x678c668 VA: 0x7598da4668
	public override Void ProcessTextToShow(Text text, ref String textToShow, ref Boolean textNotFound) { }
	// RVA: 0x678c764 VA: 0x7598da4764
	private Boolean _GetTextAndAssignedToTextToShow(Text text, ref String textToShow) { }
	// RVA: 0x678c9f4 VA: 0x7598da49f4
	public override Void SetText(Text text, String textToShow, String value, ref Boolean isVerticesDirty, ref Boolean isLayoutDirty) { }
	// RVA: 0x678c910 VA: 0x7598da4910
	private Boolean _LoadTextFromDBById(String textId, out String text) { }
	// RVA: 0x678cb60 VA: 0x7598da4b60
	private Void .ctor() { }
	// RVA: 0x678cbd8 VA: 0x7598da4bd8
	public static Void BindToUGUI() { }
}
```