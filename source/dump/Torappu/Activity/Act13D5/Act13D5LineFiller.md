# Act13D5LineFiller

**Namespace:** `Torappu.Activity.Act13D5`


## Fields

- `RectMask2D _target`

- `Vector2 _size`

- `Single _fillAmount`

- `FillType _fillType`


## Properties

- `Single fillAmount`


## Methods

- `Single get_fillAmount()`

- `Void set_fillAmount(Single)`

- `Void _UpdateFillAmount()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13D5
public class Act13D5LineFiller : MonoBehaviour, IHotfixable
{
	private RectMask2D _target; // 0x18
	private Vector2 _size; // 0x20
	private Single _fillAmount; // 0x28
	private FillType _fillType; // 0x2c
	private static DelegateBridge __Hotfix0_get_fillAmount; // 0x0
	private static DelegateBridge __Hotfix0_set_fillAmount; // 0x8
	private static DelegateBridge __Hotfix0__UpdateFillAmount; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Single fillAmount { get; set; }

	// RVA: 0x34484a4 VA: 0x7595a604a4
	public Single get_fillAmount() { }
	// RVA: 0x344850c VA: 0x7595a6050c
	public Void set_fillAmount(Single value) { }
	// RVA: 0x344858c VA: 0x7595a6058c
	private Void _UpdateFillAmount() { }
	// RVA: 0x3448670 VA: 0x7595a60670
	public Void .ctor() { }
}
```