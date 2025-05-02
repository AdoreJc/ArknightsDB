# LegionCharacterStatusManager

**Namespace:** `Torappu.Battle`


## Fields

- `LegionGameMode m_legionMode`

- `Int32 m_originMaxProfessionLevel`

- `Int32 m_originProfessionLevelAdd`


## Methods

- `Void Init(LegionGameMode)`

- `Void ResetCharStatusInfo(List`1)`

- `Int32 _GetCharLevelDefaultAddCnt(Character)`

- `Int32 GetStatusBuffMaxCnt(Character)`

- `Void ModifyProfessionBuffMaxCnt(Character, Int32, Boolean)`

- `Void ModifyProfessionBuffDefaultAddCnt(Character, Int32, Boolean)`

- `LegionCharacterStatus _GetOwnerStatus(UInt32)`

- `LegionCharacterStatus GetOwnerStatus(Character, Boolean)`

- `LegionCharacterStatus _GetOwnerStatusByKey(UInt32)`

- `Void OnCardRecycleClearStatus(UInt32)`

- `Void ReplaceCharacter(Character, Character)`

- `Void AddTargetProfessionLevelDirectly(ProfessionCategory, Character, Int32)`

- `Void TemporaryAddEachProfessionStatus(Character)`

- `Void FinishTemporaryProfessionStatus(Character)`

- `Void ClearTargetProfessionLevel(Character)`

- `Void RefreshTargetProfessionBuff(Character)`

- `Void KeepCharacterStatus(Character)`

- `Void MarkCharReturnToHandAndKeepStatues(Character, Boolean)`

- `String GetCharacterProfessionBuffInfo(Character)`

- `Int32 GetProfessionBuffNum(Character)`

- `Int32 GetStatusProfessionCnt(Character)`

- `Int32 GetSpecifiedProfessionStatusBuffCnt(Character, ProfessionCategory)`

- `LegionCharacterStatus _CreateCharacterStatus(Single)`

- `Void _RemoveCharacterStatus(UInt32)`

- `LegionCharacterStatus _AddTargetProfessionLevel(ProfessionCategory, Character, Character, Int32, Boolean)`

- `Void _RefreshLegionAbilityByName(Character, String)`

- `Void _RefreshUiCachedProfessionBuffStatus(LegionCharacterStatus, List`1)`

- `Void _LogProfessionBuffLevel(Character)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class LegionCharacterStatusManager : IHotfixable
{
	private readonly LegionCharacterStatus m_sharedStatus; // 0x10
	private readonly Dictionary`2 m_characterStateDict; // 0x18
	private readonly Queue`1 m_statusReusePool; // 0x20
	private readonly List`1 m_uiCachedProfessionStatusList; // 0x28
	private readonly Dictionary`2 m_uiCachedProfessionStatusDict; // 0x30
	private readonly Dictionary`2 m_charStatusInfoDict; // 0x38
	private LegionGameMode m_legionMode; // 0x40
	private Int32 m_originMaxProfessionLevel; // 0x48
	private Int32 m_originProfessionLevelAdd; // 0x4c
	private readonly StringBuilder m_buffInfoString; // 0x50
	private const String FORMAT_BUFF_INFO; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_ResetCharStatusInfo; // 0x8
	private static DelegateBridge __Hotfix0__GetCharLevelDefaultAddCnt; // 0x10
	private static DelegateBridge __Hotfix0_GetStatusBuffMaxCnt; // 0x18
	private static DelegateBridge __Hotfix0_ModifyProfessionBuffMaxCnt; // 0x20
	private static DelegateBridge __Hotfix0_ModifyProfessionBuffDefaultAddCnt; // 0x28
	private static DelegateBridge __Hotfix0__GetOwnerStatus; // 0x30
	private static DelegateBridge __Hotfix0_GetOwnerStatus; // 0x38
	private static DelegateBridge __Hotfix0__GetOwnerStatusByKey; // 0x40
	private static DelegateBridge __Hotfix0_OnCardRecycleClearStatus; // 0x48
	private static DelegateBridge __Hotfix0_ReplaceCharacter; // 0x50
	private static DelegateBridge __Hotfix0_AddTargetProfessionLevelDirectly; // 0x58
	private static DelegateBridge __Hotfix0_TemporaryAddEachProfessionStatus; // 0x60
	private static DelegateBridge __Hotfix0_FinishTemporaryProfessionStatus; // 0x68
	private static DelegateBridge __Hotfix0_ClearTargetProfessionLevel; // 0x70
	private static DelegateBridge __Hotfix0_RefreshTargetProfessionBuff; // 0x78
	private static DelegateBridge __Hotfix0_KeepCharacterStatus; // 0x80
	private static DelegateBridge __Hotfix0_MarkCharReturnToHandAndKeepStatues; // 0x88
	private static DelegateBridge __Hotfix0_GetCharacterProfessionBuffInfo; // 0x90
	private static DelegateBridge __Hotfix0_GetCharacterProfessionStatus; // 0x98
	private static DelegateBridge __Hotfix0_GetCharacterProfessionStatusWithHighLight; // 0xa0
	private static DelegateBridge __Hotfix0_GetProfessionBuffNum; // 0xa8
	private static DelegateBridge __Hotfix0_GetStatusProfessionCnt; // 0xb0
	private static DelegateBridge __Hotfix0_GetSpecifiedProfessionStatusBuffCnt; // 0xb8
	private static DelegateBridge __Hotfix0__CreateCharacterStatus; // 0xc0
	private static DelegateBridge __Hotfix0__RemoveCharacterStatus; // 0xc8
	private static DelegateBridge __Hotfix0__AddTargetProfessionLevel; // 0xd0
	private static DelegateBridge __Hotfix0__RefreshLegionAbilityByName; // 0xd8
	private static DelegateBridge __Hotfix0__RefreshUiCachedProfessionBuffStatus; // 0xe0
	private static DelegateBridge __Hotfix0__LogProfessionBuffLevel; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0


	// RVA: 0x3fd6a28 VA: 0x75965eea28
	public Void Init(LegionGameMode legionMode) { }
	// RVA: 0x3fd6b30 VA: 0x75965eeb30
	public Void ResetCharStatusInfo(List`1 charDataList) { }
	// RVA: 0x3fd6d2c VA: 0x75965eed2c
	private Int32 _GetCharLevelDefaultAddCnt(Character character) { }
	// RVA: 0x3fd6e34 VA: 0x75965eee34
	public Int32 GetStatusBuffMaxCnt(Character character) { }
	// RVA: 0x3fd6f80 VA: 0x75965eef80
	public Void ModifyProfessionBuffMaxCnt(Character character, Int32 addValue, Boolean isReset) { }
	// RVA: 0x3fd7508 VA: 0x75965ef508
	public Void ModifyProfessionBuffDefaultAddCnt(Character character, Int32 addValue, Boolean isReset) { }
	// RVA: 0x3fd76b4 VA: 0x75965ef6b4
	private LegionCharacterStatus _GetOwnerStatus(UInt32 uid) { }
	// RVA: 0x3fd7164 VA: 0x75965ef164
	public LegionCharacterStatus GetOwnerStatus(Character character, Boolean initIfNull) { }
	// RVA: 0x3fd7890 VA: 0x75965ef890
	private LegionCharacterStatus _GetOwnerStatusByKey(UInt32 stateKey) { }
	// RVA: 0x3fd7970 VA: 0x75965ef970
	public Void OnCardRecycleClearStatus(UInt32 stateKey) { }
	// RVA: 0x3fd7c64 VA: 0x75965efc64
	public Void ReplaceCharacter(Character source, Character target) { }
	// RVA: 0x3fd818c VA: 0x75965f018c
	public Void AddTargetProfessionLevelDirectly(ProfessionCategory profession, Character target, Int32 levelCount) { }
	// RVA: 0x3fd85b4 VA: 0x75965f05b4
	public Void TemporaryAddEachProfessionStatus(Character target) { }
	// RVA: 0x3fd88dc VA: 0x75965f08dc
	public Void FinishTemporaryProfessionStatus(Character target) { }
	// RVA: 0x3fd8a7c VA: 0x75965f0a7c
	public Void ClearTargetProfessionLevel(Character character) { }
	// RVA: 0x3fd8b20 VA: 0x75965f0b20
	public Void RefreshTargetProfessionBuff(Character character) { }
	// RVA: 0x3fd8d24 VA: 0x75965f0d24
	public Void KeepCharacterStatus(Character source) { }
	// RVA: 0x3fd8dc4 VA: 0x75965f0dc4
	public Void MarkCharReturnToHandAndKeepStatues(Character source, Boolean isRedrawOnReplace) { }
	// RVA: 0x3fd8eb0 VA: 0x75965f0eb0
	public String GetCharacterProfessionBuffInfo(Character character) { }
	// RVA: 0x3fd93dc VA: 0x75965f13dc
	public List`1 GetCharacterProfessionStatus(UInt32 characterUid) { }
	// RVA: 0x3fd97ac VA: 0x75965f17ac
	public List`1 GetCharacterProfessionStatusWithHighLight(Character fromTarget, Character toTarget, List`1 hlList) { }
	// RVA: 0x3fd9bd0 VA: 0x75965f1bd0
	public Int32 GetProfessionBuffNum(Character character) { }
	// RVA: 0x3fd9ce8 VA: 0x75965f1ce8
	public Int32 GetStatusProfessionCnt(Character character) { }
	// RVA: 0x3fda0e8 VA: 0x75965f20e8
	public Int32 GetSpecifiedProfessionStatusBuffCnt(Character character, ProfessionCategory queryProfession) { }
	// RVA: 0x3fd7794 VA: 0x75965ef794
	private LegionCharacterStatus _CreateCharacterStatus(Single hatred) { }
	// RVA: 0x3fd7b2c VA: 0x75965efb2c
	private Void _RemoveCharacterStatus(UInt32 stateKey) { }
	// RVA: 0x3fd7ed0 VA: 0x75965efed0
	private LegionCharacterStatus _AddTargetProfessionLevel(ProfessionCategory profession, Character fromTarget, Character toTarget, Int32 levelCount, Boolean refreshDict) { }
	// RVA: 0x3fd8bdc VA: 0x75965f0bdc
	private Void _RefreshLegionAbilityByName(Character character, String abilityName) { }
	// RVA: 0x3fd9474 VA: 0x75965f1474
	private Void _RefreshUiCachedProfessionBuffStatus(LegionCharacterStatus status, List`1 refreshList) { }
	// RVA: 0x3fd8454 VA: 0x75965f0454
	private Void _LogProfessionBuffLevel(Character character) { }
	// RVA: 0x3fda9c8 VA: 0x75965f29c8
	public Void .ctor() { }
}
```