# CharSkinData

**Namespace:** `Torappu`


## Fields

- `String skinId`

- `String charId`

- `String m_illustId`

- `String m_dynIllustId`

- `String m_avatarId`

- `String m_portraitId`

- `String m_dynPortraitId`

- `String m_dynEntranceId`

- `String m_buildingId`

- `BattleSkin m_battleSkin`

- `Boolean m_isBuyAble`

- `String tmplId`

- `String voiceId`

- `SkinVoiceType voiceType`

- `DisplaySkin displaySkin`


## Properties

- `String FBOnly_illustId`

- `String FBOnly_dynIllustId`

- `String FBOnly_avatarId`

- `String FBOnly_portraitId`

- `String FBOnly_dynPortraitId`

- `String FBOnly_dynEntranceId`

- `String FBOnly_buildingId`

- `BattleSkin FBOnly_battleSkin`

- `Boolean FBOnly_isBuySkin`

- `Boolean isEmpty`


## Methods

- `String get_FBOnly_illustId()`

- `Void set_FBOnly_illustId(String)`

- `String get_FBOnly_dynIllustId()`

- `Void set_FBOnly_dynIllustId(String)`

- `String get_FBOnly_avatarId()`

- `Void set_FBOnly_avatarId(String)`

- `String get_FBOnly_portraitId()`

- `Void set_FBOnly_portraitId(String)`

- `String get_FBOnly_dynPortraitId()`

- `Void set_FBOnly_dynPortraitId(String)`

- `String get_FBOnly_dynEntranceId()`

- `Void set_FBOnly_dynEntranceId(String)`

- `String get_FBOnly_buildingId()`

- `Void set_FBOnly_buildingId(String)`

- `BattleSkin get_FBOnly_battleSkin()`

- `Void set_FBOnly_battleSkin(BattleSkin)`

- `Boolean get_FBOnly_isBuySkin()`

- `Void set_FBOnly_isBuySkin(Boolean)`

- `Boolean get_isEmpty()`

- `String GetIllustId()`

- `String GetDynIllustId()`

- `String GetDynPortraitId()`

- `String GetDynEntranceId()`

- `String GetIllustIdForBattle()`

- `String GetAvatarId()`

- `String GetPortraitId()`

- `String GetBuildingId()`

- `String GetBattlePrefabId()`

- `Boolean IsBuyAble()`

- `Boolean TryGetBattleSkin(out)`

- `Void AuditOnlyHookData(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class CharSkinData
{
	public static readonly CharSkinData EMPTY; // 0x0
	public String skinId; // 0x10
	public String charId; // 0x18
	public List`1 tokenSkinMap; // 0x20
	private String m_illustId; // 0x28
	private String m_dynIllustId; // 0x30
	private String m_avatarId; // 0x38
	private String m_portraitId; // 0x40
	private String m_dynPortraitId; // 0x48
	private String m_dynEntranceId; // 0x50
	private String m_buildingId; // 0x58
	private BattleSkin m_battleSkin; // 0x60
	private Boolean m_isBuyAble; // 0x70
	public String tmplId; // 0x78
	public String voiceId; // 0x80
	public SkinVoiceType voiceType; // 0x88
	public DisplaySkin displaySkin; // 0x90

	public String FBOnly_illustId { get; set; }
	public String FBOnly_dynIllustId { get; set; }
	public String FBOnly_avatarId { get; set; }
	public String FBOnly_portraitId { get; set; }
	public String FBOnly_dynPortraitId { get; set; }
	public String FBOnly_dynEntranceId { get; set; }
	public String FBOnly_buildingId { get; set; }
	public BattleSkin FBOnly_battleSkin { get; set; }
	public Boolean FBOnly_isBuySkin { get; set; }
	public Boolean isEmpty { get; }

	// RVA: 0x34f5d7c VA: 0x7595b0dd7c
	public String get_FBOnly_illustId() { }
	// RVA: 0x34f5d84 VA: 0x7595b0dd84
	public Void set_FBOnly_illustId(String value) { }
	// RVA: 0x34f5d8c VA: 0x7595b0dd8c
	public String get_FBOnly_dynIllustId() { }
	// RVA: 0x34f5d94 VA: 0x7595b0dd94
	public Void set_FBOnly_dynIllustId(String value) { }
	// RVA: 0x34f5d9c VA: 0x7595b0dd9c
	public String get_FBOnly_avatarId() { }
	// RVA: 0x34f5da4 VA: 0x7595b0dda4
	public Void set_FBOnly_avatarId(String value) { }
	// RVA: 0x34f5dac VA: 0x7595b0ddac
	public String get_FBOnly_portraitId() { }
	// RVA: 0x34f5db4 VA: 0x7595b0ddb4
	public Void set_FBOnly_portraitId(String value) { }
	// RVA: 0x34f5dbc VA: 0x7595b0ddbc
	public String get_FBOnly_dynPortraitId() { }
	// RVA: 0x34f5dc4 VA: 0x7595b0ddc4
	public Void set_FBOnly_dynPortraitId(String value) { }
	// RVA: 0x34f5dcc VA: 0x7595b0ddcc
	public String get_FBOnly_dynEntranceId() { }
	// RVA: 0x34f5dd4 VA: 0x7595b0ddd4
	public Void set_FBOnly_dynEntranceId(String value) { }
	// RVA: 0x34f5ddc VA: 0x7595b0dddc
	public String get_FBOnly_buildingId() { }
	// RVA: 0x34f5de4 VA: 0x7595b0dde4
	public Void set_FBOnly_buildingId(String value) { }
	// RVA: 0x34f5dec VA: 0x7595b0ddec
	public BattleSkin get_FBOnly_battleSkin() { }
	// RVA: 0x34f5df8 VA: 0x7595b0ddf8
	public Void set_FBOnly_battleSkin(BattleSkin value) { }
	// RVA: 0x34f5e08 VA: 0x7595b0de08
	public Boolean get_FBOnly_isBuySkin() { }
	// RVA: 0x34f5e10 VA: 0x7595b0de10
	public Void set_FBOnly_isBuySkin(Boolean value) { }
	// RVA: 0x34f5e1c VA: 0x7595b0de1c
	public Boolean get_isEmpty() { }
	// RVA: 0x34f5e28 VA: 0x7595b0de28
	public Void .ctor() { }
	// RVA: 0x34f5ea4 VA: 0x7595b0dea4
	public Void .ctor(String skinId, String charId, String illustId, String dynIllustId, String dynPortraitId, String dynEntranceId, String avatarId, String portraitId, Boolean isBuySkin, String buildingId, BattleSkin battleSkin, DisplaySkin displaySkin) { }
	// RVA: 0x34f60a4 VA: 0x7595b0e0a4
	public Void .ctor(String skinId, String charId, String illustId, String dynIllustId, String dynPortraitId, String dynEntranceId, String avatarId, String portraitId, Boolean isBuySkin, String buildingId, DisplaySkin displaySkin) { }
	// RVA: 0x34f5ee8 VA: 0x7595b0dee8
	public Void .ctor(String skinId, String charId, String illustId, String dynIllustId, String dynPortraitId, String dynEntranceId, String avatarId, String portraitId, Boolean isBuySkin, String buildingId, List`1 tokenSkinMap, BattleSkin battleSkin, DisplaySkin displaySkin) { }
	// RVA: 0x34f6244 VA: 0x7595b0e244
	public String GetIllustId() { }
	// RVA: 0x34f624c VA: 0x7595b0e24c
	public String GetDynIllustId() { }
	// RVA: 0x34f6254 VA: 0x7595b0e254
	public String GetDynPortraitId() { }
	// RVA: 0x34f625c VA: 0x7595b0e25c
	public String GetDynEntranceId() { }
	// RVA: 0x34f6264 VA: 0x7595b0e264
	public String GetIllustIdForBattle() { }
	// RVA: 0x34f62b0 VA: 0x7595b0e2b0
	public String GetAvatarId() { }
	// RVA: 0x34f62e0 VA: 0x7595b0e2e0
	public String GetPortraitId() { }
	// RVA: 0x34f62e8 VA: 0x7595b0e2e8
	public String GetBuildingId() { }
	// RVA: 0x34f6318 VA: 0x7595b0e318
	public String GetBattlePrefabId() { }
	// RVA: 0x34f63ac VA: 0x7595b0e3ac
	public Boolean IsBuyAble() { }
	// RVA: 0x34f63b4 VA: 0x7595b0e3b4
	public Boolean TryGetBattleSkin(out BattleSkin skin) { }
	// RVA: 0x34f6460 VA: 0x7595b0e460
	public Void AuditOnlyHookData(String illustId, String buildingId) { }
	// RVA: 0x34f61b8 VA: 0x7595b0e1b8
	public static Boolean IsTrapOrToken(String charId) { }
	// RVA: 0x34f6490 VA: 0x7595b0e490
	private static Void .cctor() { }
}
```