# RL02OuterBuffLineItemView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL02`


## Fields

- `RL02OuterBuffCurve _curve`

- `Color _curveLockedColor`

- `Color _curveUnlockColor`

- `Single _curveFadetime`

- `CurveColorSwitchTween m_curveSwitchTween`

- `Boolean m_hasInited`


## Methods

- `Void Render(PolarPoint, PolarPoint, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL02
public class RL02OuterBuffLineItemView : MonoBehaviour, IHotfixable
{
	private RL02OuterBuffCurve _curve; // 0x18
	private Color _curveLockedColor; // 0x20
	private Color _curveUnlockColor; // 0x30
	private Single _curveFadetime; // 0x40
	private CurveColorSwitchTween m_curveSwitchTween; // 0x48
	private Boolean m_hasInited; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26c101c VA: 0x7594cd901c
	public Void Render(PolarPoint fromPos, PolarPoint toPos, Boolean isUnlock) { }
	// RVA: 0x26c135c VA: 0x7594cd935c
	private Void _InitIfNot() { }
	// RVA: 0x26c14c0 VA: 0x7594cd94c0
	public Void .ctor() { }
}
```