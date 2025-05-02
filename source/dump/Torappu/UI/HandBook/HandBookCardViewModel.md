# HandBookCardViewModel

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `ProfessionCategory m_npcProfession`

- `CharQuery charQuery`

- `String displayNumber`

- `HandBookRank showRank`

- `Boolean getFlag`

- `Boolean isNPC`

- `String npcIllustId`

- `Boolean m_npcHasAudioInfo`

- `String m_npcId`

- `IllustNPCResType m_resType`

- `Int32 getConnectFlag`

- `String nickName`

- `String realName`

- `Int32 chrinstID`

- `Single favorPercent`

- `String powerId`

- `EvolvePhase maxEvolvePhase`

- `Int32 level`

- `Sprite <logoSprite>k__BackingField`


## Properties

- `String characterKey`

- `Boolean hasAudioInfo`

- `String npcId`

- `IllustNPCResType resType`

- `Sprite logoSprite`


## Methods

- `String get_characterKey()`

- `ProfessionCategory GetProfession()`

- `Void SetNPCProfession(ProfessionCategory)`

- `Boolean get_hasAudioInfo()`

- `Void set_hasAudioInfo(Boolean)`

- `String get_npcId()`

- `Void set_npcId(String)`

- `IllustNPCResType get_resType()`

- `Void set_resType(IllustNPCResType)`

- `Sprite get_logoSprite()`

- `Void set_logoSprite(Sprite)`

- `Void ReloadCharQuery()`

- `Void LoadNecessarySprites()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookCardViewModel : IHotfixable
{
	private ProfessionCategory m_npcProfession; // 0x10
	public CharQuery charQuery; // 0x18
	public String displayNumber; // 0x30
	public HandBookRank showRank; // 0x38
	public Boolean getFlag; // 0x3c
	public Boolean isNPC; // 0x3d
	public String npcIllustId; // 0x40
	private Boolean m_npcHasAudioInfo; // 0x48
	private String m_npcId; // 0x50
	private IllustNPCResType m_resType; // 0x58
	public Int32 getConnectFlag; // 0x5c
	public String nickName; // 0x60
	public String realName; // 0x68
	public Int32 chrinstID; // 0x70
	public Single favorPercent; // 0x74
	public String powerId; // 0x78
	public EvolvePhase maxEvolvePhase; // 0x80
	public Int32 level; // 0x84
	private Sprite <logoSprite>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_characterKey; // 0x0
	private static DelegateBridge __Hotfix0_GetProfession; // 0x8
	private static DelegateBridge __Hotfix0_SetNPCProfession; // 0x10
	private static DelegateBridge __Hotfix0_get_hasAudioInfo; // 0x18
	private static DelegateBridge __Hotfix0_set_hasAudioInfo; // 0x20
	private static DelegateBridge __Hotfix0_get_npcId; // 0x28
	private static DelegateBridge __Hotfix0_set_npcId; // 0x30
	private static DelegateBridge __Hotfix0_get_resType; // 0x38
	private static DelegateBridge __Hotfix0_set_resType; // 0x40
	private static DelegateBridge __Hotfix0_get_logoSprite; // 0x48
	private static DelegateBridge __Hotfix0_set_logoSprite; // 0x50
	private static DelegateBridge __Hotfix0_ReloadCharQuery; // 0x58
	private static DelegateBridge __Hotfix0_LoadNecessarySprites; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public String characterKey { get; }
	public Boolean hasAudioInfo { get; set; }
	public String npcId { get; set; }
	public IllustNPCResType resType { get; set; }
	public Sprite logoSprite { get; set; }

	// RVA: 0x2eb24a4 VA: 0x75954ca4a4
	public String get_characterKey() { }
	// RVA: 0x2eb80b0 VA: 0x75954d00b0
	public ProfessionCategory GetProfession() { }
	// RVA: 0x2eb819c VA: 0x75954d019c
	public Void SetNPCProfession(ProfessionCategory profession) { }
	// RVA: 0x2eb8218 VA: 0x75954d0218
	public Boolean get_hasAudioInfo() { }
	// RVA: 0x2eb8298 VA: 0x75954d0298
	public Void set_hasAudioInfo(Boolean value) { }
	// RVA: 0x2eb8318 VA: 0x75954d0318
	public String get_npcId() { }
	// RVA: 0x2eb83ac VA: 0x75954d03ac
	public Void set_npcId(String value) { }
	// RVA: 0x2eb8430 VA: 0x75954d0430
	public IllustNPCResType get_resType() { }
	// RVA: 0x2eb84a8 VA: 0x75954d04a8
	public Void set_resType(IllustNPCResType value) { }
	// RVA: 0x2eb8524 VA: 0x75954d0524
	public Sprite get_logoSprite() { }
	// RVA: 0x2eb858c VA: 0x75954d058c
	private Void set_logoSprite(Sprite value) { }
	// RVA: 0x2eb8610 VA: 0x75954d0610
	public Void ReloadCharQuery() { }
	// RVA: 0x2eb8760 VA: 0x75954d0760
	public Void LoadNecessarySprites() { }
	// RVA: 0x2eb8830 VA: 0x75954d0830
	public Void .ctor() { }
}
```