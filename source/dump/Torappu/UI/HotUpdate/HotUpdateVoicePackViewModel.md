# HotUpdateVoicePackViewModel

**Namespace:** `Torappu.UI.HotUpdate`


## Fields

- `Int32 independentValidCount`

- `Int32 selectCount`

- `DisplayType displayType`

- `Int32 dependentItemIndex`


## Methods

- `Boolean IsTypeUnselectable(String)`

- `Boolean IsDisplayInSetting()`

- `Boolean IsDisplayInHotUpdate()`

- `Void UpdateSelectStatus(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HotUpdate
public class HotUpdateVoicePackViewModel : IHotfixable
{
	public List`1 itemViewModels; // 0x10
	public Int32 independentValidCount; // 0x18
	public Int32 selectCount; // 0x1c
	public DisplayType displayType; // 0x20
	private Int32 dependentItemIndex; // 0x24
	private static DelegateBridge __Hotfix0_Create; // 0x0
	private static DelegateBridge __Hotfix0__BuildDisplayTypeList; // 0x8
	private static DelegateBridge __Hotfix0__ConvertVoiceLangToResType; // 0x10
	private static DelegateBridge __Hotfix0_IsTypeUnselectable; // 0x18
	private static DelegateBridge __Hotfix0_IsDependentType; // 0x20
	private static DelegateBridge __Hotfix0_IsDisplayInSetting; // 0x28
	private static DelegateBridge __Hotfix0_IsDisplayInHotUpdate; // 0x30
	private static DelegateBridge __Hotfix0_UpdateSelectStatus; // 0x38
	private static DelegateBridge __Hotfix0_GetAllSelectVoiceResList; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x27cf42c VA: 0x7594de742c
	public static HotUpdateVoicePackViewModel Create(DisplayType displayType, Dictionary`2 packItemDict) { }
	// RVA: 0x27d08d4 VA: 0x7594de88d4
	private static List`1 _BuildDisplayTypeList() { }
	// RVA: 0x27d0c68 VA: 0x7594de8c68
	private static String _ConvertVoiceLangToResType(VoiceLangType voiceLang) { }
	// RVA: 0x27cfd7c VA: 0x7594de7d7c
	public Boolean IsTypeUnselectable(String voiceResType) { }
	// RVA: 0x27cfcf8 VA: 0x7594de7cf8
	public static Boolean IsDependentType(String voiceResType) { }
	// RVA: 0x27cfe18 VA: 0x7594de7e18
	public Boolean IsDisplayInSetting() { }
	// RVA: 0x27cfe88 VA: 0x7594de7e88
	public Boolean IsDisplayInHotUpdate() { }
	// RVA: 0x27cff88 VA: 0x7594de7f88
	public Void UpdateSelectStatus(Int32 index) { }
	// RVA: 0x27d01b4 VA: 0x7594de81b4
	public List`1 GetAllSelectVoiceResList() { }
	// RVA: 0x27d0808 VA: 0x7594de8808
	public Void .ctor() { }
}
```