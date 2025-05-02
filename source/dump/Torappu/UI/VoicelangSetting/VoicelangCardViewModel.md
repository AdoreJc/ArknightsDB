# VoicelangCardViewModel

**Namespace:** `Torappu.UI.VoicelangSetting`


## Fields

- `String m_voicelangTypeName`

- `VoiceLangType m_voicelangType`

- `VoiceLangGroupType m_voicelangGroupType`

- `String m_wordKey`

- `String m_charId`

- `Int32 m_instId`

- `String m_skinId`

- `String m_name`

- `String m_portraitId`

- `String m_powerId`

- `Boolean m_highLight`

- `Boolean m_newRole`

- `Boolean m_newVoice`

- `Boolean m_redPoint`

- `VoiceLangType m_targetVoiceTypeToSwitch`

- `CardGroupFilterType m_filterType`

- `VoiceQuery m_voiceQuery`


## Properties

- `String voicelangTypeName`

- `VoiceLangType voicelangType`

- `VoiceLangGroupType voicelangGroupType`

- `String wordKey`

- `String charId`

- `Int32 instId`

- `String skinId`

- `String name`

- `String portraitId`

- `String powerId`

- `Boolean highLight`

- `Boolean newVoice`

- `Boolean newRole`

- `VoiceLangType targetVoiceTypeToSwitch`

- `CardGroupFilterType filterType`

- `Boolean showVoiceMark`

- `VoiceQuery voiceQuery`

- `Boolean redPoint`


## Methods

- `String get_voicelangTypeName()`

- `VoiceLangType get_voicelangType()`

- `Void set_voicelangType(VoiceLangType)`

- `VoiceLangGroupType get_voicelangGroupType()`

- `String get_wordKey()`

- `String get_charId()`

- `Int32 get_instId()`

- `String get_skinId()`

- `String get_name()`

- `String get_portraitId()`

- `String get_powerId()`

- `Boolean get_highLight()`

- `Void set_highLight(Boolean)`

- `Boolean get_newVoice()`

- `Boolean get_newRole()`

- `VoiceLangType get_targetVoiceTypeToSwitch()`

- `Void set_targetVoiceTypeToSwitch(VoiceLangType)`

- `CardGroupFilterType get_filterType()`

- `Void set_filterType(CardGroupFilterType)`

- `Boolean get_showVoiceMark()`

- `VoiceQuery get_voiceQuery()`

- `Void set_voiceQuery(VoiceQuery)`

- `Void set_displayTypeList(List`1)`

- `Boolean get_redPoint()`

- `Void set_redPoint(Boolean)`

- `Void FillViewModel(PlayerCharacter)`

- `Boolean RefreshRedPoint()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.VoicelangSetting
public class VoicelangCardViewModel : IHotfixable
{
	private String m_voicelangTypeName; // 0x10
	private VoiceLangType m_voicelangType; // 0x18
	private VoiceLangGroupType m_voicelangGroupType; // 0x1c
	private String m_wordKey; // 0x20
	private String m_charId; // 0x28
	private Int32 m_instId; // 0x30
	private String m_skinId; // 0x38
	private String m_name; // 0x40
	private String m_portraitId; // 0x48
	private String m_powerId; // 0x50
	private Boolean m_highLight; // 0x58
	private Boolean m_newRole; // 0x59
	private Boolean m_newVoice; // 0x5a
	private Boolean m_redPoint; // 0x5b
	private VoiceLangType m_targetVoiceTypeToSwitch; // 0x5c
	private CardGroupFilterType m_filterType; // 0x60
	private VoiceQuery m_voiceQuery; // 0x68
	private List`1 m_displayTypeList; // 0x88
	private static DelegateBridge __Hotfix0_get_voicelangTypeName; // 0x0
	private static DelegateBridge __Hotfix0_get_voicelangType; // 0x8
	private static DelegateBridge __Hotfix0_set_voicelangType; // 0x10
	private static DelegateBridge __Hotfix0_get_voicelangGroupType; // 0x18
	private static DelegateBridge __Hotfix0_get_wordKey; // 0x20
	private static DelegateBridge __Hotfix0_get_charId; // 0x28
	private static DelegateBridge __Hotfix0_get_instId; // 0x30
	private static DelegateBridge __Hotfix0_get_skinId; // 0x38
	private static DelegateBridge __Hotfix0_get_name; // 0x40
	private static DelegateBridge __Hotfix0_get_portraitId; // 0x48
	private static DelegateBridge __Hotfix0_get_powerId; // 0x50
	private static DelegateBridge __Hotfix0_get_highLight; // 0x58
	private static DelegateBridge __Hotfix0_set_highLight; // 0x60
	private static DelegateBridge __Hotfix0_get_newVoice; // 0x68
	private static DelegateBridge __Hotfix0_get_newRole; // 0x70
	private static DelegateBridge __Hotfix0_get_targetVoiceTypeToSwitch; // 0x78
	private static DelegateBridge __Hotfix0_set_targetVoiceTypeToSwitch; // 0x80
	private static DelegateBridge __Hotfix0_get_filterType; // 0x88
	private static DelegateBridge __Hotfix0_set_filterType; // 0x90
	private static DelegateBridge __Hotfix0_get_showVoiceMark; // 0x98
	private static DelegateBridge __Hotfix0_get_voiceQuery; // 0xa0
	private static DelegateBridge __Hotfix0_set_voiceQuery; // 0xa8
	private static DelegateBridge __Hotfix0_get_displayTypeList; // 0xb0
	private static DelegateBridge __Hotfix0_set_displayTypeList; // 0xb8
	private static DelegateBridge __Hotfix0_get_redPoint; // 0xc0
	private static DelegateBridge __Hotfix0_set_redPoint; // 0xc8
	private static DelegateBridge __Hotfix0_FillViewModel; // 0xd0
	private static DelegateBridge __Hotfix0_RefreshRedPoint; // 0xd8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe0

	public String voicelangTypeName { get; }
	public VoiceLangType voicelangType { get; set; }
	public VoiceLangGroupType voicelangGroupType { get; }
	public String wordKey { get; }
	public String charId { get; }
	public Int32 instId { get; }
	public String skinId { get; }
	public String name { get; }
	public String portraitId { get; }
	public String powerId { get; }
	public Boolean highLight { get; set; }
	public Boolean newVoice { get; }
	public Boolean newRole { get; }
	public VoiceLangType targetVoiceTypeToSwitch { get; set; }
	public CardGroupFilterType filterType { get; set; }
	public Boolean showVoiceMark { get; }
	public VoiceQuery voiceQuery { get; set; }
	public List`1 displayTypeList { get; set; }
	public Boolean redPoint { get; set; }

	// RVA: 0x229a818 VA: 0x75948b2818
	public String get_voicelangTypeName() { }
	// RVA: 0x2297ebc VA: 0x75948afebc
	public VoiceLangType get_voicelangType() { }
	// RVA: 0x2299834 VA: 0x75948b1834
	public Void set_voicelangType(VoiceLangType value) { }
	// RVA: 0x229a744 VA: 0x75948b2744
	public VoiceLangGroupType get_voicelangGroupType() { }
	// RVA: 0x229a880 VA: 0x75948b2880
	public String get_wordKey() { }
	// RVA: 0x2298708 VA: 0x75948b0708
	public String get_charId() { }
	// RVA: 0x2297f8c VA: 0x75948aff8c
	public Int32 get_instId() { }
	// RVA: 0x2297f24 VA: 0x75948aff24
	public String get_skinId() { }
	// RVA: 0x229a8e8 VA: 0x75948b28e8
	public String get_name() { }
	// RVA: 0x229a950 VA: 0x75948b2950
	public String get_portraitId() { }
	// RVA: 0x229a3d0 VA: 0x75948b23d0
	public String get_powerId() { }
	// RVA: 0x229a9b8 VA: 0x75948b29b8
	public Boolean get_highLight() { }
	// RVA: 0x2299504 VA: 0x75948b1504
	public Void set_highLight(Boolean value) { }
	// RVA: 0x229a05c VA: 0x75948b205c
	public Boolean get_newVoice() { }
	// RVA: 0x229a6dc VA: 0x75948b26dc
	public Boolean get_newRole() { }
	// RVA: 0x229aa20 VA: 0x75948b2a20
	public VoiceLangType get_targetVoiceTypeToSwitch() { }
	// RVA: 0x229a0c4 VA: 0x75948b20c4
	public Void set_targetVoiceTypeToSwitch(VoiceLangType value) { }
	// RVA: 0x229aa88 VA: 0x75948b2a88
	public CardGroupFilterType get_filterType() { }
	// RVA: 0x229a31c VA: 0x75948b231c
	public Void set_filterType(CardGroupFilterType value) { }
	// RVA: 0x229aaf0 VA: 0x75948b2af0
	public Boolean get_showVoiceMark() { }
	// RVA: 0x229ab80 VA: 0x75948b2b80
	public VoiceQuery get_voiceQuery() { }
	// RVA: 0x229ac0c VA: 0x75948b2c0c
	public Void set_voiceQuery(VoiceQuery value) { }
	// RVA: 0x229acb0 VA: 0x75948b2cb0
	public List`1 get_displayTypeList() { }
	// RVA: 0x229ad18 VA: 0x75948b2d18
	public Void set_displayTypeList(List`1 value) { }
	// RVA: 0x229ad9c VA: 0x75948b2d9c
	public Boolean get_redPoint() { }
	// RVA: 0x229ae04 VA: 0x75948b2e04
	public Void set_redPoint(Boolean value) { }
	// RVA: 0x229ae84 VA: 0x75948b2e84
	public Void FillViewModel(PlayerCharacter playerChar) { }
	// RVA: 0x2299a74 VA: 0x75948b1a74
	public Boolean RefreshRedPoint() { }
	// RVA: 0x229b448 VA: 0x75948b3448
	public Void .ctor() { }
}
```