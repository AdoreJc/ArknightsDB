# Act1VAutoChessSettleGameEquipItemView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _equipIconImage`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `String m_iconId`


## Methods

- `Void Render(EquipViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessSettleGameEquipItemView : MonoBehaviour, IHotfixable
{
	private Image _equipIconImage; // 0x18
	private Boolean m_hasInited; // 0x20
	private ILoadAsset m_iLoadAsset; // 0x28
	private String m_iconId; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x334779c VA: 0x759595f79c
	public Void Render(EquipViewModel model) { }
	// RVA: 0x3347964 VA: 0x759595f964
	private Void _InitIfNot() { }
	// RVA: 0x3347a10 VA: 0x759595fa10
	public Void .ctor() { }
}
```