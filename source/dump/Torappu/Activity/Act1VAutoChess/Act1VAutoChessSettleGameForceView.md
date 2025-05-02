# Act1VAutoChessSettleGameForceView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Image _forceLogoImage`

- `Text _forceRestHealthText`

- `Text _forceEngagingCountText`

- `Color _forceStandColor`

- `Color _forceKnockOutColor`

- `GameObject _forceKnockOutPanel`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `String m_cachedLogoId`


## Methods

- `Void Render(ForceViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessSettleGameForceView : MonoBehaviour, IHotfixable
{
	private Image _forceLogoImage; // 0x18
	private Text _forceRestHealthText; // 0x20
	private Text _forceEngagingCountText; // 0x28
	private Color _forceStandColor; // 0x30
	private Color _forceKnockOutColor; // 0x40
	private GameObject _forceKnockOutPanel; // 0x50
	private Boolean m_hasInited; // 0x58
	private ILoadAsset m_iLoadAsset; // 0x60
	private String m_cachedLogoId; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3347ab8 VA: 0x759595fab8
	public Void Render(ForceViewModel model) { }
	// RVA: 0x3347cfc VA: 0x759595fcfc
	private Void _InitIfNot() { }
	// RVA: 0x3347da8 VA: 0x759595fda8
	public Void .ctor() { }
}
```