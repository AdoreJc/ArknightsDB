# BattleFactory

**Namespace:** `Torappu.Battle`


## Fields

- `PreviewCursor _walkCursor`

- `PreviewCursor _flyCursor`

- `Transform _enemyFolder`

- `Transform _characterFolder`

- `Transform _miscFolder`

- `Transform _projectileFolder`

- `Transform _effectFolder`

- `Transform _mapWidgetFolder`

- `Transform _cameraFolder`


## Properties

- `Transform effectFolder`

- `Transform characterFolder`

- `Transform mapWidgetFolder`


## Methods

- `Transform get_effectFolder()`

- `Transform get_characterFolder()`

- `Transform get_mapWidgetFolder()`

- `CameraController CreateCamera(Boolean)`

- `Camera CreateCameraWithoutController(Transform)`

- `PreviewCursor CreatePreviewCursor(MotionMode)`

- `Enemy CreateEnemy(String)`

- `Character CreateCharacter(BattleCharacterData)`

- `Character CreateToken(BattleCharacterData)`

- `Boolean TouchCharacter(BattleCharacterData, Action`1)`

- `Boolean TouchToken(BattleCharacterData, Action`1)`

- `Projectile CreateProjectile(String)`

- `BasicSkill CreateSkill(String)`

- `UnitAnimator CreateSkin(SkinType, String, String, String)`

- `Effect CreateEffect(String)`

- `CameraEffect CreateCameraEffect(String)`

- `GlobalBuff CreateGlobalBuff(String)`

- `GlobalEnvSystem CreateGlobalEnvSystem(String)`

- `Tile CreateTile(String, Transform)`

- `BlockedEdge CreateBlockedEdge(String, Transform)`

- `Ability CreateDynamicAbility(String)`

- `Ability AttachEquipIfNot(String, Transform, String, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class BattleFactory : MonoBehaviour, ILuaCallCSharp, IHotfixable
{
	private PreviewCursor _walkCursor; // 0x18
	private PreviewCursor _flyCursor; // 0x20
	private Transform _enemyFolder; // 0x28
	private Transform _characterFolder; // 0x30
	private Transform _miscFolder; // 0x38
	private Transform _projectileFolder; // 0x40
	private Transform _effectFolder; // 0x48
	private Transform _mapWidgetFolder; // 0x50
	private Transform _cameraFolder; // 0x58
	private const String CAMERA_WITH_POSTPROCESS; // 0x0
	private const String CAMERA_WITHOUT_POSTPROCESS; // 0x0
	private const String CAMERA_PREFAB_WITH_POSTPROCESS; // 0x0
	private static DelegateBridge __Hotfix0_get_effectFolder; // 0x0
	private static DelegateBridge __Hotfix0_get_characterFolder; // 0x8
	private static DelegateBridge __Hotfix0_get_mapWidgetFolder; // 0x10
	private static DelegateBridge __Hotfix0_CreateCamera; // 0x18
	private static DelegateBridge __Hotfix0_CreateCameraWithoutController; // 0x20
	private static DelegateBridge __Hotfix0_CreatePreviewCursor; // 0x28
	private static DelegateBridge __Hotfix0_CreateEnemy; // 0x30
	private static DelegateBridge __Hotfix0_CreateCharacter; // 0x38
	private static DelegateBridge __Hotfix0_CreateToken; // 0x40
	private static DelegateBridge __Hotfix0_TouchCharacter; // 0x48
	private static DelegateBridge __Hotfix0_TouchToken; // 0x50
	private static DelegateBridge __Hotfix0_CreateProjectile; // 0x58
	private static DelegateBridge __Hotfix0_CreateSkill; // 0x60
	private static DelegateBridge __Hotfix0_CreateSkin; // 0x68
	private static DelegateBridge __Hotfix0_CreateEffect; // 0x70
	private static DelegateBridge __Hotfix0_CreateCameraEffect; // 0x78
	private static DelegateBridge __Hotfix0_CreateGlobalBuff; // 0x80
	private static DelegateBridge __Hotfix0_CreateGlobalEnvSystem; // 0x88
	private static DelegateBridge __Hotfix0_CreateTile; // 0x90
	private static DelegateBridge __Hotfix0_CreateBlockedEdge; // 0x98
	private static DelegateBridge __Hotfix0_CreateDynamicAbility; // 0xa0
	private static DelegateBridge __Hotfix0_AttachEquipIfNot; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public Transform effectFolder { get; }
	public Transform characterFolder { get; }
	public Transform mapWidgetFolder { get; }

	// RVA: 0x40bd61c VA: 0x75966d561c
	public Transform get_effectFolder() { }
	// RVA: 0x40bd684 VA: 0x75966d5684
	public Transform get_characterFolder() { }
	// RVA: 0x40bd6ec VA: 0x75966d56ec
	public Transform get_mapWidgetFolder() { }
	// RVA: 0x40bd798 VA: 0x75966d5798
	public CameraController CreateCamera(Boolean needPostprocess) { }
	// RVA: 0x40bd9e0 VA: 0x75966d59e0
	public Camera CreateCameraWithoutController(Transform controllerOffset) { }
	// RVA: 0x40bdb94 VA: 0x75966d5b94
	public PreviewCursor CreatePreviewCursor(MotionMode motionMode) { }
	// RVA: 0x40bdde0 VA: 0x75966d5de0
	public Enemy CreateEnemy(String enemyKey) { }
	// RVA: 0x40bdfe4 VA: 0x75966d5fe4
	public Character CreateCharacter(BattleCharacterData data) { }
	// RVA: 0x40be1f4 VA: 0x75966d61f4
	public Character CreateToken(BattleCharacterData data) { }
	// RVA: 0x40be404 VA: 0x75966d6404
	public Boolean TouchCharacter(BattleCharacterData data, Action`1 cb) { }
	// RVA: 0x40be568 VA: 0x75966d6568
	public Boolean TouchToken(BattleCharacterData data, Action`1 cb) { }
	// RVA: 0x40be6cc VA: 0x75966d66cc
	public Projectile CreateProjectile(String projectileKey) { }
	// RVA: 0x40be8d0 VA: 0x75966d68d0
	public BasicSkill CreateSkill(String skillKey) { }
	// RVA: 0x40bea50 VA: 0x75966d6a50
	public UnitAnimator CreateSkin(SkinType skinType, String skinId, String charId, String tmpId) { }
	// RVA: 0x40bedb0 VA: 0x75966d6db0
	public Effect CreateEffect(String effectKey) { }
	// RVA: 0x40bef5c VA: 0x75966d6f5c
	public CameraEffect CreateCameraEffect(String effectKey) { }
	// RVA: 0x40bf024 VA: 0x75966d7024
	public GlobalBuff CreateGlobalBuff(String globalBuffKey) { }
	// RVA: 0x40bf260 VA: 0x75966d7260
	public GlobalEnvSystem CreateGlobalEnvSystem(String envSystemKey) { }
	// RVA: 0x40bf408 VA: 0x75966d7408
	public Tile CreateTile(String tileKey, Transform container) { }
	// RVA: 0x40bf648 VA: 0x75966d7648
	public BlockedEdge CreateBlockedEdge(String edgeKey, Transform container) { }
	// RVA: 0x40bf818 VA: 0x75966d7818
	public Ability CreateDynamicAbility(String abilityKey) { }
	// RVA: 0x40bf998 VA: 0x75966d7998
	public Ability AttachEquipIfNot(String equipResKey, Transform parent, String equipKey, out String equipOriginName) { }
	// RVA: 0x40bfc48 VA: 0x75966d7c48
	public Void .ctor() { }
}
```