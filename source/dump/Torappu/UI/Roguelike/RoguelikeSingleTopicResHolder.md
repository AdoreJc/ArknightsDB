# RoguelikeSingleTopicResHolder

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RoguelikeMapBossIconHolder _mapBossIconHolder`

- `RoguelikeMenu _menuPrefab`


## Methods

- `RoguelikeMapBossIconHolder GetBossIconHolder()`

- `RoguelikeMenu GetMenuPrefab()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSingleTopicResHolder : MonoBehaviour, IHotfixable
{
	private RoguelikeMapBossIconHolder _mapBossIconHolder; // 0x18
	private RoguelikeMenu _menuPrefab; // 0x20
	private static DelegateBridge __Hotfix0_GetBossIconHolder; // 0x0
	private static DelegateBridge __Hotfix0_GetMenuPrefab; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ab5f74 VA: 0x75950cdf74
	public RoguelikeMapBossIconHolder GetBossIconHolder() { }
	// RVA: 0x2aa8268 VA: 0x75950c0268
	public RoguelikeMenu GetMenuPrefab() { }
	// RVA: 0x2ab5fdc VA: 0x75950cdfdc
	public Void .ctor() { }
}
```