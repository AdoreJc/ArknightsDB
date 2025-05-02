# ClimbTowerBackgroundController

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 m_cachedLayer`

- `Tween m_tween`


## Methods

- `Void Render(Int32)`

- `Void <Render>b__6_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerBackgroundController : MonoBehaviour, IHotfixable
{
	private const Int32 TOWER_MAX_LAYER; // 0x0
	private const Int32 TOWER_LAYER_INIT_POS; // 0x0
	private const Single TOWER_LAYER_OFFSET; // 0x0
	private const Single TOWER_LAYER_MOVE_DURATION; // 0x0
	private Int32 m_cachedLayer; // 0x18
	private Tween m_tween; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2c60678 VA: 0x7595278678
	public Void Render(Int32 layer) { }
	// RVA: 0x2c60850 VA: 0x7595278850
	public Void .ctor() { }
	// RVA: 0x2c608c0 VA: 0x75952788c0
	private Void <Render>b__6_0() { }
}
```