# GrocerySellResultDiagramRingItem

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Image _ringImage`

- `Transform _ringRotateCenter`

- `Transform _ringTranverseRotateCenter`

- `TwoStateToggle _ringStyle`

- `Text _rankText`

- `Tween m_tween`


## Methods

- `Void SetRankText(Int32)`

- `Void SetStyleAndPlayTween(Single, Single, Boolean)`

- `Void ResetTweenAtBegin()`

- `Single <SetStyleAndPlayTween>b__10_0()`

- `Void <SetStyleAndPlayTween>b__10_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GrocerySellResultDiagramRingItem : MonoBehaviour, IHotfixable
{
	private static readonly Color PLAYER_RING_COLOR; // 0x0
	private static readonly Color NPC_RING_COLOR; // 0x10
	private const Single FILL_AMOUNT_TO_DEGREE; // 0x0
	private Image _ringImage; // 0x18
	private Transform _ringRotateCenter; // 0x20
	private Transform _ringTranverseRotateCenter; // 0x28
	private TwoStateToggle _ringStyle; // 0x30
	private Text _rankText; // 0x38
	private Tween m_tween; // 0x40
	private static DelegateBridge __Hotfix0_SetRankText; // 0x20
	private static DelegateBridge __Hotfix0_SetStyleAndPlayTween; // 0x28
	private static DelegateBridge __Hotfix0_ResetTweenAtBegin; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x28a1890 VA: 0x7594eb9890
	public Void SetRankText(Int32 rank) { }
	// RVA: 0x28a194c VA: 0x7594eb994c
	public Void SetStyleAndPlayTween(Single percent, Single duration, Boolean isPlayer) { }
	// RVA: 0x28a1be0 VA: 0x7594eb9be0
	public Void ResetTweenAtBegin() { }
	// RVA: 0x28a1cf0 VA: 0x7594eb9cf0
	public Void .ctor() { }
	// RVA: 0x28a1d70 VA: 0x7594eb9d70
	private static Void .cctor() { }
	// RVA: 0x28a1dd4 VA: 0x7594eb9dd4
	private Single <SetStyleAndPlayTween>b__10_0() { }
	// RVA: 0x28a1df0 VA: 0x7594eb9df0
	private Void <SetStyleAndPlayTween>b__10_1(Single value) { }
}
```