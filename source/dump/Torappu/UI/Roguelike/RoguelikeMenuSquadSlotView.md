# RoguelikeMenuSquadSlotView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `UIAtlasImage _slot`

- `UIAtlasObject _spriteObject`

- `String _spriteLockedName`

- `String _spriteUnlockedName`

- `SpriteRenderData m_spriteLocked`

- `SpriteRenderData m_spriteUnlocked`


## Properties

- `SpriteRenderData spriteLocked`

- `SpriteRenderData spriteUnlocked`


## Methods

- `SpriteRenderData get_spriteLocked()`

- `SpriteRenderData get_spriteUnlocked()`

- `Void Render(RoguelikeMenuSquadSlotViewModel, Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuSquadSlotView : MonoBehaviour, IHotfixable
{
	private static Color _colorLocked; // 0x0
	private static Color _colorEmpty; // 0x10
	private static Color _colorNonUpgraded; // 0x20
	private UIAtlasImage _slot; // 0x18
	private UIAtlasObject _spriteObject; // 0x20
	private String _spriteLockedName; // 0x28
	private String _spriteUnlockedName; // 0x30
	private SpriteRenderData m_spriteLocked; // 0x38
	private SpriteRenderData m_spriteUnlocked; // 0x60
	private static DelegateBridge __Hotfix0_get_spriteLocked; // 0x30
	private static DelegateBridge __Hotfix0_get_spriteUnlocked; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private SpriteRenderData spriteLocked { get; }
	private SpriteRenderData spriteUnlocked { get; }

	// RVA: 0x2a6b434 VA: 0x7595083434
	private SpriteRenderData get_spriteLocked() { }
	// RVA: 0x2a6b558 VA: 0x7595083558
	private SpriteRenderData get_spriteUnlocked() { }
	// RVA: 0x2a6a810 VA: 0x7595082810
	public Void Render(RoguelikeMenuSquadSlotViewModel model, Color colorUpgraded) { }
	// RVA: 0x2a6b67c VA: 0x759508367c
	public Void .ctor() { }
	// RVA: 0x2a6b76c VA: 0x759508376c
	private static Void .cctor() { }
}
```