# CrisisV2LongTermResHolder

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIAtlasObject _atlasObject`


## Methods

- `SpriteRenderData GetAchieveMapBkgSprite()`

- `SpriteRenderData GetAchieveTitleImgSprite()`

- `SpriteRenderData GetBattleFinishBgSprite()`

- `SpriteRenderData _SafeGetSprite(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2LongTermResHolder : MonoBehaviour, IHotfixable
{
	private UIAtlasObject _atlasObject; // 0x18
	private const String ACHIEVE_MAP_BKG; // 0x0
	private const String ACHIEVE_TITLE_IMG; // 0x0
	private const String BATTLE_FINISH_BKG; // 0x0
	private static DelegateBridge __Hotfix0_GetAchieveMapBkgSprite; // 0x0
	private static DelegateBridge __Hotfix0_GetAchieveTitleImgSprite; // 0x8
	private static DelegateBridge __Hotfix0_GetBattleFinishBgSprite; // 0x10
	private static DelegateBridge __Hotfix0__SafeGetSprite; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2bfa94c VA: 0x759521294c
	public SpriteRenderData GetAchieveMapBkgSprite() { }
	// RVA: 0x2bfaa00 VA: 0x7595212a00
	public SpriteRenderData GetAchieveTitleImgSprite() { }
	// RVA: 0x2c00edc VA: 0x7595218edc
	public SpriteRenderData GetBattleFinishBgSprite() { }
	// RVA: 0x2c00db0 VA: 0x7595218db0
	private SpriteRenderData _SafeGetSprite(String name) { }
	// RVA: 0x2c00f90 VA: 0x7595218f90
	public Void .ctor() { }
}
```