# LegionUICharacterStatusController

**Namespace:** `Torappu.Battle.Legion`


## Fields

- `UICharacterTabGroupAddtion _characterAddtionTabBuffDetail`

- `UIBattleLegionCharacterMenuPanel _perspectiveCharacterMenuPrefab`

- `Vector3 _dummyInReplaceOffset`

- `Boolean _dummyInReplacePlayAnim`

- `Single _dummyInReplaceAnimTimeScale`

- `Vector3 m_dummyPosition`

- `UIBattleLegionCharacterMenuPanel m_perspectiveCharacterPanel`

- `UICharacterTabGroupAddtion m_characterAddtionTabBuffDetail`

- `EasyInstancePool m_characterTabBuffDetailList`

- `LegionUIPlugin m_parentPlugin`

- `LegionGameMode m_manager`


## Methods

- `Void GatherEffects(List`1)`

- `Void OnInit(LegionUIPlugin)`

- `Void OnGameReady(UIController)`

- `Void PreloadAssets(Transform)`

- `Void OnUnitBorn(Unit)`

- `Void OnCardMenuShow(Card)`

- `Void OnCharacterMenuHide()`

- `Void OnCharacterMenuShow(Character)`

- `Void OnDummyTouchedToTile(Character, Tile)`

- `Void _ApplyCharacterInReplaceGraphicPosition(Character, Boolean)`

- `Void _ApplyCharacterInReplaceEffect(Character, Boolean)`

- `Void _RefreshCharacterBuffDetail(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Legion
public class LegionUICharacterStatusController : MonoBehaviour, IHotfixable, IEffectSource
{
	private UICharacterTabGroupAddtion _characterAddtionTabBuffDetail; // 0x18
	private UIBattleLegionCharacterMenuPanel _perspectiveCharacterMenuPrefab; // 0x20
	private Vector3 _dummyInReplaceOffset; // 0x28
	private Boolean _dummyInReplacePlayAnim; // 0x34
	private Single _dummyInReplaceAnimTimeScale; // 0x38
	private String[] _dummyInReplaceEffects; // 0x40
	private List`1 m_highLightProfessionList; // 0x48
	private Vector3 m_dummyPosition; // 0x50
	private Dictionary`2 m_cachedDummyOriginPos; // 0x60
	private List`1 m_dummyInReplaceEffects; // 0x68
	private UIBattleLegionCharacterMenuPanel m_perspectiveCharacterPanel; // 0x70
	private UICharacterTabGroupAddtion m_characterAddtionTabBuffDetail; // 0x78
	private EasyInstancePool m_characterTabBuffDetailList; // 0x80
	private LegionUIPlugin m_parentPlugin; // 0x88
	private LegionGameMode m_manager; // 0x90
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnGameReady; // 0x10
	private static DelegateBridge __Hotfix0_PreloadAssets; // 0x18
	private static DelegateBridge __Hotfix0_OnUnitBorn; // 0x20
	private static DelegateBridge __Hotfix0_OnCardMenuShow; // 0x28
	private static DelegateBridge __Hotfix0_OnCharacterMenuHide; // 0x30
	private static DelegateBridge __Hotfix0_OnCharacterMenuShow; // 0x38
	private static DelegateBridge __Hotfix0_OnDummyTouchedToTile; // 0x40
	private static DelegateBridge __Hotfix0__ApplyCharacterInReplaceGraphicPosition; // 0x48
	private static DelegateBridge __Hotfix0__ApplyCharacterInReplaceEffect; // 0x50
	private static DelegateBridge __Hotfix0__RefreshCharacterBuffDetail; // 0x58
	private static DelegateBridge __Hotfix0__GetCharacterProfessionStatus; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x1db3224 VA: 0x75943cb224
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1db32c4 VA: 0x75943cb2c4
	public Void OnInit(LegionUIPlugin plugin) { }
	// RVA: 0x1db3370 VA: 0x75943cb370
	public Void OnGameReady(UIController uiController) { }
	// RVA: 0x1db33fc VA: 0x75943cb3fc
	public Void PreloadAssets(Transform parent) { }
	// RVA: 0x1db3600 VA: 0x75943cb600
	public Void OnUnitBorn(Unit unit) { }
	// RVA: 0x1db39c8 VA: 0x75943cb9c8
	public Void OnCardMenuShow(Card card) { }
	// RVA: 0x1db3c70 VA: 0x75943cbc70
	public Void OnCharacterMenuHide() { }
	// RVA: 0x1db4194 VA: 0x75943cc194
	public Void OnCharacterMenuShow(Character character) { }
	// RVA: 0x1db4294 VA: 0x75943cc294
	public Void OnDummyTouchedToTile(Character character, Tile tile) { }
	// RVA: 0x1db36cc VA: 0x75943cb6cc
	private Void _ApplyCharacterInReplaceGraphicPosition(Character character, Boolean isReset) { }
	// RVA: 0x1db3cf4 VA: 0x75943cbcf4
	private Void _ApplyCharacterInReplaceEffect(Character character, Boolean isReset) { }
	// RVA: 0x1db3af8 VA: 0x75943cbaf8
	private Void _RefreshCharacterBuffDetail(List`1 statusList) { }
	// RVA: 0x1db3a6c VA: 0x75943cba6c
	private List`1 _GetCharacterProfessionStatus(UInt32 characterUid) { }
	// RVA: 0x1db473c VA: 0x75943cc73c
	public Void .ctor() { }
}
```