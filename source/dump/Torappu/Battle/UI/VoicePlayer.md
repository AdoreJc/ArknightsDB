# VoicePlayer

**Namespace:** `Torappu.Battle.UI`


## Fields

- `BattleVoiceData m_data`

- `BattleCharacterData m_lastVocalCharData`

- `BattleVoiceOption m_lastPlayVoice`

- `Boolean m_encounterFirstEnemyFlag`

- `Boolean m_playPlaceVoiceForPredefined`

- `DefaultGamePlugin m_plugin`


## Properties

- `DefaultGamePlugin plugin`


## Methods

- `DefaultGamePlugin get_plugin()`

- `Void OnGameReset(BattleController)`

- `Void OnGameStart()`

- `Void OnGameInit(Options)`

- `Void OnGameReady()`

- `Void OnGameOver(GameResult)`

- `Void _OnPreviewCursorSpawn(Object)`

- `Void _OnUnitBorn(Object)`

- `Void _OnSkillCasted(Object)`

- `Void _OnTileClicked(Object)`

- `Void _OnCharacterAtkOrCbt(Object)`

- `Void _OnActivateInternalHiddenCard(Object)`

- `Boolean _CheckDisableBattleStartVoice()`

- `PlayResult _PlayVoice(BattleVoiceType)`

- `PlayResult _PlayVoice(BattleVoiceType, VoiceQuery, MapLayer)`

- `Int32 _FindCardDataIndex(String)`

- `BattleCharacterData _FindCardData(String)`

- `Void _RefreshCardDataList()`

- `Void _AttachPlugin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class VoicePlayer : IBattleModule, IHotfixable
{
	private const Int32 BATTLE_VOICE_TYPES_NUM; // 0x0
	private static readonly CharWordShowType[] SKILL_CHARWORD_TYPES; // 0x0
	private static readonly BattleVoiceType[] VOICE_TYPES_TO_SHARE_CD_WITH_ALL_OTHERS; // 0x8
	private BattleVoiceData m_data; // 0x10
	private BattleVoiceOption[] m_options; // 0x18
	private List`1 m_cardDataList; // 0x20
	private BattleCharacterData m_lastVocalCharData; // 0x28
	private Single[] m_nextPlayableTime; // 0x30
	private BattleVoiceOption m_lastPlayVoice; // 0x38
	private List`1 m_randomVoiceCache; // 0x50
	private Boolean m_encounterFirstEnemyFlag; // 0x58
	private Boolean m_playPlaceVoiceForPredefined; // 0x59
	private DefaultGamePlugin m_plugin; // 0x60
	private static DelegateBridge __Hotfix0_get_plugin; // 0x10
	private static DelegateBridge __Hotfix0_OnGameReset; // 0x18
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x20
	private static DelegateBridge __Hotfix0_OnGameInit; // 0x28
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x30
	private static DelegateBridge __Hotfix0_OnGameOver; // 0x38
	private static DelegateBridge __Hotfix0__OnPreviewCursorSpawn; // 0x40
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x48
	private static DelegateBridge __Hotfix0__OnSkillCasted; // 0x50
	private static DelegateBridge __Hotfix0__OnTileClicked; // 0x58
	private static DelegateBridge __Hotfix0__OnCharacterAtkOrCbt; // 0x60
	private static DelegateBridge __Hotfix0__OnActivateInternalHiddenCard; // 0x68
	private static DelegateBridge __Hotfix0__CheckDisableBattleStartVoice; // 0x70
	private static DelegateBridge __Hotfix0__PlayVoice; // 0x78
	private static DelegateBridge __Hotfix1__PlayVoice; // 0x80
	private static DelegateBridge __Hotfix0__FindCardDataIndex; // 0x88
	private static DelegateBridge __Hotfix0__FindCardData; // 0x90
	private static DelegateBridge __Hotfix0__RefreshCardDataList; // 0x98
	private static DelegateBridge __Hotfix0__LoadRandomVoiceList; // 0xa0
	private static DelegateBridge __Hotfix0__AttachPlugin; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	private DefaultGamePlugin plugin { get; }

	// RVA: 0x2088cd0 VA: 0x75946a0cd0
	private DefaultGamePlugin get_plugin() { }
	// RVA: 0x2088d90 VA: 0x75946a0d90
	public Void OnGameReset(BattleController controller) { }
	// RVA: 0x2089114 VA: 0x75946a1114
	public Void OnGameStart() { }
	// RVA: 0x2089394 VA: 0x75946a1394
	public Void OnGameInit(Options levelOptions) { }
	// RVA: 0x208999c VA: 0x75946a199c
	public Void OnGameReady() { }
	// RVA: 0x2089a10 VA: 0x75946a1a10
	public Void OnGameOver(GameResult result) { }
	// RVA: 0x2089a98 VA: 0x75946a1a98
	private Void _OnPreviewCursorSpawn(Object arg) { }
	// RVA: 0x208a78c VA: 0x75946a278c
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x208a95c VA: 0x75946a295c
	private Void _OnSkillCasted(Object arg) { }
	// RVA: 0x208ac0c VA: 0x75946a2c0c
	private Void _OnTileClicked(Object arg) { }
	// RVA: 0x208af38 VA: 0x75946a2f38
	private Void _OnCharacterAtkOrCbt(Object arg) { }
	// RVA: 0x208b098 VA: 0x75946a3098
	private Void _OnActivateInternalHiddenCard(Object arg) { }
	// RVA: 0x20891a8 VA: 0x75946a11a8
	private Boolean _CheckDisableBattleStartVoice() { }
	// RVA: 0x2089290 VA: 0x75946a1290
	private PlayResult _PlayVoice(BattleVoiceType voiceType) { }
	// RVA: 0x2089f98 VA: 0x75946a1f98
	private PlayResult _PlayVoice(BattleVoiceType voiceType, VoiceQuery vqOrEmpty, MapLayer mapLayer) { }
	// RVA: 0x2089e78 VA: 0x75946a1e78
	private Int32 _FindCardDataIndex(String charIdOrNull) { }
	// RVA: 0x208a6b8 VA: 0x75946a26b8
	private BattleCharacterData _FindCardData(String charIdOrNull) { }
	// RVA: 0x20897a0 VA: 0x75946a17a0
	private Void _RefreshCardDataList() { }
	// RVA: 0x208b240 VA: 0x75946a3240
	private List`1 _LoadRandomVoiceList() { }
	// RVA: 0x20895f8 VA: 0x75946a15f8
	private Void _AttachPlugin() { }
	// RVA: 0x208b494 VA: 0x75946a3494
	public Void .ctor() { }
	// RVA: 0x208b628 VA: 0x75946a3628
	private static Void .cctor() { }
}
```