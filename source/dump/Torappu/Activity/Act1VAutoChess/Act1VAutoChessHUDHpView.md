# Act1VAutoChessHUDHpView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Boolean m_fastMode`

- `Single m_percentAll`

- `Int32 m_dangerPos`


## Methods

- `Void Render(Single, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDHpView : MonoBehaviour, IHotfixable
{
	private const Int32 HUD_HP_ITEM_COUNT; // 0x0
	public const Int32 HUD_HP_PER_ITEM; // 0x0
	private List`1 _hpItems; // 0x18
	private Boolean m_fastMode; // 0x20
	private Single m_percentAll; // 0x24
	private Int32 m_dangerPos; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_GetHpMaxItemCount; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3378dbc VA: 0x7595990dbc
	public Void Render(Single hpPercent, Int32 hpMaxItemCount, Boolean fastMode) { }
	// RVA: 0x3378f40 VA: 0x7595990f40
	public static Int32 GetHpMaxItemCount(Int32 hpMax) { }
	// RVA: 0x3378fd4 VA: 0x7595990fd4
	public Void .ctor() { }
}
```