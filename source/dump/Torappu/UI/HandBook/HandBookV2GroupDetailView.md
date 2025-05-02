# HandBookV2GroupDetailView

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookV2MapLineView _lineView`

- `Transform _lineContainer`

- `HandBookV2MapCardView _cardView`

- `Transform _container`

- `UIHandBookCardEvent _clickEvent`

- `CanvasGroup _showDetailButton`

- `Boolean lockedFlag`

- `HandBookV2MapCardView m_centerView`


## Methods

- `Void Render(HandBookV2GroupCharViewModel, Vector3, Vector3)`

- `Void Render(HandBookV2MapCardView)`

- `Void Refresh(HandBookV2GroupCharViewModel)`

- `IEnumerator _ShowEffect()`

- `Void StartAnimate(HandBookV2MapCardView, HandBookV2GroupCharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookV2GroupDetailView : MonoBehaviour, IHotfixable
{
	private HandBookV2MapLineView _lineView; // 0x18
	private Transform _lineContainer; // 0x20
	private HandBookV2MapCardView _cardView; // 0x28
	private Transform _container; // 0x30
	private UIHandBookCardEvent _clickEvent; // 0x38
	private CanvasGroup _showDetailButton; // 0x40
	public Boolean lockedFlag; // 0x48
	private HandBookV2MapCardView m_centerView; // 0x50
	private Dictionary`2 m_handBookV2MapCardView; // 0x58
	private Dictionary`2 m_hideV2MapCardView; // 0x60
	private Dictionary`2 m_lineViewList; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix1_Render; // 0x8
	private static DelegateBridge __Hotfix0_Refresh; // 0x10
	private static DelegateBridge __Hotfix0__ShowEffect; // 0x18
	private static DelegateBridge __Hotfix0_StartAnimate; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2ec9d7c VA: 0x75954e1d7c
	public Void Render(HandBookV2GroupCharViewModel viewModel, Vector3 pos, Vector3 scale) { }
	// RVA: 0x2ec9b4c VA: 0x75954e1b4c
	public Void Render(HandBookV2MapCardView cardView) { }
	// RVA: 0x2eca088 VA: 0x75954e2088
	public Void Refresh(HandBookV2GroupCharViewModel viewModel) { }
	// RVA: 0x2ecc034 VA: 0x75954e4034
	private IEnumerator _ShowEffect() { }
	// RVA: 0x2ecb780 VA: 0x75954e3780
	public Void StartAnimate(HandBookV2MapCardView centerView, HandBookV2GroupCharViewModel viewModel) { }
	// RVA: 0x2ecc108 VA: 0x75954e4108
	public Void .ctor() { }
}
```