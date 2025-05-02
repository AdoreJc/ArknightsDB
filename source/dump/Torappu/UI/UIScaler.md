# UIScaler

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _scaleTarget`

- `Single _scale`


## Properties

- `RectTransform scaleTarget`

- `Single scale`


## Methods

- `Void set_onScalerChange(Action`1)`

- `RectTransform get_scaleTarget()`

- `Void set_scaleTarget(RectTransform)`

- `Single get_scale()`

- `Void set_scale(Single)`

- `Void TakeScaleRawValue()`

- `UIInfo _AchieveUIInfo(RectTransform)`

- `Void _ParseUIInfos(RectTransform)`

- `Void _ResetScale(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIScaler : MonoBehaviour
{
	private RectTransform _scaleTarget; // 0x18
	private List`1 _scaleInfo; // 0x20
	private Single _scale; // 0x28
	private Action`1 m_onScalerChange; // 0x30

	private Action`1 onScalerChange { get; set; }
	public RectTransform scaleTarget { get; set; }
	public Single scale { get; set; }

	// RVA: 0x2253ad8 VA: 0x759486bad8
	private Action`1 get_onScalerChange() { }
	// RVA: 0x2253ae0 VA: 0x759486bae0
	public Void set_onScalerChange(Action`1 value) { }
	// RVA: 0x2253b2c VA: 0x759486bb2c
	public RectTransform get_scaleTarget() { }
	// RVA: 0x2253bd4 VA: 0x759486bbd4
	public Void set_scaleTarget(RectTransform value) { }
	// RVA: 0x2253c74 VA: 0x759486bc74
	public Single get_scale() { }
	// RVA: 0x2253c7c VA: 0x759486bc7c
	public Void set_scale(Single value) { }
	// RVA: 0x2253bf0 VA: 0x759486bbf0
	public Void TakeScaleRawValue() { }
	// RVA: 0x22544a8 VA: 0x759486c4a8
	private UIInfo _AchieveUIInfo(RectTransform transform) { }
	// RVA: 0x2254324 VA: 0x759486c324
	private Void _ParseUIInfos(RectTransform transform) { }
	// RVA: 0x2253d24 VA: 0x759486bd24
	private Void _ResetScale(Single scale) { }
	// RVA: 0x2254808 VA: 0x759486c808
	public Void .ctor() { }
}
```