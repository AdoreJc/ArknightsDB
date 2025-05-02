# FifthAnnivExploreValueView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `UIAtlasImage _contentImg`

- `UIAtlasImage _deltaImg`

- `RectTransform _contentTransform`

- `RectTransform _deltaTransform`

- `Text _contentNumText`

- `Text _deltaNumText`

- `Single m_contentScale`

- `Single m_deltaScale`


## Methods

- `Void _SetScaleWithTween(Single, Single)`

- `Void _RefreshScale()`

- `Single <_SetScaleWithTween>b__12_0()`

- `Void <_SetScaleWithTween>b__12_1(Single)`

- `Single <_SetScaleWithTween>b__12_2()`

- `Void <_SetScaleWithTween>b__12_3(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreValueView : FifthAnnivExploreValueAbstractView
{
	private const String NEGATIVE_DELTA_NUM_FORMAT; // 0x0
	private const String POSITIVE_DELTA_NUM_FORMAT; // 0x0
	private const Single TWEEN_DURATION; // 0x0
	private UIAtlasImage _contentImg; // 0x18
	private UIAtlasImage _deltaImg; // 0x20
	private RectTransform _contentTransform; // 0x28
	private RectTransform _deltaTransform; // 0x30
	private Text _contentNumText; // 0x38
	private Text _deltaNumText; // 0x40
	private Single m_contentScale; // 0x48
	private Single m_deltaScale; // 0x4c
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__SetScaleWithTween; // 0x8
	private static DelegateBridge __Hotfix0__RefreshScale; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x291d580 VA: 0x7594f35580
	public override Void Render(FifthAnnivExploreValueViewConfig config, FifthAnnivExploreValueViewModel viewModel, Boolean showNum) { }
	// RVA: 0x291d868 VA: 0x7594f35868
	private Void _SetScaleWithTween(Single contentScale, Single deltaScale) { }
	// RVA: 0x291db34 VA: 0x7594f35b34
	private Void _RefreshScale() { }
	// RVA: 0x291dc2c VA: 0x7594f35c2c
	public Void .ctor() { }
	// RVA: 0x291dc98 VA: 0x7594f35c98
	private Single <_SetScaleWithTween>b__12_0() { }
	// RVA: 0x291dca0 VA: 0x7594f35ca0
	private Void <_SetScaleWithTween>b__12_1(Single x) { }
	// RVA: 0x291dca8 VA: 0x7594f35ca8
	private Single <_SetScaleWithTween>b__12_2() { }
	// RVA: 0x291dcb0 VA: 0x7594f35cb0
	private Void <_SetScaleWithTween>b__12_3(Single x) { }
}
```