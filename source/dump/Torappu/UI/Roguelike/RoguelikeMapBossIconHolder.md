# RoguelikeMapBossIconHolder

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Boolean m_hasInit`


## Methods

- `Sprite GetIcon(String)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMapBossIconHolder : MonoBehaviour, IHotfixable
{
	private IconData[] _bossIconList; // 0x18
	private Dictionary`2 m_iconDict; // 0x20
	private Boolean m_hasInit; // 0x28
	private static DelegateBridge __Hotfix0_GetIcon; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2aeed04 VA: 0x7595106d04
	public Sprite GetIcon(String iconName) { }
	// RVA: 0x2aeee54 VA: 0x7595106e54
	private Void _InitIfNot() { }
	// RVA: 0x2aef004 VA: 0x7595107004
	public Void .ctor() { }
}
```