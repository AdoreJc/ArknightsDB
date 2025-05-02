# MainlineResHolder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Sprite _homeSprite`

- `Sprite _homeSpriteMulti`


## Methods

- `Sprite GetHomeSprite()`

- `Sprite GetHomeSpriteMutli()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class MainlineResHolder : MonoBehaviour, IHotfixable
{
	private Sprite _homeSprite; // 0x18
	private Sprite _homeSpriteMulti; // 0x20
	private static DelegateBridge __Hotfix0_GetHomeSprite; // 0x0
	private static DelegateBridge __Hotfix0_GetHomeSpriteMutli; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2f11d70 VA: 0x7595529d70
	public Sprite GetHomeSprite() { }
	// RVA: 0x2f11dd8 VA: 0x7595529dd8
	public Sprite GetHomeSpriteMutli() { }
	// RVA: 0x2f11e40 VA: 0x7595529e40
	public Void .ctor() { }
}
```