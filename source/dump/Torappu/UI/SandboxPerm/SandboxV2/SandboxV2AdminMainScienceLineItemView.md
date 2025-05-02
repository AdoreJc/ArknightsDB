# SandboxV2AdminMainScienceLineItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainScienceLine _line`

- `GameObject _levelItem`

- `GameObject _levelItemBlock`

- `Text _levelTxt`

- `Transform _levelItemContainer`

- `Color _lineLockedColor`

- `Color _lineUnlockColor`

- `LineColorSwitchTween m_lineSwitchTween`

- `Boolean m_hasInited`


## Methods

- `Void Render(Vector2, Vector2, Boolean, SandboxV2DevelopmentLineStyle, Int32, Boolean)`

- `Void _InitIfNot()`

- `Vector2 _CalculateMiddlePoint(Vector2, Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceLineItemView : MonoBehaviour, IHotfixable
{
	private SandboxV2AdminMainScienceLine _line; // 0x18
	private GameObject _levelItem; // 0x20
	private GameObject _levelItemBlock; // 0x28
	private Text _levelTxt; // 0x30
	private Transform _levelItemContainer; // 0x38
	private Color _lineLockedColor; // 0x40
	private Color _lineUnlockColor; // 0x50
	private const Single LINE_X_OFFSET; // 0x0
	private LineColorSwitchTween m_lineSwitchTween; // 0x60
	private Boolean m_hasInited; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__CalculateMiddlePoint; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x24dfc64 VA: 0x7594af7c64
	public Void Render(Vector2 fromPos, Vector2 toPos, Boolean isUnlock, SandboxV2DevelopmentLineStyle style, Int32 level, Boolean isHalfLine) { }
	// RVA: 0x24e00f0 VA: 0x7594af80f0
	private Void _InitIfNot() { }
	// RVA: 0x24e01c0 VA: 0x7594af81c0
	private Vector2 _CalculateMiddlePoint(Vector2 start, Vector2 end) { }
	// RVA: 0x24e03ec VA: 0x7594af83ec
	public Void .ctor() { }
}
```