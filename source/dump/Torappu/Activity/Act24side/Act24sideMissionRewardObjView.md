# Act24sideMissionRewardObjView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideMeldingItemView _actItem`

- `Single _normItemScale`

- `RectTransform _containerAct`

- `RectTransform _containerNorm`

- `GameObject _normObj`

- `GameObject _completeFront`

- `Single _alpha`

- `CanvasGroup _normGroup`

- `CanvasGroup _actGroup`

- `Text _normItemNum`

- `UIItemCard m_normCard`

- `Act24sideMeldingItemView m_actCard`


## Methods

- `Void Render(UIItemViewModel, Boolean)`

- `Void Render(Act24sideMeldingItemViewModel, String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionRewardObjView : MonoBehaviour, IHotfixable
{
	private const Single FULL_ALPHA; // 0x0
	private Act24sideMeldingItemView _actItem; // 0x18
	private Single _normItemScale; // 0x20
	private RectTransform _containerAct; // 0x28
	private RectTransform _containerNorm; // 0x30
	private GameObject _normObj; // 0x38
	private GameObject _completeFront; // 0x40
	private Single _alpha; // 0x48
	private CanvasGroup _normGroup; // 0x50
	private CanvasGroup _actGroup; // 0x58
	private Text _normItemNum; // 0x60
	private UIItemCard m_normCard; // 0x68
	private Act24sideMeldingItemView m_actCard; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix1_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x32b98f4 VA: 0x75958d18f4
	public Void Render(UIItemViewModel itemViewModel, Boolean isComplete) { }
	// RVA: 0x32b9c54 VA: 0x75958d1c54
	public Void Render(Act24sideMeldingItemViewModel actItemViewModel, String actId, Boolean isComplete) { }
	// RVA: 0x32b9dfc VA: 0x75958d1dfc
	public Void .ctor() { }
}
```