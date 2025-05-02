# CharWordDB

**Namespace:** `Torappu`


## Methods

- `Void _FilterAllTypesOfCharWordData(VoiceQuery, List`1)`

- `Boolean _CheckExtraVoiceLangValid(Dictionary`2, VoiceQuery, CharWordData)`

- `CharExtraWordData FindCharExWordData(String, String)`

- `Boolean GetVoiceLangDataByWordKey(String, out)`

- `Boolean CheckWordKeyVoiceLangValid(VoiceLangType, String)`

- `Boolean CheckCharVoiceLangValid(VoiceQuery)`

- `Boolean CheckCharRoleIsNew(String)`

- `String GetVoiceLangName(VoiceLangType)`

- `String GetVoiceLangGroupName(VoiceLangGroupType)`

- `VoiceLangType GetDefaultVoiceLangType()`

- `Boolean TryGetDefaultVoiceLangType(String, out)`

- `VoiceLangGroupType GetVoiceLangGroupTypeByType(VoiceLangType)`

- `Boolean CheckVoiceLangNeedDisplay(VoiceLangType)`

- `Boolean CheckVoiceGroupNeedDisplay(VoiceLangGroupType)`

- `String GetLinkageVoicePath(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharWordDB : ConstTable`2
{
	private Dictionary`2 m_showTypeSeachTable; // 0x60
	private Dictionary`2 m_voiceLangSearchTable; // 0x68
	private Dictionary`2 m_linkagePathTable; // 0x70
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_FliterCharWordData; // 0x8
	private static DelegateBridge __Hotfix0__FilterAllTypesOfCharWordData; // 0x10
	private static DelegateBridge __Hotfix0__CheckExtraVoiceLangValid; // 0x18
	private static DelegateBridge __Hotfix0_FilterCharWordData; // 0x20
	private static DelegateBridge __Hotfix0_ShowTypeSearchTable; // 0x28
	private static DelegateBridge __Hotfix0_FindCharExWordData; // 0x30
	private static DelegateBridge __Hotfix0_GetVoiceLangDataByWordKey; // 0x38
	private static DelegateBridge __Hotfix0_CheckWordKeyVoiceLangValid; // 0x40
	private static DelegateBridge __Hotfix0_CheckCharVoiceLangValid; // 0x48
	private static DelegateBridge __Hotfix0_CheckCharRoleIsNew; // 0x50
	private static DelegateBridge __Hotfix0_GetVoiceLangName; // 0x58
	private static DelegateBridge __Hotfix0_GetVoiceLangGroupName; // 0x60
	private static DelegateBridge __Hotfix0_GetDefaultVoiceLangType; // 0x68
	private static DelegateBridge __Hotfix0_TryGetDefaultVoiceLangType; // 0x70
	private static DelegateBridge __Hotfix0_GetVoiceLangGroupTypeByType; // 0x78
	private static DelegateBridge __Hotfix0_GetVoiceLangTypeListByGroupType; // 0x80
	private static DelegateBridge __Hotfix0_CheckVoiceLangNeedDisplay; // 0x88
	private static DelegateBridge __Hotfix0_CheckVoiceGroupNeedDisplay; // 0x90
	private static DelegateBridge __Hotfix0_GetLinkageVoicePath; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0


	// RVA: 0x31eaa50 VA: 0x7595802a50
	protected override Void OnInit() { }
	// RVA: 0x31eb0e0 VA: 0x75958030e0
	public List`1 FliterCharWordData(VoiceQuery query, CharWordShowType showType, List`1 resultBuffer) { }
	// RVA: 0x31eb47c VA: 0x759580347c
	private Void _FilterAllTypesOfCharWordData(VoiceQuery query, List`1 result) { }
	// RVA: 0x31eb7d0 VA: 0x75958037d0
	private Boolean _CheckExtraVoiceLangValid(Dictionary`2 extraVoiceData, VoiceQuery query, CharWordData charWord) { }
	// RVA: 0x31eb938 VA: 0x7595803938
	public List`1 FilterCharWordData(CharWordShowType showType, List`1 resultBuffer) { }
	// RVA: 0x31ebb34 VA: 0x7595803b34
	public Dictionary`2 ShowTypeSearchTable() { }
	// RVA: 0x31ebb9c VA: 0x7595803b9c
	public CharExtraWordData FindCharExWordData(String wordKey, String voiceId) { }
	// RVA: 0x31ebc94 VA: 0x7595803c94
	public Boolean GetVoiceLangDataByWordKey(String wordKey, out VoiceLangData voiceLangData) { }
	// RVA: 0x31ebd88 VA: 0x7595803d88
	public Boolean CheckWordKeyVoiceLangValid(VoiceLangType voiceLangType, String wordKey) { }
	// RVA: 0x31ebe74 VA: 0x7595803e74
	public Boolean CheckCharVoiceLangValid(VoiceQuery voiceQuery) { }
	// RVA: 0x31ebfdc VA: 0x7595803fdc
	public Boolean CheckCharRoleIsNew(String charId) { }
	// RVA: 0x31ec108 VA: 0x7595804108
	public String GetVoiceLangName(VoiceLangType voiceLangType) { }
	// RVA: 0x31ec204 VA: 0x7595804204
	public String GetVoiceLangGroupName(VoiceLangGroupType voiceLangGroupType) { }
	// RVA: 0x31ec2fc VA: 0x75958042fc
	public VoiceLangType GetDefaultVoiceLangType() { }
	// RVA: 0x31ec388 VA: 0x7595804388
	public Boolean TryGetDefaultVoiceLangType(String charId, out VoiceLangType defaultType) { }
	// RVA: 0x31ec47c VA: 0x759580447c
	public VoiceLangGroupType GetVoiceLangGroupTypeByType(VoiceLangType voiceLangType) { }
	// RVA: 0x31ec558 VA: 0x7595804558
	public List`1 GetVoiceLangTypeListByGroupType(VoiceLangGroupType groupType) { }
	// RVA: 0x31ec634 VA: 0x7595804634
	public Boolean CheckVoiceLangNeedDisplay(VoiceLangType voiceLangType) { }
	// RVA: 0x31ec738 VA: 0x7595804738
	public Boolean CheckVoiceGroupNeedDisplay(VoiceLangGroupType voiceLangGroupType) { }
	// RVA: 0x31ec83c VA: 0x759580483c
	public String GetLinkageVoicePath(String wordKey) { }
	// RVA: 0x31ec920 VA: 0x7595804920
	public Void .ctor() { }
}
```