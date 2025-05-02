# HandBookVoiceLangViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `VoiceLangType selectedLangType`


## Properties

- `Int32 itemCount`


## Methods

- `Int32 get_itemCount()`

- `VoiceLangItem GetVoiceLangItem(Int32)`

- `Void InitData(VoiceLangType, VoiceLangData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookVoiceLangViewModel : IHotfixable
{
	public VoiceLangType selectedLangType; // 0x10
	private List`1 m_langItems; // 0x18
	private static DelegateBridge __Hotfix0_get_itemCount; // 0x0
	private static DelegateBridge __Hotfix0_GetVoiceLangItem; // 0x8
	private static DelegateBridge __Hotfix0_InitData; // 0x10
	private static DelegateBridge __Hotfix0__EnumVoiceLangType; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Int32 itemCount { get; }

	// RVA: 0x2eb7b84 VA: 0x75954cfb84
	public Int32 get_itemCount() { }
	// RVA: 0x2eb73cc VA: 0x75954cf3cc
	public VoiceLangItem GetVoiceLangItem(Int32 index) { }
	// RVA: 0x2ebdd30 VA: 0x75954d5d30
	public Void InitData(VoiceLangType voiceLangType, VoiceLangData voiceLangData) { }
	// RVA: 0x2ec0544 VA: 0x75954d8544
	private static VoiceLangType _EnumVoiceLangType(VoiceLangType type) { }
	// RVA: 0x2ebd928 VA: 0x75954d5928
	public Void .ctor() { }
}
```