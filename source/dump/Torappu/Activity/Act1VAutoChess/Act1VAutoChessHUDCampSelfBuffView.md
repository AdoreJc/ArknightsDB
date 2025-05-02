# Act1VAutoChessHUDCampSelfBuffView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _buffNameText`

- `Text _buffDescText`

- `Image _buffDecoImage`

- `UIAnimationLocation _highlightAnimation`

- `Boolean m_hasInited`

- `ILoadAsset m_iLoadAsset`

- `AnimationWrapper m_highlightWrapper`

- `Tween m_highlightTween`

- `String m_decoIconId`


## Methods

- `Void Render(Act1VAutoChessHUDCampBuffViewModel, Boolean, Boolean)`

- `Void _InitIfNot()`

- `Void _SetHighlight()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessHUDCampSelfBuffView : MonoBehaviour, IHotfixable
{
	private Text _buffNameText; // 0x18
	private Text _buffDescText; // 0x20
	private Image _buffDecoImage; // 0x28
	private UIAnimationLocation _highlightAnimation; // 0x30
	private Boolean m_hasInited; // 0x40
	private ILoadAsset m_iLoadAsset; // 0x48
	private AnimationWrapper m_highlightWrapper; // 0x50
	private Tween m_highlightTween; // 0x58
	private String m_decoIconId; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__SetHighlight; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3367e50 VA: 0x759597fe50
	public Void Render(Act1VAutoChessHUDCampBuffViewModel model, Boolean setHighlight, Boolean fastMode) { }
	// RVA: 0x33680c8 VA: 0x75959800c8
	private Void _InitIfNot() { }
	// RVA: 0x33681b0 VA: 0x75959801b0
	private Void _SetHighlight() { }
	// RVA: 0x33682a4 VA: 0x75959802a4
	public Void .ctor() { }
}
```