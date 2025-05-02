# ShadowController

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _autoAttachToGround`

- `Single _attachOffset`

- `Boolean _simplyUseTileHeight`

- `Boolean _enableAdvanced`

- `Boolean _alwaysUseSpineOffset`

- `SpriteRenderer _sprite`

- `Transform _graphic`

- `FaceSwitcher _faceSwitcher`

- `BoneFollower _boneToFollow`

- `Boolean _specialInit`

- `Boolean _simpleFollow`

- `Ease _easeType`

- `Tile m_currentTile`

- `Entity m_owner`

- `Single m_defaultAlpha`

- `Single m_curHeight`

- `Single m_attachOffset`

- `Boolean m_isInitialized`

- `CharacterAnimator m_characterAnimator`

- `Tween m_scaleTween`


## Properties

- `Boolean EnableAdvanced`


## Methods

- `Boolean get_EnableAdvanced()`

- `Void Reset(Entity)`

- `Void _InitIfNot()`

- `Void OnUpdate()`

- `Void MakeScaleTween(Single, Single)`

- `Void _AttachToGround()`

- `Void OnDestroy()`

- `Void _FinishTweenIfNotNull()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class ShadowController : MonoBehaviour, IHotfixable
{
	private Boolean _autoAttachToGround; // 0x18
	private Single _attachOffset; // 0x1c
	private Boolean _simplyUseTileHeight; // 0x20
	private Boolean _enableAdvanced; // 0x21
	private Boolean _alwaysUseSpineOffset; // 0x22
	private SpriteRenderer _sprite; // 0x28
	private Transform _graphic; // 0x30
	private FaceSwitcher _faceSwitcher; // 0x38
	private BoneFollower _boneToFollow; // 0x40
	private Boolean _specialInit; // 0x48
	private Boolean _simpleFollow; // 0x49
	private Ease _easeType; // 0x4c
	private Tile m_currentTile; // 0x50
	private Entity m_owner; // 0x58
	private Single m_defaultAlpha; // 0x60
	private Single m_curHeight; // 0x64
	private Single m_attachOffset; // 0x68
	private Boolean m_isInitialized; // 0x6c
	private CharacterAnimator m_characterAnimator; // 0x70
	private Tween m_scaleTween; // 0x78
	private static DelegateBridge __Hotfix0_get_EnableAdvanced; // 0x0
	private static DelegateBridge __Hotfix0_Reset; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x18
	private static DelegateBridge __Hotfix0_MakeScaleTween; // 0x20
	private static DelegateBridge __Hotfix0__AttachToGround; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge __Hotfix0__FinishTweenIfNotNull; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean EnableAdvanced { get; }

	// RVA: 0x1c53dbc VA: 0x759426bdbc
	private Boolean get_EnableAdvanced() { }
	// RVA: 0x1c53e24 VA: 0x759426be24
	public Void Reset(Entity owner) { }
	// RVA: 0x1c53f38 VA: 0x759426bf38
	private Void _InitIfNot() { }
	// RVA: 0x1c54144 VA: 0x759426c144
	public Void OnUpdate() { }
	// RVA: 0x1c5488c VA: 0x759426c88c
	public Void MakeScaleTween(Single scale, Single duration) { }
	// RVA: 0x1c5454c VA: 0x759426c54c
	private Void _AttachToGround() { }
	// RVA: 0x1c54a34 VA: 0x759426ca34
	private Void OnDestroy() { }
	// RVA: 0x1c549a4 VA: 0x759426c9a4
	private Void _FinishTweenIfNotNull() { }
	// RVA: 0x1c54a9c VA: 0x759426ca9c
	public Void .ctor() { }
}
```