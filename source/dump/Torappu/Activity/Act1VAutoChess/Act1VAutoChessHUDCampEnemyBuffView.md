# Act1VAutoChessHUDCampEnemyBuffView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _buffNameText`

- `Text _buffDescText`

- `Image _buffDecoImage`

- `Image _buffBg`

- `Color _normalBgColor`

- `Color _specialBgColor`

- `GameObject _panelSpecialOutline`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `String m_decoIconId`


## Methods

- `Void Render(Act1VAutoChessHUDCampBuffViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampEnemyBuffView : MonoBehaviour, IHotfixable
{
	private Text _buffNameText; // 0x18
	private Text _buffDescText; // 0x20
	private Image _buffDecoImage; // 0x28
	private Image _buffBg; // 0x30
	private Color _normalBgColor; // 0x38
	private Color _specialBgColor; // 0x48
	private GameObject _panelSpecialOutline; // 0x58
	private Boolean m_hasInited; // 0x60
	private ILoadAsset m_iLoadAsset; // 0x68
	private String m_decoIconId; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3366508 VA: 0x759597e508
	public Void Render(Act1VAutoChessHUDCampBuffViewModel model) { }
	// RVA: 0x3366808 VA: 0x759597e808
	private Void _InitIfNot() { }
	// RVA: 0x336691c VA: 0x759597e91c
	public Void .ctor() { }
}
```