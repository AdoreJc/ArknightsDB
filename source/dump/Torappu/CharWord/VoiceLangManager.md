# VoiceLangManager

**Namespace:** `Torappu.CharWord`


## Fields

- `HotUpdatePref m_hotupdatePrefCache`


## Methods

- `Boolean GetCharVoiceLangType(String, out)`

- `String GetVoicePathWithPlayerChar(ICharWordData)`

- `Boolean TryHookAudioByFxLang(VoiceQuery, String, Dictionary`2, out)`

- `Boolean GetCharLangTypeOrDefault(VoiceQuery, out)`

- `String GetVoicePathByType(ICharWordData, VoiceLangType, Boolean)`

- `Boolean GetCharDefaultVoiceLangType(String, String, out)`

- `Boolean CheckVoiceLangTypeValid(ICharWordData, VoiceLangType)`

- `Boolean CheckVoiceLangGroupResValid(VoiceLangGroupType)`

- `Boolean CheckVoiceLangTypeResValid(VoiceLangType)`

- `Boolean CheckWordKeyDisplay(String)`

- `Void LoadResValidPrevNearestTimeData(Int64, out, out)`

- `VoiceLangType GetGlobalVoiceLang()`

- `Void UpdateGlobalVoiceLangWithPlayerData()`

- `Void SetHotUpdatePref(HotUpdatePref)`

- `VoiceLangType GetVoiceLangTypeFromHotUpdatePref()`

- `Boolean ShouldSelectGlobalPref()`

- `Boolean IsCharNeedNewVoiceTrackPoint(String)`

- `Void SaveCharNewVoiceVisited(String)`

- `Void SaveCharsNewVoiceVisited(IEnumerator`1)`

- `Boolean IsCharWithTypeNeedNewTrackPoint(String, VoiceLangType)`

- `Void SaveCharWithTypeNewVisited(String, VoiceLangType)`

- `Void ConsumeCharsWithIgnoreTypeVisited()`

- `Void SaveCharsWithTypeNewVisited(IEnumerator`1)`

- `NewVoiceTimeData _GetPrevNearestTimeDataInList(List`1, Int64)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.CharWord
public class VoiceLangManager : Singleton`1
{
	private static readonly VoiceLangType[] I18N_PREF_ORDER; // 0x0
	private HotUpdatePref m_hotupdatePrefCache; // 0x10
	private static DelegateBridge __Hotfix0_EnumerateTypeWithI18NPrefOrder; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_GetCharVoiceLangType; // 0x18
	private static DelegateBridge __Hotfix0_GetVoicePathWithPlayerChar; // 0x20
	private static DelegateBridge __Hotfix0_TryHookAudioByFxLang; // 0x28
	private static DelegateBridge __Hotfix0_GetCharLangTypeOrDefault; // 0x30
	private static DelegateBridge __Hotfix0_GetVoicePathByType; // 0x38
	private static DelegateBridge __Hotfix0_GetCharDefaultVoiceLangType; // 0x40
	private static DelegateBridge __Hotfix0_CheckVoiceLangTypeValid; // 0x48
	private static DelegateBridge __Hotfix0_CheckVoiceLangGroupResValid; // 0x50
	private static DelegateBridge __Hotfix0_CheckVoiceLangTypeResValid; // 0x58
	private static DelegateBridge __Hotfix0_CheckWordKeyDisplay; // 0x60
	private static DelegateBridge __Hotfix0_LoadResValidPrevNearestTimeData; // 0x68
	private static DelegateBridge __Hotfix0_GetGlobalVoiceLang; // 0x70
	private static DelegateBridge __Hotfix0_UpdateGlobalVoiceLangWithPlayerData; // 0x78
	private static DelegateBridge __Hotfix0_SetHotUpdatePref; // 0x80
	private static DelegateBridge __Hotfix0_GetVoiceLangTypeFromHotUpdatePref; // 0x88
	private static DelegateBridge __Hotfix0__GetGlobalLangTypeFromPlayerPref; // 0x90
	private static DelegateBridge __Hotfix0__PrefToLangType; // 0x98
	private static DelegateBridge __Hotfix0_HotUpdatePrefToResType; // 0xa0
	private static DelegateBridge __Hotfix0_ShouldSelectGlobalPref; // 0xa8
	private static DelegateBridge __Hotfix0_IsCharNeedNewVoiceTrackPoint; // 0xb0
	private static DelegateBridge __Hotfix0_SaveCharNewVoiceVisited; // 0xb8
	private static DelegateBridge __Hotfix0_SaveCharsNewVoiceVisited; // 0xc0
	private static DelegateBridge __Hotfix0_IsCharWithTypeNeedNewTrackPoint; // 0xc8
	private static DelegateBridge __Hotfix0_SaveCharWithTypeNewVisited; // 0xd0
	private static DelegateBridge __Hotfix0_ConsumeCharsWithIgnoreTypeVisited; // 0xd8
	private static DelegateBridge __Hotfix0_SaveCharsWithTypeNewVisited; // 0xe0
	private static DelegateBridge __Hotfix0__GetVoicePath; // 0xe8
	private static DelegateBridge __Hotfix0__GetPrevNearestTimeDataInList; // 0xf0
	private static DelegateBridge __Hotfix0_GetVoicePathByGroupType; // 0xf8


	// RVA: 0x VA: 0x0
	public static IEnumerator`1 EnumerateTypeWithI18NPrefOrder(Func`2 convertFunc) { }
	// RVA: 0x37673a4 VA: 0x7595d7f3a4
	private Void .ctor() { }
	// RVA: 0x3767444 VA: 0x7595d7f444
	public Boolean GetCharVoiceLangType(String charId, out VoiceLangType voiceLangType) { }
	// RVA: 0x37675fc VA: 0x7595d7f5fc
	public String GetVoicePathWithPlayerChar(ICharWordData charWordData) { }
	// RVA: 0x37679d0 VA: 0x7595d7f9d0
	public Boolean TryHookAudioByFxLang(VoiceQuery voiceQuery, String eventName, Dictionary`2 soundFxVoiceLang, out String replacedSignal) { }
	// RVA: 0x3767c34 VA: 0x7595d7fc34
	public Boolean GetCharLangTypeOrDefault(VoiceQuery voiceQuery, out VoiceLangType voiceLangType) { }
	// RVA: 0x376773c VA: 0x7595d7f73c
	public String GetVoicePathByType(ICharWordData charWordData, VoiceLangType preferLangType, Boolean needDefault) { }
	// RVA: 0x3767d38 VA: 0x7595d7fd38
	public Boolean GetCharDefaultVoiceLangType(String charId, String wordKey, out VoiceLangType defaultVoiceLang) { }
	// RVA: 0x3768060 VA: 0x7595d80060
	public Boolean CheckVoiceLangTypeValid(ICharWordData charWordData, VoiceLangType voiceLangType) { }
	// RVA: 0x37681ac VA: 0x7595d801ac
	public Boolean CheckVoiceLangGroupResValid(VoiceLangGroupType groupType) { }
	// RVA: 0x3768260 VA: 0x7595d80260
	public Boolean CheckVoiceLangTypeResValid(VoiceLangType voiceLangType) { }
	// RVA: 0x3768334 VA: 0x7595d80334
	public Boolean CheckWordKeyDisplay(String wordKey) { }
	// RVA: 0x37685cc VA: 0x7595d805cc
	public Void LoadResValidPrevNearestTimeData(Int64 timestamp, out NewVoiceTimeData newVoiceTimeData, out Dictionary`2 newTypedVoiceTimeDataDict) { }
	// RVA: 0x3767f80 VA: 0x7595d7ff80
	public VoiceLangType GetGlobalVoiceLang() { }
	// RVA: 0x3768cb0 VA: 0x7595d80cb0
	public Void UpdateGlobalVoiceLangWithPlayerData() { }
	// RVA: 0x3768dc0 VA: 0x7595d80dc0
	public Void SetHotUpdatePref(HotUpdatePref pref) { }
	// RVA: 0x3768e4c VA: 0x7595d80e4c
	public VoiceLangType GetVoiceLangTypeFromHotUpdatePref() { }
	// RVA: 0x3768c24 VA: 0x7595d80c24
	private static VoiceLangType _GetGlobalLangTypeFromPlayerPref() { }
	// RVA: 0x3768b90 VA: 0x7595d80b90
	private static VoiceLangType _PrefToLangType(HotUpdatePref pref) { }
	// RVA: 0x3768ed8 VA: 0x7595d80ed8
	public static String HotUpdatePrefToResType(HotUpdatePref pref) { }
	// RVA: 0x3768ff0 VA: 0x7595d80ff0
	public Boolean ShouldSelectGlobalPref() { }
	// RVA: 0x3769120 VA: 0x7595d81120
	public Boolean IsCharNeedNewVoiceTrackPoint(String charId) { }
	// RVA: 0x37691ec VA: 0x7595d811ec
	public Void SaveCharNewVoiceVisited(String charId) { }
	// RVA: 0x37692b8 VA: 0x7595d812b8
	public Void SaveCharsNewVoiceVisited(IEnumerator`1 charIdIter) { }
	// RVA: 0x3769474 VA: 0x7595d81474
	public Boolean IsCharWithTypeNeedNewTrackPoint(String charId, VoiceLangType voiceLangType) { }
	// RVA: 0x3769564 VA: 0x7595d81564
	public Void SaveCharWithTypeNewVisited(String charId, VoiceLangType voiceLangType) { }
	// RVA: 0x37696a8 VA: 0x7595d816a8
	public Void ConsumeCharsWithIgnoreTypeVisited() { }
	// RVA: 0x3769784 VA: 0x7595d81784
	public Void SaveCharsWithTypeNewVisited(IEnumerator`1 charIdIter) { }
	// RVA: 0x3767e6c VA: 0x7595d7fe6c
	private static String _GetVoicePath(VoiceLangType langType, String wordKey, String voiceAsset) { }
	// RVA: 0x3768a7c VA: 0x7595d80a7c
	private NewVoiceTimeData _GetPrevNearestTimeDataInList(List`1 timeSortedList, Int64 timestamp) { }
	// RVA: 0x37699ac VA: 0x7595d819ac
	public static String GetVoicePathByGroupType(VoiceLangGroupType groupType, String wordKey, String voiceAsset) { }
	// RVA: 0x3769b40 VA: 0x7595d81b40
	private static Void .cctor() { }
}
```